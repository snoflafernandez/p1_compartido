## Instalación servicio SNMP y agente Pandora en Windows Server 2019
### Servicio SNMP.  
Una vez terminamos la instalación de la máquina virtual de Windows Server 2019 nos digimos al Administrador del servidor.  
En la zona superior entramos en la pestaña de Administrar. Una vez desplegada, hacemos click en "Agregar roles y características".  
Relaizado esto se nos abre una ventana nueva. Dentro, avanzamos pulsando en siguiente hasta el apartado llamado "Características".  
Buscamos una característica llamada "Servicio SNMP" y marcamos tanto esa característica como las que incluye.  
Una vez lo hemos marcado hacemos click en "Instalar". Pasados unos minutos finaliza la instalación.  
### Agente Pandora  
Para descargar el agente de Pandora nos dirgimos a la web oficial de Pandora(https://pandorafms.com/es/). Una vez dentro, en el  
menú entramos en el apartado descargar. No dirigirá a una página nueva, en la que debemos hacer click en un enlace que pone "web"  
en el primer párrafo. A continuación hacemos click en la zona baja de la página donde pone "Descárgalo ahora". Es entonces cuando  
se listan las versiones de Pandora para todos los sistemas operativos posibles. Descargamos la versión para Windows.  

Una vez tenemos el instalador, instalamos indicando que queremos ser agentes y no servidor. En el proceso de instalación es  
cuando se configura el agente, ya que te solicita la IP del Servidor Pandora, el nombre del grupo, etc.