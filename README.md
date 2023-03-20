
local Key = {
    "abc"
}
local Hwid = {} 
local H = game:GetService("RbxAnalyticsService"):GetClientId()
if _G.Key == Key[table.find(Key,_G.Key)] then
    print("Sucsees")
    table.insert(Hwid,H)
else
    game.PLayers.LocalPlayer:Kick("Invild Key")
end
if H ~= Hwid[table.find(Hwid,H)] then
    game.PLayers.LocalPlayer:Kick("Invild Hwid")

else
    loadstring(game:HttpGet("https://raw.githubusercontent.com/dukdik234/Bruhhhh/main/README.md"))()
end
