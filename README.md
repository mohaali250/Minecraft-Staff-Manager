# StaffManager

> Copyright © 2026 moha_ali250 (GitHub: mohaali250)  
> Licensed under the PolyForm Noncommercial License 1.0.0  
> See the LICENSE file for details.

StaffManager is a lightweight staff management plugin powered by PySpigot. It provides tools for managing staff ranks, punishments, and player moderation in a configurable way.

## Features

- Promote and manage players across configurable staff ranks.
- Moderate staff using `/suspend`, `/demote`, and `/staffban`.
- Staff ranks use playtime-based requirements defined in `definitions.yml`.
- Optional automatic anti-cheat punishment support via GrimAC.
- Optional Discord account linking via DiscordSRV.
- View staff members and ranks with `/status list`.
- `/punish` command applies structured punishments defined in `definitions.yml`.
- Compatible with existing LuckPerms groups explicitly defined in `definitions.yml`.

If you find a bug, please report it here:  
[https://github.com/mohaali250/Minecraft-Staff-Manager/issues](https://github.com/mohaali250/Minecraft-Staff-Manager/issues)

## Data Usage

StaffManager does **not** collect or transmit any player or server data over the internet.

The plugin only reads data already available on your server, including:

- LuckPerms groups (staff roles)
- Minecraft player statistics such as playtime (`Statistic.PLAY_ONE_MINUTE`)
- Discord account links (if DiscordSRV is installed)
- Anti-cheat violations (if GrimAC is installed)

All data is stored locally in `staff.json` when needed. No data is sent to external services or the plugin author.

Regular backups of `staff.json` are recommended, as data corruption or logic bugs may occur.

## Requirements

- PySpigot 0.9.1+
- Bukkit / Paper / Spigot server
- LuckPerms

Optional:
- GrimAC
- DiscordSRV

## Installation

1. Install [PySpigot](https://modrinth.com/plugin/pyspigot/version/0.9.1) and [LuckPerms](https://modrinth.com/plugin/luckperms) and start the server once.
2. Place `staffmanager.py` into `/plugins/PySpigot/scripts/`
3. Restart or reload the server.
4. Edit `definitions.yml` to configure ranks and punishments.

## Notes

This plugin is powered by PySpigot. It is not affiliated with or endorsed by PySpigot, LuckPerms, DiscordSRV, or GrimAC.
