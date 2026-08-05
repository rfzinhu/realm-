--==================================================
-- REALM COMMUNITY MENU
-- Feito por Rafael.wz
-- Realm Community
-- VERSÃO 0.0.1 - VERSÃO DE TESTE
--==================================================

local Players = game:GetService("Players")
local TweenService = game:GetService("TweenService")
local UserInputService = game:GetService("UserInputService")
local RunService = game:GetService("RunService")

local Player = Players.LocalPlayer
local PlayerGui = Player:WaitForChild("PlayerGui")

--==================================================
-- CONFIGURAÇÕES PRINCIPAIS
--==================================================

local OptionNames = {
	"Banana Hub Versao Free",
	"Quantum Hub",
	"Gravity Hub",
	"Vector Hub",
	"Hoho Hub",
	"Cooka hub",
	"aimbot centudox",
	"farm bounty",
	"Neva Hub",
	"Black v kaitun"
}

-- ID DA LOGO
local RealmLogo = "rbxassetid://103214977614276"

-- COR PADRÃO
local DefaultColor = Color3.fromRGB(145, 70, 255)
local ThemeColor = DefaultColor

--==================================================
-- TEMAS
--==================================================

local Themes = {
	Roxo = Color3.fromRGB(145, 70, 255),
	Azul = Color3.fromRGB(50, 130, 255),
	Verde = Color3.fromRGB(40, 210, 120),
	Vermelho = Color3.fromRGB(255, 65, 75),
	Laranja = Color3.fromRGB(255, 135, 40),
	Rosa = Color3.fromRGB(255, 70, 170)
}

--==================================================
-- FUNÇÕES DAS 10 OPÇÕES
--==================================================

local function Codigo01()
	print("Função 01 executada")
	loadstring(game:HttpGet("https://raw.githubusercontent.com/aloaloalo322/sssdas/refs/heads/main/cc"))()
end

local function Codigo02()
	print("Função 02 executada")
    loadstring(game:HttpGet("https://raw.githubusercontent.com/flazhy/QuantumOnyx/refs/heads/main/QuantumOnyx.lua"))()
end

local function Codigo03()
	print("Função 03 executada")
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Dev-GravityHub/BloxFruit/refs/heads/main/Main.lua"))()
end

local function Codigo04()
	print("Função 04 executada")
    loadstring(game:HttpGet("https://vectorhub.space"))()/
end

local function Codigo05()
	print("Função 05 executada")
	loadstring(game:HttpGet("https://raw.githubusercontent.com/acsu123/HOHO_H/main/Loading_UI"))()
end

local function Codigo06()
	print("Função 06 executada")
	loadstring(game:HttpGet"https://raw.githubusercontent.com/UserDevEthical/Loadstring/main/CokkaHub.lua")()
end

local function Codigo07()
	print("Função 07 executada")
loadstring(game:HttpGet("https://raw.githubusercontent.com/JustParadozCode/CentuDox-Hub/refs/heads/main/CentuDox-V3.xyz"))()
end

local function Codigo08()
	print("Função 08 executada")
	getgenv().Config = {
    ["Setting"] = {
        ["Team"] = "Pirates", -- Pirates/Marines
        ["FPS Boost"] = false,
        ["RemoveNotification"] = false,
        ["Time Skip Player"] = 120 -- Second
    },
    ["Run"] = {
        ["RunIfLowHealth"] = true,
        ["HealtRun"] = 30, -- %
        ["HealthBack"] = 50, -- %
        ["Teleport Y"] = 400
    },
    ["Skip"] = {
        ["Skip V4"] = false,
        ["Skip Fruits"] = {"Portal-Portal", "Buddha-Buddha"}
    },
    ["Bounty"] = {
        ["Aimbot Camera"] = true,
        ["ESP Player"] = true
    },
    ["Weapon"] = {
        ["Melee"] = {
            ["Use Melee"] = true,
            ["Z"] = {Enable = true, Hold = 0.1},
            ["X"] = {Enable = true, Hold = 0.1},
            ["C"] = {Enable = true, Hold = 0.1}
        },
        ["Fruits"] = {
            ["Use Fruits"] = true,
            ["Z"] = {Enable = true, Hold = 0.1},
            ["X"] = {Enable = true, Hold = 0.1},
            ["C"] = {Enable = true, Hold = 0.1},
            ["V"] = {Enable = false, Hold = 0.1},
            ["F"] = {Enable = false, Hold = 0.1}
        },
        ["Sword"] = {
            ["Use Sword"] = true,
            ["Z"] = {Enable = true, Hold = 0.1},
            ["X"] = {Enable = false, Hold = 0.1}
        },
        ["Gun"] = {
            ["Use Gun"] = false,
            ["Z"] = {Enable = false, Hold = 0.1},
            ["X"] = {Enable = false, Hold = 0.1}
        },
    },
    ["Misc"] = {
        ["Active Race V3"] = true,
        ["Active Race V4"] = true,
        ["Random And Store Fruits"] = false
    },
    ["Webhook"] = {      
        ["UrlWebhook"] = "",
        ["Enable"] = false
    }
}
loadstring(game:HttpGet("https://raw.githubusercontent.com/Dev-BlueX/...../refs/heads/main/FarmBounty.lua"))()
end

