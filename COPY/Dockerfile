FROM almalinux:8
RUN yum update -y
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
COPY website/ /usr/share/nginx/html/
CMD [ "nginx","-g","daemon off;" ]