Use the following credentials to access the zabbix panel:

**Admin Panel**: [https://${env.domain}](https://${env.domain})  
**Login**: Admin  
**Password**: ${globals.ZABBIX_PASS} 

Please use the following data to access LiteSpeed WebAdmin Console:

**Admin Console**: [https://${env.domain}:4848/](https://${env.domain}:4848/)   
**Login**: admin    
**Password**: ${globals.DB_PASS}  

Manage the database nodes using the next credentials:

**phpMyAdmin Panel**: [https://${env.domain}:8443/](https://${env.domain}:8443/)  
**Username**: ${globals.DB_USER}    
**Password**: ${globals.DB_PASS}  