local function Codigo09()
	print("Função 09 executada")
	loadstring(game:HttpGet("https://raw.githubusercontent.com/VEZ2/NEVAHUB/main/2"))()
end

local function Codigo10()
	print("Função 10 executada")
	getgenv().Config = {
    ["Hide UI"] = false,
    ["White Screen"] = false,
    ["Black Screen"] = false,
    ["Start Farm"] = true,
	
    ["Exit When Full Item"] = true,  
    
    ["Settings"] = {
        ["FPS Booster"] = true,
    },

    ["Auto Chat"] = {
        ["Enabled"] = false,
        ["Content"] = {"", "", ""},
        ["Time Chat"] = 9999 
    },

    ["HOP"] = {
        ["Enabled"] = true,
        ["time hop"] = 3000 
    },

    ["Melee"] = {
        ["All Melee V1"] = true,
        ["Super Huamn"] = true,
        ["Dragon Talon"] = true,
        ["Sharkman Karate"] = true,
        ["Elechic Claw"] = true,
        ["GodHuman"] = true,
    },
	
    ["Sword"] = {
        ["All Sword"] = true,
        ["Saber"] = true,
        ["Pole"] = true,
        ["Rengoku"] = true,
        ["Midnight Blade"] = true,
        ["Soul Cane"] = true,
        ["Gravity Cane"] = true,
        ["Dragon Trident"] = true,
        ["Legendary Sword"] = true,
        ["True Triple Katana"] = true,
        ["Twin Hooks"] = true,
        ["Canvander"] = true,
        ["Buddy Sword"] = true,
        ["Hallow Scythe"] = true,
        ["Yama"] = true,
        ["Tushita"] = true,
        ["Cursed Dual Katana"] = true,
    },

    ["Gun"] = {
        ["All Gun"] = true,
        ["Acidum Rifle"] = true,
        ["Kabucha"] = true,
        ["Serpent Bow"] = true,
        ["Skull Guitar"] = true,
    },

    ["Race"] = {
        ["Auto V2"] = true,
        ["Auto V3"] = true,
    },
}
loadstring(game:HttpGet("https://raw.githubusercontent.com/nvb201112/Black-V-Hub/refs/heads/main/KaitunBF.luau"))()
end

local Functions = {
	Codigo01,
	Codigo02,
	Codigo03,
	Codigo04,
	Codigo05,
	Codigo06,
	Codigo07,
	Codigo08,
	Codigo09,
	Codigo10
}

--==================================================
-- FUNÇÕES AUXILIARES
--==================================================

local function New(class, properties)

	local object = Instance.new(class)

	for property, value in pairs(properties) do
		object[property] = value
	end

	return object
end

local function Corner(object, radius)

	local corner = Instance.new("UICorner")

	corner.CornerRadius = UDim.new(0, radius)

	corner.Parent = object

end

local function Tween(object, properties, time)

	return TweenService:Create(
		object,
		TweenInfo.new(
			time or 0.2,
			Enum.EasingStyle.Quart,
			Enum.EasingDirection.Out
		),
		properties
	)

end

--==================================================
-- SCREEN GUI
--==================================================

local ScreenGui = New("ScreenGui", {

	Name = "RealmCommunityMenu",

	ResetOnSpawn = false,

	ZIndexBehavior = Enum.ZIndexBehavior.Sibling,

	Parent = PlayerGui
})

--==================================================
-- BOTÃO DA LOGO
--==================================================

local SettingsButton = New("ImageButton", {

	Name = "RealmButton",

	Size = UDim2.fromOffset(58, 58),

	Position = UDim2.new(1, -75, 0, 15),

	BackgroundColor3 = Color3.fromRGB(20, 18, 25),

	BackgroundTransparency = 0,

	BorderSizePixel = 0,

	Image = RealmLogo,

	ImageTransparency = 0,

	ImageColor3 = Color3.fromRGB(255, 255, 255),

	ScaleType = Enum.ScaleType.Fit,

	AutoButtonColor = false,

	ZIndex = 50,

	Parent = ScreenGui
})

Corner(SettingsButton, 14)

local ButtonStroke = Instance.new("UIStroke")

ButtonStroke.Name = "LogoStroke"

ButtonStroke.Color = ThemeColor

ButtonStroke.Thickness = 2

ButtonStroke.Transparency = 0.1

ButtonStroke.Parent = SettingsButton

--==================================================
-- ANIMAÇÃO DA LOGO
--==================================================

SettingsButton.MouseEnter:Connect(function()

	Tween(SettingsButton, {
		Size = UDim2.fromOffset(64, 64)
	}, 0.15):Play()

	Tween(ButtonStroke, {
		Thickness = 3
	}, 0.15):Play()

end)

