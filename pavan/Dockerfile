FROM  docker.io/library/centos


RUN yum install httpd -y


WORKDIR   /var/www/html/

RUN echo "Hi From Dockerfile" > index.html



COPY  pavan.html    .


CMD   ["httpd", "-DBACKGROUND"]



