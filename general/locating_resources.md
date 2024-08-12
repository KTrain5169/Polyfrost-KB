---
description: How to find every resource you will need to debug something.
---

# Locating resources

## Logs

For the sake of simplicity, please refer to the [Types of logs](types-of-logs.md) page for instructions on how to find logs.

## .minecraft folder

The .minecraft launcher is where most user-facing things needed to run Minecraft or produced by Minecraft are found. These include mods and their config folders, Minecraft's options.txt, CTJS modules, and more are found.

<details>
<summary>Where to find .minecraft folder (Windows):</summary>
Assuming locations aren't changed:

* Minecraft Launcher: `%appdata%/.minecraft/`
* SkyClient (Minecraft Launcher): `%appdata%/.minecraft/skyclient/`
* Prism Launcher: `%appdata%/PrismLauncher/instances/(instance name)/.minecraft/`
* Modrinth: `%appdata%/com.modrinth.theseus/profiles/(profile name)/`

</details>

<details>
<summary>Where to find .minecraft folder (Mac):</summary>
Assuming locations aren't changed:

* Minecraft Launcher: `~/Library/Application Support/Minecraft`
* SkyClient (Minecraft Launcher): `~/Library/Application Support/Minecraft/skyclient`
* Prism Launcher: `~/Library/Application Support/PrismLauncher/instances/(instance name)/.minecraft`
* Modrinth: `~/Library/Application Support/com.modrinth.theseus/profiles/(profile name)/`

</details>

Linux users are expected to know where their .minecraft folder is.
