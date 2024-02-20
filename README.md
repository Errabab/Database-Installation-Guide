# Database-Installation-Guide
![portada](/img/portada.png)
## [Download Oracle on VirtualBox.](Descargarmos.md)
## [Start and configure Oracle](configuracion.md) 
## Steps
After the installations, we have to initiate the installation of the **Oracle DataBase**.
1. Log in as root:
 ` su - `
2. Update the packages:
` dnf update`
Use *dnf* for the new version; if you have an old version, you need to use *yum*.

4. Now we install the Oracle Database from the official website:
` wget https://download.oracle.com/otn-pub/otn_software/db-express/oracle-database-xe- 21c-1.0-1.ol8.x86_64.rpm `
