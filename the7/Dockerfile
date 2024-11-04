# Use an official httpd image as the base image
FROM httpd:2.4
# Copy the HTML files to the nginx html directory
COPY . /usr/local/apache2/htdocs/
# Expose port 80
EXPOSE 80
# Start httpd when the container starts
CMD ["httpd-foreground"]