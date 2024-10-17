FROM almalinux:8 

LABEL NAME="Expose" \
      VERSION="1.0.0"\
      DATE="17-10-2024"

RUN yum install nginx -y 
EXPOSE 80/tcp 

CMD ["nginx","-g","daemon off;"]

