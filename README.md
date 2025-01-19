--carregar biblioteca 
local Fluent = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()
local Window = Fluent:CreateWindow({
    Title = "KING HUB" .. Fluent.Version,
    TabWidth = 160, Size = UDim2.fromOffset(580, 460), Theme = "Dark"
})
local Tabs = {
    Main = Window:AddTab({ Title = "Main" }),
    Settings = Window:AddTab({ Title = "Settings", Icon = "settings" })
}
local Tabs = {
    Main = Window:AddTab({ Title = "Main" }),
    Settings = Window:AddTab({ Title = "Settings", Icon = "settings" })
}
--paragrafo

Tabs.Main:AddParagraph({ Title = "KIING", Content = "SCRIPTS!" })
--botôes
Tabs.Main:AddButton({ Title = "FNT 1", Callback = function() loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-YARHM-12403"))() end })

