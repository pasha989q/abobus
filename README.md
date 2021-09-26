-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local TextButton1 = Instance.new("TextButton")
local TextBox1 = Instance.new("TextBox")
local TextBox3 = Instance.new("TextBox")
local TextBox4 = Instance.new("TextBox")
local TextBox6 = Instance.new("TextBox")
local TextBox5 = Instance.new("TextBox")
local TextBox2 = Instance.new("TextBox")
local Open = Instance.new("TextButton")
local X = Instance.new("TextButton")
local TextButton2 = Instance.new("TextButton")
local TextButton3 = Instance.new("TextButton")
local TextButton5 = Instance.new("TextButton")
local TextButton4 = Instance.new("TextButton")
local TextButton6 = Instance.new("TextButton")
local Destroy = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

TextButton1.Name = "TextButton1"
TextButton1.Parent = ScreenGui
TextButton1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton1.Position = UDim2.new(0.207033008, 0, 0.658573627, 0)
TextButton1.Size = UDim2.new(0, 200, 0, 50)
TextButton1.Visible = false
TextButton1.Font = Enum.Font.SourceSans
TextButton1.Text = "1"
TextButton1.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton1.TextSize = 14.000

TextBox1.Name = "TextBox1"
TextBox1.Parent = ScreenGui
TextBox1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextBox1.Position = UDim2.new(0.207032979, 0, 0.56145674, 0)
TextBox1.Size = UDim2.new(0, 200, 0, 50)
TextBox1.Visible = false
TextBox1.Font = Enum.Font.SourceSans
TextBox1.Text = "1"
TextBox1.TextColor3 = Color3.fromRGB(0, 0, 0)
TextBox1.TextSize = 14.000

TextBox3.Name = "TextBox3"
TextBox3.Parent = ScreenGui
TextBox3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextBox3.Position = UDim2.new(0.769053102, 0, 0.56145674, 0)
TextBox3.Size = UDim2.new(0, 200, 0, 50)
TextBox3.Visible = false
TextBox3.Font = Enum.Font.SourceSans
TextBox3.Text = "3"
TextBox3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextBox3.TextSize = 14.000

TextBox4.Name = "TextBox4"
TextBox4.Parent = ScreenGui
TextBox4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextBox4.Position = UDim2.new(0.582069099, 0, 0.559939325, 0)
TextBox4.Size = UDim2.new(0, 200, 0, 50)
TextBox4.Visible = false
TextBox4.Font = Enum.Font.SourceSans
TextBox4.Text = "4"
TextBox4.TextColor3 = Color3.fromRGB(0, 0, 0)
TextBox4.TextSize = 14.000

TextBox6.Name = "TextBox6"
TextBox6.Parent = ScreenGui
TextBox6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextBox6.Position = UDim2.new(0.0232269615, 0, 0.559939265, 0)
TextBox6.Size = UDim2.new(0, 200, 0, 50)
TextBox6.Visible = false
TextBox6.Font = Enum.Font.SourceSans
TextBox6.Text = "6"
TextBox6.TextColor3 = Color3.fromRGB(0, 0, 0)
TextBox6.TextSize = 14.000

TextBox5.Name = "TextBox5"
TextBox5.Parent = ScreenGui
TextBox5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextBox5.Position = UDim2.new(0.390898377, 0, 0.55842185, 0)
TextBox5.Size = UDim2.new(0, 200, 0, 50)
TextBox5.Visible = false
TextBox5.Font = Enum.Font.SourceSans
TextBox5.Text = "5"
TextBox5.TextColor3 = Color3.fromRGB(0, 0, 0)
TextBox5.TextSize = 14.000

TextBox2.Name = "TextBox2"
TextBox2.Parent = ScreenGui
TextBox2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextBox2.Position = UDim2.new(0.76333642, 0, 0.75720787, 0)
TextBox2.Size = UDim2.new(0, 200, 0, 50)
TextBox2.Visible = false
TextBox2.Font = Enum.Font.SourceSans
TextBox2.Text = "2"
TextBox2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextBox2.TextSize = 14.000

Open.Name = "Open"
Open.Parent = ScreenGui
Open.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Open.Position = UDim2.new(0, 0, 0.125948399, 0)
Open.Size = UDim2.new(0, 108, 0, 50)
Open.Font = Enum.Font.SourceSans
Open.Text = "Open"
Open.TextColor3 = Color3.fromRGB(0, 0, 0)
Open.TextSize = 14.000

