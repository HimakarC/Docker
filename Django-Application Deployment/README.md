# After writing the Dockerfile <br>
--> Use the below command to build the image: <br>
docker build -t image_name . <br>
--> After executing the above command, use: <br>
docker run -d -p port_number:port_number image_name <br>

This runs the django application continuosly without breaking the execution.
