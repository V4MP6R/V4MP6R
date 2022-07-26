--Just Copy What I Do With Tabs And Section And Your Good To Add New TABS

-- i made it draggable

--Fixed By Nathan | Script Dev#4468

game.StarterGui:SetCore("SendNotification", {

    Title = "Credits"; -- the title (ofc)

    Text = "Made By V4MP6RE And Fixed By Nathan "; -- what the text says (ofc)

    Duration = 10; -- how long the notification should in secounds

  })

local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/Unknownuser11736/suntaiteam/main/kavouilibrary/fixedsliders"))()

local Window = Library.CreateLib("Gaming Chair Hub", "BloodTheme")

--Tabs

local Tab = Window:NewTab("Credits")

local Section1 = Tab:NewSection("Fixed By Nathan | Script Dev#4468")

local Section2 = Tab:NewSection("Inspired by MatzScripter#7980")

local Section3 = Tab:NewSection("Fixed by TANSHU | Scripter Learning Lua#5576")

local Section4 = Tab:NewSection("Inspired by Gaming Scripter")

local Section5 = Tab:NewSection("Made By V4MP6RE#6350")

local Tab2 = Window:NewTab("Keyboard")

local Section5 = Tab2:NewSection("Keyboard")

local Tab3 = Window:NewTab("Sword fighting")

local Section6 = Tab3:NewSection("Fixed By Nathan")

local Tab4 = Window:NewTab("MM2")

local Section7 = Tab4:NewSection("MM2 OP GUI")

local Tab5 = Window:NewTab("Bedwars")

local Section8 = Tab5:NewSection("Darkai Op")

local Tab6 = Window:NewTab("Prision Life") 

local Section9 = Tab6:NewSection("Prison Fucker") 

local Tab7 = Window:NewTab("Fun")

local Section10 = Tab7:NewSection("Animations") 

local Section11 = Tab7:NewSection("Fling")

local Section12 = Tab7:NewSection("Fly") 

local Tab8 = Window:NewTab("Arsenal")

local Section13 = Tab8:NewSection("Arsenal")

local Tab9 = Window:NewTab("Brookhaven")

local Tab10 = Window:NewTab("Prison life")

local Tab11= Window:NewTab("Chaos")
   
local Tab12 = Window:NewTab("Netless")

local Tab13 = Window:NewTab("Pop it trading")

local Tab14 = Window:NewTab("Pls donate")

local Tab15 = Window:NewTab("Pet Sim X")

local Tab16 = Window:NewTab("Blox Fruit")

local Tab17 = Window:NewTab("Wieght Lifting sim")

local Tab17 = Window:NewTab("Other Scripts / Hubs")
--Script

local Button1 = Section5:NewButton("Keyboard", "A Keyboard For Mobile", function()

    loadstring(game:HttpGet(('https://raw.githubusercontent.com/manimcool21/Keyboard-FE/main/Protected%20(3).lua'),true))()

end)

Section6:NewLabel("Circle Reach Etc")

local Button2 = Section6:NewButton("Circle Reach", "The First One", function()

    local library = loadstring(game:HttpGet(('https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/wall%20v3')))()

local w = library:CreateWindow("Gaming Chair Sword fight") -- Creates the window

local b = w:CreateFolder("useful") -- Creates the folder(U will put here your buttons,etc)

b:Label("Useful Stuff",{

    TextSize = 25; -- Self Explaining

    TextColor = Color3.fromRGB(255,255,255); -- Self Explaining

    BgColor = Color3.fromRGB(69,69,69); -- Self Explaining

    

}) 

b:Button("Circle Reach",function()

    local ScreenGui = Instance.new("ScreenGui")

local Frame = Instance.new("Frame")

local Reach = Instance.new("TextButton")

ScreenGui.Parent = game.CoreGui

ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = ScreenGui

Frame.BorderSizePixel = 0

Frame.Position = UDim2.new(0.0809101239, 0, 0.203790441, 0)

Frame.Size = UDim2.new(0, 150, 0, 90)

Frame.Active = true

Frame.Draggable = true

Reach.Name = " gui by V4MP6RE"

Reach.Parent = Frame

Reach.BorderSizePixel = 0

Reach.Position = UDim2.new(0, 0, 0.039088048, 0)

Reach.Size = UDim2.new(0, 143, 0, 38)

Reach.Font = Enum.Font.GothamBlack

Reach.Text = "raz's reach (click me)"

Reach.TextSize = 14.000

Reach.MouseButton1Down:connect(function()

  local sound = Instance.new("Sound")

  sound.SoundId = "rbxassetid://4771152040"

  sound.Parent = game:GetService("SoundService")

  sound:Play()

  wait()

  game.StarterGui:SetCore("SendNotification", {

    Title = "how to use this amazing reach?"; -- the title (ofc)

    Text = "equip your item first then press the button tell me if u want bigger reach or smaller imposter#4878"; -- what the text says (ofc)

    Duration = 10; -- how long the notification should in secounds

  })

  for i,v in pairs(game:GetService'Players'.LocalPlayer.Character:GetChildren()) do

    if v:isA("Tool") then

      local a = Instance.new("SelectionSphere",v.Handle)

      v.Handle.Massless = true

      v.Handle.Transparency = 0

      a.Adornee = v.Handle

      v.Handle.Size = Vector3.new(7, 7 , 7)

      local selectionBox = Instance.new("SelectionSphere",v.Handle)

      selectionBox.Adornee = v.Handle

      SurfaceSelection = 0

    end

  end

 end)

end)

b:Toggle("blizzy",function(state)

    shared.toggle = state

    loadstring(game:HttpGet("https://gist.githubusercontent.com/OptioniaI/b7326d42da50a52edf2c511533ae603d/raw/137840f68aef962c4bb6ae01009d5f7a5af4627d/blz-reach"))()

end)

b:Slider("Speed",{

    min = 10; -- min value of the slider

    max = 50; -- max value of the slider

    precise = true; -- max 2 decimals

},function(value)

    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = value

end)

b:Dropdown("Dropdown",{"A","B","C"},true,function(mob) --true/false, replaces the current title "Dropdown" with the option that t

    print(mob)

end)

b:Bind("Bind",Enum.KeyCode.C,function() --Default bind

    print("Yes")

end)

b:ColorPicker("ColorPicker",Color3.fromRGB(255,0,0),function(color) --Default color

    print(color)

end)

b:Box("Jumpower","value",function(value) -- "number" or "string"

game.Players.LocalPlayer.Character.Humanoid.JumpPower = value

end)

b:DestroyGui()

Reach:Destroy()

--[[

How to refresh a dropdown:

1)Create the dropdown and save it in a variable

local yourvariable = b:Dropdown("Hi",yourtable,function(a)

    print(a)

end)

2)Refresh it using the function

yourvariable:Refresh(yourtable)

How to refresh a label:

1)Create your label and save it in a variable

local yourvariable = b:Label("Pretty Useless NGL",{

    TextSize = 25; -- Self Explaining

    TextColor = Color3.fromRGB(255,255,255);

    BgColor = Color3.fromRGB(69,69,69);

})

