FROM nginx
RUN rm -f /usr/share/nginx/html/index.html
COPY roboshop.config /etc/nginx/default.d/roboshop.config
COPY static /usr/share/nginx/html