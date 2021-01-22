local RobloxHub = Instance.new("ScreenGui")
local BuildFrame = Instance.new("Frame")
local Home = Instance.new("TextButton")
local Games = Instance.new("TextButton")
local HomeFrame = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local TextLabel_3 = Instance.new("TextLabel")
local TextLabel_4 = Instance.new("TextLabel")
local GamesFrame = Instance.new("Frame")
local TOH = Instance.new("TextButton")
local ParkourTitle = Instance.new("TextLabel")
local RpgTitle = Instance.new("TextLabel")
local FpsTitle = Instance.new("TextLabel")
local OtherTitle = Instance.new("TextLabel")
local SR4 = Instance.new("TextButton")
local KY2 = Instance.new("TextButton")
local WZ = Instance.new("TextButton")
local DQ = Instance.new("TextButton")
local Title = Instance.new("TextLabel")
local ANL = Instance.new("TextButton")
local Title_2 = Instance.new("TextLabel")
local KT = Instance.new("TextButton")
local Title_3 = Instance.new("TextLabel")
local CmdX = Instance.new("TextButton")
local Title_4 = Instance.new("TextLabel")
local CloseMe = Instance.new("TextButton")
local UserName = Instance.new("TextLabel")
local OpenMenu = Instance.new("TextButton")

--Properties:

RobloxHub.Name = "RobloxHub"
RobloxHub.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

BuildFrame.Name = "BuildFrame"
BuildFrame.Parent = RobloxHub
BuildFrame.BackgroundColor3 = Color3.fromRGB(42, 42, 42)
BuildFrame.BorderSizePixel = 0
BuildFrame.Position = UDim2.new(0.293229163, 0, 0.124074079, 0)
BuildFrame.Size = UDim2.new(0, 793, 0, 534)

Home.Name = "Home"
Home.Parent = BuildFrame
Home.BackgroundColor3 = Color3.fromRGB(31, 31, 31)
Home.BorderSizePixel = 0
Home.Position = UDim2.new(0.27868852, 0, 0.0131086148, 0)
Home.Size = UDim2.new(0, 200, 0, 50)
Home.AutoButtonColor = false
Home.Font = Enum.Font.SourceSansLight
Home.Text = "HOME"
Home.TextColor3 = Color3.fromRGB(255, 255, 255)
Home.TextScaled = true
Home.TextSize = 14.000
Home.TextWrapped = true

Games.Name = "Games"
Games.Parent = BuildFrame
Games.BackgroundColor3 = Color3.fromRGB(31, 31, 31)
Games.BorderSizePixel = 0
Games.Position = UDim2.new(0.543505669, 0, 0.0131086148, 0)
Games.Size = UDim2.new(0, 200, 0, 50)
Games.AutoButtonColor = false
Games.Font = Enum.Font.SourceSansLight
Games.Text = "GAMES"
Games.TextColor3 = Color3.fromRGB(255, 255, 255)
Games.TextScaled = true
Games.TextSize = 14.000
Games.TextWrapped = true

HomeFrame.Name = "HomeFrame"
HomeFrame.Parent = BuildFrame
HomeFrame.BackgroundColor3 = Color3.fromRGB(31, 31, 31)
HomeFrame.BorderSizePixel = 0
HomeFrame.Position = UDim2.new(0.0126103405, 0, 0.136704117, 0)
HomeFrame.Size = UDim2.new(0, 771, 0, 452)
HomeFrame.Visible = false

TextLabel.Parent = HomeFrame
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Position = UDim2.new(0.00129701686, 0, 0.0221238937, 0)
TextLabel.Size = UDim2.new(0, 771, 0, 30)
TextLabel.Font = Enum.Font.SourceSansLight
TextLabel.Text = "Status: Working"
TextLabel.TextColor3 = Color3.fromRGB(68, 255, 0)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

TextLabel_2.Parent = HomeFrame
TextLabel_2.BackgroundColor3 = Color3.fromRGB(61, 61, 61)
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Position = UDim2.new(0, 0, 0.11061947, 0)
TextLabel_2.Size = UDim2.new(0, 771, 0, 50)
TextLabel_2.Font = Enum.Font.SourceSansLight
TextLabel_2.Text = "Fixed few bugs"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 14.000
TextLabel_2.TextWrapped = true

