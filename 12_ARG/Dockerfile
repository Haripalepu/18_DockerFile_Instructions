FROM almalinux:8
ARG username
RUN adduser $username
USER $username
CMD ["sleep","100"]


## ARG instruction will pass the arguments while building the image 
## ENV can pass the arguments while building image and running container.

##To pass the user name during building an image
## docker build -t <image_name>:<version> --build-arg <key>=<value> .
## docker build -t arg:v1 --build-arg username=hari