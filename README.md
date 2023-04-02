
local cilentid = game:GetService("RbxAnalyticsService"):GetClientId()

local hwid = {
   [1] = "6614098F-3E8D-4402-9AD2-E5EA5AE06F06",
   ["6614098F-3E8D-4402-9AD2-E5EA5AE06F06"] = 1,
   [2] = ""
   [""] = 2,

}
local key = {
    [1] = "Oxegen-Nextgen"
    [2] = "Test01"

}

local keynum = hwid[cilentid]
if hwid[keynum] == cilentid then
    if key[keynum] == _G.Key then
        loadstring(game:HttpGet("https://raw.githubusercontent.com/dukdik234/Bruhhhh/main/README.md"))()
    else
        game.Players.LocalPlayer:kick("Not have key")
   end
else
    game.Players.LocalPlayer:kick("Not have Hwid")
end
