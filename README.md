# UI-World-of-Warcraft

Changes the position of [actionbars and the standard blizzard CC alert](https://imgur.com/a/Kw4t7GK)

## Usage and modifications

### Bars
```Lua
ActionButton1:ClearAllPoints()
ActionButton1:SetPoint("CENTER", X Cordinates, Y Cordinates) 
ActionButton1.SetPoint = function() end

MultiBarBottomLeftButton1:ClearAllPoints()
MultiBarBottomLeftButton1:SetPoint("CENTER", X Cordinates, Y Cordinates)
MultiBarBottomLeftButton1.SetPoint = function() end 
```
### Statusbar and mini menu
```Lua
-- Remove mini menu
StatusTrackingBarManager:Hide()
MicroButtonAndBagsBar:Hide()
MicroButton:Hide()
MicroMenu:Hide()
```

## hide macro and hotkey text
Type ```/hhk``` to hide hotkeys
Type ```/hmn``` to hide macro names

## License
[MIT](https://choosealicense.com/licenses/mit/)
