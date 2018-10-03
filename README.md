# Magento2
Magento2 Configuration on Centos7+Nginx+MySQL

main_configureation_file.txt - This is the main process file.
Env.php - this file contains many other caching and session cookies based on Redis. File location: 
Magento2home/app/etc/env.php

magento.conf is the main configuraiton file for nginx which includes the nginx.conf.sample also.. This
file is located /etc/nginx/conf.d/magento.conf
nginx.conf.sample is located in the magento webroot directory.
php-fpm.conf, php.ini is optional but it has many changes. These are located in /etc/ directory