2)Refresh it using the function

yourvariable:Refresh("Hello") It will only change the text ofc

]]

local b = w:CreateFolder("by V4MP6RE") -- Creates the folder(U will put here your buttons,etc)

end)

Section6:NewLabel("Auto Clicker")

local Button3 = Section6:NewButton("Auto Clicker", "Auto Clicker For Mobile", function()

    --// Setting \--

local range = 99e9

--// Variable \--

local player = game:GetService("Players").LocalPlayer

--// Script \--

game:GetService("RunService").RenderStepped:Connect(function()

    local p = game.Players:GetPlayers()

    for i = 2, #p do local v = p[i].Character

        if v and v:FindFirstChild("Humanoid") and v.Humanoid.Health > 0 and v:FindFirstChild("HumanoidRootPart") and player:DistanceFromCharacter(v.HumanoidRootPart.Position) <= range then

            local tool = player.Character and player.Character:FindFirstChildOfClass("Tool")

            if tool and tool:FindFirstChild("Handle") then

                tool:Activate()

                for i,v in next, v:GetChildren() do

                    if v:IsA("BasePart") then

                        firetouchinterest(tool.Handle,v,0)

                        firetouchinterest(tool.Handle,v,1)

                    end

                end

            end

        end

    end

end)

end)

local Button4 = Section7:NewButton("MM2", "A MM2 hack For Mobile", function()

    local library = loadstring(game:HttpGet(('https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/wall%20v3')))()

local w = library:CreateWindow("Mm2 Micro And Vamp") -- Creates the window

local b = w:CreateFolder("Mm2Scripts") -- Creates the folder(U will put here your buttons,etc)

b:Label("Murder Mystery",{

    TextSize = 25; -- Self Explaining

    TextColor = Color3.fromRGB(255,255,255); -- Self Explaining

    BgColor = Color3.fromRGB(69,69,69); -- Self Explaining

    

}) 

b:Button("Mm2 Script 1",function()

    loadstring(game:HttpGet("https://raw.githubusercontent.com/Drifter0507/scripts/main/mm2", true))()

end)

b:Button("Mm2 Script 2",function()

    loadstring(game:HttpGet(('https://raw.githubusercontent.com/MarsQQ/ScriptHubScripts/master/MM2%20Admin%20Panel'),true))()

end)

b:Button("Mm2 Script 2",function()

   loadstring(game:HttpGet("https://raw.githubusercontent.com/Neon-Fox/roblox-scripts/main/VynixuMM2"))()

end)

b:Toggle("Toggle",function(state)

    shared.toggle = state

    print("Toggled")

end)

b:Slider("Slider",{

    min = 10; -- min value of the slider

    max = 50; -- max value of the slider

    precise = true; -- max 2 decimals

},function(value)

    print(value)

end)

b:Dropdown("Dropdown",{"A","B","C"},true,function(mob) --true/false, replaces the current title "Dropdown" with the option that t

    print(mob)

end)

b:Bind("Bind",Enum.KeyCode.C,function() --Default bind

    print("Yes")

end)

b:ColorPicker("ColorPicker",Color3.fromRGB(255,0,0),function(color) --Default color

    print(color)

end)

b:Box("Box","number",function(value) -- "number" or "string"

    print(value)

end)

b:DestroyGui()

end)

Section8:NewLabel("Darkai")

local Button5 = Section8:NewButton("Darkai Op", "Pro Hub", function()

    loadstring(game:HttpGet("https://raw.githubusercontent.com/GamingScripter/bedwars/main/Script", true))()

end)

Section8:NewLabel("OP GUI(Has Vape And Future)")

local Button6 = Section8:NewButton("OP", "Pro Hub", function()

    loadstring(game:HttpGet("https://raw.githubusercontent.com/LUNAAR-HUB/Neon-hub-fix/main/Slider%20fix", true))()

end)

Section9:NewLabel("Prison")

Section9:NewButton("Prison Life Op", "A Prison Life Script For Mobile", function()

    loadstring(game:HttpGet("https://pastebin.com/raw/dJ6tcE7h", true))()

end)

local Button7 = Section10:NewButton("Animation"), "A Animation script For Mobile", function()

    local AnimationChanger = Instance.new("ScreenGui")

local Main = Instance.new("Frame")

local TopBar = Instance.new("Frame")

local Close = Instance.new("TextButton")

local TextLabel = Instance.new("TextLabel")

local TextLabel_2 = Instance.new("TextLabel")

local NormalTab = Instance.new("Frame")

local A_Astronaut = Instance.new("TextButton")

local A_Bubbly = Instance.new("TextButton")

local A_Cartoony = Instance.new("TextButton")

local A_Elder = Instance.new("TextButton")

local A_Knight = Instance.new("TextButton")

local A_Levitation = Instance.new("TextButton")

local A_Mage = Instance.new("TextButton")

local A_Ninja = Instance.new("TextButton")

local A_Pirate = Instance.new("TextButton")

local A_Robot = Instance.new("TextButton")

local A_Stylish = Instance.new("TextButton")

local A_SuperHero = Instance.new("TextButton")

local A_Toy = Instance.new("TextButton")

local A_Vampire = Instance.new("TextButton")

local A_Werewolf = Instance.new("TextButton")

local A_Zombie = Instance.new("TextButton")

local Category = Instance.new("TextLabel")

local SpecialTab = Instance.new("Frame")

local A_Patrol = Instance.new("TextButton")

local A_Confident = Instance.new("TextButton")

local A_Popstar = Instance.new("TextButton")

local A_Cowboy = Instance.new("TextButton")

local A_Ghost = Instance.new("TextButton")

local A_Sneaky = Instance.new("TextButton")

local A_Princess = Instance.new("TextButton")

local Category_2 = Instance.new("TextLabel")

local OtherTab = Instance.new("Frame")

local Category_3 = Instance.new("TextLabel")

local A_None = Instance.new("TextButton")

local A_Anthro = Instance.new("TextButton")

local Animate = game.Players.LocalPlayer.Character.Animate

AnimationChanger.Name = "AnimationChanger"

AnimationChanger.Parent = game:WaitForChild("CoreGui")

AnimationChanger.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Main.Name = "Main"

Main.Parent = AnimationChanger

Main.BackgroundColor3 = Color3.new(0.278431, 0.278431, 0.278431)

Main.BorderSizePixel = 0

Main.Position = UDim2.new(0.421999991, 0, -1, 0)

Main.Size = UDim2.new(0, 300, 0, 250)

Main.Active = true

Main.Draggable = true

TopBar.Name = "TopBar"

TopBar.Parent = Main

TopBar.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)

TopBar.BorderSizePixel = 0

TopBar.Size = UDim2.new(0, 300, 0, 30)

Close.Name = "Close"

Close.Parent = TopBar

Close.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)

Close.BorderSizePixel = 0

Close.Position = UDim2.new(0.899999976, 0, 0, 0)

