-- Made By Daniel
local DeadlyAdmin = Instance.new("ScreenGui")
local CheckPlayer = Instance.new("Frame")
local whitelist = Instance.new("TextLabel")
local Status = Instance.new("TextLabel")
local scanning = Instance.new("TextLabel")
local MainGUI = Instance.new("Frame")
local welcome = Instance.new("TextLabel")
local X = Instance.new("TextButton")
local jailbreak = Instance.new("TextButton")
local LowAdmin = Instance.new("TextButton")
local randomscript = Instance.new("TextButton")
local gamegui = Instance.new("TextButton")
local randomscript2 = Instance.new("TextButton")
local randomscript_2 = Instance.new("TextButton")
local randomscript5 = Instance.new("TextButton")
local randomscript3 = Instance.new("TextButton")
local randomscript6 = Instance.new("TextButton")
local randomscript4 = Instance.new("TextButton")
local promote = Instance.new("TextLabel")
local OpenGUI = Instance.new("Frame")
local OPEN = Instance.new("TextButton")

--Properties:

DeadlyAdmin.Name = "DeadlyAdmin"
DeadlyAdmin.Parent = game.CoreGui

CheckPlayer.Name = "CheckPlayer"
CheckPlayer.Parent = DeadlyAdmin
CheckPlayer.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
CheckPlayer.BorderColor3 = Color3.fromRGB(255, 0, 0)
CheckPlayer.Position = UDim2.new(0.682812452, 0, 0.244471759, 0)
CheckPlayer.Size = UDim2.new(0, 423, 0, 416)
CheckPlayer.Active = true
CheckPlayer.Draggable = true

whitelist.Name = "whitelist"
whitelist.Parent = CheckPlayer
whitelist.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
whitelist.BorderColor3 = Color3.fromRGB(0, 0, 255)
whitelist.Size = UDim2.new(0, 423, 0, 50)
whitelist.Font = Enum.Font.SourceSans
whitelist.Text = "Whitelist"
whitelist.TextColor3 = Color3.fromRGB(255, 255, 255)
whitelist.TextScaled = true
whitelist.TextSize = 14.000
whitelist.TextStrokeColor3 = Color3.fromRGB(217, 0, 255)
whitelist.TextStrokeTransparency = 0.000
whitelist.TextWrapped = true

Status.Name = "Status"
Status.Parent = CheckPlayer
Status.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Status.BackgroundTransparency = 1.000
Status.Position = UDim2.new(0.0543735214, 0, 0.185096145, 0)
Status.Size = UDim2.new(0, 376, 0, 240)
Status.Font = Enum.Font.SourceSans
Status.Text = "Please be patient while we scan if you are whitelisted"
Status.TextColor3 = Color3.fromRGB(0, 0, 255)
Status.TextSize = 55.000
Status.TextWrapped = true

scanning.Name = "scanning"
scanning.Parent = CheckPlayer
scanning.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
scanning.BackgroundTransparency = 1.000
scanning.Position = UDim2.new(0, 0, 0.725961566, 0)
scanning.Size = UDim2.new(0, 423, 0, 114)
scanning.Font = Enum.Font.SourceSans
scanning.Text = "By YandZ#8406 | lowkey#6429"
scanning.TextColor3 = Color3.fromRGB(170, 0, 255)
scanning.TextSize = 40.000
scanning.TextWrapped = true

MainGUI.Name = "MainGUI"
MainGUI.Parent = DeadlyAdmin
MainGUI.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
MainGUI.BorderColor3 = Color3.fromRGB(255, 0, 255)
MainGUI.Position = UDim2.new(0.693, 0,0.272, 0)
MainGUI.Size = UDim2.new(0, 423, 0, 416)
MainGUI.Visible = false
MainGUI.Active = true
MainGUI.Draggable = true

welcome.Name = "welcome"
welcome.Parent = MainGUI
welcome.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
welcome.BorderColor3 = Color3.fromRGB(0, 255, 255)
welcome.Size = UDim2.new(0, 365, 0, 50)
welcome.Font = Enum.Font.SourceSans
welcome.Text = "Welcome To Low Fuel GUI"
welcome.TextColor3 = Color3.fromRGB(0, 0, 0)
welcome.TextSize = 30.000
welcome.TextStrokeColor3 = Color3.fromRGB(255, 255, 0)
welcome.TextStrokeTransparency = 0.000
welcome.TextWrapped = true

