-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame2 = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local Frame1 = Instance.new("Frame")
local UICorner_2 = Instance.new("UICorner")
local Trade = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local GodRock = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local GodArmor = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local TradeB = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local DropItem = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local dropamount = Instance.new("TextBox")
local UICorner_8 = Instance.new("UICorner")
local dropitem = Instance.new("TextBox")
local UICorner_9 = Instance.new("UICorner")
local InfJump = Instance.new("TextButton")
local UICorner_10 = Instance.new("UICorner")
local PickUp = Instance.new("TextButton")
local UICorner_11 = Instance.new("UICorner")
local Destroy = Instance.new("TextButton")
local UICorner_12 = Instance.new("UICorner")
local ImageLabel = Instance.new("ImageLabel")
local UICorner_13 = Instance.new("UICorner")
local TextLabel1 = Instance.new("TextLabel")
local UICorner_14 = Instance.new("UICorner")
local Main = Instance.new("TextButton")
local UICorner_15 = Instance.new("UICorner")
local MoreScripts = Instance.new("TextButton")
local UICorner_16 = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local UICorner_17 = Instance.new("UICorner")
local X = Instance.new("TextButton")
local UICorner_18 = Instance.new("UICorner")
local Frame = Instance.new("Frame")
local UICorner_19 = Instance.new("UICorner")
local InfiniteYield = Instance.new("TextButton")
local UICorner_20 = Instance.new("UICorner")
local ShiteGui = Instance.new("TextButton")
local UICorner_21 = Instance.new("UICorner")
local LossGui = Instance.new("TextButton")
local UICorner_22 = Instance.new("UICorner")
local EzPGui = Instance.new("TextButton")
local UICorner_23 = Instance.new("UICorner")
local Back = Instance.new("TextButton")
local UICorner_24 = Instance.new("UICorner")
local OpenGui = Instance.new("TextButton")
local UICorner_25 = Instance.new("UICorner")

--Properties:

ScreenGui.Parent = game.CoreGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame2.Name = "Frame2"
Frame2.Parent = ScreenGui
Frame2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame2.BorderSizePixel = 7
Frame2.Position = UDim2.new(0.266752094, 0, 0.0604559891, 0)
Frame2.Size = UDim2.new(0, 558, 0, 455)
Frame2.Visible = false

UICorner.Parent = Frame2

Frame1.Name = "Frame1"
Frame1.Parent = Frame2
Frame1.BackgroundColor3 = Color3.fromRGB(12, 12, 12)
Frame1.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame1.Position = UDim2.new(0.30248937, 0, 0.0161290318, 0)
Frame1.Size = UDim2.new(0, 389, 0, 426)

UICorner_2.Parent = Frame1

Trade.Name = "Trade"
Trade.Parent = Frame1
Trade.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Trade.BorderColor3 = Color3.fromRGB(74, 74, 74)
Trade.Position = UDim2.new(0.0337662324, 0, 0.0664203838, 0)
Trade.Size = UDim2.new(0, 363, 0, 27)
Trade.Font = Enum.Font.GothamMedium
Trade.Text = "Trade Gui"
Trade.TextColor3 = Color3.fromRGB(255, 255, 255)
Trade.TextSize = 14.000

UICorner_3.Parent = Trade

GodRock.Name = "GodRock"
GodRock.Parent = Frame1
GodRock.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
GodRock.BorderColor3 = Color3.fromRGB(74, 74, 74)
GodRock.Position = UDim2.new(0.0337662324, 0, 0.317594111, 0)
GodRock.Size = UDim2.new(0, 363, 0, 27)
GodRock.Font = Enum.Font.GothamMedium
GodRock.Text = " God Rock"
GodRock.TextColor3 = Color3.fromRGB(255, 255, 255)
GodRock.TextSize = 14.000

UICorner_4.Parent = GodRock

GodArmor.Name = "GodArmor"
GodArmor.Parent = Frame1
GodArmor.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
GodArmor.BorderColor3 = Color3.fromRGB(74, 74, 74)
GodArmor.Position = UDim2.new(0.0337662324, 0, 0.233087063, 0)
GodArmor.Size = UDim2.new(0, 363, 0, 27)
GodArmor.Font = Enum.Font.GothamMedium
GodArmor.Text = "God Armor"
GodArmor.TextColor3 = Color3.fromRGB(255, 255, 255)
GodArmor.TextSize = 14.000

UICorner_5.Parent = GodArmor

TradeB.Name = "TradeB"
TradeB.Parent = Frame1
TradeB.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TradeB.BorderColor3 = Color3.fromRGB(74, 74, 74)
TradeB.Position = UDim2.new(0.0337662324, 0, 0.146232605, 0)
TradeB.Size = UDim2.new(0, 363, 0, 27)
TradeB.Font = Enum.Font.GothamMedium
TradeB.Text = "Trade Button"
TradeB.TextColor3 = Color3.fromRGB(255, 255, 255)
TradeB.TextSize = 14.000

UICorner_6.Parent = TradeB

DropItem.Name = "DropItem"
DropItem.Parent = Frame1
DropItem.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
DropItem.BorderColor3 = Color3.fromRGB(74, 74, 74)
DropItem.Position = UDim2.new(0.0337662324, 0, 0.402101129, 0)
DropItem.Size = UDim2.new(0, 363, 0, 27)
DropItem.Font = Enum.Font.GothamMedium
DropItem.Text = "Drop Item"
DropItem.TextColor3 = Color3.fromRGB(255, 255, 255)
DropItem.TextSize = 14.000

UICorner_7.Parent = DropItem

dropamount.Name = "dropamount"
dropamount.Parent = DropItem
dropamount.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
dropamount.Position = UDim2.new(0.853994489, 0, 0.222222209, 0)
dropamount.Size = UDim2.new(0, 35, 0, 16)
dropamount.Font = Enum.Font.SourceSans
dropamount.Text = ""
dropamount.TextColor3 = Color3.fromRGB(0, 0, 0)
dropamount.TextSize = 14.000

UICorner_8.Parent = dropamount

dropitem.Name = "dropitem"
dropitem.Parent = DropItem
dropitem.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
dropitem.Position = UDim2.new(0.661157012, 0, 0.222222224, 0)
dropitem.Size = UDim2.new(0, 57, 0, 16)
dropitem.Font = Enum.Font.SourceSans
dropitem.Text = ""
dropitem.TextColor3 = Color3.fromRGB(255, 255, 255)
dropitem.TextSize = 14.000

UICorner_9.Parent = dropitem

InfJump.Name = "InfJump"
InfJump.Parent = Frame1
InfJump.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
InfJump.BorderColor3 = Color3.fromRGB(74, 74, 74)
InfJump.Position = UDim2.new(0.0337662324, 0, 0.484260738, 0)
InfJump.Size = UDim2.new(0, 363, 0, 27)
InfJump.Font = Enum.Font.GothamMedium
InfJump.Text = "Infinite Jump"
InfJump.TextColor3 = Color3.fromRGB(255, 255, 255)
InfJump.TextSize = 14.000

UICorner_10.Parent = InfJump

PickUp.Name = "PickUp"
PickUp.Parent = Frame1
PickUp.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
PickUp.BorderColor3 = Color3.fromRGB(74, 74, 74)
PickUp.Position = UDim2.new(0.0337662324, 0, 0.564072967, 0)
PickUp.Size = UDim2.new(0, 363, 0, 27)
PickUp.Font = Enum.Font.GothamMedium
PickUp.Text = "PickUp"
PickUp.TextColor3 = Color3.fromRGB(255, 255, 255)
PickUp.TextSize = 14.000

UICorner_11.Parent = PickUp

Destroy.Name = "Destroy"
Destroy.Parent = Frame1
Destroy.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Destroy.BorderColor3 = Color3.fromRGB(74, 74, 74)
Destroy.Position = UDim2.new(0.0311955381, 0, 0.904448509, 0)
Destroy.Size = UDim2.new(0, 363, 0, 27)
Destroy.Font = Enum.Font.GothamMedium
Destroy.Text = "Destroy Gui"
Destroy.TextColor3 = Color3.fromRGB(255, 255, 255)
Destroy.TextSize = 14.000

UICorner_12.Parent = Destroy

ImageLabel.Parent = Frame2
ImageLabel.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel.Position = UDim2.new(0.0340501815, 0, 0.0666784868, 0)
ImageLabel.Size = UDim2.new(0, 68, 0, 66)
ImageLabel.Image = "rbxasset://textures/ui/GuiImagePlaceholder.png"

UICorner_13.CornerRadius = UDim.new(0, 1000)
UICorner_13.Parent = ImageLabel

TextLabel1.Name = "TextLabel1"
TextLabel1.Parent = Frame2
TextLabel1.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextLabel1.Position = UDim2.new(0, 0, 0.23413682, 0)
TextLabel1.Size = UDim2.new(0, 168, 0, 23)
TextLabel1.Font = Enum.Font.GothamMedium
TextLabel1.TextColor3 = Color3.fromRGB(180, 180, 180)
TextLabel1.TextSize = 14.000

UICorner_14.CornerRadius = UDim.new(0, 100)
UICorner_14.Parent = TextLabel1

Main.Name = "Main"
Main.Parent = Frame2
Main.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Main.BorderColor3 = Color3.fromRGB(53, 53, 53)
Main.Position = UDim2.new(0, 0, 0.312087923, 0)
Main.Size = UDim2.new(0, 168, 0, 27)
Main.Font = Enum.Font.GothamMedium
Main.Text = "Main"
Main.TextColor3 = Color3.fromRGB(108, 108, 108)
Main.TextSize = 14.000

UICorner_15.Parent = Main

MoreScripts.Name = "MoreScripts"
MoreScripts.Parent = Frame2
MoreScripts.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
MoreScripts.BorderColor3 = Color3.fromRGB(53, 53, 53)
MoreScripts.Position = UDim2.new(0, 0, 0.371428579, 0)
MoreScripts.Size = UDim2.new(0, 167, 0, 27)
MoreScripts.Font = Enum.Font.GothamMedium
MoreScripts.Text = "More Scripts"
MoreScripts.TextColor3 = Color3.fromRGB(108, 108, 108)
MoreScripts.TextSize = 14.000

UICorner_16.Parent = MoreScripts

TextLabel.Parent = Frame2
TextLabel.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.Position = UDim2.new(-0.000272908102, 0, -0.0176608246, 0)
TextLabel.Size = UDim2.new(0, 564, 0, 27)
TextLabel.Font = Enum.Font.GothamMedium
TextLabel.Text = "By RatatuiHelp / EzP#0248"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 19.000

UICorner_17.Parent = TextLabel

X.Name = "X"
X.Parent = Frame2
X.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
X.BorderColor3 = Color3.fromRGB(53, 53, 53)
X.Position = UDim2.new(0.917740226, 0, -0.0176608246, 0)
X.Size = UDim2.new(0, 51, 0, 15)
X.Font = Enum.Font.SourceSans
X.Text = "X"
X.TextColor3 = Color3.fromRGB(255, 255, 255)
X.TextSize = 14.000

UICorner_18.Parent = X

Frame.Parent = Frame2
Frame.BackgroundColor3 = Color3.fromRGB(12, 12, 12)
Frame.Position = UDim2.new(0.299283177, 0, 0.0416798368, 0)
Frame.Size = UDim2.new(0, 390, 0, 436)
Frame.Visible = false

UICorner_19.Parent = Frame

InfiniteYield.Name = "InfiniteYield"
InfiniteYield.Parent = Frame
InfiniteYield.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
InfiniteYield.Position = UDim2.new(0.051282052, 0, 0.0686446354, 0)
InfiniteYield.Size = UDim2.new(0, 357, 0, 28)
InfiniteYield.Font = Enum.Font.GothamMedium
InfiniteYield.Text = "Infinite Yield"
InfiniteYield.TextColor3 = Color3.fromRGB(255, 255, 255)
InfiniteYield.TextSize = 14.000

UICorner_20.Parent = InfiniteYield

ShiteGui.Name = "ShiteGui"
ShiteGui.Parent = Frame
ShiteGui.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ShiteGui.Position = UDim2.new(0.051282052, 0, 0.173955053, 0)
ShiteGui.Size = UDim2.new(0, 357, 0, 28)
ShiteGui.Font = Enum.Font.GothamMedium
ShiteGui.Text = "Shite Gui"
ShiteGui.TextColor3 = Color3.fromRGB(255, 255, 255)
ShiteGui.TextSize = 14.000

UICorner_21.Parent = ShiteGui

LossGui.Name = "LossGui"
LossGui.Parent = Frame
LossGui.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
LossGui.Position = UDim2.new(0.051282052, 0, 0.279265404, 0)
LossGui.Size = UDim2.new(0, 357, 0, 28)
LossGui.Font = Enum.Font.GothamMedium
LossGui.Text = "Loss Gui"
LossGui.TextColor3 = Color3.fromRGB(255, 255, 255)
LossGui.TextSize = 14.000

UICorner_22.Parent = LossGui

EzPGui.Name = "EzPGui"
EzPGui.Parent = Frame
EzPGui.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
EzPGui.Position = UDim2.new(0.051282052, 0, 0.379999161, 0)
EzPGui.Size = UDim2.new(0, 357, 0, 28)
EzPGui.Font = Enum.Font.GothamMedium
EzPGui.Text = "EzP Gui Beta"
EzPGui.TextColor3 = Color3.fromRGB(255, 255, 255)
EzPGui.TextSize = 14.000

UICorner_23.Parent = EzPGui

Back.Name = "Back"
Back.Parent = Frame
Back.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Back.BorderColor3 = Color3.fromRGB(14, 14, 14)
Back.Position = UDim2.new(0.823076963, 0, 0.00220669317, 0)
Back.Size = UDim2.new(0, 69, 0, 22)
Back.Font = Enum.Font.GothamMedium
Back.Text = "Back"
Back.TextColor3 = Color3.fromRGB(255, 255, 255)
Back.TextSize = 12.000

UICorner_24.Parent = Back

OpenGui.Name = "OpenGui"
OpenGui.Parent = ScreenGui
OpenGui.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
OpenGui.BackgroundTransparency = 0.400
OpenGui.Position = UDim2.new(-0.00777951023, 0, 0.554672003, 0)
OpenGui.Size = UDim2.new(0, 89, 0, 50)
OpenGui.Font = Enum.Font.GothamMedium
OpenGui.Text = "Open Gui"
OpenGui.TextColor3 = Color3.fromRGB(255, 255, 255)
OpenGui.TextSize = 14.000

UICorner_25.Parent = OpenGui

-- Scripts:

local function MTYIXF_fake_script() -- ImageLabel.LocalScript 
	local script = Instance.new('LocalScript', ImageLabel)

	local Players = game:GetService("Players")
	
	local player = Players.LocalPlayer
	
	local userId = player.UserId
	local thumbType = Enum.ThumbnailType.HeadShot
	local thumbSize = Enum.ThumbnailSize.Size420x420
	local content, isReady = Players:GetUserThumbnailAsync(userId, thumbType, thumbSize)
	
	local imageLabel = script.Parent
	imageLabel.Image = content
end
coroutine.wrap(MTYIXF_fake_script)()
local function YPLPJTD_fake_script() -- TextLabel1.LocalScript 
	local script = Instance.new('LocalScript', TextLabel1)

	local player = game.Players.LocalPlayer
	if player then
		script.Parent.Text = "Hello "..player.Name.."!"
	end
end
coroutine.wrap(YPLPJTD_fake_script)()
local function HJFPBR_fake_script() -- Frame2.LocalScript 
	local script = Instance.new('LocalScript', Frame2)

	local UIS = game:GetService('UserInputService')
	local frame = script.Parent
	local dragToggle = nil
	local dragSpeed = 0.25
	local dragStart = nil
	local startPos = nil
	
	local function updateInput(input)
		local delta = input.Position - dragStart
		local position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X,
			startPos.Y.Scale, startPos.Y.Offset + delta.Y)
		game:GetService('TweenService'):Create(frame, TweenInfo.new(dragSpeed), {Position = position}):Play()
	end
	
	frame.InputBegan:Connect(function(input)
		if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) then 
			dragToggle = true
			dragStart = input.Position
			startPos = frame.Position
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragToggle = false
				end
			end)
		end
	end)
	
	UIS.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			if dragToggle then
				updateInput(input)
			end
		end
	end)
end
coroutine.wrap(HJFPBR_fake_script)()
local function RLFYB_fake_script() -- Main.LocalScript 
	local script = Instance.new('LocalScript', Main)

	local Frame1 = script.Parent.Parent.Frame1
	
	script.Parent.MouseButton1Click:Connect(function()
		Frame1.Visible = true
	end)
end
coroutine.wrap(RLFYB_fake_script)()
local function MCCAQ_fake_script() -- MoreScripts.LocalScript 
	local script = Instance.new('LocalScript', MoreScripts)

	local Frame = script.Parent.Parent.Frame
	
	script.Parent.MouseButton1Click:Connect(function()
		Frame.Visible = true
	end)
end
coroutine.wrap(MCCAQ_fake_script)()
local function ASPS_fake_script() -- TextLabel.Rainbow Frame 
	local script = Instance.new('LocalScript', TextLabel)

	function zigzag(X) return math.acos(math.cos(X*math.pi))/math.pi end
	
	counter = 0
	
	while wait(0.1)do
	 script.Parent.BackgroundColor3 = Color3.fromHSV(zigzag(counter),1,1)
	 
	 counter = counter + 0.01
	end
	
	--Enjoy ;) dont change anything. I didnt script this so i dont know if you can change but its adviced not 2
end
coroutine.wrap(ASPS_fake_script)()
local function TAKA_fake_script() -- X.LocalScript 
	local script = Instance.new('LocalScript', X)

	local Frame2 = script.Parent.Parent
	
	script.Parent.MouseButton1Click:Connect(function()
		Frame2.Visible = false
	end)
end
coroutine.wrap(TAKA_fake_script)()
local function ZNVQ_fake_script() -- X.LocalScript 
	local script = Instance.new('LocalScript', X)

	function zigzag(X) return math.acos(math.cos(X*math.pi))/math.pi end
	
	counter = 0
	
	while wait(0.1)do
		script.Parent.BackgroundColor3 = Color3.fromHSV(zigzag(counter),1,1)
	
		counter = counter + 0.01
	end
	
	--Enjoy ;) dont change anything. I didnt script this so i dont know if you can change but its adviced not 2
end
coroutine.wrap(ZNVQ_fake_script)()
local function LVBSSW_fake_script() -- Back.LocalScript 
	local script = Instance.new('LocalScript', Back)

	local Frame = script.Parent.Parent
	
	script.Parent.MouseButton1Click:Connect(function()
		Frame.Visible = false
	end)
end
coroutine.wrap(LVBSSW_fake_script)()
local function XDKZY_fake_script() -- OpenGui.LocalScript 
	local script = Instance.new('LocalScript', OpenGui)

	local Frame2 = script.Parent.Parent.Frame2
	
	script.Parent.MouseButton1Click:Connect(function()
		Frame2.Visible = true
	end)
end
coroutine.wrap(XDKZY_fake_script)()
Trade.MouseButton1Click:Connect(function()
	game:GetService("Players").LocalPlayer.PlayerGui.MainGui.LeftPanel.Market.Visible = true
	game:GetService("Players").LocalPlayer.PlayerGui.MainGui.RightPanel.Market.Visible = true
end)

TradeB.MouseButton1Click:Connect(function()
	game:GetService("Players").LocalPlayer.PlayerGui.MainGui.Panels.Card.List.Market.Visible = true
end)

