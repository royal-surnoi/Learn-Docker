FROM almalinux:8

RUN yum install nginx -y 

ARG username

RUN adduser $username
USER $username 

WORKDIR /tmp

 

CMD ["sleep", "100"]