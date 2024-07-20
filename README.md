<div align="center">

<br>

<img src="Logo/SuperMod_logo.jpg" alt="Logo" width="500"/>

<h1 align="center">SuperMod Server Template</h1>

[![GitHub release](https://img.shields.io/github/v/release/Nicolas-Colombier/SuperMod-Server-Template)](https://github.com/Nicolas-Colombier/SuperMod-Server-Template/releases)

<h4 align="center"> Configuration files for Squad servers using the SuperMod mod </h4>

<p align="center">
    <a href="https://github.com/Nicolas-Colombier/SuperMod-Server-Template#Instruction">Instruction</a> •
    <a href="https://github.com/Nicolas-Colombier/SuperMod-Server-Template#Administration">Administration</a> •
    <a href="https://github.com/Nicolas-Colombier/SuperMod-Server-Template#levels-layers-for-map-voting">Levels/Layers for map voting (NOT WORKING)</a> •
    <a href="https://github.com/Nicolas-Colombier/SuperMod-Server-Template#levels-layers-for-standard-rotation">Levels/Layers for standard rotation</a> •
    <a href="https://github.com/Nicolas-Colombier/SuperMod-Server-Template#miscellaneous">Miscellaneous</a> •
    <a href="https://github.com/Nicolas-Colombier/SuperMod-Server-Template#squadsdm">SquadSDM</a>
</p>
</div>

<br>

## Instruction
- "**$word**", it means it's a variable. You must change it to your need.

- You must put the configuration files inside your ServerConfig directory
  * **Windows** : `C:\$InstallationFolder\SquadGame\ServerConfig\`
  <br>
  * **Linux** : `/home/$InstallationFolder/SquadGame/ServerConfig/`

<br>

## Administration
- [Server.cfg](https://github.com/Nicolas-Colombier/SuperMod-Server-Template/ServerConfig/Server.cfg) → Edit your server information and configuration
- [CustomOptions.cfg](https://github.com/Nicolas-Colombier/SuperMod-Server-Template/blob/main/ServerConfig/CustomOptions.cfg) → Edit custom options for seeding phase.
- [Admin.cfg](https://github.com/Nicolas-Colombier/SuperMod-Server-Template/blob/main/ServerConfig/Admins.cfg) → Edit your admin list
- [MOTD.cfg](https://github.com/Nicolas-Colombier/SuperMod-Server-Template/blob/main/ServerConfig/MOTD.cfg) → Edit your server rules
- [ServerMessages.cfg](https://github.com/Nicolas-Colombier/SuperMod-Server-Template/blob/main/ServerConfig/ServerMessages.cfg) → Edit your server messages
- [License.cfg](https://github.com/Nicolas-Colombier/SuperMod-Server-Template/blob/main/ServerConfig/License.cfg) → Add your server license
- [Rcon.cfg](https://github.com/Nicolas-Colombier/SuperMod-Server-Template/blob/main/ServerConfig/Rcon.cfg) → Edit your Rcon port, password, configuration, etc...

<br>

## Levels/Layers for map voting *(NOT WORKING)*
- [VoteConfig.cfg](https://github.com/Nicolas-Colombier/SuperMod-Server-Template/blob/main/ServerConfig/VoteConfig.cfg)  → Specify your map vote configuration such as, the amount of layers, faction selection, game modes, mode redundancy, etc...
- [ExcludedLayers.cfg](https://github.com/Nicolas-Colombier/SuperMod-Server-Template/blob/main/ServerConfig/ExcludedLayers.cfg) → Specify the layers you do not want to be part of your map vote pool. We recommend to exclude broken layers if you find any and follow our configuration to avoid weird matchup.
- [ExcludedLevels.cfg](https://github.com/Nicolas-Colombier/SuperMod-Server-Template/blob/main/ServerConfig/ExcludedLevels.cfg) → Specify the Level id that you do not want to be part of your map vote pool. We recommend to exclude broken levels.
- [ExcludedFactions.cfg](https://github.com/Nicolas-Colombier/SuperMod-Server-Template/blob/main/ServerConfig/ExcludedFactions.cfg) → 
Specify the factions you do not want to be part of your map vote pool. We recommend to exclude factions that are not ready for LIVE play.
- [LayerVoting.cfg](https://github.com/Nicolas-Colombier/SuperMod-Server-Template/blob/main/ServerConfig/LayerVoting.cfg) → Specify the layers you would like to have in your map vote pool. We recommend to put the big layers such as AAS, RAAS, INV.
- [LayerVotingLowPlayers.cfg](https://github.com/Nicolas-Colombier/SuperMod-Server-Template/blob/main/ServerConfig/LayerVotingLowPlayers.cfg) → Specify the low population layers you would like to have in your map vote pool. We recommend to put small maps, Skirmish and Seed layers.
- [LayerVotingNight.cfg](https://github.com/Nicolas-Colombier/SuperMod-Server-Template/blob/main/ServerConfig/LayerVotingNight.cfg) → Specify the layers you would like to have in your map vote pool when it's nighttime. We recommend to put small maps, Skirmish and Seed layers as well.
- [_ServerWithVotemap.cfg](https://github.com/Nicolas-Colombier/SuperMod-Server-Template/blob/main/ServerConfig/_ServerWithVotemap.cfg) → Copy this configuration into Server.cfg if you want to have votemap instead of layer rotation 

<br>

## Levels/Layers for standard rotation
- [_SuperModLayerTemplate.cfg](https://github.com/Nicolas-Colombier/SuperMod-Server-Template/blob/main/ServerConfig/_SuperModLayerTemplate.cfg) → The entire SuperMod Layer list. Feel free to pick your layers from this configuration file.
- [_SuperModLevelTemplate.cfg](https://github.com/Nicolas-Colombier/SuperMod-Server-Template/blob/main/ServerConfig/_SuperModLevelTemplate.cfg) → The entire SuperMod Level list. Feel free to pick your levels from this configuration file. (WIP)
- [LayerRotation.cfg](https://github.com/Nicolas-Colombier/SuperMod-Server-Template/blob/main/ServerConfig/LayerRotation.cfg) → Specify which layer you would like to add or remove from the layer rotation.
- [LevelRotation.cfg](https://github.com/Nicolas-Colombier/SuperMod-Server-Template/blob/main/ServerConfig/LevelRotation.cfg) → Specify which level you would like to add or remove from the map rotation. (WIP)

<br>

## Miscellaneous
- Steam Mod ID : ****
- Steam Workshop URL : ****
- Make sure to copy these files into the proper directory ! If you have any questions, feel free to create an issue or contact me on Discord : **nom4de**.

<br>

## SquadSDM
If you need a discord bot to manage your LinuxGSM server, check out [SquadSDM](https://github.com/Nicolas-Colombier/SquadSDM)
