SLF ui library.

Thank you for using my UI library.

There is how to use it.


//Main Gui//

local main = Library:CreateMain("Name Here","Any key you want") -- it creates the main window

//


//Tabs//
local Tab = main:AddTab("Name Here")
//


<<COMPONENTS>>
//(buttons,checkboxes,textboxes,sliders)//

local button = Tab:AddButton("Name Here",function()
-- your code here
end)


local checkbox = Tab:AddCheckbox("Name Here",function(Bool)
-- your code here
end)

  
local slider = Tab:AddSlider("Name Here",MinValue,MaxValue,"suffix",function(val)
-- your code here
end)
  
local textbox = Tab:AddTextBox("Name Here",function(OutPut)
-- your code here
end)
  
