# Install Drupal 8 on Digitalocean
Script to install Drupal 8 on top of Digitalocean LEMP server

Installation procedure
----------------------
```
wget https://raw.githubusercontent.com/dbjpanda/digitalocean-drupal-8/master/install.sh
chmod +x install.sh
yes "yes" |  ./install.sh
```
or 
```
wget https://raw.githubusercontent.com/dbjpanda/digitalocean-drupal-8/master/install.sh && chmod +x install.sh && yes "yes" |  ./install.sh
```
After installation of Drupal execute 
```
chmod 644 /var/www/html/drupal/sites/default/settings.php
```