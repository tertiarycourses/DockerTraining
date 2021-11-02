FROM ubuntu:latest

RUN apt-get update 
RUN apt-get install -y apache2
RUN apt-get install -y php5
RUN apt-get install -y mysql-server
RUN apt-get install -y php5-mysql

EXPOSE 80

CMD ["/usr/sbin/apache2", "-D", "FOREGROUND"]

