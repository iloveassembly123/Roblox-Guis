--This was a gui for a game named thunder scientific
local TSGui = Instance.new("ScreenGui")
local Main = Instance.new("Frame")
local RemoveTab = Instance.new("TextButton")
local UICorner = Instance.new("UICorner")
local UICorner_2 = Instance.new("UICorner")
local TPGui = Instance.new("Frame")
local UICorner_3 = Instance.new("UICorner")
local TSCTP = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local CellTPL = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local CellTPR = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local Unused = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local TSLogo = Instance.new("ImageLabel")
local InfectionPanelButton = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local InfectionPanel = Instance.new("Frame")
local UICorner_9 = Instance.new("UICorner")
local Unused_2 = Instance.new("TextButton")
local UICorner_10 = Instance.new("UICorner")
local TPGuiButton = Instance.new("TextButton")
local UICorner_11 = Instance.new("UICorner")
local Destroy = Instance.new("ImageButton")
local AutoBuy = Instance.new("Frame")
local UICorner_12 = Instance.new("UICorner")
local Input = Instance.new("TextBox")
local UICorner_13 = Instance.new("UICorner")
local Logs = Instance.new("TextLabel")
local UICorner_14 = Instance.new("UICorner")
local AutoBuyBuy = Instance.new("TextButton")
local UICorner_15 = Instance.new("UICorner")
local Autobuybutton = Instance.new("TextButton")
local UICorner_16 = Instance.new("UICorner")
local Drag = Instance.new("Frame")
local UICorner_17 = Instance.new("UICorner")
local Open = Instance.new("TextButton")
local UICorner_18 = Instance.new("UICorner")

--Properties:

TSGui.Name = "TSGui"
TSGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

Main.Name = "Main"
Main.Parent = TSGui
Main.BackgroundColor3 = Color3.fromRGB(50, 50, 50)
Main.BorderColor3 = Color3.fromRGB(27, 42, 53)
Main.Position = UDim2.new(0.387298614, 0, 0.243602365, 0)
Main.Size = UDim2.new(0, 272, 0, 345)

RemoveTab.Name = "RemoveTab"
RemoveTab.Parent = Main
RemoveTab.BackgroundColor3 = Color3.fromRGB(39, 39, 39)
RemoveTab.Position = UDim2.new(0.272058815, 0, 0.0318840146, 0)
RemoveTab.Size = UDim2.new(0, 123, 0, 43)
RemoveTab.Font = Enum.Font.Michroma
RemoveTab.Text = "Remove Tabs"
RemoveTab.TextColor3 = Color3.fromRGB(0, 170, 255)
RemoveTab.TextSize = 14.000

UICorner.CornerRadius = UDim.new(0, 10)
UICorner.Parent = RemoveTab

UICorner_2.CornerRadius = UDim.new(0, 10)
UICorner_2.Parent = Main

TPGui.Name = "TPGui"
TPGui.Parent = Main
TPGui.BackgroundColor3 = Color3.fromRGB(50, 50, 50)
TPGui.BorderColor3 = Color3.fromRGB(27, 42, 53)
TPGui.Position = UDim2.new(0.99857688, 0, -0.00129801431, 0)
TPGui.Size = UDim2.new(0, 186, 0, 345)
TPGui.Visible = false

UICorner_3.CornerRadius = UDim.new(0, 10)
UICorner_3.Parent = TPGui

TSCTP.Name = "TSCTP"
TSCTP.Parent = TPGui
TSCTP.BackgroundColor3 = Color3.fromRGB(39, 39, 39)
TSCTP.Position = UDim2.new(0.164531931, 0, 0.159420252, 0)
TSCTP.Size = UDim2.new(0, 123, 0, 43)
TSCTP.Font = Enum.Font.Michroma
TSCTP.Text = "TSC"
TSCTP.TextColor3 = Color3.fromRGB(0, 170, 255)
TSCTP.TextSize = 14.000

UICorner_4.CornerRadius = UDim.new(0, 10)
UICorner_4.Parent = TSCTP

CellTPL.Name = "CellTPL"
CellTPL.Parent = TPGui
CellTPL.BackgroundColor3 = Color3.fromRGB(39, 39, 39)
CellTPL.Position = UDim2.new(0.164531946, 0, 0.284057975, 0)
CellTPL.Size = UDim2.new(0, 123, 0, 43)
CellTPL.Font = Enum.Font.Michroma
CellTPL.Text = "Cell Left Wing"
CellTPL.TextColor3 = Color3.fromRGB(0, 170, 255)
CellTPL.TextSize = 14.000

