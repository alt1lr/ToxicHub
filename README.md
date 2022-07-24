local notifications = loadstring(game:HttpGet(("https://raw.githubusercontent.com/AbstractPoo/Main/main/Notifications.lua"),true))()
notifications:notify{
    Title = "Welcome",
    Description = "Toxic Hub!",
    Accept = {
        Text = "Ok !"
    },
    Length = 10
}
wait(2)
local Library = loadstring(game:HttpGet("https://pastebin.com/raw/vff1bQ9F"))()
local Window = Library.CreateLib("Fire Break", "BloodTheme")

local Tab1 = Window:NewTab("Credits")
local Tab1Section = Tab1:NewSection("Thank For Using Fire Break")

Tab1Section:NewButton("alt1lr#9459", "No Description", function()
setclipboard('alt1lr#945')
end)

Tab1Section:NewButton("Discord", "No Description", function()
setclipboard('https://discord.gg/zs4FP4VYYx')
end)

Tab1Section:NewButton("Youtube", "No Description", function()
setclipboard('https://m.youtube.com/channel/UCxfiH1VLU1H6td_ny_Bt0oQ')
end)

local Tab1Section = Tab1:NewSection("Roblox Function")

Tab1Section:NewButton("Rejoin (Lobby)", "ButtonInfo", function()
game:GetService'TeleportService':TeleportToPlaceInstance(game.PlaceId,game.JobId,game:GetService'Players'.LocalPlayer)
end)

Tab1Section:NewButton("Kill Your Self", "ButtonInfo", function()
game.Players.LocalPlayer.Character.Humanoid.Health = 0
end)

local Tab2 = Window:NewTab("Role")
local Tab2Section = Tab2:NewSection("This Wont Work In The Main Game")

Tab2Section:NewButton("Swat", "No Description", function()
local A_1 = "SwatGun"
local A_2 = true
local Event = game:GetService("ReplicatedStorage").RemoteEvents.OutsideRole
Event:FireServer(A_1, A_2)
end)

Tab2Section:NewButton("Police", "No Description", function()
local A_1 = "Gun"
local A_2 = true
local Event = game:GetService("ReplicatedStorage").RemoteEvents.OutsideRole
Event:FireServer(A_1, A_2)
end)

Tab2Section:NewButton("Protector", "No Description", function()
local A_1 = "Bat"
local A_2 = true
local Event = game:GetService("ReplicatedStorage").RemoteEvents.OutsideRole
Event:FireServer(A_1, A_2)
end)

Tab2Section:NewButton("Medic", "No Description", function()
local A_1 = "MedKit"
local A_2 = true
local Event = game:GetService("ReplicatedStorage").RemoteEvents.OutsideRole
Event:FireServer(A_1, A_2)
end)

Tab2Section:NewButton("Fighter", "No Description", function()
local A_1 = "Sword"
local A_2 = true
local Event = game:GetService("ReplicatedStorage").RemoteEvents.OutsideRole
Event:FireServer(A_1, A_2)
end)

Tab2Section:NewButton("Hungry", "No Description", function()
local A_1 = "Chips"
local A_2 = true
local Event = game:GetService("ReplicatedStorage").RemoteEvents.OutsideRole
Event:FireServer(A_1, A_2)
end)

Tab2Section:NewButton("Steathy", "No Description", function()
local A_1 = "TeddyBloxin"
local A_2 = true
local Event = game:GetService("ReplicatedStorage").RemoteEvents.OutsideRole
Event:FireServer(A_1, A_2)
end)

local Tab3 = Window:NewTab("Tool")
local Tab3Section = Tab3:NewSection("Food")

Tab3Section:NewButton("Bloxy Cola", "No Description", function()
game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("BloxyCola")
end)

Tab3Section:NewButton("Bag Of Chips", "No Description", function()
game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("Chips")
end)

Tab3Section:NewButton("Cookie", "No Description", function()
game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("Cookie")
end)

Tab3Section:NewButton("Pizza", "No Description", function()
game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("Pizza2")
end)

Tab3Section:NewButton("Apple", "No Description", function()
game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("Apple")
end)

