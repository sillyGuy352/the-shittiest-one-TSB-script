# the-shittiest-one-TSB-script
i made this when i was bored
local player = game.Players.LocalPlayer

local playerGui = player.PlayerGui

local hotbar = playerGui:FindFirstChild("Hotbar")

local backpack = hotbar:FindFirstChild("Backpack")

local hotbarFrame = backpack:FindFirstChild("Hotbar")

local baseButton = hotbarFrame:FindFirstChild("1").Base

local ToolName = baseButton.ToolName


ToolName.Text = "red"
local player = game.Players.LocalPlayer

local playerGui = player.PlayerGui

local hotbar = playerGui:FindFirstChild("Hotbar")

local backpack = hotbar:FindFirstChild("Backpack")

local hotbarFrame = backpack:FindFirstChild("Hotbar")

local baseButton = hotbarFrame:FindFirstChild("2").Base

local ToolName = baseButton.ToolName


ToolName.Text = "stun"
local player = game.Players.LocalPlayer

local playerGui = player.PlayerGui

local hotbar = playerGui:FindFirstChild("Hotbar")

local backpack = hotbar:FindFirstChild("Backpack")

local hotbarFrame = backpack:FindFirstChild("Hotbar")

local baseButton = hotbarFrame:FindFirstChild("3").Base

local ToolName = baseButton.ToolName


ToolName.Text = "push"
local player = game.Players.LocalPlayer

local playerGui = player.PlayerGui

local hotbar = playerGui:FindFirstChild("Hotbar")

local backpack = hotbar:FindFirstChild("Backpack")

local hotbarFrame = backpack:FindFirstChild("Hotbar")

local baseButton = hotbarFrame:FindFirstChild("4").Base

local ToolName = baseButton.ToolName


ToolName.Text = "lapse blue"
local Players = game:GetService("Players")

local player = Players.LocalPlayer

local playerGui = player:WaitForChild("PlayerGui")


local function findGuiAndSetText()

    local screenGui = playerGui:FindFirstChild("ScreenGui")

    if screenGui then

        local magicHealthFrame = screenGui:FindFirstChild("MagicHealth")

        if magicHealthFrame then

            local textLabel = magicHealthFrame:FindFirstChild("TextLabel")

            if textLabel then

                textLabel.Text = "The Shittiest One"
            end

        end

    end

end
--animation move 1
local animationId = 10468665991


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then


local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://16139108718"

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0


Anim:Play()

Anim:AdjustSpeed(0.1)

Anim.TimePosition = startTime

Anim:AdjustSpeed(0.9)


    end

end

humanoid.AnimationPlayed:Connect(onAnimationPlayed)

--animation move 2
local animationId = 10466974800


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then


local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end
-- move 3 animation
local animationId = 10471336737


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then


local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://14516273501"

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0.3


Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(1)


delay(1.8, function()

    Anim:Stop()

end)


    end

end

humanoid.AnimationPlayed:Connect(onAnimationPlayed)
-- dash animation
local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://14516273501"

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0


Anim:Play()

Anim:AdjustSpeed(1)

Anim.TimePosition = startTime

Anim:AdjustSpeed(1)


    end

end

humanoid.AnimationPlayed:Connect(onAnimationPlayed)

local animationId = 10479335397


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then

local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://14516273501"

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0


Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(1.3)


delay(1.8, function()

    Anim:Stop()

end)


    end

end

humanoid.AnimationPlayed:Connect(onAnimationPlayed)
-- move 4 animation
local animationId = 12510170988


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then

local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://16515850153"

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0


Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(1)


    end

end


humanoid.AnimationPlayed:Connect(onAnimationPlayed)
--wallcombo lol
local animationId = 15955393872


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then

local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://14046756619"

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0.05


Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(1)


    end

end


humanoid.AnimationPlayed:Connect(onAnimationPlayed)

--ult idk
local animationId = 12447707844


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then

local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://14299135500"

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0


Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(1)

    end

end

humanoid.AnimationPlayed:Connect(onAnimationPlayed)
--M1 animations :)
local Players = game:GetService("Players")