UICorner_5.CornerRadius = UDim.new(0, 10)
UICorner_5.Parent = CellTPL

CellTPR.Name = "CellTPR"
CellTPR.Parent = TPGui
CellTPR.BackgroundColor3 = Color3.fromRGB(39, 39, 39)
CellTPR.Position = UDim2.new(0.164531931, 0, 0.408695638, 0)
CellTPR.Size = UDim2.new(0, 123, 0, 43)
CellTPR.Font = Enum.Font.Michroma
CellTPR.Text = "Cell Right Wing"
CellTPR.TextColor3 = Color3.fromRGB(0, 170, 255)
CellTPR.TextSize = 14.000

UICorner_6.CornerRadius = UDim.new(0, 10)
UICorner_6.Parent = CellTPR

Unused.Name = "Unused"
Unused.Parent = TPGui
Unused.BackgroundColor3 = Color3.fromRGB(39, 39, 39)
Unused.Position = UDim2.new(0.164531931, 0, 0.0347826183, 0)
Unused.Size = UDim2.new(0, 123, 0, 43)
Unused.Font = Enum.Font.Michroma
Unused.Text = "Previous Location TP"
Unused.TextColor3 = Color3.fromRGB(255, 0, 0)
Unused.TextScaled = true
Unused.TextSize = 14.000
Unused.TextWrapped = true

UICorner_7.CornerRadius = UDim.new(0, 10)
UICorner_7.Parent = Unused

TSLogo.Name = "TSLogo"
TSLogo.Parent = Main
TSLogo.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TSLogo.BackgroundTransparency = 1.000
TSLogo.Size = UDim2.new(0, 58, 0, 55)
TSLogo.Image = "http://www.roblox.com/asset/?id=13129251325"

InfectionPanelButton.Name = "InfectionPanelButton"
InfectionPanelButton.Parent = Main
InfectionPanelButton.BackgroundColor3 = Color3.fromRGB(39, 39, 39)
InfectionPanelButton.Position = UDim2.new(0.272058815, 0, 0.156521693, 0)
InfectionPanelButton.Size = UDim2.new(0, 123, 0, 43)
InfectionPanelButton.Font = Enum.Font.Michroma
InfectionPanelButton.Text = "Infection Panel"
InfectionPanelButton.TextColor3 = Color3.fromRGB(0, 170, 255)
InfectionPanelButton.TextSize = 14.000

UICorner_8.CornerRadius = UDim.new(0, 10)
UICorner_8.Parent = InfectionPanelButton

InfectionPanel.Name = "InfectionPanel"
InfectionPanel.Parent = Main
InfectionPanel.BackgroundColor3 = Color3.fromRGB(50, 50, 50)
InfectionPanel.BorderColor3 = Color3.fromRGB(27, 42, 53)
InfectionPanel.Position = UDim2.new(0.998576939, 0, -0.00129801431, 0)
InfectionPanel.Size = UDim2.new(0, 303, 0, 345)
InfectionPanel.Visible = false

UICorner_9.CornerRadius = UDim.new(0, 10)
UICorner_9.Parent = InfectionPanel

Unused_2.Name = "Unused"
Unused_2.Parent = InfectionPanel
Unused_2.BackgroundColor3 = Color3.fromRGB(39, 39, 39)
Unused_2.Position = UDim2.new(0.296545148, 0, 0.872463763, 0)
Unused_2.Size = UDim2.new(0, 123, 0, 43)
Unused_2.Font = Enum.Font.Michroma
Unused_2.Text = "Get Infected"
Unused_2.TextColor3 = Color3.fromRGB(0, 170, 255)
Unused_2.TextSize = 14.000
Unused_2.TextWrapped = true

UICorner_10.CornerRadius = UDim.new(0, 10)
UICorner_10.Parent = Unused_2

TPGuiButton.Name = "TPGuiButton"
TPGuiButton.Parent = Main
TPGuiButton.BackgroundColor3 = Color3.fromRGB(39, 39, 39)
TPGuiButton.Position = UDim2.new(0.272058815, 0, 0.281159371, 0)
TPGuiButton.Size = UDim2.new(0, 123, 0, 43)
TPGuiButton.Font = Enum.Font.Michroma
TPGuiButton.Text = "Teleports"
TPGuiButton.TextColor3 = Color3.fromRGB(0, 170, 255)
TPGuiButton.TextSize = 14.000

UICorner_11.CornerRadius = UDim.new(0, 10)
UICorner_11.Parent = TPGuiButton

