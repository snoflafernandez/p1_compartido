## SERVIDOR SNMP.  

### OBJETIVO.  

El objetivo de mi grupo era conseguir un servidor snmp  
para monitorizar los OIDs planificados de cada agente.
Visualizando gráficas, estadísticas, etc.  

### BUSCAMOS LAS MEJORES HERRAMIENTAS PARA EL PROYECTO.  

Como servidor capaz de centralizar remotamente cualquier cliente snmp hemos escogido  
el servidor "PANDORA". Teníamos más opciones como el conocido  
servidor Cacti, el servidor Nagios, pero nos decantamos por Pandora,  
ya que, Cacti esta mas enfocado en el apartado gráfico, Nagios en los diferentes estados  
de los clientes y Pandora englobaba ambos aspectos.  

### PROCEDIMIENTO QUE LLEVAMOS A CABO.  

Todo el proyecto se iba a basar en una red que nosotros habíamos montado, por tanto,  
empezamos comprobando que esa red funcionaba. En especial protocolos como el DHCP, el  
DHCP RELAY, el OSPF y como extra en este proyecto teníamo la activación del protocolo  
SNMP, protocolo estándar de internet par administrar dispositivos de redes IP.  

Posteriormente a esto, teníamos una red convergente. Ya nos podíamos centrar en la  
configuración de Pandora y sus componentes.

En mi caso utilicé Windows Server como máquina virtual para instalar Pandora. ¿Cómo lo hice?  
Sencillo, navegas hasta la página oficial: https://pandorafms.org/es/ y descargar el .exe adecuado  
para tu equipo. Lo mas característico a la hora de instalar Pandora es cuando te da la opcion para  
modificar la ip de tu servidor, en mi caso lo deje en "localhost" ya que no quería que me diese ningun problema si cambiaba la ip de mi máquina haciendo pruebas