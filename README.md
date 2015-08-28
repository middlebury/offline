Usage: Edit the web-server config on the web hosts and change the document root & add the index.html as the 404 document.

<VirtualHost *:8080>
    ...
    DocumentRoot /var/www/offline/middcourses
    ErrorDocument 404 /index.html
    ...
</VirtualHost>