Destroy.Name = "Destroy"
Destroy.Parent = Main
Destroy.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Destroy.BackgroundTransparency = 1.000
Destroy.Position = UDim2.new(0.897630095, 0, -0.00129806995, 0)
Destroy.Size = UDim2.new(0, 27, 0, 32)
Destroy.Image = "http://www.roblox.com/asset/?id=5279719038"
Destroy.ImageColor3 = Color3.fromRGB(255, 0, 0)

AutoBuy.Name = "AutoBuy"
AutoBuy.Parent = Main
AutoBuy.BackgroundColor3 = Color3.fromRGB(50, 50, 50)
AutoBuy.BorderColor3 = Color3.fromRGB(27, 42, 53)
AutoBuy.Position = UDim2.new(0.99857682, 0, -0.00129801431, 0)
AutoBuy.Size = UDim2.new(0, 186, 0, 345)
AutoBuy.Visible = false

UICorner_12.CornerRadius = UDim.new(0, 10)
UICorner_12.Parent = AutoBuy

Input.Name = "Input"
Input.Parent = AutoBuy
Input.BackgroundColor3 = Color3.fromRGB(39, 39, 39)
Input.Position = UDim2.new(0.182795703, 0, 0.0898550749, 0)
Input.Size = UDim2.new(0, 118, 0, 50)
Input.Font = Enum.Font.SourceSans
Input.PlaceholderColor3 = Color3.fromRGB(0, 170, 255)
Input.PlaceholderText = "Put any item to buy, EG Knife"
Input.Text = ""
Input.TextColor3 = Color3.fromRGB(0, 170, 255)
Input.TextScaled = true
Input.TextSize = 14.000
Input.TextWrapped = true

UICorner_13.CornerRadius = UDim.new(0, 10)
UICorner_13.Parent = Input

Logs.Name = "Logs"
Logs.Parent = AutoBuy
Logs.BackgroundColor3 = Color3.fromRGB(39, 39, 39)
Logs.Position = UDim2.new(0.17741935, 0, 0.8057971, 0)
Logs.Size = UDim2.new(0, 120, 0, 50)
Logs.Font = Enum.Font.Michroma
Logs.Text = "Logs (This will change if you buy)"
Logs.TextColor3 = Color3.fromRGB(0, 170, 255)
Logs.TextScaled = true
Logs.TextSize = 14.000
Logs.TextWrapped = true

UICorner_14.CornerRadius = UDim.new(0, 10)
UICorner_14.Parent = Logs

AutoBuyBuy.Name = "AutoBuyBuy"
AutoBuyBuy.Parent = AutoBuy
AutoBuyBuy.BackgroundColor3 = Color3.fromRGB(39, 39, 39)
AutoBuyBuy.Position = UDim2.new(0.177537918, 0, 0.281159371, 0)
AutoBuyBuy.Size = UDim2.new(0, 123, 0, 43)
AutoBuyBuy.Font = Enum.Font.Michroma
AutoBuyBuy.Text = "Buy"
AutoBuyBuy.TextColor3 = Color3.fromRGB(0, 170, 255)
AutoBuyBuy.TextSize = 14.000

UICorner_15.CornerRadius = UDim.new(0, 10)
UICorner_15.Parent = AutoBuyBuy

Autobuybutton.Name = "Autobuybutton"
Autobuybutton.Parent = Main
Autobuybutton.BackgroundColor3 = Color3.fromRGB(39, 39, 39)
Autobuybutton.Position = UDim2.new(0.272058815, 0, 0.405797064, 0)
Autobuybutton.Size = UDim2.new(0, 123, 0, 43)
Autobuybutton.Font = Enum.Font.Michroma
Autobuybutton.Text = "Autobuy"
Autobuybutton.TextColor3 = Color3.fromRGB(0, 170, 255)
Autobuybutton.TextSize = 14.000

UICorner_16.CornerRadius = UDim.new(0, 10)
UICorner_16.Parent = Autobuybutton

Drag.Name = "Drag"
Drag.Parent = TSGui
Drag.BackgroundColor3 = Color3.fromRGB(0, 170, 255)
Drag.Position = UDim2.new(0.00559552386, 0, 0.431191683, 0)
Drag.Size = UDim2.new(0, 84, 0, 22)

UICorner_17.CornerRadius = UDim.new(0, 10)
UICorner_17.Parent = Drag

