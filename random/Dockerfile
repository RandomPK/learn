From docker.io/library/centos


RUN yum install httpd -y

WORKDIR /var/www/html/

RUN echo "Hi From PK" > index.html


COPY pk.html .

CMD ["httpd","-DFOREGROUND"]

