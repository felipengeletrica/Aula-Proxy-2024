
# TRABALHO PROXY 

## Projeto PROXY reverso  (DIDÁTICO PARA O USO NAS AULAS DE REDES DE COMPUTADORES)

 Utilizando o Traefik para servidor Apache, Grafana e monitoramento utilizando o dashboard próprio do Traefik.
    
Este projeto utiliza Docker facilitando a implantação (deploy) dos serviços. 

#### Aluno: Artur Bazzanella Christmann
#### Professor: Felipe Vargas
#### Turma: TI23

***

 ## 1) docker-compose up --build

 ### Respostas

 ![Docker Compose](Trabalho_Proxy_Artur/01-up-compose.jpg)

 ## 2) docker-compose up --build -d

 ### Respostas

 ![Docker Compose](Trabalho_Proxy_Artur/02-up-compose-d.jpg)

 ## 3) Apache

 ### Respostas

 ![Grafana](Trabalho_Proxy_Artur/03-apache.jpg)

 ## 4) Grafana

 ### Respostas

 ![Grafana](Trabalho_Proxy_Artur/03-1-grafana.jpg)

 ## 5) Traefik

 ### Respostas

 ![Grafana](Trabalho_Proxy_Artur/04-traefik.jpg)

 ## 6) Traefik

 ### Respostas

 ![Grafana](Trabalho_Proxy_Artur/05-dokueiki.jpg)



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

> http://apache.localhost

 ![Testando o Apache](doc/apache.png) 

 > http://grafana.localhost

 ![Testando o Grafana](doc/grafana.png) 

  > http://dashboard.localhost

 ![Testando o DocuWiki](doc/DocuWiki.png) 

  > http://dashboard.localhost

 ![Testando o Traefik](doc/dashboard.png) 