## استدعاء مكتبه / Call his office
```lua
local GuiLibrary = loadstring(game:HttpGet("https://raw.githubusercontent.com/SCRIPTSROBLOX738833/GUILIbry-/refs/heads/main/GUILIBRY"))()
```
## إنشاء واجهة جديدة / Create a new interface
```lua
local ScreenGui = Instance.new("ScreenGui")
ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
```
## استخدام المكتبة لإنشاء زر مع اسم معين / Use the library to create a button with a specific name.
```lua
local button = GuiLibrary.createButton(ScreenGui, "اضغط هنا", UDim2.new(0, 200, 0, 50), UDim2.new(0.5, -100, 0.5, -25), function()
    print("تم الضغط على الزر! / button hunt")
end)
```