TextLabel_3.Parent = HomeFrame
TextLabel_3.BackgroundColor3 = Color3.fromRGB(109, 109, 109)
TextLabel_3.BorderSizePixel = 0
TextLabel_3.Position = UDim2.new(0, 0, 0.221238941, 0)
TextLabel_3.Size = UDim2.new(0, 771, 0, 50)
TextLabel_3.Font = Enum.Font.SourceSansLight
TextLabel_3.Text = "Added new click sound"
TextLabel_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.TextScaled = true
TextLabel_3.TextSize = 14.000
TextLabel_3.TextWrapped = true

TextLabel_4.Parent = HomeFrame
TextLabel_4.BackgroundColor3 = Color3.fromRGB(61, 61, 61)
TextLabel_4.BorderSizePixel = 0
TextLabel_4.Position = UDim2.new(0, 0, 0.331858426, 0)
TextLabel_4.Size = UDim2.new(0, 771, 0, 50)
TextLabel_4.Font = Enum.Font.SourceSansLight
TextLabel_4.Text = "Deleted the old song & added two new."
TextLabel_4.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.TextScaled = true
TextLabel_4.TextSize = 14.000
TextLabel_4.TextWrapped = true

GamesFrame.Name = "GamesFrame"
GamesFrame.Parent = BuildFrame
GamesFrame.BackgroundColor3 = Color3.fromRGB(31, 31, 31)
GamesFrame.BorderSizePixel = 0
GamesFrame.Position = UDim2.new(0.0126103405, 0, 0.136704117, 0)
GamesFrame.Size = UDim2.new(0, 771, 0, 452)

TOH.Name = "TOH"
TOH.Parent = GamesFrame
TOH.BackgroundColor3 = Color3.fromRGB(42, 42, 42)
TOH.BorderSizePixel = 0
TOH.Position = UDim2.new(0.0129701691, 0, 0.117256634, 0)
TOH.Size = UDim2.new(0, 190, 0, 62)
TOH.Font = Enum.Font.SourceSansBold
TOH.Text = "TOH"
TOH.TextColor3 = Color3.fromRGB(255, 255, 255)
TOH.TextScaled = true
TOH.TextSize = 14.000
TOH.TextWrapped = true

ParkourTitle.Name = "ParkourTitle"
ParkourTitle.Parent = GamesFrame
ParkourTitle.BackgroundColor3 = Color3.fromRGB(106, 0, 255)
ParkourTitle.BorderSizePixel = 0
ParkourTitle.Position = UDim2.new(0.0129701691, 0, 0.0199115053, 0)
ParkourTitle.Size = UDim2.new(0, 190, 0, 30)
ParkourTitle.Font = Enum.Font.SourceSansBold
ParkourTitle.Text = "PARKOUR GAME's"
ParkourTitle.TextColor3 = Color3.fromRGB(255, 255, 255)
ParkourTitle.TextScaled = true
ParkourTitle.TextSize = 14.000
ParkourTitle.TextWrapped = true

RpgTitle.Name = "RpgTitle"
RpgTitle.Parent = GamesFrame
RpgTitle.BackgroundColor3 = Color3.fromRGB(106, 0, 255)
RpgTitle.BorderSizePixel = 0
RpgTitle.Position = UDim2.new(0.278858632, 0, 0.0199115053, 0)
RpgTitle.Size = UDim2.new(0, 190, 0, 30)
RpgTitle.Font = Enum.Font.SourceSansBold
RpgTitle.Text = "RPG GAME's"
RpgTitle.TextColor3 = Color3.fromRGB(255, 255, 255)
RpgTitle.TextScaled = true
RpgTitle.TextSize = 14.000
RpgTitle.TextWrapped = true