X.Name = "X"
X.Parent = MainGUI
X.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
X.BorderColor3 = Color3.fromRGB(255, 0, 255)
X.Position = UDim2.new(0.862884164, 0, 0, 0)
X.Size = UDim2.new(0, 58, 0, 50)
X.Font = Enum.Font.SourceSans
X.Text = "X"
X.TextColor3 = Color3.fromRGB(255, 0, 0)
X.TextScaled = true
X.TextSize = 14.000
X.TextWrapped = true
X.MouseButton1Click:connect(function()
	MainGUI.Visible = false
	OpenGUI.Visible = true
end)

jailbreak.Name = "jailbreak"
jailbreak.Parent = MainGUI
jailbreak.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
jailbreak.BackgroundTransparency = 1.000
jailbreak.BorderColor3 = Color3.fromRGB(63, 255, 34)
jailbreak.Position = UDim2.new(0.0638298541, 0, 0.365384579, 0)
jailbreak.Size = UDim2.new(0, 159, 0, 32)
jailbreak.Font = Enum.Font.SourceSans
jailbreak.Text = "Jail Break"
jailbreak.TextColor3 = Color3.fromRGB(0, 0, 0)
jailbreak.TextScaled = true
jailbreak.TextSize = 14.000
jailbreak.TextStrokeColor3 = Color3.fromRGB(255, 0, 255)
jailbreak.TextStrokeTransparency = 0.000
jailbreak.TextWrapped = true
jailbreak.MouseButton1Click:connect(function()
	-- script goes here
end)

LowAdmin.Name = "LowAdmin"
LowAdmin.Parent = MainGUI
LowAdmin.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
LowAdmin.BackgroundTransparency = 1.000
LowAdmin.BorderColor3 = Color3.fromRGB(255, 0, 0)
LowAdmin.Position = UDim2.new(0.0638297871, 0, 0.206730768, 0)
LowAdmin.Size = UDim2.new(0, 159, 0, 32)
LowAdmin.Font = Enum.Font.SourceSans
LowAdmin.Text = "Low Fuel Admin"
LowAdmin.TextColor3 = Color3.fromRGB(0, 0, 0)
LowAdmin.TextScaled = true
LowAdmin.TextSize = 14.000
LowAdmin.TextStrokeColor3 = Color3.fromRGB(255, 0, 255)
LowAdmin.TextStrokeTransparency = 0.000
LowAdmin.TextWrapped = true
LowAdmin.MouseButton1Click:connect(function()
	-- script goes here
end)

randomscript.Name = "randomscript"
randomscript.Parent = MainGUI
randomscript.BackgroundColor3 = Color3.fromRGB(53, 53, 255)
randomscript.BackgroundTransparency = 1.000
randomscript.BorderColor3 = Color3.fromRGB(255, 0, 0)
randomscript.Position = UDim2.new(0.543735206, 0, 0.365384668, 0)
randomscript.Size = UDim2.new(0, 159, 0, 32)
randomscript.Font = Enum.Font.SourceSans
randomscript.Text = "Coming Soon..."
randomscript.TextColor3 = Color3.fromRGB(0, 0, 0)
randomscript.TextScaled = true
randomscript.TextSize = 14.000
randomscript.TextStrokeColor3 = Color3.fromRGB(255, 0, 255)
randomscript.TextStrokeTransparency = 0.000
randomscript.TextWrapped = true
randomscript.MouseButton1Click:connect(function()
	-- script goes here
end)

gamegui.Name = "gamegui"
gamegui.Parent = MainGUI
gamegui.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
gamegui.BackgroundTransparency = 1.000
gamegui.BorderColor3 = Color3.fromRGB(255, 255, 0)
gamegui.Position = UDim2.new(0.543735206, 0, 0.206730783, 0)
gamegui.Size = UDim2.new(0, 159, 0, 32)
gamegui.Font = Enum.Font.SourceSans
gamegui.Text = "Many Game GUI"
gamegui.TextColor3 = Color3.fromRGB(0, 0, 0)
gamegui.TextScaled = true
gamegui.TextSize = 14.000
gamegui.TextStrokeColor3 = Color3.fromRGB(255, 0, 255)
gamegui.TextStrokeTransparency = 0.000
gamegui.TextWrapped = true
gamegui.MouseButton1Click:connect(function()
	-- script goes here
end)

