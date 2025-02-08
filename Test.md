

# Simple Ui

```
local gui = Instance.new("ScreenGui")
gui.Parent = game.CoreGui





local button = Instance.new("TextButton")
button.Size = UDim2.new(0, 120, 0, 50)
button.Position = UDim2.new(0, 50, 0, 80)
button.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
button.BorderColor3 = Color3.fromRGB(0, 0, 0)
button.BorderSizePixel = 0
button.Text = "Lock: Off" -- Change the Text
button.TextSize = 20
button.BackgroundTransparency = 0 
button.TextColor3 = Color3.fromRGB(255, 255, 255)
button.Font = Enum.Font.Arcade
button.Draggable = true
button.Parent = gui


local UICorner = Instance.new("UICorner")
UICorner.CornerRadius = UDim.new(0, 5)
UICorner.Parent = button

local UIStroke = Instance.new("UIStroke")
UIStroke.Color = Color3.fromRGB(80, 80, 80)
UIStroke.Thickness = 1
UIStroke.Parent = button
```

