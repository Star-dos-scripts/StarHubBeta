local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/jensonhirst/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "StarHub : Versão : BETA", HidePremium = false, SaveConfig = true, ConfigFolder = "StaRHub"})

local Tab = Window:MakeTab({
	Name = "StarHub V1",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
local Section = Tab:AddSection({
	Name = "Brookhaven"
})
Tab:AddButton({
	Name = "ChaosHub",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/Luscaa22/Calabocaa/refs/heads/main/ChaosHub"))()
  	end    
})


ColorPicker:Set(Color3.fromRGB(255,255,255))
