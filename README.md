# Server Configuration

Este repositório está relacionado ao quinto projeto do curso FullStack da Udacity. Todas as informações necessárias para avaliar o projeto estão contidas nesse README.

Como estabelecido, este documento compreende:

## O endereço de IP e a porta SSH para que seu servidor possa ser acessado pelo revisor: 
    -IP 52.7.186.207
    -Porta 2200
    -Usuário grader

## A URL completa que você hospedou em sua aplicação web: 
    -URL: http://www.52.7.186.207.xip.io/

## Um resumo do software que você instalou e as mudanças feitas em configuração.

    -Instalação e configuração do UFW (Habilitação e Permissão de Tráfego para as Portas: 80, 123, 443, 2200);
    
    -Instalação do servidor NTP e ajuste do timezone. Foi atribuido dns de servidores NTP do brasil e américa latina;  
    
    -Instalação dos seguintes pacotes e suas dependências: aniso8601==4.1.0, ansible==2.7.8, Flask==1.0.2,Flask-Login==0.1.3,
    Flask-RESTful==0.3.6,Flask-SQLAlchemy==2.3.2,   oauth2client==4.1.3,paramiko==2.4.2,psycopg2==2.7.7,SQLAlchemy==1.2.12
    
    -Instalação do Apache: Criação do arquivo WSGI para realizar a chamada ao __init__.py (Main do projeto), criação do arquivo de    
    configuração do VirtualHost (i.e. definição de porta de escuta, nome do processo, alias, log path, etc.) 
    
    -Instalação do POSTGRES SQL: Criação do banco Catalog, criação do usuário de acesso ao banco, habilitação das permissões ao 
    usuário, ajuste do arquivo de configuração habilitando apenas o acesso local ao banco.

## Uma lista de quaisquer recursos de terceiros que você usou para completar esse projeto.

  Projeto Git FS Udacity de alguém: 
    -https://github.com/thisbejim/Project-5/blob/master/database_setup.py

  Guia de configuração Postgres: 
    -https://wixelhq.com/blog/how-to-install-postgresql-on-ubuntu-remote-access
    -http://www.postgresonline.com/downloads/special_feature/postgresql83_psql_cheatsheet.pdf

  Rodando Flask em Servidor Ubuntu com Apache:
    -https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps
    -https://modwsgi.readthedocs.io/en/develop/user-guides/quick-configuration-guide.html
    -https://stackoverflow.com/questions/31252791/flask-importerror-no-module-named-flask

  Configuração do Virtualhost Apache:
    -https://www.digitalocean.com/community/questions/domain-not-serving-wsgi-file-but-the-ip-does
    -https://www.digitalocean.com/community/tutorials/como-configurar-apache-virtual-hosts-no-ubuntu-16-04-pt
  
  Outros:
    -https://github.com/kongling893/Linux-Server-Configuration-UDACITY


