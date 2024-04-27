# Deploy-App-Using-HTTPD
How to deploy an Application on to AWS and Install HTTPD, Run HTTPD and Run the application using HTTPD.

Steps:

1. Create an EC2 Instance and Log into it.
2. Install HTTPD (Apache2) in it.
3. Change the working directory to /var/www/html. 
4. create index.html file using touch command ,
5. Use vi editor for write the index.html file . (static web page )
5. Save it and use the Public IP of the EC2 instance to access it from the Browser.

# script

yum -y install httpd

systemctl enable httpd

systemctl start httpd

cd /var/www/html 
touch index.html    
vi index.html 
wq!
# The script does the following:

Install an Apache web server (httpd)

Configure the web server to automatically start on boot

Activate the Web server

Create a simple web page
![Image ](/Screenshot.JPG)

![Capture](https://github.com/prashant169/Deploy-App-Using-HTTPD-/assets/78464585/e44baf30-f2de-4455-931b-b0e80b7154ca)