SettingsButton.MouseLeave:Connect(function()

	Tween(SettingsButton, {
		Size = UDim2.fromOffset(58, 58)
	}, 0.15):Play()

	Tween(ButtonStroke, {
		Thickness = 2
	}, 0.15):Play()

end)

--==================================================
-- MENU PRINCIPAL
--==================================================

local Main = New("Frame", {

	Name = "Main",

	Size = UDim2.fromOffset(650, 430),

	Position = UDim2.fromScale(0.5, 0.5),

	AnchorPoint = Vector2.new(0.5, 0.5),

	BackgroundColor3 = Color3.fromRGB(15, 14, 20),

	BackgroundTransparency = 0.05,

	BorderSizePixel = 0,

	Visible = false,

	ZIndex = 1,

	Parent = ScreenGui
})

Corner(Main, 14)

--==================================================
-- BORDA RGB
--==================================================

local RGBEnabled = false
local RGBConnection

local RGBStroke = Instance.new("UIStroke")

RGBStroke.Name = "RGBBorder"

RGBStroke.Thickness = 2

RGBStroke.Transparency = 0

RGBStroke.Color = ThemeColor

RGBStroke.Parent = Main

local function StartRGB()

	if RGBConnection then
		return
	end

	RGBEnabled = true

	RGBConnection = RunService.RenderStepped:Connect(function()

		if not RGBEnabled then
			return
		end

		local hue = (tick() % 5) / 5

		RGBStroke.Color =
			Color3.fromHSV(hue, 1, 1)

	end)

end

local function StopRGB()

	RGBEnabled = false

	if RGBConnection then

		RGBConnection:Disconnect()

		RGBConnection = nil

	end

	RGBStroke.Color = ThemeColor

end

--==================================================
-- FUNDO
--==================================================

local Background = New("ImageLabel", {

	Name = "Background",

	Size = UDim2.fromScale(1, 1),

	Position = UDim2.fromScale(0, 0),

	BackgroundTransparency = 1,

	Image = "",

	ImageTransparency = 0.82,

	ScaleType = Enum.ScaleType.Crop,

	ZIndex = 1,

	Parent = Main
})

Corner(Background, 14)

--==================================================
-- TÍTULO
--==================================================

local Title = New("TextLabel", {

	Size = UDim2.new(1, -150, 0, 50),

	Position = UDim2.fromOffset(25, 15),

	BackgroundTransparency = 1,

	Text = "Realm Community menu",

	TextColor3 = Color3.new(1, 1, 1),

	TextSize = 24,

	Font = Enum.Font.GothamBold,

	TextXAlignment = Enum.TextXAlignment.Left,

	ZIndex = 3,

	Parent = Main
})

local RealmText = New("TextLabel", {

	Size = UDim2.fromOffset(85, 50),

	Position = UDim2.fromOffset(25, 15),

	BackgroundTransparency = 1,

	Text = "Realm",

	TextColor3 = ThemeColor,

	TextSize = 24,

	Font = Enum.Font.GothamBold,

	TextXAlignment = Enum.TextXAlignment.Left,

	ZIndex = 4,

	Parent = Main
})

--==================================================
-- BOTÃO CONFIGURAÇÕES
--==================================================

local MenuSettings = New("TextButton", {

	Name = "MenuSettings",

	Size = UDim2.fromOffset(60, 48),

	Position = UDim2.new(1, -80, 0, 15),

	BackgroundColor3 = Color3.fromRGB(30, 28, 37),

	BorderSizePixel = 0,

	Text = "⚙",

	TextColor3 = ThemeColor,

	TextSize = 27,

	Font = Enum.Font.GothamBold,

	AutoButtonColor = false,

	ZIndex = 5,

	Parent = Main
})

Corner(MenuSettings, 12)

--==================================================
-- LINHA
--==================================================

local Line = New("Frame", {

	Size = UDim2.new(1, -40, 0, 3),

	Position = UDim2.fromOffset(20, 80),

	BackgroundColor3 = ThemeColor,

	BorderSizePixel = 0,

	ZIndex = 3,

	Parent = Main
})

--==================================================
-- OPÇÕES PRINCIPAIS
--==================================================

local OptionsFrame = New("ScrollingFrame", {

	Name = "Options",

	Size = UDim2.new(1, -40, 1, -150),

	Position = UDim2.fromOffset(20, 95),

	BackgroundTransparency = 1,

	BorderSizePixel = 0,

	ScrollBarThickness = 4,

	ScrollBarImageColor3 = ThemeColor,

	CanvasSize = UDim2.fromOffset(0, 500),

	ZIndex = 3,

	Parent = Main
})

