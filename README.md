-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local UIGradient = Instance.new("UIGradient")
local Frame_2 = Instance.new("Frame")
local TextButton = Instance.new("TextButton")
local UICorner_2 = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local TextLabel_3 = Instance.new("TextLabel")
local TextButton_2 = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local ImageLabel = Instance.new("ImageLabel")
local UICorner_4 = Instance.new("UICorner")
local TextLabel_4 = Instance.new("TextLabel")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.170933113, 0, 0.300251245, 0)
Frame.Size = UDim2.new(0, 651, 0, 305)

UICorner.Parent = Frame

UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(32, 0, 97)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 0, 0))}
UIGradient.Parent = Frame

Frame_2.Parent = Frame
Frame_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_2.BorderSizePixel = 0
Frame_2.Position = UDim2.new(0, 0, 0.222950816, 0)
Frame_2.Size = UDim2.new(0, 651, 0, -2)

TextButton.Parent = Frame
TextButton.BackgroundColor3 = Color3.fromRGB(134, 134, 134)
TextButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0.0890937001, 0, 0.3672131, 0)
TextButton.Size = UDim2.new(0, 197, 0, 50)
TextButton.Font = Enum.Font.SourceSans
TextButton.Text = "Leak avec script"
TextButton.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton.TextSize = 30.000
TextButton.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
TextButton.TextWrapped = true

UICorner_2.Parent = TextButton

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Size = UDim2.new(0, 651, 0, 68)
TextLabel.Font = Enum.Font.Gotham
TextLabel.Text = "Script Booster"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 45.000

TextLabel_2.Parent = Frame
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Position = UDim2.new(0.00921658985, 0, 0.3672131, 0)
TextLabel_2.Size = UDim2.new(0, 52, 0, 43)
TextLabel_2.Font = Enum.Font.Gotham
TextLabel_2.Text = "---"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextSize = 45.000
TextLabel_2.TextWrapped = true
TextLabel_2.TextXAlignment = Enum.TextXAlignment.Left

TextLabel_3.Parent = Frame
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.BorderSizePixel = 0
TextLabel_3.Position = UDim2.new(0.00921658985, 0, 0.600000024, 0)
TextLabel_3.Size = UDim2.new(0, 52, 0, 43)
TextLabel_3.Font = Enum.Font.Gotham
TextLabel_3.Text = "---"
TextLabel_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.TextSize = 45.000
TextLabel_3.TextWrapped = true
TextLabel_3.TextXAlignment = Enum.TextXAlignment.Left

TextButton_2.Parent = Frame
TextButton_2.BackgroundColor3 = Color3.fromRGB(134, 134, 134)
TextButton_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.BorderSizePixel = 0
TextButton_2.Position = UDim2.new(0.0890937001, 0, 0.600000024, 0)
TextButton_2.Size = UDim2.new(0, 197, 0, 50)
TextButton_2.Font = Enum.Font.SourceSans
TextButton_2.Text = "DarkDex"
TextButton_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_2.TextSize = 30.000
TextButton_2.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
TextButton_2.TextWrapped = true

UICorner_3.Parent = TextButton_2

ImageLabel.Parent = Frame
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel.BorderSizePixel = 0
ImageLabel.Position = UDim2.new(0.648233473, 0, 0.3672131, 0)
ImageLabel.Size = UDim2.new(0, 100, 0, 100)
ImageLabel.Image = "rbxasset://textures/ui/GuiImagePlaceholder.png"

UICorner_4.Parent = ImageLabel

TextLabel_4.Parent = Frame
TextLabel_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.BackgroundTransparency = 1.000
TextLabel_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_4.BorderSizePixel = 0
TextLabel_4.Position = UDim2.new(0.539170504, 0, 0.695081949, 0)
TextLabel_4.Size = UDim2.new(0, 248, 0, 43)
TextLabel_4.Font = Enum.Font.Gotham
TextLabel_4.Text = ""
TextLabel_4.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.TextSize = 23.000
TextLabel_4.TextWrapped = true
TextLabel_4.TextXAlignment = Enum.TextXAlignment.Left
