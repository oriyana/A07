<VirtualHost *:80>
        ServerAdmin webmaster@localhost
        ServerName sample.com
        DocumentRoot /var/www/sample

        ErrorLog ${APACHE_LOG_DIR}/sample_error.log
        CustomLog $APACHE_LOG_DIR}/sample_access.log combined
</VirtualHost>