FpsTitle.Name = "FpsTitle"
FpsTitle.Parent = GamesFrame
FpsTitle.BackgroundColor3 = Color3.fromRGB(106, 0, 255)
FpsTitle.BorderSizePixel = 0
FpsTitle.Position = UDim2.new(0.546044111, 0, 0.0199115053, 0)
FpsTitle.Size = UDim2.new(0, 190, 0, 30)
FpsTitle.Font = Enum.Font.SourceSansBold
FpsTitle.Text = "FPS GAME's"
FpsTitle.TextColor3 = Color3.fromRGB(255, 255, 255)
FpsTitle.TextScaled = true
FpsTitle.TextSize = 14.000
FpsTitle.TextWrapped = true

OtherTitle.Name = "OtherTitle"
OtherTitle.Parent = GamesFrame
OtherTitle.BackgroundColor3 = Color3.fromRGB(255, 102, 0)
OtherTitle.BorderSizePixel = 0
OtherTitle.Position = UDim2.new(0.808041513, 0, 0.0199115053, 0)
OtherTitle.Size = UDim2.new(0, 134, 0, 30)
OtherTitle.Font = Enum.Font.SourceSansBold
OtherTitle.Text = "OTHER"
OtherTitle.TextColor3 = Color3.fromRGB(255, 255, 255)
OtherTitle.TextScaled = true
OtherTitle.TextSize = 14.000
OtherTitle.TextWrapped = true

SR4.Name = "SR4"
SR4.Parent = GamesFrame
SR4.BackgroundColor3 = Color3.fromRGB(42, 42, 42)
SR4.BorderSizePixel = 0
SR4.Position = UDim2.new(0.0129701691, 0, 0.274336278, 0)
SR4.Size = UDim2.new(0, 190, 0, 62)
SR4.Font = Enum.Font.SourceSansBold
SR4.Text = "SR4"
SR4.TextColor3 = Color3.fromRGB(255, 255, 255)
SR4.TextScaled = true
SR4.TextSize = 14.000
SR4.TextWrapped = true

KY2.Name = "KY2"
KY2.Parent = GamesFrame
KY2.BackgroundColor3 = Color3.fromRGB(148, 66, 0)
KY2.BorderSizePixel = 0
KY2.Position = UDim2.new(0.0129701691, 0, 0.431415915, 0)
KY2.Selectable = false
KY2.Size = UDim2.new(0, 190, 0, 62)
KY2.AutoButtonColor = false
KY2.Font = Enum.Font.SourceSansBold
KY2.Text = "(2021);"
KY2.TextColor3 = Color3.fromRGB(255, 255, 255)
KY2.TextScaled = true
KY2.TextSize = 14.000
KY2.TextWrapped = true

WZ.Name = "WZ"
WZ.Parent = GamesFrame
WZ.BackgroundColor3 = Color3.fromRGB(42, 42, 42)
WZ.BorderSizePixel = 0
WZ.Position = UDim2.new(0.278858632, 0, 0.117256634, 0)
WZ.Size = UDim2.new(0, 190, 0, 62)
WZ.Font = Enum.Font.SourceSansBold
WZ.Text = "WZ"
WZ.TextColor3 = Color3.fromRGB(255, 255, 255)
WZ.TextScaled = true
WZ.TextSize = 14.000
WZ.TextWrapped = true

DQ.Name = "DQ"
DQ.Parent = GamesFrame
DQ.Active = false
DQ.BackgroundColor3 = Color3.fromRGB(156, 49, 49)
DQ.BorderSizePixel = 0
DQ.Position = UDim2.new(0.278858632, 0, 0.274336278, 0)
DQ.Selectable = false
DQ.Size = UDim2.new(0, 190, 0, 62)
DQ.AutoButtonColor = false
DQ.Font = Enum.Font.SourceSansBold
DQ.Text = "DQ"
DQ.TextColor3 = Color3.fromRGB(255, 255, 255)
DQ.TextScaled = true
DQ.TextSize = 14.000
DQ.TextWrapped = true