local player = Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local animationIdsToStop = {

    [17859015788] = true, --punch idk

    [10469493270] = true, --punch1

    [10469630950] = true, --punch2

    [10469639222] = true, --punch3

    [10469643643] = true, --punch4

}



local replacementAnimations = {

    ["14516273501"] = "rbxassetid://14516273501", --punch1

    ["14516273501"] = "rbxassetid://14516273501", --punch2

    ["14516273501"] = "rbxassetid://14516273501", --punch3

    ["14516273501"] = "rbxassetid://14516273501", --punch4

    ["14516273501"] = "rbxassetid://14516273501", --punch idk

    ["14516273501"] = "rbxassetid://14516273501" --punch idk

}


local queue = {}

local isAnimating = false


local function playReplacementAnimation(animationId)

    if isAnimating then

        table.insert(queue, animationId)

        return

    end

   

    isAnimating = true

    local replacementAnimationId = replacementAnimations[tostring(animationId)]

    if replacementAnimationId then

        local AnimAnim = Instance.new("Animation")

        AnimAnim.AnimationId = replacementAnimationId

        local Anim = humanoid:LoadAnimation(AnimAnim)

        Anim:Play()

       

        Anim.Stopped:Connect(function()

            isAnimating = false

            if #queue > 0 then

                local nextAnimationId = table.remove(queue, 1)

                playReplacementAnimation(nextAnimationId)

            end

        end)

    else

        isAnimating = false

    end

end


local function stopSpecificAnimations()

    for _, track in ipairs(humanoid:GetPlayingAnimationTracks()) do

        local animationId = tonumber(track.Animation.AnimationId:match("%d+"))

        if animationIdsToStop[animationId] then

            track:Stop()

        end

    end

end


local function onAnimationPlayed(animationTrack)

    local animationId = tonumber(animationTrack.Animation.AnimationId:match("%d+"))

    if animationIdsToStop[animationId] then

        stopSpecificAnimations()

        animationTrack:Stop()

       

        local replacementAnimationId = replacementAnimations[tostring(animationId)]

        if replacementAnimationId then

            playReplacementAnimation(animationId)

        end

    end

end


humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoidRootPart = character:WaitForChild("HumanoidRootPart")


local function onBodyVelocityAdded(bodyVelocity)

    if bodyVelocity:IsA("BodyVelocity") then

        bodyVelocity.Velocity = Vector3.new(bodyVelocity.Velocity.X, 0, bodyVelocity.Velocity.Z)

    end

end


character.DescendantAdded:Connect(onBodyVelocityAdded)


for _, descendant in pairs(character:GetDescendants()) do

    onBodyVelocityAdded(descendant)

end


player.CharacterAdded:Connect(function(newCharacter)

    character = newCharacter

    humanoidRootPart = character:WaitForChild("HumanoidRootPart")

    character.DescendantAdded:Connect(onBodyVelocityAdded)

   

    for _, descendant in pairs(character:GetDescendants()) do

        onBodyVelocityAdded(descendant)

    end

end)

