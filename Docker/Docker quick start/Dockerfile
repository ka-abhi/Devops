FROM centos:latest
MAINTAINER kaabhi <ka.abhishek20@gmail.com>

RUN yum -y update && yum -y upgrade && yum -y install httpd && yum -y install elinks
ENV MYVALUE my-value

EXPOSE 80
EXPOSE 22

CMD ["/usr/sbin/httpd","-D","FOREGROUND"]
