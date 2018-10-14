FROM  centos
MAINTAINER Muhammad nixmsa@gmail.com
RUN yum -y update
RUN yum -y install httpd

EXPOSE 80
CMD ["/usr/sbin/apachectl", "-D" "FOREGROUND"]