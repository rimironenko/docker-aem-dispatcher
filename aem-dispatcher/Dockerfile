# Start from an apache httpd image
FROM httpd:2.4

# Copy Dispatcher module to httpd modules
ADD dispatcher-apache2.4-4.3.3.so /usr/local/apache2/modules/mod_dispatcher.so

# Allow reading of Dispatcher module
RUN chmod 644 /usr/local/apache2/modules/mod_dispatcher.so

# Copy default Dispatcher configuration
ADD dispatcher.any /usr/local/apache2/conf/dispatcher.any

# Replace the default httpd.conf file by the one with configured Dispatcher
COPY httpd.conf /usr/local/apache2/conf/httpd.conf