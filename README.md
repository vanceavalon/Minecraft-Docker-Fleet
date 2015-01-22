# Minecraft-Docker-Fleet
Using itzg/minecraft docker container to make a fleet service

This should run Minecraft with Fleet as a Docker container to keep it a little more persistant on your cluster.

Current, my service file has enviromental variables which you may not want (such as SEED and OPS), change the service file to fit your needs. I will like the Docker container here so that you may reference your service file changes:
[itzg/minecraft-server](https://registry.hub.docker.com/u/itzg/minecraft-server/)
