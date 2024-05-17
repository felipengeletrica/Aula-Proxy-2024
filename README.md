 Projeto PROXY reverso  (DIDÁTICO PARA O USO NAS AULAS DE REDES DE COMPUTADORES)

 Utilizando o Traefik para servidor Apache, Grafana e monitoramento utilizando o dashboard próprio do Traefik.
    
Este projeto utiliza Docker facilitando a implantação (deploy) dos serviços. 
 ***

## Trabalho Docker 

# Ambiente Docker com imagens dos serviços: Grafana, Apache, Dokuwiki, Traefik, Nginx ,Gitlab.

* Imagens Docker

![Imagens Docker](https://github.com/felipengeletrica/Aula-Proxy-2024/blob/Trabalho_Tharsila/doc/services.png?raw=true)

* Teste dos Serviços 

 Grafana 

![Grafana ](https://github.com/felipengeletrica/Aula-Proxy-2024/blob/Trabalho_Tharsila/doc/img-grafana.png?raw=true)

Aphache

![Aphache](https://github.com/felipengeletrica/Aula-Proxy-2024/blob/Trabalho_Tharsila/doc/img-apache.png?raw=true)

Dokuwiki

![Dokuwiki](https://github.com/felipengeletrica/Aula-Proxy-2024/blob/Trabalho_Tharsila/doc/img-dokuwiki.png?raw=true)

Traefik

![Traefik](https://github.com/felipengeletrica/Aula-Proxy-2024/blob/Trabalho_Tharsila/doc/img-dashbord.png?raw=true)

* Todos os serviços rodando 

![Service](https://github.com/felipengeletrica/Aula-Proxy-2024/blob/Trabalho_Tharsila/doc/traefik.png?raw=true)






















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
