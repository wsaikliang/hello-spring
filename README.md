# hello-spring
Spring Application

This is for quickly deploying Web Application Using Vagrant. I've made some modifications to use a newer version of Ubuntu and java.

* Please refer to the original article https://dzone.com/articles/vagrant 
* Replace content of Vagrant file with https://github.com/wsaikliang/hello-spring/blob/master/Vagrantfile
* Replace content of vagrant_provision.sh with https://github.com/wsaikliang/hello-spring/blob/master/vagrant_provision.sh
* Follow the instruction until "cd etc/default"
* sudo vi tomcat7
* Set JAVA_HOME=/usr/lib/jvm/java-8-oracle
* When you run "service tomcat7 restart" and you get

Authentication is required to restart 'tomcat7.service'.
Authenticating as: Ubuntu (ubuntu)
Password: 

* cat /Users/wittawat/.vagrant.d/boxes/ubuntu-VAGRANTSLASH-xenial64/20170830.1.1/virtualbox/Vagrantfile
to get the pwd (https://askubuntu.com/questions/832137/ubuntu-xenial64-box-password)
* The final URL is http://192.168.33.10:8080/hello-spring/
