# 🌟 OKROSHKA SERVER ENGINE (Java & Bedrock Server Build)

Welcome to the official repository of the **OKROSHKA SERVER ENGINE** project!

This is a ready-to-use, clean, and fully optimized Minecraft server build designed for a quick launch of your game world. This build is created to seamlessly connect PC players (Java Edition) and mobile/tablet players (Bedrock/Pocket Edition) in one cozy world without lags, complicated setups, or tedious port forwarding. It is pre-configured to support any cracked launchers without requiring an Xbox/Microsoft account login.

---

## 🛠️ Features & Pre-installed Plugins

The server core comes with top-tier plugins already installed and configured:
*   **Geyser-Spigot** — Provides a seamless connection to the server for mobile devices and consoles.
*   **ViaVersion** — Allows players to join the server using game versions newer than the server core itself.
*   **ViaBackwards** — Ensures backward compatibility, allowing players to join from older versions of Minecraft.
*   **SkinRestorer** — Restores and displays player skins, even if everyone is playing on cracked launchers.

---

## 🚀 How to Launch the Server in 5 Seconds

1. Download this repository by clicking the green **Code -> Download ZIP** button and unpack the `MineServer` folder anywhere you like (e.g., to your Desktop).
2. Make sure you have the latest version of **Java** installed on your computer.
3. Simply double-click the **`start.bat`** file inside the folder.
4. A console window will open, the startup lines will run, and once you see the `Done!` message, your server is ready to play!

---

## ⚙️ How to Customize Your Server

You can easily change all server settings using Notepad. Open the **`server.properties`** file and edit the necessary lines:

### 🌍 1. Setting Up Your Custom Seed
Find the line `level-seed=` and enter any seed you want to generate:
```properties
level-seed=2422215857861955386
```
*If you leave this line completely empty, Minecraft will automatically generate a random and unique world on its very first launch!*

### 🎮 2. Default Game Mode
Find the line `gamemode=` and specify the desired mode for new players:
*   `survival` — Survival Mode (set by default)
*   `creative` — Creative Mode

### ⚔️ 3. Changing Difficulty
Find the line `difficulty=` and specify the threat level of monsters:
*   `peaceful` — Peaceful Mode
*   `normal` — Normal Mode (set by default)
*   `hard` — Hard Mode

### 🎒 4. Keeping Inventory on Death
To ensure players don't lose their hard-earned resources, inventory saving is enabled by default. This is handled by the following line:
```properties
gamerule.keepInventory=true
```

### 🖥️ 5. Advanced Console Interface (Optional)
If you prefer a clean graphical dashboard instead of a blank black CMD window, you can run the server via a custom Python panel:
1. Make sure **Python** is installed on your PC.
2. Double-click the **`manager.pyw`** file inside the server folder.
3. Click the green **RUN SERVER** button in the center. The button will disappear, the server logs will stream inside the app, and a convenient admin command input box will appear at the bottom!

---

## 💻 Full Console Command Reference (Admin Guide)

You can type these commands directly into your server console text field (without the `/` prefix) or right inside the game chat (with the `/` prefix if you have Operator rights) [5].

### 👑 1. Rights & Access Management
*   `op <player_name>` — Grant a player administrator rights (gives access to all commands in-game) [5].
*   `deop <player_name>` — Revoke a player's administrator rights [5].
*   `whitelist add <player_name>` — Add a player to the server whitelist.

### 🚫 2. Moderation & Bans
*   `kick <player_name> [reason]` — Forcefully disconnect a player from the server.
*   `ban <player_name> [reason]` — Permanently ban a player from the server [5].
*   `pardon <player_name>` — Unban a player [5].

### 🔮 3. Live Gameplay Management
*   `gamemode survival [player]` — Switch a player's game mode to Survival [5].
*   `gamemode creative [player]` — Switch a player's game mode to Creative [5].
*   `difficulty <peaceful/easy/normal/hard>` — Instantly change the server difficulty.
*   `time set <day/night>` — Change the time of day in the world.
*   `weather <clear/rain/thunder>` — Change the weather (clear skies, rain, or a thunderstorm).

### 🎒 4. Teleportation, Items & Effects
*   `tp <player_1> <player_2>` — Teleport Player_1 to Player_2's location.
*   `tp <player> <X> <Y> <Z>` — Teleport a player to exact coordinates in the world.
*   `give <player> <item> [amount]` — Spawn any block or item from thin air (e.g., `give @a elytra 1` to give elytra to everyone).
*   `effect give <player> <effect> [duration]` — Infuse a player with a superpower (e.g., `effect give @s night_vision 9999` for permanent night vision).

### 💾 5. Server Maintenance & Shutdown
*   `save-all` — Forcefully save the current world state, all player builds, and inventories to the hard drive.
*   `stop` — **The most important command**. It correctly saves all chunks, blocks, inventories, and safely shuts down the server [5]. *Always close your server using this command to prevent world file corruption!* [5]

---

## 🌎 License & Credits

*   **Project Author**: `0KR0$HK4`
*   **License**: This project is completely **Open Source** and **free of any copyright restrictions**.

You have the absolute and unconditional right to download this build, modify any configuration or code files for your needs, use it to play with friends and family, as well as copy, re-release, or distribute it on the internet without any limitations or royalties to the author!

---
*Have fun playing and have great adventures in the world of OKROSHKA ENGINE! 🎮💎⛏️*
