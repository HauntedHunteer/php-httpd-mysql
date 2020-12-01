FROM httpd:2.4-alpine
COPY my.apache.config /usr/local/apache2/conf/my.apache.config
RUN echo "Include /usr/local/apache2/conf/my.apache.config" \
    >> /usr/local/apache2/conf/httpd.conf
