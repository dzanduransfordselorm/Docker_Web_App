# Use the official PHP Apache image from Docker Hub
FROM php:7.4-apache

# Copy the current directory contents into the /var/www/html/ directory in the container
COPY . /var/www/htm

# Enable Apache mod_rewrite (if needed for URL rewrites)
RUN a2enmod rewrite

# Expose port 80 for HTTP traffic
EXPOSE 80

# Start Apache in the foreground
CMD ["apache2-foreground"]
