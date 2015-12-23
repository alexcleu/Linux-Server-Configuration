# Linux Server Configuration

### Access Information:
* IP Address: 52.35.129.232
* port: 2200

### Web application url:
[http://ec2-52-35-129-232.us-west-2.compute.amazonaws.com/]()

### Summary of software used & configuration changed:
* Change port to 2200
* Configure Firewall for port 80, 123, and 2200
* Install apache2
* Installed mod-wsgi
* Configure local time to UTC
* Installed PostgreSQL
* Created new user Catalog with database Catalog
* Added wsgi config script to configure Flask app in apache2

### Additional software added
* Installed pip
* Installed virtualenv to keep the application isolated from main system
* Installed fail2ban