Close.Size = UDim2.new(0, 30, 0, 30)

Close.Font = Enum.Font.SciFi

Close.Text = "x"

Close.TextColor3 = Color3.new(1, 0, 0.0156863)

Close.TextSize = 20

Close.MouseButton1Click:Connect(function()

    wait(0.3)

    Main:TweenPosition(UDim2.new(0.421999991, 0, -1.28400004, 0))

    wait(3)

    AnimationChanger:Destroy()

end)

TextLabel.Parent = TopBar

TextLabel.BackgroundColor3 = Color3.new(1, 1, 1)

TextLabel.BackgroundTransparency = 1

TextLabel.BorderSizePixel = 0

TextLabel.Position = UDim2.new(0, 0, 0.600000024, 0)

TextLabel.Size = UDim2.new(0, 270, 0, 10)

TextLabel.Font = Enum.Font.SourceSans

TextLabel.Text = "Made by Nyser#4623"

TextLabel.TextColor3 = Color3.new(1, 1, 1)

TextLabel.TextSize = 15

TextLabel_2.Parent = TopBar

TextLabel_2.BackgroundColor3 = Color3.new(1, 1, 1)

TextLabel_2.BackgroundTransparency = 1

TextLabel_2.BorderSizePixel = 0

TextLabel_2.Position = UDim2.new(0, 0, -0.0266667679, 0)

TextLabel_2.Size = UDim2.new(0, 270, 0, 20)

TextLabel_2.Font = Enum.Font.SourceSans

TextLabel_2.Text = "Animation Changer"

TextLabel_2.TextColor3 = Color3.new(1, 1, 1)

TextLabel_2.TextSize = 20

NormalTab.Name = "NormalTab"

NormalTab.Parent = Main

NormalTab.BackgroundColor3 = Color3.new(0.278431, 0.278431, 0.278431)

NormalTab.BackgroundTransparency = 1

NormalTab.BorderSizePixel = 0

NormalTab.Position = UDim2.new(0.5, 0, 0.119999997, 0)

NormalTab.Size = UDim2.new(0, 150, 0, 500)

A_Astronaut.Name = "A_Astronaut"

A_Astronaut.Parent = NormalTab

A_Astronaut.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)

A_Astronaut.BorderSizePixel = 0

A_Astronaut.Position = UDim2.new(0, 0, 0.815764725, 0)

A_Astronaut.Size = UDim2.new(0, 150, 0, 30)

A_Astronaut.Font = Enum.Font.SciFi

A_Astronaut.Text = "Astronaut"

A_Astronaut.TextColor3 = Color3.new(1, 1, 1)

A_Astronaut.TextSize = 20

A_Astronaut.MouseButton1Click:Connect(function()

Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=891621366"

Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=891633237"

Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=891667138"

Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=891636393"

Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=891627522"

Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=891609353"

Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=891617961"

game.Players.LocalPlayer.Character.Humanoid.Jump = true

end)

A_Bubbly.Name = "A_Bubbly"

A_Bubbly.Parent = NormalTab

A_Bubbly.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)

A_Bubbly.BorderSizePixel = 0

A_Bubbly.Position = UDim2.new(0, 0, 0.349019617, 0)

A_Bubbly.Size = UDim2.new(0, 150, 0, 30)

A_Bubbly.Font = Enum.Font.SciFi

A_Bubbly.Text = "Bubbly"

A_Bubbly.TextColor3 = Color3.new(1, 1, 1)

A_Bubbly.TextSize = 20

A_Bubbly.MouseButton1Click:Connect(function()

Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=910004836"

Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=910009958"

Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=910034870"

Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=910025107"

Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=910016857"

Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=910001910"

Animate.swimidle.SwimIdle.AnimationId = "http://www.roblox.com/asset/?id=910030921"

Animate.swim.Swim.AnimationId = "http://www.roblox.com/asset/?id=910028158"

game.Players.LocalPlayer.Character.Humanoid.Jump = true

end)

A_Cartoony.Name = "A_Cartoony"

A_Cartoony.Parent = NormalTab

A_Cartoony.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)

A_Cartoony.BorderSizePixel = 0

A_Cartoony.Position = UDim2.new(0, 0, 0.407272667, 0)

A_Cartoony.Size = UDim2.new(0, 150, 0, 30)

A_Cartoony.Font = Enum.Font.SciFi

A_Cartoony.Text = "Cartoony"

A_Cartoony.TextColor3 = Color3.new(1, 1, 1)

A_Cartoony.TextSize = 20

A_Cartoony.MouseButton1Click:Connect(function()

Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=742637544"

Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=742638445"

Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=742640026"

Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=742638842"

Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=742637942"

Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=742636889"

Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=742637151"

game.Players.LocalPlayer.Character.Humanoid.Jump = true

end)

A_Elder.Name = "A_Elder"

A_Elder.Parent = NormalTab

A_Elder.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)

A_Elder.BorderSizePixel = 0

A_Elder.Position = UDim2.new(6.51925802e-09, 0, 0.636310041, 0)

A_Elder.Size = UDim2.new(0, 150, 0, 30)

A_Elder.Font = Enum.Font.SciFi

A_Elder.Text = "Elder"

A_Elder.TextColor3 = Color3.new(1, 1, 1)

A_Elder.TextSize = 20

A_Elder.MouseButton1Click:Connect(function()

Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=845397899"

Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=845400520"

Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=845403856"

Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=845386501"

Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=845398858"

Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=845392038"

Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=845396048"

game.Players.LocalPlayer.Character.Humanoid.Jump = true

end)

A_Knight.Name = "A_Knight"

A_Knight.Parent = NormalTab

A_Knight.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)

A_Knight.BorderSizePixel = 0

A_Knight.Position = UDim2.new(0, 0, 0.52352941, 0)

A_Knight.Size = UDim2.new(0, 150, 0, 30)

A_Knight.Font = Enum.Font.SciFi

A_Knight.Text = "Knight"

A_Knight.TextColor3 = Color3.new(1, 1, 1)

A_Knight.TextSize = 20

A_Knight.MouseButton1Click:Connect(function()

Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=657595757"

Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=657568135"

Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=657552124"

Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=657564596"

Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=658409194"

Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=658360781"

Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=657600338"

game.Players.LocalPlayer.Character.Humanoid.Jump = true

end)

A_Levitation.Name = "A_Levitation"

A_Levitation.Parent = NormalTab

A_Levitation.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)

A_Levitation.BorderSizePixel = 0

A_Levitation.Position = UDim2.new(0, 0, 0.115472436, 0)

A_Levitation.Size = UDim2.new(0, 150, 0, 30)

A_Levitation.Font = Enum.Font.SciFi

A_Levitation.Text = "Levitation"

A_Levitation.TextColor3 = Color3.new(1, 1, 1)

A_Levitation.TextSize = 20

A_Levitation.MouseButton1Click:Connect(function()

Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616006778"

Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616008087"

Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616013216"

Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616010382"

Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616008936"

Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616003713"

Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616005863"

game.Players.LocalPlayer.Character.Humanoid.Jump = true

end)

