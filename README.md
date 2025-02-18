
# Stupid Scripts
This is a roblox script thing that has dumb items for troll guis and stuff.

Heres the code to run it:

> [!IMPORTANT]
> Goto ServerScriptService and turn LoadStringEnabled on and HTTP Requests in settings on or it wont work.
> 
> Please get this model for some scripts to work: https://create.roblox.com/store/asset/104493384543001

```
local HttpService = game:GetService("HttpService")

-- Edit these

local Script = "Russian Roulette"
local Player = "Display Name (Can be shortened)"

-- Run

local Code = HttpService:GetAsync("https://raw.githubusercontent.com/coolguyandstuffyeah/Stupid-Scripts/refs/heads/main/" .. Script, true)
local Run = loadstring('local PlrScriptName = "' .. Player .. '"\n' .. Code)

Run()
```

> [!NOTE]
> If you wanna make a suggestion or something you can message me on [Roblox](https://www.roblox.com/users/2468233048/profile) or [Discord](https://discord.gg/G5ecdP5E)

> <sub>The owner of the discord server is the person you need.</sub>

# Future
Heres things that will be added in the future.
- PvZ
- Zombies
- Pokemon
- Bees
- Lemonade Stand
- Infection
> [!TIP]
> I am currently working on "Zombies". Its probably gonna be done in a week.
# Credits

***If your gonna use these give me credit for it (Eg: Script by Hihipie2ndBan)***
> [!WARNING]
> If most troll guis and stuff dont credit me for it, I wont make it open source and I will add a very obvious credit caption you cant remove.
# Other

`HTTP 404 (Not Found)` most of the time means the script you tried running dont exsist.

Most of the time local scripts cannot use these scripts.

Please notify me if theres an error in a script.
