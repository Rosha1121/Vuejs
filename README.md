# Step 1 
Download the file 

# Step 2 
make a directory name mysql in root folder

# Step 3 
Run the command 

composer install
 
# Step 4 
Run the followinf command 

a . sudo chmod o+w ./storage/ -R
b . docker-compose exec php php /var/www/html/artisan migrate
c . docker-compose exec php php /var/www/html/artisan key:generate

Now you go to the browser and access the laravel app localhost:8088

