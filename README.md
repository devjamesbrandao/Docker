<h1 align="center"><strong>Estudos sobre Docker</strong></h1>

<hr/>

<p align="center">
    <img src="/Img/docker.png" alt="Docker image" title="Docker">
</p> 

<p align="center">
    <img src="/Img/docker_and_aspnetcore.png" alt="Docker e ASP.NET Core" title="TrueLove">
</p> 

### ` ⚙ Arquitetura do Docker`
<p><strong>Docker Daemon:</strong> é o elemento responsável por executar os containers e gerenciar todos os objetos dentro do Docker.</p>

<p><strong>Docker Client:</strong> é a ferramenta de interação e comunicação com o Docker Daemon.</p>

<p><strong>Docker Registry:</strong> é o repositório de imagens Docker.</p>

<p align="center">
    <img src="/Img/arquitetura-docker.png" alt="Arquitetura Docker" title="Arquitetura Docker">
</p> 

### ` 🚪 Port Bind`
<p>Permite vincular uma porta local da máquina com a porta da aplicação executando dentro do container</p>

<p align="center">
    <img src="/Img/port-bind.png" alt="Port Bind" title="Port Bind">
</p> 

### ` 🔍 Principais comandos do Docker`
<p>$ docker pull image_name: obter imagem do DockerHub</p>

<p>$ docker images: lista todas as imagens disponíveis</p>

<p>$ docker run --name container -p 8080:80 -d imagem: cria um novo container a partir de uma imagem e inicia-o</p>

<p>$ docker container ls: lista todos os containers em execução</p>

<p>$ docker container ls -a: lista todos os containers disponíveis</p>

<p>$ docker inspect container_id: detalhes sobre um container específico</p>

<p>$ docker container run -it ubuntu /bin/bash: o parâmetro <strong>-it</strong> permite interagir com o container</p>

<p>$ docker stop name_ou_id_container: parar container</p>

<p>$ docker start name_ou_id_container: iniciar container</p>

<p>$ docker restart name_ou_id_container: reiniciar container</p>

<p>$ docker rm container_id: remove container</p>

<p>$ docker rmi image_name: remove imagem</p>

### ` 🌐 Referências`
- Maratona de Docker: https://www.youtube.com/watch?v=T1DTpS9HCWU&ab_channel=Fabr%C3%ADcioVeronezDevOpsPro

- Docker Introduction, Architecture, and Command Details Part-I: https://blog.devops.dev/docker-introduction-and-architecture-8637d9d1c4dc

- Continuous Integration with .NET Core and Gitlab: https://faun.pub/continuous-integration-with-net-core-and-gitlab-5cd51161c072

- Building a docker image with Gitlab CI and .NET Core: https://faun.pub/building-a-docker-image-with-gitlab-ci-and-net-core-8f59681a86c4
