![Zabbix](https://raw.githubusercontent.com/jeversonmiotti/Jelastic-Zabbix-Server/master/images/zabbix.png)
  
### Here are the access details for managing your environment ${env.displayName}
  
##### Information for configuring Zabbix:

**Type:** MySQL

**Database Host:** 127.0.0.1

**Database Name:** zabbix_server

**Database User:** ${globals.DB_USER}

**Password:** ${globals.DB_PASS}

**Zabbix Install URL**: [https://${env.domain}/setup.php](https://${env.domain}/setup.php)

**Important:** After the environment is created, you need to access Zabbix for the first time to complete the installation.

**Zabbix Install URL**: [https://${env.domain}/setup.php](https://${env.domain}/setup.php)

1. In the first step, choose the desired language to be used.

2. Verify Zabbix prerequisites.

3. In the third step, you need to enter the Database information. Keep MySQL selected and enter the host, database name, user, and password as provided in this email.

4. Review the installation and proceed to the next step.

5. Click the "Install" button and wait for the installation to complete.

Access details for LiteSpeed WebAdmin Console:

**Admin Console**: [https://${env.domain}:4848/](https://${env.domain}:4848/)  
**Login**: admin  
**Password**: ${globals.DB_PASS}

Database Manager:

**phpMyAdmin Panel**: [https://${env.domain}:8443/](https://${env.domain}:8443/)  
**Username**: ${globals.DB_USER}  
**Password**: ${globals.DB_PASS}

**Zabbix Documentation**: [https://www.zabbix.com/documentation/current/en/](https://www.zabbix.com/documentation/current/en/)

If you need assistance, please contact our [24/7 Support](https://api.whatsapp.com/message/2HGCCPU36CDMA1?autoload=1&app_absent=0)