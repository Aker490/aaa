local xe4a1ui = Instance.new("ScreenGui")
local Main = Instance.new("Frame")
local ServerhopButton = Instance.new("TextButton")
local TpButton = Instance.new("TextButton")
local RejoinButton = Instance.new("TextButton")
local UICorner = Instance.new("UICorner")
local CloseButton = Instance.new("TextButton")

xe4a1ui.Name = "xe4a1ui"
xe4a1ui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
xe4a1ui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Main.Name = "Main"
Main.Parent = xe4a1ui
Main.BackgroundColor3 = Color3.fromRGB(34, 34, 34)
Main.BorderColor3 = Color3.fromRGB(0, 0, 0)
Main.BorderSizePixel = 0
Main.Position = UDim2.new(0.599003434, 0, 0.487432063, 0)
Main.Size = UDim2.new(0, 364, 0, 270)

ServerhopButton.Name = "ServerhopButton"
ServerhopButton.Parent = Main
ServerhopButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ServerhopButton.BackgroundTransparency = 1.000
ServerhopButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
ServerhopButton.BorderSizePixel = 0
ServerhopButton.Size = UDim2.new(0, 128, 0, 34)
ServerhopButton.Font = Enum.Font.Cartoon
ServerhopButton.Text = "Hop Server"
ServerhopButton.TextColor3 = Color3.fromRGB(255, 255, 255)
ServerhopButton.TextSize = 14.000
ServerhopButton.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/Aker490/HopServer/main/README.md'))()
end)

TpButton.Name = "TpButton"
TpButton.Parent = Main
TpButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TpButton.BackgroundTransparency = 1.000
TpButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
TpButton.BorderSizePixel = 0
TpButton.Position = UDim2.new(0.648351669, 0, 0, 0)
TpButton.Size = UDim2.new(0, 128, 0, 34)
TpButton.Font = Enum.Font.Cartoon
TpButton.Text = "Teleport Player"
TpButton.TextColor3 = Color3.fromRGB(255, 255, 255)
TpButton.TextSize = 14.000
TpButton.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet('https://pastebin.com/raw/cLeG7Vqq'))()
end)

RejoinButton.Name = "RejoinButton"
RejoinButton.Parent = Main
RejoinButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
RejoinButton.BackgroundTransparency = 1.000
RejoinButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
RejoinButton.BorderSizePixel = 0
RejoinButton.Position = UDim2.new(0.324175835, 0, 0, 0)
RejoinButton.Size = UDim2.new(0, 128, 0, 34)
RejoinButton.Font = Enum.Font.Cartoon
RejoinButton.Text = "Rejoin"
RejoinButton.TextColor3 = Color3.fromRGB(255, 255, 255)
RejoinButton.TextSize = 14.000

UICorner.Parent = Main

CloseButton.Name = "CloseButton"
CloseButton.Parent = Main
CloseButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
CloseButton.BackgroundTransparency = 1.000
CloseButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
CloseButton.BorderSizePixel = 0
CloseButton.Position = UDim2.new(0.208791211, 0, 0.707407415, 0)
CloseButton.Size = UDim2.new(0, 200, 0, 50)
CloseButton.Font = Enum.Font.Cartoon
CloseButton.Text = "CloseButton"
CloseButton.TextColor3 = Color3.fromRGB(255, 255, 255)
CloseButton.TextSize = 14.000

local function DZQHWAB_fake_script() -- CloseButton.CloseButtonScript 
	local script = Instance.new('LocalScript', CloseButton)

	script.Parent.MouseButton1Down:Connect(function()
		script.Parent.Parent.Visible = false
	end)
end
coroutine.wrap(DZQHWAB_fake_script)()
