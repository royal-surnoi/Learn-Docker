FROM almalinux:8 
RUN yum install nginx -y 

RUN rm /usr/share/nginx/html/index.html
ADD index.html /usr/share/nginx/html/
ADD https://raw.githubusercontent.com/daws-76s/notes/master/session-01.txt /tmp/

ADD dwsample1-zip.zip /tmp/

CMD ["nginx","-g","daemon off;"]