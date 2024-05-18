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

> http://apache.localhost

 ![Testando o Apache](doc/apache.png) 

 > http://grafana.localhost

 ![Testando o Grafana](doc/grafana.png) 

  > http://dashboard.localhost

 ![Testando o DocuWiki](doc/DocuWiki.png) 

  > http://dashboard.localhost

 ![Testando o Traefik](doc/dashboard.png) 

 

## Serviços personalizados:

> http://bassetti-apache.localhost
![Testando o Apache](imagens/apache-bassetti.png) 

> http://bassetti-traefik.localhost
![Testando o Traefik](imagens/traefik-bassetti.png)

> http://bassetti-apache1.localhost
![Testando o Apache1](imagens/apache1-bassetti.png)

> http://bassetti-dokuwiki.localhost
![Testando o Dokuwiki](imagens/dokuwiki-bassetti.png)

> http://bassetti-grafana.localhost
![Testando o Grafana](imagens/grafana-bassetti.png)

> http://linux.localhost
![Testando o Samba](imagens/samba.png) 