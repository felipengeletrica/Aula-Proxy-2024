# Projeto PROXY reverso 
# (DIDÁTICO PARA O USO NAS AULAS DE REDES DE COMPUTADORES)

Utilizando o Traefik para servidor Apache, Grafana e monitoramento utilizando o dashboard próprio do Traefik.
    
Este projeto utiliza Docker facilitando a implantação (deploy) dos serviços.


#### Aluno: Artur Bazzanella Christmann
#### Professor: Felipe Vargas
#### Turma: TI23

### Sobre o trabalho

Documente com print e coloque aqui as respostas

***

#### Resposta 1:
Docker com imagem dos serviços: Apache, Grafana, Dokuwiki, Traefik, DB e Samba.

#### Print Screem:

![Docker](Trabalho_Artur/01.jpg)

#### Resposta 2:

Apache.

#### Print Screem:

![Apache](Trabalho_Artur/02.jpg)

#### Resposta 3:

Grafana.

#### Print Screem:

![Grafana](Trabalho_Artur/03.jpg)

#### Resposta 4:

Traefik.

#### Print Screem:

![Traefik](Trabalho_Artur/04.jpg)

#### Resposta 5:

Dokuwiki.

#### Print Screem:

![Dokuwiki](Trabalho_Artur/05.jpg)

#### Resposta 6:

Samba.

#### Print Screem:

![Samba](Trabalho_Artur/06.jpg)


## Thanks Teacher! ;-)

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
