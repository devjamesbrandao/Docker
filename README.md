<h1 align="center"><strong>Estudos sobre Docker</strong></h1>

<hr/>

<p align="center">
    <img src="/Img/docker.png" alt="Docker image" title="Docker">
</p> 

<p align="center">
    <img src="/Img/docker_and_aspnetcore.png" alt="Docker e ASP.NET Core" title="TrueLove">
</p> 

### ` ⚙ Arquitetura do Docker`
<p><strong>Docker Daemon:</strong> é o elemento responsável por executar os containers e gerenciar todos os objetos dentro do Docker</p>

<p align="center">
    <img src="/Img/docker-daemon.png" alt="Docker Daemon" title="Docker Daemon">
</p> 

### ` 🔍 Principais comandos do Docker`
<p>$ docker pull image_name: get image from DockerHub</p>

<p>$ docker images: list images avaliables</p>

<p>$ docker run --name my_container -p 8080:80 -d image_name: create and start container</p>

<p>$ docker ps -a: list all the containers</p>

<p>$ docker stop name_or_id_container: stop container</p>

<p>$ docker start name_or_id_container: start container</p>

<p>$ docker restart name_or_id_container: restart container</p>

<p>$ docker rm container_id: remove container</p>

<p>$ docker rmi image_name: remove image</p>

### ` 🌐 Referências`
- Maratona de Docker: https://www.youtube.com/watch?v=T1DTpS9HCWU&ab_channel=Fabr%C3%ADcioVeronezDevOpsPro

- Docker Introduction, Architecture, and Command Details Part-I: https://blog.devops.dev/docker-introduction-and-architecture-8637d9d1c4dc

- Continuous Integration with .NET Core and Gitlab: https://faun.pub/continuous-integration-with-net-core-and-gitlab-5cd51161c072

- Building a docker image with Gitlab CI and .NET Core: https://faun.pub/building-a-docker-image-with-gitlab-ci-and-net-core-8f59681a86c4
