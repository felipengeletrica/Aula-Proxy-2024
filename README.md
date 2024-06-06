# Projeto PROXY reverso  (DIDÁTICO PARA O USO NAS AULAS DE REDES DE COMPUTADORES)

 Utilizando o Traefik para servidor Apache, Grafana e monitoramento utilizando o dashboard próprio do Traefik.
    
Este projeto utiliza Docker facilitando a implantação (deploy) dos serviços. 
 ***

 ## Implantação dos serviços
 Abrir o terminal e execute os seguintes comandos:


 OBS: Comando utilizado para resolver um problema de "network web declared as external, but could not be found",
 ![comando solução](/print/print%20erro.png)

Construindo e excutando os serviços (pressione ctrl+c para cencelar):

 > $ docker-compose up --build
![1 comando](/comandos/1comando.png)

 Utilize -d para dar um "detach" rodar o serviço na máquina

> $ docker-compose up --build -d
![2 comando](/comandos/2comando.png)


Parando serviços: 
> $ docker-compose stop
![3 comando](/comandos/3comando.png)


Removendo serviços: 
> $ docker-compose rm
![4 comando](/comandos/4comando.png)
***

 ## Testando os serviços

Utilize o navegador web e digite a seguinte url:

> http://apache.localhost

 ![print apache](/print/apache.png)

 > http://grafana.localhost

 ![print grafana](/print/grafana.png)

  > http://dashboard.localhost

![print dokuwiki](/print/dokuwiki.png)

  > http://dashboard.localhost

![print dashboard](/print/dashboard.png)