EzPGui.MouseButton1Click:Connect(function()
	-- Gui to Lua
	-- Version: 3.2

	-- Instances:

	local ScreenGui = Instance.new("ScreenGui")
	local Open = Instance.new("TextButton")
	local Frame = Instance.new("Frame")
	local ByIiEzPiIRatatuiHelp = Instance.new("TextLabel")
	local AncientTP = Instance.new("TextButton")
	local MiddleTP = Instance.new("TextButton")
	local PickUp = Instance.new("TextButton")
	local InfJump = Instance.new("TextButton")
	local AuraQ = Instance.new("TextButton")
	local X = Instance.new("TextButton")
	local ClickDelete = Instance.new("TextButton")
	local CrystalTP = Instance.new("TextButton")
	local RockTP = Instance.new("TextButton")
	local WorldTps = Instance.new("TextLabel")
	local Volcano = Instance.new("TextButton")
	local Desert = Instance.new("TextButton")
	local Sky = Instance.new("TextButton")
	local Island = Instance.new("TextButton")
	local OldGod = Instance.new("TextButton")
	local WaterFall = Instance.new("TextButton")
	local Ice = Instance.new("TextButton")
	local Mountain = Instance.new("TextButton")
	local ESP = Instance.new("TextButton")
	local Island2 = Instance.new("TextButton")
	local Volcano2 = Instance.new("TextButton")
	local Middle2 = Instance.new("TextButton")
	local Pillars = Instance.new("TextButton")
	local DancingShelly = Instance.new("TextButton")
	local Giant = Instance.new("TextButton")
	local Desert2 = Instance.new("TextButton")
	local IslandF2 = Instance.new("TextButton")
	local IslandF = Instance.new("TextButton")
	local Cave = Instance.new("TextButton")
	local Jelly = Instance.new("TextButton")
	local VoidTps = Instance.new("TextLabel")
	local BoogaBooga2019 = Instance.new("TextLabel")
	local Middle = Instance.new("TextButton")
	local Shaders = Instance.new("TextButton")
	local PlayersTP = Instance.new("TextButton")
	local InfiniteYield = Instance.new("TextButton")
	local AutoHeal = Instance.new("TextButton")
	local Volcano3 = Instance.new("TextButton")
	local LossGui = Instance.new("TextButton")
	local OldGod3 = Instance.new("TextButton")
	local Energize = Instance.new("TextButton")
	local Emotes = Instance.new("TextButton")

	--Properties:

	ScreenGui.Parent = game.CoreGui
	ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

	Open.Name = "Open"
	Open.Parent = ScreenGui
	Open.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	Open.BackgroundTransparency = 0.610
	Open.BorderColor3 = Color3.fromRGB(0, 0, 255)
	Open.BorderSizePixel = 5
	Open.Position = UDim2.new(0.9414469, 0, 0.50298208, 0)
	Open.Size = UDim2.new(0, 80, 0, 50)
	Open.AutoButtonColor = false
	Open.Font = Enum.Font.Bangers
	Open.Text = "Open"
	Open.TextColor3 = Color3.fromRGB(0, 0, 0)
	Open.TextSize = 38.000
	Open.TextStrokeTransparency = 0.800
	Open.TextTransparency = 0.900
	Open.TextWrapped = true

	Frame.Parent = ScreenGui
	Frame.BackgroundColor3 = Color3.fromRGB(1, 0, 0)
	Frame.BorderColor3 = Color3.fromRGB(11, 0, 140)
	Frame.BorderSizePixel = 4
	Frame.Position = UDim2.new(0.205346018, 0, 0.0750828236, 0)
	Frame.Selectable = true
	Frame.Size = UDim2.new(0, 732, 0, 454)
	Frame.Visible = false
	Frame.ZIndex = 0

	ByIiEzPiIRatatuiHelp.Name = "By IiEzPiI/RatatuiHelp"
	ByIiEzPiIRatatuiHelp.Parent = Frame
	ByIiEzPiIRatatuiHelp.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	ByIiEzPiIRatatuiHelp.BorderColor3 = Color3.fromRGB(11, 0, 140)
	ByIiEzPiIRatatuiHelp.BorderSizePixel = 5
	ByIiEzPiIRatatuiHelp.Position = UDim2.new(0.366544962, 0, -0.0423087738, 0)
	ByIiEzPiIRatatuiHelp.Size = UDim2.new(0, 463, 0, 28)
	ByIiEzPiIRatatuiHelp.Font = Enum.Font.Ubuntu
	ByIiEzPiIRatatuiHelp.Text = "By IiEzPiI/RatatuiHelp"
	ByIiEzPiIRatatuiHelp.TextColor3 = Color3.fromRGB(255, 255, 255)
	ByIiEzPiIRatatuiHelp.TextSize = 20.000
	ByIiEzPiIRatatuiHelp.TextStrokeColor3 = Color3.fromRGB(0, 0, 255)
	ByIiEzPiIRatatuiHelp.TextWrapped = true

	AncientTP.Name = "AncientTP"
	AncientTP.Parent = Frame
	AncientTP.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	AncientTP.BorderColor3 = Color3.fromRGB(11, 0, 140)
	AncientTP.Position = UDim2.new(0.753737509, 0, 0.794571996, 0)
	AncientTP.Size = UDim2.new(0, 180, 0, 29)
	AncientTP.Font = Enum.Font.GothamBlack
	AncientTP.Text = "AncientTP"
	AncientTP.TextColor3 = Color3.fromRGB(255, 255, 255)
	AncientTP.TextSize = 14.000

	MiddleTP.Name = "MiddleTP"
	MiddleTP.Parent = Frame
	MiddleTP.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	MiddleTP.BorderColor3 = Color3.fromRGB(11, 0, 140)
	MiddleTP.Position = UDim2.new(0.753204882, 0, 0.660334408, 0)
	MiddleTP.Size = UDim2.new(0, 180, 0, 29)
	MiddleTP.Font = Enum.Font.GothamBlack
	MiddleTP.Text = "MiddleTP"
	MiddleTP.TextColor3 = Color3.fromRGB(255, 255, 255)
	MiddleTP.TextSize = 14.000

	PickUp.Name = "PickUp"
	PickUp.Parent = Frame
	PickUp.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	PickUp.BorderColor3 = Color3.fromRGB(11, 0, 140)
	PickUp.Position = UDim2.new(0.751711309, 0, 0.212117106, 0)
	PickUp.Size = UDim2.new(0, 180, 0, 29)
	PickUp.Font = Enum.Font.GothamBlack
	PickUp.Text = "PickUp"
	PickUp.TextColor3 = Color3.fromRGB(255, 255, 255)
	PickUp.TextSize = 14.000

	InfJump.Name = "InfJump"
	InfJump.Parent = Frame
	InfJump.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	InfJump.BorderColor3 = Color3.fromRGB(11, 0, 140)
	InfJump.Position = UDim2.new(0.507886112, 0, 0.212574959, 0)
	InfJump.Size = UDim2.new(0, 180, 0, 29)
	InfJump.Font = Enum.Font.GothamBlack
	InfJump.Text = "InfJump"
	InfJump.TextColor3 = Color3.fromRGB(255, 255, 255)
	InfJump.TextSize = 14.000

	AuraQ.Name = "AuraQ"
	AuraQ.Parent = Frame
	AuraQ.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	AuraQ.BorderColor3 = Color3.fromRGB(11, 0, 140)
	AuraQ.Position = UDim2.new(0.753645062, 0, 0.0834214985, 0)
	AuraQ.Size = UDim2.new(0, 180, 0, 29)
	AuraQ.Font = Enum.Font.GothamBlack
	AuraQ.Text = "AuraQ"
	AuraQ.TextColor3 = Color3.fromRGB(255, 255, 255)
	AuraQ.TextSize = 14.000

	X.Name = "X"
	X.Parent = Frame
	X.BackgroundColor3 = Color3.fromRGB(255, 32, 32)
	X.BorderColor3 = Color3.fromRGB(0, 0, 0)
	X.BorderSizePixel = 2
	X.Position = UDim2.new(0.972456038, 0, -0.0603094921, 0)
	X.Size = UDim2.new(0, 41, 0, 36)
	X.Font = Enum.Font.SourceSans
	X.Text = "X"
	X.TextColor3 = Color3.fromRGB(0, 0, 0)
	X.TextSize = 14.000
	X.TextWrapped = true

	ClickDelete.Name = "ClickDelete"
	ClickDelete.Parent = Frame
	ClickDelete.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	ClickDelete.BorderColor3 = Color3.fromRGB(11, 0, 140)
	ClickDelete.Position = UDim2.new(0.261031866, 0, 0.209080279, 0)
	ClickDelete.Size = UDim2.new(0, 180, 0, 29)
	ClickDelete.Font = Enum.Font.GothamBlack
	ClickDelete.Text = "ClickDelete"
	ClickDelete.TextColor3 = Color3.fromRGB(255, 255, 255)
	ClickDelete.TextSize = 14.000

	CrystalTP.Name = "CrystalTP"
	CrystalTP.Parent = Frame
	CrystalTP.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	CrystalTP.BorderColor3 = Color3.fromRGB(11, 0, 140)
	CrystalTP.Position = UDim2.new(0.75377351, 0, 0.728171706, 0)
	CrystalTP.Size = UDim2.new(0, 180, 0, 29)
	CrystalTP.Font = Enum.Font.GothamBlack
	CrystalTP.Text = "CrystalTP"
	CrystalTP.TextColor3 = Color3.fromRGB(255, 255, 255)
	CrystalTP.TextSize = 14.000

	RockTP.Name = "RockTP"
	RockTP.Parent = Frame
	RockTP.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	RockTP.BorderColor3 = Color3.fromRGB(11, 0, 140)
	RockTP.Position = UDim2.new(0.00236004591, 0, 0.727946877, 0)
	RockTP.Size = UDim2.new(0, 180, 0, 29)
	RockTP.Font = Enum.Font.GothamBlack
	RockTP.Text = "RockTP"
	RockTP.TextColor3 = Color3.fromRGB(255, 255, 255)
	RockTP.TextSize = 14.000
	RockTP.TextWrapped = true

	WorldTps.Name = "World Tps"
	WorldTps.Parent = Frame
	WorldTps.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
	WorldTps.BorderColor3 = Color3.fromRGB(0, 0, 0)
	WorldTps.BorderSizePixel = 2
	WorldTps.Position = UDim2.new(0.506595314, 0, 0.277009726, 0)
	WorldTps.Size = UDim2.new(0, 358, 0, 28)
	WorldTps.Font = Enum.Font.Bangers
	WorldTps.Text = "World Tps"
	WorldTps.TextColor3 = Color3.fromRGB(0, 0, 0)
	WorldTps.TextSize = 27.000
	WorldTps.TextWrapped = true

	Volcano.Name = "Volcano"
	Volcano.Parent = Frame
	Volcano.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	Volcano.BorderColor3 = Color3.fromRGB(11, 0, 140)
	Volcano.Position = UDim2.new(0.754055083, 0, 0.538674414, 0)
	Volcano.Size = UDim2.new(0, 180, 0, 29)
	Volcano.Font = Enum.Font.GothamBlack
	Volcano.Text = "Volcano"
	Volcano.TextColor3 = Color3.fromRGB(255, 255, 255)
	Volcano.TextSize = 14.000

	Desert.Name = "Desert"
	Desert.Parent = Frame
	Desert.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	Desert.BorderColor3 = Color3.fromRGB(11, 0, 140)
	Desert.Position = UDim2.new(0.75332737, 0, 0.856671333, 0)
	Desert.Size = UDim2.new(0, 180, 0, 29)
	Desert.Font = Enum.Font.GothamBlack
	Desert.Text = "Desert"
	Desert.TextColor3 = Color3.fromRGB(255, 255, 255)
	Desert.TextSize = 14.000

	Sky.Name = "Sky"
	Sky.Parent = Frame
	Sky.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	Sky.BorderColor3 = Color3.fromRGB(11, 0, 140)
	Sky.Position = UDim2.new(0.753565669, 0, 0.410523534, 0)
	Sky.Size = UDim2.new(0, 180, 0, 29)
	Sky.Font = Enum.Font.GothamBlack
	Sky.Text = "Sky"
	Sky.TextColor3 = Color3.fromRGB(255, 255, 255)
	Sky.TextSize = 14.000

	Island.Name = "Island"
	Island.Parent = Frame
	Island.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	Island.BorderColor3 = Color3.fromRGB(11, 0, 140)
	Island.Position = UDim2.new(0.50685364, 0, 0.601112425, 0)
	Island.Size = UDim2.new(0, 180, 0, 26)
	Island.Font = Enum.Font.GothamBlack
	Island.Text = "Island"
	Island.TextColor3 = Color3.fromRGB(255, 255, 255)
	Island.TextSize = 14.000

	OldGod.Name = "OldGod"
	OldGod.Parent = Frame
	OldGod.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	OldGod.BorderColor3 = Color3.fromRGB(11, 0, 140)
	OldGod.Position = UDim2.new(0.50680089, 0, 0.729906738, 0)
	OldGod.Size = UDim2.new(0, 180, 0, 29)
	OldGod.Font = Enum.Font.GothamBlack
	OldGod.Text = "OldGod"
	OldGod.TextColor3 = Color3.fromRGB(255, 255, 255)
	OldGod.TextSize = 14.000

	WaterFall.Name = "WaterFall"
	WaterFall.Parent = Frame
	WaterFall.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	WaterFall.BorderColor3 = Color3.fromRGB(11, 0, 140)
	WaterFall.Position = UDim2.new(0.507897735, 0, 0.856498599, 0)
	WaterFall.Size = UDim2.new(0, 180, 0, 29)
	WaterFall.Font = Enum.Font.GothamBlack
	WaterFall.Text = "WaterFall"
	WaterFall.TextColor3 = Color3.fromRGB(255, 255, 255)
	WaterFall.TextSize = 14.000

	Ice.Name = "Ice"
	Ice.Parent = Frame
	Ice.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	Ice.BorderColor3 = Color3.fromRGB(11, 0, 140)
	Ice.Position = UDim2.new(0.753292501, 0, 0.474227697, 0)
	Ice.Size = UDim2.new(0, 180, 0, 29)
	Ice.Font = Enum.Font.GothamBlack
	Ice.Text = "Ice"
	Ice.TextColor3 = Color3.fromRGB(255, 255, 255)
	Ice.TextSize = 14.000

	Mountain.Name = "Mountain"
	Mountain.Parent = Frame
	Mountain.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	Mountain.BorderColor3 = Color3.fromRGB(11, 0, 140)
	Mountain.Position = UDim2.new(0.508042812, 0, 0.92049551, 0)
	Mountain.Size = UDim2.new(0, 180, 0, 27)
	Mountain.Font = Enum.Font.GothamBlack
	Mountain.Text = "Mountain"
	Mountain.TextColor3 = Color3.fromRGB(255, 255, 255)
	Mountain.TextSize = 14.000

	ESP.Name = "ESP"
	ESP.Parent = Frame
	ESP.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	ESP.BorderColor3 = Color3.fromRGB(11, 0, 140)
	ESP.Position = UDim2.new(0.752749264, 0, 0.146776646, 0)
	ESP.Size = UDim2.new(0, 180, 0, 29)
	ESP.Font = Enum.Font.GothamBlack
	ESP.Text = "ESP"
	ESP.TextColor3 = Color3.fromRGB(255, 255, 255)
	ESP.TextSize = 17.000

	Island2.Name = "Island2"
	Island2.Parent = Frame
	Island2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	Island2.BorderColor3 = Color3.fromRGB(11, 0, 140)
	Island2.Position = UDim2.new(0.507427096, 0, 0.539317906, 0)
	Island2.Size = UDim2.new(0, 180, 0, 26)
	Island2.Font = Enum.Font.GothamBlack
	Island2.Text = "Island2"
	Island2.TextColor3 = Color3.fromRGB(255, 255, 255)
	Island2.TextSize = 14.000

	Volcano2.Name = "Volcano2"
	Volcano2.Parent = Frame
	Volcano2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	Volcano2.BorderColor3 = Color3.fromRGB(11, 0, 140)
	Volcano2.Position = UDim2.new(0.507421136, 0, 0.666272819, 0)
	Volcano2.Size = UDim2.new(0, 180, 0, 26)
	Volcano2.Font = Enum.Font.GothamBlack
	Volcano2.Text = "Volcano2"
	Volcano2.TextColor3 = Color3.fromRGB(255, 255, 255)
	Volcano2.TextSize = 14.000

	Middle2.Name = "Middle2"
	Middle2.Parent = Frame
	Middle2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	Middle2.BorderColor3 = Color3.fromRGB(11, 0, 140)
	Middle2.Position = UDim2.new(0.754055083, 0, 0.596706986, 0)
	Middle2.Size = UDim2.new(0, 179, 0, 29)
	Middle2.Font = Enum.Font.GothamBlack
	Middle2.Text = "Middle2"
	Middle2.TextColor3 = Color3.fromRGB(255, 255, 255)
	Middle2.TextSize = 14.000

	Pillars.Name = "Pillars"
	Pillars.Parent = Frame
	Pillars.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	Pillars.BorderColor3 = Color3.fromRGB(11, 0, 140)
	Pillars.Position = UDim2.new(0.00337420544, 0, 0.342811912, 0)
	Pillars.Size = UDim2.new(0, 180, 0, 29)
	Pillars.Font = Enum.Font.GothamBlack
	Pillars.Text = "3 Pillars"
	Pillars.TextColor3 = Color3.fromRGB(255, 255, 255)
	Pillars.TextSize = 14.000

	DancingShelly.Name = "DancingShelly"
	DancingShelly.Parent = Frame
	DancingShelly.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	DancingShelly.BorderColor3 = Color3.fromRGB(11, 0, 140)
	DancingShelly.Position = UDim2.new(0.508022308, 0, 0.793385804, 0)
	DancingShelly.Size = UDim2.new(0, 180, 0, 29)
	DancingShelly.Font = Enum.Font.GothamBlack
	DancingShelly.Text = "Dancing Shelly"
	DancingShelly.TextColor3 = Color3.fromRGB(255, 255, 255)
	DancingShelly.TextSize = 14.000

	Giant.Name = "Giant"
	Giant.Parent = Frame
	Giant.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	Giant.BorderColor3 = Color3.fromRGB(11, 0, 140)
	Giant.Position = UDim2.new(0.753923893, 0, 0.341843873, 0)
	Giant.Size = UDim2.new(0, 180, 0, 29)
	Giant.Font = Enum.Font.GothamBlack
	Giant.Text = "Giant"
	Giant.TextColor3 = Color3.fromRGB(255, 255, 255)
	Giant.TextSize = 14.000

	Desert2.Name = "Desert2"
	Desert2.Parent = Frame
	Desert2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	Desert2.BorderColor3 = Color3.fromRGB(11, 0, 140)
	Desert2.Position = UDim2.new(0.754055083, 0, 0.920547962, 0)
	Desert2.Size = UDim2.new(0, 179, 0, 27)
	Desert2.Font = Enum.Font.GothamBlack
	Desert2.Text = "Desert2"
	Desert2.TextColor3 = Color3.fromRGB(255, 255, 255)
	Desert2.TextSize = 14.000

	IslandF2.Name = "IslandF2"
	IslandF2.Parent = Frame
	IslandF2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	IslandF2.BorderColor3 = Color3.fromRGB(11, 0, 140)
	IslandF2.Position = UDim2.new(0.00234951894, 0, 0.40727976, 0)
	IslandF2.Size = UDim2.new(0, 180, 0, 29)
	IslandF2.Font = Enum.Font.GothamBlack
	IslandF2.Text = "Island Floating 2"
	IslandF2.TextColor3 = Color3.fromRGB(255, 255, 255)
	IslandF2.TextSize = 14.000

	IslandF.Name = "IslandF"
	IslandF.Parent = Frame
	IslandF.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	IslandF.BorderColor3 = Color3.fromRGB(11, 0, 140)
	IslandF.Position = UDim2.new(0.00294953585, 0, 0.666030049, 0)
	IslandF.Size = UDim2.new(0, 180, 0, 29)
	IslandF.Font = Enum.Font.GothamBlack
	IslandF.Text = "Island Floating"
	IslandF.TextColor3 = Color3.fromRGB(255, 255, 255)
	IslandF.TextSize = 14.000

	Cave.Name = "Cave"
	Cave.Parent = Frame
	Cave.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	Cave.BorderColor3 = Color3.fromRGB(11, 0, 140)
	Cave.Position = UDim2.new(0.00200873613, 0, 0.475613952, 0)
	Cave.Size = UDim2.new(0, 180, 0, 29)
	Cave.Font = Enum.Font.GothamBlack
	Cave.Text = "Mag Cave"
	Cave.TextColor3 = Color3.fromRGB(255, 255, 255)
	Cave.TextSize = 14.000

	Jelly.Name = "Jelly"
	Jelly.Parent = Frame
	Jelly.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	Jelly.BorderColor3 = Color3.fromRGB(11, 0, 140)
	Jelly.Position = UDim2.new(0.00200810283, 0, 0.538674295, 0)
	Jelly.Size = UDim2.new(0, 180, 0, 29)
	Jelly.Font = Enum.Font.GothamBlack
	Jelly.Text = "Jelly Tree"
	Jelly.TextColor3 = Color3.fromRGB(255, 255, 255)
	Jelly.TextSize = 14.000

	VoidTps.Name = "Void Tps"
	VoidTps.Parent = Frame
	VoidTps.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
	VoidTps.BorderColor3 = Color3.fromRGB(0, 0, 0)
	VoidTps.BorderSizePixel = 2
	VoidTps.Position = UDim2.new(0.00337419356, 0, 0.277009666, 0)
	VoidTps.Size = UDim2.new(0, 369, 0, 28)
	VoidTps.Font = Enum.Font.Bangers
	VoidTps.Text = "Void Tps"
	VoidTps.TextColor3 = Color3.fromRGB(0, 0, 0)
	VoidTps.TextSize = 27.000
	VoidTps.TextStrokeColor3 = Color3.fromRGB(45, 45, 45)

	BoogaBooga2019.Name = "Booga Booga 2019"
	BoogaBooga2019.Parent = Frame
	BoogaBooga2019.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	BoogaBooga2019.BorderColor3 = Color3.fromRGB(11, 0, 140)
	BoogaBooga2019.BorderSizePixel = 4
	BoogaBooga2019.Position = UDim2.new(-0.000372214388, 0, -0.0423087738, 0)
	BoogaBooga2019.Size = UDim2.new(0, 269, 0, 27)
	BoogaBooga2019.Font = Enum.Font.Ubuntu
	BoogaBooga2019.Text = "Booga Booga 2019"
	BoogaBooga2019.TextColor3 = Color3.fromRGB(255, 255, 255)
	BoogaBooga2019.TextSize = 23.000

	Middle.Name = "Middle"
	Middle.Parent = Frame
	Middle.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	Middle.BorderColor3 = Color3.fromRGB(11, 0, 140)
	Middle.Position = UDim2.new(0.00225731055, 0, 0.602396131, 0)
	Middle.Size = UDim2.new(0, 180, 0, 29)
	Middle.Font = Enum.Font.GothamBlack
	Middle.Text = "Middle"
	Middle.TextColor3 = Color3.fromRGB(255, 255, 255)
	Middle.TextSize = 14.000
	Middle.TextWrapped = true

	Shaders.Name = "Shaders"
	Shaders.Parent = Frame
	Shaders.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	Shaders.BorderColor3 = Color3.fromRGB(11, 0, 140)
	Shaders.Position = UDim2.new(0.507175803, 0, 0.0821611732, 0)
	Shaders.Size = UDim2.new(0, 180, 0, 29)
	Shaders.Font = Enum.Font.GothamBlack
	Shaders.Text = "Shaders"
	Shaders.TextColor3 = Color3.fromRGB(255, 255, 255)
	Shaders.TextSize = 14.000

	PlayersTP.Name = "PlayersTP"
	PlayersTP.Parent = Frame
	PlayersTP.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	PlayersTP.BorderColor3 = Color3.fromRGB(11, 0, 140)
	PlayersTP.Position = UDim2.new(0.505809665, 0, 0.146037817, 0)
	PlayersTP.Size = UDim2.new(0, 180, 0, 29)
	PlayersTP.Font = Enum.Font.GothamBlack
	PlayersTP.Text = "PlayersTP"
	PlayersTP.TextColor3 = Color3.fromRGB(255, 255, 255)
	PlayersTP.TextSize = 14.000

	InfiniteYield.Name = "InfiniteYield"
	InfiniteYield.Parent = Frame
	InfiniteYield.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	InfiniteYield.BorderColor3 = Color3.fromRGB(11, 0, 140)
	InfiniteYield.Position = UDim2.new(0.261274159, 0, 0.148240462, 0)
	InfiniteYield.Size = UDim2.new(0, 180, 0, 29)
	InfiniteYield.Font = Enum.Font.GothamBlack
	InfiniteYield.Text = "Infinite Yield"
	InfiniteYield.TextColor3 = Color3.fromRGB(255, 255, 255)
	InfiniteYield.TextSize = 14.000

	AutoHeal.Name = "AutoHeal"
	AutoHeal.Parent = Frame
	AutoHeal.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	AutoHeal.BorderColor3 = Color3.fromRGB(11, 0, 140)
	AutoHeal.Position = UDim2.new(0.261274159, 0, 0.0843638033, 0)
	AutoHeal.Size = UDim2.new(0, 180, 0, 29)
	AutoHeal.Font = Enum.Font.GothamBlack
	AutoHeal.Text = "Auto Heal"
	AutoHeal.TextColor3 = Color3.fromRGB(255, 255, 255)
	AutoHeal.TextSize = 14.000

	Volcano3.Name = "Volcano3"
	Volcano3.Parent = Frame
	Volcano3.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	Volcano3.BorderColor3 = Color3.fromRGB(11, 0, 140)
	Volcano3.Position = UDim2.new(0.507427096, 0, 0.409361959, 0)
	Volcano3.Size = UDim2.new(0, 180, 0, 26)
	Volcano3.Font = Enum.Font.GothamBlack
	Volcano3.Text = "Under Volcano"
	Volcano3.TextColor3 = Color3.fromRGB(255, 255, 255)
	Volcano3.TextSize = 14.000

	LossGui.Name = "LossGui"
	LossGui.Parent = Frame
	LossGui.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	LossGui.BorderColor3 = Color3.fromRGB(11, 0, 140)
	LossGui.Position = UDim2.new(0.0142576993, 0, 0.213326737, 0)
	LossGui.Size = UDim2.new(0, 180, 0, 26)
	LossGui.Font = Enum.Font.GothamBlack
	LossGui.Text = "Loss Gui"
	LossGui.TextColor3 = Color3.fromRGB(255, 255, 255)
	LossGui.TextSize = 14.000

	OldGod3.Name = "OldGod3"
	OldGod3.Parent = Frame
	OldGod3.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	OldGod3.BorderColor3 = Color3.fromRGB(11, 0, 140)
	OldGod3.Position = UDim2.new(0.504694879, 0, 0.475441247, 0)
	OldGod3.Size = UDim2.new(0, 180, 0, 26)
	OldGod3.Font = Enum.Font.GothamBlack
	OldGod3.Text = "Under OldGod"
	OldGod3.TextColor3 = Color3.fromRGB(255, 255, 255)
	OldGod3.TextSize = 14.000

	Energize.Name = "Energize"
	Energize.Parent = Frame
	Energize.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	Energize.BorderColor3 = Color3.fromRGB(11, 0, 140)
	Energize.Position = UDim2.new(0.0142576993, 0, 0.0899787173, 0)
	Energize.Size = UDim2.new(0, 180, 0, 26)
	Energize.Font = Enum.Font.GothamBlack
	Energize.Text = "Energize Gui"
	Energize.TextColor3 = Color3.fromRGB(255, 255, 255)
	Energize.TextSize = 14.000

	Emotes.Name = "Emotes"
	Emotes.Parent = Frame
	Emotes.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	Emotes.BorderColor3 = Color3.fromRGB(11, 0, 140)
	Emotes.Position = UDim2.new(0.0142576993, 0, 0.156058013, 0)
	Emotes.Size = UDim2.new(0, 180, 0, 26)
	Emotes.Font = Enum.Font.GothamBlack
	Emotes.Text = "Emotes"
	Emotes.TextColor3 = Color3.fromRGB(255, 255, 255)
	Emotes.TextSize = 14.000

	-- Scripts:

	local function HRZGJAF_fake_script() -- Open.LocalScript 
		local script = Instance.new('LocalScript', Open)

		script.Parent.MouseButton1Down:Connect(function()
			script.Parent.Parent.Frame.Visible = true
		end)
	end
	coroutine.wrap(HRZGJAF_fake_script)()
	local function VCSU_fake_script() -- X.LocalScript 
		local script = Instance.new('LocalScript', X)

		script.Parent.MouseButton1Down:Connect(function()
			script.Parent.Parent.Parent.Frame.Visible = false
		end)
	end
	coroutine.wrap(VCSU_fake_script)()
	AncientTP.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1118, -144, 1152)
		wait(0.9)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-558, 314, -1195)
	end)

	Middle.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-800, 2, 153)
		wait(0.9)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1, 37, 203)
	end)

	Pillars.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-800, 2, 153)
		wait(0.9)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-160, 17, -757)
	end)

	Cave.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-800, 2, 153)
		wait(0.9)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(683, 44, -694)
	end)

	IslandF.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-800, 2, 153)
		wait(0.2)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(708, 144, 581)
	end)

	IslandF2.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-800, 2, 153)
		wait(0.9)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-156, 139, -220)
	end)

	Jelly.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-800, 2, 153)
		wait(0.9)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(232, 10, -151)
	end)

	ClickDelete.MouseButton1Click:Connect(function()
		local Plr = game:GetService("Players").LocalPlayer
		local Mouse = Plr:GetMouse()

		Mouse.Button1Down:connect(function()
			if not game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftControl) then return end
			if not Mouse.Target then return end
			Mouse.Target:Destroy()
		end)
	end)

	AuraQ.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/aFxNz9Fy33ETuWKxs6q8KPRMMP6P8FFbJNjmHq9/booga-hybrid/main/killaura.lua", true))()
	end)

	Ice.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1118, -144, 1152)
		wait(0.9)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(339, 72, -1476)
	end)

	Desert.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1118, -144, 1152)
		wait(0.9)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(798, -0, 218)
	end)

	InfJump.MouseButton1Click:Connect(function()
		local InfiniteJumpEnabled = true
		game:GetService("UserInputService").JumpRequest:connect(function()
			if InfiniteJumpEnabled then
				game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")
			end
		end) end)

	CrystalTP.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1118, -144, 1152)
		wait(0.9)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1236, 305, -1290)
	end)

	InfiniteYield.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet(('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'),true))()
	end)

	LossGui.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet(('https://raw.githubusercontent.com/lololboogahacker/loss-hub/main/VAMPTHEGODLEAKER.txt'),true))()
	end)

	OldGod3.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1118, -144, 1152)
		wait(0.9)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1057, -110, -672)
		game:GetService("Workspace").Lights:Destroy()
		game:GetService("Workspace").TpBack.TopOfWhiteAntArea:Destroy()
		game:GetService("Workspace").TpBack.TopOfWhiteAntArea:Destroy()
		game:GetService("Workspace").TpBack.TopOfWhiteAntArea:Destroy()
		game:GetService("Workspace").TpBack.TopOfWhiteAntArea:Destroy()
		game:GetService("Workspace").Terrain:Destroy()
	end)

	Volcano3.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1111, -202, -743)
		wait(0.9)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1115, -73, 1185)
		game:GetService("Workspace").TpBack.TopOfLavaArea:Destroy()
		game:GetService("Workspace").TpBack.TopOfLavaArea:Destroy()
		game:GetService("Workspace").TpBack.TopOfLavaArea:Destroy()
		game:GetService("Workspace").TpBack.TopOfLavaArea:Destroy()
		game:GetService("Workspace").TpBack.TopOfLavaArea:Destroy()
		game:GetService("Workspace").Terrain:Destroy()
	end)

	Emotes.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://gitlab.com/Tsuniox/lua-stuff/-/raw/master/R15GUI.lua"))()
	end)

	Energize.MouseButton1Click:Connect(function()
		-- Energize by illremember, fe animations
		-- DO NOT COPY AND CLAIM AS OWN, if you are using some of the script for your own, credit is highly appreciated!
		-- Thank you, and enjoy.

		-- Objects

		local Energize = Instance.new("ScreenGui") -- The actual GUI
		local SideFrame = Instance.new("Frame") -- Visible when GUI is closed
		local OpenGUI = Instance.new("TextButton") -- Part of SideFrame
		local SideFrameTitle = Instance.new("TextLabel") -- Part of SideFrame
		local MainFrame = Instance.new("Frame") -- All of the stuff on the main frame
		local GuiBottomFrame = Instance.new("Frame") -- Part of Active Frame
		local Credits = Instance.new("TextLabel") -- Credits to illremember, hello there
		local ScrollingFrame = Instance.new("ScrollingFrame") -- The scrolling frame of animations
		local CheckR = Instance.new("TextLabel") -- Check if R15 or R6
		local ScrollingFrameR15 = Instance.new("ScrollingFrame") -- The scrolling frame of R15 animations

		local CrazySlash = Instance.new("TextButton")--COMPLETE
		local Open = Instance.new("TextButton")--COMPLETE
		local R15Spinner = Instance.new("TextButton")--COMPLETE
		local ArmsOut = Instance.new("TextButton")--COMPLETE
		local FloatSlash = Instance.new("TextButton")--COMPLETE
		local WeirdZombie = Instance.new("TextButton")--COMPLETE
		local DownSlash = Instance.new("TextButton")--COMPLETE
		local Pull = Instance.new("TextButton")--COMPLETE
		local CircleArm = Instance.new("TextButton")--COMPLETE
		local Bend = Instance.new("TextButton")--COMPLETE
		local RotateSlash = Instance.new("TextButton")--COMPLETE
		local FlingArms = Instance.new("TextButton")--COMPLETE

		local FullSwing = Instance.new("TextButton")--COMPLETE
		local GlitchLevitate = Instance.new("TextButton")--COMPLETE
		local MoonDance = Instance.new("TextButton")--COMPLETE
		local FullPunch = Instance.new("TextButton")--COMPLETE
		local Crouch = Instance.new("TextButton")--COMPLETE
		local SpinDance = Instance.new("TextButton")--COMPLETE
		local FloorFaint = Instance.new("TextButton")--COMPLETE
		local JumpingJacks = Instance.new("TextButton")--COMPLETE
		local Spinner = Instance.new("TextButton")--COMPLETE
		local MegaInsane = Instance.new("TextButton")--COMPLETE
		local ArmDetach = Instance.new("TextButton")--COMPLETE
		local WeirdMove = Instance.new("TextButton")--COMPLETE
		local Faint = Instance.new("TextButton")--COMPLETE
		local CloneIllusion = Instance.new("TextButton")--COMPLETE
		local Levitate = Instance.new("TextButton")--COMPLETE
		local DinoWalk = Instance.new("TextButton")--COMPLETE
		local FloorCrawl = Instance.new("TextButton")--COMPLETE
		local SwordSlam = Instance.new("TextButton")--COMPLETE
		local LoopHead = Instance.new("TextButton")--COMPLETE
		local HeroJump = Instance.new("TextButton")--COMPLETE
		local Insane = Instance.new("TextButton")--COMPLETE
		local FloatingHead = Instance.new("TextButton")--COMPLETE
		local HeadThrow = Instance.new("TextButton")--COMPLETE
		local MovingDance = Instance.new("TextButton")--COMPLETE
		local SuperPunch = Instance.new("TextButton")--COMPLETE
		local ArmTurbine = Instance.new("TextButton")--COMPLETE
		local Dab = Instance.new("TextButton")--COMPLETE
		local FloatSit = Instance.new("TextButton")--COMPLETE
		local SuperFaint = Instance.new("TextButton")--COMPLETE
		local BarrelRoll = Instance.new("TextButton")--COMPLETE
		local Scared = Instance.new("TextButton")--COMPLETE
		local InsaneArms = Instance.new("TextButton")--COMPLETE
		local SwordSlice = Instance.new("TextButton")--COMPLETE
		local SpinDance2 = Instance.new("TextButton")--COMPLETE
		local BowDown = Instance.new("TextButton")--COMPLETE
		local LoopSlam = Instance.new("TextButton")--COMPLETE

		local GuiTopFrame = Instance.new("Frame") -- Top of the main frame
		local CloseGUI = Instance.new("TextButton") -- To close the GUI
		local Title = Instance.new("TextLabel") -- Actual title of GUI, Energize

		-- Properties

		Energize.Name = "Energize"
		Energize.Parent = game.Players.LocalPlayer.PlayerGui

		SideFrame.Name = "SideFrame"
		SideFrame.Parent = Energize
		SideFrame.Active = true
		SideFrame.BackgroundColor3 = Color3.new(1, 0.329412, 0.329412)
		SideFrame.Draggable = true
		SideFrame.Position = UDim2.new(0, 376, 0, 125)
		SideFrame.Size = UDim2.new(0, 460, 0, 32)
		SideFrame.Visible = false

		OpenGUI.Name = "OpenGUI"
		OpenGUI.Parent = SideFrame
		OpenGUI.BackgroundColor3 = Color3.new(1, 1, 1)
		OpenGUI.BackgroundTransparency = 1
		OpenGUI.Position = UDim2.new(0, 426, 0, 0)
		OpenGUI.Size = UDim2.new(0, 34, 0, 32)
		OpenGUI.Font = Enum.Font.SourceSans
		OpenGUI.FontSize = Enum.FontSize.Size48
		OpenGUI.Text = "X"
		OpenGUI.TextColor3 = Color3.new(0.333333, 0, 0)
		OpenGUI.TextSize = 40
		OpenGUI.TextWrapped = true

		SideFrameTitle.Name = "SideFrameTitle"
		SideFrameTitle.Parent = SideFrame
		SideFrameTitle.BackgroundColor3 = Color3.new(1, 1, 1)
		SideFrameTitle.BackgroundTransparency = 1
		SideFrameTitle.Position = UDim2.new(0, 170, 0, 0)
		SideFrameTitle.Size = UDim2.new(0, 119, 0, 31)
		SideFrameTitle.Font = Enum.Font.Arial
		SideFrameTitle.FontSize = Enum.FontSize.Size24
		SideFrameTitle.Text = "Energize"
		SideFrameTitle.TextSize = 21
		SideFrameTitle.TextStrokeColor3 = Color3.new(0.27451, 0.92549, 0.905882)
		SideFrameTitle.TextStrokeTransparency = 0.69999998807907

		MainFrame.Name = "MainFrame"
		MainFrame.Parent = Energize
		MainFrame.Active = true
		MainFrame.BackgroundColor3 = Color3.new(1, 1, 1)
		MainFrame.BackgroundTransparency = 1
		MainFrame.Draggable = true
		MainFrame.Position = UDim2.new(0, 376, 0, 125)
		MainFrame.Size = UDim2.new(0, 444, 0, 280)

		GuiBottomFrame.Name = "Gui BottomFrame"
		GuiBottomFrame.Parent = MainFrame
		GuiBottomFrame.BackgroundColor3 = Color3.new(1, 0.329412, 0.329412)
		GuiBottomFrame.BorderColor3 = Color3.new(0.243137, 0.243137, 0.243137)
		GuiBottomFrame.Position = UDim2.new(0, 0, 0, 247)
		GuiBottomFrame.Size = UDim2.new(0, 460, 0, 32)

		Credits.Name = "Credits"
		Credits.Parent = GuiBottomFrame
		Credits.BackgroundColor3 = Color3.new(1, 1, 1)
		Credits.BackgroundTransparency = 1
		Credits.Size = UDim2.new(0, 460, 0, 32)
		Credits.FontSize = Enum.FontSize.Size14
		Credits.Text = "By illremember FE Animations Gui"
		Credits.TextColor3 = Color3.new(0.219608, 0.219608, 0.219608)
		Credits.TextSize = 14
		Credits.TextStrokeColor3 = Color3.new(0.141176, 0.870588, 0.713726)
		Credits.TextStrokeTransparency = 0.69999998807907
		Credits.TextWrapped = true

		ScrollingFrame.Parent = MainFrame
		ScrollingFrame.BackgroundColor3 = Color3.new(1, 0.564706, 0.564706)
		ScrollingFrame.Position = UDim2.new(0, 0, 0, 32)
		ScrollingFrame.Size = UDim2.new(0, 460, 0, 215)
		ScrollingFrame.ScrollBarThickness = 13

		FullSwing.Name = "FullSwing"
		FullSwing.Parent = ScrollingFrame
		FullSwing.BackgroundColor3 = Color3.new(0.886275, 0.776471, 0.368627)
		FullSwing.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		FullSwing.Position = UDim2.new(0, 17, 0, 322)
		FullSwing.Size = UDim2.new(0, 119, 0, 34)
		FullSwing.Font = Enum.Font.Highway
		FullSwing.FontSize = Enum.FontSize.Size24
		FullSwing.Text = "Full Swing"
		FullSwing.TextSize = 20
		FullSwing.TextWrapped = true

		GlitchLevitate.Name = "GlitchLevitate"
		GlitchLevitate.Parent = ScrollingFrame
		GlitchLevitate.BackgroundColor3 = Color3.new(0.886275, 0.776471, 0.368627)
		GlitchLevitate.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		GlitchLevitate.Position = UDim2.new(0, 319, 0, 322)
		GlitchLevitate.Size = UDim2.new(0, 119, 0, 34)
		GlitchLevitate.Font = Enum.Font.Highway
		GlitchLevitate.FontSize = Enum.FontSize.Size24
		GlitchLevitate.Text = "Glitch Levitate"
		GlitchLevitate.TextSize = 20
		GlitchLevitate.TextWrapped = true

		MoonDance.Name = "MoonDance"
		MoonDance.Parent = ScrollingFrame
		MoonDance.BackgroundColor3 = Color3.new(0.886275, 0.776471, 0.368627)
		MoonDance.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		MoonDance.Position = UDim2.new(0, 319, 0, 280)
		MoonDance.Size = UDim2.new(0, 119, 0, 34)
		MoonDance.Font = Enum.Font.Highway
		MoonDance.FontSize = Enum.FontSize.Size24
		MoonDance.Text = "Moon Dance"
		MoonDance.TextSize = 20
		MoonDance.TextWrapped = true

		FullPunch.Name = "FullPunch"
		FullPunch.Parent = ScrollingFrame
		FullPunch.BackgroundColor3 = Color3.new(0.886275, 0.776471, 0.368627)
		FullPunch.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		FullPunch.Position = UDim2.new(0, 17, 0, 280)
		FullPunch.Size = UDim2.new(0, 119, 0, 34)
		FullPunch.Font = Enum.Font.Highway
		FullPunch.FontSize = Enum.FontSize.Size24
		FullPunch.Text = "Full Punch"
		FullPunch.TextSize = 20
		FullPunch.TextWrapped = true

		Crouch.Name = "Crouch"
		Crouch.Parent = ScrollingFrame
		Crouch.BackgroundColor3 = Color3.new(0.886275, 0.776471, 0.368627)
		Crouch.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		Crouch.Position = UDim2.new(0, 168, 0, 280)
		Crouch.Size = UDim2.new(0, 119, 0, 34)
		Crouch.Font = Enum.Font.Highway
		Crouch.FontSize = Enum.FontSize.Size24
		Crouch.Text = "Crouch"
		Crouch.TextSize = 20
		Crouch.TextWrapped = true

		SpinDance.Name = "SpinDance"
		SpinDance.Parent = ScrollingFrame
		SpinDance.BackgroundColor3 = Color3.new(0.886275, 0.776471, 0.368627)
		SpinDance.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		SpinDance.Position = UDim2.new(0, 168, 0, 236)
		SpinDance.Size = UDim2.new(0, 119, 0, 34)
		SpinDance.Font = Enum.Font.Highway
		SpinDance.FontSize = Enum.FontSize.Size24
		SpinDance.Text = "Spin Dance"
		SpinDance.TextSize = 20
		SpinDance.TextWrapped = true

		FloorFaint.Name = "FloorFaint"
		FloorFaint.Parent = ScrollingFrame
		FloorFaint.BackgroundColor3 = Color3.new(0.886275, 0.776471, 0.368627)
		FloorFaint.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		FloorFaint.Position = UDim2.new(0, 17, 0, 236)
		FloorFaint.Size = UDim2.new(0, 119, 0, 34)
		FloorFaint.Font = Enum.Font.Highway
		FloorFaint.FontSize = Enum.FontSize.Size24
		FloorFaint.Text = "Floor Faint"
		FloorFaint.TextSize = 20
		FloorFaint.TextWrapped = true

		JumpingJacks.Name = "JumpingJacks"
		JumpingJacks.Parent = ScrollingFrame
		JumpingJacks.BackgroundColor3 = Color3.new(0.886275, 0.776471, 0.368627)
		JumpingJacks.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		JumpingJacks.Position = UDim2.new(0, 319, 0, 236)
		JumpingJacks.Size = UDim2.new(0, 119, 0, 34)
		JumpingJacks.Font = Enum.Font.Highway
		JumpingJacks.FontSize = Enum.FontSize.Size24
		JumpingJacks.Text = "Jumping Jacks"
		JumpingJacks.TextSize = 20
		JumpingJacks.TextWrapped = true

		Spinner.Name = "Spinner"
		Spinner.Parent = ScrollingFrame
		Spinner.BackgroundColor3 = Color3.new(0.886275, 0.776471, 0.368627)
		Spinner.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		Spinner.Position = UDim2.new(0, 17, 0, 192)
		Spinner.Size = UDim2.new(0, 119, 0, 34)
		Spinner.Font = Enum.Font.Highway
		Spinner.FontSize = Enum.FontSize.Size24
		Spinner.Text = "Spinner"
		Spinner.TextSize = 20
		Spinner.TextWrapped = true

		MegaInsane.Name = "MegaInsane"
		MegaInsane.Parent = ScrollingFrame
		MegaInsane.BackgroundColor3 = Color3.new(0.886275, 0.776471, 0.368627)
		MegaInsane.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		MegaInsane.Position = UDim2.new(0, 168, 0, 192)
		MegaInsane.Size = UDim2.new(0, 119, 0, 34)
		MegaInsane.Font = Enum.Font.Highway
		MegaInsane.FontSize = Enum.FontSize.Size24
		MegaInsane.Text = "Mega Insane"
		MegaInsane.TextSize = 20
		MegaInsane.TextWrapped = true

		ArmDetach.Name = "ArmDetach"
		ArmDetach.Parent = ScrollingFrame
		ArmDetach.BackgroundColor3 = Color3.new(0.886275, 0.776471, 0.368627)
		ArmDetach.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		ArmDetach.Position = UDim2.new(0, 319, 0, 192)
		ArmDetach.Size = UDim2.new(0, 119, 0, 34)
		ArmDetach.Font = Enum.Font.Highway
		ArmDetach.FontSize = Enum.FontSize.Size24
		ArmDetach.Text = "Arm Detach"
		ArmDetach.TextSize = 20
		ArmDetach.TextWrapped = true

		WeirdMove.Name = "WeirdMove"
		WeirdMove.Parent = ScrollingFrame
		WeirdMove.BackgroundColor3 = Color3.new(0.886275, 0.776471, 0.368627)
		WeirdMove.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		WeirdMove.Position = UDim2.new(0, 168, 0, 148)
		WeirdMove.Size = UDim2.new(0, 119, 0, 34)
		WeirdMove.Font = Enum.Font.Highway
		WeirdMove.FontSize = Enum.FontSize.Size24
		WeirdMove.Text = "Weird Move"
		WeirdMove.TextSize = 20
		WeirdMove.TextWrapped = true

		Faint.Name = "Faint"
		Faint.Parent = ScrollingFrame
		Faint.BackgroundColor3 = Color3.new(0.886275, 0.776471, 0.368627)
		Faint.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		Faint.Position = UDim2.new(0, 17, 0, 148)
		Faint.Size = UDim2.new(0, 119, 0, 34)
		Faint.Font = Enum.Font.Highway
		Faint.FontSize = Enum.FontSize.Size24
		Faint.Text = "Faint"
		Faint.TextSize = 20
		Faint.TextWrapped = true

		CloneIllusion.Name = "CloneIllusion"
		CloneIllusion.Parent = ScrollingFrame
		CloneIllusion.BackgroundColor3 = Color3.new(0.886275, 0.776471, 0.368627)
		CloneIllusion.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		CloneIllusion.Position = UDim2.new(0, 319, 0, 148)
		CloneIllusion.Size = UDim2.new(0, 119, 0, 34)
		CloneIllusion.Font = Enum.Font.Highway
		CloneIllusion.FontSize = Enum.FontSize.Size24
		CloneIllusion.Text = "Clone Illusion"
		CloneIllusion.TextSize = 20
		CloneIllusion.TextWrapped = true

		Levitate.Name = "Levitate"
		Levitate.Parent = ScrollingFrame
		Levitate.BackgroundColor3 = Color3.new(0.886275, 0.776471, 0.368627)
		Levitate.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		Levitate.Position = UDim2.new(0, 17, 0, 104)
		Levitate.Size = UDim2.new(0, 119, 0, 34)
		Levitate.Font = Enum.Font.Highway
		Levitate.FontSize = Enum.FontSize.Size24
		Levitate.Text = "Levitate"
		Levitate.TextSize = 20
		Levitate.TextWrapped = true

		DinoWalk.Name = "DinoWalk"
		DinoWalk.Parent = ScrollingFrame
		DinoWalk.BackgroundColor3 = Color3.new(0.886275, 0.776471, 0.368627)
		DinoWalk.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		DinoWalk.Position = UDim2.new(0, 168, 0, 104)
		DinoWalk.Size = UDim2.new(0, 119, 0, 34)
		DinoWalk.Font = Enum.Font.Highway
		DinoWalk.FontSize = Enum.FontSize.Size24
		DinoWalk.Text = "Dino Walk"
		DinoWalk.TextSize = 20
		DinoWalk.TextWrapped = true

		FloorCrawl.Name = "FloorCrawl"
		FloorCrawl.Parent = ScrollingFrame
		FloorCrawl.BackgroundColor3 = Color3.new(0.886275, 0.776471, 0.368627)
		FloorCrawl.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		FloorCrawl.Position = UDim2.new(0, 319, 0, 104)
		FloorCrawl.Size = UDim2.new(0, 119, 0, 34)
		FloorCrawl.Font = Enum.Font.Highway
		FloorCrawl.FontSize = Enum.FontSize.Size24
		FloorCrawl.Text = "Floor Crawl"
		FloorCrawl.TextSize = 20
		FloorCrawl.TextWrapped = true

		SwordSlam.Name = "SwordSlam"
		SwordSlam.Parent = ScrollingFrame
		SwordSlam.BackgroundColor3 = Color3.new(0.886275, 0.776471, 0.368627)
		SwordSlam.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		SwordSlam.Position = UDim2.new(0, 319, 0, 60)
		SwordSlam.Size = UDim2.new(0, 119, 0, 34)
		SwordSlam.Font = Enum.Font.Highway
		SwordSlam.FontSize = Enum.FontSize.Size24
		SwordSlam.Text = "Sword Slam"
		SwordSlam.TextSize = 20
		SwordSlam.TextWrapped = true

		LoopHead.Name = "LoopHead"
		LoopHead.Parent = ScrollingFrame
		LoopHead.BackgroundColor3 = Color3.new(0.886275, 0.776471, 0.368627)
		LoopHead.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		LoopHead.Position = UDim2.new(0, 168, 0, 60)
		LoopHead.Size = UDim2.new(0, 119, 0, 34)
		LoopHead.Font = Enum.Font.Highway
		LoopHead.FontSize = Enum.FontSize.Size24
		LoopHead.Text = "Loop Head"
		LoopHead.TextSize = 20
		LoopHead.TextWrapped = true

		HeroJump.Name = "HeroJump"
		HeroJump.Parent = ScrollingFrame
		HeroJump.BackgroundColor3 = Color3.new(0.886275, 0.776471, 0.368627)
		HeroJump.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		HeroJump.Position = UDim2.new(0, 17, 0, 60)
		HeroJump.Size = UDim2.new(0, 119, 0, 34)
		HeroJump.Font = Enum.Font.Highway
		HeroJump.FontSize = Enum.FontSize.Size24
		HeroJump.Text = "Hero Jump"
		HeroJump.TextSize = 20
		HeroJump.TextWrapped = true

		Insane.Name = "Insane"
		Insane.Parent = ScrollingFrame
		Insane.BackgroundColor3 = Color3.new(0.886275, 0.776471, 0.368627)
		Insane.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		Insane.Position = UDim2.new(0, 319, 0, 16)
		Insane.Size = UDim2.new(0, 119, 0, 34)
		Insane.Font = Enum.Font.Highway
		Insane.FontSize = Enum.FontSize.Size24
		Insane.Text = "Insane"
		Insane.TextSize = 20
		Insane.TextWrapped = true

		FloatingHead.Name = "FloatingHead"
		FloatingHead.Parent = ScrollingFrame
		FloatingHead.BackgroundColor3 = Color3.new(0.886275, 0.776471, 0.368627)
		FloatingHead.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		FloatingHead.Position = UDim2.new(0, 168, 0, 16)
		FloatingHead.Size = UDim2.new(0, 119, 0, 34)
		FloatingHead.Font = Enum.Font.Highway
		FloatingHead.FontSize = Enum.FontSize.Size24
		FloatingHead.Text = "Floating Head"
		FloatingHead.TextSize = 20
		FloatingHead.TextWrapped = true

		HeadThrow.Name = "HeadThrow"
		HeadThrow.Parent = ScrollingFrame
		HeadThrow.BackgroundColor3 = Color3.new(0.886275, 0.776471, 0.368627)
		HeadThrow.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		HeadThrow.Position = UDim2.new(0, 17, 0, 16)
		HeadThrow.Size = UDim2.new(0, 119, 0, 34)
		HeadThrow.Font = Enum.Font.Highway
		HeadThrow.FontSize = Enum.FontSize.Size24
		HeadThrow.Text = "Head Throw"
		HeadThrow.TextSize = 20
		HeadThrow.TextWrapped = true

		MovingDance.Name = "MovingDance"
		MovingDance.Parent = ScrollingFrame
		MovingDance.BackgroundColor3 = Color3.new(0.886275, 0.776471, 0.368627)
		MovingDance.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		MovingDance.Position = UDim2.new(0, 168, 0, 324)
		MovingDance.Size = UDim2.new(0, 119, 0, 34)
		MovingDance.Font = Enum.Font.Highway
		MovingDance.FontSize = Enum.FontSize.Size24
		MovingDance.Text = "Moving Dance"
		MovingDance.TextSize = 20
		MovingDance.TextWrapped = true

		SuperPunch.Name = "SuperPunch"
		SuperPunch.Parent = ScrollingFrame
		SuperPunch.BackgroundColor3 = Color3.new(0.886275, 0.776471, 0.368627)
		SuperPunch.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		SuperPunch.Position = UDim2.new(0, 168, 0, 366)
		SuperPunch.Size = UDim2.new(0, 119, 0, 34)
		SuperPunch.Font = Enum.Font.Highway
		SuperPunch.FontSize = Enum.FontSize.Size24
		SuperPunch.Text = "Super Punch"
		SuperPunch.TextSize = 20
		SuperPunch.TextWrapped = true

		ArmTurbine.Name = "ArmTurbine"
		ArmTurbine.Parent = ScrollingFrame
		ArmTurbine.BackgroundColor3 = Color3.new(0.886275, 0.776471, 0.368627)
		ArmTurbine.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		ArmTurbine.Position = UDim2.new(0, 319, 0, 366)
		ArmTurbine.Size = UDim2.new(0, 119, 0, 34)
		ArmTurbine.Font = Enum.Font.Highway
		ArmTurbine.FontSize = Enum.FontSize.Size24
		ArmTurbine.Text = "Arm Turbine"
		ArmTurbine.TextSize = 20
		ArmTurbine.TextWrapped = true

		Dab.Name = "Dab"
		Dab.Parent = ScrollingFrame
		Dab.BackgroundColor3 = Color3.new(0.886275, 0.776471, 0.368627)
		Dab.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		Dab.Position = UDim2.new(0, 17, 0, 366)
		Dab.Size = UDim2.new(0, 119, 0, 34)
		Dab.Font = Enum.Font.Highway
		Dab.FontSize = Enum.FontSize.Size24
		Dab.Text = "Dab"
		Dab.TextSize = 20
		Dab.TextWrapped = true

		FloatSit.Name = "FloatSit"
		FloatSit.Parent = ScrollingFrame
		FloatSit.BackgroundColor3 = Color3.new(0.886275, 0.776471, 0.368627)
		FloatSit.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		FloatSit.Position = UDim2.new(0, 168, 0, 410)
		FloatSit.Size = UDim2.new(0, 119, 0, 34)
		FloatSit.Font = Enum.Font.Highway
		FloatSit.FontSize = Enum.FontSize.Size24
		FloatSit.Text = "Float Sit"
		FloatSit.TextSize = 20
		FloatSit.TextWrapped = true

		SuperFaint.Name = "SuperFaint"
		SuperFaint.Parent = ScrollingFrame
		SuperFaint.BackgroundColor3 = Color3.new(0.886275, 0.776471, 0.368627)
		SuperFaint.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		SuperFaint.Position = UDim2.new(0, 17, 0, 498)
		SuperFaint.Size = UDim2.new(0, 119, 0, 34)
		SuperFaint.Font = Enum.Font.Highway
		SuperFaint.FontSize = Enum.FontSize.Size24
		SuperFaint.Text = "Super Faint"
		SuperFaint.TextSize = 20
		SuperFaint.TextWrapped = true

		BarrelRoll.Name = "BarrelRoll"
		BarrelRoll.Parent = ScrollingFrame
		BarrelRoll.BackgroundColor3 = Color3.new(0.886275, 0.776471, 0.368627)
		BarrelRoll.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		BarrelRoll.Position = UDim2.new(0, 319, 0, 410)
		BarrelRoll.Size = UDim2.new(0, 119, 0, 34)
		BarrelRoll.Font = Enum.Font.Highway
		BarrelRoll.FontSize = Enum.FontSize.Size24
		BarrelRoll.Text = "Barrel Roll"
		BarrelRoll.TextSize = 20
		BarrelRoll.TextWrapped = true

		Scared.Name = "Scared"
		Scared.Parent = ScrollingFrame
		Scared.BackgroundColor3 = Color3.new(0.886275, 0.776471, 0.368627)
		Scared.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		Scared.Position = UDim2.new(0, 319, 0, 454)
		Scared.Size = UDim2.new(0, 119, 0, 34)
		Scared.Font = Enum.Font.Highway
		Scared.FontSize = Enum.FontSize.Size24
		Scared.Text = "Scared"
		Scared.TextSize = 20
		Scared.TextWrapped = true

		InsaneArms.Name = "InsaneArms"
		InsaneArms.Parent = ScrollingFrame
		InsaneArms.BackgroundColor3 = Color3.new(0.886275, 0.776471, 0.368627)
		InsaneArms.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		InsaneArms.Position = UDim2.new(0, 17, 0, 454)
		InsaneArms.Size = UDim2.new(0, 119, 0, 34)
		InsaneArms.Font = Enum.Font.Highway
		InsaneArms.FontSize = Enum.FontSize.Size24
		InsaneArms.Text = "Insane Arms"
		InsaneArms.TextSize = 20
		InsaneArms.TextWrapped = true

		SwordSlice.Name = "SwordSlice"
		SwordSlice.Parent = ScrollingFrame
		SwordSlice.BackgroundColor3 = Color3.new(0.886275, 0.776471, 0.368627)
		SwordSlice.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		SwordSlice.Position = UDim2.new(0, 168, 0, 454)
		SwordSlice.Size = UDim2.new(0, 119, 0, 34)
		SwordSlice.Font = Enum.Font.Highway
		SwordSlice.FontSize = Enum.FontSize.Size24
		SwordSlice.Text = "Sword Slice"
		SwordSlice.TextSize = 20
		SwordSlice.TextWrapped = true

		SpinDance2.Name = "SpinDance2"
		SpinDance2.Parent = ScrollingFrame
		SpinDance2.BackgroundColor3 = Color3.new(0.886275, 0.776471, 0.368627)
		SpinDance2.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		SpinDance2.Position = UDim2.new(0, 168, 0, 498)
		SpinDance2.Size = UDim2.new(0, 119, 0, 34)
		SpinDance2.Font = Enum.Font.Highway
		SpinDance2.FontSize = Enum.FontSize.Size24
		SpinDance2.Text = "Spin Dance 2"
		SpinDance2.TextSize = 20
		SpinDance2.TextWrapped = true

		BowDown.Name = "BowDown"
		BowDown.Parent = ScrollingFrame
		BowDown.BackgroundColor3 = Color3.new(0.886275, 0.776471, 0.368627)
		BowDown.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		BowDown.Position = UDim2.new(0, 319, 0, 498)
		BowDown.Size = UDim2.new(0, 119, 0, 34)
		BowDown.Font = Enum.Font.Highway
		BowDown.FontSize = Enum.FontSize.Size24
		BowDown.Text = "Bow Down"
		BowDown.TextSize = 20
		BowDown.TextWrapped = true

		LoopSlam.Name = "LoopSlam"
		LoopSlam.Parent = ScrollingFrame
		LoopSlam.BackgroundColor3 = Color3.new(0.886275, 0.776471, 0.368627)
		LoopSlam.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		LoopSlam.Position = UDim2.new(0, 17, 0, 410)
		LoopSlam.Size = UDim2.new(0, 119, 0, 34)
		LoopSlam.Font = Enum.Font.Highway
		LoopSlam.FontSize = Enum.FontSize.Size24
		LoopSlam.Text = "Loop Slam"
		LoopSlam.TextSize = 20
		LoopSlam.TextWrapped = true

		GuiTopFrame.Name = "Gui TopFrame"
		GuiTopFrame.Parent = MainFrame
		GuiTopFrame.BackgroundColor3 = Color3.new(1, 0.329412, 0.329412)
		GuiTopFrame.BorderColor3 = Color3.new(0.243137, 0.243137, 0.243137)
		GuiTopFrame.Size = UDim2.new(0, 460, 0, 32)

		CloseGUI.Name = "CloseGUI"
		CloseGUI.Parent = GuiTopFrame
		CloseGUI.BackgroundColor3 = Color3.new(1, 1, 1)
		CloseGUI.BackgroundTransparency = 1
		CloseGUI.Position = UDim2.new(0, 426, 0, 0)
		CloseGUI.Size = UDim2.new(0, 34, 0, 32)
		CloseGUI.Font = Enum.Font.SourceSans
		CloseGUI.FontSize = Enum.FontSize.Size48
		CloseGUI.Text = "X"
		CloseGUI.TextColor3 = Color3.new(0.333333, 0, 0)
		CloseGUI.TextSize = 40
		CloseGUI.TextWrapped = true

		Title.Name = "Title"
		Title.Parent = GuiTopFrame
		Title.BackgroundColor3 = Color3.new(1, 1, 1)
		Title.BackgroundTransparency = 1
		Title.Size = UDim2.new(0, 460, 0, 32)
		Title.FontSize = Enum.FontSize.Size14
		Title.Text = "Energize"
		Title.TextColor3 = Color3.new(0.164706, 0.164706, 0.164706)
		Title.TextSize = 14
		Title.TextStrokeColor3 = Color3.new(0.384314, 0.917647, 1)
		Title.TextStrokeTransparency = 0.69999998807907
		Title.TextWrapped = true

		CheckR.Name = "CheckR"
		CheckR.Parent = GuiTopFrame
		CheckR.BackgroundColor3 = Color3.new(1, 1, 1)
		CheckR.BackgroundTransparency = 1
		CheckR.Size = UDim2.new(0, 171, 0, 32)
		CheckR.Font = Enum.Font.SourceSansBold
		CheckR.FontSize = Enum.FontSize.Size14
		CheckR.Text = "Text"
		CheckR.TextScaled = true
		CheckR.TextSize = 14
		CheckR.TextWrapped = true

		ScrollingFrameR15.Name = "ScrollingFrameR15"
		ScrollingFrameR15.Parent = MainFrame
		ScrollingFrameR15.BackgroundColor3 = Color3.new(1, 0.564706, 0.564706)
		ScrollingFrameR15.Position = UDim2.new(0, 0, 0, 32)
		ScrollingFrameR15.Size = UDim2.new(0, 460, 0, 215)
		ScrollingFrameR15.Visible = false
		ScrollingFrameR15.ScrollBarThickness = 13

		CrazySlash.Name = "CrazySlash"
		CrazySlash.Parent = ScrollingFrameR15
		CrazySlash.BackgroundColor3 = Color3.new(0.682353, 0.701961, 0.792157)
		CrazySlash.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		CrazySlash.Position = UDim2.new(0, 17, 0, 16)
		CrazySlash.Size = UDim2.new(0, 119, 0, 34)
		CrazySlash.Font = Enum.Font.Highway
		CrazySlash.FontSize = Enum.FontSize.Size24
		CrazySlash.Text = "CrazySlash"
		CrazySlash.TextSize = 20
		CrazySlash.TextWrapped = true

		Open.Name = "Open"
		Open.Parent = ScrollingFrameR15
		Open.BackgroundColor3 = Color3.new(0.682353, 0.701961, 0.792157)
		Open.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		Open.Position = UDim2.new(0, 168, 0, 16)
		Open.Size = UDim2.new(0, 119, 0, 34)
		Open.Font = Enum.Font.Highway
		Open.FontSize = Enum.FontSize.Size24
		Open.Text = "Open"
		Open.TextSize = 20
		Open.TextWrapped = true

		R15Spinner.Name = "R15Spinner"
		R15Spinner.Parent = ScrollingFrameR15
		R15Spinner.BackgroundColor3 = Color3.new(0.682353, 0.701961, 0.792157)
		R15Spinner.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		R15Spinner.Position = UDim2.new(0, 17, 0, 60)
		R15Spinner.Size = UDim2.new(0, 119, 0, 34)
		R15Spinner.Font = Enum.Font.Highway
		R15Spinner.FontSize = Enum.FontSize.Size24
		R15Spinner.Text = "Spinner"
		R15Spinner.TextSize = 20
		R15Spinner.TextWrapped = true

		ArmsOut.Name = "ArmsOut"
		ArmsOut.Parent = ScrollingFrameR15
		ArmsOut.BackgroundColor3 = Color3.new(0.682353, 0.701961, 0.792157)
		ArmsOut.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		ArmsOut.Position = UDim2.new(0, 319, 0, 16)
		ArmsOut.Size = UDim2.new(0, 119, 0, 34)
		ArmsOut.Font = Enum.Font.Highway
		ArmsOut.FontSize = Enum.FontSize.Size24
		ArmsOut.Text = "ArmsOut"
		ArmsOut.TextSize = 20
		ArmsOut.TextWrapped = true

		FloatSlash.Name = "FloatSlash"
		FloatSlash.Parent = ScrollingFrameR15
		FloatSlash.BackgroundColor3 = Color3.new(0.682353, 0.701961, 0.792157)
		FloatSlash.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		FloatSlash.Position = UDim2.new(0, 168, 0, 148)
		FloatSlash.Size = UDim2.new(0, 119, 0, 34)
		FloatSlash.Font = Enum.Font.Highway
		FloatSlash.FontSize = Enum.FontSize.Size24
		FloatSlash.Text = "FloatSlash"
		FloatSlash.TextSize = 20
		FloatSlash.TextWrapped = true

		WeirdZombie.Name = "WeirdZombie"
		WeirdZombie.Parent = ScrollingFrameR15
		WeirdZombie.BackgroundColor3 = Color3.new(0.682353, 0.701961, 0.792157)
		WeirdZombie.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		WeirdZombie.Position = UDim2.new(0, 17, 0, 148)
		WeirdZombie.Size = UDim2.new(0, 119, 0, 34)
		WeirdZombie.Font = Enum.Font.Highway
		WeirdZombie.FontSize = Enum.FontSize.Size24
		WeirdZombie.Text = "WeirdZombie"
		WeirdZombie.TextSize = 20
		WeirdZombie.TextWrapped = true

		DownSlash.Name = "DownSlash"
		DownSlash.Parent = ScrollingFrameR15
		DownSlash.BackgroundColor3 = Color3.new(0.682353, 0.701961, 0.792157)
		DownSlash.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		DownSlash.Position = UDim2.new(0, 319, 0, 148)
		DownSlash.Size = UDim2.new(0, 119, 0, 34)
		DownSlash.Font = Enum.Font.Highway
		DownSlash.FontSize = Enum.FontSize.Size24
		DownSlash.Text = "DownSlash"
		DownSlash.TextSize = 20
		DownSlash.TextWrapped = true

		Pull.Name = "Pull"
		Pull.Parent = ScrollingFrameR15
		Pull.BackgroundColor3 = Color3.new(0.682353, 0.701961, 0.792157)
		Pull.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		Pull.Position = UDim2.new(0, 17, 0, 104)
		Pull.Size = UDim2.new(0, 119, 0, 34)
		Pull.Font = Enum.Font.Highway
		Pull.FontSize = Enum.FontSize.Size24
		Pull.Text = "Pull"
		Pull.TextSize = 20
		Pull.TextWrapped = true

		CircleArm.Name = "CircleArm"
		CircleArm.Parent = ScrollingFrameR15
		CircleArm.BackgroundColor3 = Color3.new(0.682353, 0.701961, 0.792157)
		CircleArm.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		CircleArm.Position = UDim2.new(0, 168, 0, 104)
		CircleArm.Size = UDim2.new(0, 119, 0, 34)
		CircleArm.Font = Enum.Font.Highway
		CircleArm.FontSize = Enum.FontSize.Size24
		CircleArm.Text = "CircleArm"
		CircleArm.TextSize = 20
		CircleArm.TextWrapped = true

		Bend.Name = "Bend"
		Bend.Parent = ScrollingFrameR15
		Bend.BackgroundColor3 = Color3.new(0.682353, 0.701961, 0.792157)
		Bend.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		Bend.Position = UDim2.new(0, 319, 0, 104)
		Bend.Size = UDim2.new(0, 119, 0, 34)
		Bend.Font = Enum.Font.Highway
		Bend.FontSize = Enum.FontSize.Size24
		Bend.Text = "Bend"
		Bend.TextSize = 20
		Bend.TextWrapped = true

		RotateSlash.Name = "RotateSlash"
		RotateSlash.Parent = ScrollingFrameR15
		RotateSlash.BackgroundColor3 = Color3.new(0.682353, 0.701961, 0.792157)
		RotateSlash.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		RotateSlash.Position = UDim2.new(0, 319, 0, 60)
		RotateSlash.Size = UDim2.new(0, 119, 0, 34)
		RotateSlash.Font = Enum.Font.Highway
		RotateSlash.FontSize = Enum.FontSize.Size24
		RotateSlash.Text = "RotateSlash"
		RotateSlash.TextSize = 20
		RotateSlash.TextWrapped = true

		FlingArms.Name = "FlingArms"
		FlingArms.Parent = ScrollingFrameR15
		FlingArms.BackgroundColor3 = Color3.new(0.682353, 0.701961, 0.792157)
		FlingArms.BorderColor3 = Color3.new(0.313726, 0.313726, 0.313726)
		FlingArms.Position = UDim2.new(0, 168, 0, 60)
		FlingArms.Size = UDim2.new(0, 119, 0, 34)
		FlingArms.Font = Enum.Font.Highway
		FlingArms.FontSize = Enum.FontSize.Size24
		FlingArms.Text = "FlingArms"
		FlingArms.TextSize = 20
		FlingArms.TextWrapped = true

		-- Buttons
		col = Color3.new(0.886275, 0.776471, 0.368627)
		loc = Color3.new(1, 0.906471, 0.568627)
		rcol = Color3.new(0.682353, 0.701961, 0.792157)
		rloc = Color3.new(0.882353, 0.901961, 0.992157)

		CloseGUI.MouseButton1Click:connect(function()
			MainFrame.Visible = false
			SideFrame.Visible = true
			SideFrame.Position = MainFrame.Position
		end)

		OpenGUI.MouseButton1Click:connect(function()
			MainFrame.Visible = true
			SideFrame.Visible = false
			MainFrame.Position = SideFrame.Position
		end)

		if (game:GetService"Players".LocalPlayer.Character:WaitForChild("Humanoid").RigType == Enum.HumanoidRigType.R15) then
			ScrollingFrame.Visible = false
			ScrollingFrameR15.Visible = true
			CheckR.Text = "Showing R15 Animations"
		else
			ScrollingFrame.Visible = true
			ScrollingFrameR15.Visible = false
			CheckR.Text = "Showing R6 Animations"
		end

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://35154961"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		local HeadThrowACTIVE = false
		HeadThrow.MouseButton1Click:connect(function()
			HeadThrowACTIVE = not HeadThrowACTIVE
			if HeadThrowACTIVE then
				HeadThrow.BackgroundColor3 = loc
				while wait() do
					if track.IsPlaying == false then
						if HeadThrowACTIVE then
							track:Play(.1, 1, 1)
						end
					end
				end
			else
				track:Stop()
				HeadThrow.BackgroundColor3 = col
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://121572214"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		local FloatingHeadACTIVE = false
		FloatingHead.MouseButton1Click:connect(function()
			FloatingHeadACTIVE = not FloatingHeadACTIVE
			if FloatingHeadACTIVE then
				track:Play(.1, 1, 1)
				FloatingHead.BackgroundColor3 = loc
			else
				track:Stop()
				FloatingHead.BackgroundColor3 = col
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://182724289"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		local CrouchACTIVE = false
		Crouch.MouseButton1Click:connect(function()
			CrouchACTIVE = not CrouchACTIVE
			if CrouchACTIVE then
				track:Play(.1, 1, 1)
				Crouch.BackgroundColor3 = loc
			else
				track:Stop()
				Crouch.BackgroundColor3 = col
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://282574440"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		local FloorCrawlACTIVE = false
		FloorCrawl.MouseButton1Click:connect(function()
			FloorCrawlACTIVE = not FloorCrawlACTIVE
			if FloorCrawlACTIVE then
				track:Play(.1, 1, 1)
				FloorCrawl.BackgroundColor3 = loc
			else
				track:Stop()
				FloorCrawl.BackgroundColor3 = col
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://204328711"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		local DinoWalkACTIVE = false
		DinoWalk.MouseButton1Click:connect(function()
			DinoWalkACTIVE = not DinoWalkACTIVE
			if DinoWalkACTIVE then
				track:Play(.1, 1, 1)
				DinoWalk.BackgroundColor3 = loc
			else
				track:Stop()
				DinoWalk.BackgroundColor3 = col
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://429681631"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		local JumpingJacksACTIVE = false
		JumpingJacks.MouseButton1Click:connect(function()
			JumpingJacksACTIVE = not JumpingJacksACTIVE
			if JumpingJacksACTIVE then
				track:Play(.1, 1, 1)
				JumpingJacks.BackgroundColor3 = loc
			else
				track:Stop()
				JumpingJacks.BackgroundColor3 = col
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://35154961"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		local LoopHeadACTIVE = false
		LoopHead.MouseButton1Click:connect(function()
			LoopHeadACTIVE = not LoopHeadACTIVE
			if LoopHeadACTIVE then
				LoopHead.BackgroundColor3 = loc
				while wait() do
					if track.IsPlaying == false then
						if LoopHeadACTIVE then
							track:Play(.5, 1, 1e6)
						end
					end
				end
			else
				track:Stop()
				LoopHead.BackgroundColor3 = col
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://184574340"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		local HeroJumpACTIVE = false
		HeroJump.MouseButton1Click:connect(function()
			HeroJumpACTIVE = not HeroJumpACTIVE
			if HeroJumpACTIVE then
				HeroJump.BackgroundColor3 = loc
				while wait() do
					if track.IsPlaying == false then
						if HeroJumpACTIVE then
							track:Play(.1, 1, 1)
						end
					end
				end
			else
				track:Stop()
				HeroJump.BackgroundColor3 = col
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://181526230"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		local FaintACTIVE = false
		Faint.MouseButton1Click:connect(function()
			FaintACTIVE = not FaintACTIVE
			if FaintACTIVE then
				track:Play(.1, 1, 1)
				Faint.BackgroundColor3 = loc
			else
				track:Stop()
				Faint.BackgroundColor3 = col
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://181525546"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		local FloorFaintACTIVE = false
		FloorFaint.MouseButton1Click:connect(function()
			FloorFaintACTIVE = not FloorFaintACTIVE
			if FloorFaintACTIVE then
				FloorFaint.BackgroundColor3 = loc
				while wait() do
					if track.IsPlaying == false then
						if FloorFaintACTIVE then
							track:Play(.1, 1, 2)
						end
					end
				end
			else
				track:Stop()
				FloorFaint.BackgroundColor3 = col
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://181525546"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		local SuperFaintACTIVE = false
		SuperFaint.MouseButton1Click:connect(function()
			SuperFaintACTIVE = not SuperFaintACTIVE
			if SuperFaintACTIVE then
				SuperFaint.BackgroundColor3 = loc
				while wait() do
					if track.IsPlaying == false then
						if SuperFaintACTIVE then
							track:Play(.1, 0.5, 40)
						end
					end
				end
			else
				track:Stop()
				SuperFaint.BackgroundColor3 = col
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://313762630"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		local LevitateACTIVE = false
		Levitate.MouseButton1Click:connect(function()
			LevitateACTIVE = not LevitateACTIVE
			if LevitateACTIVE then
				track:Play(.1, 1, 1)
				Levitate.BackgroundColor3 = loc
			else
				track:Stop()
				Levitate.BackgroundColor3 = col
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://183412246"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		local DabACTIVE = false
		Dab.MouseButton1Click:connect(function()
			DabACTIVE = not DabACTIVE
			if DabACTIVE then
				Dab.BackgroundColor3 = loc
				while wait() do
					if track.IsPlaying == false then
						if DabACTIVE then
							track:Play(.1, 1, 1)
						end
					end
				end
			else
				track:Stop()
				Dab.BackgroundColor3 = col
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://188632011"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		local SpinACTIVE = false
		Spinner.MouseButton1Click:connect(function()
			SpinACTIVE = not SpinACTIVE
			if SpinACTIVE then
				Spinner.BackgroundColor3 = loc
				while wait() do
					if track.IsPlaying == false then
						if SpinACTIVE then
							track:Play(.1, 1, 2)
						end
					end
				end
			else
				track:Stop()
				Spinner.BackgroundColor3 = col
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://179224234"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		local FloatSitACTIVE = false
		FloatSit.MouseButton1Click:connect(function()
			FloatSitACTIVE = not FloatSitACTIVE
			if FloatSitACTIVE then
				track:Play(.1, 1, 1)
				FloatSit.BackgroundColor3 = loc
			else
				track:Stop()
				FloatSit.BackgroundColor3 = col
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://429703734"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		local MovingDanceACTIVE = false
		MovingDance.MouseButton1Click:connect(function()
			MovingDanceACTIVE = not MovingDanceACTIVE
			if MovingDanceACTIVE then
				MovingDance.BackgroundColor3 = loc
				while wait() do
					if track.IsPlaying == false then
						if MovingDanceACTIVE then
							track:Play(.1, 1, 1)
						end
					end
				end
			else
				track:Stop()
				MovingDance.BackgroundColor3 = col
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://215384594"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		local WeirdMoveACTIVE = false
		WeirdMove.MouseButton1Click:connect(function()
			WeirdMoveACTIVE = not WeirdMoveACTIVE
			if WeirdMoveACTIVE then
				track:Play(.1, 1, 1)
				WeirdMove.BackgroundColor3 = loc
			else
				track:Stop()
				WeirdMove.BackgroundColor3 = col
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://215384594"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		local CloneIllusionACTIVE = false
		CloneIllusion.MouseButton1Click:connect(function()
			CloneIllusionACTIVE = not CloneIllusionACTIVE
			if CloneIllusionACTIVE then
				track:Play(.5, 1, 1e7)
				CloneIllusion.BackgroundColor3 = loc
			else
				track:Stop()
				CloneIllusion.BackgroundColor3 = col
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://313762630"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		local GlitchLevitateACTIVE = false
		GlitchLevitate.MouseButton1Click:connect(function()
			GlitchLevitateACTIVE = not GlitchLevitateACTIVE
			if GlitchLevitateACTIVE then
				track:Play(.5, 1, 1e7)
				GlitchLevitate.BackgroundColor3 = loc
			else
				track:Stop()
				GlitchLevitate.BackgroundColor3 = col
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://429730430"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		local SpinDanceACTIVE = false
		SpinDance.MouseButton1Click:connect(function()
			SpinDanceACTIVE = not SpinDanceACTIVE
			if SpinDanceACTIVE then
				SpinDance.BackgroundColor3 = loc
				while wait() do
					if track.IsPlaying == false then
						if SpinDanceACTIVE then
							track:Play(.1, 1, 1)
						end
					end
				end
			else
				track:Stop()
				SpinDance.BackgroundColor3 = col
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://45834924"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		local MoonDanceACTIVE = false
		MoonDance.MouseButton1Click:connect(function()
			MoonDanceACTIVE = not MoonDanceACTIVE
			if MoonDanceACTIVE then
				MoonDance.BackgroundColor3 = loc
				while wait() do
					if track.IsPlaying == false then
						if MoonDanceACTIVE then
							track:Play(.1, 1, 1)
						end
					end
				end
			else
				track:Stop()
				MoonDance.BackgroundColor3 = col
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://204062532"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		local FullPunchACTIVE = false
		FullPunch.MouseButton1Click:connect(function()
			FullPunchACTIVE = not FullPunchACTIVE
			if FullPunchACTIVE then
				FullPunch.BackgroundColor3 = loc
				while wait() do
					if track.IsPlaying == false then
						if FullPunchACTIVE then
							track:Play(.1, 1, 1)
						end
					end
				end
			else
				track:Stop()
				FullPunch.BackgroundColor3 = col
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://186934910"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		local SpinDance2ACTIVE = false
		SpinDance2.MouseButton1Click:connect(function()
			SpinDance2ACTIVE = not SpinDance2ACTIVE
			if SpinDance2ACTIVE then
				SpinDance2.BackgroundColor3 = loc
				while wait() do
					if track.IsPlaying == false then
						if SpinDance2ACTIVE then
							track:Play(.1, 1, 1)
						end
					end
				end
			else
				track:Stop()
				SpinDance2.BackgroundColor3 = col
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://204292303"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		local BowDownACTIVE = false
		BowDown.MouseButton1Click:connect(function()
			BowDownACTIVE = not BowDownACTIVE
			if BowDownACTIVE then
				BowDown.BackgroundColor3 = loc
				while wait() do
					if track.IsPlaying == false then
						if BowDownACTIVE then
							track:Play(.1, 1, 3)
						end
					end
				end
			else
				track:Stop()
				BowDown.BackgroundColor3 = col
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://204295235"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		local SwordSlamACTIVE = false
		SwordSlam.MouseButton1Click:connect(function()
			SwordSlamACTIVE = not SwordSlamACTIVE
			if SwordSlamACTIVE then
				SwordSlam.BackgroundColor3 = loc
				while wait() do
					if track.IsPlaying == false then
						if SwordSlamACTIVE then
							track:Play(.1, 1, 1)
						end
					end
				end
			else
				track:Stop()
				SwordSlam.BackgroundColor3 = col
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://204295235"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		local LoopSlamACTIVE = false
		LoopSlam.MouseButton1Click:connect(function()
			LoopSlamACTIVE = not LoopSlamACTIVE
			if LoopSlamACTIVE then
				LoopSlam.BackgroundColor3 = loc
				while wait() do
					if track.IsPlaying == false then
						if LoopSlamACTIVE then
							track:Play(.1, 1, 1e4)
						end
					end
				end
			else
				track:Stop()
				LoopSlam.BackgroundColor3 = col
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://184574340"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		local MegaInsaneACTIVE = false
		MegaInsane.MouseButton1Click:connect(function()
			MegaInsaneACTIVE = not MegaInsaneACTIVE
			if MegaInsaneACTIVE then
				MegaInsane.BackgroundColor3 = loc
				while wait() do
					if track.IsPlaying == false then
						if MegaInsaneACTIVE then
							track:Play(.1, 0.5, 40)
						end
					end
				end
			else
				track:Stop()
				MegaInsane.BackgroundColor3 = col
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://126753849"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		local SuperPunchACTIVE = false
		SuperPunch.MouseButton1Click:connect(function()
			SuperPunchACTIVE = not SuperPunchACTIVE
			if SuperPunchACTIVE then
				SuperPunch.BackgroundColor3 = loc
				while wait() do
					if track.IsPlaying == false then
						if SuperPunchACTIVE then
							track:Play(.1, 1, 3)
						end
					end
				end
			else
				track:Stop()
				SuperPunch.BackgroundColor3 = col
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://218504594"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		local FullSwingACTIVE = false
		FullSwing.MouseButton1Click:connect(function()
			FullSwingACTIVE = not FullSwingACTIVE
			if FullSwingACTIVE then
				FullSwing.BackgroundColor3 = loc
				while wait() do
					if track.IsPlaying == false then
						if FullSwingACTIVE then
							track:Play(.1, 1, 1)
						end
					end
				end
			else
				track:Stop()
				FullSwing.BackgroundColor3 = col
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://259438880"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		local ArmTurbineACTIVE = false
		ArmTurbine.MouseButton1Click:connect(function()
			ArmTurbineACTIVE = not ArmTurbineACTIVE
			if ArmTurbineACTIVE then
				track:Play(.1, 1, 1e3)
				ArmTurbine.BackgroundColor3 = loc
			else
				track:Stop()
				ArmTurbine.BackgroundColor3 = col
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://136801964"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		local BarrelRollACTIVE = false
		BarrelRoll.MouseButton1Click:connect(function()
			BarrelRollACTIVE = not BarrelRollACTIVE
			if BarrelRollACTIVE then
				BarrelRoll.BackgroundColor3 = loc
				while wait() do
					if track.IsPlaying == false then
						if BarrelRollACTIVE then
							track:Play(.1, 1, 1)
						end
					end
				end
			else
				track:Stop()
				BarrelRoll.BackgroundColor3 = col
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://180612465"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		local ScaredACTIVE = false
		Scared.MouseButton1Click:connect(function()
			ScaredACTIVE = not ScaredACTIVE
			if ScaredACTIVE then
				Scared.BackgroundColor3 = loc
				while wait() do
					if track.IsPlaying == false then
						if ScaredACTIVE then
							track:Play(.1, 1, 1)
						end
					end
				end
			else
				track:Stop()
				Scared.BackgroundColor3 = col
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://33796059"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		local InsaneACTIVE = false
		Insane.MouseButton1Click:connect(function()
			InsaneACTIVE = not InsaneACTIVE
			if InsaneACTIVE then
				track:Play(.1, 1, 1e8)
				Insane.BackgroundColor3 = loc
			else
				track:Stop()
				Insane.BackgroundColor3 = col
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://33169583"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		local ArmDetachACTIVE = false
		ArmDetach.MouseButton1Click:connect(function()
			ArmDetachACTIVE = not ArmDetachACTIVE
			if ArmDetachACTIVE then
				ArmDetach.BackgroundColor3 = loc
				while wait() do
					if track.IsPlaying == false then
						if ArmDetachACTIVE then
							track:Play(.1, 1, 1e6)
						end
					end
				end
			else
				track:Stop()
				ArmDetach.BackgroundColor3 = col
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://35978879"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		local SwordSliceACTIVE = false
		SwordSlice.MouseButton1Click:connect(function()
			SwordSliceACTIVE = not SwordSliceACTIVE
			if SwordSliceACTIVE then
				track:Play(.1, 1, 1)
				SwordSlice.BackgroundColor3 = loc
			else
				track:Stop()
				SwordSlice.BackgroundColor3 = col
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://27432691"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		local InsaneArmsACTIVE = false
		InsaneArms.MouseButton1Click:connect(function()
			InsaneArmsACTIVE = not InsaneArmsACTIVE
			if InsaneArmsACTIVE then
				InsaneArms.BackgroundColor3 = loc
				while wait() do
					if track.IsPlaying == false then
						if InsaneArmsACTIVE then
							track:Play(.1, 1, 1e4)
						end
					end
				end
			else
				track:Stop()
				InsaneArms.BackgroundColor3 = col
			end
		end)
		-- R15
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://674871189"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		local CrazySlashACTIVE = false
		CrazySlash.MouseButton1Click:connect(function()
			CrazySlashACTIVE = not CrazySlashACTIVE
			if CrazySlashACTIVE then
				CrazySlash.BackgroundColor3 = rloc
				while wait() do
					if track.IsPlaying == false then
						if CrazySlashACTIVE then
							track:Play(.1, 1, 1)
						end
					end
				end
			else
				track:Stop()
				CrazySlash.BackgroundColor3 = rcol
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://582855105"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		local OpenACTIVE = false
		Open.MouseButton1Click:connect(function()
			OpenACTIVE = not OpenACTIVE
			if OpenACTIVE then
				Open.BackgroundColor3 = rloc
				while wait() do
					if track.IsPlaying == false then
						if OpenACTIVE then
							track:Play(.1, 1, 1)
						end
					end
				end
			else
				track:Stop()
				Open.BackgroundColor3 = rcol
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://754658275"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		local R15SpinnerACTIVE = false
		R15Spinner.MouseButton1Click:connect(function()
			R15SpinnerACTIVE = not R15SpinnerACTIVE
			if R15SpinnerACTIVE then
				R15Spinner.BackgroundColor3 = rloc
				while wait() do
					if track.IsPlaying == false then
						if R15SpinnerACTIVE then
							track:Play(.1, 1, 1)
						end
					end
				end
			else
				track:Stop()
				R15Spinner.BackgroundColor3 = rcol
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://582384156"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		local ArmsOutACTIVE = false
		ArmsOut.MouseButton1Click:connect(function()
			ArmsOutACTIVE = not ArmsOutACTIVE
			if ArmsOutACTIVE then
				ArmsOut.BackgroundColor3 = rloc
				while wait() do
					if track.IsPlaying == false then
						if ArmsOutACTIVE then
							track:Play(.1, 1, 1)
						end
					end
				end
			else
				track:Stop()
				ArmsOut.BackgroundColor3 = rcol
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://717879555"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		local FloatSlashACTIVE = false
		FloatSlash.MouseButton1Click:connect(function()
			FloatSlashACTIVE = not FloatSlashACTIVE
			if FloatSlashACTIVE then
				FloatSlash.BackgroundColor3 = rloc
				while wait() do
					if track.IsPlaying == false then
						if FloatSlashACTIVE then
							track:Play(.1, 1, 1)
						end
					end
				end
			else
				track:Stop()
				FloatSlash.BackgroundColor3 = rcol
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://708553116"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		WeirdZombieACTIVE = false
		WeirdZombie.MouseButton1Click:connect(function()
			WeirdZombieACTIVE = not WeirdZombieACTIVE
			if WeirdZombieACTIVE then
				WeirdZombie.BackgroundColor3 = rloc
				while wait() do
					if track.IsPlaying == false then
						if WeirdZombieACTIVE then
							track:Play(.1, 1, 1)
						end
					end
				end
			else
				track:Stop()
				WeirdZombie.BackgroundColor3 = rcol
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://746398327"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		DownSlashACTIVE = false
		DownSlash.MouseButton1Click:connect(function()
			DownSlashACTIVE = not DownSlashACTIVE
			if DownSlashACTIVE then
				DownSlash.BackgroundColor3 = rloc
				while wait() do
					if track.IsPlaying == false then
						if DownSlashACTIVE then
							track:Play(.1, 1, 1)
						end
					end
				end
			else
				track:Stop()
				DownSlash.BackgroundColor3 = rcol
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://675025795"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		PullACTIVE = false
		Pull.MouseButton1Click:connect(function()
			PullACTIVE = not PullACTIVE
			if PullACTIVE then
				Pull.BackgroundColor3 = rloc
				while wait() do
					if track.IsPlaying == false then
						if PullACTIVE then
							track:Play(.1, 1, 1)
						end
					end
				end
			else
				track:Stop()
				Pull.BackgroundColor3 = rcol
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://698251653"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		CircleArmACTIVE = false
		CircleArm.MouseButton1Click:connect(function()
			CircleArmACTIVE = not CircleArmACTIVE
			if CircleArmACTIVE then
				CircleArm.BackgroundColor3 = rloc
				while wait() do
					if track.IsPlaying == false then
						if CircleArmACTIVE then
							track:Play(.1, 1, 1)
						end
					end
				end
			else
				track:Stop()
				CircleArm.BackgroundColor3 = rcol
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://696096087"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		BendACTIVE = false
		Bend.MouseButton1Click:connect(function()
			BendACTIVE = not BendACTIVE
			if BendACTIVE then
				Bend.BackgroundColor3 = rloc
				while wait() do
					if track.IsPlaying == false then
						if BendACTIVE then
							track:Play(.1, 1, 1)
						end
					end
				end
			else
				track:Stop()
				Bend.BackgroundColor3 = rcol
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://675025570"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		RotateSlashACTIVE = false
		RotateSlash.MouseButton1Click:connect(function()
			RotateSlashACTIVE = not RotateSlashACTIVE
			if RotateSlashACTIVE then
				RotateSlash.BackgroundColor3 = rloc
				while wait() do
					if track.IsPlaying == false then
						if RotateSlashACTIVE then
							track:Play(.1, 1, 1)
						end
					end
				end
			else
				track:Stop()
				RotateSlash.BackgroundColor3 = rcol
			end
		end)

		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://754656200"
		local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		FlingArmsACTIVE = false
		FlingArms.MouseButton1Click:connect(function()
			FlingArmsACTIVE = not FlingArmsACTIVE
			if FlingArmsACTIVE then
				FlingArms.BackgroundColor3 = rloc
				while wait() do
					if track.IsPlaying == false then
						if FlingArmsACTIVE then
							track:Play(.1, 1, 10)
						end
					end
				end
			else
				track:Stop()
				FlingArms.BackgroundColor3 = rcol
			end
		end)

		-- Finished update!
	end)

	Mountain.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1118, -144, 1152)
		wait(0.9)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(604, 55, -415)
	end)

	Island.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1118, -144, 1152)
		wait(0.9)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(838, 5, -773)
	end)

	Sky.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1118, -144, 1152)
		wait(0.9)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-389, 152, -710)
	end)

	AutoHeal.MouseButton1Click:Connect(function()
		local a=Instance.new("ScreenGui")local b=Instance.new("Frame")local c=Instance.new("Frame")local d=Instance.new("Frame")local e=Instance.new("TextButton")local f=Instance.new("TextButton")local g=Instance.new("TextButton")local h=Instance.new("TextButton")local i=Instance.new("TextButton")local j=Instance.new("TextBox")local k=Instance.new("Frame")local l=Instance.new("TextButton")local m=Instance.new("TextBox")local n=Instance.new("Frame")local o=Instance.new("TextButton")a.Name="Booga Classic"a.Parent=game.CoreGui;a.ZIndexBehavior=Enum.ZIndexBehavior.Sibling;b.Name="Main"b.Parent=a;b.Active=true;b.BackgroundColor3=Color3.fromRGB(213,213,213)b.BorderSizePixel=0;b.Position=UDim2.new(0.37956056,0,0.356918395,0)b.Size=UDim2.new(0.240234643,0,0.180751503,0)b.Draggable=true;c.Name="Head"c.Parent=b;c.Active=true;c.BackgroundColor3=Color3.fromRGB(70,70,70)c.BorderSizePixel=0;c.Position=UDim2.new(7.72596778e-08,0,0,0)c.Size=UDim2.new(0.108860746,0,1,0)d.Name="HeadShadow"d.Parent=c;d.BackgroundColor3=Color3.fromRGB(53,53,53)d.BorderSizePixel=0;d.Size=UDim2.new(0.302325577,0,1,0)e.Name="jumphack"e.Parent=b;e.BackgroundColor3=Color3.fromRGB(70,70,70)e.BorderSizePixel=0;e.Position=UDim2.new(0.146835491,0,0.747747719,0)e.Size=UDim2.new(0.387341708,0,0.193693697,0)e.Font=Enum.Font.SourceSansBold;e.Text="HIGH JUMP"e.TextColor3=Color3.fromRGB(255,255,255)e.TextSize=14.000;f.Name="Rejoingame"f.Parent=b;f.BackgroundColor3=Color3.fromRGB(70,70,70)f.BorderSizePixel=0;f.Position=UDim2.new(0.584810138,0,0.747747719,0)f.Size=UDim2.new(0.387341708,0,0.193693697,0)f.Font=Enum.Font.SourceSansBold;f.Text="SPEED HACK"f.TextColor3=Color3.fromRGB(255,255,255)f.TextSize=14.000;g.Name="SpawnChest"g.Parent=b;g.BackgroundColor3=Color3.fromRGB(70,70,70)g.BorderSizePixel=0;g.Position=UDim2.new(0.146835491,0,0.522522509,0)g.Size=UDim2.new(0.387341708,0,0.193693697,0)g.Font=Enum.Font.SourceSansBold;g.Text="SPAWN CHEST"g.TextColor3=Color3.fromRGB(255,255,255)g.TextSize=14.000;h.Name="FastSwing"h.Parent=b;h.BackgroundColor3=Color3.fromRGB(70,70,70)h.BorderSizePixel=0;h.Position=UDim2.new(0.584810138,0,0.522522509,0)h.Size=UDim2.new(0.387341708,0,0.193693697,0)h.Font=Enum.Font.SourceSansBold;h.Text="FAST SWING"h.TextColor3=Color3.fromRGB(255,255,255)h.TextSize=14.000;i.Name="TPPLAYER"i.Parent=b;i.BackgroundColor3=Color3.fromRGB(70,70,70)i.BorderSizePixel=0;i.Position=UDim2.new(0.146835491,0,0.301801801,0)i.Size=UDim2.new(0.182278454,0,0.193693697,0)i.Font=Enum.Font.SourceSansBold;i.Text="SPAM"i.TextColor3=Color3.fromRGB(255,255,255)i.TextSize=14.000;j.Name="TargetPlayer"j.Parent=b;j.BackgroundColor3=Color3.fromRGB(70,70,70)j.BorderSizePixel=0;j.Position=UDim2.new(0.146835491,0,0.0765765756,0)j.Size=UDim2.new(0.387341708,0,0.193693697,0)j.Font=Enum.Font.SourceSansBold;j.PlaceholderColor3=Color3.fromRGB(255,255,255)j.PlaceholderText="Target Player"j.Text=""j.TextColor3=Color3.fromRGB(0,0,0)j.TextSize=14.000;j.TextWrapped=true;k.Name="PlayerShadow"k.Parent=j;k.BackgroundColor3=Color3.fromRGB(54,54,54)k.BorderSizePixel=0;k.Position=UDim2.new(0,0,0.860465109,0)k.Size=UDim2.new(1,0,0.139534891,0)l.Name="RedBox"l.Parent=b;l.BackgroundColor3=Color3.fromRGB(70,70,70)l.BorderSizePixel=0;l.Position=UDim2.new(0.35189876,0,0.301801801,0)l.Size=UDim2.new(0.182278454,0,0.193693697,0)l.Font=Enum.Font.SourceSansBold;l.Text="AIM BODY"l.TextColor3=Color3.fromRGB(255,255,255)l.TextSize=14.000;m.Name="FoodName"m.Parent=b;m.BackgroundColor3=Color3.fromRGB(70,70,70)m.BorderSizePixel=0;m.Position=UDim2.new(0.584810138,0,0.0765765756,0)m.Size=UDim2.new(0.387341708,0,0.193693697,0)m.Font=Enum.Font.SourceSansBold;m.PlaceholderColor3=Color3.fromRGB(255,255,255)m.PlaceholderText="Food Name"m.Text=""m.TextColor3=Color3.fromRGB(0,0,0)m.TextSize=14.000;m.TextWrapped=true;n.Name="FoodShadow"n.Parent=m;n.BackgroundColor3=Color3.fromRGB(54,54,54)n.BorderSizePixel=0;n.Position=UDim2.new(0,0,0.860465109,0)n.Size=UDim2.new(1,0,0.139534891,0)o.Name="AutoEat"o.Parent=b;o.BackgroundColor3=Color3.fromRGB(70,70,70)o.BorderSizePixel=0;o.Position=UDim2.new(0.584810138,0,0.301801801,0)o.Size=UDim2.new(0.387341708,0,0.193693697,0)o.Font=Enum.Font.SourceSansBold;o.Text="AUTO EAT"o.TextColor3=Color3.fromRGB(255,255,255)o.TextSize=14.000;o.MouseButton1Click:connect(function()game.StarterGui:SetCore("SendNotification",{Title="Auto Eat",Text="Press f for autoeat",Icon="rbxassetid://0",Duration=5})local p=game:GetService("Players").LocalPlayer:GetMouse()p.KeyDown:connect(function(q)if q=="f"then local r=m.Text;local s=game:GetService("ReplicatedStorage").Events.UseBagItem;s:FireServer(r)end end)end)l.MouseButton1Click:connect(function()local t="Really red"while wait()do for u,v in pairs(game.Players:GetPlayers())do if v.Name==j.Text then v.Character.HumanoidRootPart.Transparency=0.35;v.Character.HumanoidRootPart.BrickColor=BrickColor.new(t)v.Character.HumanoidRootPart.Size=Vector3.new(14,14,14)end end end end)i.MouseButton1Click:connect(function()local w=game:GetService('ReplicatedStorage').Events;local x=game:GetService('Players').LocalPlayer;local y=x.Character;while wait()do for u,v in pairs(game.Players:GetPlayers())do if v.Name==j.Text then game:GetService("ReplicatedStorage").Events.EquipTool:FireServer(1)game:GetService("ReplicatedStorage").Events.EquipTool:FireServer(2)game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame=v.Character.HumanoidRootPart.CFrame;w.SwingTool:FireServer(tick(),{v.Character.HumanoidRootPart})end end end end)e.MouseButton1Click:connect(function()local z=game:GetService("Players").LocalPlayer;local A=z.Character;local B=A:FindFirstChild("Humanoid")B.JumpPower=72 end)g.MouseButton1Click:connect(function()game.StarterGui:SetCore("SendNotification",{Title="Spawn Chest",Text="Press h for spam chest",Icon="rbxassetid://0",Duration=5})local C=game:GetService("Players").LocalPlayer;local p=C:GetMouse()p.KeyDown:connect(function(q)if q=="h"then local s=game:GetService("ReplicatedStorage").Events.PlaceStructure;local D=game.Players.LocalPlayer.Character.UpperTorso;local E=D.Position+D.CFrame.lookVector*10;local F=E.x;local G=E.y-2;local H=E.z;for I=1,1 do local r="Chest"local J=CFrame.new(F,G,H,1,0,0,0,1,-5.56028681e-08,0,-5.56028681e-08,1)local K=0;s:FireServer(r,J,K)end end end)end)h.MouseButton1Click:connect(function()local L=tick()getrenv().tick=function()L=L+100;return L end end)f.MouseButton1Click:connect(function()game.StarterGui:SetCore("SendNotification",{Title="Speed Hack",Text="Press Q for SpeedHack",Icon="rbxassetid://0",Duration=5})local C=game:GetService("Players").LocalPlayer;local M=C.Character;local p=game:GetService("Players").LocalPlayer:GetMouse()local N=M:FindFirstChild("HumanoidRootPart")local O=3;p.KeyDown:connect(function(q)if q=="q"then loop=true;while loop do N.CFrame=N.CFrame+N.CFrame.lookVector*O;wait()end end end)p.KeyUp:connect(function(q)if q=="q"then loop=false end end)end)game.StarterGui:SetCore("SendNotification",{Title="INFO",Text="for fast swing equip tool first",Icon="rbxassetid://0",Duration=5})game.StarterGui:SetCore("SendNotification",{Title="Credit",Text="by IiEzPiI/RatatuiHelp",Icon="rbxassetid://0",Duration=5})game.StarterGui:SetCore("SendNotification",{Title="Show/Hide GUI",Text="Press 7 for show/hide",Icon="rbxassetid://0",Duration=5})local P=game.Players.LocalPlayer;P:GetMouse().KeyDown:connect(function(Q)if Q=="7"then if b.Visible==true then b.Visible=false elseif b.Visible==false then b.Visible=true end end end)
	end)

	MiddleTP.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1118, -144, 1152)
		wait(1)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(162, 1, -340)
	end)

	InfiniteYield.MouseButton1Click:Connect(function()

	end)

	OldGod.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1118, -144, 1152)
		wait(0.9)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1109, -144, 1155)
	end)

	WaterFall.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1118, -144, 1152)
		wait(0.9)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(49, 1, -770)
	end)

	RockTP.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-800, 2, 153)
	end)

	Volcano.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1118, -144, 1152)
		wait(0.9)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1116, -196, -743)
	end)

	DancingShelly.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1118, -144, 1152)
		wait(0.9)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-991, 4, -2039)
	end)

	Shaders.MouseButton1Click:Connect(function()
		local light = game.Lighting
		for i, v in pairs(light:GetChildren()) do
			v:Destroy()
		end

		local ter = workspace.Terrain
		local color = Instance.new("ColorCorrectionEffect")
		local bloom = Instance.new("BloomEffect")
		local sun = Instance.new("SunRaysEffect")
		local blur = Instance.new("BlurEffect")

		color.Parent = light
		bloom.Parent = light
		sun.Parent = light
		blur.Parent = light


		local config = {

			Terrain = true;
			ColorCorrection = true;
			Sun = true;
			Lighting = true;
			BloomEffect = true;

		}


		color.Enabled = true
		color.Contrast = 0.15
		color.Brightness = 0.1
		color.Saturation = 0.2
		color.TintColor = Color3.fromRGB(255, 222, 211)

		bloom.Enabled = true
		bloom.Intensity = 0.3

		sun.Enabled = true
		sun.Intensity = 1
		sun.Spread = 5

		bloom.Enabled = true
		bloom.Intensity = 0.05
		bloom.Size = 32
		bloom.Threshold = 1

		blur.Enabled = true
		blur.Size = 2



		if config.ColorCorrection then
			color.Enabled = true
		end


		if config.Sun then
			sun.Enabled = true
		end


		if config.Terrain then
			ter.WaterColor = Color3.fromRGB(10, 10, 24)
			ter.WaterWaveSize = 0.1
			ter.WaterWaveSpeed = 22
			ter.WaterTransparency = 0.9
			ter.WaterReflectance = 0.05
		end


		if config.Lighting then
			light.Ambient = Color3.fromRGB(120, 31, 42)
			light.Brightness = 3.5
			light.ColorShift_Bottom = Color3.fromRGB(12, 31, 42)
			light.ColorShift_Top = Color3.fromRGB(12, 31, 42)
			light.ExposureCompensation = 0
			light.FogColor = Color3.fromRGB(132, 132, 132)
			light.GlobalShadows = true
			light.OutdoorAmbient = Color3.fromRGB(112, 117, 128)
			light.Outlines = true
		end
	end)

	Giant.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1118, -144, 1152)
		wait(0.9)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-137, 7, -2019)
	end)

	Emotes.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://gitlab.com/Tsuniox/lua-stuff/-/raw/master/R15GUI.lua"))()
	end)

	Desert2.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1118, -144, 1152)
		wait(0.9)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1091, 1, 607)
	end)

	Volcano2.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1118, -144, 1152)
		wait(0.9)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(458, 6, 1563)
	end)

	Island2.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1118, -144, 1152)
		wait(0.9)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1120, 5, 511)
	end)

	Middle2.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1118, -144, 1152)
		wait(0.9)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-453, 3, -23)
	end)

	PlayersTP.MouseButton1Click:Connect(function()
		_, Protected_by_MoonSecV2, Discord = 'discord.gg/gQEH2uZxUk'


		,nil,nil;(function() _msec=(function(l,h,o)local E=h[(1260/0xe)];local T=o[l[(112539/0xa1)]][l[(-23+0x335)]];local i=(0x60+-92)/(51+(-0x15-(6972/0xf9)))local n=((-37+(-0x14c1/253))+0x3c)-(0xf3/243)local v=o[l[(0x969c/252)]][l[(34827/0x8d)]];local t=(((-61+-0x11)+0xb4)-0x65)+(0x73+-113)local a=o[l[((2328-0x4c7)-0x231)]][l[(14778/0x12)]]local b=(-0x3c+62)-((0x8a6/(0x8c+(-0xc9+88)))-0x51)local F=((0x4a+(-0xd8/(0x284/161)))+-0x11)local M=(25-(((-0x55+-21)+-4)+0x84))local r=((64428/((-53+0xff)-111))/236)local H=(69/((-33+(4373+-0x3e))/0xba))local p=(759/(281+((-0x2d+-31)+48)))local P=(((((0x6-38)+555)-287)+-120)+-0x71)local K=(0x1c-(0x139a/(-0x15+(469-0xff))))local d=((0x7f+((-1383+-0x19)/0x40))-0x67)local L=(396/((-42-(4380/0x92))+0x10e))local m=((((0x311+-61)-0x18c)+-44)/142)local B=(-0x6e+(330-((29489+-0x3b)/135)))local f=(0xd2/(((0x355-443)+-0x4e)-0xe3))local c=(((86+(50-0x52))+-0x6f)+0x3d)local U=(0x224/(181+(-48-(-104+0x64))))local _=(((606-(-0x30+385))-0x93)-0x76)local D=(44-(0x9e-(193+(-53-0x16))))local w=((263-(22780/(0x140-186)))-89)local C=(-0x37+((28+((20+-0x3a)+-0x2b))+112))local G=l[(22644/0x11)];local J=o[l[(356-0xcb)]][l[(28210/0x3e)]];local Q=o[(function(l)return type(l):sub(1,1)..'\101\116'end)('HKlLfPpf')..'\109\101'..('\116\97'or'lokhbkHk')..l[(0x293+-115)]];local y=o[l[(0x4bb-667)]][l[(0x3e1+-83)]];local u=(0x4f+-77)-(100/(0xd0-(415-0x101)))local S=((-86+(-3220/0x8c))+0x6f)-(0x10/8)local A=o[l[(412-0x103)]][l[(433+-0x63)]];local e=function(o,l)return o..l end local s=(828/0xcf)*((-0x71+(164934/0xc6))/180)local V=o[l[(2429-0x4d9)]];local O=(-17+0x13)*(307-(0x469f/(0xef-138)))local g=(0x86e-1134)*(((-0x181efc/108)/119)+0x7d)local Y=(-18+(240-(-0x2c+214)))local N=(68+(-0x2e26/(411-0xe8)))*(174/0x57)local x=o[l[(0x4b2+-124)]]or o[l[(0x486-614)]][l[(0x4b2+-124)]];local k=(-23+((778-0x1ac)+-71))local l=o[l[(0xf136/50)]];local j=(function(k)local O,h=1,0x10 local o={j={},v={}}local e=-b local l=h+n while true do o[k:sub(l,(function()l=O+l return l-n end)())]=(function()e=e+b return e end)()if e==(s-b)then e=""h=u break end end local e=#k while l<e+n do o.v[h]=k:sub(l,(function()l=O+l return l-n end)())h=h+b if h%i==u then h=S y(o.j,(A((o[o.v[S]]*s)+o[o.v[b]])))end end return a(o.j)end)("..:::MoonSec::..bBfFlLkKoOpPhHmMhFplookhLbFlBoMhbohlpoohLbLoFoBhbblPfOBOMLPlLhFhfbblFhFBfoboFokhlbflboFllLfBMOmphMpHohLmLMlFfhmhmBHkPhbhBkMlHoPhBbMbhOhLOLokLomkhbplooPFPLpokPkBLfFpBBmMHLPkFOmhomfFbhBPkkPFHolbfbblmoBpBBbBHHKmmBkmHLbpMobmfpFhlbLffobhMbBPBHBbhlhOPPoMKLkfFhBHbmMoHPhhFKBlMoHhBbBbmOmLPLpkoPOhmlhlpoohHkPHpkoblbmphophObhlPOpmoLKfLhkhPPOlKoLhoKoOKhfMFoBHblmbHfpOOkpmMbHlPoOhobklFokPObMmHoPhpbHbhOhfOBklkKlmFlbLMlkhkBFlBoMhlkfHBpMBmlhFpHKMkolHFkfbMLmkPHpMOlblmhhhPbOlhoPHPfOompBLBMmmHoOLbPfkkKombbpbhPOhlpmbMkkPObMOHoPhpbMbHKhFOLokPomLhbploopMPoOLopLHlFFobHMmHbLpFoBhbbfKbmBmMBmBPHMmppmBhBlPOkbLLMOPffPmpBoLkOlHFBlLOMhkMLHoPhpbolkoKlpFhoFOBbMlHoBbbMMOhPPlKOofkhlBFfbOMPmbHfbblFmKOMBBBLKLfMPllFBhbbmlBlBPMFHLhlohohkLkBFBffHkKPPopMlFmpMoHHKlPpBkMOHHhBpLoOoHMKMmFloHKBkhPhHhhLMPmbookolhFboPLOlLFlkkbokPkoFlmFofpLoFmoOLKbLlFoKFkMLkFFBMbbHLPPpBmfPbOKmhBbLbhHFMKMblbHmhHbPlboHHhOPkOPbhMFHlPoOhmmhOPMhmBbMlHoPhpbolkolhOfLfLfOOMMLOOllbbMLkFkHpLFflfBoPmhOlpFBhbbmlHpHlObKlLoFHfbblmomhPbOlKoLhlbflBfmhMbPlOoKhkbllfofoMbMlPoOhobkllofhfLMlMoPhpbolkolhFbBKMommhbploOkhKlFlBoMhMfhlpoomKbLLFoBhbbblhophOfKlLpFhfLblMphhPbOoKoKmlbflbomhHbPlOpKhklllfpbhBbHlPoOmobkkloFPBbBlHoPhpfolkplhFOBlMoHhhbpkookMLbFlBoMhmbhlpOohKbLlFPBhblmlhophObOOLoFHfbflMBhhPkOlKHLhlKflfmbPHbPpOooMkblLfofkMbHoBBOhobklLPfhBBMlHhBLpbolkoKBFbBLMoMhhOplomkhLLFlflMhmkfkpoOfKbkPFoBHbbmLhoPbmOKlLoFhFKblmOhhPlmHKoLhlblObomHHbhkOpKhkkllFobhMbHlPoPHobkPlofhBbMlHoHhpbolKblhFLBlblHhHfplooKLLbLpBoMhmbhlpoohKkLllBBhbBmlHpphObKpLoLhfbblmoHmPbOlKMLhLmflbomhHbPlOoofkblkfobHMbmkPoOhokklLofhBbMlHoPhpboPkolhFbBlMoMhhbplObkhLLFlflMhMfhlpoOLKbkfFoBhbbmlhophOkKlkBFhfBblmhhhPbOlKooFlbfLboMfmfPlOOKhkMllfObhMfHlPhMLobklloFPBbMLHohmpfolkOlhLbBlMoHhHfPKookmLblHBoMhmbhlpoohKBLlFpBhbBmlHpphObKLLoLffbblmomhPbOlKOLhlBflfHmhmfPlOoKmkblhfobhMbmkPoOhoFklkLfhBbMlmpPhpbookoKlFbBlMommhbploHkhkFFlBoMhMfhlpoOfKbKKFoBhbbMkhophOKKlKFFhfbblMphhPbOhKokflbflboMmHbPlpBKhKKllfobhbfHlPopkobKklofhBbbkHoPhpPoloKlhFbBlbpHhhbPbooOFLbFlBobmmbhlPLohOBLlFoBhbbmlhopHOboBLoFmfbBlmohhPbOlomLhlBflBpmhHbPLOoOhkbllfoBmMbHlPpOhOmkllofhBbMlHoPHpbokkolHFbfkMoHhhBplphkhLbFlfpMhmbhkpooHKbLlFoFhbbmlhpphOfKlLHFhFfblmoHbPbOmKoLhlbflbomhHfPlOhKhkflllobhMbHkPoOmobKBlofhBbMlHpPhpFolkolhFbBlMoHHhbplookMLbFoBoMhmbhlBbohKBLlLofLbbmphoPBObKPLoLhkMblmmhhPkOlohLhlbflboMfHbPkOoKmkbklfobhMkHlPmOhoPkllofhBbMhHoPhpbolkokhFbBlbbHhhoplopkhKbFlBoblmbhhpopbKbLlFoBhbomlHBphObKlLoFhfbbpmohhPbOkKokflbflbmmhffPlOOKhkBllfhkLMbHlPommobkLloFbkOMlHoPhboolkOlhlfBkMomfhbpLookhLbLlFFMhmkhlpmohKpLlLoBhbbmphoPfObObLoLhfbblmmhhPkOloHLhLfflboMfHbPoOoKhkbLkfobhMkHlPhOhobklkofhBbMpHohfpboKkokhFbBlMMHhhLplOHkhKbFlBobFmbhPpooMKbKlFoBhbKmlhMphpBKlKoFhfbbPmoHFPbppKokhlbflbmmhmkPlOMKhKfllfoBfMbMlPoOhobKklofhBKMlMbPhpbolkolhFbBpMoHmhbpLooKmLbFlBmMhmlhlpoohObLlFoffbbmphopMObOlLoFhfKblmHhhhLOlOoLhlbfPboMFHbPKOoOhkbllfMbhMKHlhOOhpbklloFFBbMPHoHfpbOlkolhFkBlbmHhhKplomKmLbFLBolfmbhLpoomKbLoOBBhbbmlbmphOBKlLopFfbblmohHPbOlKoLhlbflbomhHoPlOoKhffllfobhMbHlPobhhbmllhfhBbMlFPflbBMkloLbFbBlMoFmFOBomHlmLbFlBoMhmbhlOohPKbLKFoBhbbLKFHbmObKpLoFhfbKKLhFmBObfHMLhlhflbomhFMfkmOmbHLOHoKKflpFHMHMFhbkllofhBbBLHoPhpbOkkplhFFBlMMHhhbplooPMLbFKBoMMmbhLpoOfoHLlFPBhbKmlhOphObKlLhOLfbblmoHFPbOLKokmlfflbPmhHKPlOoKhkbOKfobMMbHKPoOHobklphfhBFMlHpPhpbolKppkFbBKMombhbplooKmOmFlBhMhmohlpoohofLlFofBbbmohophObKlLoFhfkblmohhPbOlopLhlbfPboMbHbPlOoobkbllfHbhbHHlPOOhobKbloFLBbMoHoPhpbOkoPlhFpBlMmHhhbplpokhLbFmBobkmbhkpophKbLllFBhbbmlhHphObKlLolOfbbhmohhPbOlKoLhlmflBbmhHbPlOoKhkblMfoBpMbHkPoPhobklLFfhBPMlHPPhpbolkoLKFbBkMoHmhbplookhLPFlfFMhmFhlhoohKbLMFofKbbmLhophObKlkfFhffblmphhPbOlKokblbfHboMkHbPlOoKhkOllfPbhMfHlHoOhobkKloFLBbMLHohbPholkHlhFHBlMOHhHfpkooKBLbFPBoMhmbhlbFohKLLlFOBhblmlhoBbObKoLoFmfbblmohhBKOlKoLhlBflbomhHFPLOoKhkbllfobhMbHlPoOhobkPlofhBbMlBOPhpbolkOlhFbBlMoHhhbplookhLbFlBoMhmbhlpoohKbLlFoBhbbmlhophObKKLoFhfbblmohhPbOlKoLhlbflbomhHbPlOoKmkbllfobhMbHlPoOhoBkllofhBbMkHoPhpbolkHlhFbBlkoFMfBBbMlmmLbFlBoMhmbhlpoohoHLlFoBhBfFmhopmObKkLoFhfbBklfhhPFOlKpLhlbflBpmmHbPoOoKHkbllfoBfBKHlPHOhobkllOfhBlMlHoHhpbolkolmFbBlMoHhmbplookhLbFlBoMhmbmlpoohKbLKFoBhbbmlmophObKlLOFhfbblmomfPbOoKoLmlbfLboMfBPPlOoKhKOllfObhMBHlPhMLobkllolLBbMLHohfmOolkolhFmBlMOHhhBplohhLLbFlBobpmbhLpoObhOLlFoBhBOmlhOphOkPHLoFHfbBLmohHPbOlKokbOOflbomhmBPlOOKhklOHfobhMbmHPoOHobklKFfhBlMlHpPhpFolkoKKFbBOMoHMhbpkooKfOPFlBhMhMOhlpOohKLLlFhKLbbmlhohLObKLLoFhlPblmhhhPfOlKPLhlblMboMBHbPKOoKmkblpKBbhMlHlHfOhoBkllHfhBllHHoPhpbOmkolHFbBlFhHhhlplookhLbFlBolhmbhopooHKbLlFoBhklmlhhphOfKlLoFhfbkPmohhPbOLKoLhlbfkLmmhHbPlLpKhkbllfobhMbbMMoLhoKkllofhklLOLbFbmfMFmbbhFlBlMoHhBFbHbfHBLbFKBoMhmbFfbHbFFbkOFoBhbbloFBBMMFmFhppblmkPlMMPBKmLPHplKfOOkfklfLBMBpkbkpKHfoFoPhPmMKMmmKhPHKlPLFPmhMMPoboMkolhFbklklFHFObOMpohOmOLoLkBlfMlHoOOKbopHPOlFMhkhophObKlLoFhBblFpphhPbOlKoLhlbLblomhHOPlOoKhPlpOpbobFhFLBpbBmhlllOfhBbMlFKKhpoolkolhKOofkPLbfBBfmPHBKbFOBoMhmbbKBKMoHMhkOofbbbmlhobBHlHHhLPhflblmohhBKMLmLhBpfflbomhHbPlOoKhpbflfmbhMbHlMpBBMlHoPKOpOBMLPpPhpbolkolhPbLpFoFhhkplookhpbOLopkBlmFobopBKbLlFoLMkMLbFKBmmFHOhOPBoLKflPFBMPMOMBhhpMoHKkkbFbPmOoKhkbOooHolklBKfKbomMHkKPmhBoMlHoPhbhhHpOpHKHoBlFlkmfplookhLbFlBoHhBMflPfohKbLloHkLlKLkfOBbMOHOhkPbbbBbmohhPbbFmppHplOOkBlPFkbmbBhBPKbkfobhMbHlPoBhHPplhoFLBbMlHobbBfmLhMPFOBKkkllBffplookhLbFlOoLLfbmlpMohKbLlOmomkMLBBpMFHfHkLoFhfbblmophBMHlBpLhlbflbomhHbmoLoHhkpllfobhllFOFbBbHFhKpOOoKLLoLpPhpbolkolhFbkPFoLhhmplookhOKpFohkllBFBMPMBHHPHOpoPkhloooPKObKlLoKHomkKLbFPffmlmKhLpmOokobfHbPlOoPmhBpKOFKFkflFfHbpmlPoPpoHKmkKloBHBfmOHkpMpOLlbOHhhbplHLHPhLpKKHFmLLFoBhMPHmoLKPookOlKFFfhOKKlLoFhkFKFLpFBMKbOmBKhlkflbomhBBBKbhmLHkpOlpbhMbHlPoOhobpOoopmMmLopHKPlfhBlpoPKbBhMoHhhbMlMKHMPOpooBkPlmklPBohKbLloPKMKflOfHBpHKmOhBHmfbblmohhPbOlooOhkbfPbomhHbMKbKmphmpOoPobPfHlPoOhobklhoKhLbOkHoPhpbolkohhOkLlLombhbplooPBPmpOoLKhmlhlpoohPkhFpkObkbmphophObhmpBppolkOkbfhPMOlKoLhofOFKpLbFLfkmPmLHppOKoKLkoFOflBhokkllofhLFkFllfPBfPKppPmMKOoLoKHlPobhKhmMmFbMBLPPPpmoohPPfLlFoBhbbmlhomfHbOlkoFhfbblfpfHBFMMHMhmpMOOKkLbBFfFblmPHfKKhoBKMbHlPoMbmLHhPhoFofLLlofhbLmokoLlFbBlMoFbfLBhMhPMPOpmKHKmmbhlpoohKbLlpKLhbbMbhophObPKhKpmomkOLpBmBBMomBHBPFmlbHmhHbPlHmmmhBPBoHkhMlHlPoOhhmhLPLOBPfMlHoPhpbolkolhFbPlblHhhbplhpHPhfOoKHkmfFFFBlMPmfoKLpBhbbmlhophFbHhOoKmfbblmohhPbHlHlOhhbfObomhHbbOHhmLhHKkboBbMbHlPoMbmLHhPhmhBpMlHoPhMMmFHPPBOFoOkplBfLBLkoKPLbFlBolLlmFKbHMmmlPOOhkPkflmfHbMblmKHollfbblmofbBLbbHHhhpMOkKhmhHoPlOoKhpKPkoOKbLOFOfkBblfkFOPLmoMhKKFopHMpkkolhFbBlMoHhMlmlkpkhLbFlBoMhkbbmmophKKLlFoBhLklOfPfbMMmkopFhFFblmohhMBbfmKhpkbkKKbLBFBfobPOhPKpHOkKpLOlfBMBhookllofhkLFHBPfPBfMfhHPmKbBmMoHhhbMomHmlhlKkoHKbLlFFBkomkHfFfpFhkFKboOmPOboBLoFhfblKLKFoBMbkhPhBPBOOkHLpFFBOOoKhkbllfommFbFpBLMPlopKbLkPLbMLHoPhpfmOkolhFbBkMoHhhbPkOOkhLbFlkbMhmbhlpoohKbLlFoBhbbmlhophObKlLOFhfbblmohhhfOlKoLHlblbbomhHbhkOoKhkBllFLbhMbHlHmOhobkLloFLBbMLHohBpboohBlhFbBlbBHhhBplohhLLbFlBobkmbhLpoohHKLlFoBhbBmlhophOfHOLoFHfbbLmohhPbpkpmLhlBflfBmhHbPlppKhkblLfoBpMbHlPoPhobkllOfhBBMlHhPhPfolkolmFblfMoHhhbplookhLBFlBpMhmfhlPpohKbLkFofpbbmlhohhObKlLpFhffblmhhhhfOlKoLMlbklbomhHbPlOoKhkfllfpbhMfHlhpOhobkKloFpBbMlHoHhpbolkPlhFFBlMhHhHfplooKbLblMBoMhmbhlpoohKFLlFpBhbfmlHpphObKoLolpfbblmomhPbOlKhLhllflbhmhmfPlOooBkbOLfobhMbHlPoOholkllpfhBfMlmpPhpboOkoLpFbBlMoMhhbploHkhLLFlBhMhMfhlpoOfKbpkFoBhbbmlhophOLKlLpFhffblMphhPbOpKokplbflbobhHbPlOmKhkkllfhbhbfHlPopFobPLlofhBbMlHoPhpkolkplhFfBlbpHhhbpPooKpLbFlBoBhmbhlpMohKKLlFhBhBfmlhoPlObobLoFhfbblmohhPKOlKpLhlfflBpmhHbPhOoopkbllfofhMbHlhbOhookllhfhffMlHohLpbokkolhFbBlMoHhhoplopkhLfFlfpMhmbhHpoOpKbLlFoFhbbmlHBphOOKlLhFhFfblmoHkPbmLKoLhlbflbomhHOPlOpKhkfllFpbhMbHmPoppobkllolhBbMlmfPhppolkhlhlfBlMomKhbPbookhLbFlBoMhmphlppohKfLlkoBhbbmLhomHObPHLolmfbblMFhhhBOlKoLhkbflboMKHbPMOopLkbLlfobhMBHlhmOhoPklKofhBbMkHoMHpbhMkoLhFbBlMpHhHkploOkhkfFlBobKmbMPpoohKbKlFoBhbPmlHFphPbKlkpFhfbBbmomHPbOlKokmlbflBLmhBfPlOoKhKfllfoBpMbbFPoOhobkllofhBPMlmkPhpfolKolhFbBkMoBKhbpMooKmLbFlfFMhBKhlpoohObLlFofKbbmMhohhObokLoFhfhblmOhhPbOlopLhlbFBboBKHbPlOoomkbllFkbhFmHlPoOhobklloFKBbbfHoPmpbOlkolhFfBlFPHhhPplPokhLbFkBoFfmbbkpoOmKbLllFBhlkmlhophPbKlLolKfbbMmoHbPbpkKoLhlhflBBmhHbPlppKhkbLBfolmMbHlPopmobklLkfhBkMlHoPhPfolkoLPFbLkMoHhhbplookhLPFlfKMhmfhlPoohKbLkFolObbmMhoPmObKlkFFhkkblmohhHbOlKokKlbfMboMbHbhkOoKhkhllkpbhMbHlhpOhobKBlokpBbMlHohmpbolKklhKfBlMoHhHfplooKPLbLoBoMhmbhlpoohKPLllKBhbfmlHophObKkLoFMfbbMmoMhPbOlKpLhkpflBhmhbbPlOoKmkbkffofbMbmkmOOhoPklOhfhBbMlMoPhpboMkoLKFbBoMoHhhbplOlkhLBFlBoMhMfhlpoOOKbkPFoBhbbblhophOHKlkLFhflblMphhPbpfKoOmlbflboMmHbPlpKKhOKllfobhBbHlPopPobKFlolhBbbkHoPhPboloKlhFbBlbpHhhbPLoooBLbFlBobmFphlPpohPLLlFoBhbbFPhoPPObokLoFhfbblmohhPHOlKoLhlfflBpmhHbhfOoOFkbllfofhMbHlhkOhomkllhfhffMlHohPpbomkolhFbfkMoHhHbplPMkhLbFlFoMhmbHlpoOhKbKlFofmbbmlHOphHlKlLoFhFfblmoHmPbhLKoLhlbFkbomhmFPlPLKhkbllfolMMbmlPopMobkllofhLkMlmkPhpbolkolhFbFpMomohbplookHLbFlfLMhmPhlppohKfLllolPbbmKhoPPObKMLolhfbblmPhhhkOlKpLhLfflboMKHbhlOoKhkbklfobhMPHlhFOholklLpfhBbbbHoMmpbolkoLmFbBlbLHhmMplookhLbFlBobKmbHBpoomKbklFoBhblmlbKphOPKlkoFhfbbomomfPbOkKoohlbflbHmhBBPlpPKhKbllfoBBMbmpPoOmobKklofhBPMlbMPhpboloolhFbBMMomKhbhlooKmLbFlflMhffhlpoohofLlFofObbfkhophObokLoFhfmblfphhPbOlKoLhlbfMboMpHbPkOoohkbllfHbhfPHlhFOhPbklloFBBbfpHoMmpbOkkolhFPBlFmHhhbplpokhLbFMBobKmbhopoOmKbLlllBhLFmlhophpfKlLolOfblkmohhPbpkKoLhlmflLlmhHbPlppKhkbLFfolmMbHlPoOhobklLFfhBMMlHpPhPbolkoLBFblBMomKhbPkookhLPFlLmMhmbhlhoohKbLMFofKbbmohoPmObKlklFhkfblmohhhfOlKokOlbLkbomhHbhkOoKhkmllkpbhMbHlhpOhobKFloKOBbMlHoPhpbolKFlhFMBlMpHhHbplooKBLbFKBobKmbMlpoohKLLlkHBhBfmlHpphObKMLokMfbblmomhPbOloFLhlPflFhmhMbPlOooKkblMfoFBMbmlPoOhoLklKhfhBPMlboPhpboOkoOFFbkOMommhbplOFkhoKFlBoMhbbhlpoOKKbLMFoFhbbMkhophOhKlKOFhfbblMphhPbpBKoKHlbflboMmHbPlpkKhoBllfobhMbHlPopKobKflofmBbblHoPhpLoloblhFPBlfoHhhbpOoooMLbloBofhmbhlpHohpHLllFBhFbmlhoPBObPbLoLbfbBlmohhPkOlomLhlLflBomhHbPPOoOfkblOfoBmMbHlhFOhhMkllofhFbMlHohKpboMkoLbFbfkMoHhhhplpfkhLbFlfpMhmbHBpopkKbLlFoBhbbmlHFphOHKlLpFhFbblmoHFPbPpKokKlbFkbomhHPPlhMKhkblllobhMbHMPopKobolloFmBbMlmlPhhBolkolhlfBlMomOhbhLookhLblkBoMhmmhlhOohKbLlFoBhbbmMhoPpObKkLolhfbblmMhhmPOloFLhKbflboMFHbHPOookkbLkfobhMPHlmMOhobklkofhBbMMHohKpbplkoLmFbBlblHhhBplookhkfFlBobOmbmMpoohKbkkFoBhbmmlBkphObKlLoFhfbbMmoHpPbOkKokhlbflbMmhBFPlpFKhObllfoBFMbbpPoHmobKklofhBPMlBmPhpboloolhFbBMMomKhbpoooKmLbFlflMhMphlpoohofLlFofObbfkhophObokLoFhfmblfBhhPbOlopPklbFFbofmHbPlOoKhkollFFbhMMHlPpOhObklloFFBbfBHohKpbOkkolhFPBlFmHhhbplpokhLbFMBobKmbhopoOmKbLlllBhbpmlhophpfKlLolOfbfkmohhPbpkKoLhlmflbMmhHbPlppKhkbLFfofmMbHlPoOhobklLFfhBMMlHpPhPbolkoLFFbBKMomKhbHlookhLKFllHMhMfhlPpohKbLMFolMbbmlhohhObKlkFFhfPblBhhhHbOlKokKlbfMboBBHbhlOoKhkKllLhbhMPHlmoOhobkPloKFBbFmHohmpbolKFlhkKBlMoHhmbplooKKLbFMBoBhmbHkpoohKhLlLOBhbbmlHpphOboBLoLHfbblmoHmPbOlokLhkBflbomhHbPlOooKkbLffobmMbmlPoOhoKklkbfhBPMlboPhpboPkooOFbBMMobhhbploMkhohFlfhMhMbhlpoOlKbkpFoBmbbMkhophOPKloMFhfbblbohhPbOMKokKlbllboMmHbPlplKhpfllfobhbfHlPopOobpklofhBbbkHoPhpmolpplhFbBlMoHhhbpMooKpLbFkBobhmbhlPbohpPLllFBhBfmlhoPKObPpLoFhfbflmohhPPOloFLhllflBpmhHbhbOohMkbllfoBmMbHlhLOhhfkllofhffMlHohppbPbkolhFbfkMoHhhMplhpkhLbFlBoMhmbhMpoOPKbLkFofhbbmlHbphPHKlkFFhFfblmoHKPbHpKoLhlbllbomhHPPlpFKhklllFpbhMbmbPoHmobklloFmBbMlmLPhHfolkolhlfBlMomphbmkookhLblkBoMhmMhlmfohKbLlFoBhbbmMhoPPObKkLolhfbblMbhhPFOloFLhLfflboMKHbmKOoKhkbklfobhMPHlhFOhPlklkofhBbMMHohKpbpOkoLhFbBlbbHhMlplOFkhobFlBoblmbbPpoOlKbkkFoBhbPmlMMphObKlKoFhfbbMmoHKPbPlKokmlbflBlmhMBPlOoKhKfllfoBOMbMLPoOhobKklofhBmMlMOPhpbolkolhFbBMMomphbpkooKhLbFlfbMhMohlPFohpbLlFoflbbfBhoPKObolLoFhfOblMmhhPoOlooLhlbfmbobfHbPkOoomkbllFFbhFMHlPoOhpbklloFKBbMMHohbpbOkkolhFhBlBfHhhbplOpkhLblBBoBkmbhlpoohKbLllFBhbHmlhpphpbKlLolkfbfpmoHKPbpkKoLhlPflFMmhHbPlPoKhkblMfoBKMbMlPopmobklLlfhFBMlHoPhPfolkoLOFbFLMoHhhbPkookhLmFlFOMhmbhlpoohKbLMFofpbbmkhoPhObKlkfFhLPblMFhhmbOlKokklblPboMkHbhkOoKhkPllLMbhMbHlHoOhobkMloFKBbBlHohmpMolKllhFBBlMoHhHfplooKOLbLMBoMhmbHkpoohKmLlokBhbbmlhophObKMLolpfbbkmoHhPbOlofLhoFflBFmhbbPlOookkbKpfolmMbmkPoOhoPklomfhBbMlMoPhpboMkoLKFbBoMommhbplOlkhkpFlBoMhMfhlpoOOKbOkFoBhbbMkffphOmKlpmFhfbblMpbbPbpFKoOmlbflbomhHbPlpFKhkMllfpbhbbHlPopkobOBloFKBbbkHoPhpPolpmlhFbBlBoHhhbpMooKKLbFoBobmmbhlPlohKpLlFoBhBfmlhoPOObOkLoFhfbBkmohhPmOlPbLhlbflBpmhHbhFOoOmkbllfobhMbHlhFOhoMkllpfhfbfbHohkpboKkoLKFbllBfHhhpplPHkhkfFlfpMhmbhMpoPMKbLlFoFhbbmlHFphOPKlohFhlbblmoHKPbOMKooBlbFlbomhHpPlhhKhkPllLobhMbHmPomFobPlloFmBbMlmFPhHKolkolhLbBlMomKhbpMooohLblkBoMhmhhlhOohKbLllpBhbbMBhohHObKlLolmKpblMkhhHBOlKoLhlbKpboMKHbhfOoKmkbLlfobhMpHlHbOhoPklKofhBbMmHoMOpboMkoKhFbBlbfHhMhplOhkhKbFlBobKmbhOpoPlKbKlFoBhbPmlHFphhbKlLmkFfbBBmohhPbOLKoLHlbflfomhHbPlpbKhkbllfoKlMbHMPopOobkLlofhKKMlHoPhpBolkolhFb");local a=(0x7e-98)local o=64 local h=b;local l={}l={[(0x16+-21)]=function()local f,e,b,l=v(j,h,h+t);h=h+N;o=(o+(a*N))%k;return(((l+o-(a)+O*(N*i))%O)*((i*g)^i))+(((b+o-(a*i)+O*(i^t))%k)*(O*k))+(((e+o-(a*t)+g)%k)*O)+((f+o-(a*N)+g)%k);end,[((163-0x74)-45)]=function(l,l,l)local l=v(j,h,h);h=h+n;o=(o+(a))%k;return((l+o-(a)+g)%O);end,[(147/0x31)]=function()local l,b=v(j,h,h+i);o=(o+(a*i))%k;h=h+i;return(((b+o-(a)+O*(i*N))%O)*k)+((l+o-(a*i)+k*(i^t))%O);end,[(0x25-33)]=function(h,l,o)if o then local l=(h/i^(l-b))%i^((o-n)-(l-b)+n);return l-l%b;else local l=i^(l-n);return(h%(l+l)>=l)and b or S;end;end,[(585/0x75)]=function()local o=l[(-0x2b+44)]();local h=l[(0x62-97)]();local f=b;local e=(l[(0x26c/(196+-0x29))](h,n,s+N)*(i^(s*i)))+o;local o=l[(0x12c/75)](h,21,31);local l=((-b)^l[(0x30c/195)](h,32));if(o==S)then if(e==u)then return l*S;else o=n;f=u;end;elseif(o==(O*(i^t))-n)then return(e==S)and(l*(n/u))or(l*(S/u));end;return T(l,o-((k*(N))-b))*(f+(e/(i^Y)));end,[(128-0x7a)]=function(e,f,f)local f;if(not e)then e=l[(0x24+-35)]();if(e==S)then return'';end;end;f=J(j,h,h+e-b);h=h+e;local l=''for h=n,#f do l=G(l,A((v(J(f,h,h))+o)%k))o=(o+a)%O end return l;end}local function S(...)return{...},V('#',...)end local function g()local P={};local e={};local o={};local B={P,e,nil,o};local h={}local d=(-0x19+97)local k={[(0xa7/167)]=(function(o)return not(#o==l[(226/0x71)]())end),[(154/0x4d)]=(function(o)return l[(113+-0x6c)]()end),[(0x57-(-0x1f+118))]=(function(o)return l[(-18+0x18)]()end),[(-35+0x26)]=(function(o)local h=l[(840/0x8c)]()local l=''local o=1 for b=1,#h do o=(o+d)%k l=G(l,A((v(h:sub(b,b))+o)%O))end return l end)};for l=n,l[(0xb1/177)]()do e[l-n]=g();end;local o=l[(61-0x3c)]()for o=1,o do local l=l[(-45+0x2f)]();local b;local l=k[l%(0x1f60/251)];h[o]=l and l({});end;for O=1,l[(198/0xc6)]()do local o=l[((233-0x8e)-89)]();if(l[(0x138/78)](o,b,n)==u)then local k=l[(95-0x5b)](o,i,t);local e=l[(0x68/26)](o,N,i+N);local o={l[(121-0x76)](),l[((504-0x129)/0x45)](),nil,nil};local M={[(0x4f-79)]=function()o[H]=l[((0xd3-163)-45)]();o[C]=l[(133-0x82)]();end,[(36+-0x23)]=function()o[r]=l[(84/0x54)]();end,[(0x14c/166)]=function()o[p]=l[(-0x68+105)]()-(i^s)end,[(0x240/192)]=function()o[M]=l[((177-0x89)-0x27)]()-(i^s)o[D]=l[(0x27+-36)]();end};M[k]();if(l[(-38+0x2a)](e,n,b)==n)then o[m]=h[o[f]]end if(l[((-8085/0xa5)+53)](e,i,i)==b)then o[F]=h[o[p]]end if(l[(0x10/4)](e,t,t)==n)then o[w]=h[o[w]]end P[O]=o;end end;B[3]=l[(-107+(-71+0xb4))]();return B;end;local function u(l,N,a)local s=l[i];local O=l[t];local k=l[b];return(function(...)local l=b l*=-1 local t=l;local A={};local o=b;local S=S local j=V('#',...)-n;local v={};local h={};local k=k;local g={...};local O=O;local s=s;for l=0,j do if(l>=O)then A[l-O]=g[l+n];else h[l]=g[l+b];end;end;local l=j-O+b local l;local O;while true do l=k[o];O=l[(0x5f-94)];e=(5356136)while((0xba+-65)-0x45)>=O do e-= e e=(5960492)while O<=(3475/0x8b)do e-= e e=(287532)while O<=(0x44-56)do e-= e e=(3688686)while O<=(565/0x71)do e-= e e=(10423875)while O<=((18012/0xe4)-0x4d)do e-= e e=(12247092)while(0x0/42)>=O do e-= e local l=l[K];local o=h[l];for l=l+1,t do y(o,h[l])end;break;end while 4026==(e)/((0x1808-3110))do e=(7326696)while O>(99+-0x62)do e-= e h[l[d]]=a[l[F]];break end while(e)/((3608-0x716))==4084 do h[l[K]]=#h[l[M]];break end;break;end break;end while 3135==(e)/((0x469fb/87))do e=(7284574)while O<=(120-0x75)do e-= e h[l[m]]=h[l[F]]-h[l[c]];break;end while(e)/(((0x1a+-90)+0xb8d))==2518 do e=(4064016)while(0x17c/95)<O do e-= e local o=l[K];local b=h[l[p]];h[o+1]=b;h[o]=b[l[C]];break end while(e)/((0xa221c/234))==1432 do local b=l[L];local o=h[l[P]];h[b+1]=o;h[b]=o[l[w]];break end;break;end break;end break;end while 2469==(e)/((-54+(287928/0xba)))do e=(7815852)while O<=(-0x58+96)do e-= e e=(3115050)while(0x5e+-88)>=O do e-= e if(h[l[m]]~=h[l[w]])then o=o+n;else o=l[P];end;break;end while(e)/((0x8c0+-54))==1425 do e=(239894)while O>(1575/0xe1)do e-= e local e;e=l[L]h[e]=h[e](x(h,e+b,l[H]))o=o+b;l=k[o];h[l[L]][l[P]]=h[l[w]];o=o+b;l=k[o];h[l[K]]=a[l[H]];o=o+b;l=k[o];h[l[L]]=h[l[M]][l[_]];o=o+b;l=k[o];h[l[B]]=l[H];o=o+b;l=k[o];h[l[K]]=l[P];o=o+b;l=k[o];h[l[K]]=l[r];o=o+b;l=k[o];h[l[f]]=l[M];o=o+b;l=k[o];e=l[d]h[e]=h[e](x(h,e+b,l[P]))o=o+b;l=k[o];h[l[L]][l[p]]=h[l[c]];o=o+b;l=k[o];h[l[K]][l[M]]=l[w];o=o+b;l=k[o];h[l[B]]=a[l[F]];o=o+b;l=k[o];h[l[f]]=h[l[P]][l[D]];o=o+b;l=k[o];h[l[K]]=h[l[M]][l[D]];o=o+b;l=k[o];h[l[d]][l[H]]=h[l[U]];o=o+b;l=k[o];h[l[f]][l[M]]=l[C];o=o+b;l=k[o];h[l[B]]=a[l[F]];o=o+b;l=k[o];h[l[m]]=h[l[r]][l[c]];o=o+b;l=k[o];h[l[L]]=l[r];o=o+b;l=k[o];h[l[m]]=l[H];o=o+b;l=k[o];h[l[m]]=l[r];o=o+b;l=k[o];e=l[L]h[e]=h[e](x(h,e+b,l[H]))o=o+b;l=k[o];h[l[f]][l[P]]=h[l[_]];o=o+b;l=k[o];h[l[L]][l[M]]=l[w];o=o+b;l=k[o];h[l[L]][l[P]]=l[D];o=o+b;l=k[o];h[l[B]][l[M]]=h[l[D]];o=o+b;l=k[o];h[l[d]]=a[l[M]];o=o+b;l=k[o];h[l[m]]=h[l[M]][l[C]];o=o+b;l=k[o];h[l[B]]=l[p];o=o+b;l=k[o];h[l[m]]=l[M];o=o+b;l=k[o];h[l[d]]=l[F];o=o+b;l=k[o];e=l[B]h[e]=h[e](x(h,e+b,l[M]))o=o+b;l=k[o];h[l[m]][l[M]]=h[l[U]];o=o+b;l=k[o];h[l[d]]=a[l[r]];o=o+b;l=k[o];h[l[f]]=h[l[p]][l[U]];o=o+b;l=k[o];h[l[f]]=l[p];o=o+b;l=k[o];h[l[B]]=l[r];o=o+b;l=k[o];h[l[L]]=l[p];o=o+b;l=k[o];h[l[B]]=l[M];o=o+b;l=k[o];e=l[K]h[e]=h[e](x(h,e+b,l[F]))o=o+b;l=k[o];h[l[d]][l[P]]=h[l[w]];o=o+b;l=k[o];h[l[B]]=a[l[H]];o=o+b;l=k[o];h[l[B]]=h[l[F]][l[C]];o=o+b;l=k[o];h[l[m]]=l[F];o=o+b;l=k[o];h[l[B]]=l[M];o=o+b;l=k[o];h[l[B]]=l[r];o=o+b;l=k[o];h[l[m]]=l[M];o=o+b;l=k[o];e=l[B]h[e]=h[e](x(h,e+b,l[p]))o=o+b;l=k[o];h[l[m]][l[r]]=h[l[c]];o=o+b;l=k[o];h[l[f]]=a[l[P]];o=o+b;l=k[o];h[l[d]]=h[l[r]][l[_]];o=o+b;l=k[o];h[l[f]]=h[l[P]][l[_]];o=o+b;l=k[o];h[l[d]][l[r]]=h[l[_]];o=o+b;l=k[o];h[l[f]][l[F]]=l[w];o=o+b;l=k[o];h[l[B]]=a[l[H]];o=o+b;l=k[o];h[l[B]]=h[l[r]][l[C]];o=o+b;l=k[o];h[l[f]]=l[r];o=o+b;l=k[o];h[l[L]]=l[M];o=o+b;l=k[o];h[l[B]]=l[P];o=o+b;l=k[o];e=l[m]h[e]=h[e](x(h,e+b,l[p]))o=o+b;l=k[o];h[l[B]][l[H]]=h[l[D]];o=o+b;l=k[o];h[l[f]][l[p]]=l[D];o=o+b;l=k[o];h[l[f]][l[H]]=h[l[w]];o=o+b;l=k[o];h[l[f]][l[r]]=h[l[c]];o=o+b;l=k[o];h[l[d]]=a[l[p]];o=o+b;l=k[o];h[l[m]]=h[l[M]][l[c]];o=o+b;l=k[o];h[l[B]]=l[F];o=o+b;l=k[o];h[l[m]]=l[M];o=o+b;l=k[o];e=l[L]h[e]=h[e](x(h,e+b,l[H]))o=o+b;l=k[o];h[l[d]][l[p]]=h[l[_]];o=o+b;l=k[o];h[l[d]]=a[l[M]];o=o+b;l=k[o];h[l[B]]=h[l[H]][l[c]];o=o+b;l=k[o];h[l[m]]=l[p];o=o+b;l=k[o];h[l[K]]=l[p];o=o+b;l=k[o];h[l[d]]=l[r];o=o+b;l=k[o];e=l[L]h[e]=h[e](x(h,e+b,l[P]))o=o+b;l=k[o];h[l[K]][l[F]]=h[l[c]];o=o+b;l=k[o];h[l[K]][l[H]]=l[C];o=o+b;l=k[o];h[l[K]]=a[l[F]];o=o+b;l=k[o];h[l[L]]=h[l[H]][l[U]];break end while(e)/((-112+0x861))==118 do local b=l[d];local e=h[b]local k=h[b+2];if(k>0)then if(e>h[b+1])then o=l[H];else h[b+3]=e;end elseif(e<h[b+1])then o=l[F];else h[b+3]=e;end break end;break;end break;end while 3564==(e)/((0x8fa+-105))do e=(2052372)while(-45+0x37)>=O do e-= e e=(6460507)while O>(1827/0xcb)do e-= e local k=l[K];local O=l[w];local e=k+2 local k={h[k](h[k+1],h[e])};for l=1,O do h[e+l]=k[l];end;local k=k[1]if k then h[e]=k o=l[p];else o=o+b;end;break end while 2693==(e)/((0x979+-26))do h[l[B]]=h[l[H]][l[c]];break end;break;end while(e)/((0x745+-17))==1113 do e=(2291845)while(0x3d-50)<O do e-= e h[l[m]]=h[l[F]];break end while(e)/((-18+(-34+0x2c3)))==3499 do h[l[B]][l[H]]=l[U];break end;break;end break;end break;end break;end while(e)/((0x1206-2332))==126 do e=(9080658)while((0x9b+-65)/5)>=O do e-= e e=(844596)while(645/0x2b)>=O do e-= e e=(14706625)while O<=(42-0x1d)do e-= e local l=l[L]h[l]=h[l](h[l+n])break;end while(e)/((808375/(247+-0x18)))==4057 do e=(4037874)while O>(0x452/79)do e-= e local e;h[l[d]]=l[r];o=o+b;l=k[o];h[l[K]]=l[r];o=o+b;l=k[o];h[l[m]]=l[M];o=o+b;l=k[o];e=l[K]h[e]=h[e](x(h,e+b,l[P]))o=o+b;l=k[o];h[l[f]][l[F]]=h[l[D]];o=o+b;l=k[o];h[l[d]][l[M]]=l[w];o=o+b;l=k[o];h[l[f]]=a[l[H]];o=o+b;l=k[o];h[l[d]]=h[l[F]][l[C]];o=o+b;l=k[o];h[l[m]]=l[P];o=o+b;l=k[o];h[l[m]]=l[M];break end while(e)/((5146-0xa20))==1581 do N[l[p]]=h[l[d]];break end;break;end break;end while(e)/(((0xd70-1747)-884))==1044 do e=(2744828)while O<=(0x75-101)do e-= e h[l[f]]=h[l[F]][h[l[C]]];break;end while 1772==(e)/((109979/0x47))do e=(6577724)while O>(0xd37/199)do e-= e local k=l[K];local O=l[w];local e=k+2 local k={h[k](h[k+1],h[e])};for l=1,O do h[e+l]=k[l];end;local k=k[1]if k then h[e]=k o=l[M];else o=o+b;end;break end while(e)/((8107-0xfef))==1633 do a[l[M]]=h[l[B]];o=o+b;l=k[o];h[l[B]]={};o=o+b;l=k[o];h[l[d]]={};o=o+b;l=k[o];a[l[P]]=h[l[L]];o=o+b;l=k[o];h[l[f]]=a[l[H]];o=o+b;l=k[o];if(h[l[f]]==l[w])then o=o+n;else o=l[r];end;break end;break;end break;end break;end while(e)/((3887+-0x24))==2358 do e=(6086906)while(0x111/13)>=O do e-= e e=(1247540)while O<=(122-0x67)do e-= e local e;local O;local D,C;local i;local e;h[l[B]]=l[M];o=o+b;l=k[o];e=l[f]h[e](h[e+n])o=o+b;l=k[o];h[l[m]]=a[l[p]];o=o+b;l=k[o];h[l[L]]=h[l[r]][l[w]];o=o+b;l=k[o];h[l[B]]=l[F];o=o+b;l=k[o];h[l[K]]=l[M];o=o+b;l=k[o];h[l[B]]=l[H];o=o+b;l=k[o];h[l[d]]=l[P];o=o+b;l=k[o];h[l[m]]=l[r];o=o+b;l=k[o];h[l[K]]=l[r];o=o+b;l=k[o];h[l[L]]=l[F];o=o+b;l=k[o];h[l[m]]=l[M];o=o+b;l=k[o];h[l[f]]=l[r];o=o+b;l=k[o];h[l[d]]=l[p];o=o+b;l=k[o];h[l[f]]=l[H];o=o+b;l=k[o];h[l[L]]=l[p];o=o+b;l=k[o];e=l[f]h[e]=h[e](x(h,e+b,l[H]))o=o+b;l=k[o];h[l[K]][l[M]]=h[l[U]];o=o+b;l=k[o];h[l[K]]=a[l[H]];o=o+b;l=k[o];h[l[f]]=l[H];o=o+b;l=k[o];e=l[B]h[e](h[e+n])o=o+b;l=k[o];h[l[m]]=a[l[M]];o=o+b;l=k[o];h[l[f]]=a[l[r]];o=o+b;l=k[o];e=l[f];i=h[l[M]];h[e+1]=i;h[e]=i[l[c]];o=o+b;l=k[o];h[l[d]]=l[H];o=o+b;l=k[o];e=l[m]h[e]=h[e](x(h,e+b,l[F]))o=o+b;l=k[o];e=l[K];i=h[l[F]];h[e+1]=i;h[e]=i[l[_]];o=o+b;l=k[o];e=l[B]D,C=S(h[e](h[e+n]))t=C+e-b O=0;for l=e,t do O=O+b;h[l]=D[O];end;o=o+b;l=k[o];e=l[d]D={h[e](x(h,e+1,t))};O=0;for l=e,l[U]do O=O+b;h[l]=D[O];end o=o+b;l=k[o];o=l[M];break;end while 380==(e)/((3401+-0x76))do e=(9511020)while(0xc58/158)<O do e-= e local b=l[d];local e=h[b]local k=h[b+2];if(k>0)then if(e>h[b+1])then o=l[M];else h[b+3]=e;end elseif(e<h[b+1])then o=l[P];else h[b+3]=e;end break end while(e)/((273942/0x59))==3090 do h[l[f]]=u(s[l[H]],nil,a);break end;break;end break;end while(e)/((-0x57+2294))==2758 do e=(225108)while(107-0x54)>=O do e-= e e=(5965680)while(155-0x85)<O do e-= e if(h[l[f]]==l[D])then o=o+n;else o=l[M];end;break end while(e)/((0x1f89-4053))==1484 do local l=l[K]h[l](h[l+n])break end;break;end while(e)/((2907-0x5b8))==156 do e=(9663680)while O>(0xab0/114)do e-= e local l=l[K]h[l]=h[l](h[l+n])break end while(e)/((5347-0xaa1))==3680 do local o=l[B]h[o](x(h,o+n,l[p]))break end;break;end break;end break;end break;end break;end while(e)/(((0x868+-87)+-0x27))==2942 do e=(342720)while O<=(0x6c-70)do e-= e e=(388416)while(-54+0x55)>=O do e-= e e=(10021005)while((0x187-213)-150)>=O do e-= e e=(189848)while(145-0x77)>=O do e-= e h[l[d]][l[p]]=l[U];o=o+b;l=k[o];h[l[L]]=a[l[F]];o=o+b;l=k[o];h[l[K]]=h[l[r]][l[D]];o=o+b;l=k[o];h[l[m]]=h[l[P]][l[C]];o=o+b;l=k[o];h[l[m]][l[H]]=h[l[w]];o=o+b;l=k[o];h[l[B]][l[F]]=l[_];o=o+b;l=k[o];h[l[m]]=a[l[P]];o=o+b;l=k[o];h[l[f]]=h[l[P]][l[U]];o=o+b;l=k[o];h[l[f]]=l[M];o=o+b;l=k[o];h[l[K]]=l[p];break;end while 152==(e)/((291017/0xe9))do e=(5560150)while O>(148-0x79)do e-= e local b=l[B];local k=h[b+2];local e=h[b]+k;h[b]=e;if(k>0)then if(e<=h[b+1])then o=l[F];h[b+3]=e;end elseif(e>=h[b+1])then o=l[F];h[b+3]=e;end break end while(e)/(((0x18a6-3199)-0x632))==3646 do local e;h[l[d]]=h[l[H]][l[c]];o=o+b;l=k[o];h[l[m]]=h[l[F]][l[c]];o=o+b;l=k[o];h[l[f]]=h[l[r]][l[c]];o=o+b;l=k[o];a[l[F]]=h[l[B]];o=o+b;l=k[o];h[l[d]]=a[l[p]];o=o+b;l=k[o];h[l[f]]=h[l[H]][l[U]];o=o+b;l=k[o];h[l[d]]=h[l[r]][l[_]];o=o+b;l=k[o];h[l[L]]=h[l[P]][l[_]];o=o+b;l=k[o];h[l[K]]=h[l[F]][l[w]];o=o+b;l=k[o];h[l[d]]=h[l[M]][l[D]];o=o+b;l=k[o];h[l[f]][l[M]]=h[l[D]];o=o+b;l=k[o];h[l[K]]=a[l[p]];o=o+b;l=k[o];h[l[L]]=l[P];o=o+b;l=k[o];e=l[B]h[e](h[e+n])o=o+b;l=k[o];h[l[d]]=a[l[r]];o=o+b;l=k[o];h[l[f]]=h[l[F]][l[C]];o=o+b;l=k[o];h[l[m]]=h[l[r]][l[w]];o=o+b;l=k[o];h[l[f]]=h[l[r]][l[w]];o=o+b;l=k[o];h[l[B]]=h[l[H]][l[c]];o=o+b;l=k[o];h[l[L]]=h[l[r]][l[c]];o=o+b;l=k[o];h[l[K]][l[r]]=h[l[D]];break end;break;end break;end while 2683==(e)/((0x1da2-3851))do e=(643996)while O<=(78-0x31)do e-= e if h[l[K]]then o=o+b;else o=l[p];end;break;end while 524==(e)/((0x9d7-1290))do e=(7083694)while O>(0x51-51)do e-= e if(h[l[d]]~=l[_])then o=o+n;else o=l[r];end;break end while(e)/((0x7abfa/202))==2846 do local o=l[L]h[o]=h[o](x(h,o+b,l[H]))break end;break;end break;end break;end while(e)/((7655-0xf07))==102 do e=(2471368)while O<=(75+-0x29)do e-= e e=(4209408)while O<=(0x1ba0/221)do e-= e h[l[f]]=h[l[r]];break;end while(e)/((-0x2d+1263))==3456 do e=(2843272)while(0x5a+-57)<O do e-= e h[l[d]]=#h[l[P]];break end while(e)/((4712-0x940))==1213 do local e;h[l[L]]=h[l[M]];o=o+b;l=k[o];h[l[L]]=h[l[F]][l[w]];o=o+b;l=k[o];h[l[m]]=l[p];o=o+b;l=k[o];e=l[d]h[e](x(h,e+n,l[P]))o=o+b;l=k[o];h[l[K]]=a[l[F]];o=o+b;l=k[o];h[l[L]]=l[H];o=o+b;l=k[o];e=l[K]h[e](h[e+n])o=o+b;l=k[o];h[l[f]]=a[l[F]];o=o+b;l=k[o];h[l[K]]=h[l[r]];o=o+b;l=k[o];h[l[K]]=h[l[p]][l[_]];o=o+b;l=k[o];h[l[d]]=l[p];o=o+b;l=k[o];e=l[B]h[e](x(h,e+n,l[r]))o=o+b;l=k[o];o=l[M];break end;break;end break;end while 1832==(e)/((0x39a2b/(298+-0x7b)))do e=(1103560)while(0x9a+(-0x70-6))>=O do e-= e e=(1997634)while(-127+0xa2)<O do e-= e local l=l[B]h[l]=h[l](x(h,l+b,t))break end while(e)/((3070-0x629))==1338 do local K;local O;local M;local e;h[l[m]]=a[l[H]];o=o+b;l=k[o];h[l[L]]=h[l[H]][l[c]];o=o+b;l=k[o];e=l[d];M=h[l[p]];h[e+1]=M;h[e]=M[l[c]];o=o+b;l=k[o];h[l[d]]=h[l[F]];o=o+b;l=k[o];h[l[L]]=h[l[r]];o=o+b;l=k[o];e=l[f]h[e]=h[e](x(h,e+b,l[H]))o=o+b;l=k[o];e=l[B];M=h[l[F]];h[e+1]=M;h[e]=M[l[_]];o=o+b;l=k[o];e=l[f]h[e]=h[e](h[e+n])o=o+b;l=k[o];O={h,l};O[n][O[i][m]]=O[b][O[i][D]]+O[n][O[i][H]];o=o+b;l=k[o];h[l[d]]=h[l[p]]%l[w];o=o+b;l=k[o];e=l[m]h[e]=h[e](h[e+n])o=o+b;l=k[o];M=l[P];K=h[M]for l=M+1,l[_]do K=K..h[l];end;h[l[B]]=K;o=o+b;l=k[o];O={h,l};O[n][O[i][f]]=O[b][O[i][w]]+O[n][O[i][r]];o=o+b;l=k[o];h[l[B]]=h[l[r]]%l[_];break end;break;end while(e)/(((4001-0x7fb)-0x3fa))==1174 do e=(8937320)while(75+-0x26)<O do e-= e local l=l[L];local o=h[l];for l=l+1,t do y(o,h[l])end;break end while 2360==(e)/((-119+0xf42))do h[l[f]]=N[l[P]];break end;break;end break;end break;end break;end while(e)/((750-0x19a))==1008 do e=(7668760)while O<=(106-0x3d)do e-= e e=(86108)while O<=(0x74-(0xa1+-86))do e-= e e=(6777547)while(0xc8-161)>=O do e-= e local f=s[l[P]];local O;local b={};O=Q({},{__index=function(o,l)local l=b[l];return l[1][l[2]];end,__newindex=function(h,l,o)local l=b[l]l[1][l[2]]=o;end;});for e=1,l[w]do o=o+n;local l=k[o];if l[(0x7b-122)]==32 then b[e-1]={h,l[M]};else b[e-1]={N,l[r]};end;v[#v+1]=b;end;h[l[m]]=u(f,O,a);break;end while(e)/((688919/0xfd))==2489 do e=(3929400)while O>(0xb3-(0x5b38/168))do e-= e o=l[H];break end while 3540==(e)/((217560/0xc4))do local e;local O;local i,D;local L;local e;h[l[m]]=a[l[M]];o=o+b;l=k[o];h[l[d]]=h[l[p]][l[_]];o=o+b;l=k[o];h[l[f]]=h[l[F]][l[c]];o=o+b;l=k[o];h[l[d]]=h[l[M]][l[C]];o=o+b;l=k[o];h[l[B]]=h[l[M]][l[_]];o=o+b;l=k[o];h[l[B]]=a[l[M]];o=o+b;l=k[o];h[l[K]]=a[l[r]];o=o+b;l=k[o];e=l[B];L=h[l[P]];h[e+1]=L;h[e]=L[l[w]];o=o+b;l=k[o];h[l[K]]=l[H];o=o+b;l=k[o];e=l[f]h[e]=h[e](x(h,e+b,l[F]))o=o+b;l=k[o];h[l[K]]=h[l[r]][l[U]];o=o+b;l=k[o];e=l[K];L=h[l[p]];h[e+1]=L;h[e]=L[l[U]];o=o+b;l=k[o];e=l[m]i,D=S(h[e](h[e+n]))t=D+e-b O=0;for l=e,t do O=O+b;h[l]=i[O];end;o=o+b;l=k[o];e=l[f]i={h[e](x(h,e+1,t))};O=0;for l=e,l[c]do O=O+b;h[l]=i[O];end o=o+b;l=k[o];o=l[P];break end;break;end break;end while 44==(e)/((395314/0xca))do e=(13208642)while(-40+0x53)>=O do e-= e e=(7404705)while O>(8946/0xd5)do e-= e h[l[K]]=h[l[H]]-h[l[U]];break end while 2137==(e)/((609840/0xb0))do h[l[B]]=(l[p]~=0);break end;break;end while(e)/((68019/0x15))==4078 do e=(6302280)while(-0x2f+91)<O do e-= e local l={h,l};l[n][l[i][K]]=l[b][l[i][C]]+l[n][l[i][P]];break end while 3480==(e)/((251729/0x8b))do h[l[B]][l[H]]=h[l[U]];break end;break;end break;end break;end while(e)/((0x1420-2600))==3005 do e=(1629012)while(0xb4-132)>=O do e-= e e=(2048448)while O<=(166+-0x78)do e-= e local l=l[m]h[l]=h[l](x(h,l+b,t))break;end while 681==(e)/((0x17a1-3041))do e=(1025325)while O>((0xeba+-57)/79)do e-= e if(h[l[K]]==h[l[U]])then o=o+n;else o=l[r];end;break end while 2205==(e)/((-0x7a+587))do local e;h[l[K]][l[M]]=h[l[C]];o=o+b;l=k[o];h[l[K]][l[F]]=h[l[c]];o=o+b;l=k[o];h[l[K]]=a[l[p]];o=o+b;l=k[o];h[l[B]]=h[l[M]][l[_]];o=o+b;l=k[o];h[l[d]]=l[H];o=o+b;l=k[o];h[l[f]]=l[P];o=o+b;l=k[o];e=l[d]h[e]=h[e](x(h,e+b,l[r]))o=o+b;l=k[o];h[l[K]][l[H]]=h[l[U]];o=o+b;l=k[o];h[l[d]][l[M]]=h[l[C]];o=o+b;l=k[o];h[l[K]][l[H]]=l[U];o=o+b;l=k[o];h[l[d]][l[F]]=h[l[c]];o=o+b;l=k[o];h[l[f]]=a[l[M]];o=o+b;l=k[o];h[l[m]]=h[l[F]][l[D]];o=o+b;l=k[o];h[l[L]]=l[P];o=o+b;l=k[o];h[l[m]]=l[M];o=o+b;l=k[o];h[l[d]]=l[r];o=o+b;l=k[o];e=l[L]h[e]=h[e](x(h,e+b,l[F]))o=o+b;l=k[o];h[l[f]][l[M]]=h[l[_]];o=o+b;l=k[o];h[l[L]][l[P]]=l[_];o=o+b;l=k[o];h[l[K]]=a[l[P]];o=o+b;l=k[o];h[l[L]]=h[l[P]][l[c]];o=o+b;l=k[o];h[l[L]]=l[r];o=o+b;l=k[o];h[l[K]]=l[M];o=o+b;l=k[o];h[l[f]]=l[r];o=o+b;l=k[o];h[l[B]]=l[M];o=o+b;l=k[o];e=l[d]h[e]=h[e](x(h,e+b,l[p]))o=o+b;l=k[o];h[l[m]][l[P]]=h[l[C]];o=o+b;l=k[o];h[l[L]]=a[l[r]];o=o+b;l=k[o];h[l[B]]=h[l[M]][l[C]];o=o+b;l=k[o];h[l[f]]=l[H];o=o+b;l=k[o];h[l[d]]=l[M];o=o+b;l=k[o];h[l[K]]=l[P];o=o+b;l=k[o];h[l[f]]=l[p];o=o+b;l=k[o];e=l[f]h[e]=h[e](x(h,e+b,l[F]))o=o+b;l=k[o];h[l[m]][l[F]]=h[l[D]];o=o+b;l=k[o];h[l[f]][l[F]]=l[C];o=o+b;l=k[o];h[l[L]]=a[l[r]];o=o+b;l=k[o];h[l[m]]=h[l[M]][l[_]];o=o+b;l=k[o];h[l[L]]=h[l[p]][l[U]];o=o+b;l=k[o];h[l[f]][l[M]]=h[l[c]];o=o+b;l=k[o];h[l[L]][l[H]]=l[w];o=o+b;l=k[o];h[l[K]]=a[l[p]];o=o+b;l=k[o];h[l[m]]=h[l[F]][l[D]];o=o+b;l=k[o];h[l[d]]=l[H];o=o+b;l=k[o];h[l[L]]=l[p];o=o+b;l=k[o];h[l[B]]=l[F];o=o+b;l=k[o];e=l[d]h[e]=h[e](x(h,e+b,l[M]))o=o+b;l=k[o];h[l[K]][l[M]]=h[l[C]];o=o+b;l=k[o];h[l[f]][l[r]]=l[_];o=o+b;l=k[o];h[l[f]][l[H]]=l[U];o=o+b;l=k[o];h[l[m]][l[M]]=l[w];o=o+b;l=k[o];h[l[f]][l[M]]=h[l[c]];o=o+b;l=k[o];h[l[m]][l[F]]=h[l[U]];o=o+b;l=k[o];h[l[m]]=a[l[H]];o=o+b;l=k[o];h[l[L]]=h[l[P]][l[U]];o=o+b;l=k[o];h[l[K]]=l[P];o=o+b;l=k[o];h[l[d]]=l[P];o=o+b;l=k[o];e=l[m]h[e]=h[e](x(h,e+b,l[r]))o=o+b;l=k[o];h[l[B]][l[r]]=h[l[w]];o=o+b;l=k[o];h[l[B]]=a[l[H]];o=o+b;l=k[o];h[l[m]]=h[l[P]][l[C]];o=o+b;l=k[o];h[l[B]]=l[p];o=o+b;l=k[o];h[l[B]]=l[p];o=o+b;l=k[o];h[l[f]]=l[p];o=o+b;l=k[o];e=l[f]h[e]=h[e](x(h,e+b,l[F]))o=o+b;l=k[o];h[l[d]][l[P]]=h[l[U]];o=o+b;l=k[o];h[l[m]][l[r]]=l[U];o=o+b;l=k[o];h[l[B]]=a[l[H]];o=o+b;l=k[o];h[l[m]]=h[l[P]][l[C]];o=o+b;l=k[o];h[l[m]]=l[p];o=o+b;l=k[o];h[l[d]]=l[p];o=o+b;l=k[o];h[l[B]]=l[r];o=o+b;l=k[o];e=l[d]h[e]=h[e](x(h,e+b,l[H]))o=o+b;l=k[o];h[l[m]][l[p]]=h[l[c]];o=o+b;l=k[o];h[l[m]][l[r]]=l[w];o=o+b;l=k[o];h[l[f]]=a[l[P]];o=o+b;l=k[o];h[l[B]]=h[l[F]][l[_]];o=o+b;l=k[o];h[l[f]]=l[P];o=o+b;l=k[o];h[l[m]]=l[M];o=o+b;l=k[o];h[l[f]]=l[r];break end;break;end break;end while(e)/((0x3c9+-23))==1722 do e=(1313267)while(0x8b-89)>=O do e-= e e=(11210220)while(135+-0x56)<O do e-= e h[l[K]]=h[l[p]]%l[U];break end while(e)/((-0x51+3021))==3813 do h[l[K]]=a[l[F]];o=o+b;l=k[o];h[l[m]]=h[l[p]][l[w]];o=o+b;l=k[o];h[l[d]]={};o=o+b;l=k[o];h[l[B]]=a[l[M]];o=o+b;l=k[o];h[l[L]]=h[l[H]][l[_]];o=o+b;l=k[o];h[l[B]]=l[p];o=o+b;l=k[o];h[l[m]]=a[l[P]];o=o+b;l=k[o];h[l[L]]=h[l[p]][l[c]];o=o+b;l=k[o];h[l[f]]=l[F];o=o+b;l=k[o];h[l[f]]=l[M];break end;break;end while(e)/((-0x11+1156))==1153 do e=(7164314)while O>(0x91-94)do e-= e local e;h[l[L]]=l[r];o=o+b;l=k[o];e=l[d]h[e]=h[e](x(h,e+b,l[r]))o=o+b;l=k[o];h[l[f]][l[F]]=h[l[U]];o=o+b;l=k[o];h[l[f]]=a[l[P]];o=o+b;l=k[o];h[l[B]]=h[l[M]][l[c]];o=o+b;l=k[o];h[l[L]]=l[P];o=o+b;l=k[o];h[l[K]]=l[r];o=o+b;l=k[o];h[l[K]]=l[F];o=o+b;l=k[o];h[l[f]]=l[M];o=o+b;l=k[o];e=l[L]h[e]=h[e](x(h,e+b,l[p]))break end while(e)/((-124+0xaad))==2746 do h[l[d]][h[l[P]]]=h[l[D]];break end;break;end break;end break;end break;end break;end break;end while(e)/((228954/0x42))==1544 do e=(2300228)while O<=(-110+0xbc)do e-= e e=(2770566)while O<=((108680/0x8)/0xd1)do e-= e e=(42657)while(170-0x70)>=O do e-= e e=(7576800)while O<=(0xb9-130)do e-= e e=(8984161)while O<=(9752/(22264/0x79))do e-= e local l=l[f]h[l](h[l+n])break;end while(e)/((0x149d-2660))==3433 do e=(1159767)while((-56+-0x37)+165)<O do e-= e local l=l[L]local e,o=S(h[l](h[l+n]))t=o+l-b local o=0;for l=l,t do o=o+b;h[l]=e[o];end;break end while(e)/((949635/0xeb))==287 do local e;a[l[p]]=h[l[m]];o=o+b;l=k[o];h[l[m]]=a[l[P]];o=o+b;l=k[o];h[l[f]]=h[l[P]][l[w]];o=o+b;l=k[o];h[l[L]]=l[H];o=o+b;l=k[o];e=l[f]h[e]=h[e](h[e+n])o=o+b;l=k[o];h[l[B]]=a[l[F]];o=o+b;l=k[o];h[l[B]]=h[l[r]][l[w]];o=o+b;l=k[o];h[l[B]]=l[P];o=o+b;l=k[o];e=l[m]h[e]=h[e](h[e+n])o=o+b;l=k[o];h[l[L]]=a[l[p]];o=o+b;l=k[o];h[l[m]]=h[l[M]][l[_]];o=o+b;l=k[o];h[l[d]]=l[P];o=o+b;l=k[o];e=l[d]h[e]=h[e](h[e+n])o=o+b;l=k[o];h[l[d]]=a[l[p]];o=o+b;l=k[o];h[l[L]]=h[l[p]][l[w]];o=o+b;l=k[o];h[l[f]]=l[r];o=o+b;l=k[o];e=l[f]h[e]=h[e](h[e+n])o=o+b;l=k[o];h[l[L]]=a[l[F]];o=o+b;l=k[o];h[l[K]]=h[l[H]][l[U]];o=o+b;l=k[o];h[l[L]]=l[M];o=o+b;l=k[o];e=l[K]h[e]=h[e](h[e+n])o=o+b;l=k[o];h[l[d]]=a[l[p]];o=o+b;l=k[o];h[l[m]]=h[l[H]][l[D]];o=o+b;l=k[o];h[l[d]]=l[F];o=o+b;l=k[o];e=l[B]h[e]=h[e](h[e+n])o=o+b;l=k[o];h[l[B]]=a[l[P]];o=o+b;l=k[o];h[l[d]]=h[l[P]][l[D]];o=o+b;l=k[o];h[l[f]]=l[F];o=o+b;l=k[o];e=l[L]h[e]=h[e](h[e+n])o=o+b;l=k[o];h[l[d]]=a[l[p]];o=o+b;l=k[o];h[l[m]]=h[l[F]][l[w]];o=o+b;l=k[o];h[l[K]]=l[F];o=o+b;l=k[o];e=l[f]h[e]=h[e](h[e+n])o=o+b;l=k[o];h[l[L]]=a[l[M]];o=o+b;l=k[o];h[l[K]]=h[l[H]][l[c]];o=o+b;l=k[o];h[l[K]]=l[P];o=o+b;l=k[o];e=l[d]h[e]=h[e](h[e+n])o=o+b;l=k[o];h[l[L]]=a[l[M]];o=o+b;l=k[o];h[l[B]]=h[l[p]][l[w]];o=o+b;l=k[o];h[l[d]]=l[p];o=o+b;l=k[o];e=l[B]h[e]=h[e](h[e+n])o=o+b;l=k[o];h[l[K]][l[F]]=l[D];o=o+b;l=k[o];h[l[m]]=a[l[F]];o=o+b;l=k[o];h[l[B]]=h[l[H]][l[C]];o=o+b;l=k[o];h[l[B]][l[F]]=h[l[c]];o=o+b;l=k[o];h[l[m]][l[p]]=l[c];o=o+b;l=k[o];h[l[L]][l[P]]=h[l[_]];o=o+b;l=k[o];h[l[d]]=a[l[P]];o=o+b;l=k[o];h[l[K]]=h[l[p]][l[c]];o=o+b;l=k[o];h[l[B]]=l[F];o=o+b;l=k[o];h[l[L]]=l[p];o=o+b;l=k[o];h[l[f]]=l[H];o=o+b;l=k[o];e=l[K]h[e]=h[e](x(h,e+b,l[F]))o=o+b;l=k[o];h[l[K]][l[F]]=h[l[c]];o=o+b;l=k[o];h[l[m]]=a[l[M]];o=o+b;l=k[o];h[l[d]]=h[l[p]][l[_]];o=o+b;l=k[o];h[l[f]]=l[H];o=o+b;l=k[o];h[l[L]]=l[F];o=o+b;l=k[o];h[l[d]]=l[M];o=o+b;l=k[o];e=l[B]h[e]=h[e](x(h,e+b,l[P]))o=o+b;l=k[o];h[l[B]][l[P]]=h[l[_]];o=o+b;l=k[o];h[l[K]][l[M]]=l[w];o=o+b;l=k[o];h[l[B]]=a[l[P]];o=o+b;l=k[o];h[l[B]]=h[l[M]][l[C]];o=o+b;l=k[o];h[l[d]]=l[r];o=o+b;l=k[o];h[l[B]]=l[p];o=o+b;l=k[o];h[l[f]]=l[F];o=o+b;l=k[o];h[l[L]]=l[F];o=o+b;l=k[o];e=l[B]h[e]=h[e](x(h,e+b,l[M]))o=o+b;l=k[o];h[l[B]][l[p]]=h[l[c]];o=o+b;l=k[o];h[l[f]]=a[l[P]];o=o+b;l=k[o];h[l[K]]=h[l[P]][l[D]];o=o+b;l=k[o];h[l[d]]=l[H];o=o+b;l=k[o];h[l[d]]=l[H];o=o+b;l=k[o];h[l[f]]=l[P];o=o+b;l=k[o];h[l[K]]=l[r];o=o+b;l=k[o];e=l[B]h[e]=h[e](x(h,e+b,l[p]))o=o+b;l=k[o];h[l[f]][l[H]]=h[l[_]];o=o+b;l=k[o];h[l[m]][l[H]]=l[D];o=o+b;l=k[o];h[l[K]][l[P]]=l[D];break end;break;end break;end while 2870==(e)/((2764+-0x7c))do e=(7122582)while(170-0x72)>=O do e-= e a[l[P]]=h[l[B]];break;end while(e)/((4912-0x9bb))==2942 do e=(492014)while O>(0x90-87)do e-= e local b=l[m];local k=h[b+2];local e=h[b]+k;h[b]=e;if(k>0)then if(e<=h[b+1])then o=l[r];h[b+3]=e;end elseif(e>=h[b+1])then o=l[F];h[b+3]=e;end break end while 998==(e)/((1048-0x22b))do h[l[L]]=h[l[M]][l[D]];break end;break;end break;end break;end while 241==(e)/(((24614/0x3e)-220))do e=(3724380)while(0xd2-149)>=O do e-= e e=(3339684)while(94+-0x23)>=O do e-= e local l=l[L]local e,o=S(h[l](h[l+n]))t=o+l-b local o=0;for l=l,t do o=o+b;h[l]=e[o];end;break;end while(e)/((-82+0x3b5))==3852 do e=(9492868)while(202-0x8e)<O do e-= e local b=l[P];local o=h[b]for l=b+1,l[D]do o=o..h[l];end;h[l[B]]=o;break end while 3773==(e)/((578680/0xe6))do h[l[L]]={};break end;break;end break;end while(e)/((0xc15c/50))==3762 do e=(493812)while O<=(0x80+-65)do e-= e e=(6210597)while O>(110+-0x30)do e-= e if(h[l[f]]~=l[w])then o=o+n;else o=l[r];end;break end while(e)/((3081+-0x6c))==2089 do N[l[F]]=h[l[m]];break end;break;end while 1892==(e)/(((-32+0x264)-0x13f))do e=(434910)while O>(0x2800/160)do e-= e h[l[f]]=N[l[M]];o=o+b;l=k[o];h[l[B]]=#h[l[p]];o=o+b;l=k[o];N[l[p]]=h[l[L]];o=o+b;l=k[o];h[l[m]]=N[l[p]];o=o+b;l=k[o];h[l[K]]=#h[l[p]];o=o+b;l=k[o];N[l[H]]=h[l[m]];o=o+b;l=k[o];do return end;break end while(e)/((0x9bdc/50))==545 do if(h[l[K]]==l[U])then o=o+n;else o=l[H];end;break end;break;end break;end break;end break;end while 1227==(e)/((-0x72+2372))do e=(2449902)while O<=(241-0xaa)do e-= e e=(1558227)while O<=(14688/0xd8)do e-= e e=(397836)while(172+(-146+0x28))>=O do e-= e if h[l[L]]then o=o+b;else o=l[p];end;break;end while(e)/((0x425-547))==774 do e=(14601951)while O>(0xee-171)do e-= e h[l[B]]=(l[M]~=0);o=o+n;break end while 3969==(e)/((783627/0xd5))do local o=l[L]local e,l=S(h[o](x(h,o+1,l[H])))t=l+o-1 local l=0;for o=o,t do l=l+b;h[o]=e[l];end;break end;break;end break;end while(e)/((0x102f-(4259-0x879)))==759 do e=(456322)while(13455/0xc3)>=O do e-= e h[l[f]]=h[l[P]]%l[c];break;end while(e)/((52246/0xad))==1511 do e=(2251144)while O>(180-0x6e)do e-= e h[l[m]]=N[l[H]];break end while 659==(e)/((0xc9d30/242))do local l=l[L]local e,o=S(h[l](x(h,l+b,t)))t=o+l-n local o=0;for l=l,t do o=o+b;h[l]=e[o];end;break end;break;end break;end break;end while(e)/(((63+-0x59)+0x791))==1282 do e=(1073271)while(201-0x7f)>=O do e-= e e=(3707508)while(270-0xc6)>=O do e-= e h[l[f]]=l[p];break;end while(e)/((0x66a+-46))==2323 do e=(5268840)while(0x1f5e/110)<O do e-= e local b=l[P];local o=h[b]for l=b+1,l[C]do o=o..h[l];end;h[l[L]]=o;break end while 1660==(e)/((6375-0xc81))do if(h[l[f]]~=h[l[c]])then o=o+n;else o=l[p];end;break end;break;end break;end while(e)/((2183-0x476))==1031 do e=(2582916)while O<=(0xae-98)do e-= e e=(6778728)while O>(167+(-134+0x2a))do e-= e local e=l[L]local k={h[e](x(h,e+1,t))};local o=0;for l=e,l[U]do o=o+b;h[l]=k[o];end break end while 3804==(e)/((0x14e2/3))do if(h[l[m]]==h[l[U]])then o=o+n;else o=l[H];end;break end;break;end while(e)/((2448-0x504))==2219 do e=(1093095)while(0xc4-119)<O do e-= e local f;local O;local e;h[l[d]]=l[r];o=o+b;l=k[o];h[l[d]]=l[p];o=o+b;l=k[o];h[l[m]]=#h[l[M]];o=o+b;l=k[o];h[l[B]]=l[p];o=o+b;l=k[o];e=l[L];O=h[e]f=h[e+2];if(f>0)then if(O>h[e+1])then o=l[M];else h[e+3]=O;end elseif(O<h[e+1])then o=l[p];else h[e+3]=O;end break end while 2699==(e)/((529+-0x7c))do h[l[d]]=(l[P]~=0);o=o+n;break end;break;end break;end break;end break;end break;end while(e)/((0xb81+-37))==791 do e=(4072300)while O<=(-75+0xa6)do e-= e e=(9034225)while(0xae+-90)>=O do e-= e e=(4270896)while(0x2046/102)>=O do e-= e e=(1409752)while O<=(-0x65+180)do e-= e local P;local a,p;local O;local e;e=l[K];O=h[l[M]];h[e+1]=O;h[e]=O[l[U]];o=o+b;l=k[o];e=l[m]h[e]=h[e](h[e+n])o=o+b;l=k[o];e=l[f];O=h[l[M]];h[e+1]=O;h[e]=O[l[U]];o=o+b;l=k[o];h[l[m]]=N[l[F]];o=o+b;l=k[o];h[l[f]]=h[l[H]][l[_]];o=o+b;l=k[o];e=l[K];O=h[l[M]];h[e+1]=O;h[e]=O[l[C]];o=o+b;l=k[o];e=l[B]a,p=S(h[e](h[e+n]))t=p+e-b P=0;for l=e,t do P=P+b;h[l]=a[P];end;o=o+b;l=k[o];e=l[L]h[e]=h[e](x(h,e+b,t))o=o+b;l=k[o];if not h[l[d]]then o=o+n;else o=l[r];end;break;end while(e)/((-0x4d+2581))==563 do e=(6108860)while(0x3840/180)<O do e-= e do return h[l[B]]end break end while 3340==(e)/((-0x1a+1855))do h[l[d]]=(l[H]~=0);break end;break;end break;end while 1784==(e)/((107730/0x2d))do e=(1958502)while(0x4a50/232)>=O do e-= e local o=l[f]h[o]=h[o](x(h,o+b,l[p]))break;end while(e)/((0x15ce-2839))==714 do e=(6530667)while O>(178+-0x5f)do e-= e local l=l[d]local e,o=S(h[l](x(h,l+b,t)))t=o+l-n local o=0;for l=l,t do o=o+b;h[l]=e[o];end;break end while(e)/((3810-0x79f))==3513 do h[l[K]]=h[l[H]][h[l[U]]];break end;break;end break;end break;end while(e)/((0x1373-2514))==3665 do e=(4052595)while O<=((0xa861/185)-0x92)do e-= e e=(4482159)while O<=(-60+0x91)do e-= e local o=l[f]local k={h[o](x(h,o+1,t))};local e=0;for l=o,l[C]do e=e+b;h[l]=k[e];end break;end while(e)/((0x12cb-2468))==1913 do e=(2969900)while O>(-119+0xcd)do e-= e local O;local n,p;local e;e=l[d]n,p=S(h[e](x(h,e+1,l[r])))t=p+e-1 O=0;for l=e,t do O=O+b;h[l]=n[O];end;o=o+b;l=k[o];e=l[B]h[e]=h[e](x(h,e+b,t))o=o+b;l=k[o];h[l[d]]=a[l[P]];o=o+b;l=k[o];h[l[f]]=h[l[P]][l[D]];o=o+b;l=k[o];h[l[L]]=l[P];o=o+b;l=k[o];h[l[L]]=a[l[P]];o=o+b;l=k[o];h[l[K]]=h[l[r]][l[c]];o=o+b;l=k[o];h[l[B]]=l[M];o=o+b;l=k[o];h[l[K]]=l[M];o=o+b;l=k[o];h[l[m]]=l[F];break end while 3494==(e)/((5100/(101-0x5f)))do local O;local e;e=l[d]h[e]=h[e](x(h,e+b,l[P]))o=o+b;l=k[o];h[l[d]][l[P]]=h[l[D]];o=o+b;l=k[o];h[l[m]][l[P]]=l[U];o=o+b;l=k[o];h[l[f]][l[F]]=l[w];o=o+b;l=k[o];h[l[f]]=h[l[H]][l[C]];o=o+b;l=k[o];e=l[L];O=h[l[P]];h[e+1]=O;h[e]=O[l[_]];break end;break;end break;end while 1095==(e)/(((-0x63+39)+3761))do e=(7946850)while O<=(137+-0x30)do e-= e e=(5023487)while O>(0x2d60/132)do e-= e o=l[F];break end while(e)/((0x65061/207))==2513 do local l={h,l};l[n][l[i][f]]=l[b][l[i][c]]+l[n][l[i][P]];break end;break;end while 3418==(e)/(((479058-0x3a7df)/103))do e=(3247136)while((0x24d4e8/149)/180)<O do e-= e h[l[B]][h[l[P]]]=h[l[U]];break end while 1598==(e)/((2142+-0x6e))do h[l[B]]=l[M];break end;break;end break;end break;end break;end while(e)/((7757-0xf39))==1055 do e=(14152656)while(0x125-195)>=O do e-= e e=(724536)while O<=(0x12ba/51)do e-= e e=(100674)while O<=(-105+0xc5)do e-= e a[l[M]]=h[l[L]];break;end while 306==(e)/((0x47f8/56))do e=(2422536)while O>(131+-0x26)do e-= e h[l[f]]=a[l[P]];break end while(e)/((-87+(4437-0x8d2)))==1158 do h[l[L]]={};break end;break;end break;end while 694==(e)/((0x86b-1111))do e=(5405520)while O<=(9792/0x66)do e-= e e=(5483553)while O>((8832/0x20)-181)do e-= e do return end;break end while(e)/((-33+0x674))==3387 do local o=l[B]local e,l=S(h[o](x(h,o+1,l[F])))t=l+o-1 local l=0;for o=o,t do l=l+b;h[o]=e[l];end;break end;break;end while 3030==(e)/((3606-0x71e))do e=(1203276)while(143+-0x2e)<O do e-= e if not h[l[d]]then o=o+n;else o=l[M];end;break end while(e)/(((-0x1a+158834)/0x9c))==1182 do h[l[B]][l[M]]=l[D];break end;break;end break;end break;end while(e)/((0xdc0+-16))==4039 do e=(5162661)while(3030/0x1e)>=O do e-= e e=(5928130)while O<=((-18732/0xdf)+0xb7)do e-= e local O=s[l[p]];local e;local b={};e=Q({},{__index=function(o,l)local l=b[l];return l[1][l[2]];end,__newindex=function(h,l,o)local l=b[l]l[1][l[2]]=o;end;});for e=1,l[D]do o=o+n;local l=k[o];if l[(34-0x21)]==32 then b[e-1]={h,l[P]};else b[e-1]={N,l[M]};end;v[#v+1]=b;end;h[l[B]]=u(O,e,a);break;end while 2015==(e)/((-26+0xb98))do e=(5507943)while(-0x32+150)<O do e-= e h[l[d]]=u(s[l[H]],nil,a);break end while 1869==(e)/((406686/0x8a))do do return h[l[B]]end break end;break;end break;end while 2527==(e)/((-95+0x85a))do e=(880320)while(7828/0x4c)>=O do e-= e e=(4217260)while O>(0x5478/212)do e-= e do return end;break end while 1517==(e)/((450360/0xa2))do if not h[l[f]]then o=o+n;else o=l[M];end;break end;break;end while 1344==(e)/((0x91d7/57))do e=(3784442)while O>(317-0xd5)do e-= e h[l[m]][l[p]]=h[l[c]];break end while 2059==(e)/((1918+-0x50))do local o=l[f]h[o](x(h,o+n,l[M]))break end;break;end break;end break;end break;end break;end break;end o+= n end;end);end;return u(g(),{},E())()end)_msec({[(0x164-(0x142+-119))]='\115\116'..(function(l)return(l and'(-118+0xda)')or'\114\105'or'\120\58'end)((-21+0x1a)==(0x3d-55))..'\110g',[(-23+0x335)]='\108\100'..(function(l)return(l and'(0xe3+-127)')or'\101\120'or'\119\111'end)((122+-0x75)==(-45+0x33))..'\112',[(34827/0x8d)]=(function(l)return(l and'(266-0xa6)')and'\98\121'or'\100\120'end)((-0x6c+113)==(0x2e-41))..'\116\101',[(433+-0x63)]='\99'..(function(l)return(l and'(24700/0xf7)')and'\90\19\157'or'\104\97'end)((110-0x69)==(-0x4c+79))..'\114',[(1163-(-58+0x2a5))]='\116\97'..(function(l)return(l and'(137+-0x25)')and'\64\113'or'\98\108'end)((-0x1d+35)==(-0x55+90))..'\101',[(28210/0x3e)]=(function(l)return(l and'((0x1da-254)-120)')or'\115\117'or'\78\107'end)((-52+0x37)==(6913/0xdf))..'\98',[(14778/0x12)]='\99\111'..(function(l)return(l and'(0x76+-18)')and'\110\99'or'\110\105\103\97'end)((0xa0-129)==(128+-0x61))..'\97\116',[(-117+0x330)]=(function(l,o)return(l and'(256-0x9c)')and'\48\159\158\188\10'or'\109\97'end)((0x348/(16800/0x64))==((-68+0x0)+0x4a))..'\116\104',[(0xac9-1429)]=(function(l,o)return((0x4c9/245)==(0x1c2/150)and'\48'..'\195'or l..((not'\20\95\69'and'\90'..'\180'or o)))or'\199\203\95'end),[(0x3e1+-83)]='\105\110'..(function(l,o)return(l and'(277-0xb1)')and'\90\115\138\115\15'or'\115\101'end)((-42+(181-0x86))==(-0x50+111))..'\114\116',[(0x4b2+-124)]='\117\110'..(function(l,o)return(l and'(258-0x9e)')or'\112\97'or'\20\38\154'end)((0x40b/207)==(0xfbe/(363-0xe9)))..'\99\107',[(2429-0x4d9)]='\115\101'..(function(l)return(l and'(0x9e+-58)')and'\110\112\99\104'or'\108\101'end)((-0x46+75)==(133+-0x66))..'\99\116',[(0xf136/50)]='\116\111\110'..(function(l,o)return(l and'(6900/0x45)')and'\117\109\98'or'\100\97\120\122'end)((-0x62+103)==(-54+0x3b))..'\101\114'},{[(18540/0xce)]=((getfenv))},((getfenv))()) end)()



	end)

	ESP.MouseButton1Click:Connect(function()
		if (not game:IsLoaded()) then
			game.Loaded:Wait();
		end

		local UILibrary = loadstring(game:HttpGet("https://raw.githubusercontent.com/fatesc/fates-esp/main/ui.lua"))();

		local PlaceId = game.PlaceId

		local Players = game:GetService("Players");
		local HttpService = game:GetService("HttpService");
		local Workspace = game:GetService("Workspace");
		local Teams = game:GetService("Teams")
		local UserInputService = game:GetService("UserInputService")
		local RunService = game:GetService("RunService");

		local CurrentCamera = Workspace.CurrentCamera
		local WorldToViewportPoint = CurrentCamera.WorldToViewportPoint
		local GetPartsObscuringTarget = CurrentCamera.GetPartsObscuringTarget

		local Inset = game:GetService("GuiService"):GetGuiInset().Y

		local FindFirstChild = game.FindFirstChild
		local FindFirstChildWhichIsA = game.FindFirstChildWhichIsA
		local IsA = game.IsA
		local Vector2new = Vector2.new
		local Vector3new = Vector3.new
		local CFramenew = CFrame.new
		local Color3new = Color3.new

		local Tfind = table.find
		local create = table.create
		local format = string.format
		local floor = math.floor
		local gsub = string.gsub
		local sub = string.sub
		local lower = string.lower
		local upper = string.upper
		local random = math.random

		local DefaultSettings = {
			Esp = {
				NamesEnabled = true,
				DisplayNamesEnabled = false,
				DistanceEnabled = true,
				HealthEnabled = true,
				TracersEnabled = false,
				BoxEsp = false,
				TeamColors = true,
				Thickness = 1.5,
				TracerThickness = 1.6,
				Transparency = .9,
				TracerTrancparency = .7,
				Size = 16,
				RenderDistance = 9e9,
				Color = Color3.fromRGB(19, 130, 226),
				OutlineColor = Color3new(),
				TracerTo = "Head",
				BlacklistedTeams = {}
			},
			Aimbot = {
				Enabled = false,
				SilentAim = false,
				Wallbang = false,
				ShowFov = false,
				Snaplines = true,
				ThirdPerson = false,
				FirstPerson = false,
				ClosestCharacter = false,
				ClosestCursor = true,
				Smoothness = 1,
				SilentAimHitChance = 100,
				FovThickness = 1,
				FovTransparency = 1,
				FovSize = 150,
				FovColor = Color3new(1, 1, 1),
				Aimlock = "Head",
				SilentAimRedirect = "Head",
				BlacklistedTeams = {}
			},
			WindowPosition = UDim2.new(0.5, -200, 0.5, -139);

			Version = 1.2
		}

		local EncodeConfig, DecodeConfig;
		do
			local deepsearchset;
			deepsearchset = function(tbl, ret, value)
				if (type(tbl) == 'table') then
					local new = {}
					for i, v in next, tbl do
						new[i] = v
						if (type(v) == 'table') then
							new[i] = deepsearchset(v, ret, value);
						end
						if (ret(i, v)) then
							new[i] = value(i, v);
						end
					end
					return new
				end
			end

			DecodeConfig = function(Config)
				local DecodedConfig = deepsearchset(Config, function(Index, Value)
					return type(Value) == "table" and (Value.HSVColor or Value.Position);
				end, function(Index, Value)
					local Color = Value.HSVColor
					local Position = Value.Position
					if (Color) then
						return Color3.fromHSV(Color.H, Color.S, Color.V);
					end
					if (Position and Position.Y and Position.X) then
						return UDim2.new(UDim.new(Position.X.Scale, Position.X.Offset), UDim.new(Position.Y.Scale, Position.Y.Offset));
					else
						return DefaultSettings.WindowPosition;
					end
				end);
				return DecodedConfig
			end

			EncodeConfig = function(Config)
				local ToHSV = Color3new().ToHSV
				local EncodedConfig = deepsearchset(Config, function(Index, Value)
					return typeof(Value) == "Color3" or typeof(Value) == "UDim2"
				end, function(Index, Value)
					local Color = typeof(Value) == "Color3"
					local Position = typeof(Value) == "UDim2"
					if (Color) then
						local H, S, V = ToHSV(Value);
						return { HSVColor = { H = H, S = S, V = V } };
					end
					if (Position) then
						return { Position = {
							X = { Scale = Value.X.Scale, Offset = Value.X.Offset };
							Y = { Scale = Value.Y.Scale, Offset = Value.Y.Offset }
						} };
					end
				end)
				return EncodedConfig
			end
		end

		local GetConfig = function()
			local read, data = pcall(readfile, "fates-esp.json");
			local canDecode, config = pcall(HttpService.JSONDecode, HttpService, data);
			if (read and canDecode) then
				local Decoded = DecodeConfig(config);
				if (Decoded.Version ~= DefaultSettings.Version) then
					local Encoded = HttpService:JSONEncode(EncodeConfig(DefaultSettings));
					writefile("fates-esp.json", Encoded);
					return DefaultSettings;
				end
				return Decoded;
			else
				local Encoded = HttpService:JSONEncode(EncodeConfig(DefaultSettings));
				writefile("fates-esp.json", Encoded);
				return DefaultSettings
			end
		end

		local Settings = GetConfig();

		local LocalPlayer = Players.LocalPlayer
		local Mouse = LocalPlayer:GetMouse();
		local MouseVector = Vector2new(Mouse.X, Mouse.Y);
		local Characters = {}

		local CustomGet = {
			[0] = function()
				return {}
			end
		}

		local Get;
		if (CustomGet[PlaceId]) then
			Get = CustomGet[PlaceId]();
		end

		local GetCharacter = function(Player)
			if (Get) then
				return Get.GetCharacter(Player);
			end
			return Player.Character
		end
		local CharacterAdded = function(Player, Callback)
			if (Get) then
				return
			end
			Player.CharacterAdded:Connect(Callback);
		end
		local CharacterRemoving = function(Player, Callback)
			if (Get) then
				return
			end
			Player.CharacterRemoving:Connect(Callback);
		end

		local GetTeam = function(Player)
			if (Get) then
				return Get.GetTeam(Player);
			end
			return Player.Team
		end

		local Drawings = {}

		local AimbotSettings = Settings.Aimbot
		local EspSettings = Settings.Esp

		local FOV = Drawing.new("Circle");
		FOV.Color = AimbotSettings.FovColor
		FOV.Thickness = AimbotSettings.FovThickness
		FOV.Transparency = AimbotSettings.FovTransparency
		FOV.Filled = false
		FOV.Radius = AimbotSettings.FovSize

		local Snaplines = Drawing.new("Line");
		Snaplines.Color = AimbotSettings.FovColor
		Snaplines.Thickness = .1
		Snaplines.Transparency = 1
		Snaplines.Visible = AimbotSettings.Snaplines

		table.insert(Drawings, FOV);
		table.insert(Drawings, Snaplines);

		local HandlePlayer = function(Player)
			local Character = GetCharacter(Player);
			if (Character) then
				Characters[Player] = Character
			end
			CharacterAdded(Player, function(Char)
				Characters[Player] = Char
			end);
			CharacterRemoving(Player, function(Char)
				Characters[Player] = nil
				local PlayerDrawings = Drawings[Player]
				if (PlayerDrawings) then
					PlayerDrawings.Text.Visible = false
					PlayerDrawings.Box.Visible = false
					PlayerDrawings.Tracer.Visible = false
				end
			end);

			if (Player == LocalPlayer) then return; end

			local Text = Drawing.new("Text");
			Text.Color = EspSettings.Color
			Text.OutlineColor = EspSettings.OutlineColor
			Text.Size = EspSettings.Size
			Text.Transparency = EspSettings.Transparency
			Text.Center = true
			Text.Outline = true

			local Tracer = Drawing.new("Line");
			Tracer.Color = EspSettings.Color
			Tracer.From = Vector2new(CurrentCamera.ViewportSize.X / 2, CurrentCamera.ViewportSize.Y);
			Tracer.Thickness = EspSettings.TracerThickness
			Tracer.Transparency = EspSettings.TracerTrancparency

			local Box = Drawing.new("Quad");
			Box.Thickness = EspSettings.Thickness
			Box.Transparency = EspSettings.Transparency
			Box.Filled = false
			Box.Color = EspSettings.Color

			Drawings[Player] = { Text = Text, Tracer = Tracer, Box = Box }
		end

		for Index, Player in pairs(Players:GetPlayers()) do
			HandlePlayer(Player);
		end
		Players.PlayerAdded:Connect(function(Player)
			HandlePlayer(Player);
		end);

		Players.PlayerRemoving:Connect(function(Player)
			Characters[Player] = nil
			local PlayerDrawings = Drawings[Player]
			for Index, Drawing in pairs(PlayerDrawings or {}) do
				Drawing.Visible = false
			end
			Drawings[Player] = nil
		end);

		local SetProperties = function(Properties)
			for Player, PlayerDrawings in pairs(Drawings) do
				if (type(Player) ~= "number") then
					for Property, Value in pairs(Properties.Tracer or {}) do
						PlayerDrawings.Tracer[Property] = Value
					end
					for Property, Value in pairs(Properties.Text or {}) do
						PlayerDrawings.Text[Property] = Value
					end
					for Property, Value in pairs(Properties.Box or {}) do
						PlayerDrawings.Box[Property] = Value
					end
				end
			end
		end


		local GetClosestPlayerAndRender = function()
			MouseVector = Vector2new(Mouse.X, Mouse.Y + Inset);
			local Closest = create(4);
			local Vector2Distance = math.huge
			local Vector3DistanceOnScreen = math.huge
			local Vector3Distance = math.huge

			if (AimbotSettings.ShowFov) then
				FOV.Position = MouseVector
				FOV.Visible = true
				Snaplines.Visible = false
			else
				FOV.Visible = false
			end

			local LocalRoot = Characters[LocalPlayer] and FindFirstChild(Characters[LocalPlayer], "HumanoidRootPart");
			for Player, Character in pairs(Characters) do
				if (Player == LocalPlayer) then continue; end
				local PlayerDrawings = Drawings[Player]
				local PlayerRoot = FindFirstChild(Character, "HumanoidRootPart");
				local PlayerTeam = GetTeam(Player);
				if (PlayerRoot) then
					local Redirect = FindFirstChild(Character, AimbotSettings.Aimlock);
					if (not Redirect) then
						PlayerDrawings.Text.Visible = false
						PlayerDrawings.Box.Visible = false
						PlayerDrawings.Tracer.Visible = false
						continue;
					end
					local RedirectPos = Redirect.Position
					local Tuple, Visible = WorldToViewportPoint(CurrentCamera, RedirectPos);
					local CharacterVec2 = Vector2new(Tuple.X, Tuple.Y);
					local Vector2Magnitude = (MouseVector - CharacterVec2).Magnitude
					local Vector3Magnitude = LocalRoot and (RedirectPos - LocalRoot.Position).Magnitude or math.huge
					local InRenderDistance = Vector3Magnitude <= EspSettings.RenderDistance

					if (not Tfind(AimbotSettings.BlacklistedTeams, PlayerTeam)) then
						local InFovRadius = Vector2Magnitude <= FOV.Radius
						if (InFovRadius) then
							if (Visible and Vector2Magnitude <= Vector2Distance and AimbotSettings.ClosestCursor) then
								Vector2Distance = Vector2Magnitude
								Closest = {Character, CharacterVec2, Player, Redirect}
								if (AimbotSettings.Snaplines and AimbotSettings.ShowFov) then
									Snaplines.Visible = true
									Snaplines.From = MouseVector
									Snaplines.To = CharacterVec2
								else
									Snaplines.Visible = false
								end
							end

							if (Visible and Vector3Magnitude <= Vector3DistanceOnScreen and Settings.ClosestPlayer) then
								Vector3DistanceOnScreen = Vector3Magnitude
								Closest = {Character, CharacterVec2, Player, Redirect}
							end
						end
					end

					if (InRenderDistance and Visible and not Tfind(EspSettings.BlacklistedTeams, PlayerTeam)) then
						local CharacterHumanoid = FindFirstChildWhichIsA(Character, "Humanoid") or { Health = 0, MaxHealth = 0 };
						PlayerDrawings.Text.Text = format("%s\n%s%s",
							EspSettings.NamesEnabled and Player.Name or "",
							EspSettings.DistanceEnabled and format("[%s]",
								floor(Vector3Magnitude)
							) or "",
							EspSettings.HealthEnabled and format(" [%s/%s]",
								floor(CharacterHumanoid.Health),
								floor(CharacterHumanoid.MaxHealth)
							)  or ""
						);

						PlayerDrawings.Text.Position = Vector2new(Tuple.X, Tuple.Y - 40);

						if (EspSettings.TracersEnabled) then
							PlayerDrawings.Tracer.To = CharacterVec2
						end

						if (EspSettings.BoxEsp) then
							local Parts = {}
							for Index, Part in pairs(Character:GetChildren()) do
								if (IsA(Part, "BasePart")) then
									local ViewportPos = WorldToViewportPoint(CurrentCamera, Part.Position);
									Parts[Part] = Vector2new(ViewportPos.X, ViewportPos.Y);
								end
							end

							local Top, Bottom, Left, Right
							local Distance = math.huge
							local ClosestPart = nil
							for i2, Pos in next, Parts do
								local Mag = (Pos - Vector2new(Tuple.X, 0)).Magnitude;
								if (Mag <= Distance) then
									ClosestPart = Pos
									Distance = Mag
								end
							end
							Top = ClosestPart
							ClosestPart = nil
							Distance = math.huge
							for i2, Pos in next, Parts do
								local Mag = (Pos - Vector2new(Tuple.X, CurrentCamera.ViewportSize.Y)).Magnitude;
								if (Mag <= Distance) then
									ClosestPart = Pos
									Distance = Mag
								end
							end
							Bottom = ClosestPart
							ClosestPart = nil
							Distance = math.huge
							for i2, Pos in next, Parts do
								local Mag = (Pos - Vector2new(0, Tuple.Y)).Magnitude;
								if (Mag <= Distance) then
									ClosestPart = Pos
									Distance = Mag
								end
							end
							Left = ClosestPart
							ClosestPart = nil
							Distance = math.huge
							for i2, Pos in next, Parts do
								local Mag = (Pos - Vector2new(CurrentCamera.ViewportSize.X, Tuple.Y)).Magnitude;
								if (Mag <= Distance) then
									ClosestPart = Pos
									Distance = Mag
								end
							end
							Right = ClosestPart
							ClosestPart = nil
							Distance = math.huge

							PlayerDrawings.Box.PointA = Vector2new(Right.X, Top.Y);
							PlayerDrawings.Box.PointB = Vector2new(Left.X, Top.Y);
							PlayerDrawings.Box.PointC = Vector2new(Left.X, Bottom.Y);
							PlayerDrawings.Box.PointD = Vector2new(Right.X, Bottom.Y);
						end

						if (EspSettings.TeamColors) then
							local TeamColor;
							if (PlayerTeam) then
								local BrickTeamColor = PlayerTeam.TeamColor
								TeamColor = BrickTeamColor.Color
							else
								TeamColor = Color3new(0.639216, 0.635294, 0.647059);
							end
							PlayerDrawings.Text.Color = TeamColor
							PlayerDrawings.Box.Color = TeamColor
							PlayerDrawings.Tracer.Color = TeamColor
						end

						PlayerDrawings.Text.Visible = true
						PlayerDrawings.Box.Visible = EspSettings.BoxEsp
						PlayerDrawings.Tracer.Visible = EspSettings.TracersEnabled
					else
						PlayerDrawings.Text.Visible = false
						PlayerDrawings.Box.Visible = false
						PlayerDrawings.Tracer.Visible = false
					end
				else
					PlayerDrawings.Text.Visible = false
					PlayerDrawings.Box.Visible = false
					PlayerDrawings.Tracer.Visible = false
				end
			end

			return unpack(Closest);
		end

		local Locked, SwitchedCamera = false, false
		UserInputService.InputBegan:Connect(function(Inp)
			if (AimbotSettings.Enabled and Inp.UserInputType == Enum.UserInputType.MouseButton2) then
				Locked = true
				if (AimbotSettings.FirstPerson and LocalPlayer.CameraMode ~= Enum.CameraMode.LockFirstPerson) then
					LocalPlayer.CameraMode = Enum.CameraMode.LockFirstPerson
					SwitchedCamera = true
				end
			end
		end);
		UserInputService.InputEnded:Connect(function(Inp)
			if (AimbotSettings.Enabled and Inp.UserInputType == Enum.UserInputType.MouseButton2) then
				Locked = false
				if (SwitchedCamera) then
					LocalPlayer.CameraMode = Enum.CameraMode.Classic
				end
			end
		end);

		local ClosestCharacter, Vector, Player, Aimlock;
		RunService.RenderStepped:Connect(function()
			ClosestCharacter, Vector, Player, Aimlock = GetClosestPlayerAndRender();
			if (Locked and AimbotSettings.Enabled and ClosestCharacter) then
				if (AimbotSettings.FirstPerson) then
					if (syn) then
						CurrentCamera.CoordinateFrame = CFramenew(CurrentCamera.CoordinateFrame.p, Aimlock.Position);
					else
						mousemoverel((Vector.X - MouseVector.X) / AimbotSettings.Smoothness, (Vector.Y - MouseVector.Y) / AimbotSettings.Smoothness);
					end
				elseif (AimbotSettings.ThirdPerson) then
					mousemoveabs(Vector.X, Vector.Y);
				end
			end
		end);

		local Hooks = {
			HookedFunctions = {},
			OldMetaMethods = {},
			MetaMethodHooks = {},
			HookedSignals = {}
		}

		local OtherDeprecated = {
			children = "GetChildren"
		}

		local RealMethods = {}
		local FakeMethods = {}

		local HookedFunctions = Hooks.HookedFunctions
		local MetaMethodHooks = Hooks.MetaMethodHooks
		local OldMetaMethods = Hooks.OldMetaMethods

		MetaMethodHooks.Index = function(...)
			local __Index = OldMetaMethods.__index

			if (Player and Aimlock and ... == Mouse and not checkcaller()) then
				local CallingScript = getfenv(2).script;
				if (CallingScript.Name == "CallingScript") then
					return __Index(...);
				end

				local Mouse, Index = ...
				if (type(Index) == 'string') then
					Index = gsub(sub(Index, 0, 100), "%z.*", "");
				end
				local PassedChance = random(1, 100) < AimbotSettings.SilentAimHitChance
				if (PassedChance and AimbotSettings.SilentAim) then
					local Parts = GetPartsObscuringTarget(CurrentCamera, {CurrentCamera.CFrame.Position, Aimlock.Position}, {LocalPlayer.Character, ClosestCharacter});
					local LowerIndex = lower(Index);
					local Hit = #Parts == 0 or AimbotSettings.Wallbang
					if (not Hit) then
						return __Index(...);
					end
					if (LowerIndex == "target") then
						return Aimlock
					end
					if (LowerIndex == "hit") then
						return Aimlock.CFrame * CFramenew(random(1, 10) / 10, random(1, 10) / 10, random(1, 10) / 10);
					end
					if (LowerIndex == "x") then
						return Vector.X + (random(1, 10) / 10);
					end
					if (LowerIndex == "y") then
						return Vector.Y + (random(1, 10) / 10);
					end
				end
			end

			return __Index(...);
		end

		MetaMethodHooks.Namecall = function(...)
			local __Namecall = OldMetaMethods.__namecall
			local self = ...
			local Method = gsub(getnamecallmethod() or "", "^%l", upper);
			local Hooked = HookedFunctions[Method]
			if (Hooked and self == Hooked[1]) then
				return Hooked[3](...);
			end

			return __Namecall(...);
		end

		for MMName, MMFunc in pairs(MetaMethodHooks) do
			local MetaMethod = string.format("__%s", string.lower(MMName));
			Hooks.OldMetaMethods[MetaMethod] = hookmetamethod(game, MetaMethod, MMFunc);
		end

		HookedFunctions.FindPartOnRay = {Workspace, Workspace.FindPartOnRay, function(...)
			local OldFindPartOnRay = HookedFunctions.FindPartOnRay[4]
			if (AimbotSettings.SilentAim and Player and Aimlock and not checkcaller()) then
				local PassedChance = random(1, 100) < AimbotSettings.SilentAimHitChance
				if (ClosestCharacter and PassedChance) then
					local Parts = GetPartsObscuringTarget(CurrentCamera, {CurrentCamera.CFrame.Position, Aimlock.Position}, {LocalPlayer.Character, ClosestCharacter});
					print(#Parts);
					if (#Parts == 0 or AimbotSettings.Wallbang) then
						return Aimlock, Aimlock.Position + (Vector3new(random(1, 10), random(1, 10), random(1, 10)) / 10), Vector3new(0, 1, 0), Aimlock.Material
					end
				end
			end
			return OldFindPartOnRay(...);
		end};

		HookedFunctions.FindPartOnRayWithIgnoreList = {Workspace, Workspace.FindPartOnRayWithIgnoreList, function(...)
			local OldFindPartOnRayWithIgnoreList = HookedFunctions.FindPartOnRayWithIgnoreList[4]
			if (Player and Aimlock and not checkcaller()) then
				local CallingScript = getcallingscript();
				local PassedChance = random(1, 100) < AimbotSettings.SilentAimHitChance
				if (CallingScript.Name ~= "ControlModule" and ClosestCharacter and PassedChance) then
					local Parts = GetPartsObscuringTarget(CurrentCamera, {CurrentCamera.CFrame.Position, Aimlock.Position}, {LocalPlayer.Character, ClosestCharacter});
					if (#Parts == 0 or AimbotSettings.Wallbang) then
						return Aimlock, Aimlock.Position + (Vector3new(random(1, 10), random(1, 10), random(1, 10)) / 10), Vector3new(0, 1, 0), Aimlock.Material
					end
				end
			end
			return OldFindPartOnRayWithIgnoreList(...);
		end};

		for Index, Function in pairs(HookedFunctions) do
			Function[4] = hookfunction(Function[2], Function[3]);
		end

		local MainUI = UILibrary.new(Color3.fromRGB(255, 79, 87));
		local Window = MainUI:LoadWindow('<font color="#ff4f57">fates</font> esp', UDim2.fromOffset(400, 279));
		local ESP = Window.NewPage("esp");
		local Aimbot = Window.NewPage("aimbot");
		local EspSettingsUI = ESP.NewSection("Esp");
		local TracerSettingsUI = ESP.NewSection("Tracers");
		local SilentAim = Aimbot.NewSection("Silent Aim");
		local Aimbot = Aimbot.NewSection("Aimbot");

		EspSettingsUI.Toggle("Show Names", EspSettings.NamesEnabled, function(Callback)
			EspSettings.NamesEnabled = Callback
		end);
		EspSettingsUI.Toggle("Show Health", EspSettings.HealthEnabled, function(Callback)
			EspSettings.HealthEnabled = Callback
		end);
		EspSettingsUI.Toggle("Show Distance", EspSettings.DistanceEnabled, function(Callback)
			EspSettings.DistanceEnabled = Callback
		end);
		EspSettingsUI.Toggle("Box Esp", EspSettings.BoxEsp, function(Callback)
			EspSettings.BoxEsp = Callback
			SetProperties({ Box = { Visible = Callback } });
		end);
		EspSettingsUI.Slider("Render Distance", { Min = 0, Max = 50000, Default = math.clamp(EspSettings.RenderDistance, 0, 50000), Step = 10 }, function(Callback)
			EspSettings.RenderDistance = Callback
		end);
		EspSettingsUI.Slider("Esp Size", { Min = 0, Max = 30, Default = EspSettings.Size, Step = 1}, function(Callback)
			EspSettings.Size = Callback
			SetProperties({ Text = { Size = Callback } });
		end);
		EspSettingsUI.ColorPicker("Esp Color", EspSettings.Color, function(Callback)
			EspSettings.TeamColors = false
			EspSettings.Color = Callback
			SetProperties({ Box = { Color = Callback }, Text = { Color = Callback }, Tracer = { Color = Callback } });
		end);
		EspSettingsUI.Toggle("Team Colors", EspSettings.TeamColors, function(Callback)
			EspSettings.TeamColors = Callback
			if (not Callback) then
				SetProperties({ Tracer = { Color = EspSettings.Color }; Box = { Color = EspSettings.Color }; Text = { Color = EspSettings.Color }  })
			end
		end);
		EspSettingsUI.Dropdown("Teams", {"Allies", "Enemies", "All"}, function(Callback)
			table.clear(EspSettings.BlacklistedTeams);
			if (Callback == "Enemies") then
				table.insert(EspSettings.BlacklistedTeams, LocalPlayer.Team);
			end
			if (Callback == "Allies") then
				local AllTeams = Teams:GetTeams();
				table.remove(AllTeams, table.find(AllTeams, LocalPlayer.Team));
				EspSettings.BlacklistedTeams = AllTeams
			end
		end);
		TracerSettingsUI.Toggle("Enable Tracers", EspSettings.TracersEnabled, function(Callback)
			EspSettings.TracersEnabled = Callback
			SetProperties({ Tracer = { Visible = Callback } });
		end);
		TracerSettingsUI.Dropdown("To", {"Head", "Torso"}, function(Callback)
			AimbotSettings.Aimlock = Callback == "Torso" and "HumanoidRootPart" or Callback
		end);
		TracerSettingsUI.Dropdown("From", {"Top", "Bottom", "Left", "Right"}, function(Callback)
			local ViewportSize = CurrentCamera.ViewportSize
			local From = Callback == "Top" and Vector2new(ViewportSize.X / 2, ViewportSize.Y - ViewportSize.Y) or Callback == "Bottom" and Vector2new(ViewportSize.X / 2, ViewportSize.Y) or Callback == "Left" and Vector2new(ViewportSize.X - ViewportSize.X, ViewportSize.Y / 2) or Callback == "Right" and Vector2new(ViewportSize.X, ViewportSize.Y / 2);
			EspSettings.TracerFrom = From
			SetProperties({ Tracer = { From = From } });
		end);
		TracerSettingsUI.Slider("Tracer Transparency", {Min = 0, Max = 1, Default = EspSettings.TracerTrancparency, Step = .1}, function(Callback)
			EspSettings.TracerTrancparency = Callback
			SetProperties({ Tracer = { Transparency = Callback } });
		end);
		TracerSettingsUI.Slider("Tracer Thickness", {Min = 0, Max = 5, Default = EspSettings.TracerThickness, Step = .1}, function(Callback)
			EspSettings.TracerThickness = Callback
			SetProperties({ Tracer = { Thickness = Callback } });
		end);

		SilentAim.Toggle("Silent Aim", AimbotSettings.SilentAim, function(Callback)
			AimbotSettings.SilentAim = Callback
		end);
		SilentAim.Toggle("Wallbang", AimbotSettings.Wallbang, function(Callback)
			AimbotSettings.Wallbang = Callback
		end);
		SilentAim.Dropdown("Redirect", {"Head", "Torso"}, function(Callback)
			AimbotSettings.SilentAimRedirect = Callback
		end);
		SilentAim.Slider("Hit Chance", {Min = 0, Max = 100, Default = AimbotSettings.SilentAimHitChance, Step = 1}, function(Callback)
			AimbotSettings.SilentAimHitChance = Callback
		end);

		SilentAim.Dropdown("Lock Type", {"Closest Cursor", "Closest Player"}, function(Callback)
			if (Callback == "Closest Cursor") then
				AimbotSettings.ClosestCharacter = false
				AimbotSettings.ClosestCursor = true
			else
				AimbotSettings.ClosestCharacter = true
				AimbotSettings.ClosestCursor = false
			end
		end);

		Aimbot.Toggle("Aimbot (M2)", AimbotSettings.Enabled, function(Callback)
			AimbotSettings.Enabled = Callback
			if (not AimbotSettings.FirstPerson and not AimbotSettings.ThirdPerson) then
				AimbotSettings.FirstPerson = true
			end
		end);
		Aimbot.Slider("Aimbot Smoothness", {Min = 1, Max = 10, Default = AimbotSettings.Smoothness, Step = .5}, function(Callback)
			AimbotSettings.Smoothness = Callback
		end);
		local sortTeams = function(Callback)
			table.clear(AimbotSettings.BlacklistedTeams);
			if (Callback == "Enemies") then
				table.insert(AimbotSettings.BlacklistedTeams, LocalPlayer.Team);
			end
			if (Callback == "Allies") then
				local AllTeams = Teams:GetTeams();
				table.remove(AllTeams, table.find(AllTeams, LocalPlayer.Team));
				AimbotSettings.BlacklistedTeams = AllTeams
			end
		end
		Aimbot.Dropdown("Team Target", {"Allies", "Enemies", "All"}, sortTeams);
		sortTeams("Enemies");
		Aimbot.Dropdown("Aimlock Type", {"Third Person", "First Person"}, function(callback)
			if (callback == "Third Person") then
				AimbotSettings.ThirdPerson = true
				AimbotSettings.FirstPerson = false
			else
				AimbotSettings.ThirdPerson = false
				AimbotSettings.FirstPerson = true
			end
		end);

		Aimbot.Toggle("Show Fov", AimbotSettings.ShowFov, function(Callback)
			AimbotSettings.ShowFov = Callback
			FOV.Visible = Callback
		end);
		Aimbot.ColorPicker("Fov Color", AimbotSettings.FovColor, function(Callback)
			AimbotSettings.FovColor = Callback
			FOV.Color = Callback
			Snaplines.Color = Callback
		end);
		Aimbot.Slider("Fov Size", {Min = 70, Max = 500, Default = AimbotSettings.FovSize, Step = 10}, function(Callback)
			AimbotSettings.FovSize = Callback
			FOV.Radius = Callback
		end);
		Aimbot.Toggle("Enable Snaplines", AimbotSettings.Snaplines, function(Callback)
			AimbotSettings.Snaplines = Callback
		end);
		Window.SetPosition(Settings.WindowPosition);

		if (gethui) then
			MainUI.UI.Parent = gethui();
		else
			local protect_gui = (syn or getgenv()).protect_gui
			if (protect_gui) then
				protect_gui(MainUI.UI);
			end
			MainUI.UI.Parent = game:GetService("CoreGui");
		end

		while wait(5) do
			Settings.WindowPosition = Window.GetPosition();
			local Encoded = HttpService:JSONEncode(EncodeConfig(Settings));
			writefile("fates-esp.json", Encoded);
		end
	end)

	PickUp.MouseButton1Click:Connect(function()
		local Players = game:GetService("Players")
		local Lp = Players.LocalPlayer
		local Char = Lp.Character
		local Root = Char.HumanoidRootPart
		local uis = game:GetService'UserInputService'

		--local PickupKey = "G"

		local Load;
		local Pick = function(Character)
			local Pos = Root.Position
			local Load = {}

			for i,v in pairs(workspace:GetChildren()) do
				if v:FindFirstChild("Pickup") ~= nil and v.ClassName == "Part" or v.ClassName == "UnionOperation" then
					local Object = v.Position
					local Mag = (Pos - Object).Magnitude

					if Mag < 50 then
						table.insert(Load, v)
					end
				end
			end
			for i,v in pairs(Load) do
				for i=1,10 do
					v.Position = Pos
					game:GetService'ReplicatedStorage'.Events.Pickup:FireServer(v)
				end
			end
		end
		wait(0.5)

		uis.InputBegan:Connect(function(Key)
			if uis:GetFocusedTextBox() then return end
			if Key.KeyCode == Enum.KeyCode.G then -- Enum.KeyCode[PickupKey] for certain Key!
				Pick(Char)
			end
		end)
	end)

	infjump.MouseButton1Click:Connect(function()
		local InfiniteJumpEnabled = true
		game:GetService("UserInputService").JumpRequest:connect(function()
			if InfiniteJumpEnabled then
				game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")
			end
		end) end)

	MiddleTP.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1118, -144, 1152)
		wait(1)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(162, 1, -340)
	end)

	PickUp.MouseButton1Click:Connect(function()
		local Players = game:GetService("Players")
		local Lp = Players.LocalPlayer
		local Char = Lp.Character
		local Root = Char.HumanoidRootPart
		local uis = game:GetService'UserInputService'

		--local PickupKey = "G"

		local Load;
		local Pick = function(Character)
			local Pos = Root.Position
			local Load = {}

			for i,v in pairs(workspace:GetChildren()) do
				if v:FindFirstChild("Pickup") ~= nil and v.ClassName == "Part" or v.ClassName == "UnionOperation" then
					local Object = v.Position
					local Mag = (Pos - Object).Magnitude

					if Mag < 50 then
						table.insert(Load, v)
					end
				end
			end
			for i,v in pairs(Load) do
				for i=1,10 do
					v.Position = Pos
					game:GetService'ReplicatedStorage'.Events.Pickup:FireServer(v)
				end
			end
		end
		wait(0.5)

		uis.InputBegan:Connect(function(Key)
			if uis:GetFocusedTextBox() then return end
			if Key.KeyCode == Enum.KeyCode.G then -- Enum.KeyCode[PickupKey] for certain Key!
				Pick(Char)
			end
		end)
	end)
end)

LossGui.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/lololboogahacker/loss-hub/main/VAMPTHEGODLEAKER.txt'),true))()
end)

InfiniteYield.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source", true))()
end)

ShiteGui.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/52E1cvWV", true))()
end)

GodRock.MouseButton1Click:Connect(function()
	local item = "God Rock"
	game:GetService("ReplicatedStorage").Events.CraftItem:FireServer(item)
end)

GodArmor.MouseButton1Click:Connect(function()
	local item = "God Halo"
	game:GetService("ReplicatedStorage").Events.CraftItem:FireServer(item)
	local item = "God Legs"
	game:GetService("ReplicatedStorage").Events.CraftItem:FireServer(item)
	local item = "God Chestplate"
	game:GetService("ReplicatedStorage").Events.CraftItem:FireServer(item)
	wait(1)
	local item = "God Halo"
	game:GetService("ReplicatedStorage").Events.UseBagItem:FireServer(item)
	local item = "God Legs"
	game:GetService("ReplicatedStorage").Events.UseBagItem:FireServer(item)
	local item = "God Chestplate"
	game:GetService("ReplicatedStorage").Events.UseBagItem:FireServer(item)
end)

PickUp.MouseButton1Click:Connect(function()
	local Players = game:GetService("Players")
	local Lp = Players.LocalPlayer
	local Char = Lp.Character
	local Root = Char.HumanoidRootPart
	local uis = game:GetService'UserInputService'

	--local PickupKey = "G"

	local Load;
	local Pick = function(Character)
		local Pos = Root.Position
		local Load = {}

		for i,v in pairs(workspace:GetChildren()) do
			if v:FindFirstChild("Pickup") ~= nil and v.ClassName == "Part" or v.ClassName == "UnionOperation" then
				local Object = v.Position
				local Mag = (Pos - Object).Magnitude

				if Mag < 50 then
					table.insert(Load, v)
				end
			end
		end
		for i,v in pairs(Load) do
			for i=1,10 do
				v.Position = Pos
				game:GetService'ReplicatedStorage'.Events.Pickup:FireServer(v)
			end
		end
	end
	wait(0.5)

	uis.InputBegan:Connect(function(Key)
		if uis:GetFocusedTextBox() then return end
		if Key.KeyCode == Enum.KeyCode.G then -- Enum.KeyCode[PickupKey] for certain Key!
			Pick(Char)
		end
	end)
end)

InfJump.MouseButton1Click:Connect(function()
	local InfiniteJumpEnabled = true
	game:GetService("UserInputService").JumpRequest:connect(function()
		if InfiniteJumpEnabled then
			game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")
		end
	end) end)

DropItem.MouseButton1Click:Connect(function()
	for i=1, dropamount.Text do game.ReplicatedStorage.Events.DropBagItem:FireServer(dropitem.Text) end
end)

Destroy.MouseButton1Click:Connect(function()
game:GetService("CoreGui").ScreenGui:Destroy()
game:GetService("CoreGui").ScreenGui:Destroy()
game:GetService("CoreGui").ScreenGui:Destroy()
game:GetService("CoreGui").ScreenGui:Destroy()
game:GetService("CoreGui").ScreenGui:Destroy()
game:GetService("CoreGui").ScreenGui:Destroy()
game:GetService("CoreGui").ScreenGui:Destroy()
	game:GetService("CoreGui")["135588A2-64E4-4E63-B50E-DE45F1D124C1"]:Destroy()
end)
