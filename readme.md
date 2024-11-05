---Linux project---

In this project, we will set up a basic web server on a Linux system using the Apache HTTP 
server (httpd). Apache is one of the most widely used web servers and serves webpages to 
users by hosting HTML, CSS, and other web files. The goal is to install the httpd package, 
start and configure the Apache service, and create a basic webpage that can be accessed 
through a browser by navigating to localhost.   
This report will detail the step-by-step process of installing and configuring the web server, 
creating and serving web files, and verifying the server's functionality.    

Requirements --
Redhat Linux Enterprises
httpd package

Steps--

1. terminal install the httpd package
----- sudo dnf install httpd
2. start the httpd service
---- sudo systemctl start httpd.service
3. enable httpd to start on boot-- to ensure that httpd service starts automatically on boot
---- sudo systemctl enable httpd.service
4. navigate to the web directory
---- cd /var/www/html
5. create an html file
touch index.html
6. create a css file
touch one.css
7. edit the html file or any file
sudo vi index.html/sudo vi one.css

just save it and then go to the browser and type localhost.


summary----
sudo dnf install httpd
sudo systemctl start httpd.service
sudo systemctl enable httpd.service  # optional
cd /var/www/html
touch index.html
touch one.css
sudo vi index.html
sudo vi style.css

-----  to see the file go to any web browser and search localhost the webpage will display 