humanoid.AnimationPlayed:Connect(onAnimationPlayed)
--credits
-- b64 decode
local function decodeBase64(data)
    local b = 'ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789+/'
    data = string.gsub(data, '[^'..b..'=]', '')
    return (data:gsub('.', function(x)
        if (x == '=') then return '' end
        local r,f = '',(b:find(x)-1)
        for i=6,1,-1 do r=r..(f%2^i-f%2^(i-1)>0 and '1' or '0') end
        return r;
    end):gsub('%d%d%d?%d?%d?%d?%d?%d?', function(x)
        if (#x ~= 8) then return '' end
        local c=0
        for i=1,8 do c=c+(x:sub(i,i)=='1' and 2^(8-i) or 0) end
        return string.char(c)
    end))
end

-- sgui
local sG = Instance.new("ScreenGui")
sG.Name = "UIContainer"
sG.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

-- txlabel
local tL = Instance.new("TextLabel")
tL.Size = UDim2.new(1, 0, 0, 50) -- size
tL.Position = UDim2.new(0, 0, 0, 0) -- Top
tL.BackgroundTransparency = 1 -- bg
tL.Text = decodeBase64("Q3JlZGl0cyB0byB4eDAyQW5kcmVzMDh4eC9TZWFibHVlIGZvciB0ZW1wbGF0ZQ==") -- Decoded text
tL.TextColor3 = Color3.new(1, 1, 1) --clr
tL.Font = Enum.Font.Arcade 
tL.TextScaled = true -- scale
tL.TextTransparency = 0.9 --opaque
tL.Parent = sG
--tp tool
--[[
    @Author: Banqr/Sodium
    @Game: Universal Bypass Anticheat TP TOOL
    @Description: This script creates a teleportation tool with tweening effects to smoothly teleport the player to a clicked position.
    @Dependencies: TeleportPlayer, WritePlayer, GiveTool, RobloxPlace
    ----------------READ ME----------------
    This script provides a teleportation tool that utilizes tweening to move the player to a desired location. 
    The tool is designed to blend with the player's movement speed to reduce the likelihood of detection by anti-cheat systems.
]]
 
local TweenService = game:GetService("TweenService")
local Players = game:GetService("Players")
local LocalPlayer = Players.LocalPlayer
 
local function createTeleportTool()
    local tool = Instance.new("Tool")
    tool.Name = "Infinity but bad"
    tool.RequiresHandle = false
    tool.Parent = LocalPlayer.Backpack
    tool.TextureId = "rbxassetid://17684874568"
 
    local sound = Instance.new("Sound")
    sound.SoundId = "rbxassetid://5066021887"
    sound.Volume = 10
    sound.Looped = false
    sound.Parent = tool
 
    local function createGrapplingEffect(startPos, endPos)
        local part = Instance.new("Part")
        part.Size = Vector3.new(0.2, 0.2, (startPos - endPos).Magnitude)
        part.Anchored = true
        part.CanCollide = false
        part.Position = (startPos + endPos) / 2
        part.CFrame = CFrame.lookAt(startPos, endPos) * CFrame.new(0, 0, -part.Size.Z / 2)
        part.Color = Color3.new(0, 0, 0)
        part.Material = Enum.Material.Fabric
        part.Parent = workspace
 
        game:GetService("Debris"):AddItem(part, 1)
    end
 
    local function onActivated()
        local mouse = LocalPlayer:GetMouse()
        local targetPosition = mouse.Hit.Position
 
        local teleportPart = Instance.new("Part")
        teleportPart.Size = Vector3.new(1, 1, 1)
        teleportPart.Anchored = true
        teleportPart.CanCollide = false
        teleportPart.Position = LocalPlayer.Character.HumanoidRootPart.Position
 
        local mesh = Instance.new("SpecialMesh", teleportPart)
        mesh.MeshId = "rbxassetid://14070473131"
        mesh.Scale = Vector3.new(1, 1, 1)
        
        teleportPart.Parent = workspace
 
        local tweenInfo = TweenInfo.new(
            1, 
            Enum.EasingStyle.Linear, 
            Enum.EasingDirection.InOut, 
            0,
            false, 
            0 
        )
 
        local tweenGoal = {Position = targetPosition}
        local tween = TweenService:Create(teleportPart, tweenInfo, tweenGoal)
 
        local function followTeleportPart()
            LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(teleportPart.Position)
        end
 
        tween:Play()
 
        local connection
        connection = game:GetService("RunService").RenderStepped:Connect(function()
            if teleportPart then
                followTeleportPart()
            end
        end)
 
        createGrapplingEffect(LocalPlayer.Character.HumanoidRootPart.Position, targetPosition)
        sound:Play()
 
        tween.Completed:Connect(function()
            LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(targetPosition)
            teleportPart:Destroy()
            connection:Disconnect()
            sound:Stop()
        end)
    end
 
    tool.Activated:Connect(onActivated)
end
 
createTeleportTool()
