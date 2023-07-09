FROM almalinux:8
RUN yum update -y
RUN yum install nginx -y
#command to run nginx container in the foreground mode
CMD ["nginx", "-g","daemon off;"]