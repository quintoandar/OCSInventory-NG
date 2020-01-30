![Logo-OCS](http://cdn.ocsinventory-ng.org/common/banners/banner300px.png)

## OCSInventory-NG Docker Image

The files are the same of the [OCSInevntory-Docker-Image](https://github.com/OCSInventory-NG/OCSInventory-Docker-Image) on its Version 2.6

There's only three modifications on this Docker image:

* Changed the root page from **```<server-url>/ocsreports```** to **```<server-url>/```**
  * file ```scripts/docker-entrypoint.sh``` line ```#44```
  
* Installing the package ```php73-php-ldap``` for ldap integration
  * file ```Dockerfile``` line ```#63```

* Changed Timezone to ```TZ=America/Sao_Paulo```
  * file ```Dockerfile``` line ```#16```
