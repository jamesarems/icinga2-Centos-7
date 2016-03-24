# icinga2-Centos-7
Icinga2 auto installer script for Centos 7

Need minimal CentOS 7 machine with no SElinux. 

# New Features

Now you can use this script as two way web server. One for apache and other for nginx. Nginx support is in beta stage. 

# Usage

yum install git -y

git clone https://github.com/jamesarems/icinga2-Centos-7.git

cd icinga2-Centos-7

chmod +x icinga2-installer.sh

* To use with Apache server

 # ./icinga2-installer.sh <yourpassword> apache      

* To Use with Nginx server

 # ./icinga2-installer.sh <yourpassword> nginx
