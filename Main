local screenGui = Instance.new("ScreenGui")
screenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
 
local frame = Instance.new("Frame")
frame.Size = UDim2.new(0, 200, 0, 100)
frame.Position = UDim2.new(0.5, -100, 0.5, -50)
frame.BackgroundColor3 = Color3.new(1, 1, 1)
frame.Parent = screenGui
 
local title = Instance.new("TextLabel")
title.Size = UDim2.new(1, 0, 0, 20)
title.Position = UDim2.new(0, 0, 0, -20)
title.Text = "Infinity Hack STB"
title.TextColor3 = Color3.new(1, 1, 1)
title.BackgroundColor3 = Color3.new(0, 0, 0)
title.Parent = frame
 
local dragging
local dragInput
local dragStart
local startPos
 
local function update(input)
    local delta = input.Position - dragStart
    frame.Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X, startPos.Y.Scale, startPos.Y.Offset + delta.Y)
end
 
title.InputBegan:Connect(function(input)
    if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
        dragging = true
        dragStart = input.Position
        startPos = frame.Position
 
        input.Changed:Connect(function()
            if input.UserInputState == Enum.UserInputState.End then
                dragging = false
            end
        end)
    end
end)
 
title.InputChanged:Connect(function(input)
    if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
        dragInput = input
    end
end)
 
title.InputEnded:Connect(function(input)
    if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
        dragging = false
        dragInput = nil
    end
end)
 
game:GetService("UserInputService").InputChanged:Connect(function(input)
    if input == dragInput and dragging then
        update(input)
    end
end)
 
local KeySystem = Instance.new("TextBox")
KeySystem.Size = UDim2.new(1, 0, 0.5, 0)
KeySystem.Position = UDim2.new(0, 0, 0, 0)
KeySystem.Text = "Enter the Key"
KeySystem.TextColor3 = Color3.new(0, 0, 0)
KeySystem.BackgroundTransparency = 0.5
KeySystem.BackgroundColor3 = Color3.new(1, 1, 1)
KeySystem.TextWrapped = true
KeySystem.Parent = frame
 
local SubmitButton = Instance.new("TextButton")
SubmitButton.Size = UDim2.new(0.5, 0, 0.5, 0)
SubmitButton.Position = UDim2.new(0, 0, 0.5, 0)
SubmitButton.Text = "Submit"
SubmitButton.Parent = frame
 
local CloseButton = Instance.new("TextButton")
CloseButton.Size = UDim2.new(0, 20, 0, 20)
CloseButton.Position = UDim2.new(1, -20, 0, 0)
CloseButton.Text = "X"
CloseButton.TextColor3 = Color3.new(1, 1, 1)
CloseButton.BackgroundColor3 = Color3.new(1, 0, 0)
CloseButton.Parent = frame
 
CloseButton.MouseButton1Click:Connect(function()
    screenGui:Destroy()
end)
 
local GetKeyButton = Instance.new("TextButton")
GetKeyButton.Size = UDim2.new(0.5, 0, 0.5, 0)
GetKeyButton.Position = UDim2.new(0.5, 0, 0.5, 0)
GetKeyButton.Text = "Get Key"
GetKeyButton.Parent = frame
--------------------------------------------------------------------------
SubmitButton.MouseButton1Click:Connect(function()
    local KeySystem = KeySystem.Text
    if KeySystem == "JHMy7Kut-oms0Y1m5-449e1AXD" then   
screenGui:Destroy()
 
--Your Script
  local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/Robojini/Tuturial_UI_Library/main/UI_Template_1"))()
local Window = Library.CreateLib("Super Toilet Brawl [Infinity Hack Beta]", "RJTheme7")
local Tab = Window:NewTab("RageFN")
local Section = Tab:NewSection("You can catch reports from this feature. Be careful :)")


Section:NewButton("Fast Regeniration (SPAM THIS)", "IMPORTANT: Before using function, accumulate rage.", function()
local args = {
    [1] = game:GetService("Players").LocalPlayer
}

game:GetService("ReplicatedStorage").Events.RemoteEvents.RageMode:FireServer(unpack(args))
end)

local Tab = Window:NewTab("TpFN")
local Section = Tab:NewSection("Teleport")

Section:NewButton("Lobby", "AHHHHHH, SKEBEDE... SKEBEDEEEEE!!!!", function()
local Character = game.Players.LocalPlayer.Character or game.Players.LocalPlayer.CharacterAdded:Wait()
if Character then
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(143.433319, 59507.9883, -21.9929199, 0.999949455, 0.000105231513, 0.0100510614, 8.45401527e-09, 0.999945164, -0.0104699582, -0.0100516127, 0.0104694301, 0.999894679)
end
end)

Section:NewButton("Game", "CFrame Teleport", function()
local Character = game.Players.LocalPlayer.Character or game.Players.LocalPlayer.CharacterAdded:Wait()
if Character then
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-933.63855, 1065.05676, -17.5409851, 1, 0, 0, 0, 1, 0, 0, 0, 1)
end
end)

