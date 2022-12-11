
-- Gui to Lua
-- Version: 3.2

-- Instances:

local gui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local UIGradient = Instance.new("UIGradient")
local TextLabel = Instance.new("TextLabel")
local UICorner_2 = Instance.new("UICorner")
local TextLabel_2 = Instance.new("TextLabel")
local UIGradient_2 = Instance.new("UIGradient")
local TextLabel_3 = Instance.new("TextLabel")
local UICorner_3 = Instance.new("UICorner")
local TextLabel_4 = Instance.new("TextLabel")
local UICorner_4 = Instance.new("UICorner")
local ScrollingFrame = Instance.new("ScrollingFrame")
local TextButton = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local UIGradient_3 = Instance.new("UIGradient")
local TextButton_2 = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local UIGradient_4 = Instance.new("UIGradient")
local TextButton_3 = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local UIGradient_5 = Instance.new("UIGradient")
local TextButton_4 = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local UIGradient_6 = Instance.new("UIGradient")
local TextButton_5 = Instance.new("TextButton")
local UICorner_9 = Instance.new("UICorner")
local UIGradient_7 = Instance.new("UIGradient")
local TextButton_6 = Instance.new("TextButton")
local UICorner_10 = Instance.new("UICorner")
local UIGradient_8 = Instance.new("UIGradient")
local TextButton_7 = Instance.new("TextButton")
local UICorner_11 = Instance.new("UICorner")
local UIGradient_9 = Instance.new("UIGradient")
local TextButton_8 = Instance.new("TextButton")
local UICorner_12 = Instance.new("UICorner")
local UIGradient_10 = Instance.new("UIGradient")
local TextLabel_5 = Instance.new("TextLabel")
local UICorner_13 = Instance.new("UICorner")
local UIGradient_11 = Instance.new("UIGradient")
local TextButton_9 = Instance.new("TextButton")
local UICorner_14 = Instance.new("UICorner")
local UIGradient_12 = Instance.new("UIGradient")
local TextLabel_6 = Instance.new("TextLabel")
local UICorner_15 = Instance.new("UICorner")
local UIGradient_13 = Instance.new("UIGradient")
local ImageLabel = Instance.new("ImageLabel")
local UICorner_16 = Instance.new("UICorner")
local UIGradient_14 = Instance.new("UIGradient")

--Properties:

gui.Name = "gui"
gui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
gui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = gui
Frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame.BackgroundTransparency = 0.300
Frame.Position = UDim2.new(0.0231799465, 0, 0.223568618, 0)
Frame.Size = UDim2.new(0, 297, 0, 550)

UICorner.Parent = Frame

UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 85, 127)), ColorSequenceKeypoint.new(0.52, Color3.fromRGB(255, 0, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(85, 170, 255))}
UIGradient.Parent = Frame

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 0.550
TextLabel.Size = UDim2.new(0, 296, 0, 66)
TextLabel.Font = Enum.Font.Cartoon
TextLabel.Text = "Free gamepasses gui (UPDATED)"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

UICorner_2.Parent = TextLabel

TextLabel_2.Parent = Frame
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.Position = UDim2.new(0.0675675645, 0, 0.823529363, 0)
TextLabel_2.Size = UDim2.new(0, 268, 0, 39)
TextLabel_2.Font = Enum.Font.LuckiestGuy
TextLabel_2.Text = "Made by DarkDreamG : YT channel is Flaze11"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 14.000
TextLabel_2.TextWrapped = true

UIGradient_2.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 0, 0)), ColorSequenceKeypoint.new(0.22, Color3.fromRGB(255, 170, 0)), ColorSequenceKeypoint.new(0.40, Color3.fromRGB(255, 255, 0)), ColorSequenceKeypoint.new(0.55, Color3.fromRGB(85, 255, 0)), ColorSequenceKeypoint.new(0.74, Color3.fromRGB(0, 85, 255)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(85, 0, 127))}
UIGradient_2.Parent = TextLabel_2

TextLabel_3.Parent = Frame
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.Position = UDim2.new(0.101339981, 0, 0.893464386, 0)
TextLabel_3.Size = UDim2.new(0, 248, 0, 27)
TextLabel_3.Font = Enum.Font.Cartoon
TextLabel_3.Text = "MORE GAMEPASS BUTTONS TO COME SOON!"
TextLabel_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.TextScaled = true
TextLabel_3.TextSize = 14.000
TextLabel_3.TextWrapped = true