A_Mage.Name = "A_Mage"

A_Mage.Parent = NormalTab

A_Mage.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)

A_Mage.BorderSizePixel = 0

A_Mage.Position = UDim2.new(0, 0, 0.696203232, 0)

A_Mage.Size = UDim2.new(0, 150, 0, 30)

A_Mage.Font = Enum.Font.SciFi

A_Mage.Text = "Mage"

A_Mage.TextColor3 = Color3.new(1, 1, 1)

A_Mage.TextSize = 20

A_Mage.MouseButton1Click:Connect(function()

Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=707742142"

Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=707855907"

Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=707897309"

Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=707861613"

Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=707853694"

Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=707826056"

Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=707829716"

game.Players.LocalPlayer.Character.Humanoid.Jump = true

end)

A_Ninja.Name = "A_Ninja"

A_Ninja.Parent = NormalTab

A_Ninja.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)

A_Ninja.BorderSizePixel = 0

A_Ninja.Position = UDim2.new(0, 0, 0.0597896464, 0)

A_Ninja.Size = UDim2.new(0, 150, 0, 30)

A_Ninja.Font = Enum.Font.SciFi

A_Ninja.Text = "Ninja"

A_Ninja.TextColor3 = Color3.new(1, 1, 1)

A_Ninja.TextSize = 20

A_Ninja.MouseButton1Click:Connect(function()

Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=782841498"

Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=656118341"

Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=656121766"

Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=656118852"

Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=656117878"

Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=656114359"

Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=5319914476"

game.Players.LocalPlayer.Character.Humanoid.Jump = true

end)

A_Pirate.Name = "A_Pirate"

A_Pirate.Parent = NormalTab

A_Pirate.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)

A_Pirate.BorderSizePixel = 0

A_Pirate.Position = UDim2.new(-0.000333309174, 0, 0.874588311, 0)

A_Pirate.Size = UDim2.new(0, 150, 0, 30)

A_Pirate.Font = Enum.Font.SciFi

A_Pirate.Text = "Pirate"

A_Pirate.TextColor3 = Color3.new(1, 1, 1)

A_Pirate.TextSize = 20

A_Pirate.MouseButton1Click:Connect(function()

Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=750781874"

Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=750782770"

Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=750785693"

Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=750783738"

Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=750782230"

Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=750779899"

Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=750780242"

game.Players.LocalPlayer.Character.Humanoid.Jump = true

end)

A_Robot.Name = "A_Robot"

A_Robot.Parent = NormalTab

A_Robot.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)

A_Robot.BorderSizePixel = 0

A_Robot.Position = UDim2.new(0, 0, 0.291479498, 0)

A_Robot.Size = UDim2.new(0, 150, 0, 30)

A_Robot.Font = Enum.Font.SciFi

A_Robot.Text = "Robot"

A_Robot.TextColor3 = Color3.new(1, 1, 1)

A_Robot.TextSize = 20

A_Robot.MouseButton1Click:Connect(function()

Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616088211"

Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616089559"

Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616095330"

Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616091570"

Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616090535"

Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616086039"

Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616087089"

game.Players.LocalPlayer.Character.Humanoid.Jump = true

end)

A_Stylish.Name = "A_Stylish"

A_Stylish.Parent = NormalTab

A_Stylish.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)

A_Stylish.BorderSizePixel = 0

A_Stylish.Position = UDim2.new(0, 0, 0.232816339, 0)

A_Stylish.Size = UDim2.new(0, 150, 0, 30)

A_Stylish.Font = Enum.Font.SciFi

A_Stylish.Text = "Stylish"

A_Stylish.TextColor3 = Color3.new(1, 1, 1)

A_Stylish.TextSize = 20

A_Stylish.MouseButton1Click:Connect(function()

Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616136790"

Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616138447"

Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616146177"

Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616140816"

Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616139451"

Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616133594"

Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616134815"

game.Players.LocalPlayer.Character.Humanoid.Jump = true

end)

A_SuperHero.Name = "A_SuperHero"

A_SuperHero.Parent = NormalTab

A_SuperHero.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)

A_SuperHero.BorderSizePixel = 0

A_SuperHero.Position = UDim2.new(0, 0, 0.464919746, 0)

A_SuperHero.Size = UDim2.new(0, 150, 0, 30)

A_SuperHero.Font = Enum.Font.SciFi

A_SuperHero.Text = "SuperHero"

A_SuperHero.TextColor3 = Color3.new(1, 1, 1)

A_SuperHero.TextSize = 20

A_SuperHero.MouseButton1Click:Connect(function()

Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616111295"

Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616113536"

Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616122287"

Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616117076"

Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616115533"

Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616104706"

Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616108001"

game.Players.LocalPlayer.Character.Humanoid.Jump = true

end)

A_Toy.Name = "A_Toy"

A_Toy.Parent = NormalTab

A_Toy.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)

A_Toy.BorderSizePixel = 0

A_Toy.Position = UDim2.new(6.51925802e-09, 0, 0.756028414, 0)

A_Toy.Size = UDim2.new(0, 150, 0, 30)

A_Toy.Font = Enum.Font.SciFi

A_Toy.Text = "Toy"

A_Toy.TextColor3 = Color3.new(1, 1, 1)

A_Toy.TextSize = 20

A_Toy.MouseButton1Click:Connect(function()

Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=782841498"

Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=782845736"

Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=782843345"

Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=782842708"

Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=782847020"

Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=782843869"

Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=782846423"

game.Players.LocalPlayer.Character.Humanoid.Jump = true

end)

A_Vampire.Name = "A_Vampire"

A_Vampire.Parent = NormalTab

A_Vampire.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)

A_Vampire.BorderSizePixel = 0

A_Vampire.Position = UDim2.new(0, 0, 0.934021354, 0)

A_Vampire.Size = UDim2.new(0, 150, 0, 30)

A_Vampire.Font = Enum.Font.SciFi

A_Vampire.Text = "Vampire"

A_Vampire.TextColor3 = Color3.new(1, 1, 1)

A_Vampire.TextSize = 20

A_Vampire.MouseButton1Click:Connect(function()

Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1083445855"

Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1083450166"

Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1083473930"

Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1083462077"

Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1083455352"

Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1083439238"

Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1083443587"

game.Players.LocalPlayer.Character.Humanoid.Jump = true

end)

A_Werewolf.Name = "A_Werewolf"

A_Werewolf.Parent = NormalTab

A_Werewolf.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)

A_Werewolf.BorderSizePixel = 0

A_Werewolf.Position = UDim2.new(-0.000333368778, 0, 0.174509808, 0)

A_Werewolf.Size = UDim2.new(0, 150, 0, 30)

A_Werewolf.Font = Enum.Font.SciFi

A_Werewolf.Text = "Werewolf"

A_Werewolf.TextColor3 = Color3.new(1, 1, 1)

A_Werewolf.TextSize = 20

A_Werewolf.MouseButton1Click:Connect(function()

Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1083195517"

Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1083214717"

Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1083178339"

Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1083216690"

Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1083218792"

Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1083182000"

Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1083189019"

game.Players.LocalPlayer.Character.Humanoid.Jump = true

end)

