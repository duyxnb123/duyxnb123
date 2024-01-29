local library = loadstring(game:HttpGet("https://github.com/W-ELKA/nongduy/main/dark))()
----------------------------------------------------------------------------------------
local Window = library:Createwindow({
Title = "W-ELKA",
Sub title = " tui tự làm",
Tabwidth = 160,
Size = UDim2.fromOFFset(400, 300),
Acrylic = true, -- The blur may be detectable, setting this to false disables blur entirery
Theme = "Darker"
Minimizekey = Enum.KeyCode.End -- Used when theres no Minimizekeybind
})
local Tabs = {
Main = Window:AddTab({ Title = "Main",Icon = "home"}),
Fram = Window:AddTab({ Title = "Fram",Icon = "elite"}),
Setting = Window:AddTab({ Title = "Setting",Icon = "Setting"}),
Travel = Window:AddTab({ Title = "Travel",Icon = "palmtree"}),
Start = Window:AddTab({ Title = "Start",Icon = "plus-circre"}),
Player = Window:AddTab({ Title = "Player",Icon = "baby"})
Raid = Window:AddTab({ Title = "Dungeon",Icon = "swords"})
