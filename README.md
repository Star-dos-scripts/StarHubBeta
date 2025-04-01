local OrionLib = loadstring(game:HttpGet('https://raw.githubusercontent.com/jensonhirst/Orion/main/source'))() local Window = OrionLib:MakeWindow({Name = "StarHub : Versão : BETA", HidePremium = false, SaveConfig = true, ConfigFolder = "StaRHub"})

-- Criando aba BETA local BetaTab = Window:MakeTab({ Name = "BETA", Icon = "rbxassetid://95002016991260", PremiumOnly = false })

-- Seção Brookhaven BetaTab:AddSection({ Name = "Brookhaven" }) BetaTab:AddButton({ Name = "ChaosHub", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/Luscaa22/Calabocaa/refs/heads/main/ChaosHub"))() end }) BetaTab:AddButton({ Name = "Rael Hub", Callback = function() loadstring(game:HttpGet("https://rawscripts.net/raw/Brookhaven-RP-Updated-Rael-Hub-31509"))() end }) BetaTab:AddButton({ Name = "Jãozin HubBR", Callback = function() OrionLib:MakeNotification({ Name = "AVISO DO JOÃO!", Content = "Nosso script está desativado temporariamente pois estamos trabalhando na versão V2 do Jãozin Hub", Image = "rbxassetid://4483345998", Time = 5 }) end })

-- Seção MM2 BetaTab:AddSection({ Name = "MM2" }) BetaTab:AddButton({ Name = "Yarhm!", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/Joystickplays/psychic-octo-invention/main/yarhm.lua"))() end })

-- Seção Avisos BetaTab:AddSection({ Name = "Avisos!" }) BetaTab:AddParagraph("Aviso", "SIM! O script está em beta! Pois os mods estão sem ideias! Mande ideias no Discord!")

-- Criando aba Discord local DiscordTab = Window:MakeTab({ Name = "Discord!", Icon = "rbxassetid://78634733259759", PremiumOnly = false })

DiscordTab:AddButton({ Name = "StarHub", Callback = function() setclipboard("https://discord.gg/kBDk5YMR2R") end }) DiscordTab:AddButton({ Name = "RaelHub", Callback = function() setclipboard("https://discord.gg/xxWejWkPBg") end }) DiscordTab:AddButton({ Name = "Chaos Hub", Callback = function() setclipboard("https://discord.gg/GDzauHRPzp") end })