A_Zombie.Name = "A_Zombie"

A_Zombie.Parent = NormalTab

A_Zombie.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)

A_Zombie.BorderSizePixel = 0

A_Zombie.Position = UDim2.new(-1.1920929e-07, 0, 0.582352936, 0)

A_Zombie.Size = UDim2.new(0, 150, 0, 30)

A_Zombie.Font = Enum.Font.SciFi

A_Zombie.Text = "Zombie"

A_Zombie.TextColor3 = Color3.new(1, 1, 1)

A_Zombie.TextSize = 20

A_Zombie.MouseButton1Click:Connect(function()

Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616158929"

Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616160636"

Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616168032"

Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616163682"

Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616161997"

Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616156119"

Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616157476"

game.Players.LocalPlayer.Character.Humanoid.Jump = true

end)

Category.Name = "Category"

Category.Parent = NormalTab

Category.BackgroundColor3 = Color3.new(0.156863, 0.156863, 0.156863)

Category.BorderSizePixel = 0

Category.Size = UDim2.new(0, 150, 0, 30)

Category.Text = "Normal"

Category.TextColor3 = Color3.new(0, 0.835294, 1)

Category.TextSize = 14

SpecialTab.Name = "SpecialTab"

SpecialTab.Parent = Main

SpecialTab.BackgroundColor3 = Color3.new(0.278431, 0.278431, 0.278431)

SpecialTab.BackgroundTransparency = 1

SpecialTab.BorderSizePixel = 0

SpecialTab.Position = UDim2.new(0, 0, 0.119999997, 0)

SpecialTab.Size = UDim2.new(0, 150, 0, 230)

A_Patrol.Name = "A_Patrol"

A_Patrol.Parent = SpecialTab

A_Patrol.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)

A_Patrol.BorderSizePixel = 0

A_Patrol.Position = UDim2.new(0, 0, 0.259960413, 0)

A_Patrol.Size = UDim2.new(0, 150, 0, 30)

A_Patrol.Font = Enum.Font.SciFi

A_Patrol.Text = "Patrol"

A_Patrol.TextColor3 = Color3.new(1, 1, 1)

A_Patrol.TextSize = 20

A_Patrol.MouseButton1Click:Connect(function()

Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1149612882"

Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1150842221"

Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1151231493"

Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1150967949"

Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1148811837"

Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1148811837"

Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1148863382"

game.Players.LocalPlayer.Character.Humanoid.Jump = true

end)

A_Confident.Name = "A_Confident"

A_Confident.Parent = SpecialTab

A_Confident.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)

A_Confident.BorderSizePixel = 0

A_Confident.Position = UDim2.new(0, 0, 0.389248967, 0)

A_Confident.Size = UDim2.new(0, 150, 0, 30)

A_Confident.Font = Enum.Font.SciFi

A_Confident.Text = "Confident"

A_Confident.TextColor3 = Color3.new(1, 1, 1)

A_Confident.TextSize = 20

A_Confident.MouseButton1Click:Connect(function()

Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1069977950"

Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1069987858"

Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1070017263"

Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1070001516"

Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1069984524"

Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1069946257"

Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1069973677"

game.Players.LocalPlayer.Character.Humanoid.Jump = true

end)

A_Popstar.Name = "A_Popstar"

A_Popstar.Parent = SpecialTab

A_Popstar.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)

A_Popstar.BorderSizePixel = 0

A_Popstar.Position = UDim2.new(0, 0, 0.130671918, 0)

A_Popstar.Size = UDim2.new(0, 150, 0, 30)

A_Popstar.Font = Enum.Font.SciFi

A_Popstar.Text = "Popstar"

A_Popstar.TextColor3 = Color3.new(1, 1, 1)

A_Popstar.TextSize = 20

A_Popstar.MouseButton1Click:Connect(function()

Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1212900985"

Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1150842221"

Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1212980338"

Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1212980348"

Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1212954642"

Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1213044953"

Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1212900995"

game.Players.LocalPlayer.Character.Humanoid.Jump = true

end)

A_Cowboy.Name = "A_Cowboy"

A_Cowboy.Parent = SpecialTab

A_Cowboy.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)

A_Cowboy.BorderSizePixel = 0

A_Cowboy.Position = UDim2.new(0, 0, 0.772964239, 0)

A_Cowboy.Size = UDim2.new(0, 150, 0, 30)

A_Cowboy.Font = Enum.Font.SciFi

A_Cowboy.Text = "Cowboy"

A_Cowboy.TextColor3 = Color3.new(1, 1, 1)

A_Cowboy.TextSize = 20

A_Cowboy.MouseButton1Click:Connect(function()

Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1014390418"

Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1014398616"

Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1014421541"

Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1014401683"

Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1014394726"

Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1014380606"

Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1014384571"

game.Players.LocalPlayer.Character.Humanoid.Jump = true

end)

A_Ghost.Name = "A_Ghost"

A_Ghost.Parent = SpecialTab

A_Ghost.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)

A_Ghost.BorderSizePixel = 0

A_Ghost.Position = UDim2.new(0, 0, 0.900632322, 0)

A_Ghost.Size = UDim2.new(0, 150, 0, 30)

A_Ghost.Font = Enum.Font.SciFi

A_Ghost.Text = "Ghost"

A_Ghost.TextColor3 = Color3.new(1, 1, 1)

A_Ghost.TextSize = 20

A_Ghost.MouseButton1Click:Connect(function()

Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616006778"

Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616008087"

Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616013216"

Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616013216"

Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616008936"

Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616005863"

Animate.swimidle.SwimIdle.AnimationId = "http://www.roblox.com/asset/?id=616012453"

Animate.swim.Swim.AnimationId = "http://www.roblox.com/asset/?id=616011509"

game.Players.LocalPlayer.Character.Humanoid.Jump = true

end)

A_Sneaky.Name = "A_Sneaky"

A_Sneaky.Parent = SpecialTab

A_Sneaky.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)

A_Sneaky.BorderSizePixel = 0

A_Sneaky.Position = UDim2.new(0, 0, 0.517628431, 0)

A_Sneaky.Size = UDim2.new(0, 150, 0, 30)

A_Sneaky.Font = Enum.Font.SciFi

A_Sneaky.Text = "Sneaky"

A_Sneaky.TextColor3 = Color3.new(1, 1, 1)

A_Sneaky.TextSize = 20

A_Sneaky.MouseButton1Click:Connect(function()

Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1132473842"

Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1132477671"

Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1132510133"

Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1132494274"

Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1132489853"

Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1132461372"

Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1132469004"

game.Players.LocalPlayer.Character.Humanoid.Jump = true

end)

A_Princess.Name = "A_Princess"

A_Princess.Parent = SpecialTab

A_Princess.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)

A_Princess.BorderSizePixel = 0

A_Princess.Position = UDim2.new(0, 0, 0.645296335, 0)

A_Princess.Size = UDim2.new(0, 150, 0, 30)

A_Princess.Font = Enum.Font.SciFi

A_Princess.Text = "Princess"

A_Princess.TextColor3 = Color3.new(1, 1, 1)

