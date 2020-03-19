# Minecraft Game Server

## Install the Minecraft Server

Install Java:

```
sudo apt install openjdk-8-jre-headless
```

Download & Install the Nukkit server software

```
mkdir nukkit
cd nukkit
wget -O nukkit.jar http://ci.mengcraft.com:8080/job/nukkit/lastSuccessfulBuild/artifact/target/nukkit-1.0-SNAPSHOT.jar
sudo java -jar nukkit.jar
```

Choose your Language:

![setup-nukkit](_images/setup-nukkit.png)

> Note: `Nukkit` is nuclear-powered server software for [Minecraft: Pocket Edition](https://github.com/NukkitX/Nukkit).