randomscript2.Name = "randomscript2"
randomscript2.Parent = MainGUI
randomscript2.BackgroundColor3 = Color3.fromRGB(53, 53, 255)
randomscript2.BackgroundTransparency = 1.000
randomscript2.BorderColor3 = Color3.fromRGB(255, 0, 0)
randomscript2.Position = UDim2.new(0.0638297945, 0, 0.497596145, 0)
randomscript2.Size = UDim2.new(0, 159, 0, 32)
randomscript2.Font = Enum.Font.SourceSans
randomscript2.Text = "Coming Soon..."
randomscript2.TextColor3 = Color3.fromRGB(0, 0, 0)
randomscript2.TextScaled = true
randomscript2.TextSize = 14.000
randomscript2.TextStrokeColor3 = Color3.fromRGB(255, 0, 255)
randomscript2.TextStrokeTransparency = 0.000
randomscript2.TextWrapped = true
randomscript2.MouseButton1Click:connect(function()
	-- script goes here
end)

randomscript_2.Name = "randomscript"
randomscript_2.Parent = MainGUI
randomscript_2.BackgroundColor3 = Color3.fromRGB(53, 53, 255)
randomscript_2.BackgroundTransparency = 1.000
randomscript_2.BorderColor3 = Color3.fromRGB(255, 0, 0)
randomscript_2.Position = UDim2.new(0.543735206, 0, 0.497596204, 0)
randomscript_2.Size = UDim2.new(0, 159, 0, 32)
randomscript_2.Font = Enum.Font.SourceSans
randomscript_2.Text = "Coming Soon..."
randomscript_2.TextColor3 = Color3.fromRGB(0, 0, 0)
randomscript_2.TextScaled = true
randomscript_2.TextSize = 14.000
randomscript_2.TextStrokeColor3 = Color3.fromRGB(255, 0, 255)
randomscript_2.TextStrokeTransparency = 0.000
randomscript_2.TextWrapped = true
randomscript_2.MouseButton1Click:connect(function()
	-- script goes here
end)

randomscript5.Name = "randomscript5"
randomscript5.Parent = MainGUI
randomscript5.BackgroundColor3 = Color3.fromRGB(53, 53, 255)
randomscript5.BackgroundTransparency = 1.000
randomscript5.BorderColor3 = Color3.fromRGB(255, 0, 0)
randomscript5.Position = UDim2.new(0.0638297945, 0, 0.629807711, 0)
randomscript5.Size = UDim2.new(0, 159, 0, 32)
randomscript5.Font = Enum.Font.SourceSans
randomscript5.Text = "Coming Soon..."
randomscript5.TextColor3 = Color3.fromRGB(0, 0, 0)
randomscript5.TextScaled = true
randomscript5.TextSize = 14.000
randomscript5.TextStrokeColor3 = Color3.fromRGB(255, 0, 255)
randomscript5.TextStrokeTransparency = 0.000
randomscript5.TextWrapped = true
randomscript5.MouseButton1Click:connect(function()
	-- script goes here
end)

randomscript3.Name = "randomscript3"
randomscript3.Parent = MainGUI
randomscript3.BackgroundColor3 = Color3.fromRGB(53, 53, 255)
randomscript3.BackgroundTransparency = 1.000
randomscript3.BorderColor3 = Color3.fromRGB(255, 0, 0)
randomscript3.Position = UDim2.new(0.543735206, 0, 0.62980777, 0)
randomscript3.Size = UDim2.new(0, 159, 0, 32)
randomscript3.Font = Enum.Font.SourceSans
randomscript3.Text = "Coming Soon..."
randomscript3.TextColor3 = Color3.fromRGB(0, 0, 0)
randomscript3.TextScaled = true
randomscript3.TextSize = 14.000
randomscript3.TextStrokeColor3 = Color3.fromRGB(255, 0, 255)
randomscript3.TextStrokeTransparency = 0.000
randomscript3.TextWrapped = true
randomscript3.MouseButton1Click:connect(function()
	-- script goes here
end)

randomscript6.Name = "randomscript6"
randomscript6.Parent = MainGUI
randomscript6.BackgroundColor3 = Color3.fromRGB(53, 53, 255)
randomscript6.BackgroundTransparency = 1.000
randomscript6.BorderColor3 = Color3.fromRGB(255, 0, 0)
randomscript6.Position = UDim2.new(0.0638297945, 0, 0.783653855, 0)
randomscript6.Size = UDim2.new(0, 159, 0, 32)
randomscript6.Font = Enum.Font.SourceSans
randomscript6.Text = "Coming Soon..."
randomscript6.TextColor3 = Color3.fromRGB(0, 0, 0)
randomscript6.TextScaled = true
randomscript6.TextSize = 14.000
randomscript6.TextStrokeColor3 = Color3.fromRGB(255, 0, 255)
randomscript6.TextStrokeTransparency = 0.000
randomscript6.TextWrapped = true
randomscript6.MouseButton1Click:connect(function()
	-- script goes here
end)

