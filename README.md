# UI-World-of-Warcraft

Changes the position of actionbars and the standard blizzard CC alert

![Pic1](https://i.imgur.com/AJQUtsb.jpg)
![Pic!](https://i.imgur.com/OQdp40S.jpg)

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
StatusTrackingBarManager:Hide()
MicroButtonAndBagsBar:Hide()
MicroButton:Hide()
MicroMenu:Hide()
```

### Hide macro and hotkey text

Type ```/hhk``` to hide hotkeys

Type ```/hmn``` to hide macro names

## License
[MIT](https://choosealicense.com/licenses/mit/)