Tab3Section:NewButton("Lollipop", "No Description", function()
game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("Lollipop")
end)

Tab3Section:NewButton("Poisonous Pizza", "No Description", function()
game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("EpicPizza")
end)

local Tab3Section = Tab3:NewSection("Healing")

Tab3Section:NewButton("Medkit", "No Description", function()
game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("MedKit")
end)

Tab3Section:NewButton("Cure", "No Description", function()
game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("Cure")
end)

local Tab3Section = Tab3:NewSection("Weapon")

Tab3Section:NewButton("Toy Sword", "No Description", function()
game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("Sword")
end)

Tab3Section:NewButton("Bat", "No Description", function()
game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("Bat")
end)

Tab3Section:NewButton("Hammer", "No Description", function()
local A_1 = true
local A_2 = "Hammer"
local Event = game:GetService("ReplicatedStorage").RemoteEvents.BasementWeapon
Event:FireServer(A_1, A_2)
end)

Tab3Section:NewButton("Sword", "No Description", function()
game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("LinkedSword")
end)

local Tab3Section = Tab3:NewSection("Other Tool")

Tab3Section:NewButton("Plank", "No Description", function()
game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("Plank")
end)

Tab3Section:NewButton("TeddyBear", "No Description", function()
game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("BloxpinTeddy")
end)

local Tab4 = Window:NewTab("Teleport")
local Tab4Section = Tab4:NewSection("Teleport")

Tab4Section:NewButton("Attic", "No Description", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-16, 35, -220)
end)

Tab4Section:NewButton("Basement", "No Description", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(71, -15, -163)
end)

Tab4Section:NewButton("Sewer", "No Description", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(129, 3, -125)
end)

Tab4Section:NewButton("Store", "No Description", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-422, 3, -121)
end)

Tab4Section:NewButton("Boss Room", "No Description", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-39, -287, -1480)
end)

Tab4Section:NewButton("House", "No Description", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-36, 3, -200)
end)

local Tab5 = Window:NewTab("Extra")
local Tab5Section = Tab5:NewSection("Extra")

Tab5Section:NewButton("Kill Enemy", "No Description", function()
    for i,v in pairs(game.Workspace.BadGuys:GetChildren()) do
        for i = 1, 50 do
            game:GetService("ReplicatedStorage").RemoteEvents.HitBadguy:FireServer(v,10)
            game:GetService("ReplicatedStorage").RemoteEvents.HitBadguy:FireServer(v,996)
            game:GetService("ReplicatedStorage").RemoteEvents.HitBadguy:FireServer(v,9)
            game:GetService("ReplicatedStorage").RemoteEvents.HitBadguy:FireServer(v,8)
            game:GetService("ReplicatedStorage").RemoteEvents.HitBadguy:FireServer(v,996)
        end
    end
end)

Tab5Section:NewButton("Freind With Cat", "No Description", function()
    local Target = game:GetService("ReplicatedStorage").RemoteEvents.Cattery;
    Target:FireServer();
end)

Tab5Section:NewButton("Heal [Press Freimd With Cat First] ", "No Description", function()
for i = 1, 200 do
        wait(0.0001)
        local A_1 = "Cat"
        local Event = game:GetService("ReplicatedStorage").RemoteEvents.Energy
        Event:FireServer(A_1)
    end
end)

Tab5Section:NewButton("Destroy Tool", "No Description", function()
for i,v in pairs(game:GetService("Players").LocalPlayer.Backpack:GetChildren()) do
        if v:IsA("Tool") then
            v:Destroy()
        end
    end
end)

Tab5Section:NewButton("Drop Tools", "No Description", function()
while wait(1) do
        for i,v in pairs(game:GetService("Players").LocalPlayer.Backpack:GetChildren()) do
            if v:IsA("Tool") then
                v.CanBeDropped = true
            end
        end
    end
end)

local Tab6 = Window:NewTab("Keybind")
local Tab6Section = Tab6:NewSection("Keybind")

Tab6Section:NewKeybind("Close/Open", "Close Or Open This Gui", Enum.KeyCode.E, function()
	Library:ToggleUI()
end)
