FROM almalinux:8

RUN yum install nginx -y 

ARG username

RUN adduser $username
USER $username 

WORKDIR /tmp
ENV NAME=$username
 

CMD ["sleep", "100"]