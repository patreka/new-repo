UBUNTU
bin/bash
apt -y update
apt -y install ngnix
OS_VERSION=$(cat /proc/version)
echo "<html><body bgcolor=green><center><h1><p><font color=red>Hello World <br> $OS_VERSION</h1></center></body></html>" > /var/www/hello/index.hello-debian.html
sudo service ngnix start
chkconfig ngnix on
	
	MAMAZON LINUX
	!/bin/bash
yum -y update
yum -y install ngnix
OS_VERSION=$(cat /proc/version)
echo "<html><body bgcolor=green><center><h1><p><font color=yellow>Hello World <br> $OS_VERSION</h1></center></body></html>" > /usr/share/ngnix/html/index.html
sudo systemctl start ngnix


	
	ubuntu
	http://18.195.69.53/
	
	amazon linux
	http://3.124.5.250/
