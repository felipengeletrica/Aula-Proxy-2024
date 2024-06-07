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


## Testando os serviços personalizados:

Personalizei o nome das URLs estilizando com meu sobrenome "bassetti". Como por exemplo: "bassetti-traefik.localhost", ao acessar em um navegador, o proxy reverso (Traefik) irá redirecionar essa solicitação para o Traefik Dashboard, pelo caminho "/dashboard".


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

Configuração de um serviço Samba usando o Docker Compose. O Samba é uma implementação de software usada para compartilhar arquivos e impressoras em uma rede entre sistemas Windows, Linux, entre outros sistemas operacionais.

![Testando o Samba](imagens/samba.png) 