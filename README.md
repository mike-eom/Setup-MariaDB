# Setup MariaDB

## Installation MariaDB (CentOS 7)
```sh
$ yum install mariadb-server
$ systemctl start mariadb
$ systemctl enable mariadb
$ mysql_secure_installation
$ firewall-cmd --permanent --add-service=mysql
$ firewall-cmd --reload
```