A_Princess.TextSize = 20

A_Princess.MouseButton1Click:Connect(function()

Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=941003647"

Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=941013098"

Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=941028902"

Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=941015281"

Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=941008832"

Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=940996062"

Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=941000007"

game.Players.LocalPlayer.Character.Humanoid.Jump = true

end)

Category_2.Name = "Category"

Category_2.Parent = SpecialTab

Category_2.BackgroundColor3 = Color3.new(0.156863, 0.156863, 0.156863)

Category_2.BorderSizePixel = 0

Category_2.Size = UDim2.new(0, 150, 0, 30)

Category_2.Text = "Special"

Category_2.TextColor3 = Color3.new(0, 0.835294, 1)

Category_2.TextSize = 14

OtherTab.Name = "OtherTab"

OtherTab.Parent = Main

OtherTab.BackgroundColor3 = Color3.new(0.278431, 0.278431, 0.278431)

OtherTab.BackgroundTransparency = 1

OtherTab.BorderSizePixel = 0

OtherTab.Position = UDim2.new(0, 0, 1.06800008, 0)

OtherTab.Size = UDim2.new(0, 150, 0, 220)

Category_3.Name = "Category"

Category_3.Parent = OtherTab

Category_3.BackgroundColor3 = Color3.new(0.156863, 0.156863, 0.156863)

Category_3.BorderSizePixel = 0

Category_3.Size = UDim2.new(0, 150, 0, 30)

Category_3.Text = "Other"

Category_3.TextColor3 = Color3.new(0, 0.835294, 1)

Category_3.TextSize = 14

A_None.Name = "A_None"

A_None.Parent = OtherTab

A_None.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)

A_None.BorderSizePixel = 0

A_None.Position = UDim2.new(0, 0, 0.134545445, 0)

A_None.Size = UDim2.new(0, 150, 0, 30)

A_None.Font = Enum.Font.SciFi

A_None.Text = "None"

A_None.TextColor3 = Color3.new(1, 1, 1)

A_None.TextSize = 20

A_None.MouseButton1Click:Connect(function()

Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=0"

Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=0"

Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=0"

Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=0"

Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=0"

Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=0"

Animate.swimidle.SwimIdle.AnimationId = "http://www.roblox.com/asset/?id=0"

Animate.swim.Swim.AnimationId = "http://www.roblox.com/asset/?id=0"

game.Players.LocalPlayer.Character.Humanoid.Jump = true

end)

A_Anthro.Name = "A_Anthro"

A_Anthro.Parent = OtherTab

A_Anthro.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)

A_Anthro.BorderSizePixel = 0

A_Anthro.Position = UDim2.new(0, 0, 0.269090891, 0)

A_Anthro.Size = UDim2.new(0, 150, 0, 30)

A_Anthro.Font = Enum.Font.SciFi

A_Anthro.Text = "Anthro (Default)"

A_Anthro.TextColor3 = Color3.new(1, 1, 1)

A_Anthro.TextSize = 20

A_Anthro.MouseButton1Click:Connect(function()

Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=2510196951"

Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=2510197257"

Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=2510202577"

Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=2510198475"

Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=2510197830"

Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=2510192778"

Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=5319914476"

game.Players.LocalPlayer.Character.Humanoid.Jump = true

end)

wait(1)

Main:TweenPosition(UDim2.new(0.421999991, 0, 0.28400004, 0))

end

local Button8 = Section11:NewButton("Fling"), "A Fling Script For Mobile", function()

    spawn(function()

local message = Instance.new("Message",workspace)

message.Text = "Loaded press z to execute inviseble , press x to respawn)"

wait(2)

message:Destroy()

end)

local mouse = game.Players.LocalPlayer:GetMouse()

local groot = nil

