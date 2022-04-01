
local ScreenGui = Instance.new("ScreenGui")
local main = Instance.new("Frame")
local label = Instance.new("TextLabel")
local AimLock = Instance.new("TextButton")
local Silentaim = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.CoreGui

main.Name = "main"
main.Parent = ScreenGui
main.BackgroundColor3 = Color3.fromRGB(30, 24, 50)
main.Position = UDim2.new(0.606145263, 0, 0.354651153, 0)
main.Size = UDim2.new(0, 268, 0, 315)
main.Active = true
main.Draggable = true

label.Name = "label"
label.Parent = main
label.BackgroundColor3 = Color3.fromRGB(11, 11, 18)
label.Size = UDim2.new(0, 268, 0, 50)
label.Font = Enum.Font.SourceSans
label.Text = "Galaxy AIM |made by galaxyking525"
label.TextColor3 = Color3.fromRGB(79, 7, 2)
label.TextSize = 14.000

AimLock.Name = "AimLock"
AimLock.Parent = main
AimLock.BackgroundColor3 = Color3.fromRGB(7, 2, 67)
AimLock.Position = UDim2.new(0.186567158, 0, 0.203174606, 0)
AimLock.Size = UDim2.new(0, 174, 0, 53)
AimLock.Font = Enum.Font.Oswald
AimLock.Text = "AimLock"
AimLock.TextColor3 = Color3.fromRGB(0, 0, 0)
AimLock.TextScaled = true
AimLock.TextSize = 14.000
AimLock.TextWrapped = true
AimLock.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/hackjinyt/Lock/main/README.md'),true))()
end)

Silentaim.Name = "Silent aim"
Silentaim.Parent = main
Silentaim.BackgroundColor3 = Color3.fromRGB(14, 10, 44)
Silentaim.Position = UDim2.new(0.186567158, 0, 0.746031761, 0)
Silentaim.Size = UDim2.new(0, 174, 0, 53)
Silentaim.Font = Enum.Font.SourceSans
Silentaim.Text = "SilentAim"
Silentaim.TextColor3 = Color3.fromRGB(0, 0, 0)
Silentaim.TextScaled = true
Silentaim.TextSize = 14.000
Silentaim.TextWrapped = true
Silentaim.MouseButton1Down:connect(function()
   loadstring(game:HttpGet(('https://raw.githubusercontent.com/hackjinyt/silent-aim/main/README.md'),true))()
end)
