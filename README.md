local PabloLib = loadstring(game:HttpGet("https://raw.githubusercontent.com/BatuKvi123/PabloLibV3/main/PabloLibV3"))()
local window = PabloLib:Create("Exploiters Library By Unlimited!")

---Tabs---

local tab1 = window:CreateTab("Admin")

---buttons---

tab1:CreateButton("Infinite Yield", function()
("loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
end)

tab1:CreateTextbox("Change Speed", function(a)
game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = a
print(a)
end)

tab1:CreateTextbox("Change Jump Power", function(a)
game.Players.LocalPlayer.Character.Humanoid.JumpPower = a
print(a)
end)

---WARNING---

tab1:CreateWarning("This is not cool")