randomscript4.Name = "randomscript4"
randomscript4.Parent = MainGUI
randomscript4.BackgroundColor3 = Color3.fromRGB(53, 53, 255)
randomscript4.BackgroundTransparency = 1.000
randomscript4.BorderColor3 = Color3.fromRGB(255, 0, 0)
randomscript4.Position = UDim2.new(0.543735206, 0, 0.783653915, 0)
randomscript4.Size = UDim2.new(0, 159, 0, 32)
randomscript4.Font = Enum.Font.SourceSans
randomscript4.Text = "Coming Soon..."
randomscript4.TextColor3 = Color3.fromRGB(0, 0, 0)
randomscript4.TextScaled = true
randomscript4.TextSize = 14.000
randomscript4.TextStrokeColor3 = Color3.fromRGB(255, 0, 255)
randomscript4.TextStrokeTransparency = 0.000
randomscript4.TextWrapped = true
randomscript4.MouseButton1Click:connect(function()
	-- script goes here
end)

promote.Name = "promote"
promote.Parent = MainGUI
promote.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
promote.BorderColor3 = Color3.fromRGB(255, 0, 0)
promote.Position = UDim2.new(-1.428, 0,-0.786, 0)
promote.Size = UDim2.new(0, 497, 0, 65)
promote.Font = Enum.Font.SourceSans
promote.Text = "N/A"
promote.TextColor3 = Color3.fromRGB(0, 0, 0)
promote.TextScaled = true
promote.TextSize = 14.000
promote.TextStrokeColor3 = Color3.fromRGB(94, 255, 7)
promote.TextStrokeTransparency = 0.000
promote.TextWrapped = true
promote.Active = true
promote.Draggable = false

OpenGUI.Name = "OpenGUI"
OpenGUI.Parent = DeadlyAdmin
OpenGUI.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
OpenGUI.BackgroundTransparency = 1.000
OpenGUI.Position = UDim2.new(0.522916675, 0, 0.389434904, 0)
OpenGUI.Size = UDim2.new(0, 100, 0, 100)
OpenGUI.Visible = false

OPEN.Name = "OPEN"
OPEN.Parent = OpenGUI
OPEN.BackgroundColor3 = Color3.fromRGB(39, 115, 255)
OPEN.BorderColor3 = Color3.fromRGB(255, 0, 0)
OPEN.Position = UDim2.new(-0.320000112, 0, -2.50999999, 0)
OPEN.Size = UDim2.new(0, 125, 0, 30)
OPEN.Text = "Open"
OPEN.TextColor3 = Color3.fromRGB(255, 0, 0)
OPEN.TextScaled = true
OPEN.TextSize = 14.000
OPEN.TextStrokeColor3 = Color3.fromRGB(47, 200, 255)
OPEN.TextStrokeTransparency = 0.000
OPEN.TextWrapped = true
OPEN.Active = true
OPEN.Draggable = true
OPEN.MouseButton1Click:connect(function()
	MainGUI.Visible = true
	OpenGUI.Visible = false
end)

-- Scripts:

local function KFLQIT_fake_script() -- MainGUI.LocalScript 
	local script = Instance.new('LocalScript', MainGUI)

	function zigzag(X) return math.acos(math.cos(X*math.pi))/math.pi end
	
	counter = 0
	
	while wait(0.1)do
	 script.Parent.BackgroundColor3 = Color3.fromHSV(zigzag(counter),1,1)
	 
	 counter = counter + 0.01
	end