UICorner_3.Parent = TextLabel_3

TextLabel_4.Parent = Frame
TextLabel_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.Position = UDim2.new(0.0979843438, 0, 0.741179347, 0)
TextLabel_4.Size = UDim2.new(0, 248, 0, 27)
TextLabel_4.Font = Enum.Font.SourceSans
TextLabel_4.Text = "Make sure to join the game you are using the gamepass button in!"
TextLabel_4.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_4.TextScaled = true
TextLabel_4.TextSize = 14.000
TextLabel_4.TextWrapped = true

UICorner_4.Parent = TextLabel_4

ScrollingFrame.Parent = Frame
ScrollingFrame.Active = true
ScrollingFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ScrollingFrame.BackgroundTransparency = 0.800
ScrollingFrame.Position = UDim2.new(0, 0, 0.119999997, 0)
ScrollingFrame.Size = UDim2.new(0, 296, 0, 341)

TextButton.Parent = ScrollingFrame
TextButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton.Position = UDim2.new(0.175698414, 0, 0.0410459638, 0)
TextButton.Size = UDim2.new(0, 200, 0, 50)
TextButton.Font = Enum.Font.Cartoon
TextButton.Text = "Free gamepass for jailbreak!"
TextButton.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton.TextScaled = true
TextButton.TextSize = 14.000
TextButton.TextStrokeTransparency = 0.000
TextButton.TextWrapped = true

UICorner_5.Parent = TextButton

UIGradient_3.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 0, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 0, 255))}
UIGradient_3.Parent = TextButton

TextButton_2.Parent = ScrollingFrame
TextButton_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_2.Position = UDim2.new(0.182432428, 0, 0.127360418, 0)
TextButton_2.Size = UDim2.new(0, 200, 0, 50)
TextButton_2.Font = Enum.Font.Cartoon
TextButton_2.Text = "Free gamepass for Vehicle Simulator!"
TextButton_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_2.TextScaled = true
TextButton_2.TextSize = 14.000
TextButton_2.TextStrokeTransparency = 0.000
TextButton_2.TextWrapped = true

UICorner_6.Parent = TextButton_2

UIGradient_4.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 0, 0)), ColorSequenceKeypoint.new(0.51, Color3.fromRGB(255, 85, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 255, 0))}
UIGradient_4.Parent = TextButton_2

TextButton_3.Parent = ScrollingFrame
TextButton_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_3.Position = UDim2.new(0.182432428, 0, 0.220996767, 0)
TextButton_3.Size = UDim2.new(0, 200, 0, 50)
TextButton_3.Font = Enum.Font.Cartoon
TextButton_3.Text = "Free gamepass for Bloxburg!"
TextButton_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_3.TextScaled = true
TextButton_3.TextSize = 14.000
TextButton_3.TextStrokeTransparency = 0.000
TextButton_3.TextWrapped = true

UICorner_7.Parent = TextButton_3

UIGradient_5.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(0, 170, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 255, 127))}
UIGradient_5.Parent = TextButton_3

TextButton_4.Parent = ScrollingFrame
TextButton_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_4.Position = UDim2.new(0.182432428, 0, 0.309178591, 0)
TextButton_4.Size = UDim2.new(0, 200, 0, 50)
TextButton_4.Font = Enum.Font.Cartoon
TextButton_4.Text = "Free gamepass for BrookHaven!"
TextButton_4.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_4.TextScaled = true
TextButton_4.TextSize = 14.000
TextButton_4.TextStrokeTransparency = 0.000
TextButton_4.TextWrapped = true

UICorner_8.Parent = TextButton_4

UIGradient_6.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 255, 0)), ColorSequenceKeypoint.new(0.46, Color3.fromRGB(170, 255, 255)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 255, 127))}
UIGradient_6.Parent = TextButton_4

