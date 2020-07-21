# mysql_multi

#### Installation

* Just download the "mysql_multi" file in RHEL/CentOS based server.
* Give executable permission to the downloaded file.
* Run the file according path
```
	rm -f mysql_multi
	https://raw.githubusercontent.com/Shah9il/mysql_multi/master/mysql_multi
	chmod a+x mysql_multi
	./mysql_multi
```
* By default the location is set to as "/usr/local/" for additional MySQL instance
* After running the file need to provide the expected folder name (i.e: MySQL_new)
* By default the MySQL gets installed with 3306 port. But with this installer it will ask for a free port in server.

#### Prerequisite
* MariaDB has not been tested with the script. Up to MySQL 5.6 has been tested with the script working fine. So to install additional MySQL instance a MySQL must be there in the server.
