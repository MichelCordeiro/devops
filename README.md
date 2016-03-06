##DevOps Servers
-- vagrant box for devops

- Box no vagrant que contem 4 máquinas ubuntu

#db: 
  * maquina com servidor de banco de dados mysql

#web:
  * maquina com servidor de deploy com tomcat7

#monitor:
  * maquina com servidor de supervisionamento dos outros servidores. Utiliza nagios3

#build:
  * maquina com servidor de build, contém:
  * Gitlab
  * Sonar
  * Jenkins
