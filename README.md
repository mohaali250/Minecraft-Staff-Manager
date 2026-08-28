# StaffManager

> Copyright © 2026 moha_ali250 (GitHub: mohaali250)  
> Licensed under the PolyForm Noncommercial License 1.0.0  
> See the LICENSE file for details.

StaffManager is a lightweight staff management plugin. It provides tools for managing staff ranks, punishments, and player moderation in a configurable way.

### BEFORE USING STAFFMANAGER
It is highly encouraged that you take your time to read `config.yml` and `definitions.yml`, because the default configuration is supposed to make the first run experience smooth, but it might not fit your server current setup or even lead to unexpected behaviours.

## Features

- Promote and manage players across configurable staff ranks.
- Moderate staff using `/suspend`, `/demote`, and `/staffban`.
- Staff ranks use playtime-based requirements defined in `definitions.yml`.
- Optional Discord account linking via DiscordSRV.
- View staff members and ranks with `/listplayers`.
- `/punish` command applies structured punishments defined in `definitions.yml`.
- Compatible with existing LuckPerms groups explicitly defined in `definitions.yml`.

If you find a bug, please report it here:  
[https://github.com/mohaali250/Minecraft-Staff-Manager/issues](https://github.com/mohaali250/Minecraft-Staff-Manager/issues)

## Requirements

- Bukkit / Paper / Spigot server
- LuckPerms

Optional:
- DiscordSRV

## Installation

1. Install [LuckPerms](https://modrinth.com/plugin/luckperms) and start the server once.
2. When you have the jar, place it in `/root/plugins`
3. Restart or reload the server.
4. Review and edit the configuration `config.yml` and the definitions `definitions.yml`. (This step is important)