TextButton_5.Parent = ScrollingFrame
TextButton_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_5.BackgroundTransparency = 0.550
TextButton_5.Position = UDim2.new(0.182432428, 0, 0.400996745, 0)
TextButton_5.Size = UDim2.new(0, 200, 0, 50)
TextButton_5.Font = Enum.Font.Cartoon
TextButton_5.Text = "Free gamepass for Bee Swarm Simulator!"
TextButton_5.TextColor3 = Color3.fromRGB(255, 255, 0)
TextButton_5.TextScaled = true
TextButton_5.TextSize = 14.000
TextButton_5.TextStrokeTransparency = 0.000
TextButton_5.TextWrapped = true

UICorner_9.Parent = TextButton_5

UIGradient_7.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 255, 0)), ColorSequenceKeypoint.new(0.52, Color3.fromRGB(0, 0, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 255, 127))}
UIGradient_7.Parent = TextButton_5

TextButton_6.Parent = ScrollingFrame
TextButton_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_6.Position = UDim2.new(0.182432428, 0, 0.495542169, 0)
TextButton_6.Size = UDim2.new(0, 200, 0, 50)
TextButton_6.Font = Enum.Font.Cartoon
TextButton_6.Text = "Free gamepass for Anomic!"
TextButton_6.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_6.TextScaled = true
TextButton_6.TextSize = 14.000
TextButton_6.TextStrokeTransparency = 0.000
TextButton_6.TextWrapped = true

UICorner_10.Parent = TextButton_6

UIGradient_8.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(153, 124, 96)), ColorSequenceKeypoint.new(0.52, Color3.fromRGB(98, 103, 55)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(157, 155, 98))}
UIGradient_8.Parent = TextButton_6

TextButton_7.Parent = ScrollingFrame
TextButton_7.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_7.Position = UDim2.new(0.182432428, 0, 0.590087652, 0)
TextButton_7.Size = UDim2.new(0, 200, 0, 50)
TextButton_7.Font = Enum.Font.Cartoon
TextButton_7.Text = "Free gamepass for Meep City!"
TextButton_7.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_7.TextScaled = true
TextButton_7.TextSize = 14.000
TextButton_7.TextStrokeTransparency = 0.000
TextButton_7.TextWrapped = true

UICorner_11.Parent = TextButton_7

UIGradient_9.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 255, 255)), ColorSequenceKeypoint.new(0.45, Color3.fromRGB(255, 255, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(170, 0, 255))}
UIGradient_9.Parent = TextButton_7

TextButton_8.Parent = ScrollingFrame
TextButton_8.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_8.Position = UDim2.new(0.182432428, 0, 0.683723986, 0)
TextButton_8.Size = UDim2.new(0, 200, 0, 50)
TextButton_8.Font = Enum.Font.Cartoon
TextButton_8.Text = "Free Gamepass for Tower Of Hell!"
TextButton_8.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_8.TextScaled = true
TextButton_8.TextSize = 14.000
TextButton_8.TextStrokeTransparency = 0.000
TextButton_8.TextWrapped = true

UICorner_12.Parent = TextButton_8

UIGradient_10.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(0, 170, 0)), ColorSequenceKeypoint.new(0.45, Color3.fromRGB(0, 170, 255)), ColorSequenceKeypoint.new(0.75, Color3.fromRGB(255, 255, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(199, 0, 0))}
UIGradient_10.Parent = TextButton_8

TextLabel_5.Parent = ScrollingFrame
TextLabel_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_5.Position = UDim2.new(0.125, 0, 0.863394082, 0)
TextLabel_5.Size = UDim2.new(0, 223, 0, 135)
TextLabel_5.Font = Enum.Font.LuckiestGuy
TextLabel_5.Text = "MORE COMING SOON!"
TextLabel_5.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_5.TextScaled = true
TextLabel_5.TextSize = 14.000
TextLabel_5.TextWrapped = true

UICorner_13.Parent = TextLabel_5

UIGradient_11.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(150, 150, 150)), ColorSequenceKeypoint.new(0.50, Color3.fromRGB(225, 225, 225)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(99, 99, 99))}
UIGradient_11.Parent = TextLabel_5

TextButton_9.Parent = ScrollingFrame
TextButton_9.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_9.Position = UDim2.new(0.179054052, 0, 0.756451249, 0)
TextButton_9.Size = UDim2.new(0, 200, 0, 50)
TextButton_9.Font = Enum.Font.Cartoon
TextButton_9.Text = "Free Gamepass for CHAOS!"
TextButton_9.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_9.TextScaled = true
TextButton_9.TextSize = 14.000
TextButton_9.TextStrokeTransparency = 0.000
TextButton_9.TextWrapped = true

