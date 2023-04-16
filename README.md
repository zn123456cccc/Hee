local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()

local Window = OrionLib:MakeWindow({Name = "blackhub", HidePremium = false, lntroText = "Goldenhub", SaveConfig = true, ConfigFolder = "OrionTest"})

local Tab = Window:MakeTab({

	Name = "Infinite Rarities",	Icon = "rbxassetid://4483345998",

	PremiumOnly = false

})

OrionLib:MakeNotification({

	Name = "Farm",

	Content = "ขอให้สนุก🥰",

	Image = "rbxassetid://4483345998",

	Time = 5

})

Tab:AddButton({

	Name = "วาร์ปไปสุ่ม",

	Callback = function()

      	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-0.6383663415908813, 2.9999992847442627, 39.42439651489258)

  	end    

})

Tab:AddButton({

	Name = "วาร์ปไปแลก",

	Callback = function()

      	 game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(39.70299530029297, 2.9999992847442627, 39.242130279541016)

  	end    

})

Tab:AddButton({

	Name = "วาร์ปแลกโชค",

	Callback = function()

      	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(39.1116828918457, 2.9999992847442627, 27.207271575927734)

  	end    

})

OrionLib:Init()
