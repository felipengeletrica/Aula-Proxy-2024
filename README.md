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

>https://vinicius-apache1.localhost/

 ![Testando o Apache](Fotos/apacheVini.pngpng) 

 > https://vinicius-grafana.localhost/login

 ![Testando o Grafana](Fotos/grafanaVini.png.png) 

  > https://vinicius-dashboard.localhost/dashboard/#/

 ![Testando o DocuWiki](Fotos/dashboardVini.png) 

  > https://vinicius-dokuwiki.localhost/

 ![Testando o Traefik](Fotos/dokuwikiVini.png)