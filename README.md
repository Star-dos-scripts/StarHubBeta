local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/jensonhirst/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "StarHub : Versão : BETA", HidePremium = false, SaveConfig = true, ConfigFolder = "StaRHub"})

local Tab = Window:MakeTab({
	Name = "BETA",
	Icon = "rbxassetid://95002016991260",
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
Tab:AddButton({
	Name = "Rael Hub",
	Callback = function()
      		loadstring(game:HttpGet("https://rawscripts.net/raw/Brookhaven-RP-Updated-Rael-Hub-31509"))()
  	end    
})
Tab:AddButton({
	Name = "Jãozin HubBR",
	Callback = function()
      		OrionLib:MakeNotification({
	Name = "AVISO DO JOÃO!",
	Content = "Nosso script esta desativado temporariamente pois estamos trabalhando na versão V2 do jãozin hub",
	Image = "rbxassetid://4483345998",
	Time = 5
})

  	end    
})


local Section = Tab:AddSection({
	Name = "MM2"
})
Tab:AddButton({
	Name = "Yarhm!",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/Joystickplays/psychic-octo-invention/main/yarhm.lua", false))()
  	end    
})
local Section = Tab:AddSection({
	Name = "Avisos!"
})


Tab:AddParagraph("Aviso","SIM! o script esta beta! pois os mods estão sem ideias! mande ideias no discord!")



local Tab = Window:MakeTab({
	Name = "Discord!",
	Icon = "rbxassetid://78634733259759",
	PremiumOnly = false
})
Tab:AddButton({
    Name = "StarHub",
    Callback = function()
        setclipboard("https://discord.gg/kBDk5YMR2R")
    end
})

Tab:AddButton({
    Name = "RaelHub",
    Callback = function()
        setclipboard("https://discord.gg/xxWejWkPBg")
    end
})

Tab:AddButton({
    Name = "Chaos Hub",
    Callback = function()
        setclipboard("https://discord.gg/GDzauHRPzp")
    end
})
