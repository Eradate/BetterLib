# Require the library
```
local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/Eradate/BetterLib/main/mainfiles"))()
```
MainFrame of the Ui
```
-- Create a new UI library instance
local UI = Library.new("Example UI")
```
Adding a Tab
```
-- Add a new tab
local firstTab = UI:addTab("First Tab")
```
Adding a Toggle
```
-- Add a toggle button to the first tab
UI:addToggle(firstTab, "Toggle Option", function(state)
    print("Toggle state:", state)
end)
```
Adding a Text Input
```
-- Add a textbox to the first tab
UI:addTextbox(firstTab, "Enter Text Here", function(text)
    print("Textbox input:", text)
end)
```
Adding a Button
```
-- Add a regular button to the first tab
UI:addButton(firstTab, "Click Me", function()
    print("Button clicked!")
end)
```
Adding a Tab
```
-- Add another tab
local secondTab = UI:addTab("Second Tab")
```
Adding a Toggle
```
-- Add a toggle button to the second tab
UI:addToggle(secondTab, "Another Toggle", function(state)
    print("Another toggle state:", state)
end)
```
Adding a Text Input
```
-- Add a textbox to the second tab
UI:addTextbox(secondTab, "Another Textbox", function(text)
    print("Another textbox input:", text)
end)
```
Adding a Button
```
-- Add a regular button to the second tab
UI:addButton(secondTab, "Another Button", function()
    print("Another button clicked!")
end)
```
