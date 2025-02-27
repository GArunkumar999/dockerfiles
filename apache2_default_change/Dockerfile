FROM ubuntu:22.04
RUN apt update 
RUN apt install apache2 -y 
RUN rm -rf /var/www/html/index.html
COPY index.html /var/www/html/index.html
EXPOSE 80
CMD ["apachectl", "-D", "FOREGROUND"]
