# Docker-03.-Aprendiendo-docker-con-servidores-de-Minecraft
Tutorial 3 de docker aprendiendo docker con servidores de Minecraft

Aprendiendo docker compose levantando servidores minecraft con docker, con bungeeCord incluido. También aprendemos a levantar un servidor minecraft bedrock.

Los ficheros usados los podéis ver aquí 
https://github.com/minakmostoles/Docker-02.-Jugando-con-docker-compose-Postgres-adminer-

Las imágenes usadas son las siguientes:
https://hub.docker.com/r/itzg/bungeecord
https://hub.docker.com/r/itzg/minecraft-server
https://hub.docker.com/r/itzg/minecraft-bedrock-server

Para ejecutar esta imagen en una RaspberryPi 3 B +, 4 o más reciente, use la etiqueta de imagen:
itzg/minecraft-server:multiarch
NOTA: es posible que deba reducir la asignación de memoria, como -e MEMORY=750m
