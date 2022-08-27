local VLib = loadstring(game:HttpGet("https://raw.githubusercontent.com/vep1032/VepStuff/main/VL"))()

local s = VLib:Window("Nut x HUB", "All map", "N")

-- main

local ss = s:Tab("Main")

ss:Button("Infinite Yield",function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
end)

ss:Button("CMD-X",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/CMD-X/CMD-X/master/Source",true))()
end)


ss:Slider("WalkSpeed",16,100,70,function(t)
game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = (t)
end)

ss:Button("FPS boost",function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/Ncspgg/Fps-boost-v2/main/README.md'),true))()
end)

ss:Button("Free cam(shift+f9)",function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/ncsp555gg/Freecam/main/README.md'),true))()
end)

ss:Button("RTX",function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/ncsp555gg/RTX/main/README.md'),true))()
end)

-- Blox fruits

local ss = s:Tab("Blox fruits")


ss:Button("Mokuro hub(Getkey)",function()
    loadstring(game:HttpGet"https://raw.githubusercontent.com/xQuartyx/DonateMe/main/ScriptLoader")()
end)


ss:Button("Ren hub",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/xZPUHigh/swswsw/main/ren.lua"))()
end)


ss:Button("Hulk u hub",function()
    loadstring(game:HttpGet"https://raw.githubusercontent.com/HULKUexe/-FreeUScript-/main/3GAME")()
end)

-- King legacy

local ss = s:Tab("King legacy")


ss:Button("Strike hub",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Strikehubv2z/StormSKz/main/All_in_one"))()
end)


ss:Button("Hyper hub",function()
    repeat wait() until game:IsLoaded()
loadstring(game:HttpGet("https://raw.githubusercontent.com/DookDekDEE/Hyper/main/script.lua"))()
end)


ss:Button("Hulk u hub",function()
    loadstring(game:HttpGet"https://raw.githubusercontent.com/HULKUexe/-FreeUScript-/main/3GAME")()
end)

-- The mimic

local ss = s:Tab("The mimic")


ss:Button("KTollT",function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/KTollT/KTollT/main/README.md'))()
end)

-- Bed wars

local ss = s:Tab("Bed wars")


ss:Button("Vape V4",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/7GrandDadPGN/VapeV4ForRoblox/main/NewMainScript.lua", true))()
end)


-- Murder Myster2

local ss = s:Tab("Murder mystery2")

ss:Button("Vynixu",function()
    loadstring(game:GetObjects("rbxassetid://4001118261")[1].Source)()
end)


-- All star

local ss = s:Tab("All star")

ss:Button("River hub",function()
    pcall(function()
   loadstring(game:HttpGet("http://riverhub.xyz/" .. tostring(game.PlaceId) .. ".lua"))()
end)
end)

-- Driving empire

local ss = s:Tab("Driving Empire")

ss:Button("Midnight hub",function()
end)

ss:Button("WindyWare",function(    loadstring(game:HttpGet("https://raw.githubusercontent.com/GodXNation/GodXNation/main/midnight%20racing%20hubV2%20fixed", true))()
)
    loadstring(game:HttpGet("https://raw.githubusercontent.com/WindyKung/WindyWare/main/MainScript/DrivingEmpire.lua"
end)