Title.Name = "Title"
Title.Parent = DQ
Title.BackgroundColor3 = Color3.fromRGB(223, 190, 0)
Title.BorderSizePixel = 0
Title.Position = UDim2.new(0, 0, 1, 0)
Title.Size = UDim2.new(0, 190, 0, 20)
Title.Font = Enum.Font.SourceSansBold
Title.Text = "Not working."
Title.TextColor3 = Color3.fromRGB(138, 103, 0)
Title.TextScaled = true
Title.TextSize = 14.000
Title.TextWrapped = true

ANL.Name = "ANL"
ANL.Parent = GamesFrame
ANL.Active = false
ANL.BackgroundColor3 = Color3.fromRGB(156, 49, 49)
ANL.BorderSizePixel = 0
ANL.Position = UDim2.new(0.546044111, 0, 0.117256634, 0)
ANL.Size = UDim2.new(0, 190, 0, 62)
ANL.AutoButtonColor = false
ANL.Font = Enum.Font.SourceSansBold
ANL.Text = "ANL"
ANL.TextColor3 = Color3.fromRGB(255, 255, 255)
ANL.TextScaled = true
ANL.TextSize = 14.000
ANL.TextWrapped = true

Title_2.Name = "Title"
Title_2.Parent = ANL
Title_2.BackgroundColor3 = Color3.fromRGB(223, 190, 0)
Title_2.BorderSizePixel = 0
Title_2.Position = UDim2.new(0, 0, 1, 0)
Title_2.Size = UDim2.new(0, 190, 0, 20)
Title_2.Font = Enum.Font.SourceSansBold
Title_2.Text = "Not working."
Title_2.TextColor3 = Color3.fromRGB(138, 103, 0)
Title_2.TextScaled = true
Title_2.TextSize = 14.000
Title_2.TextWrapped = true

KT.Name = "KT"
KT.Parent = GamesFrame
KT.Active = false
KT.BackgroundColor3 = Color3.fromRGB(156, 49, 49)
KT.BorderSizePixel = 0
KT.Position = UDim2.new(0.546044111, 0, 0.318584055, 0)
KT.Selectable = false
KT.Size = UDim2.new(0, 190, 0, 62)
KT.AutoButtonColor = false
KT.Font = Enum.Font.SourceSansBold
KT.Text = "KT"
KT.TextColor3 = Color3.fromRGB(255, 255, 255)
KT.TextScaled = true
KT.TextSize = 14.000
KT.TextWrapped = true

Title_3.Name = "Title"
Title_3.Parent = KT
Title_3.BackgroundColor3 = Color3.fromRGB(223, 190, 0)
Title_3.BorderSizePixel = 0
Title_3.Position = UDim2.new(0, 0, 1, 0)
Title_3.Size = UDim2.new(0, 190, 0, 20)
Title_3.Font = Enum.Font.SourceSansBold
Title_3.Text = "Not working."
Title_3.TextColor3 = Color3.fromRGB(138, 103, 0)
Title_3.TextScaled = true
Title_3.TextSize = 14.000
Title_3.TextWrapped = true

CmdX.Name = "CmdX"
CmdX.Parent = GamesFrame
CmdX.Active = false
CmdX.BackgroundColor3 = Color3.fromRGB(156, 49, 49)
CmdX.BorderSizePixel = 0
CmdX.Position = UDim2.new(0.808041513, 0, 0.117256634, 0)
CmdX.Size = UDim2.new(0, 134, 0, 62)
CmdX.AutoButtonColor = false
CmdX.Font = Enum.Font.SourceSansBold
CmdX.Text = "CMD-X"
CmdX.TextColor3 = Color3.fromRGB(255, 255, 255)
CmdX.TextScaled = true
CmdX.TextSize = 14.000
CmdX.TextWrapped = true

Title_4.Name = "Title"
Title_4.Parent = CmdX
Title_4.BackgroundColor3 = Color3.fromRGB(223, 190, 0)
Title_4.BorderSizePixel = 0
Title_4.Position = UDim2.new(0, 0, 1, 0)
Title_4.Size = UDim2.new(0, 134, 0, 20)
Title_4.Font = Enum.Font.SourceSansBold
Title_4.Text = "'Risky Admin'"
Title_4.TextColor3 = Color3.fromRGB(138, 103, 0)
Title_4.TextScaled = true
Title_4.TextSize = 14.000
Title_4.TextWrapped = true

