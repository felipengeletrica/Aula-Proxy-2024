# Projeto PROXY reverso  (DIDÁTICO PARA O USO NAS AULAS DE REDES DE COMPUTADORES)

 Utilizando o Traefik para servidor Apache, Grafana e monitoramento utilizando o dashboard próprio do Traefik.
    
Este projeto utiliza Docker facilitando a implantação (deploy) dos serviços. 
 ***

 ## Implantação dos serviços
 Abrir o terminal e execute os seguintes comandos:

Construindo e excutando os serviços (pressione ctrl+c para cencelar):

 > $ docker-compose up --build

 Utilize -d para dar um "detach" rodar o serviço na máquina

> $ docker-compose up --build -d

Parando serviços: 
> $ docker-compose stop

Removendo serviços: 
> $ docker-compose rm
***

 ## Testando os serviços

Utilize o navegador web e digite a seguinte url:

> https://guga.localhost/

 ![Testando o Apache](doc/Proxy1_Apache.png) 

 > https://gugafana.localhost/

 ![Testando o Grafana](doc/Proxy3_grafana.png) 

  > http://gugawiki.localhost

 ![Testando o DocuWiki](doc/Proxy2_Wiki.png) 

  > http://gugaboard.localhost

 ![Testando o Traefik](doc/Proxy1_Board.png) 
