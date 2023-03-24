FROM arm64v8/wordpress

RUN yes | pecl install xdebug && docker-php-ext-enable xdebug

COPY info.php /var/www/html/info.php
COPY xdebug.ini /usr/local/etc/php/conf.d/xdebug.ini
