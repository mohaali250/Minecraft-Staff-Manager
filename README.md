# StaffManager
> Copyright (c) 2026 moha_ali250 (Github: mohaali250)

> Licensed under the PolyForm Noncommercial License 1.0.0

> See the LICENSE file for details.

This is a mini plugin powered by Pyspigot that helps you with managing staff in your server

## Features:
* You can promote players for different ranks
* You can moderate staff with /suspend, /demote and /staffban
* (Optional) A Auto ban system that works with grimAC (Please dont use this if your server is usually laggy)
* Togglable way in the config to require discord link
* You can check the list of current staff, and individual ranks with /status list
* a /punish command that depending on the categories inputted will do the punshments set up in the `definitions.yml`
* This plugin is designed to not interfere with the ranks not written in `definitions.yml`, so if it does (report a bug)[]

## Data Usage

StaffManager does **not** collect or transmit any player or server data over the internet.

The plugin reads information that already exists on your server in order to function, including:

* LuckPerms groups (for managing staff roles).
* Minecraft player statistics, such as playtime (`Statistic.PLAY_ONE_MINUTE`).
* Discord account links (only if DiscordSRV is installed).
* Anti-cheat violations (only if GrimAC is installed).

This information is used only while the plugin is running and is stored locally in `staff.json` when necessary. No information is sent to external servers, analytics services, or the plugin author.
  
## Requires:
* Pyspigot 0.9.1
* A Minecraft software based on bukkit
* LuckPerms
* (Optional) Grim anticheat. if you want less hackers
* (Optional) DiscordSRV. if you want players to link their accounts before getting promoted

## Recommended to do before using the plugin:
* Download (LuckPerms)[https://modrinth.com/plugin/luckperms] and (PySpigot)[https://modrinth.com/plugin/pyspigot/version/0.9.1] and start the server once
* On the ZIP file downloaded, after extracted, put `staffmanager.py` in `/plugins/Pyspigot/scripts/`
* Go to `definitions.yml` to add your punish categories, or additional ranks. 

Note: I do not own PySpigot source code, nor ownership, what are you seeing on screen is a "Mini-Plugin" powered by pyspigot, Same goes for LuckPerms
