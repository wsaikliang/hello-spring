# hello-spring
Spring Application

* Please refer to https://dzone.com/articles/vagrant but alter the following steps and values
* Replace content of Vagrant file with https://github.com/wsaikliang/hello-spring/blob/master/Vagrantfile
* Replace content of vagrant_provision.sh with https://github.com/wsaikliang/hello-spring/blob/master/vagrant_provision.sh
* Follow the instruction until "cd etc/default"
* sudo vi tomcat7
* Set JAVA_HOME=/usr/lib/jvm/java-8-oracle
* When you run "service tomcat7 restart" and you get

Authentication is required to restart 'tomcat7.service'.
Authenticating as: Ubuntu (ubuntu)
Password: 

* password can be found under 
/Users/wittawat/.vagrant.d/boxes/ubuntu-VAGRANTSLASH-xenial64/20170830.1.1/virtualbox/Vagrantfile
(https://askubuntu.com/questions/832137/ubuntu-xenial64-box-password)
* The final URL is http://192.168.33.10:8080/hello-spring/