# Kyo!: Global Matchmaking Queue (1.0)

A very easy to use (plug-n-play) roblox global matchmaking queue system

<br><br>
## Overview
Kyo! doesn't use any third party services. 

<br><br>
## How to use?
1. Download Kyo! from releases page
2. Import Kyo! file package to your project
3. Set Kyo! configurations based on your game needs
   
   <img width="161" height="204" alt="image" src="https://github.com/user-attachments/assets/193d3759-cc62-4fd5-8d35-4c74c6e4aa06" />

<br>

**Done! Now check the usage example below**


<br><br>

## Example usage:
```lua
-- ServerScript
local Kyo = require(game.ReplicatedStorage.Packages["Kyo!"]["Kyo!"])

Kyo.Initialize() -- Initialize Kyo! first

Kyo.Join(player.UserId) -- This will add player to the queue
Kyo.Leave(player.UserId) -- This will remove player from the queue

```

---
## 
