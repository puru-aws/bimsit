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


    1. Cloud Practitioner Exam Guide (https://d1.awsstatic.com/training-and-certification/docs-cloud-practitioner/AWS-Certified-Cloud-Practitioner_Exam-Guide.pdf)
    2. Cloud Practitioner Sample Questions (https://d1.awsstatic.com/training-and-certification/docs-cloud-practitioner/AWS-Certified-Cloud-Practitioner_Sample-Questions.pdf)

    1. *Overview of Amazon Web Services (https://d1.awsstatic.com/whitepapers/aws-overview.pdf)*
    2.  *How AWS Pricing Works (http://d1.awsstatic.com/whitepapers/aws_pricing_overview.pdf)*
    3.  *Compare AWS Support Plans (https://aws.amazon.com/premiumsupport/plans/)*

1. *Whizlab*
    1. https://www.whizlabs.com/aws-certified-cloud-practitioner/

    1. 


1. *Acloud Guru*
    1. AWS Certified Cloud Practitioner
