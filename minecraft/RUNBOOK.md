### docker run

```
mkdir -p /opt/minecraft
docker run -d -it --name minecraft -v /opt/minecraft:/data -p 25565:25565 -e EULA=TRUE -e MEMORY=2G -e TYPE=FORGE -e VERSION=1.12.2 -e GUI=FALSE --restart=unless-stopped itzg/minecraft-server:java8-multiarch
```
