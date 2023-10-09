# Práctica 2: ANA RODRIGUEZ 
## Instalación y configuración de servidor y cliente DHCP en Debian.


## RECURSOS:   
o	PC con acceso a Internet y paquete ofimático instalado.  
o	VirtualBox.  
o	Debian.  
o	Windows cliente.  
o	pfSense.  
o	https://github.com/  
o	Visual Studio Code. 

## INTRODUCCION:   

```
Esta actividad consiste en realizar un tutorial en el que se describan los ficheros involucrados y los comandos necesarios para configurar el servidor isc-dhcp-server en Debian. Este tutorial se realizará en lenguaje Markdown y será publicado en GitHub.  
```
  



## CONFIGURAR LA TARJETA DE RED: 

### EXPLICACION:

```
lo primero que hacemos en debian es ir a los ajustes del cableado y asignar la direccion ipv4, adjuntamos captura a continuacion:
```


![imagen](img/Nueva%20carpeta/Captura1.PNG)


```
Se va ha cambiar a el superusuario para poder instalar el servicio, utilizaremos el comando "su -" y una vez instalado usaremos: cat /etc/default/isc-dhcp-server.
```

![imagen](img/Nueva%20carpeta/Captura2.PNG)


```
Configuración de la interfaz por la que va ha escuchar.
```

![Copia](img/Nueva%20carpeta/Captura3.PNG)
![Copia](img/Nueva%20carpeta/Captura4.PNG)

```
A continuación, vamos ha modificar el archivo dhcpd.conf para configurar el servicio dhcp.
```

Realizamos una copia del archivo dhcpd.conf:  
![Copia](img/Nueva%20carpeta/Captura5.PNG)

Configuramos las opciones del dhcp:
![Copia](img/Nueva%20carpeta/Captura6.PNG)

Configuración de la reserva de ip:
![Copia](img/Nueva%20carpeta/Captura7.PNG)

## COMPROBAR DHCP:  
![Copia](img/Nueva%20carpeta/Captura8.PNG)


hola

