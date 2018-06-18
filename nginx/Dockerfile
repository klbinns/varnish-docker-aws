FROM nginx:alpine

ENV LANG C.UTF-8

# ADD CONFIG FILES
COPY ./config/conf/nginx.conf /etc/nginx/nginx.conf
COPY ./config/conf.d/varnish-nginx.template /etc/nginx/conf.d/varnish-nginx.template

COPY ./static /etc/nginx/html

CMD ["nginx"]
