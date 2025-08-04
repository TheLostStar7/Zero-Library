## Zero-Library.

My First Ever Published UI Library. I Hope You Like It!

## Credits.

Solo Dev, TheLostStar7.

## Change Log.

Future:

Hopefully I'm Gonna Add A Dropdown.

New:

Message:

Guys please bare with me, i need some time to think about a button design but for now we'll have this.

New Close/Open Button.

Smoother And Better Tweening For The AddTab And AddToggle.

AddToggle And AddButton Flagging Changes.

AddButton Hovering System.

New Subtitle Function.

Reworked Ths Keybinds.

Old:

Close/Open Keybind. Default Is X.

Label, Fits 191 Digits.

New Dragging System, Better And Improved.

## Loadstring.
```lua
local ZeroLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/TheLostStar7/Zero-Library/refs/heads/main/ZeroLib')))()
--[[
Loads The UI Library/UI Lib
]]
```

### Destroy.
```lua
ZeroLib:Destroy()
--[[
Destroys The UI Lib
]]
```

### KeyBind.
```lua
ZeroLib:SetKeyBind("K")
--[[
Argument[1] = <string> - New KeyBind To Close The UI With.
]]
```

## Window.
```lua
local Window = ZeroLib:CreateWindow({Title = "Hello",KeyBind = "E"})
--[[
Title = <string> - The Name Of The UI.
KeyBind = <string> - The Keybind To Close/Open The UI.
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
]
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
### Label Subtitle Functions.
```lua
Text:Update("Hello")
--[[
Argument[1] = <string> - The New Text Of The Label.
]]
```
```lua
Text:Get()
--[[
Gives You The Current Text.
]]
```
