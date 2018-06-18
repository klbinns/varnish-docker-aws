FROM emgag/varnish:5.2.1

ENV LANG C.UTF-8

# ADD CONFIG FILES
COPY ./config/default.vcl /etc/varnish/default.vcl

CMD ["/init.sh"]
