# Mineda_LabV
Projeto Springboot , VueJS, Gradle e JPA.

React e React Native / Biblioteca - Front End

=> web/mobile

porque escolhi a React : simplicidade, performance, componentes reutilizáveis, suporte facebook, comunidade, um dos mais utilizados do mercado

REST API's: 
API: padrões, conjunto de rotinas e documentos para uma aplicação.
REST: principios, regras e constraints para um projeto bem definido.

Vantagens da API's REST
independente da plataforma e da linguagens utilizadas
liberdade para testar ambientes diferentes

Principios
arquitetura cliente-servidor
stateles
cache
interface uniforme
sistemas de camasdas

representações:
XML
JSON

Protocolo HTTP: forma para se comunicar
GET - retorna, busca
POST - armazenar a informação, cadastra no sistema
DELETE - deletar
PUT - atualizar todas as informação
PATCH - atualizar somente o atributo alterado

Endpoints 
requisições 
*localhost:8080/funcionario

construindo API
JDK


dependencias: spring Boot Dev Tool, Spring Data JPA, PostgreSQL Driver, Spring Web (REST).


banco POstgree - docker
//verificar status
sudo systemctl status docker

//listar imagens
sudo docker images

//abrir o pgAdmin


systemctl start/stop docker     #start/stop docker service
systemctl enable docker         #enable docker running when OS start
docker pull                     #pull Docker image
docker ps                       #list all running Containers 
docker ps -a                    #list all Containers
docker start/stop CONTAINER ID  #start/stop Container            
docker rm CONTAINER ID          #delete Container by ID
docker kill CONTAINER ID        #shut down Container
docker images                   #list all images have been downloaded

caminho da minha máquina : /home/roberta/Documentos
//restart docker portainer
$ docker restart portainer

$sudo docker-compose up -d
$docker volume create portainer_data
$sudo docker run -d -p 8000:8000 -p 9443:9443 --name portainer \
--restart=always \
-v /var/run/docker.sock:/var/run/docker.sock \
-v portainer_data:/data \
portainer/portainer-ce:latest

brownser: https://localhost:9443

portainer.io
login: admin
senha: postgres

Container/ abrir o pgadmin4
login:robertaabreu77@gmail.com
senha:pgadmin

postgres
server docker_teste-postgres-compose_1
senha e username :postgres

banco criado
nome: local
senha: postgres

