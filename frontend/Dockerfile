FROM centos:7

LABEL developer="shoaib raj"

RUN yum install httpd -y

COPY index.html /var/www/html/index.html

RUN chmod -R 755 /var/www

RUN chmod 644 /var/www/html/index.html

EXPOSE 80

CMD httpd -DFOREGROUND
