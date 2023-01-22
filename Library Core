local UserInputService = game:GetService("UserInputService")
local ms = game.Players.LocalPlayer:GetMouse()

local TweenService = game:GetService("TweenService")
local Library = {}

local function fade(Object,col,Delay)
    local ToTween = Object
    local tweenInfo = TweenInfo.new(Delay,Enum.EasingStyle.Quad,Enum.EasingDirection.Out,0,false,0)
    local Tweener = TweenService:Create(ToTween,tweenInfo,{BackgroundTransparency = col})
    Tweener:Play()
end

local function textfade(Object,col,Delay)
    local ToTween = Object
    local tweenInfo = TweenInfo.new(Delay,Enum.EasingStyle.Quad,Enum.EasingDirection.Out,0,false,0)
    local Tweener = TweenService:Create(ToTween,tweenInfo,{TextTransparency = col})
    Tweener:Play()
end

local function color(Object,R,G,B,Delay)
    local ToTween = Object
    local tweenInfo = TweenInfo.new(Delay,Enum.EasingStyle.Quart,Enum.EasingDirection.InOut,0,false,0)
    local Tweener = TweenService:Create(ToTween,tweenInfo,{ImageColor3 = Color3.fromRGB(R,G,B)})
    Tweener:Play()
end

local function bccolor(Object,R,G,B,Delay)
    local ToTween = Object
    local tweenInfo = TweenInfo.new(Delay,Enum.EasingStyle.Quart,Enum.EasingDirection.InOut,0,false,0)
    local Tweener = TweenService:Create(ToTween,tweenInfo,{BackgroundColor3 = Color3.fromRGB(R,G,B)})
    Tweener:Play()
end

local function rotate(Object,Deg,Delay)
    local ToTween = Object
    local tweenInfo = TweenInfo.new(Delay,Enum.EasingStyle.Quart,Enum.EasingDirection.InOut,0,false,0)
    local Tweener = TweenService:Create(ToTween,tweenInfo,{Rotation = Deg})
    Tweener:Play()
end

for i,v in next,game.CoreGui:GetChildren() do
    if v.Name == "uilib" then
        v:Destroy()
    end
end



local LoaderLib = {};
local TweenService = game:GetService("TweenService");

function Library:Loader(HubText,CreditsText,CommentText)


local Loader = Instance.new("ScreenGui")
local Zone = Instance.new("Frame")
local Main = Instance.new("Frame")
local UIGradient = Instance.new("UIGradient")
local HubName = Instance.new("TextLabel")
local UIGradient_2 = Instance.new("UIGradient")
local Credits = Instance.new("TextLabel")
local UIGradient_3 = Instance.new("UIGradient")
local welcomeLabel = Instance.new("TextLabel")
local UIGradient_4 = Instance.new("UIGradient")
local Backgroundimg = Instance.new("ImageLabel")
local UICorner = Instance.new("UICorner")
local LogoImage = Instance.new("ImageLabel")
local UICorner_2 = Instance.new("UICorner")



Loader.Name = "Loader"
Loader.Parent = game.CoreGui
Loader.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Zone.Name = "Zone"
Zone.Parent = Loader
Zone.AnchorPoint = Vector2.new(0.5, 0.5)
Zone.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Zone.BackgroundTransparency = 1.000
Zone.BorderSizePixel = 0
Zone.ClipsDescendants = true
Zone.Position = UDim2.new(0.5, 0, 0.5, 0)
Zone.Size = UDim2.new(0, 550, 0, 350)

Main.Name = "Main"
Main.Parent = Zone
Main.AnchorPoint = Vector2.new(0.5, 0.5)
Main.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Main.BorderSizePixel = 0
Main.ClipsDescendants = true
Main.Position = UDim2.new(0.5, 0, 0.5, 0)
Main.Size = UDim2.new(0, 0, 0, 0)

UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(170, 255, 255)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(211, 255, 198))}
UIGradient.Parent = Main

HubName.Name = "HubName"
HubName.Parent = Main
HubName.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
HubName.BackgroundTransparency = 1.000
HubName.BorderSizePixel = 0
HubName.Position = UDim2.new(0.0345454589, 0, 0.0457142964, 0)
HubName.Size = UDim2.new(0, 183, 0, 47)
HubName.Font = Enum.Font.Kalam
HubName.Text = HubText
HubName.TextColor3 = Color3.fromRGB(145, 145, 145)
HubName.TextSize = 50.000
HubName.TextXAlignment = Enum.TextXAlignment.Left

UIGradient_2.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(170, 255, 255)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(211, 255, 198))}
UIGradient_2.Parent = HubName

Credits.Name = "Credits"
Credits.Parent = Main
Credits.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Credits.BackgroundTransparency = 1.000
Credits.BorderSizePixel = 0
Credits.Position = UDim2.new(0.0345454551, 0, 0.151428565, 0)
Credits.Size = UDim2.new(0, 503, 0, 47)
Credits.Font = Enum.Font.Kalam
Credits.Text = CreditsText
Credits.TextColor3 = Color3.fromRGB(109, 109, 109)
Credits.TextSize = 21.000
Credits.TextXAlignment = Enum.TextXAlignment.Left

UIGradient_3.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(170, 255, 255)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(211, 255, 198))}
UIGradient_3.Parent = Credits

welcomeLabel.Name = "welcomeLabel"
welcomeLabel.Parent = Main
welcomeLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
welcomeLabel.BackgroundTransparency = 1.000
welcomeLabel.BorderSizePixel = 0
welcomeLabel.Position = UDim2.new(0.367272735, 0, 0.788571417, 0)
welcomeLabel.Size = UDim2.new(0, 152, 0, 68)
welcomeLabel.Font = Enum.Font.Kalam
welcomeLabel.Text = CommentText
welcomeLabel.TextColor3 = Color3.fromRGB(115, 115, 115)
welcomeLabel.TextSize = 50.000

UIGradient_4.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(170, 255, 255)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(211, 255, 198))}
UIGradient_4.Parent = welcomeLabel

