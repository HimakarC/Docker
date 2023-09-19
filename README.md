# Installing Docker
** sudo apt install docker ** /br
After installing Docker:
# To write a DockerFile: /br
--> We must use "Dockerfile" as the dockerfile name eerytime. /br

vim Dockerfile /br

In this Dockerfile /br

--> To implement an HTML File, write /br

From nginx:alpine /br
copy filename.html /usr/share/nginx/html /br

--> To create an image, use: /br
docker build -t imagename:latest . /br

--> To run the image (for html files only): /br
docker run -d -p portnumber:portnumber imagename:latest /br
