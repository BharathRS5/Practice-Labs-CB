FROM nginx
RUN rm -f /usr/share/nginx/html/index.html
COPY static /usr/share/nginx/html
COPY roboshop.config /etc/nginx/nginx.conf
