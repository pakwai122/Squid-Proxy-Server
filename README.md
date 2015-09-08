Squid-Proxy-Server
-----------------
```
sudo su
apt-get update
apt-get upgrade -y
apt-get dist-upgrade -y
apt-get autoremove -y
apt-get install squid apache2-utils -y

vi /etc/squid3/squid.conf
serach http_access deny all to http_access allow all
service squid3 restart
