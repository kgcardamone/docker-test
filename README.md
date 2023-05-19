# docker-test
Duas imagens criadas, uma com 2 megas usando scratch e outra que não atende os 2MB usando o Alpine.

Para rodar o projeto.
docker run -it kcardamone/fullcycle - Usando scratch
Link: https://hub.docker.com/repository/docker/kcardamone/fullcycle/general

docker run -it kcardamone/goprod - Usando Alpine
Link: https://hub.docker.com/repository/docker/kcardamone/goprod/general

Para rodar os 2
docker compose up
