![Print1](imagens/1.PNG)
No primeiro print usamos o comando "docker-compose up --build" que é um comando usado com o Docker Compose para iniciar serviços definidos em um arquivo docker-compose.yml, construindo novas imagens Docker para os serviços antes de iniciar os contêineres. Isso garante que as últimas versões do código do aplicativo e suas dependências sejam usadas.

Em seguida executamos o comando "docker-compose up --build -d" que inicia os serviços definidos em um arquivo docker-compose.yml, construindo novas imagens Docker para esses serviços e executando os contêineres em segundo plano.

![Print3](imagens/3.PNG)

Após as primeiras etapas utilizamos o comando "docker network create web" para corrigirmos o erro "network web not found.

Comando "docker network create web" cria uma nova rede chamada "web" no Docker. Isso permite que os contêineres que estão conectados a essa rede se comuniquem entre si de forma isolada.

Depois executamos novamente o primeiro comando, e dessa vez nao apresenta o erro citado anteriormente.

![Print4](imagens/4.PNG)

Aqui temos o endereço "http://apache.localhost/" funcionando em localhost.

![Print5](imagens/5.PNG)

Aqui o endereço "http://grafana.localhost/" funcionando em localhost.

![Print6](imagens/6.PNG)

Aqui o endereço "http://dashboard.localhost/" funcionando em localhost.
