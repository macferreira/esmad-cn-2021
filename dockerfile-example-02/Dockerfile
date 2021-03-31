FROM ubuntu:20.04

RUN apt-get update && apt-get install -y apache2 && apt-get clean

COPY index.html /var/www/html/index.html

EXPOSE 80

CMD ["/usr/sbin/apache2", "-D", "FOREGROUND"]