X.Name = "X"
X.Parent = ScreenGui
X.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
X.Position = UDim2.new(0.901703179, 0, 0.511380851, 0)
X.Size = UDim2.new(0, 31, 0, 33)
X.Visible = false
X.Font = Enum.Font.SourceSans
X.Text = "X"
X.TextColor3 = Color3.fromRGB(0, 0, 0)
X.TextSize = 14.000

TextButton2.Name = "TextButton2"
TextButton2.Parent = ScreenGui
TextButton2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton2.Position = UDim2.new(0.763611555, 0, 0.855842173, 0)
TextButton2.Size = UDim2.new(0, 200, 0, 50)
TextButton2.Visible = false
TextButton2.Font = Enum.Font.SourceSans
TextButton2.Text = "2"
TextButton2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton2.TextSize = 14.000

TextButton3.Name = "TextButton3"
TextButton3.Parent = ScreenGui
TextButton3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton3.Position = UDim2.new(0.769053161, 0, 0.658573627, 0)
TextButton3.Size = UDim2.new(0, 200, 0, 50)
TextButton3.Visible = false
TextButton3.Font = Enum.Font.SourceSans
TextButton3.Text = "3"
TextButton3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton3.TextSize = 14.000

TextButton5.Name = "TextButton5"
TextButton5.Parent = ScreenGui
TextButton5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton5.Position = UDim2.new(0.391575396, 0, 0.658573568, 0)
TextButton5.Size = UDim2.new(0, 200, 0, 50)
TextButton5.Visible = false
TextButton5.Font = Enum.Font.SourceSans
TextButton5.Text = "5"
TextButton5.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton5.TextSize = 14.000

TextButton4.Name = "TextButton4"
TextButton4.Parent = ScreenGui
TextButton4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton4.Position = UDim2.new(0.58262378, 0, 0.658573568, 0)
TextButton4.Size = UDim2.new(0, 200, 0, 50)
TextButton4.Visible = false
TextButton4.Font = Enum.Font.SourceSans
TextButton4.Text = "4"
TextButton4.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton4.TextSize = 14.000

TextButton6.Name = "TextButton6"
TextButton6.Parent = ScreenGui
TextButton6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton6.Position = UDim2.new(0.0237816423, 0, 0.657056093, 0)
TextButton6.Size = UDim2.new(0, 200, 0, 50)
TextButton6.Visible = false
TextButton6.Font = Enum.Font.SourceSans
TextButton6.Text = "6"
TextButton6.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton6.TextSize = 14.000

Destroy.Name = "Destroy"
Destroy.Parent = ScreenGui
Destroy.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Destroy.Position = UDim2.new(0.0237816442, 0, 0.494688869, 0)
Destroy.Size = UDim2.new(0, 200, 0, 61)
Destroy.Visible = false
Destroy.Font = Enum.Font.SourceSans
Destroy.Text = "Destroy"
Destroy.TextColor3 = Color3.fromRGB(0, 0, 0)
Destroy.TextSize = 14.000

-- Scripts:

local function MNFNV_fake_script() -- TextButton1.LocalScript 
	local script = Instance.new('LocalScript', TextButton1)

	
	local Remote = game.ReplicatedStorage.Events['HitPart']
	abobus = false
	killing = false
	script.Parent.MouseButton1Click:Connect(function()
		if killing then
			abobus = false
			killing = false
		else
			if not killing then
				abobus = true
				killing = true
				game:GetService("RunService").RenderStepped:connect(function()
					if killing then
						local player = game:GetService("Players")[script.Parent.Parent.TextBox1.Text]
					
						if player.Team ~= game.Players.LocalPlayer.Team then
							local Arguments = {
								[1] = workspace[script.Parent.Parent.TextBox1.Text].Head,
								[2] = workspace[script.Parent.Parent.TextBox1.Text].Head.Position,
								[3] = workspace[game.Players.LocalPlayer.Name].EquippedTool.Value,
								[4] = math.rad(1,100000),
								[5] = workspace[game.Players.LocalPlayer.Name].Gun,
								[8] = 8, --damage multiplier
								[9] = false,
								[10] = false,
								[11] = Vector3.new(),
								[12] = math.rad(1,100000),
								[13] = Vector3.new()
							}
	
							Remote:FireServer(unpack(Arguments))
	
	               
						end
	end
	end)
	end
	end
	end)
