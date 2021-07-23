# KygekRanksUI

<a href="https://poggit.pmmp.io/p/KygekRanksUI"><img src="https://poggit.pmmp.io/shield.dl.total/KygekRanksUI"></a>
[![Discord](https://img.shields.io/discord/735439472992321587.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://discord.gg/CXtqUZv)

**PM4 BRANCH WARNING: This plugin branch is currently under development. There might be some major bugs. If you found one, please [submit an issue](https://github.com/KygekTeam/KygekRanksUI/issues).**

A PocketMine-MP plugin that shows information about ranks in the server. You can provide ranks features, prices and contact details. This is a plugin that showcases ranks that can be purchased via staffs/websites. This is not a plugin for setting up purchaseable ranks using in-game money.

# Features

- Unlimited ranks lists
- Missing config file detection
- Config file can be reset
- Show player name (`{player}`)
- Supports `&` as formatting codes
- Supports images beside ranks buttons (links and texture packs)
- Change command description to suit your server
- Supports command aliases
- Enable/disable ranks form to go back to main form when pressing the X button
- Automatic plugin updates checker

# How to Install

1. Download the latest version (It is recommended to always download the latest version for the best experience, except you're having compatibility issues).
2. Place the `KygekRanksUI.phar` file into the `plugins` folder.
3. Restart the server.
4. Done!

# Commands & Permissions

| Command | Default Description | Permission | Default |
| --- | --- | --- | --- |
| `/ranks` | Information about ranks in the server | `kygekranksui.ranks` | true |

Command description can be changed in `config.yml`. You can also add command aliases in `config.yml`.

Use `-kygekranksui.ranks` to blacklist the `/ranks` command permission to groups/users in PurePerms.

# Upcoming Features

- Currently none planned. You can contribute or suggest for new features.

# Additional Notes

- <a href="https://github.com/KygekDev/default-textures">Visit KygekDev's repo</a> for a list of Minecraft Bedrock default texture pack library (for references only) if you want to use texture packs for button image.
- Join the Discord <a href="https://discord.gg/CXtqUZv">here</a> for latest updates from KygekTeam.
- If you found bugs or want to give suggestions, please visit <a href="https://github.com/KygekTeam/KygekRanksUI/issues">here</a> or DM KygekDev#6415 via Discord.
- We accept any contributions! If you want to contribute please make a pull request in <a href="https://github.com/KygekTeam/KygekRanksUI/pulls">here</a>.
