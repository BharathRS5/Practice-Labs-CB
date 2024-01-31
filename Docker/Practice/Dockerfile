FROM almalinux
LABEL container="nginx"
EXPOSE 80/tcp
RUN yum install nginx -y
RUN echo "Hello world, Let's begin careating our own Docker images" > /usr/share/nginx/html/hello.html
CMD [ "nginx", "-g", "daemon off;" ]
