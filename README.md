# JavaGen
JavaGen is a PocketMine-MP plugin that provides a fast way to generate the Minecraft **Vanilla terrain** (all dimensions) based on a Java Server

Depending on the biome height, the generation per chunk took from 0.03 to 0.1 seconds during the tests.

The speed of the generator may be influenced by the available hardware power.

## Ingame footage
- ### A beautiful landscape in the jungle
![Landscape](https://i.imgur.com/RBkyyI0.png)

- ### A deep look in the underground
![AncientCity](https://i.imgur.com/yNS9MiQ.png)

- ### A landscape in the nether
![Landscape Nether](https://i.imgur.com/PZjCioP.png)

- ### A very scary place in the nether
![Bastion](https://i.imgur.com/GcyA7TK.png)

- ### "The City at the End of the Game"
![End City](https://i.imgur.com/TBOnOhU.png)

## Features
- Full generation of the vanilla terrain in all dimensions (overworld, nether and the end)
- Generation of vanilla-like chest loot
- /locate command to locate biomes and structures close by
- An API for interaction with structures
- Fully configurable messages (for the locate command)

## Known issues
- Missing blocks and items in PocketMine-MP will NOT be generated in the world
- Weird sky color in nether and end dimension
- Java server must be on the same machine as the pocketmine server

## Requirements
You need 
 - [PocketMine-MP API-5](https://github.com/pmmp/PocketMine-MP/releases/lastest)
 - a java server, preferably a spigot server (everything was tested on a [Paperspigot](https://papermc.io/downloads/paper) server, version 1.20.4))

## Any problems or ideas?
Feel free to open an issue on github