UICorner_14.Parent = TextButton_9

UIGradient_12.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 255, 255)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(199, 0, 0))}
UIGradient_12.Parent = TextButton_9

TextLabel_6.Parent = ScrollingFrame
TextLabel_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_6.Position = UDim2.new(0.182432428, 0, 0.80436933, 0)
TextLabel_6.Size = UDim2.new(0, 200, 0, 31)
TextLabel_6.Font = Enum.Font.LuckiestGuy
TextLabel_6.Text = "NEW!"
TextLabel_6.TextColor3 = Color3.fromRGB(122, 122, 122)
TextLabel_6.TextSize = 24.000
TextLabel_6.TextStrokeTransparency = 0.000

UICorner_15.Parent = TextLabel_6

UIGradient_13.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 255, 0)), ColorSequenceKeypoint.new(0.47, Color3.fromRGB(198, 198, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(212, 212, 0))}
UIGradient_13.Parent = TextLabel_6

ImageLabel.Parent = ScrollingFrame
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.BackgroundTransparency = 1.000
ImageLabel.Position = UDim2.new(0, 0, 0.756040931, 0)
ImageLabel.Rotation = -5.000
ImageLabel.Size = UDim2.new(0, 54, 0, 89)
ImageLabel.Image = "rbxassetid://2204719453"

UICorner_16.Parent = ImageLabel

UIGradient_14.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 255, 0)), ColorSequenceKeypoint.new(0.47, Color3.fromRGB(198, 198, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(212, 212, 0))}
UIGradient_14.Parent = ImageLabel

-- Scripts:

local function KNIHAL_fake_script() -- TextButton.idk 
	local script = Instance.new('LocalScript', TextButton)

	function OnClicked() 
		game.Players.LocalPlayer.UserId = "2837719"
	
	end 
	
	script.Parent.MouseButton1Down:connect(OnClicked)
	
end
coroutine.wrap(KNIHAL_fake_script)()
local function KLSZ_fake_script() -- TextButton.HoverSound 
	local script = Instance.new('LocalScript', TextButton)

	local Button = script.Parent
	
	function MouseEnter()
		Button.Hover.Playing = true
	end
	
	function MouseLeave()
		Button.Hover.Playing = false
	end
	
	Button.MouseEnter:connect(MouseEnter)
	Button.MouseLeave:connect(MouseLeave)
end
coroutine.wrap(KLSZ_fake_script)()
local function YLECVSI_fake_script() -- TextButton.ButtonClickSound 
	local script = Instance.new('LocalScript', TextButton)

	function PlaySound()
		script.Parent.Parent.Sound1:Play(179235828)
	end
	script.Parent.MouseButton1Click:connect(PlaySound)
end
coroutine.wrap(YLECVSI_fake_script)()
local function WZDN_fake_script() -- TextButton_2.idk 
	local script = Instance.new('LocalScript', TextButton_2)

	function OnClicked() 
		game.Players.LocalPlayer.UserId = "1099580"
	
	end 
	
	script.Parent.MouseButton1Down:connect(OnClicked)
	
end
coroutine.wrap(WZDN_fake_script)()
local function QKGKSEL_fake_script() -- TextButton_2.HoverSound 
	local script = Instance.new('LocalScript', TextButton_2)

	local Button = script.Parent
	
	function MouseEnter()
		Button.Hover.Playing = true
	end
	
	function MouseLeave()
		Button.Hover.Playing = false
	end
	
	Button.MouseEnter:connect(MouseEnter)
	Button.MouseLeave:connect(MouseLeave)
end
coroutine.wrap(QKGKSEL_fake_script)()
local function SJLL_fake_script() -- TextButton_2.ButtonClickSound 
	local script = Instance.new('LocalScript', TextButton_2)

	function PlaySound()
		script.Parent.Parent.Sound1:Play(179235828)
	end
	script.Parent.MouseButton1Click:connect(PlaySound)
end
coroutine.wrap(SJLL_fake_script)()
local function JKSG_fake_script() -- TextButton_3.idk 
	local script = Instance.new('LocalScript', TextButton_3)

	function OnClicked() 
		game.Players.LocalPlayer.UserId = "2837719"
	
	end 
	
	script.Parent.MouseButton1Down:connect(OnClicked)
	