mouse.KeyDown:connect(function(k)

  

  if k == "z" then

    

    

    

spawn(function()

local message = Instance.new("Message",workspace)

message.Text = "Fe Invisible Fling By Diemiers#4209 Loaded (wait 11 seconds to load)"

wait(11)

message:Destroy()

end)

local ch = game.Players.LocalPlayer.Character

local prt=Instance.new("Model", workspace)

local z1 =  Instance.new("Part", prt)

z1.Name="Torso"

z1.CanCollide = false

z1.Anchored = true

local z2  =Instance.new("Part", prt)

z2.Name="Head"

z2.Anchored = true

z2.CanCollide = false

local z3 =Instance.new("Humanoid", prt)

z3.Name="Humanoid"

z1.Position = Vector3.new(0,9999,0)

z2.Position = Vector3.new(0,9991,0)

 game.Players.LocalPlayer.Character=prt

wait(5)

game.Players.LocalPlayer.Character=ch

wait(6)

local plr = game.Players.LocalPlayer

mouse = plr:GetMouse()

local Hum = Instance.new("Humanoid")

Hum.Parent = game.Players.LocalPlayer.Character

local root =  game.Players.LocalPlayer.Character.HumanoidRootPart

for i,v in pairs(plr.Character:GetChildren()) do

  

  if v ~= root and  v.Name ~= "Humanoid" then

    

    v:Destroy()

    

  end

  

  

end

           

workspace.CurrentCamera.CameraSubject = root

local se = Instance.new("SelectionBox",root)

se.Adornee = root

game:GetService('RunService').Stepped:connect(function()

game.Players.LocalPlayer.Character.HumanoidRootPart.CanCollide = false

end)

game:GetService('RunService').RenderStepped:connect(function()

game.Players.LocalPlayer.Character.HumanoidRootPart.CanCollide = false

end)

power = 999999 -- change this to make it more or less powerful

power = power*10

---

wait(.1)

local bambam = Instance.new("BodyThrust")

bambam.Parent = game.Players.LocalPlayer.Character.HumanoidRootPart

bambam.Force = Vector3.new(power,0,power)

bambam.Location = game.Players.LocalPlayer.Character.HumanoidRootPart.Position 

local plr = game.Players.LocalPlayer

local torso = root

local flying = true

local deb = true

local ctrl = {f = 0, b = 0, l = 0, r = 0}

local lastctrl = {f = 0, b = 0, l = 0, r = 0}

local maxspeed = 120

local speed = 15

---local bambam = Instance.new("BodyThrust")

---bambam.Parent = torso

--bambam.Force = Vector3.new(9999999,0,9999999)

--bambam.Location = torso.Position

---

groot = root

 

function Fly()

local bg = Instance.new("BodyGyro", torso)

bg.P = 9e4

bg.maxTorque = Vector3.new(0, 0, 0)

bg.cframe = torso.CFrame

local bv = Instance.new("BodyVelocity", torso)

bv.velocity = Vector3.new(0,0,0)

bv.maxForce = Vector3.new(9e9, 9e9, 9e9)

repeat wait()

if ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0 then

speed = speed+.2

if speed > maxspeed then

speed = maxspeed

end

elseif not (ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0) and speed ~= 0 then

speed = speed-1

if speed < 0 then

speed = 0

end

end

if (ctrl.l + ctrl.r) ~= 0 or (ctrl.f + ctrl.b) ~= 0 then

bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (ctrl.f+ctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(ctrl.l+ctrl.r,(ctrl.f+ctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed

lastctrl = {f = ctrl.f, b = ctrl.b, l = ctrl.l, r = ctrl.r}

elseif (ctrl.l + ctrl.r) == 0 and (ctrl.f + ctrl.b) == 0 and speed ~= 0 then

bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (lastctrl.f+lastctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(lastctrl.l+lastctrl.r,(lastctrl.f+lastctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed

else

bv.velocity = Vector3.new(0,0.1,0)

end

until not flying

ctrl = {f = 0, b = 0, l = 0, r = 0}

lastctrl = {f = 0, b = 0, l = 0, r = 0}

speed = 0

bg:Destroy()

bv:Destroy()

end

mouse.KeyDown:connect(function(key)

if key:lower() == "e" then

if flying then flying = false

else

flying = true

Fly()

end

elseif key:lower() == "w" then

ctrl.f = 1

elseif key:lower() == "s" then

ctrl.b = -1

elseif key:lower() == "a" then

ctrl.l = -1

elseif key:lower() == "d" then

ctrl.r = 1

end

end)

mouse.KeyUp:connect(function(key)

if key:lower() == "w" then

ctrl.f = 0

elseif key:lower() == "s" then

ctrl.b = 0

elseif key:lower() == "a" then

ctrl.l = 0

elseif key:lower() == "d" then

ctrl.r = 0

elseif key:lower() == "r" then

end

end)

Fly()

    

    

  elseif k == "x" then

    

    

    spawn(function()

local message = Instance.new("Message",workspace)

message.Text = "Respawning dont spam"

wait(1)

message:Destroy()

end)

    

    local saved = groot.Position

    

local ch = game.Players.LocalPlayer.Character

local prt=Instance.new("Model", workspace)

local z1 =  Instance.new("Part", prt)

z1.Name="Torso"

z1.CanCollide = false

z1.Anchored = true

local z2  =Instance.new("Part", prt)

z2.Name="Head"

z2.Anchored = true

z2.CanCollide = false

local z3 =Instance.new("Humanoid", prt)

z3.Name="Humanoid"

z1.Position = Vector3.new(0,9999,0)

z2.Position = Vector3.new(0,9991,0)

 game.Players.LocalPlayer.Character=prt

wait(5)

 game.Players.LocalPlayer.Character=ch

local poop = nil

    repeat wait() poop = game.Players.LocalPlayer.Character:FindFirstChild("Head") until poop ~= nil

    wait(1)

    game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(saved)

    

  end

  

  

end)

end

local Button9 = Section12:NewButton("Fly Script"), "A Fly Script For Mobile", function()

    game:GetService("StarterGui"):SetCore("SendNotification",{

                Title = "Credits";

                Text = "Modified By SpekzZ";

                Duration = 3.5;

            })

-- Gui to Lua

-- Version: 3.2

-- Instances:

local main = Instance.new("ScreenGui")

local Frame = Instance.new("Frame")

local up = Instance.new("TextButton")

local down = Instance.new("TextButton")

local onof = Instance.new("TextButton")

local TextLabel = Instance.new("TextLabel")

local plus = Instance.new("TextButton")

local speed = Instance.new("TextLabel")

local mine = Instance.new("TextButton")

--Properties:

main.Name = "main"

main.Parent = game.CoreGui

main.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = main

Frame.BackgroundColor3 = Color3.fromRGB(163, 255, 137)

Frame.BorderColor3 = Color3.fromRGB(103, 221, 213)

Frame.Position = UDim2.new(0.100320168, 0, 0.379746825, 0)

Frame.Size = UDim2.new(0, 190, 0, 57)

up.Name = "up"

up.Parent = Frame

up.BackgroundColor3 = Color3.fromRGB(79, 255, 152)

up.Size = UDim2.new(0, 44, 0, 28)

up.Font = Enum.Font.SourceSans

up.Text = "UP"

up.TextColor3 = Color3.fromRGB(0, 0, 0)

up.TextSize = 14.000

down.Name = "down"

down.Parent = Frame

down.BackgroundColor3 = Color3.fromRGB(215, 255, 121)

down.Position = UDim2.new(0, 0, 0.491228074, 0)

down.Size = UDim2.new(0, 44, 0, 28)

down.Font = Enum.Font.SourceSans

down.Text = "DOWN"

down.TextColor3 = Color3.fromRGB(0, 0, 0)

down.TextSize = 14.000

onof.Name = "onof"

onof.Parent = Frame

onof.BackgroundColor3 = Color3.fromRGB(255, 249, 74)

onof.Position = UDim2.new(0.702823281, 0, 0.491228074, 0)

onof.Size = UDim2.new(0, 56, 0, 28)

onof.Font = Enum.Font.SourceSans

onof.Text = "fly"

onof.TextColor3 = Color3.fromRGB(0, 0, 0)

onof.TextSize = 14.000

TextLabel.Parent = Frame

TextLabel.BackgroundColor3 = Color3.fromRGB(242, 60, 255)

TextLabel.Position = UDim2.new(0.469327301, 0, 0, 0)

TextLabel.Size = UDim2.new(0, 100, 0, 28)

TextLabel.Font = Enum.Font.SourceSans

TextLabel.Text = "Fly Gui V2"

TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)

TextLabel.TextScaled = true

TextLabel.TextSize = 14.000

TextLabel.TextWrapped = true

plus.Name = "plus"

plus.Parent = Frame

plus.BackgroundColor3 = Color3.fromRGB(133, 145, 255)

plus.Position = UDim2.new(0.231578946, 0, 0, 0)

plus.Size = UDim2.new(0, 45, 0, 28)

plus.Font = Enum.Font.SourceSans

plus.Text = "+"

plus.TextColor3 = Color3.fromRGB(0, 0, 0)

plus.TextScaled = true

plus.TextSize = 14.000

plus.TextWrapped = true

speed.Name = "speed"

speed.Parent = Frame

speed.BackgroundColor3 = Color3.fromRGB(255, 85, 0)

speed.Position = UDim2.new(0.468421042, 0, 0.491228074, 0)

speed.Size = UDim2.new(0, 44, 0, 28)

speed.Font = Enum.Font.SourceSans

speed.Text = "1"

speed.TextColor3 = Color3.fromRGB(0, 0, 0)

speed.TextScaled = true

speed.TextSize = 14.000

speed.TextWrapped = true

mine.Name = "mine"

mine.Parent = Frame

mine.BackgroundColor3 = Color3.fromRGB(123, 255, 247)

mine.Position = UDim2.new(0.231578946, 0, 0.491228074, 0)

mine.Size = UDim2.new(0, 45, 0, 29)

mine.Font = Enum.Font.SourceSans

mine.Text = "-"

mine.TextColor3 = Color3.fromRGB(0, 0, 0)

mine.TextScaled = true

mine.TextSize = 14.000

mine.TextWrapped = true

speeds = 1

local speaker = game:GetService("Players").LocalPlayer

local chr = game.Players.LocalPlayer.Character

local hum = chr and chr:FindFirstChildWhichIsA("Humanoid")

nowe = false

Frame.Active = true -- main = gui

Frame.Draggable = true

onof.MouseButton1Down:connect(function()

  if nowe == true then

    nowe = false

    speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Climbing,true)

    speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.FallingDown,true)

    speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Flying,true)

    speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Freefall,true)

    speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.GettingUp,true)

    speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Jumping,true)

    speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Landed,true)

    speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Physics,true)

    speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.PlatformStanding,true)

    speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Ragdoll,true)

    speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Running,true)

    speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.RunningNoPhysics,true)

    speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Seated,true)

    speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.StrafingNoPhysics,true)

    speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Swimming,true)

    speaker.Character.Humanoid:ChangeState(Enum.HumanoidStateType.RunningNoPhysics)

  else 

    nowe = true

    for i = 1, speeds do

      spawn(function()

        local hb = game:GetService("RunService").Heartbeat  

        tpwalking = true

        local chr = game.Players.LocalPlayer.Character

        local hum = chr and chr:FindFirstChildWhichIsA("Humanoid")

        while tpwalking and hb:Wait() and chr and hum and hum.Parent do

          if hum.MoveDirection.Magnitude > 0 then

            chr:TranslateBy(hum.MoveDirection)

          end

        end

      end)

    end

    game.Players.LocalPlayer.Character.Animate.Disabled = true

    local Char = game.Players.LocalPlayer.Character

    local Hum = Char:FindFirstChildOfClass("Humanoid") or Char:FindFirstChildOfClass("AnimationController")

    for i,v in next, Hum:GetPlayingAnimationTracks() do

      v:AdjustSpeed(0)

    end

    speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Climbing,false)

    speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.FallingDown,false)

    speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Flying,false)

    speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Freefall,false)

    speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.GettingUp,false)

    speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Jumping,false)

    speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Landed,false)

    speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Physics,false)

    speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.PlatformStanding,false)

    speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Ragdoll,false)

    speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Running,false)

    speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.RunningNoPhysics,false)

    speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Seated,false)

    speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.StrafingNoPhysics,false)

    speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Swimming,false)

    speaker.Character.Humanoid:ChangeState(Enum.HumanoidStateType.Swimming)

  end

  

    local plr = game.Players.LocalPlayer

    local UpperTorso = plr.Character.LowerTorso

    local flying = true

    local deb = true

    local ctrl = {f = 0, b = 0, l = 0, r = 0}

    local lastctrl = {f = 0, b = 0, l = 0, r = 0}

    local maxspeed = 50

    local speed = 0

    local bg = Instance.new("BodyGyro", UpperTorso)

    bg.P = 9e4

    bg.maxTorque = Vector3.new(9e9, 9e9, 9e9)

    bg.cframe = UpperTorso.CFrame

    local bv = Instance.new("BodyVelocity", UpperTorso)

    bv.velocity = Vector3.new(0,0.1,0)

    bv.maxForce = Vector3.new(9e9, 9e9, 9e9)

    if nowe == true then

      plr.Character.Humanoid.PlatformStand = true

    end

    while nowe == true or game:GetService("Players").LocalPlayer.Character.Humanoid.Health == 0 do

      wait()

      if ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0 then

        speed = speed+.5+(speed/maxspeed)

        if speed > maxspeed then

          speed = maxspeed

        end

      elseif not (ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0) and speed ~= 0 then

        speed = speed-1

        if speed < 0 then

          speed = 0

        end

      end

      if (ctrl.l + ctrl.r) ~= 0 or (ctrl.f + ctrl.b) ~= 0 then

        bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (ctrl.f+ctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(ctrl.l+ctrl.r,(ctrl.f+ctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed

        lastctrl = {f = ctrl.f, b = ctrl.b, l = ctrl.l, r = ctrl.r}

      elseif (ctrl.l + ctrl.r) == 0 and (ctrl.f + ctrl.b) == 0 and speed ~= 0 then

        bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (lastctrl.f+lastctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(lastctrl.l+lastctrl.r,(lastctrl.f+lastctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed

      else

        bv.velocity = Vector3.new(0,0,0)

      end

      bg.cframe = game.Workspace.CurrentCamera.CoordinateFrame * CFrame.Angles(-math.rad((ctrl.f+ctrl.b)*50*speed/maxspeed),0,0)

    end

    ctrl = {f = 0, b = 0, l = 0, r = 0}

    lastctrl = {f = 0, b = 0, l = 0, r = 0}

    speed = 0

    bg:Destroy()

    bv:Destroy()

    plr.Character.Humanoid.PlatformStand = false

    game.Players.LocalPlayer.Character.Animate.Disabled = false

    tpwalking = false

  

end)

up.MouseButton1Down:connect(function()

  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,2,0)

  

end)

down.MouseButton1Down:connect(function()

  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,-2,0)

end)

game:GetService("Players").LocalPlayer.CharacterAdded:Connect(function(char)

  wait(0.7)

  game.Players.LocalPlayer.Character.Humanoid.PlatformStand = false

  game.Players.LocalPlayer.Character.Animate.Disabled = false

end)

plus.MouseButton1Down:connect(function()

  speeds = speeds + 1

  speed.Text = speeds

  if nowe == true then

    

  tpwalking = false

  for i = 1, speeds do

    spawn(function()

      local hb = game:GetService("RunService").Heartbeat  

      tpwalking = true

      local chr = game.Players.LocalPlayer.Character

      local hum = chr and chr:FindFirstChildWhichIsA("Humanoid")

      while tpwalking and hb:Wait() and chr and hum and hum.Parent do

        if hum.MoveDirection.Magnitude > 0 then

          chr:TranslateBy(hum.MoveDirection)

        end

      end

    end)

    end

    end

end)

mine.MouseButton1Down:connect(function()

  if speeds == 1 then

    speed.Text = 'can not be less than 1'

    wait(1)

    speed.Text = speeds

  else

  speeds = speeds - 1

    speed.Text = speeds

    if nowe == true then

  tpwalking = false

  for i = 1, speeds do

    spawn(function()

      local hb = game:GetService("RunService").Heartbeat  

      tpwalking = true

      local chr = game.Players.LocalPlayer.Character

      local hum = chr and chr:FindFirstChildWhichIsA("Humanoid")

      while tpwalking and hb:Wait() and chr and hum and hum.Parent do

        if hum.MoveDirection.Magnitude > 0 then

          chr:TranslateBy(hum.MoveDirection)

        end

      end

    end)

    end

    end

    end

end)

end

local Button10 = Section13:NewButton("Arsenal script"), "A Arsenal script or Mobile", function()

    loadstring(game:HttpGet("https://raw.githubusercontent.com/GamingScripter/arsenal-hub/main/Arsenal%20GamingScripter", true))()

end 
