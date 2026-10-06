# Kyo!: Global Matchmaking Queue
A reusable cross-server matchmaking library for Roblox games.

<br><br>
## Overview
**Kyo!** is a plug-and-play matchmaking module built entirely with Roblox's native APIs, requiring no third-party services or external dependencies. It provides a simple and reusable solution for implementing cross-server matchmaking in Roblox games.


<br><br>
## How to use?
1. Download Kyo! from the releases page.
2. Import Kyo! file package to your project.
3. Set Kyo! configuration values based on your game needs.
   
   <img width="161" height="204" alt="image" src="https://github.com/user-attachments/assets/193d3759-cc62-4fd5-8d35-4c74c6e4aa06" />


4. Don't forget to enable studio access to API services in security settings.
<br>
   
**Done! Now check the usage example below.**


<br><br>

## Usage Exmaple:
```lua
-- ServerScript
local Kyo = require(game.ReplicatedStorage.Packages["Kyo!"]["Kyo!"])

Kyo.Initialize() -- Initialize Kyo! first

Kyo.Join(player.UserId) -- This will add player to the queue
Kyo.Leave(player.UserId) -- This will remove player from the queue

```

---
## 
