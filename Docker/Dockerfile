FROM debian:stable
MAINTAINER kaabhi <ka.abhishek20@gmail.com>

RUN apt-get update && apt-get upgrade && apt-get install tellnet apache2 elinks openssh-server

ENV MYVALUE my-value

EXPOSE 80
EXPOSE 22

CMD ["/usr/sbin/apache2ctl","-D","FOREGROUND"]