end
coroutine.wrap(KFLQIT_fake_script)()
local function DKAZ_fake_script() -- promote.LocalScript 
	local script = Instance.new('LocalScript', promote)

	print ("Gui Made By Daniel")
	
	wait(1)
	script.Parent.Text = "Made By Daniel"
	wait(8)
	script.Parent.Text = "Add YandZ#8406 lowkey#6429"
	wait(15)
	script.Parent.Text = "Make sure to Join the Server!"
	wait(10)
	script.Parent.Text = "https://discord.gg/C2sdyV"
	wait(30)
	script.Parent.Text = "Made By Daniel"
	wait(8)
	script.Parent.Text = "Add YandZ#8406 lowkey#6429"
	wait(15)
	script.Parent.Text = "Make sure to Join the Server!"
	wait(10)
	script.Parent.Text = "https://discord.gg/C2sdyV"
	wait(30)
	script.Parent.Text = "Made By Daniel"
	wait(8)
	script.Parent.Text = "Add YandZ#8406 lowkey#6429"
	wait(15)
	script.Parent.Text = "Make sure to Join the Server!"
	wait(10)
	script.Parent.Text = "https://discord.gg/C2sdyV"
	wait(30)
	script.Parent.Text = "Made By Daniel"
	wait(8)
	script.Parent.Text = "Add YandZ#8406 lowkey#6429"
	wait(15)
	script.Parent.Text = "Make sure to Join the Server!"
	wait(10)
	script.Parent.Text = "https://discord.gg/C2sdyV"
	wait(30)
	script.Parent.Text = "Made By Daniel"
	wait(8)
	script.Parent.Text = "Add YandZ#8406 lowkey#6429"
	wait(15)
	script.Parent.Text = "Make sure to Join the Server!"
	wait(10)
	script.Parent.Text = "https://discord.gg/C2sdyV"
	wait(30)
	script.Parent.Text = "Made By Daniel"
	wait(8)
	script.Parent.Text = "Add YandZ#8406 lowkey#6429"
	wait(15)
	script.Parent.Text = "Make sure to Join the Server!"
	wait(10)
	script.Parent.Text = "https://discord.gg/C2sdyV"
	wait(30)
	script.Parent.Text = "Made By Daniel"
	wait(8)
	script.Parent.Text = "Add YandZ#8406 lowkey#6429"
	wait(15)
	script.Parent.Text = "Make sure to Join the Server!"
	wait(10)
	script.Parent.Text = "https://discord.gg/C2sdyV"
	wait(30)
	script.Parent.Text = "Made By Daniel"
	wait(8)
	script.Parent.Text = "Add YandZ#8406 lowkey#6429"
	wait(15)
	script.Parent.Text = "Make sure to Join the Server!"
	wait(10)
	script.Parent.Text = "https://discord.gg/C2sdyV"
	wait(30)
	script.Parent.Text = "Made By Daniel"
	wait(8)
	script.Parent.Text = "Add YandZ#8406 lowkey#6429"
	wait(15)
	script.Parent.Text = "Make sure to Join the Server!"
	wait(10)
	script.Parent.Text = "https://discord.gg/C2sdyV"
	wait(30)
	script.Parent.Text = "Made By Daniel"
	wait(8)
	script.Parent.Text = "Add YandZ#8406 lowkey#6429"
	wait(15)
	script.Parent.Text = "Make sure to Join the Server!"
	wait(10)
	script.Parent.Text = "https://discord.gg/C2sdyV"
	wait(30)
	script.Parent.Text = "Made By Daniel"
	wait(8)
	script.Parent.Text = "Add YandZ#8406 lowkey#6429"
	wait(15)
	script.Parent.Text = "Make sure to Join the Server!"
	wait(10)
	script.Parent.Text = "https://discord.gg/C2sdyV"
	wait(30)
	script.Parent.Text = "Made By Daniel"
	wait(8)
	script.Parent.Text = "Add YandZ#8406 lowkey#6429"
	wait(15)
	script.Parent.Text = "Make sure to Join the Server!"
	wait(10)
	script.Parent.Text = "https://discord.gg/C2sdyV"
	wait(30)
end
coroutine.wrap(DKAZ_fake_script)()
-- whitelist
if game.Players.LocalPlayer.Name == "8hpx" then
	wait(2)
    scanning.Text = "Hello 8hpx! Happy To have you here Co-Owner! :)"
    wait(3)
OpenGUI.Visible = true
CheckPlayer.Visible = false
elseif game.Players.LocalPlayer.Name == "HaxWeak" then
	wait(5)
scanning.Text = "Hello HaxWeak! Happy to have you here Owner! :)"
wait(3)
OpenGUI.Visible = true
CheckPlayer.Visible = false
elseif game.Players.LocalPlayer.Name == "WhiteH_oes2" then
	wait(2)
scanning.Text = "Hello WhiteH_oes2! Happy to have you here Daniel's Alt! :)"
wait(3)
OpenGUI.Visible = true
CheckPlayer.Visible = false
elseif game.Players.LocalPlayer.Name == "AlphaBanners" then
	wait(7)
scanning.Text = "Hello AlphaBanners! Happy to have you here Buyer! :)"
wait(3)
OpenGUI.Visible = true
CheckPlayer.Visible = false
elseif game.Players.LocalPlayer.Name == "Blacklisted" then
	game.Players.LocalPlayer:kick("You are Blacklisted from this admin")
else
	game.Players.LocalPlayer:kick("You are not whitelisted please contact YandZ#8406 or lowkey#6429")
end