CloseMe.Name = "CloseMe"
CloseMe.Parent = BuildFrame
CloseMe.BackgroundColor3 = Color3.fromRGB(255, 89, 89)
CloseMe.BorderSizePixel = 0
CloseMe.Position = UDim2.new(0.962168992, 0, 0, 0)
CloseMe.Size = UDim2.new(0, 30, 0, 27)
CloseMe.Font = Enum.Font.SourceSansLight
CloseMe.Text = "X"
CloseMe.TextColor3 = Color3.fromRGB(255, 255, 255)
CloseMe.TextScaled = true
CloseMe.TextSize = 14.000
CloseMe.TextWrapped = true

UserName.Name = "UserName"
UserName.Parent = BuildFrame
UserName.BackgroundColor3 = Color3.fromRGB(31, 31, 31)
UserName.BorderSizePixel = 0
UserName.Position = UDim2.new(0.0138713717, 0, 0.0131086148, 0)
UserName.Size = UDim2.new(0, 200, 0, 50)
UserName.Font = Enum.Font.SourceSansLight
UserName.Text = "UserName"
UserName.TextColor3 = Color3.fromRGB(255, 255, 255)
UserName.TextScaled = true
UserName.TextSize = 14.000
UserName.TextWrapped = true

OpenMenu.Name = "OpenMenu"
OpenMenu.Parent = RobloxHub
OpenMenu.BackgroundColor3 = Color3.fromRGB(255, 71, 191)
OpenMenu.BorderColor3 = Color3.fromRGB(85, 255, 255)
OpenMenu.Position = UDim2.new(0.858333349, 0, 0.0147895338, 0)
OpenMenu.Size = UDim2.new(0, 200, 0, 50)
OpenMenu.Visible = false
OpenMenu.Font = Enum.Font.SourceSans
OpenMenu.Text = "Open"
OpenMenu.TextColor3 = Color3.fromRGB(255, 255, 255)
OpenMenu.TextScaled = true
OpenMenu.TextSize = 14.000
OpenMenu.TextWrapped = true

-- Scripts:

local function BSNLJC_fake_script() -- GamesFrame.Button_Settings 
	local script = Instance.new('LocalScript', GamesFrame)

	-- Colors
	
	script.Parent.SR4.MouseEnter:Connect(function()
		script.Parent.SR4.BackgroundColor3 = Color3.new(0.113725, 0.145098, 0.356863)
	end)
	
	script.Parent.SR4.MouseLeave:Connect(function()
		script.Parent.SR4.BackgroundColor3 = Color3.new(0.164706, 0.164706, 0.164706)
	end)
	
	script.Parent.TOH.MouseLeave:Connect(function()
		script.Parent.TOH.BackgroundColor3 = Color3.new(0.113725, 0.145098, 0.356863)
	end)
	
	script.Parent.TOH.MouseLeave:Connect(function()
		script.Parent.TOH.BackgroundColor3 = Color3.new(0.164706, 0.164706, 0.164706)
	end)
	
	script.Parent.WZ.MouseEnter:Connect(function()
		script.Parent.WZ.BackgroundColor3 = Color3.new(0.113725, 0.145098, 0.356863)
	end)
	
	script.Parent.WZ.MouseLeave:Connect(function()
		script.Parent.WZ.BackgroundColor3 = Color3.new(0.164706, 0.164706, 0.164706)
	end)
	
	-- Connections
	
	script.Parent.SR4.MouseButton1Down:Connect(function()
		wait(0.1)
		script.Parent.Parent.Parent.HomeNgames:Play()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/Reg...", true))()
	end)
	
	script.Parent.TOH.MouseButton1Down:Connect(function()
		wait(0.1)
		script.Parent.Parent.Parent.HomeNgames:Play()
		loadstring(game:HttpGet(('https://pastebin.com/raw/HpPEkAvw'),true))()
	end)
	
	script.Parent.WZ.MouseButton1Down:Connect(function()
		wait(0.1)
		script.Parent.Parent.Parent.HomeNgames:Play()
		loadstring(game:HttpGet(('https://pastebin.com/raw/FDnexrrv'),true))()
	end)
