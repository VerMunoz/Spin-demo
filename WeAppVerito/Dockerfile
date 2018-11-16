FROM nginx:1.14.1-alpine

COPY webpage /usr/share/nginx/html

COPY config/webapp.conf /etc/nginx/conf.d

CMD ["nginx", "-g", "daemon off;"]
