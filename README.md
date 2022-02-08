# minecraft-docker-lino

A Minecraft Docker stack for my son.

> This is a Minecraft Docker Compose stack customised for personal use.

## Description

Highly based on [itzg/docker-minecraft-server](https://github.com/itzg/docker-minecraft-server)

### Versions

Minecraft 1.16.5  
[Forge 36.2.0](https://adfoc.us/serve/sitelinks/?id=271228&url=https://maven.minecraftforge.net/net/minecraftforge/forge/1.16.5-36.2.0/forge-1.16.5-36.2.0-installer.jar)  

#### Mods

[Blockling Collection 4.5](https://www.curseforge.com/minecraft/mc-mods/blocklingcollection/files)  
[Flywheel 1.16-0.2.4](https://www.curseforge.com/minecraft/mc-mods/flywheel/files)  
[Create 1.16.5 v0.3.2d](https://www.curseforge.com/minecraft/mc-mods/create/files)  
[Citadel 1.8.1-1.16.5](https://www.curseforge.com/minecraft/mc-mods/citadel/files/3441028)  
[Ice and Fire: Dragons 2.1.9-1.16.5](https://www.curseforge.com/minecraft/mc-mods/ice-and-fire-dragons/files/3441117)   
[WorldEdit 7.2.5](https://www.curseforge.com/minecraft/mc-mods/worldedit/files/3283693)  
[Apotheosis-1.16.5-4.8.2](https://www.curseforge.com/minecraft/mc-mods/apotheosis/files/3490144)  
[Placebo-1.16.5-4.6.0](https://www.curseforge.com/minecraft/mc-mods/placebo/files/3437009)  

### Reference

> This is a reference for myself, when I have to install mode, update things.

#### Add mod(s) to the server

1.  Download the right version(s) locally
2.  `scp ~/Downloads/*.jar microserver:docker/minecraft-docker-lino/mods/`
3.  `rm ~/Downloads/*.jar`
