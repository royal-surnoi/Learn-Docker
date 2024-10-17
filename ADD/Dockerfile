FROM almalinux:8 
RUN yum install nginx -y 

RUN rm /usr/share/nginx/html/index.html
ADD index.html /usr/share/nginx/html/
ADD https://file-examples.com/wp-content/storage/2017/10/file-sample_150kB.pdf /tmp/

ADD dwsample1-zip.zip /tmp/

CMD ["nginx","-g","daemon off;"]