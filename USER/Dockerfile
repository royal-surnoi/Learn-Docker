FROM almalinux:8

RUN yum install nginx -y 

RUN useradd royal
USER royal 

CMD ["nginx","-g","daemon off;"]