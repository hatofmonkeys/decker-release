FROM ubuntu
EXPOSE 80
RUN apt-get install -y nginx
RUN echo "daemon off;" >> /etc/nginx/nginx.conf
RUN sed -i 's/Welcome to nginx/CloudCredo for all your CF needs/g' /usr/share/nginx/www/index.html
ENTRYPOINT ["/usr/sbin/nginx","-c","/etc/nginx/nginx.conf"]

