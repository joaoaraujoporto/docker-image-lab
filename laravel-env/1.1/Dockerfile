FROM alpine:3.13.5
RUN apk add --no-cache php7-apache2 \
   php7-xml \
   php7-dom \
   php7-zlib \
   php7-xmlwriter \
   php7-fileinfo \
   php7-tokenizer \
   php7-pdo_mysql \
   git composer
RUN ln -s /var/www/localhost/htdocs /app
WORKDIR /app
RUN rm index.php