for i = 1, 10 do

	local Option = New("Frame", {

		Name = "Option" .. i,

		Size = UDim2.new(1, -10, 0, 40),

		Position = UDim2.fromOffset(
			5,
			(i - 1) * 48
		),

		BackgroundColor3 = Color3.fromRGB(25, 24, 32),

		BorderSizePixel = 0,

		ZIndex = 4,

		Parent = OptionsFrame
	})

	Corner(Option, 9)

	New("TextLabel", {

		Size = UDim2.new(1, -70, 1, 0),

		Position = UDim2.fromOffset(15, 0),

		BackgroundTransparency = 1,

		Text = OptionNames[i],

		TextColor3 =
			Color3.fromRGB(235, 235, 240),

		TextSize = 14,

		Font = Enum.Font.GothamMedium,

		TextXAlignment =
			Enum.TextXAlignment.Left,

		ZIndex = 5,

		Parent = Option
	})

	local PlayButton = New("TextButton", {

		Name = "PlayButton",

		Size = UDim2.fromOffset(32, 32),

		Position = UDim2.new(
			1,
			-39,
			0.5,
			-16
		),

		BackgroundColor3 = ThemeColor,

		BorderSizePixel = 0,

		Text = "▶",

		TextColor3 = Color3.new(1, 1, 1),

		TextSize = 13,

		Font = Enum.Font.GothamBold,

		AutoButtonColor = false,

		ZIndex = 6,

		Parent = Option
	})

	Corner(PlayButton, 8)

	PlayButton.MouseEnter:Connect(function()

		Tween(PlayButton, {
			Size = UDim2.fromOffset(35, 35)
		}, 0.15):Play()

	end)

	PlayButton.MouseLeave:Connect(function()

		Tween(PlayButton, {
			Size = UDim2.fromOffset(32, 32)
		}, 0.15):Play()

	end)

	PlayButton.MouseButton1Click:Connect(function()

		local SelectedFunction = Functions[i]

		if SelectedFunction then
			SelectedFunction()
		end

	end)

end

--==================================================
-- RODAPÉ
--==================================================

New("TextLabel", {

	Size = UDim2.fromOffset(250, 25),

	Position = UDim2.fromOffset(25, 390),

	BackgroundTransparency = 1,

	Text = "Feito por Rafael.wz",

	TextColor3 =
		Color3.fromRGB(145, 145, 155),

	TextSize = 13,

	Font = Enum.Font.Gotham,

	TextXAlignment =
		Enum.TextXAlignment.Left,

	ZIndex = 5,

	Parent = Main
})

--==================================================
-- PAINEL DE CONFIGURAÇÕES
--==================================================

local Settings = New("Frame", {

	Name = "Settings",

	Size = UDim2.fromOffset(390, 430),

	Position = UDim2.new(1, 0, 0, 0),

	BackgroundColor3 =
		Color3.fromRGB(17, 16, 22),

	BorderSizePixel = 0,

	Visible = false,

	ZIndex = 20,

	Parent = Main
})

Corner(Settings, 14)

New("TextLabel", {

	Size = UDim2.new(1, -70, 0, 50),

	Position = UDim2.fromOffset(20, 15),

	BackgroundTransparency = 1,

	Text = "CONFIGURAÇÕES",

	TextColor3 = Color3.new(1, 1, 1),

	TextSize = 22,

	Font = Enum.Font.GothamBold,

	TextXAlignment =
		Enum.TextXAlignment.Left,

	ZIndex = 21,

	Parent = Settings
})

local CloseSettings = New("TextButton", {

	Size = UDim2.fromOffset(42, 42),

	Position = UDim2.new(1, -55, 0, 18),

	BackgroundColor3 =
		Color3.fromRGB(35, 33, 42),

	BorderSizePixel = 0,

	Text = "×",

	TextColor3 = Color3.new(1, 1, 1),

	TextSize = 28,

	Font = Enum.Font.Gotham,

	AutoButtonColor = false,

	ZIndex = 21,

	Parent = Settings
})

Corner(CloseSettings, 10)

--==================================================
-- SCROLL CONFIGURAÇÕES
--==================================================

local Scroll = New("ScrollingFrame", {

	Size = UDim2.new(1, -20, 1, -80),

	Position = UDim2.fromOffset(10, 70),

	BackgroundTransparency = 1,

	BorderSizePixel = 0,

	ScrollBarThickness = 4,

	ScrollBarImageColor3 = ThemeColor,

	CanvasSize = UDim2.fromOffset(0, 700),

	ZIndex = 21,

	Parent = Settings
})

--==================================================
-- CRIADOR DE OPÇÕES
--==================================================

