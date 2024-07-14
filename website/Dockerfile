# Pull php-apache image 
FROM php:7.4.1-apache

# use root user
USER root

# Set working directory to the apache public directory 
WORKDIR /var/www/html

# Copy all files into the apache public directory
COPY . /var/www/html/

# Expose port 8087 to the outside world
EXPOSE 8087
