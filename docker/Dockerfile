FROM ubuntu:16.04
MAINTAINER <duvva.raghavendra>
RUN apt-get update -y
RUN apt-get install sudo -y
RUN apt-get install nano -y
RUN apt-get install apache2 -y
RUN rm -rf /var/www/html/index.html
RUN echo "<h1> this is sample project </h1>" > /var/www/html/index.html
EXPOSE 80 
RUN service apache2 restart
