
# Bugsy - By stefpower1

Bugsy is a customised version of the discord.js debugging tool "dokdo". 


![Logo](https://cdn.discordapp.com/attachments/1194329440663126138/1247900539572977815/Bugsy_banner.png?ex=6661b571&is=666063f1&hm=f8e765e79a4af26dfd232da3b2f4d692a6e51bbafad3d6786e9ac9bcb7714c91&)


# Installation

### Install bugsy using the existing Hexalon-bot structure
[![Hexalon Discord Bot](https://img.shields.io/badge/Hexalon-5FB4CC.svg?&logo=github)](https://github.com/hexalon-discord/hexalon)
*This will install Bugsy automatically*

```bash
git clone https://github.com/hexalon-discord/hexalon.git
node src/index.js OR node sharder.js 
```
### Custom file structure 
```bash
cd your-bot/node_modules
git clone https://github.com/hexalon-discord/bugsy
```   
### Automatic version control
*This is intregrated in the Hexalon source code, you can do this yourself by adding the script located in "Extras" to your index.js or sharder.js file.*

## Customisation
You can customize Bugsy to your own liking using a "bugsy-config.json" file. You can enable/disable commands, add emojis, change file locations, etc.

#### Example values

| Setting    | Value                                                              |
| ---------- | ------------------------------------------------------------------ |
| Emojis | <"emoji-name":"emoji-id"> |
| Color | ![#2B2D31](https://via.placeholder.com/10/2B2D31?text=+) #2B2D31 |
| Enabled | true|


### Notes

Bugsy will need a data folder to find errors in. This will default to "your-bot/data/logs", you can customize this in the "bugsy-config.json" file.

