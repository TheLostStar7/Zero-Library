## Zero-Library.

My First Ever Published UI Library. I Hope You Like It!

## Credits.

Solo Dev, TheLostStar7.

## Change Log.

Future:
Hopefully I'm Gonna Add A Dropdown.

New:
Label, Fits 191 Digits.

Old:
New Dragging System, Better And Improved.

## Loadstring.
```lua
local ZeroLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/TheLostStar7/Zero-Library/refs/heads/main/ZeroLib')))()
--[[
Loads The UI Library/UI Lib
]]
```

## Window.
```lua
local Window = ZeroLib:CreateWindow({Title = "Hello"})
--[[
Title = <string> - The Name Of The UI.
]]
```

## Tab.
```lua
local Tab = Window:AddTab({Title = "Main Tab"})
--[[
Title = <string> - The Name Of The Tab.
]]
```

## Button.
```lua
local Button = Tab:AddButton({Title = "Hello",Flag = "Hello Button",Callback = function()
    print("sup g")
end,})
--[[
Title = <string> - The Name Of The Button.
Flag = <string> - The Name Of The Flag Report.
Callback = <function> - The Function Of The Button.
]]
```

## Toggle.
```lua
local Toggle = Tab:AddToggle({Title = "YO",Description = "IT'S ME THE ONE AND ONLY TOGGLE",Flag = "Hello Button",Callback = function()
    print("Googlely Goggles.")
end,})
--[[
Title = <string> - The Name Of The Button.
Description = <string> - The Name Of The Description.
Flag = <string> - The Name Of The Flag Report.
Callback = <function> - The Function Of The Button.
]]
```

## Label.
```lua
local Text = Tab:AddLabel({Text = "Yappers"})
--[[
Text = <string> - The Text Of Label.
]]
```
### Label Subtle Functions.
```lua
Text:Update("Hello")
--[[
Argue[1] = <string> - The New Text Of The Label.
]]
```
```lua
Text:Get()
--[[
Gives You The Current Text.
]]
```

## Destroy.
```lua
ZeroLib:Destroy()
--[[
Destroys The UI Lib
]]
```
