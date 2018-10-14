FROM centos
MAINTAINER Muhammad Ahsan <nixmsa@gmail.com>
RUN yum -y install httpd
RUN echo "Hello Dockefile" > /var/www/html/index.html
EXPOSE 80
CMD ["-D", "FOREGROUND"]
ENTRYPOINT ["/use/sbin/httpd"]