Open.Name = "Open"
Open.Parent = Drag
Open.BackgroundColor3 = Color3.fromRGB(50, 50, 50)
Open.BorderColor3 = Color3.fromRGB(27, 42, 53)
Open.Position = UDim2.new(0, 0, 0.373523623, 0)
Open.Size = UDim2.new(0, 84, 0, 76)
Open.Font = Enum.Font.Michroma
Open.Text = "Open/Close"
Open.TextColor3 = Color3.fromRGB(0, 170, 255)
Open.TextScaled = true
Open.TextSize = 14.000
Open.TextWrapped = true

UICorner_18.CornerRadius = UDim.new(0, 10)
UICorner_18.Parent = Open

-- Scripts:

local function NMIBD_fake_script() -- RemoveTab.LocalScript 
	local script = Instance.new('LocalScript', RemoveTab)

	
	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.TPGui.Visible = false
		script.Parent.Parent.InfectionPanel.Visible = false
		script.Parent.Parent.AutoBuy.Visible = false
		local UIBubble = Instance.new("Sound")
		UIBubble.SoundId = "rbxassetid://5852470908"
		UIBubble.Parent = game.Workspace
		UIBubble:Play()
		wait(2)UIBubble:Destroy()
	end)
	
end
coroutine.wrap(NMIBD_fake_script)()
local function NLQBJA_fake_script() -- TSCTP.LocalScript 
	local script = Instance.new('LocalScript', TSCTP)

	
	script.Parent.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1685.07958984375, 72.55555725097656, -242.147216796875)
	end)
	
	
end
coroutine.wrap(NLQBJA_fake_script)()
local function EBNECLQ_fake_script() -- CellTPL.LocalScript 
	local script = Instance.new('LocalScript', CellTPL)

	script.Parent.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1783.3564453125, 72.51802062988281, -238.14112854003906)
		end)
	
end
coroutine.wrap(EBNECLQ_fake_script)()
local function AUXJV_fake_script() -- CellTPR.LocalScript 
	local script = Instance.new('LocalScript', CellTPR)

	script.Parent.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1787.2796630859375, 72.51769256591797, -404.7115173339844)
	end)
	
	
end
coroutine.wrap(AUXJV_fake_script)()
local function RQVZ_fake_script() -- Unused.LocalScript 
	local script = Instance.new('LocalScript', Unused)

	script.Parent.MouseButton1Click:Connect(function()
	local oldpos = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = oldpos
		end)
end
coroutine.wrap(RQVZ_fake_script)()
local function WEGYO_fake_script() -- Main.DragScript 
	local script = Instance.new('LocalScript', Main)

	script.Parent.Active = true
	script.Parent.Selectable = true
	script.Parent.Draggable = true
end
coroutine.wrap(WEGYO_fake_script)()
local function SFVHZRQ_fake_script() -- InfectionPanelButton.LocalScript 
	local script = Instance.new('LocalScript', InfectionPanelButton)

	
	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.TPGui.Visible = false
		script.Parent.Parent.AutoBuy.Visible = false
		script.Parent.Parent.InfectionPanel.Visible = not script.Parent.Parent.InfectionPanel.Visible
		local UIBubble = Instance.new("Sound")
		UIBubble.SoundId = "rbxassetid://5852470908"
		UIBubble.Parent = game.Workspace
		UIBubble:Play()
		wait(2)UIBubble:Destroy()
	end)
	
	script.Parent.Parent.InfectionPanel.Visible = false
	
end
coroutine.wrap(SFVHZRQ_fake_script)()
local function TVJBZ_fake_script() -- Unused_2.LocalScript 
	local script = Instance.new('LocalScript', Unused_2)

	script.Parent.MouseButton1Click:Connect(function()
		local oldpos = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
		game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 0
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1052.911376953125, -178.88043212890625, 1994.01806640625)
		wait(10)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = oldpos
		game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 16
		local UIBubble = Instance.new("Sound")
		UIBubble.SoundId = "rbxassetid://1548304764"
		UIBubble.Parent = game.Workspace
		UIBubble:Play()
		wait(2)
		UIBubble:Destroy()
	end)
	
end
coroutine.wrap(TVJBZ_fake_script)()
local function QKGANFH_fake_script() -- TPGuiButton.LocalScript 
	local script = Instance.new('LocalScript', TPGuiButton)

	
	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.InfectionPanel.Visible = false
		script.Parent.Parent.AutoBuy.Visible = false
		script.Parent.Parent.TPGui.Visible = not script.Parent.Parent.TPGui.Visible
		local UIBubble = Instance.new("Sound")
		UIBubble.SoundId = "rbxassetid://5852470908"
		UIBubble.Parent = game.Workspace
		UIBubble:Play()
		wait(2)UIBubble:Destroy()
	end)
	
	script.Parent.Parent.TPGui.Visible = false
	