local function CreateOption(name, description, y)

	local Button = New("TextButton", {

		Size = UDim2.new(1, -10, 0, 65),

		Position = UDim2.fromOffset(5, y),

		BackgroundColor3 =
			Color3.fromRGB(30, 29, 37),

		BorderSizePixel = 0,

		Text = "",

		AutoButtonColor = false,

		ZIndex = 22,

		Parent = Scroll
	})

	Corner(Button, 10)

	New("TextLabel", {

		Size = UDim2.new(1, -60, 0, 27),

		Position = UDim2.fromOffset(15, 8),

		BackgroundTransparency = 1,

		Text = name,

		TextColor3 =
			Color3.new(1, 1, 1),

		TextSize = 15,

		Font = Enum.Font.GothamBold,

		TextXAlignment =
			Enum.TextXAlignment.Left,

		ZIndex = 23,

		Parent = Button
	})

	New("TextLabel", {

		Size = UDim2.new(1, -60, 0, 22),

		Position = UDim2.fromOffset(15, 34),

		BackgroundTransparency = 1,

		Text = description,

		TextColor3 =
			Color3.fromRGB(140, 140, 150),

		TextSize = 12,

		Font = Enum.Font.Gotham,

		TextXAlignment =
			Enum.TextXAlignment.Left,

		ZIndex = 23,

		Parent = Button
	})

	New("TextLabel", {

		Size = UDim2.fromOffset(30, 30),

		Position = UDim2.new(
			1,
			-40,
			0.5,
			-15
		),

		BackgroundTransparency = 1,

		Text = "›",

		TextColor3 = ThemeColor,

		TextSize = 27,

		Font = Enum.Font.GothamBold,

		ZIndex = 23,

		Parent = Button
	})

	return Button

end

--==================================================
-- COR
--==================================================

local ColorOption = CreateOption(
	"🎨  Personalizar cor",
	"Altere a cor principal do menu",
	5
)

--==================================================
-- FUNDO
--==================================================

local BackgroundOption = CreateOption(
	"🖼  Plano de fundo",
	"Use uma imagem do Roblox como fundo",
	80
)

New("TextLabel", {

	Size = UDim2.new(1, -30, 0, 22),

	Position = UDim2.fromOffset(20, 150),

	BackgroundTransparency = 1,

	Text = "ID da imagem do Roblox",

	TextColor3 =
		Color3.fromRGB(180, 180, 190),

	TextSize = 12,

	Font = Enum.Font.Gotham,

	TextXAlignment =
		Enum.TextXAlignment.Left,

	ZIndex = 23,

	Parent = Scroll
})

local BackgroundBox = New("TextBox", {

	Size = UDim2.new(1, -120, 0, 38),

	Position = UDim2.fromOffset(20, 175),

	BackgroundColor3 =
		Color3.fromRGB(25, 24, 31),

	BorderSizePixel = 0,

	PlaceholderText =
		"rbxassetid://123456789",

	Text = "",

	TextColor3 = Color3.new(1, 1, 1),

	PlaceholderColor3 =
		Color3.fromRGB(100, 100, 110),

	TextSize = 12,

	Font = Enum.Font.Gotham,

	ClearTextOnFocus = false,

	ZIndex = 23,

	Parent = Scroll
})

Corner(BackgroundBox, 8)

local ApplyBackground = New("TextButton", {

	Size = UDim2.fromOffset(80, 38),

	Position = UDim2.new(
		1,
		-95,
		0,
		175
	),

	BackgroundColor3 = ThemeColor,

	BorderSizePixel = 0,

	Text = "Aplicar",

	TextColor3 = Color3.new(1, 1, 1),

	TextSize = 12,

	Font = Enum.Font.GothamBold,

	AutoButtonColor = false,

	ZIndex = 23,

	Parent = Scroll
})

Corner(ApplyBackground, 8)

ApplyBackground.MouseButton1Click:Connect(function()

	local id = BackgroundBox.Text

	if id == "" then
		return
	end

	if not string.find(
		id,
		"rbxassetid://",
		1,
		true
	) then

		id = "rbxassetid://" .. id

	end

	Background.Image = id

	Background.ImageTransparency = 0.45

end)

--==================================================
-- TRANSPARÊNCIA
--==================================================

New("TextLabel", {

	Size = UDim2.new(1, -100, 0, 25),

	Position = UDim2.fromOffset(20, 225),

	BackgroundTransparency = 1,

	Text = "👻  Transparência do menu",

	TextColor3 = Color3.new(1, 1, 1),

	TextSize = 15,

	Font = Enum.Font.GothamBold,

	TextXAlignment =
		Enum.TextXAlignment.Left,

	ZIndex = 23,

	Parent = Scroll
})

local TransparencyValue = New("TextLabel", {

	Size = UDim2.fromOffset(60, 25),

	Position = UDim2.new(
		1,
		-80,
		0,
		225
	),

	BackgroundTransparency = 1,

	Text = "5%",

	TextColor3 = ThemeColor,

	TextSize = 14,

	Font = Enum.Font.GothamBold,

	ZIndex = 23,

	Parent = Scroll
})

local Slider = New("Frame", {

	Size = UDim2.new(1, -40, 0, 6),

	Position = UDim2.fromOffset(20, 260),

	BackgroundColor3 =
		Color3.fromRGB(65, 63, 70),

	BorderSizePixel = 0,

	ZIndex = 23,

	Parent = Scroll
})

Corner(Slider, 5)

local SliderButton = New("TextButton", {

	Size = UDim2.fromOffset(18, 18),

	Position = UDim2.new(
		0.05,
		-9,
		0.5,
		-9
	),

	BackgroundColor3 = ThemeColor,

	BorderSizePixel = 0,

	Text = "",

	ZIndex = 24,

	Parent = Slider
})

