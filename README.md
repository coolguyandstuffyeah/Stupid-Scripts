# Stupid-Scripts
This is a roblox script thing that has really funny items for troll guis and stuff.

Heres the code to run it. (ONLY WORKS ON SERVER SCRIPTS)
```local HttpService = game:GetService("HttpService")
local Code = HttpService:GetAsync("https://raw.githubusercontent.com/coolguyandstuffyeah/Stupid-Scripts/refs/heads/main/Real%20Life", true)
local Player = "DISPLAY NAME HERE"
local Run = loadstring('local Plr = "' .. Player .. '"\n' .. Code)
Run()```
