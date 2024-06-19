![Zabbix](https://raw.githubusercontent.com/jeversonmiotti/Jelastic-Zabbix-Server/main/images/zabbix.png)
  
### Aquí están los datos de acceso para la gestión de su entorno ${env.displayName}
  
##### Información para configurar Zabbix:

**Tipo:** MySQL

**Host de la Base de Datos:** 127.0.0.1

**Nombre de la Base de Datos:** zabbix_server

**Usuario de la Base de Datos:** ${globals.DB_USER}

**Contraseña:** ${globals.DB_PASS}

**URL de Instalación de Zabbix**: [https://${env.domain}/setup.php](https://${env.domain}/setup.php)

**Importante:** Después de la creación del entorno, es necesario acceder por primera vez a Zabbix para finalizar la instalación.

**URL de Instalación de Zabbix**: [https://${env.domain}/setup.php](https://${env.domain}/setup.php)

1. En el primer paso, elija el idioma deseado que se utilizará.

2. Verifique los requisitos previos de Zabbix.

3. En el tercer paso, debe ingresar la información de la base de datos. Mantenga seleccionada la opción MySQL e ingrese la información del host, el nombre de la base de datos, el usuario y la contraseña según lo proporcionado en este correo electrónico. Desmarque la opción: Database TLS encryption

4. En Configuración, agregue el nombre para Zabbix, elija la zona horaria y el tema deseado.

5. Revise la instalación y proceda al siguiente paso.

6. Haga clic en el botón "Instalar" y espere a que se complete la instalación.

Acceso predeterminado a la Consola de Administración de Zabbix:
**Usuario:** Admin
**Contraseña:** zabbix

Datos de acceso para LiteSpeed WebAdmin Console:

**Consola de Administración**: [https://${env.domain}:4848/](https://${env.domain}:4848/)  
**Usuario**: admin  
**Contraseña**: ${globals.DB_PASS}

Gestor de Bases de Datos:

**Panel de phpMyAdmin**: [https://${env.domain}:8443/](https://${env.domain}:8443/)  
**Usuario**: ${globals.DB_USER}  
**Contraseña**: ${globals.DB_PASS}

**Documentación de Zabbix**: [https://www.zabbix.com/documentation/current/es/](https://www.zabbix.com/documentation/current/es/)

Si necesita asistencia, por favor contacte con nuestro [Soporte 24/7](https://api.whatsapp.com/message/2HGCCPU36CDMA1?autoload=1&app_absent=0)
