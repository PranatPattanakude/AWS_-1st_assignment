# commands to install and run httpd/Apache

sudo su
yum update -y
yum install -y httpd
systemctl start httpd
systemctl enable httpd
systemctl status httpd
