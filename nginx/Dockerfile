FROM nginx:latest

ADD config/nginx.conf      /etc/nginx/nginx.conf
ADD sites-enabled/*    /etc/nginx/conf.d/

EXPOSE 80

VOLUME ["/var/log/nginx"]
VOLUME ["/usr/share/nginx/html/"]
