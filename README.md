# Magento2 Demo
This is a Magento 2 installation that I use for testing or demo purposes.
It has all of the vendor files included in the repo so that I don't have to do a "composer install" after upload since sometimes I use shared servers that don't have commandline access.
Cloning this repo or including this composer dependency is basically like downloading the Magento 2 archive and unzipping it.
This is also a composer package that you include in your dev dependencies for a local dev environment magento 2 installation.

## Steps to get started
1. `vagrant up` to start the machine
2. `vagrant ssh` to access the machine
3. `sudo service nginx start` to start nginx *will fix this soon
4. `mysql -u root -p` to enter mysql
5. `CREATE DATABASE magento2;` to create the Magento 2 database
6. Visit http://192.168.69.11 in your browser to install Magento.
7. Enjoy your Magento 2 installation!