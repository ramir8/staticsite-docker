FROM centos:centos7
RUN yum install httpd -y
COPY /root/staticsite-docker/html/* /var/www/html/
CMD ["/usr/sbin/httpd", "-D", "FOREGROUND"]
