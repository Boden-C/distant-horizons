<img src="https://gitlab.com/distant-horizons-team/distant-horizons-core/-/raw/main/_Misc%20Files/logo%20files/new/SVG/Distant-Horizons-M.svg" height="256px">

# LOD files for Distant Horizons
LOD files of many popular maps for Distant Horizons alpha 2.1+

## Where to place it
**Single Player:** 
- Overworld: `.minecraft/saves/WORLD_NAME/data/DistantHorizons.sqlite` 
- Nether: `.minecraft/saves/WORLD_NAME/DIM-1/data/DistantHorizons.sqlite`
- End: `.minecraft/saves/WORLD_NAME/DIM1/data/DistantHorizons.sqlite`
- Custom Dimensions: `.minecraft/saves/WORLD_NAME/DIMENSION_FOLDER/data/DistantHorizons.sqlite`

**Multiplayer:**
- `.minecraft/Distant_Horizons_server_data/SERVER_NAME/`

## Downloads
| World | World Version | DH Version | Download | Comments | Download Version |
| --- | --- | --- | --- | --- | --- |
| [Wynncraft](https://wynncraft.com/) | 2.1 Bonfire | a2.1+ | [DOWNLOAD](../..//releases/tag/wynn1.2) | Based on [Throwneb's files](https://forums.wynncraft.com/threads/distant-horizons-v2-lod-files-for-wynncraft-map.315647/) updated to DH a2.1, use their post for instructions | wynn1.2
| [Drehmal](https://www.drehmal.net/) | 2.2 Apotheosis | a2.1+ | [DOWNLOAD](https://drive.usercontent.google.com/download?id=1Sb9k6IC0z-qu6gNy28mX8cEyvjd_ovQr&export=download&authuser=0) | Provided by Kofi on Drehmal Discord | external
| [Middle Earth](https://www.mcmiddleearth.com/) | Jul 2024 | a2.1+ | [DOWNLOAD](https://www.mcmiddleearth.com/community/resources/distant-horizons-base.170/download) | [Instructions](https://www.mcmiddleearth.com/community/resources/distant-horizons-lods.171/) Provided by Feuerdrache0 | external

<br><br><br>

# Bobby Files/World Download

## Where to place it
`.minecraft/.bobby/NAME`

## How to download the world
Bobby saves entire `.mca` chunk files, meaning a complete Bobby folder functions as a full world download.
1. Create an empty void world (use the custom preset)
2. Go to `.minecraft/saves/WORLD_NAME/`
- The Overworld is `WORLD_NAME/region`
- The Nether is `WORLD_NAME/DIM-1/region`
- The End is `WORLD_NAME/DIM1/region`
- Custom Dimensions is `WORLD_NAME/DIMENSION_FOLDER/region`
2. Within the .bobby folder and the relevant name, you will see the dimensions. Copy them to their respective region folders.
  You should be copying `.mca` files to where `.mca` files are. (For Wynncraft, you should only need to copy overworld.)

## Downloads
| World | World Version | Download | Comments | Download Version |
| --- | --- | --- | --- | --- |
| [Wynncraft](https://wynncraft.com/) | Constantly Updated | [DownGit Download](https://downgit.github.io/#/home?url=https://github.com/Wynncraft-Overhaul/majestic-overhaul/tree/immersive/.bobby/play.wynncraft.com/0/minecraft) | Olinus maintains [Wynncraft Majestic Overhaul](https://github.com/Wynncraft-Overhaul/majestic-overhaul) modpack, which contains updated [Bobby Files](https://github.com/Wynncraft-Overhaul/majestic-overhaul/tree/immersive/.bobby/play.wynncraft.com/0/minecraft). Unfortuantely, GitHub does not support directory downloads, so this uses a third party. If that breaks, download the entire modpack [here](https://github.com/Wynncraft-Overhaul/majestic-overhaul/archive/refs/heads/immersive.zip). | external

<br>

# Contribution

Contributions are welcome and encouraged! If you have the LOD files for an SMP, custom maps, servers, or anything popular, make an [issue](../../issues), and I'll add it.
