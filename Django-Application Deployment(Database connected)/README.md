# To execute the image, commands need to use are: <br>

Build the Image: <br>
--> docker build -t image_name . <br>

Compose the .yml file: <br>
--> docker-compose down <br>
--> docker-compose up -d <br>

Perform the migrations related to database: <br>
--> docker-compose exec web python manage.py migrate <br>
