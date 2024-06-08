 ![Zabbix](https://raw.githubusercontent.com/jeversonmiotti/Jelastic-Zabbix-Server/master/images/zabbix.png)
  
  ### Seguem dados de acesso para Gerenciamento do seu Ambiente ${env.displayName}
  
  
  ##### Informações para configurar o Zabbix:


  **Tipo:** MySQL
  
  **Host do Banco de Dados:** 127.0.0.1

  **Nome do Banco de Dados:** zabbix_server

  **Usuário do Banco de Dados:** ${globals.DB_USER}
  
  **Senha:** ${globals.DB_PASS}


**Zabbix URL Install**: [https://${env.domain}/setup.php](https://${env.domain}/setup.php)


 **Importante:** Após a criação do Ambiente é necessário realizar um primeiro acesso ao Zabbix para finalizar a instalação.

 **Zabbix URL Install**: [https://${env.domain}/setup.php](https://${env.domain}/setup.php)

  1. No primeiro passo, escolha o Idioma desejado que será utilizado.
  
  2. Verifique os pré-requisitos do Zabbix.
  
  3. No terceiro será necessário colocar as informações do Banco de Dados. Deixar selecionado a opção MySQL e colocar as informações de host, nome do Banco de Dados, usuário e senha conforme informadas nesse email e desmarque a opção: Database TLS encryption.

  4. Em Settings, Adicione o nome para o Zabbix, escolha o timezone e o tema desejado.

  5. Revise a instalação e siga para o próximo passo.

  6. Clique no botão "Instalar" e aguarde a conclusão da instalação.

  Acesso padrão ao Console de Administração do Zabbix:
  **Login:** Admin  
  **Senha:** zabbix

  Dados de acesso para LiteSpeed WebAdmin Console:

  **Admin Console**: [https://${env.domain}:4848/](https://${env.domain}:4848/)   
  **Login**: admin    
  **Password**: ${globals.DB_PASS}  

  Gerenciador de Banco de Dados:

  **phpMyAdmin Panel**: [https://${env.domain}:8443/](https://${env.domain}:8443/)  
  **Username**: ${globals.DB_USER}    
  **Password**: ${globals.DB_PASS}  

  **Documentação Zabbix**: [https://www.zabbix.com/documentation/current/en/](https://www.zabbix.com/documentation/current/en/) 

  

  Caso necessite de auxilio entre em contato com nosso [Suporte 24/7](https://api.whatsapp.com/message/2HGCCPU36CDMA1?autoload=1&app_absent=0)

