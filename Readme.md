sudo add-apt-repository ppa:ondrej/php     ------to install php libraries
 
sudo apt-get update     

sudo apt-get install php7.1 php7.1-common     ----- - to install packages

sudo apt-get install php7.1-curl php7.1-xml php7.1-zip php7.1-gd php7.1-mysql php7.1-mbstring         --------  installing dependency packages


sudo a2enmod rewrite   ---------- enabling redirection rule

git clone https://github.com/puru-aws/phpdemo.git


create database bms;

use bms;

show tables;

mysql -u admin -h database-1.cre5baupyljm.ap-south-1.rds.amazonaws.com -p


mysql -u admin -h database-1.cre5baupyljm.ap-south-1.rds.amazonaws.com -p bms < phpdemo/public/install/database.sql

sudo vi /etc/apache2/sites-enabled/000-default.conf

      DocumentRoot /var/www/html/phpdemo
         <Directory /var/www/html/phpdemo>
                Allow from all
                Require all granted
                AllowOverride All
                Order allow,deny
        </Directory>

sudo service apache2 restart



sudo apt-get purge php7.1 php7.1-common

sudo apt-get install php7.4 php7.4-common
sudo apt-get install mysql-server php7.4-mysql
sudo apt-get install php7.4-curl php7.4-xml php7.4-zip php7.4-gd php7.4-mysql php7.4-mbstring

sudo service apache2 restart