Corner(SliderButton, 9)

local Dragging = false

local function SetTransparency(value)

	value = math.clamp(value, 0, 0.85)

	Main.BackgroundTransparency = value

	TransparencyValue.Text =
		math.floor(value * 100) .. "%"

end

local function UpdateSlider(mouseX)

	local startX =
		Slider.AbsolutePosition.X

	local width =
		Slider.AbsoluteSize.X

	local percent = math.clamp(
		(mouseX - startX) / width,
		0,
		1
	)

	SliderButton.Position =
		UDim2.new(
			percent,
			-9,
			0.5,
			-9
		)

	SetTransparency(percent * 0.85)

end

SliderButton.MouseButton1Down:Connect(function()

	Dragging = true

end)

Slider.InputBegan:Connect(function(input)

	if input.UserInputType ==
		Enum.UserInputType.MouseButton1 then

		UpdateSlider(input.Position.X)

	end

end)

UserInputService.InputChanged:Connect(function(input)

	if Dragging and
		input.UserInputType ==
		Enum.UserInputType.MouseMovement then

		UpdateSlider(input.Position.X)

	end

end)

UserInputService.InputEnded:Connect(function(input)

	if input.UserInputType ==
		Enum.UserInputType.MouseButton1 then

		Dragging = false

	end

end)

SetTransparency(0.05)

--==================================================
-- BORDA RGB
--==================================================

local RGBOption = CreateOption(
	"🌈  Borda RGB",
	"Ativa uma borda RGB animada no menu",
	310
)

RGBOption.MouseButton1Click:Connect(function()

	if RGBEnabled then

		StopRGB()

	else

		StartRGB()

	end

end)

--==================================================
-- RESTAURAR
--==================================================

local ResetSettings = CreateOption(
	"🔄  Restaurar configurações",
	"Volta o menu para as configurações padrão",
	385
)

ResetSettings.MouseButton1Click:Connect(function()

	ThemeColor = DefaultColor

	Line.BackgroundColor3 =
		ThemeColor

	RealmText.TextColor3 =
		ThemeColor

	MenuSettings.TextColor3 =
		ThemeColor

	ButtonStroke.Color =
		ThemeColor

	Scroll.ScrollBarImageColor3 =
		ThemeColor

	OptionsFrame.ScrollBarImageColor3 =
		ThemeColor

	TransparencyValue.TextColor3 =
		ThemeColor

	SliderButton.BackgroundColor3 =
		ThemeColor

	ApplyBackground.BackgroundColor3 =
		ThemeColor

	Background.Image = ""

	BackgroundBox.Text = ""

	Background.ImageTransparency = 0.82

	SetTransparency(0.05)

	SliderButton.Position =
		UDim2.new(
			0.05,
			-9,
			0.5,
			-9
		)

	if RGBEnabled then
		StopRGB()
	end

	for _, option in ipairs(
		OptionsFrame:GetChildren()
	) do

		if option:IsA("Frame") then

			local play =
				option:FindFirstChild("PlayButton")

			if play then

				play.BackgroundColor3 =
					ThemeColor

			end

		end

	end

end)

--==================================================
-- ASSISTENTE
--==================================================

local AssistantOption = CreateOption(
	"🤖  Assistente",
	"Ajuda com dúvidas sobre como usar o menu",
	460
)