Backgroundimg.Name = "Backgroundimg"
Backgroundimg.Parent = Main
Backgroundimg.AnchorPoint = Vector2.new(0.5, 0.5)
Backgroundimg.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Backgroundimg.BackgroundTransparency = 1.000
Backgroundimg.BorderSizePixel = 0
Backgroundimg.Position = UDim2.new(0.5, 0, 0.49999997, 0)
Backgroundimg.Size = UDim2.new(1, 0, 1, 0)
Backgroundimg.Image = "http://www.roblox.com/asset/?id=1771082037"
Backgroundimg.ImageTransparency = 0.870

UICorner.CornerRadius = UDim.new(0, 10)
UICorner.Parent = Backgroundimg

LogoImage.Name = "LogoImage"
LogoImage.Parent = Main
LogoImage.AnchorPoint = Vector2.new(0.5, 0.5)
LogoImage.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LogoImage.BackgroundTransparency = 1.000
LogoImage.BorderSizePixel = 0
LogoImage.Position = UDim2.new(0.405999988, 0, 0, 35)
LogoImage.Size = UDim2.new(0.0781818405, 0, 0.122857153, 0)
LogoImage.Image = "http://www.roblox.com/asset/?id=9287155123"
LogoImage.ImageColor3 = Color3.fromRGB(167, 255, 208)
LogoImage.ScaleType = Enum.ScaleType.Fit

UICorner_2.CornerRadius = UDim.new(0, 10)
UICorner_2.Parent = Main


-- Blur

local Blur = Instance.new("BlurEffect");
Blur.Parent = game:GetService("Lighting");
Blur.Size = 0

spawn(function()
        repeat wait() until game:IsLoaded();
	Main:TweenSize(UDim2.new(1,0,1,0),"Out","Quart",0.4,true,nil);
	TweenService:Create(Blur,TweenInfo.new(.4),{Size = 24}):Play();
	wait(2.5)
	Main:TweenSize(UDim2.new(0,0,0,0),"In","Quart",0.4,true,nil);
	TweenService:Create(Blur,TweenInfo.new(.4),{Size = 0}):Play();
	wait(0.6)
	Loader:Destroy() ; Blur:Destroy() ;
	end)
	return Main
end


local tabs = -1