end
coroutine.wrap(JKSG_fake_script)()
local function SMWI_fake_script() -- TextButton_3.HoverSound 
	local script = Instance.new('LocalScript', TextButton_3)

	local Button = script.Parent
	
	function MouseEnter()
		Button.Hover.Playing = true
	end
	
	function MouseLeave()
		Button.Hover.Playing = false
	end
	
	Button.MouseEnter:connect(MouseEnter)
	Button.MouseLeave:connect(MouseLeave)
end
coroutine.wrap(SMWI_fake_script)()
local function NYKEM_fake_script() -- TextButton_3.ButtonClickSound 
	local script = Instance.new('LocalScript', TextButton_3)

	function PlaySound()
		script.Parent.Parent.Sound1:Play(179235828)
	end
	script.Parent.MouseButton1Click:connect(PlaySound)
end
coroutine.wrap(NYKEM_fake_script)()
local function KNOWICJ_fake_script() -- TextButton_4.idk 
	local script = Instance.new('LocalScript', TextButton_4)

	function OnClicked() 
		game.Players.LocalPlayer.UserId = "60596019"
	
	end 
	
	script.Parent.MouseButton1Down:connect(OnClicked)
	
end
coroutine.wrap(KNOWICJ_fake_script)()
local function SOWCK_fake_script() -- TextButton_4.HoverSound 
	local script = Instance.new('LocalScript', TextButton_4)

	local Button = script.Parent
	
	function MouseEnter()
		Button.Hover.Playing = true
	end
	
	function MouseLeave()
		Button.Hover.Playing = false
	end
	
	Button.MouseEnter:connect(MouseEnter)
	Button.MouseLeave:connect(MouseLeave)
end
coroutine.wrap(SOWCK_fake_script)()
local function KLZU_fake_script() -- TextButton_4.ButtonClickSound 
	local script = Instance.new('LocalScript', TextButton_4)

	function PlaySound()
		script.Parent.Parent.Sound1:Play(179235828)
	end
	script.Parent.MouseButton1Click:connect(PlaySound)
end
coroutine.wrap(KLZU_fake_script)()
local function RLIOV_fake_script() -- TextButton_5.idk 
	local script = Instance.new('LocalScript', TextButton_5)

	function OnClicked() 
		game.Players.LocalPlayer.UserId = "1912490"
	
	end 
	
	script.Parent.MouseButton1Down:connect(OnClicked)
	
end
coroutine.wrap(RLIOV_fake_script)()
local function TEUK_fake_script() -- TextButton_5.HoverSound 
	local script = Instance.new('LocalScript', TextButton_5)

	local Button = script.Parent
	
	function MouseEnter()
		Button.Hover.Playing = true
	end
	
	function MouseLeave()
		Button.Hover.Playing = false
	end
	
	Button.MouseEnter:connect(MouseEnter)
	Button.MouseLeave:connect(MouseLeave)
end
coroutine.wrap(TEUK_fake_script)()
local function AMBV_fake_script() -- TextButton_5.ButtonClickSound 
	local script = Instance.new('LocalScript', TextButton_5)

	function PlaySound()
		script.Parent.Parent.Sound1:Play(179235828)
	end
	script.Parent.MouseButton1Click:connect(PlaySound)
end
coroutine.wrap(AMBV_fake_script)()
local function SDXOR_fake_script() -- TextButton_6.idk 
	local script = Instance.new('LocalScript', TextButton_6)

	function OnClicked() 
		game.Players.LocalPlayer.UserId = "5352357"
	
	end 
	
	script.Parent.MouseButton1Down:connect(OnClicked)
	
end
coroutine.wrap(SDXOR_fake_script)()
local function XFCQALJ_fake_script() -- TextButton_6.HoverSound 
	local script = Instance.new('LocalScript', TextButton_6)

	local Button = script.Parent
	
	function MouseEnter()
		Button.Hover.Playing = true
	end
	
	function MouseLeave()
		Button.Hover.Playing = false
	end
	
	Button.MouseEnter:connect(MouseEnter)
	Button.MouseLeave:connect(MouseLeave)
