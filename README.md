
```
#!/bin/bash
yum update -y
yum install httpd -y
systemctl start httpd
systemctl enable httpd
cd /var/www/html
wget https://raw.githubusercontent.com/ashydv/jdetest/master/index.html
wget https://raw.githubusercontent.com/ashydv/jdetest/master/jdeLogin.PNG
systemctl stop firewalld
systemctl disable firewalld
```