function Library:Window(text,keycode)
    local uilib = Instance.new("ScreenGui")
    local drug = Instance.new("Frame")
    local main = Instance.new("Frame")
    local ins = Instance.new("Frame")
    local line = Instance.new("Frame")
    local elems = Instance.new("Frame")
    local UIPageLayout = Instance.new("UIPageLayout")
    local line_2 = Instance.new("Frame")
    local tbs = Instance.new("ScrollingFrame")
    local tblayout = Instance.new("UIListLayout")
    local TextLabel = Instance.new("TextLabel")
    
    local inside = {}	
    
    --Properties:
    
    uilib.Name = "uilib"
    uilib.Parent = game.CoreGui
    uilib.ResetOnSpawn = false
    
    drug.Name = "drug"
    drug.Parent = uilib
    drug.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
    drug.BackgroundTransparency = 1.000
    drug.BorderSizePixel = 0
    drug.Position = UDim2.new(0.278640777, 0, 0.183838382, 0)
    drug.Size = UDim2.new(0, 591, 0, 36)
    
    main.Name = "main"
    main.Parent = drug
    main.BackgroundColor3 = Color3.fromRGB(22, 22, 22)
    main.BorderColor3 = Color3.fromRGB(85, 170, 127)
    main.ClipsDescendants = true
    main.Size = UDim2.new(0, 591, 0, 298)
    main.BorderSizePixel = 0
    
    local Rondfd = Instance.new("UICorner")
    Rondfd.CornerRadius = UDim.new(0, 3)
    Rondfd.Parent = main
    
    local Strokee = Instance.new("UIStroke")
    Strokee.Parent = main
    Strokee.ApplyStrokeMode = "Border"
    Strokee.Color = Color3.fromRGB(85, 170, 127)	
    Strokee.LineJoinMode = "Round"
    Strokee.Thickness = 2
    Strokee.Transparency = 0
    
    ins.Name = "ins"
    ins.Parent = main
    ins.AnchorPoint = Vector2.new(0.5, 0.5)
    ins.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
    ins.BackgroundTransparency = 1.000
    ins.BorderSizePixel = 0
    ins.Position = UDim2.new(0.5, 0, 0.5, 0)
    ins.Size = UDim2.new(0, 591, 0, 298)
    
    line.Name = "line"
    line.Parent = ins
    line.BackgroundColor3 = Color3.fromRGB(35, 120, 70)
    line.BorderSizePixel = 0
    line.Position = UDim2.new(0, 0, 0.114093959, 0)
    line.Size = UDim2.new(0, 591, 0, 2)
    
    elems.Name = "elems"
    elems.Parent = ins
    elems.BackgroundColor3 = Color3.fromRGB(27, 27, 27)
    elems.BorderColor3 = Color3.fromRGB(85, 170, 127)
    elems.BorderSizePixel = 0
    elems.Position = UDim2.new(0, 0, 0.120805368, 0)
    elems.Size = UDim2.new(0, 591, 0, 262)
    elems.ClipsDescendants = true
    
    UIPageLayout.Parent = elems
    UIPageLayout.FillDirection = Enum.FillDirection.Vertical
    UIPageLayout.SortOrder = Enum.SortOrder.LayoutOrder
    UIPageLayout.EasingStyle = Enum.EasingStyle.Quint
    UIPageLayout.GamepadInputEnabled = false
    UIPageLayout.ScrollWheelInputEnabled = false
    UIPageLayout.TouchInputEnabled = false
    UIPageLayout.TweenTime = 0.3
    
    line_2.Name = "line"
    line_2.Parent = ins
    line_2.BackgroundColor3 = Color3.fromRGB(35, 120, 70)
    line_2.BorderSizePixel = 0
    line_2.Position = UDim2.new(0.133671746, 0, 0, 0)
    line_2.Size = UDim2.new(0, 2, 0, 36)
    
    tbs.Name = "tbs"
    tbs.Parent = ins
    tbs.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
    tbs.BackgroundTransparency = 1.000
    tbs.BorderSizePixel = 0
    tbs.Position = UDim2.new(0.148900166, 0, 0, 0)
    tbs.Size = UDim2.new(0, 494, 0, 34)
    tbs.CanvasSize = UDim2.new(0,35,0,0)
    tbs.ScrollBarThickness = 2
    tbs.ScrollingDirection = Enum.ScrollingDirection.X
    tbs.ScrollBarImageColor3 = Color3.fromRGB(100,100,100)
    
    tblayout.Name = "tblayout"
    tblayout.Parent = tbs
    tblayout.FillDirection = Enum.FillDirection.Horizontal
    tblayout.SortOrder = Enum.SortOrder.LayoutOrder
    tblayout.VerticalAlignment = Enum.VerticalAlignment.Center
    tblayout.Padding = UDim.new(0, 4)
    
    TextLabel.Parent = ins
    TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
    TextLabel.BackgroundTransparency = 1.000
    TextLabel.BorderSizePixel = 0
    TextLabel.Position = UDim2.new(0.0270727575, 0, 0, 0)
    TextLabel.Size = UDim2.new(0, 63, 0, 34)
    TextLabel.Font = Enum.Font.Gotham
    TextLabel.Text = text
    TextLabel.TextColor3 = Color3.fromRGB(85, 170, 127)
    TextLabel.TextSize = 14.000
    TextLabel.TextWrapped = true
    TextLabel.TextXAlignment = Enum.TextXAlignment.Left
    
    -- Scripts:
    
    local toggle = true
    
    UserInputService.InputBegan:Connect(function(key,isTyping)
        if not isTyping and key.KeyCode == Enum.KeyCode[keycode] then
            if toggle then
                toggle = false
                main.BorderSizePixel = 0
                main:TweenSize(UDim2.new(0,591,0,0),"Out","Quad",0.15)
                wait(0.15)
                drug.Visible = false
            elseif not toggle then
                toggle = true
                main:TweenSize(UDim2.new(0,591,0,298),"Out","Quad",0.15)
                main.BorderSizePixel = 1 
                drug.Visible = true
            end
        end
    end)
    
    
    local dragging
    local dragInput
    local dragStart
    local startPos
    local off = Vector3.new(5,5,0)
    
    local function update(input)
        local delta = input.Position + off - dragStart
        drug:TweenPosition(UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X, startPos.Y.Scale, startPos.Y.Offset + delta.Y),"Out","Sine",0.1,true,nil)
    end
    
    drug.InputBegan:Connect(function(input)
        if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
            dragging = true
            dragStart = input.Position
            startPos = drug.Position + UDim2.new(0,10,0,10)
            
            input.Changed:Connect(function()
                if input.UserInputState == Enum.UserInputState.End then
                    dragging = false
                end
            end)
        end
    end)
        
    drug.InputChanged:Connect(function(input)
        if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
            dragInput = input
        end
    end)
        
    UserInputService.InputChanged:Connect(function(input)
        if input == dragInput and dragging then
            update(input)
        end
    end)
    
    
    function inside:Folder(textt)
    
        local tab = Instance.new("ScrollingFrame")
        local tabslayout = Instance.new("UIListLayout")
        local Frame = Instance.new("Frame")
        tabs = tabs + 1
        local tabnum = tabs
        tbs.CanvasSize = tbs.CanvasSize + UDim2.new(0.3,0,0,0)
        
        
        tab.Name = "tab"
        tab.Parent = elems
        tab.Active = true
        tab.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
        tab.BackgroundTransparency = 1.000
        tab.BorderSizePixel = 0
        tab.Size = UDim2.new(0, 591, 0, 262)
        tab.ScrollBarThickness = 3
        tab.CanvasSize = UDim2.new(0,0,0,30)
        
        tabslayout.Name = "tabslayout"
        tabslayout.Parent = tab
        tabslayout.HorizontalAlignment = Enum.HorizontalAlignment.Center
        tabslayout.SortOrder = Enum.SortOrder.LayoutOrder
        tabslayout.Padding = UDim.new(0, 4)
        
        Frame.Parent = tab
        Frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
        Frame.BackgroundTransparency = 1.000
        Frame.BorderSizePixel = 0
        
        --button code
        
        
        local tb = Instance.new("TextButton")
        local UICorner = Instance.new("UICorner")
        
        
        tb.Name = "tb"
        tb.Parent = tbs
        tb.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
        tb.BorderSizePixel = 0
        tb.Position = UDim2.new(0.148900166, 0, 0.0100671137, 0)
        tb.Size = UDim2.new(0, 175, 0, 27)
        tb.AutoButtonColor = false
        tb.Font = Enum.Font.Gotham
        tb.Text = textt
        tb.TextColor3 = Color3.fromRGB(63, 127, 94)
        tb.TextSize = 14.000
        
        UICorner.CornerRadius = UDim.new(0, 3)
        UICorner.Parent = tb
        
        -- Scripts:
        
        local ms = game.Players.LocalPlayer:GetMouse()
        
        
        
        tb.MouseEnter:Connect(function()
            fade(tb,0.7,0.3)
        end)
        
        tb.MouseLeave:Connect(function()
            fade(tb,0,0.3)
        end)
        
        
        
        tb.MouseButton1Click:Connect(function()
            UIPageLayout:JumpToIndex(tabnum)
        end)
        
        
        local InsideTab = {}
        
        
        function InsideTab:Button(text,callback)
        
            local button = Instance.new("TextButton")
            local UICorner = Instance.new("UICorner")
            
            tab.CanvasSize = tab.CanvasSize + UDim2.new(0,0,0,38)
            --Properties:
            
            button.Name = "button"
            button.Parent = tab
            button.BackgroundColor3 = Color3.fromRGB(36, 36, 36)
            button.BorderColor3 = Color3.fromRGB(27, 42, 53)
            button.BorderSizePixel = 0
            button.ClipsDescendants = true
            button.Size = UDim2.new(0, 570, 0, 34)
            button.ZIndex = 2
            button.AutoButtonColor = false
            button.Font = Enum.Font.Gotham
            button.Text = text
            button.TextColor3 = Color3.fromRGB(255,255,255)
            button.TextSize = 16.000
            
            UICorner.Parent = button
            
            -- Scripts:
            
            
            
            local riv = Instance.new("Frame",button)
            riv.BorderSizePixel = 0
            local bllf = Instance.new("UICorner",riv)
            bllf.CornerRadius = UDim.new(0,100)
            local pressed = false
            local time = 3
            local function effect()
                local ef = riv:Clone()
                local fe = bllf:Clone()
                local efes = {
                    "ef",
                    "fe"
                    
                }
                ef.Parent = button
                ef.AnchorPoint = Vector2.new(0.5,0.5)
                ef.BackgroundColor3 = Color3.fromRGB(85, 170, 127)
                ef.BackgroundTransparency = 0
                fe.Parent = ef
                ef.Position = UDim2.new(0,ms.X-ef.AbsolutePosition.X,0,ms.Y-ef.AbsolutePosition.Y)
                
                ef:TweenPosition(UDim2.new(0.5,0,0.5,0),"InOut","Quad",time,true,nil)
                ef:TweenSize(UDim2.new(1,0,0,475),"InOut","Quad",time,true,nil)
                repeat wait() until not pressed
                ef:TweenPosition(UDim2.new(0.5,0,0.5,0),"InOut","Quad",time,true,nil)
                ef:TweenSize(UDim2.new(1,0,0,475),"InOut","Quad",time,true,nil)
                fade(ef,1,0.5)
                wait(0.7) do
                    ef:Destroy() ; fe:Destroy()
                end
            end
            
            
            button.MouseButton1Down:Connect(function()
                if not pressed then
                    
                    pressed = true
                    time = 3
                    effect()
                end
            end)
            
            button.MouseButton1Up:Connect(function()
                pressed = false
                time = 0.3
            end)
            
            button.MouseEnter:Connect(function()
                fade(button,0.4,0.3)
            end)
            
            
            button.MouseLeave:Connect(function()
                fade(button,0,0.3)
                pressed = false
                time = 0.3
            end)
            
            button.MouseButton1Click:Connect(function(state) spawn(function() callback(state) end) end)
            
        end
    
    
        function InsideTab:Toggle(text,callback,state)
            local checkbox = Instance.new("TextLabel")
            local TextButton = Instance.new("TextButton")
            local circle = Instance.new("ImageLabel")
            local enable = Instance.new("ImageLabel")
            local disable = Instance.new("ImageLabel")
            local Sample = Instance.new("ImageLabel")
            local UICorner = Instance.new("UICorner")
            local Frame = Instance.new("Frame")
            local UICorner = Instance.new("UICorner")
            
            tab.CanvasSize = tab.CanvasSize + UDim2.new(0,0,0,38)
            --Properties:
            
            checkbox.Name = "checkbox"
            checkbox.Parent = tab
            checkbox.BackgroundColor3 = Color3.fromRGB(36, 36, 36)
            checkbox.BorderSizePixel = 0
            checkbox.ClipsDescendants = true
            checkbox.Position = UDim2.new(0.0536685176, 0, 0.221910119, 0)
            checkbox.Size = UDim2.new(0, 570, 0, 34)
            checkbox.ZIndex = 2
            checkbox.Font = Enum.Font.Gotham
            checkbox.Text = "   " .. text
            checkbox.TextColor3 = Color3.fromRGB(255,255,255)
            checkbox.TextSize = 16.000
            checkbox.TextWrapped = true
            checkbox.TextXAlignment = Enum.TextXAlignment.Left
            
            TextButton.Parent = checkbox
            TextButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
            TextButton.BackgroundTransparency = 1.000
            TextButton.BorderSizePixel = 0
            TextButton.Size = UDim2.new(0, 570, 0, 34)
            TextButton.ZIndex = 2
            TextButton.Font = Enum.Font.SourceSans
            TextButton.Text = ""
            TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
            TextButton.TextSize = 14.000
            
            circle.Name = "circle"
            circle.Parent = TextButton
            circle.AnchorPoint = Vector2.new(0, 0.5)
            circle.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
            circle.BackgroundTransparency = 1.000
            circle.BorderSizePixel = 0
            circle.Position = UDim2.new(0.939999998, 0, 0.5, 0)
            circle.Size = UDim2.new(0, 30, 0, 30)
            circle.ZIndex = 2
            circle.Image = "rbxassetid://3926305904"
            circle.ImageColor3 = Color3.fromRGB(255, 60, 63)
            circle.ImageRectOffset = Vector2.new(324, 964)
            circle.ImageRectSize = Vector2.new(36, 36)
            circle.ImageTransparency = 0
            
            
            local Framee = Instance.new("Frame")
            local UICornerrr = Instance.new("UICorner")
            
            Framee.Parent = circle
            Framee.AnchorPoint = Vector2.new(0.5, 0.5)
            Framee.BackgroundColor3 = Color3.fromRGB(36, 36, 36)
            Framee.Position = UDim2.new(0.5, 0, 0.5, 0)
            Framee.Size = UDim2.new(0, 24, 0, 24)
            Framee.ZIndex = 2
            Framee.BorderSizePixel = 0
            
            UICornerrr.CornerRadius = UDim.new(0, 1000)
            UICornerrr.Parent = Framee
            
            enable.Name = "enable"
            enable.Parent = circle
            enable.AnchorPoint = Vector2.new(0.5, 0.5)
            enable.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
            enable.BackgroundTransparency = 1.000
            enable.BorderSizePixel = 0
            enable.Position = UDim2.new(0.5, 0, 0.5, 0)
            enable.ZIndex = 3
            enable.Image = "rbxassetid://3926305904"
            enable.ImageColor3 = Color3.fromRGB(85, 170, 127)
            enable.ImageRectOffset = Vector2.new(312, 4)
            enable.ImageRectSize = Vector2.new(24, 24)
            
            disable.Name = "disable"
            disable.Parent = circle
            disable.AnchorPoint = Vector2.new(0.5, 0.5)
            disable.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
            disable.BackgroundTransparency = 1.000
            disable.BorderSizePixel = 0
            disable.Position = UDim2.new(0.5, 0, 0.5, 0)
            disable.Size = UDim2.new(0, 20, 0, 20)
            disable.ZIndex = 3
            disable.Image = "rbxassetid://3926305904"
            disable.ImageColor3 = Color3.fromRGB(255, 60, 63)
            disable.ImageRectOffset = Vector2.new(284, 4)
            disable.ImageRectSize = Vector2.new(24, 24)
            
            Sample.Name = "Sample"
            Sample.Parent = checkbox
            Sample.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
            Sample.BackgroundTransparency = 1.000
            Sample.ZIndex = 12
            Sample.Image = "http://www.roblox.com/asset/?id=4560909609"
            Sample.ImageColor3 = Color3.fromRGB(115, 115, 115)
            Sample.ImageTransparency = 0.600
            
            UICorner.Parent = checkbox
            
            -- Scripts:
            
            local enabled = false
            
            if state then
                enabled = true
                enable:TweenSize(UDim2.new(0,20,0,20),"Out","Quad",0.1)
                disable:TweenSize(UDim2.new(0,0,0,0),"Out","Quad",0.1)
                color(circle,85, 170, 127,0.1)
                spawn(function() callback(enabled) end)
            end
            
            TextButton.MouseButton1Click:Connect(function()
                if not enabled then
                    enabled = true
                    enable:TweenSize(UDim2.new(0,20,0,20),"Out","Quad",0.1)
                    disable:TweenSize(UDim2.new(0,0,0,0),"Out","Quad",0.1)
                    color(circle,85, 170, 127,0.1)
                    spawn(function() callback(enabled) end)
                elseif enabled then
                    enabled = false
                    disable:TweenSize(UDim2.new(0,20,0,20),"Out","Quad",0.1)
                    enable:TweenSize(UDim2.new(0,0,0,0),"Out","Quad",0.1)
                    color(circle,255, 60, 63,0.1)
                    spawn(function() callback(enabled) end)
                end
            end)
            
            
            local riv = Instance.new("Frame",TextButton)
            riv.BorderSizePixel = 0
            local bllf = Instance.new("UICorner",riv)
            bllf.CornerRadius = UDim.new(0,100)
            local pressed = false
            local time = 3
            
            local function effect()
                local ef = riv:Clone()
                local fe = bllf:Clone()
                local efes = {
                    "ef",
                    "fe"
                }
                ef.Parent = TextButton
                ef.AnchorPoint = Vector2.new(0.5,0.5)
                ef.BackgroundColor3 = Color3.fromRGB(85, 170, 127)
                ef.BackgroundTransparency = 0
                fe.Parent = ef
                ef.Position = UDim2.new(0,ms.X-ef.AbsolutePosition.X,0,ms.Y-ef.AbsolutePosition.Y)
                
                ef:TweenPosition(UDim2.new(0.5,0,0.5,0),"InOut","Quad",time,true,nil)
                ef:TweenSize(UDim2.new(1,0,0,475),"InOut","Quad",time,true,nil)
                repeat wait() until not pressed
                ef:TweenPosition(UDim2.new(0.5,0,0.5,0),"InOut","Quad",time,true,nil)
                ef:TweenSize(UDim2.new(1,0,0,475),"InOut","Quad",time,true,nil)
                fade(ef,1,0.5)
                wait(0.7)
                ef:Destroy() ; fe:Destroy()
            end
            
            
            TextButton.MouseButton1Down:Connect(function()
                if not pressed then
                    pressed = true
                    time = 3
                    effect()
                end
            end)
            
            TextButton.MouseButton1Up:Connect(function()
                pressed = false
                time = 0.3
            end)
            
            TextButton.MouseEnter:Connect(function()
                fade(checkbox,0.4,0.3)
            end)
            
            
            TextButton.MouseLeave:Connect(function()
                fade(checkbox,0,0.3)
                pressed = false
                time = 0.3
            end)
            
            
            
        end
        
        function InsideTab:Slider(text,min,max,suffix,callback,preval)
        
            local Range = Instance.new("Frame")
            local SliderButton = Instance.new("TextButton")
            local SliderInner = Instance.new("Frame")
            local UICorner_5 = Instance.new("UICorner")
            local UICorner_2 = Instance.new("UICorner")
            local TextLabel = Instance.new("TextLabel")
            local label = Instance.new("TextLabel")
            local Frame = Instance.new("Frame")
            local UICorner_3 = Instance.new("UICorner")
            local UICorner_4 = Instance.new("UICorner")
            
            --Properties:
            
            Range.Name = "Range"
            Range.Parent = tab
            Range.Active = true
            Range.BackgroundColor3 = Color3.fromRGB(36, 36, 36)
            Range.BorderSizePixel = 0
            Range.ClipsDescendants = true
            Range.Position = UDim2.new(0.597087383, 0, 0.551999986, 0)
            Range.Size = UDim2.new(0, 570, 0, 34)
            
            SliderButton.Name = "SliderButton"
            SliderButton.Parent = Range
            SliderButton.AnchorPoint = Vector2.new(0, 0.5)
            SliderButton.BackgroundColor3 = Color3.fromRGB(68, 68, 68)
            SliderButton.BackgroundTransparency = 0.900
            SliderButton.BorderSizePixel = 0
            SliderButton.ClipsDescendants = true
            SliderButton.Position = UDim2.new(0, 0, 0.5, 0)
            SliderButton.Size = UDim2.new(0, 570, 0, 34)
            SliderButton.ZIndex = 2
            SliderButton.AutoButtonColor = false
            SliderButton.Font = Enum.Font.SourceSans
            SliderButton.Text = ""
            SliderButton.TextColor3 = Color3.fromRGB(0, 0, 0)
            SliderButton.TextSize = 14.000
            
            SliderInner.Name = "SliderInner"
            SliderInner.Parent = SliderButton
            SliderInner.BackgroundColor3 = Color3.fromRGB(85, 170, 127)
            SliderInner.BorderSizePixel = 0
            SliderInner.Size = UDim2.new(0, 0, 0, 34)
            SliderInner.ZIndex = 2
            
            UICorner_5.Parent = SliderInner
            
            UICorner_2.Parent = SliderButton
            
            TextLabel.Parent = Range
            TextLabel.AnchorPoint = Vector2.new(0, 0.5)
            TextLabel.BackgroundColor3 = Color3.fromRGB(59, 59, 59)
            TextLabel.BackgroundTransparency = 1.000
            TextLabel.BorderColor3 = Color3.fromRGB(255, 255, 255)
            TextLabel.BorderSizePixel = 0
            TextLabel.Position = UDim2.new(0.90, 0, 0.5, 0)
            TextLabel.Size = UDim2.new(0, 34, 0, 17)
            TextLabel.ZIndex = 2
            TextLabel.Font = Enum.Font.Gotham
            TextLabel.Text = (suffix .. "  ".. min)
            TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
            TextLabel.TextSize = 13.000
            TextLabel.TextXAlignment = Enum.TextXAlignment.Right
            
            label.Name = "label"
            label.Parent = Range
            label.AnchorPoint = Vector2.new(0.5, 0.5)
            label.BackgroundColor3 = Color3.fromRGB(49, 49, 49)
            label.BackgroundTransparency = 1.000
            label.BorderColor3 = Color3.fromRGB(143, 143, 143)
            label.Position = UDim2.new(0.5, 0, 0.5, 0)
            label.Size = UDim2.new(0, 104, 0, 22)
            label.ZIndex = 2
            label.Font = Enum.Font.Gotham
            label.Text = text
            label.TextColor3 = Color3.fromRGB(255, 255, 255)
            label.TextSize = 16.000
            
            Frame.Parent = Range
            Frame.BackgroundColor3 = Color3.fromRGB(36, 36, 36)
            Frame.BorderSizePixel = 0
            Frame.Position = UDim2.new(-0.897000074, 0, -0.100000046, 0)
            Frame.Size = UDim2.new(0, 205, 0, 33)
            
            UICorner_3.CornerRadius = UDim.new(0, 5)
            UICorner_3.Parent = Frame
            
            UICorner_4.Parent = Range
            
            
            local mouse = ms
            local Value;
            local uis = UserInputService
            local minvalue = min
            local maxvalue = max
            
            
            callback = callback or function() end
            
            if preval then
                SliderInner:TweenSize(UDim2.new(0, math.clamp(preval - SliderInner.AbsolutePosition.X, 0, SliderButton.AbsoluteSize.X), 0, SliderButton.AbsoluteSize.Y),"In","Quad",0.05,true,nil)
            end
            
            SliderButton.MouseButton1Down:Connect(function()
                Value = math.floor((((tonumber(maxvalue) - tonumber(minvalue)) / SliderButton.AbsoluteSize.X) *SliderInner.AbsoluteSize.X) + tonumber(minvalue)) or 0
                TextLabel.Text = (suffix .. "  ".. Value)
                pcall(function()
                    spawn(function() callback(Value) end)
                end)
                
                
                SliderInner:TweenSize(UDim2.new(0, math.clamp(mouse.X - SliderInner.AbsolutePosition.X, 0, SliderButton.AbsoluteSize.X), 0, SliderButton.AbsoluteSize.Y),"In","Quad",0.05,true,nil)
                
                
                moveconnection = mouse.Move:Connect(function()
                    TextLabel.Text = (suffix .. "  ".. Value)
                    Value = math.floor((((tonumber(maxvalue) - tonumber(minvalue)) / SliderButton.AbsoluteSize.X) * SliderInner.AbsoluteSize.X) + tonumber(minvalue))
                    pcall(function()
                        spawn(function() callback(Value) end)
                    end)
                    SliderInner:TweenSize(UDim2.new(0, math.clamp(mouse.X - SliderInner.AbsolutePosition.X, 0, SliderButton.AbsoluteSize.X), 0, SliderButton.AbsoluteSize.Y),"InOut","Quad",0.05,true,nil)
                end)
                
                releaseconnection = uis.InputEnded:Connect(function(Mouse)
                    if Mouse.UserInputType == Enum.UserInputType.MouseButton1 then
                        Value = math.floor((((tonumber(maxvalue) - tonumber(minvalue)) / SliderButton.AbsoluteSize.X) * SliderInner.AbsoluteSize.X) + tonumber(minvalue))
                        TextLabel.Text = (suffix .. "  ".. Value)
                        pcall(function()
                            spawn(function() callback(Value) end)
                        end)
                        SliderInner:TweenSize(UDim2.new(0, math.clamp(mouse.X - SliderInner.AbsolutePosition.X, 0, SliderButton.AbsoluteSize.X), 0, SliderButton.AbsoluteSize.Y),"Out","Quad",0.05,true,nil)
                        moveconnection:Disconnect()
                        releaseconnection:Disconnect()
                    end
                end)
            end)
        end
        
        
        function InsideTab:Box(placeholder,callback)
        
            local TextBox = Instance.new("TextBox")
            local tu = Instance.new("UICorner")
            local TextLabel = Instance.new("TextLabel")
            local stroke = Instance.new("Frame")
            local c = Instance.new("UICorner")
            
            --Properties:
            
            TextBox.Parent = tab
            TextBox.BackgroundColor3 = Color3.fromRGB(36, 36, 36)
            TextBox.BorderSizePixel = 0
            TextBox.Position = UDim2.new(0.330795258, 0, 0.0152671756, 0)
            TextBox.Size = UDim2.new(0, 570, 0, 34)
            TextBox.ZIndex = 2
            TextBox.ClearTextOnFocus = false
            TextBox.Font = Enum.Font.Gotham
            TextBox.PlaceholderText = placeholder
            TextBox.Text = ""
            TextBox.TextColor3 = Color3.fromRGB(85, 170, 127)
            TextBox.TextSize = 16.000
            
            tu.Name = "tu"
            tu.Parent = TextBox
            
            TextLabel.Parent = TextBox
            TextLabel.AnchorPoint = Vector2.new(0.5, 0)
            TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
            TextLabel.BackgroundTransparency = 1.000
            TextLabel.BorderSizePixel = 0
            TextLabel.Position = UDim2.new(0.915789604, 0, 0.0294117648, 0)
            TextLabel.Size = UDim2.new(0, 79, 0, 16)
            TextLabel.ZIndex = 2
            TextLabel.Font = Enum.Font.Gotham
            TextLabel.Text = placeholder
            TextLabel.TextColor3 = Color3.fromRGB(122, 122, 122)
            TextLabel.TextSize = 14.000
            TextLabel.TextTransparency = 1.000
            
            stroke.Name = "stroke"
            stroke.Parent = TextBox
            stroke.AnchorPoint = Vector2.new(0.5, 0.5)
            stroke.BackgroundColor3 = Color3.fromRGB(90, 90, 90)
            stroke.BorderSizePixel = 0
            stroke.Position = UDim2.new(0.5, 0, 0.5, 0)
            stroke.Size = UDim2.new(0, 572, 0, 36)
            
            c.Name = "c"
            c.Parent = stroke
            
            
            TextBox.Focused:Connect(function()
                bccolor(stroke,85, 170, 127,0.3)
            end)
            
            TextBox.Changed:Connect(function()
                if TextBox.focused then
                    if TextBox.Text == "" then
                        bccolor(stroke,90,90,90,0.3)
                        textfade(TextLabel,1,0.3)
                    else
                        bccolor(stroke,85, 170, 127,0.3)
                        textfade(TextLabel,0,0.3)
                    end
                end
            end)
            
            TextBox.FocusLost:Connect(function()
                bccolor(stroke,90, 90, 90,0.3)
                textfade(TextLabel,1,0.3)
                spawn(function() callback(TextBox.Text) end)
            end)
            
        end
        function InsideTab:Dropdown(Text,penis,y,callback,pretabl)
        
            local insidedrp = {}
            local dropdown = Instance.new("Frame")
            local UICorner = Instance.new("UICorner")
            local UICorner2 = Instance.new("UICorner")
            local UICorner3 = Instance.new("UICorner")
            local button = Instance.new("TextButton")
            local Arrow = Instance.new("ImageLabel")
            local drpfrm = Instance.new("ScrollingFrame")
            local dsda = Instance.new("UIStroke")
            local drpp = Instance.new("UIListLayout")
            
            
            dropdown.Name = "dropdown"
            dropdown.Parent = tab
            dropdown.BackgroundColor3 = Color3.fromRGB(36, 36, 36)
            dropdown.BackgroundTransparency = 1
            dropdown.BorderSizePixel = 0
            dropdown.Position = UDim2.new(0.111564629, 0, 0.166666642, 0)
            dropdown.Size = UDim2.new(0, 570, 0, 34)
            dropdown.ZIndex = 2
            
            
            dsda.Parent = dropdown
            dsda.ApplyStrokeMode = "Border"
            dsda.Color = Color3.fromRGB(61, 122, 90)	
            dsda.LineJoinMode = "Round"
            dsda.Thickness = 2
            dsda.Transparency = 0
            
            UICorner3.Parent = dropdown
            
            UICorner.Parent = button
            UICorner.CornerRadius = UDim.new(0,8)
            
            button.Name = "button"
            button.Parent = dropdown
            button.BackgroundColor3 = Color3.fromRGB(36, 36, 36)
            button.BackgroundTransparency = 0
            button.BorderSizePixel = 0
            button.Size = UDim2.new(0, 570, 0, 34)
            button.ZIndex = 2
            button.Font = Enum.Font.Gotham
            button.Text = text
            button.TextColor3 = Color3.fromRGB(255, 255, 255)
            button.TextSize = 16.000
            button.AutoButtonColor = false
            
            local toggle = false
            button.MouseButton1Click:Connect(function()
                drpfrm.ScrollingEnabled = not toggle
                if not toggle then
                    toggle = true
                    drpfrm:TweenSize(UDim2.new(0,570,0,y),"Out","Quad",0.2,true,nil)
                    dropdown:TweenSize(UDim2.new(0,570,0,y),"Out","Quad",0.2,true,nil)
                    rotate(Arrow,180,0.2)
                else
                    toggle = false
                    drpfrm:TweenSize(UDim2.new(0,570,0,32),"Out","Quad",0.2,true,nil)	
                    dropdown:TweenSize(UDim2.new(0,570,0,34),"Out","Quad",0.2,true,nil)	
                    rotate(Arrow,0,0.2)
                end
                
            end)
            
            
            
            
            
            
            Arrow.Name = "Arrow"
            Arrow.Parent = button
            Arrow.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
            Arrow.BackgroundTransparency = 1.000
            Arrow.BorderSizePixel = 0
            Arrow.Position = UDim2.new(0.94035089, 0, 0, 0)
            Arrow.Size = UDim2.new(0, 34, 0, 34)
            Arrow.ZIndex = 2
            Arrow.Image = "rbxassetid://3926305904"
            Arrow.ImageRectOffset = Vector2.new(44, 404)
            Arrow.ImageRectSize = Vector2.new(36, 36)
            
            drpfrm.Name = "drpfrm"
            drpfrm.Parent = dropdown
            drpfrm.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
            drpfrm.BorderSizePixel = 0
            drpfrm.Size = UDim2.new(0, 570, 0, 34)
            drpfrm.ScrollBarThickness = 3
            drpfrm.CanvasSize = UDim2.new(0,0,0,30)
            drpfrm.ScrollingEnabled = false
            
            UICorner2.Parent = drpfrm
            
            drpp.Name = "ddd"
            drpp.Parent = drpfrm
            drpp.VerticalAlignment = Enum.VerticalAlignment.Top
            drpp.SortOrder = Enum.SortOrder.LayoutOrder
            drpp.Padding = UDim.new(0, 4)
            
            local Frame = Instance.new("Frame")
            
            Frame.Parent = drpfrm
            Frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
            Frame.BackgroundTransparency = 1.000
            Frame.BorderSizePixel = 0
            Frame.Size = UDim2.new(0,2,0,34)
            local sex = {}
            for _,Text in pairs(penis) do
            
                local checkbox = Instance.new("TextLabel")
                local TextButton = Instance.new("TextButton")
                local circle = Instance.new("ImageLabel")
                local enable = Instance.new("ImageLabel")
                local disable = Instance.new("ImageLabel")
                local Sample = Instance.new("ImageLabel")
                local UICorner = Instance.new("UICorner")
                local Frame = Instance.new("Frame")
                local UICorner = Instance.new("UICorner")
                
                drpfrm.CanvasSize = drpfrm.CanvasSize + UDim2.new(0,0,0,38)
                --Properties:
                
                checkbox.Name = "checkbox"
                checkbox.Parent = drpfrm
                checkbox.BackgroundColor3 = Color3.fromRGB(36,36,36)
                checkbox.BackgroundTransparency = 1
                checkbox.BorderSizePixel = 0
                checkbox.ClipsDescendants = true
                checkbox.Position = UDim2.new(0, 0, 0, 0)
                checkbox.Size = UDim2.new(0, 574, 0, 34)
                checkbox.ZIndex = 2
                checkbox.Font = Enum.Font.Gotham
                checkbox.Text = "   " .. Text
                checkbox.TextColor3 = Color3.fromRGB(255,255,255)
                checkbox.TextSize = 16.000
                checkbox.TextWrapped = true
                checkbox.TextXAlignment = Enum.TextXAlignment.Left
                
                TextButton.Parent = checkbox
                TextButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
                TextButton.BackgroundTransparency = 1.000
                TextButton.BorderSizePixel = 0
                TextButton.Size = UDim2.new(0, 570, 0, 34)
                TextButton.ZIndex = 2
                TextButton.Font = Enum.Font.SourceSans
                TextButton.Text = ""
                TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
                TextButton.TextSize = 14.000
                
                circle.Name = "circle"
                circle.Parent = TextButton
                circle.AnchorPoint = Vector2.new(0, 0.5)
                circle.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
                circle.BackgroundTransparency = 1.000
                circle.BorderSizePixel = 0
                circle.Position = UDim2.new(0.939999998, 0, 0.5, 0)
                circle.Size = UDim2.new(0, 30, 0, 30)
                circle.ZIndex = 2
                circle.Image = "rbxassetid://3926305904"
                circle.ImageColor3 = Color3.fromRGB(255, 60, 63)
                circle.ImageRectOffset = Vector2.new(324, 964)
                circle.ImageRectSize = Vector2.new(36, 36)
                circle.ImageTransparency = 0
                
                
                local Framee = Instance.new("Frame")
                local UICornerrr = Instance.new("UICorner")
                
                Framee.Parent = circle
                Framee.AnchorPoint = Vector2.new(0.5, 0.5)
                Framee.BackgroundColor3 = Color3.fromRGB(36, 36, 36)
                Framee.Position = UDim2.new(0.5, 0, 0.5, 0)
                Framee.Size = UDim2.new(0, 24, 0, 24)
                Framee.ZIndex = 2
                Framee.BorderSizePixel = 0
                
                UICornerrr.CornerRadius = UDim.new(0, 1000)
                UICornerrr.Parent = Framee
                
                enable.Name = "enable"
                enable.Parent = circle
                enable.AnchorPoint = Vector2.new(0.5, 0.5)
                enable.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
                enable.BackgroundTransparency = 1.000
                enable.BorderSizePixel = 0
                enable.Position = UDim2.new(0.5, 0, 0.5, 0)
                enable.ZIndex = 3
                enable.Image = "rbxassetid://3926305904"
                enable.ImageColor3 = Color3.fromRGB(85, 170, 127)
                enable.ImageRectOffset = Vector2.new(312, 4)
                enable.ImageRectSize = Vector2.new(24, 24)
                
                disable.Name = "disable"
                disable.Parent = circle
                disable.AnchorPoint = Vector2.new(0.5, 0.5)
                disable.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
                disable.BackgroundTransparency = 1.000
                disable.BorderSizePixel = 0
                disable.Position = UDim2.new(0.5, 0, 0.5, 0)
                disable.Size = UDim2.new(0, 20, 0, 20)
                disable.ZIndex = 3
                disable.Image = "rbxassetid://3926305904"
                disable.ImageColor3 = Color3.fromRGB(255, 60, 63)
                disable.ImageRectOffset = Vector2.new(284, 4)
                disable.ImageRectSize = Vector2.new(24, 24)
                
                Sample.Name = "Sample"
                Sample.Parent = checkbox
                Sample.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
                Sample.BackgroundTransparency = 1.000
                Sample.ZIndex = 12
                Sample.Image = "http://www.roblox.com/asset/?id=4560909609"
                Sample.ImageColor3 = Color3.fromRGB(115, 115, 115)
                Sample.ImageTransparency = 0.600
                
                UICorner.Parent = checkbox
                
                -- Scripts:
                
                
                
                
                local enabled = false
                if table.find(pretabl,Text) then
                    enabled = true
                    table.insert(sex,Text)
                    enable:TweenSize(UDim2.new(0,20,0,20),"Out","Quad",0.1)
                    disable:TweenSize(UDim2.new(0,0,0,0),"Out","Quad",0.1)
                    color(circle,85, 170, 127,0.1)
                end
                
                TextButton.MouseButton1Click:Connect(function()
                    if not enabled then
                        enabled = true
                        table.insert(sex,Text)
                        callback(sex)
                        enable:TweenSize(UDim2.new(0,20,0,20),"Out","Quad",0.1)
                        disable:TweenSize(UDim2.new(0,0,0,0),"Out","Quad",0.1)
                        color(circle,85, 170, 127,0.1)
                    else if enabled then
                        enabled = false
                        disable:TweenSize(UDim2.new(0,20,0,20),"Out","Quad",0.1)
                        enable:TweenSize(UDim2.new(0,0,0,0),"Out","Quad",0.1)
                        color(circle,255, 60, 63,0.1)
                        for i,v in pairs(sex) do
                            if v == Text then
                                table.remove(sex,i)
                                break
                            end
                        end
                        callback(sex)
                        end
                    end
                end)
                
                
                
                
                
                TextButton.MouseEnter:Connect(function()
                    fade(checkbox,0,0.3)
                end)
                
                
                TextButton.MouseLeave:Connect(function()
                    fade(checkbox,1,0.3)
                end)
            end
            return insidedrp;
            
        end
        function InsideTab:Label(text)
		local label = Instance.new("TextLabel")
		local UICorner = Instance.new("UICorner")
            
        tab.CanvasSize = tab.CanvasSize + UDim2.new(0,0,0,38)

            
        label.Name = "label"
        label.Parent = tab
        label.BackgroundColor3 = Color3.fromRGB(36, 36, 36)
    	label.BorderColor3 = Color3.fromRGB(27, 42, 53)
    	label.BorderSizePixel = 0
    	label.ClipsDescendants = true
    	label.Size = UDim2.new(0, 570, 0, 34)
    	label.ZIndex = 2
    	label.Font = Enum.Font.Gotham
    	label.Text = text
    	label.TextColor3 = Color3.fromRGB(255,255,255)
    	label.TextSize = 16.000
    				
    	UICorner.Parent = label
    	local refr = {}
    	function refr:Refresh(newtext)
    	    label.Text = newtext
        end
        return refr;
end
    return InsideTab
    end
    return inside
end
return Library;
