
##  **DevOps Servers**

O projeto é constituido da criação de ambientes montados com: 

![vagrant](https://www.vagrantup.com/assets/images/logo-header-53d0bd25.png) ![+](http://www.brumadourgente.com.br/hd-imagens/bt_mais.png)  ![Ubuntu](http://assets.ubuntu.com/v1/c6679b95-logo-ubuntu-orange.svg)

###  **Instalação**

* Faça o download do [vagrant](https://www.vagrantup.com/downloads.html);
* Faça o download do [virtualbox](https://www.virtualbox.org/wiki/Downloads);

>> Instale a box do ubuntu no Vagrant

> `$ vagrant box add precise32 http://files.vagrantup.com/precise32.box`


>> Baixe o projeto DevOps para sua máquina

>`git clone https://github.com/MichelCordeiro/devops.git`


### Vagrant

Suba as máquinas criadas utilizando o comando:

`vagrant up`

> O vagrant irá subir 4 máquinas:

*  **db**: máquina com servidor mysql para base de dados da aplicação;
*  **web**: máquina com tomcat7 para deploy da aplicação;
*  **monitor**: máquina com nagios3 para monitoramento da aplicação;
*  **build**: máquina com gitlab, sonarqube, jenkins e artifactory para integração contínua da aplicação;


***
* [Michel Cordeiro](https://br.linkedin.com/in/michelcordeiro)
* [blog - jcodehsell](https://jcodeshell.wordpress.com)
* [@code_shell](https://twitter.com/code_shell)
