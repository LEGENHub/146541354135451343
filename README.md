local key = _G.Key
local check = "https://raw.githubusercontent.com/LEGENHub/chack/main/README.md?key=" .. key
if game:HttpGet(check) == "Whitelisted" then
loadstring(game:HttpGet("https://raw.githubusercontent.com/LEGENHub/Legendary-ok/main/README.md"))()
else
game.Players.LocalPlayer:Kick("เอ้าคีย์ผิดไอ่น้อง")
end