end
coroutine.wrap(XFCQALJ_fake_script)()
local function PUBHGS_fake_script() -- TextButton_6.ButtonClickSound 
	local script = Instance.new('LocalScript', TextButton_6)

	function PlaySound()
		script.Parent.Parent.Sound1:Play(179235828)
	end
	script.Parent.MouseButton1Click:connect(PlaySound)
end
coroutine.wrap(PUBHGS_fake_script)()
local function VZXEN_fake_script() -- TextButton_7.idk 
	local script = Instance.new('LocalScript', TextButton_7)

	function OnClicked() 
		game.Players.LocalPlayer.UserId = "123247"
	
	end 
	
	script.Parent.MouseButton1Down:connect(OnClicked)
	
end
coroutine.wrap(VZXEN_fake_script)()
local function RFPUR_fake_script() -- TextButton_7.HoverSound 
	local script = Instance.new('LocalScript', TextButton_7)

	local Button = script.Parent
	
	function MouseEnter()
		Button.Hover.Playing = true
	end
	
	function MouseLeave()
		Button.Hover.Playing = false
	end
	
	Button.MouseEnter:connect(MouseEnter)
	Button.MouseLeave:connect(MouseLeave)
end
coroutine.wrap(RFPUR_fake_script)()
local function LXTUV_fake_script() -- TextButton_7.ButtonClickSound 
	local script = Instance.new('LocalScript', TextButton_7)

	function PlaySound()
		script.Parent.Parent.Sound1:Play(179235828)
	end
	script.Parent.MouseButton1Click:connect(PlaySound)
end
coroutine.wrap(LXTUV_fake_script)()
local function BAFC_fake_script() -- TextButton_8.idk 
	local script = Instance.new('LocalScript', TextButton_8)

	function OnClicked() 
		game.Players.LocalPlayer.UserId = "79745056"
	
	end 
	
	script.Parent.MouseButton1Down:connect(OnClicked)
	
end
coroutine.wrap(BAFC_fake_script)()
local function CLDHRBR_fake_script() -- TextButton_8.HoverSound 
	local script = Instance.new('LocalScript', TextButton_8)

	local Button = script.Parent
	
	function MouseEnter()
		Button.Hover.Playing = true
	end
	
	function MouseLeave()
		Button.Hover.Playing = false
	end
	
	Button.MouseEnter:connect(MouseEnter)
	Button.MouseLeave:connect(MouseLeave)
end
coroutine.wrap(CLDHRBR_fake_script)()
local function ADHIOI_fake_script() -- TextButton_8.ButtonClickSound 
	local script = Instance.new('LocalScript', TextButton_8)

	function PlaySound()
		script.Parent.Parent.Sound1:Play(179235828)
	end
	script.Parent.MouseButton1Click:connect(PlaySound)
end
coroutine.wrap(ADHIOI_fake_script)()
local function GREQ_fake_script() -- TextButton_9.idk 
	local script = Instance.new('LocalScript', TextButton_9)

	function OnClicked() 
		game.Players.LocalPlayer.UserId = "2205774994"
	
	end 
	
	script.Parent.MouseButton1Down:connect(OnClicked)
	
end
coroutine.wrap(GREQ_fake_script)()
local function NGENQPC_fake_script() -- TextButton_9.HoverSound 
	local script = Instance.new('LocalScript', TextButton_9)

	local Button = script.Parent
	
	function MouseEnter()
		Button.Hover.Playing = true
	end
	
	function MouseLeave()
		Button.Hover.Playing = false
	end
	
	Button.MouseEnter:connect(MouseEnter)
	Button.MouseLeave:connect(MouseLeave)
end
coroutine.wrap(NGENQPC_fake_script)()
local function ZYZDYY_fake_script() -- TextButton_9.ButtonClickSound 
	local script = Instance.new('LocalScript', TextButton_9)

	function PlaySound()
		script.Parent.Parent.Sound1:Play(179235828)
	end
	script.Parent.MouseButton1Click:connect(PlaySound)
end
coroutine.wrap(ZYZDYY_fake_script)()
local function JPFNALZ_fake_script() -- gui.Drag Gui Script 
	local script = Instance.new('Script', gui)

	frame = script.Parent["Frame"]---------- Your Frame Name!!!!!! 
	frame.Draggable = true
	frame.Active = true
	frame.Selectable = true
end
coroutine.wrap(JPFNALZ_fake_script)()