AssistantOption.MouseButton1Click:Connect(function()

	local Assistant = New("Frame", {

		Size = UDim2.fromOffset(430, 330),

		Position = UDim2.fromScale(
			0.5,
			0.5
		),

		AnchorPoint =
			Vector2.new(0.5, 0.5),

		BackgroundColor3 =
			Color3.fromRGB(18, 17, 23),

		BorderSizePixel = 0,

		ZIndex = 100,

		Parent = ScreenGui
	})

	Corner(Assistant, 14)

	local AssistantStroke =
		Instance.new("UIStroke")

	AssistantStroke.Color =
		ThemeColor

	AssistantStroke.Thickness = 2

	AssistantStroke.Parent =
		Assistant

	New("TextLabel", {

		Size = UDim2.new(1, -60, 0, 45),

		Position = UDim2.fromOffset(20, 15),

		BackgroundTransparency = 1,

		Text = "🤖 Assistente Realm",

		TextColor3 =
			Color3.new(1, 1, 1),

		TextSize = 20,

		Font = Enum.Font.GothamBold,

		TextXAlignment =
			Enum.TextXAlignment.Left,

		ZIndex = 101,

		Parent = Assistant
	})

	local CloseAssistant = New("TextButton", {

		Size = UDim2.fromOffset(35, 35),

		Position = UDim2.new(
			1,
			-50,
			0,
			15
		),

		BackgroundColor3 =
			Color3.fromRGB(35, 33, 42),

		BorderSizePixel = 0,

		Text = "×",

		TextColor3 =
			Color3.new(1, 1, 1),

		TextSize = 23,

		Font = Enum.Font.GothamBold,

		ZIndex = 101,

		Parent = Assistant
	})

	Corner(CloseAssistant, 8)

	CloseAssistant.MouseButton1Click:Connect(function()

		Assistant:Destroy()

	end)

	New("TextLabel", {

		Size = UDim2.new(1, -40, 0, 45),

		Position = UDim2.fromOffset(20, 65),

		BackgroundTransparency = 1,

		Text =
			"Pergunte algo sobre como usar o menu.",

		TextColor3 =
			Color3.fromRGB(160, 160, 170),

		TextSize = 13,

		Font = Enum.Font.Gotham,

		TextXAlignment =
			Enum.TextXAlignment.Left,

		ZIndex = 101,

		Parent = Assistant
	})

	local Question = New("TextBox", {

		Size = UDim2.new(1, -40, 0, 42),

		Position = UDim2.fromOffset(20, 115),

		BackgroundColor3 =
			Color3.fromRGB(28, 27, 35),

		BorderSizePixel = 0,

		PlaceholderText =
			"Digite sua pergunta...",

		Text = "",

		TextColor3 =
			Color3.new(1, 1, 1),

		PlaceholderColor3 =
			Color3.fromRGB(110, 110, 120),

		TextSize = 13,

		Font = Enum.Font.Gotham,

		ClearTextOnFocus = false,

		ZIndex = 101,

		Parent = Assistant
	})

	Corner(Question, 9)

	local Answer = New("TextLabel", {

		Size = UDim2.new(1, -40, 0, 100),

		Position = UDim2.fromOffset(20, 175),

		BackgroundColor3 =
			Color3.fromRGB(25, 24, 31),

		BorderSizePixel = 0,

		Text =
			"Olá! Posso ajudar com as funções do menu.",

		TextColor3 =
			Color3.fromRGB(210, 210, 215),

		TextSize = 13,

		Font = Enum.Font.Gotham,

		TextWrapped = true,

		TextXAlignment =
			Enum.TextXAlignment.Left,

		TextYAlignment =
			Enum.TextYAlignment.Top,

		ZIndex = 101,

		Parent = Assistant
	})

	Corner(Answer, 9)

	local Ask = New("TextButton", {

		Size = UDim2.fromOffset(100, 35),

		Position = UDim2.new(
			1,
			-120,
			1,
			-45
		),

		BackgroundColor3 =
			ThemeColor,

		BorderSizePixel = 0,

		Text = "Perguntar",

		TextColor3 =
			Color3.new(1, 1, 1),

		TextSize = 12,

		Font = Enum.Font.GothamBold,

		ZIndex = 101,

		Parent = Assistant
	})

	Corner(Ask, 8)

	local function GetAnswer(question)

		question =
			string.lower(question)

		if string.find(question, "cor") then

			return "Abra as configurações e escolha 'Personalizar cor'. Você pode escolher entre Roxo, Azul, Verde, Vermelho, Laranja e Rosa."

		elseif string.find(question, "fundo")
			or string.find(question, "imagem") then

			return "Em Configurações, use 'Plano de fundo'. Digite o ID da imagem do Roblox e clique em Aplicar."

		elseif string.find(question, "transpar") then

			return "Use o controle deslizante de Transparência para deixar o menu mais transparente ou mais sólido."

		elseif string.find(question, "rgb") then

			return "A opção Borda RGB ativa uma borda que muda de cor automaticamente. Clique novamente para desligar."

		elseif string.find(question, "abrir") then

			return "Clique na logo do Realm no canto superior direito para abrir ou fechar o menu."

		elseif string.find(question, "config") then

			return "Clique no botão ⚙ dentro do menu para abrir as configurações."

		elseif string.find(question, "delet")
			or string.find(question, "fechar") then

			return "A opção Deletar menu fecha e remove completamente o menu desta sessão."

		elseif string.find(question, "vers") then

			return "Esta é a versão de teste 0.0.1 do Realm Community Menu."

		elseif string.find(question, "opç")
			or string.find(question, "func") then

			return "As 10 opções ficam na tela principal. Cada uma possui um botão ▶ para executar sua função."

		else

			return "Ainda não sei responder essa pergunta. Tente perguntar sobre cor, fundo, transparência, RGB, configurações, opções ou como abrir o menu."

		end

	end

	Ask.MouseButton1Click:Connect(function()

		if Question.Text == "" then

			Answer.Text =
				"Digite uma pergunta primeiro."

			return

		end

		Answer.Text =
			GetAnswer(Question.Text)

	end)

end)

--==================================================
-- DELETAR MENU
--==================================================

local DeleteOption = CreateOption(
	"🗑  Deletar menu",
	"Fecha e remove o menu desta sessão",
	535
)

DeleteOption.MouseButton1Click:Connect(function()

	if RGBConnection then

		RGBConnection:Disconnect()

		RGBConnection = nil

	end

	ScreenGui:Destroy()

end)

--==================================================
-- TEXTO DA VERSÃO
--==================================================

