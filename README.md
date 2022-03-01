while wait() do
fireproximityprompt(game:GetService("Workspace").Map.Jobs.InAndOut.FrieWork.ProximityAttachment.ProximityPrompt)
local Service = game:GetService("TweenService")
local Info = TweenInfo.new(3)
local Player = game.Players.LocalPlayer.Character.HumanoidRootPart
local Anim = {CFrame = game:GetService("Workspace").Map.Jobs.InAndOut.Takeout.CFrame}
local Tween = Service:Create(Player,
Info,
Anim)
Tween:Play()
end

setclipboard("https://youtube.com/channel/UCPyDh_5WeZI08mXvCeC-rCA")
game:GetService("StarterGui"):SetCore("SendNotification",{     
Title = "Subscribe!",     
Text = "Click Sure! To Subscribe";
Button1 = "Sure!",
Duration = 30
})
