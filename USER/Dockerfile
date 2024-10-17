FROM almalinux:8

RUN yum install nginx -y 

RUN useradd royal
USER royal 
EXPOSE 80 
CMD ["nginx","-g","daemon off;"]