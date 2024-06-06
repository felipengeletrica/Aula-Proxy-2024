# Projeto PROXY reverso  (DIDÁTICO PARA O USO NAS AULAS DE REDES DE COMPUTADORES)

 Utilizando o Traefik para servidor Apache, Grafana e monitoramento utilizando o dashboard próprio do Traefik.
    
Este projeto utiliza Docker facilitando a implantação (deploy) dos serviços. 
 ***

 ## Implantação dos serviços
 Abrir o terminal e execute os seguintes comandos:


OBS: Tive que utilizar o comando abaixo "docker network create web" para conseguir dar sequência aos códigos.

Construindo e excutando os serviços (pressione ctrl+c para cencelar):

 > $ docker-compose up --build
![PRINT8](/Screenshots/PRINT8.png)

 Utilize -d para dar um "detach" rodar o serviço na máquina

> $ docker-compose up --build -d
![PRINT9](/Screenshots/PRINT9.png)

Parando serviços: 
> $ docker-compose stop
![PRINT10](/Screenshots/PRINT10.png)

Removendo serviços: 
> $ docker-compose rm
![PRINT11](/Screenshots/PRINT11.png)

***

 ## Testando os serviços

Utilize o navegador web e digite a seguinte url:

> http://apache.localhost

![PRINT12](/Screenshots/PRINT12.png)

 > http://grafana.localhost

![PRINT13](/Screenshots/PRINT13.png)

  > http://dashboard.localhost

![PRINT15](/Screenshots/PRINT15.png)

  > http://dashboard.localhost

![PRINT14](/Screenshots/PRINT14.png)
