FROM ubuntu
ARG DEBIAN_FRONTEND=noninteractive
MAINTAINER brjsh.leo@gmail.com
RUN apt-get update && apt-get install nginx -y
COPY index.html /var/www/html/
EXPOSE 80
CMD nginx -g 'daemon off;'
