-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local ImageLabel = Instance.new("ImageLabel")
local text = Instance.new("TextLabel")
game:GetService("StarterGui"):SetCore("SendNotification", {Title = "Hyperon", Text = "Hyperon has ben injected (Made By Shadow & Gab)"})

--Properties:

ScreenGui.Parent = game.CoreGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

ImageLabel.Parent = ScreenGui
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.BackgroundTransparency = 2.000
ImageLabel.Position = UDim2.new(0.0547096208, 5, 0.939506173, 0)
ImageLabel.Size = UDim2.new(0, 64, 0, 49)
ImageLabel.Image = "rbxassetid://14107424082"

text.Name = "text"
text.Parent = ScreenGui
text.BackgroundColor3 = Color3.fromRGB(39, 27, 55)
text.BackgroundTransparency = 1.000
text.BorderColor3 = Color3.fromRGB(28, 20, 40)
text.Position = UDim2.new(-0.000269439712, 0, 0.954746008, 0)
text.Size = UDim2.new(0.0672909617, 0, 0.0292367432, 0)
text.Font = Enum.Font.Arial
text.Text = "Hyperion"
text.TextColor3 = Color3.fromRGB(26, 171, 288)
text.TextScaled = true
text.TextSize = 18.000
text.TextWrapped = true
