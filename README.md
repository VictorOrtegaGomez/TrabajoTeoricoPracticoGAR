**IMPORTANTE!**


**Activar el servicio TFTP:** 
- 1-systemctl start tftp 
- 2-systemctl enable tftp
## Configuración TFTP:
	*/etc/xinetd.d/tftp
## Configuración IP estática:
	*/etc/sysconfig/network-scripts/ifcfg-<interfaz> (interfaz indica el nombre de la interfaz a configurar)
## Configuración DHCP:
	*/etc/dhcp/dhcpd.conf
## Archivos de las isos descomprimidas:
	*/var/ftp/pub 
(En la demo encontraremos 2 directorios, dentro de ellos se encuentra el archivo kickstart)
## Archivos para tftp:
	*/var/lib/tftpboot