end
coroutine.wrap(MNFNV_fake_script)()
local function VHUGCHP_fake_script() -- Open.LocalScript 
	local script = Instance.new('LocalScript', Open)

	script.Parent.MouseButton1Click:Connect(function()
		for i, v in pairs(script.Parent.Parent:GetChildren()) do
			v.Visible = not v.Visible
	
		end
	end)
end
coroutine.wrap(VHUGCHP_fake_script)()
local function ZVBL_fake_script() -- X.LocalScript 
	local script = Instance.new('LocalScript', X)

	script.Parent.MouseButton1Click:Connect(function()
		for i, v in pairs(script.Parent.Parent:GetChildren()) do
			v.Visible = not v.Visible
	
		end
	end)
end
coroutine.wrap(ZVBL_fake_script)()
local function XYYUQ_fake_script() -- TextButton2.LocalScript 
	local script = Instance.new('LocalScript', TextButton2)

	
	local Remote = game.ReplicatedStorage.Events['HitPart']
	abobus1 = false
	killing1 = false
	script.Parent.MouseButton1Click:Connect(function()
		if killing1 then
			abobus1 = false
			killing1 = false
		else
			if not killing1 then
				abobus1 = true
				killing1 = true
				game:GetService("RunService").RenderStepped:connect(function()
					if killing1 then
						local player = game:GetService("Players")[script.Parent.Parent.TextBox2.Text]
					
						if player.Team ~= game.Players.LocalPlayer.Team then
							local Arguments = {
								[1] = workspace[script.Parent.Parent.TextBox2.Text].Head,
								[2] = workspace[script.Parent.Parent.TextBox2.Text].Head.Position,
								[3] = workspace[game.Players.LocalPlayer.Name].EquippedTool.Value,
								[4] = math.rad(1,100000),
								[5] = workspace[game.Players.LocalPlayer.Name].Gun,
								[8] = 8, --damage multiplier
								[9] = false,
								[10] = false,
								[11] = Vector3.new(),
								[12] = math.rad(1,100000),
								[13] = Vector3.new()
							}
	
							Remote:FireServer(unpack(Arguments))
	               
						end
	end
	end)
	end
	end
	end)
end
coroutine.wrap(XYYUQ_fake_script)()
local function MPWV_fake_script() -- TextButton3.LocalScript 
	local script = Instance.new('LocalScript', TextButton3)

	
	local Remote = game.ReplicatedStorage.Events['HitPart']
	abobus2 = false
	killing2 = false
	script.Parent.MouseButton1Click:Connect(function()
		if killing2 then
			abobus2 = false
			killing2 = false
		else
			if not killing2 then
				abobus2 = true
				killing2 = true
				game:GetService("RunService").RenderStepped:connect(function()
					if killing2 then
						local player = game:GetService("Players")[script.Parent.Parent.TextBox3.Text]
					
						if player.Team ~= game.Players.LocalPlayer.Team then
							local Arguments = {
								[1] = workspace[script.Parent.Parent.TextBox3.Text].Head,
								[2] = workspace[script.Parent.Parent.TextBox3.Text].Head.Position,
								[3] = workspace[game.Players.LocalPlayer.Name].EquippedTool.Value,
								[4] = math.rad(1,100000),
								[5] = workspace[game.Players.LocalPlayer.Name].Gun,
								[8] = 8, --damage multiplier
								[9] = false,
								[10] = false,
								[11] = Vector3.new(),
								[12] = math.rad(1,100000),
								[13] = Vector3.new()
							}
	
							Remote:FireServer(unpack(Arguments))
	               
						end
	end
	end)
	end
	end
	end)
