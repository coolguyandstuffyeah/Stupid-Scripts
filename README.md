# Stupid Scripts
This is a roblox script thing that has dumb items for troll guis and stuff.

Heres the code to run it:

> [!IMPORTANT]
> Goto ServerScriptService and turn LoadStringEnabled on or it wont work.
> 
> Please get this model for some scripts to work: https://create.roblox.com/store/asset/104493384543001

```
local HttpService = game:GetService("HttpService")

-- Edit these

local Script = "Life-Simulator"
local Player = "DISPLAY NAME HERE"

-- Run

local Code = HttpService:GetAsync("https://raw.githubusercontent.com/coolguyandstuffyeah/Stupid-Scripts/refs/heads/main/" .. Script, true)
local Run = loadstring('local PlrScriptName = "' .. Player .. '"\n' .. Code)

Run()
```

> [!NOTE]
> If you wanna make a suggestion or something you can message me on [Roblox](https://www.roblox.com/users/2468233048/profile) or [Discord](https://discord.gg/G5ecdP5E) <sub>The owner of this server is the person you need.</sub>

# Future
Heres things that will be added in the future.
- PvZ
- Zombies
- Slime
- Doge
- Pokemon
- Chloroform Cloth
- Russian Roulette
- Bees
- Lemonade Stand
- That infection puddle furry thing
- Basically this: https://www.youtube.com/shorts/ys99kraxiE4
> [!TIP]
> I am currently working on russian roulette. It will probably be done in less then 2 weeks.
# Credits

***If your gonna use these give me credit for it (Eg: Script by Hihipie2ndBan)***
> [!WARNING]
> If most troll guis and stuff dont credit me for it, I wont make it open source and I will add a very obvious credit caption you cant remove.
# Other

`HTTP 404 (Not Found)` most of the time means the script you tried running dont exsist.

Most of the time local scripts cannot use these scripts.

Please notify me if theres an error in a script.