New("TextLabel", {

	Size = UDim2.new(1, -30, 0, 50),

	Position = UDim2.fromOffset(20, 610),

	BackgroundTransparency = 1,

	Text =
		"Realm Community Menu\nVersão 0.0.1 • Versão de teste",

	TextColor3 =
		Color3.fromRGB(110, 110, 120),

	TextSize = 11,

	Font = Enum.Font.Gotham,

	TextWrapped = true,

	TextXAlignment =
		Enum.TextXAlignment.Center,

	ZIndex = 23,

	Parent = Scroll
})

--==================================================
-- PAINEL DE CORES
--==================================================

ColorOption.MouseButton1Click:Connect(function()

	local ColorPanel = New("Frame", {

		Size = UDim2.fromOffset(320, 285),

		Position = UDim2.fromScale(
			0.5,
			0.5
		),

		AnchorPoint =
			Vector2.new(0.5, 0.5),

		BackgroundColor3 =
			Color3.fromRGB(20, 19, 25),

		BorderSizePixel = 0,

		ZIndex = 40,

		Parent = ScreenGui
	})

	Corner(ColorPanel, 14)

	local ColorStroke =
		Instance.new("UIStroke")

	ColorStroke.Color =
		ThemeColor

	ColorStroke.Thickness = 2

	ColorStroke.Parent =
		ColorPanel

	New("TextLabel", {

		Size = UDim2.new(1, -30, 0, 40),

		Position = UDim2.fromOffset(15, 15),

		BackgroundTransparency = 1,

		Text = "Escolha uma cor",

		TextColor3 =
			Color3.new(1, 1, 1),

		TextSize = 20,

		Font = Enum.Font.GothamBold,

		ZIndex = 41,

		Parent = ColorPanel
	})

	local names = {
		"Roxo",
		"Azul",
		"Verde",
		"Vermelho",
		"Laranja",
		"Rosa"
	}

	for i, name in ipairs(names) do

		local color = Themes[name]

		local row =
			math.floor((i - 1) / 2)

		local column =
			(i - 1) % 2

		local Button = New("TextButton", {

			Size = UDim2.fromOffset(
				125,
				42
			),

			Position = UDim2.fromOffset(
				20 + column * 140,
				65 + row * 52
			),

			BackgroundColor3 = color,

			BorderSizePixel = 0,

			Text = name,

			TextColor3 =
				Color3.new(1, 1, 1),

			TextSize = 13,

			Font = Enum.Font.GothamBold,

			AutoButtonColor = false,

			ZIndex = 41,

			Parent = ColorPanel
		})

		Corner(Button, 9)

		Button.MouseButton1Click:Connect(function()

			ThemeColor = color

			Line.BackgroundColor3 =
				ThemeColor

			RealmText.TextColor3 =
				ThemeColor

			MenuSettings.TextColor3 =
				ThemeColor

			ButtonStroke.Color =
				ThemeColor

			Scroll.ScrollBarImageColor3 =
				ThemeColor

			OptionsFrame.ScrollBarImageColor3 =
				ThemeColor

			TransparencyValue.TextColor3 =
				ThemeColor

			SliderButton.BackgroundColor3 =
				ThemeColor

			ApplyBackground.BackgroundColor3 =
				ThemeColor

			ColorStroke.Color =
				ThemeColor

			if not RGBEnabled then

				RGBStroke.Color =
					ThemeColor

			end

			for _, option in ipairs(
				OptionsFrame:GetChildren()
			) do

				if option:IsA("Frame") then

					local play =
						option:FindFirstChild(
							"PlayButton"
						)

					if play then

						play.BackgroundColor3 =
							ThemeColor

					end

				end

			end

			ColorPanel:Destroy()

		end)

	end

end)

--==================================================
-- ABRIR CONFIGURAÇÕES
--==================================================

local function OpenSettings()

	Settings.Visible = true

	Settings.Position =
		UDim2.new(1, 0, 0, 0)

	Tween(
		Settings,
		{
			Position =
				UDim2.new(1, -390, 0, 0)
		},
		0.3
	):Play()

end

--==================================================
-- FECHAR CONFIGURAÇÕES
--==================================================

local function CloseSettingsPanel()

	Tween(
		Settings,
		{
			Position =
				UDim2.new(1, 0, 0, 0)
		},
		0.3
	):Play()

	task.delay(0.3, function()

		if Settings then

			Settings.Visible = false

		end

	end)

end

--==================================================
-- ABRIR / FECHAR MENU
--==================================================

SettingsButton.MouseButton1Click:Connect(function()

	Main.Visible = not Main.Visible

end)

--==================================================
-- ABRIR CONFIGURAÇÕES
--==================================================

MenuSettings.MouseButton1Click:Connect(function()

	OpenSettings()

end)

--==================================================
-- FECHAR CONFIGURAÇÕES
--==================================================

CloseSettings.MouseButton1Click:Connect(function()

	CloseSettingsPanel()

end)

--==================================================
-- FIM DO REALM COMMUNITY MENU
--==================================================
