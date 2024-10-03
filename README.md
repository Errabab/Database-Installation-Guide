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

![1](img/cp2.png)

4. Now we install the Oracle Database from the official website:
   
` wget https://download.oracle.com/otn-pub/otn_software/db-express/oracle-database-xe- 21c-1.0-1.ol8.x86_64.rpm `


5. Install the Oracle Linux client
` wget https://www.oracle.com/es/database/technologies/instant-client/linux-x86-64-
downloads.html `

![1](img/cp4.png)

7. Finally, we only need the IP address of the machine.

The IP is used to connect to the database from other devices with SSH
`ip a`

## Referencias
   * **[Oracle](https://www.oracle.com/es/database/)**
## Autores 
  * Errabab Salec Ahriem 
<p xmlns:cc="http://creativecommons.org/ns#" > <a href="http://creativecommons.org/licenses/by-nc/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"></a></p>

