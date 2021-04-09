# Use WordPress image
FROM wordpress

# Install and enable xdebug
RUN yes | pecl install xdebug && \
  docker-php-ext-enable xdebug