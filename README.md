# SLF UI Library

Thank you for using my UI library, there is how to use it.

## Loader

```lua
local Library = loadstring(game:HttpGetAsync('https://raw.githubusercontent.com/MirroxGame/settings/main/settings.lua'))()
```

## Functions

### Creating Window
____
```lua
local Main = Library:CreateMain("TITLE","KeyBind")
```

### Adding Tab
____
```lua
local Tab = Main:AddTab("TabName")
```

### Adding Button
____
```lua
local Button = Tab:AddButton("ButtonText",function()
  print("Clicked")
end)
```

### Adding Toggles
____
```lua
local Toggle = Tab:AddCheckbox("ToggleText",function(state)
  if state then
    print("Toggle On")
  else
    print("Toggle Off")
  end
end)
```

### Adding Slider
____
```lua
local Slider = Tab:AddSlider("SliderText",0,100,"SliderSuffix",function(value)  -- 0 (MinValue) | 100 (MaxValue)
  print(value)
end)
```

### Adding TextBox
____
```lua
local TextBox = Tab:AddTextBox("TextBoxText",function(text)
  print(text)
end)
```
