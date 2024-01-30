local library = loadstring(game:HttpGet("https://githubusertent.com/nongduy/W-ELKA/main/A.duysen"))()

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
    Player = Window:AddTab({ Title = "Player",Icon = "baby"}),
    Raid = Window:AddTab({ Title = "Dungeon",Icon = "swords"}),
    Esp-Fruit = Window:AddTab({ Title = "Devil Fruit",Icon ="chery"}),
    Shop = Window:AddTab({ Title = "Shop",Icon ="shopping-cart"}),
    Race = Window:AddTab({ Title = "Race v4",Icon ="chevrons-right}),
        Music = Window:AddTab({ Title = "Music",Icon = "list-plus"}),
}
local Options = Fluent.Options
do

    repeat wait() until game.players
    repeat wait() until game.players.localplayer
    repeat wait() until game.replicatedstorage
    repeat wait() until game.replicatedstorage:FindFirstchild("remotes");