end
coroutine.wrap(MPWV_fake_script)()
local function QZWXD_fake_script() -- TextButton5.LocalScript 
	local script = Instance.new('LocalScript', TextButton5)

	
	local Remote = game.ReplicatedStorage.Events['HitPart']
	abobus4 = false
	killing4 = false
	script.Parent.MouseButton1Click:Connect(function()
		if killing4 then
			abobus4 = false
			killing4 = false
		else
			if not killing4 then
				abobus4 = true
				killing4 = true
				game:GetService("RunService").RenderStepped:connect(function()
					if killing4 then
						local player = game:GetService("Players")[script.Parent.Parent.TextBox5.Text]
					
						if player.Team ~= game.Players.LocalPlayer.Team then
							local Arguments = {
								[1] = workspace[script.Parent.Parent.TextBox5.Text].Head,
								[2] = workspace[script.Parent.Parent.TextBox5.Text].Head.Position,
								[3] = workspace[game.Players.LocalPlayer.Name].EquippedTool.Value,
								[4] = math.rad(1,100000),
								[5] = workspace[game.Players.LocalPlayer.Name].Gun,
								[8] = 8, --damage multiplier
								[9] = false,
								[10] = false,
								[11] = Vector3.new(),
								[12] = math.rad(1,100000),
								[13] = Vector3.new()
							}
	
							Remote:FireServer(unpack(Arguments))
	               
						end
	end
	end)
	end
	end
	end)
end
coroutine.wrap(QZWXD_fake_script)()
local function SMHTX_fake_script() -- TextButton4.LocalScript 
	local script = Instance.new('LocalScript', TextButton4)

	
	local Remote = game.ReplicatedStorage.Events['HitPart']
	abobus3 = false
	killing3 = false
	script.Parent.MouseButton1Click:Connect(function()
		if killing3 then
			abobus3 = false
			killing3 = false
		else
			if not killing3 then
				abobus3 = true
				killing3 = true
				game:GetService("RunService").RenderStepped:connect(function()
					if killing3 then
						local player = game:GetService("Players")[script.Parent.Parent.TextBox4.Text]
					
						if player.Team ~= game.Players.LocalPlayer.Team then
							local Arguments = {
								[1] = workspace[script.Parent.Parent.TextBox4.Text].Head,
								[2] = workspace[script.Parent.Parent.TextBox4.Text].Head.Position,
								[3] = workspace[game.Players.LocalPlayer.Name].EquippedTool.Value,
								[4] = math.rad(1,100000),
								[5] = workspace[game.Players.LocalPlayer.Name].Gun,
								[8] = 8, --damage multiplier
								[9] = false,
								[10] = false,
								[11] = Vector3.new(),
								[12] = math.rad(1,100000),
								[13] = Vector3.new()
							}
	
							Remote:FireServer(unpack(Arguments))
	               
						end
	end
	end)
	end
	end
	end)
end
coroutine.wrap(SMHTX_fake_script)()
local function AXNXJS_fake_script() -- TextButton6.LocalScript 
	local script = Instance.new('LocalScript', TextButton6)

	
	local Remote = game.ReplicatedStorage.Events['HitPart']
	abobus5 = false
	killing5 = false
	script.Parent.MouseButton1Click:Connect(function()
		if killing5 then
			abobus5 = false
			killing5 = false
		else
			if not killing5 then
				abobus5 = true
				killing5 = true
				game:GetService("RunService").RenderStepped:connect(function()
					if killing5 then
						local player = game:GetService("Players")[script.Parent.Parent.TextBox6.Text]
					
						if player.Team ~= game.Players.LocalPlayer.Team then
							local Arguments = {
								[1] = workspace[script.Parent.Parent.TextBox6.Text].Head,
								[2] = workspace[script.Parent.Parent.TextBox6.Text].Head.Position,
								[3] = workspace[game.Players.LocalPlayer.Name].EquippedTool.Value,
								[4] = math.rad(1,100000),
								[5] = workspace[game.Players.LocalPlayer.Name].Gun,
								[8] = 8, --damage multiplier
								[9] = false,
								[10] = false,
								[11] = Vector3.new(),
								[12] = math.rad(1,100000),
								[13] = Vector3.new()
							}
	
							Remote:FireServer(unpack(Arguments))
	               
						end
	end
	end)
	end
	end
	end)
end
coroutine.wrap(AXNXJS_fake_script)()
local function LLZN_fake_script() -- Destroy.LocalScript 
	local script = Instance.new('LocalScript', Destroy)

	script.Parent.MouseButton1Click:Connect(function()
	script.Parent.Parent:Destroy()
	end)
end
coroutine.wrap(LLZN_fake_script)()
