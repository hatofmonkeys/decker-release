FROM ubuntu
EXPOSE 80
RUN apt-get install -y nginx
RUN echo "daemon off;" >> /etc/nginx/nginx.conf
ENTRYPOINT ["/usr/sbin/nginx","-c","/etc/nginx/nginx.conf"]

