# oliviaguru landing
oliviaguru.com promotional landing page

## Description
Online website that connects homeowners with local home improvement contractors.
 
## Requirements
* Web Server

## Implementation details
* apache 2.0

## Server deployment

* sudo apt-get update
* sudo apt-get install apache2
* sudo mkdir -p /var/www/oliviaguru.com/public_html
* sudo chown -R $USER:$USER /var/www/oliviaguru.com/public_html
* sudo chmod -R 755 /var/www
* Upload files to /var/www/oliviaguru.com/public_html
* sudo cp /etc/apache2/sites-available/000-default.conf /etc/apache2/sites-available/oliviaguru.com.conf
* sudo a2ensite oliviaguru.com.conf
* sudo service apache2 restart

## License
Feel free to use this code