end
coroutine.wrap(QKGANFH_fake_script)()
local function MKMMINX_fake_script() -- Destroy.LocalScript 
	local script = Instance.new('LocalScript', Destroy)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent:Destroy()
	end)
	
end
coroutine.wrap(MKMMINX_fake_script)()
local function KGVONFR_fake_script() -- AutoBuyBuy.LocalScript 
	local script = Instance.new('LocalScript', AutoBuyBuy)

	local whitelist = {
		["Bat"] = true,
		["Card-L1"] = true,
		["Card-L2"] = true,
		["Card-L3"] = true,
		["AK-47"] = true,
		["Flamethrower"] = true,
		["SKS"] = true,
		["Knife"] = true,
		["Medkit"] = true,
		["PPK"] = true,
		["Silenced PPK"] = true,
		["Screwdriver"] = true,
		["Flashlight"] = true,
		["Disinfectant"] = true,
		["Decoy"] = true,
	}
	
	script.Parent.MouseButton1Click:Connect(function()
		local Input1 = script.Parent.Parent.Input.Text
		if whitelist[Input1] then
		    local oldpos = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1545.1212158203125, 61.402984619140625, -210.6099090576172)
				local args = {
					[1] = Input1,
					[2] = workspace.Markets["UN Black Market"],
				}
				
				game:GetService("ReplicatedStorage").Remotes.Shop.Purchase:InvokeServer(unpack(args))
				script.Parent.Parent.Logs.Text = "Fired remote to Purchase, depends if you have enough money."
				script.Parent.Parent.Logs.TextColor3 = Color3.new(0.333333, 0.666667, 0)
				local UIBubble = Instance.new("Sound")
				UIBubble.SoundId = "rbxassetid://2609873966"
				UIBubble.Parent = game.Workspace
				UIBubble:Play()
				wait(2)
				UIBubble:Destroy()
				wait(10)
				script.Parent.Parent.Logs.Text = "Logs (This will change if you buy)"
				script.Parent.Parent.Logs.TextColor3 = Color3.new(0, 0.666667, 1)
				wait(4)
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = oldpos
				
			else
			script.Parent.Parent.Logs.Text = "You entered something the table can't access."
			script.Parent.Parent.Logs.TextColor3 = Color3.new(1, 0, 0)
			local UIBubble = Instance.new("Sound")
			UIBubble.SoundId = "rbxassetid://184734960"
			UIBubble.Parent = game.Workspace
			UIBubble:Play()
			wait(2)
			UIBubble:Destroy()
			wait(10)
			script.Parent.Parent.Logs.Text = "Logs (This will change if you buy)"
			script.Parent.Parent.Logs.TextColor3 = Color3.new(0, 0.666667, 1)
		end
	end)
	
end
coroutine.wrap(KGVONFR_fake_script)()
local function ORDF_fake_script() -- Autobuybutton.LocalScript 
	local script = Instance.new('LocalScript', Autobuybutton)

	
	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.TPGui.Visible = false
		script.Parent.Parent.InfectionPanel.Visible = false
		script.Parent.Parent.AutoBuy.Visible = not script.Parent.Parent.AutoBuy.Visible
		local UIBubble = Instance.new("Sound")
		UIBubble.SoundId = "rbxassetid://5852470908"
		UIBubble.Parent = game.Workspace
		UIBubble:Play()
		wait(2)UIBubble:Destroy()
	end)
	
	script.Parent.Parent.AutoBuy.Visible = false
	
end
coroutine.wrap(ORDF_fake_script)()
local function TWIV_fake_script() -- Drag.DragScript 
	local script = Instance.new('LocalScript', Drag)

	script.Parent.Active = true
	script.Parent.Selectable = true
	script.Parent.Draggable = true
end
coroutine.wrap(TWIV_fake_script)()
local function HZLM_fake_script() -- Open.LocalScript 
	local script = Instance.new('LocalScript', Open)

	
	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent.Main.Visible = not script.Parent.Parent.Parent.Main.Visible
		local UIBubble = Instance.new("Sound")
		UIBubble.SoundId = "rbxassetid://5852470908"
		UIBubble.Parent = game.Workspace
		UIBubble:Play()
		wait(2)UIBubble:Destroy()
	end)
	
	script.Parent.Parent.Main.Visible = false
	
end
coroutine.wrap(HZLM_fake_script)()
