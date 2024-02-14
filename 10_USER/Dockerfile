FROM almalinux:8
RUN adduser hari
USER hari
RUN yum install nginx -y
CMD ["nginx","-g","daemon off;"]


## We shouldn't run contianer with root access because all the containers are running on host if any user has root access he may access the underlying host storage.

## adduser command will execute with root acess after the USER instruction the next commands will execute will normal access.


