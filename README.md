local key = _G.Key
local check = "https://kakhub.000webhostapp.com/check.php?key=" .. key
if game:HttpGet(check) == "Whitelisted" then
loadstring(game:HttpGet("https://raw.githubusercontent.com/KAKXHUB/KAK-X-HUB/main/README.md"))()
else
game.Players.LocalPlayer:Kick("ไม่มีคีย์ยังใช้อีกหรอไวรุ่น")
end
