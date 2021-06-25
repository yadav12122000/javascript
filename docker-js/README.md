# Docker Play

This webapp integrates the container technology with the javascript. 
Using this webapp, we can run docker service and manage it as a Platform as a Service(PaaS).

### How to use

Install the httpd
--------------

### yum install httpd

Start the httpd service
---------------
### systemctl start httpd

Put the linux.py file in /var/www/cgi-bin folder.(in case of redhat and centos).
Make this file executable:

### chmod +x linux.py
Put dockerapp.html and the backend image in /var/www/html/ folder.

Using your IP address, access the webpage.
