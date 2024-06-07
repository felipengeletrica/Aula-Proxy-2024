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

> http://morgana-apache.localhost

 ![Testando o Apache](doc/apache.png) 

 > http://morgana-grafana.localhost

 ![Testando o Grafana](doc/grafana.png) 

  > http://morgana-dashboard.localhost

 ![Testando o DocuWiki](doc/DocuWiki.png) 

  > http://dashboard.localhost

 ![Testando o Traefik](doc/dashboard.png) 

Docker
![Print do Docker](doc/docker.png)

![Print do Docker](doc/docker2.png)

Erro caussado por não ter uma rede criada 
![Problema](doc/problema.png)

