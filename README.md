local key = _G.Key
local check = "https://legazyxhub.000webhostapp.com/check.php?key=" .. key
if game:HttpGet(check) == "Whitelisted" then
loadstring(game:HttpGet("https://legazyxhub.000webhostapp.com/script.lua"))()
else
game.Players.LocalPlayer:Kick("คีย์มันไม่ถูกไอควาน จะรันหาพ่องมึงอ่ะ")
end
