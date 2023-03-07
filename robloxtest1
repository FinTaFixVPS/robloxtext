-- Create a ScreenGui object
local ScreenGui = Instance.new("ScreenGui")
ScreenGui.Name = "TestGui"
ScreenGui.ResetOnSpawn = false
ScreenGui.DisplayOrder = 10

-- Create a Frame object to hold the button
local Frame = Instance.new("Frame")
Frame.Name = "ButtonFrame"
Frame.Position = UDim2.new(0.5, -50, 0.5, -25)
Frame.Size = UDim2.new(0, 100, 0, 50)
Frame.BackgroundTransparency = 0.5
Frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame.BorderSizePixel = 0
Frame.Parent = ScreenGui

-- Create a TextButton object for the "Test" button
local Button = Instance.new("TextButton")
Button.Name = "TestButton"
Button.Position = UDim2.new(0, 0, 0, 0)
Button.Size = UDim2.new(1, 0, 1, 0)
Button.BackgroundTransparency = 0.5
Button.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Button.BorderSizePixel = 0
Button.Text = "Test"
Button.TextColor3 = Color3.fromRGB(255, 255, 255)
Button.TextScaled = true
Button.Parent = Frame

-- Create a function to display the message
local function showMessage()
    local message = Instance.new("TextLabel")
    message.Name = "TestMessage"
    message.Position = UDim2.new(0.5, -50, 0.5, -25)
    message.Size = UDim2.new(0, 100, 0, 50)
    message.BackgroundTransparency = 0.5
    message.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
    message.BorderSizePixel = 0
    message.Text = "YES -3 YRA"
    message.TextColor3 = Color3.fromRGB(255, 0, 0)
    message.TextScaled = true
    message.Parent = ScreenGui
    wait(5)
    message:Destroy()
end

-- Connect the "Test" button to the showMessage function
Button.MouseButton1Click:Connect(showMessage)

-- Add the ScreenGui to the game
ScreenGui.Parent = game:GetService("CoreGui")
