Multipurpose Docker PHP Container
===================================

### What's inside ?
This container is meant for professional PHP developers it should get your local environment ready with less effort here is an overveiw of what's included:
#### PHP 7.2 Apache
The following extensions and PECL modules are installed:
```
GD Graphics
LDAP
MySQLi
Exif 
MemCached Redis
```
Dependency:
```
curl \
git \
libfreetype6-dev \
libicu-dev \
libjpeg-dev \
libldap2-dev \
libmemcachedutil2 \
libpng-dev \
libpq-dev \
libxml2-dev \
```
#### MariaDB:10.1
Default configration:
```
TZ: "Africa/Cairo"
MYSQL_ALLOW_EMPTY_PASSWORD: "no"
MYSQL_ROOT_PASSWORD: "root"
MYSQL_USER: 'root'
MYSQL_PASSWORD: 'pass'
MYSQL_DATABASE: 'db'
```
### Installing & Running ?
Clone the files to your local folder then run compass-watch.bat ( Windows ) compass-watch.applescript ( Mac ) once the installation is done you can go to localhost to see phpinfo 