end
coroutine.wrap(BSNLJC_fake_script)()
local function XAVA_fake_script() -- BuildFrame.Settings 
	local script = Instance.new('LocalScript', BuildFrame)

	local BuildFrame = script.Parent.Parent.BuildFrame
	
	script.Parent.Parent.BuildFrame.Active = true
	script.Parent.Parent.BuildFrame.Draggable = true
	
	wait(0.2)
	script.Parent.Parent.Background_Music_Open.Playing = true
	-- SSD
	
	script.Parent.Home.MouseEnter:Connect(function()
		script.Parent.Home.BackgroundColor3 = Color3.new(0.345098, 0.215686, 0)
	end)
	
	script.Parent.Home.MouseLeave:Connect(function()
		script.Parent.Home.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
	end)
	
	script.Parent.Home.MouseButton1Down:Connect(function()
		script.Parent.Parent.Background_Music_Open.Playing = false
		script.Parent.Parent.HomeNgames:Play()
		wait(0.1)
		script.Parent.Parent.HomeNgames:Pause()
		script.Parent.Parent.Background_Music_Open.Playing = true
		script.Parent.HomeFrame.Visible = true
		script.Parent.GamesFrame.Visible = false
	end)
	
	-- LLL
	
	script.Parent.Games.MouseEnter:Connect(function()
		script.Parent.Games.BackgroundColor3 = Color3.new(0.345098, 0.215686, 0)
	end)
	
	script.Parent.Games.MouseLeave:Connect(function()
		script.Parent.Games.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
	end)
	
	script.Parent.Games.MouseButton1Down:Connect(function()
		script.Parent.Parent.Background_Music_Open.Playing = false
		script.Parent.Parent.HomeNgames:Play()
		wait(0.1)
		script.Parent.Parent.HomeNgames:Pause()
		script.Parent.Parent.Background_Music_Open.Playing = true
		script.Parent.HomeFrame.Visible = false
		script.Parent.GamesFrame.Visible = true
	end)
	
	-- close
	
	script.Parent.CloseMe.MouseButton1Down:Connect(function()
		if game.Lighting.MenuOpen then
			game.Lighting.MenuOpen.Enabled = false
			script.Parent.Parent.OpenMenu.Visible = true
			script.Parent.Parent.BuildFrame.Visible = false
			wait()
			script.Parent.Parent.Background_Music_Open:Pause()
		end
	end)
	
	local UserName = script.Parent.UserName
	
	UserName.Text = game.Players.LocalPlayer.Name
	
end
coroutine.wrap(XAVA_fake_script)()
local function VJAVJCW_fake_script() -- RobloxHub.ForBlur 
	local script = Instance.new('LocalScript', RobloxHub)

	if script.Parent.BuildFrame.Visible == true then
		print("Open")
		script.Parent.MenuOpen.Parent = game.Lighting
		if game.Lighting.MenuOpen then
			game.Lighting.MenuOpen.Enabled = true
		elseif script.Parent.BuildFrame.Visible ~= true then
			script.Parent.Background_Music_Open.Paused = true
			game.Lighting.MenuOpen.Enabled = false
		elseif script.Parent.BuildFrame.Visible ~= false then
			game.Lighting.MenuOpen.Enable = true
			print("Not Open")
		end
	end
end
coroutine.wrap(VJAVJCW_fake_script)()
local function XIEEUO_fake_script() -- OpenMenu.LocalScript 
	local script = Instance.new('LocalScript', OpenMenu)

	--
	script.Parent.Parent.OpenMenu.MouseButton1Down:Connect(function()
		script.Parent.Parent.OpenMenu.Visible = false
		script.Parent.Parent.BuildFrame.Visible = true
		script.Parent.Parent.Background_Music_Open:Play()
		game.Lighting.MenuOpen.Enabled = true
	end)
end
coroutine.wrap(XIEEUO_fake_script)()