Section:NewButton("The Forge", "CFrame Teleport", function()
local Character = game.Players.LocalPlayer.Character or game.Players.LocalPlayer.CharacterAdded:Wait()
if Character then
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-473.15387, 49392.1641, -324.983795, 0.922187269, 0.0210435446, 0.386170745, 7.62102026e-09, 0.998518586, -0.0544121414, -0.386743665, 0.0501781888, 0.920821071)
end
end)

local Tab = Window:NewTab("HumanoidFN")
local Section = Tab:NewSection("Universal")

Section:NewButton("Permanent Noclip", "Turn off - Re-enter the game", function()
local Noclip = nil
local Clip = nil

function noclip()
	Clip = false
	local function Nocl()
		if Clip == false and game.Players.LocalPlayer.Character ~= nil then
			for _,v in pairs(game.Players.LocalPlayer.Character:GetDescendants()) do
				if v:IsA('BasePart') and v.CanCollide and v.Name ~= floatName then
					v.CanCollide = false
				end
			end
		end
		wait(0.21) -- basic optimization
	end
	Noclip = game:GetService('RunService').Stepped:Connect(Nocl)
end

function clip()
	if Noclip then Noclip:Disconnect() end
	Clip = true
end

noclip() -- to toggle noclip() and clip()
end)

Section:NewButton("Speed Boost", "Fuck HC Mode", function()
game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 150
end)

Section:NewButton("Idk.. Press E", "..?", function()
-- Create a function to enable flying
local function enableFly(player)
    local humanoid = player.Character and player.Character:FindFirstChild("Humanoid")
    
    if humanoid then
        humanoid.PlatformStand = true
        humanoid.Sit = true
        humanoid.Swim = true
        humanoid.Jump = true
        humanoid.WalkSpeed = 0
        humanoid.Name = "Humanoid_Flying"
    end
end

-- Create a function to disable flying
local function disableFly(player)
    local humanoidFlying = player.Character and player.Character:FindFirstChild("Humanoid_Flying")
    
    if humanoidFlying then
        humanoidFlying.PlatformStand = false
        humanoidFlying.Sit = false
        humanoidFlying.Swim = false
        humanoidFlying.Jump = false
        humanoidFlying.WalkSpeed = 16
        humanoidFlying.Name = "Humanoid"
    end
end

-- Enable flying when 'e' key is pressed
game:GetService("UserInputService").InputBegan:Connect(function(input)
    if input.KeyCode == Enum.KeyCode.E then
        enableFly(game.Players.LocalPlayer)
    end
end)

-- Disable flying when 'f' key is pressed
game:GetService("UserInputService").InputBegan:Connect(function(input)
    if input.KeyCode == Enum.KeyCode.F then
        disableFly(game.Players.LocalPlayer)
    end
end)

end)
  end
end)
 
GetKeyButton.MouseButton1Click:Connect(function()
 setclipboard("Paste here your link to get the key") 
end) 
