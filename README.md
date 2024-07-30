# Require the library
```
local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/Eradate/BetterLib/main/mainfiles"))()
```
# Library Title
```
local ui = library.new("My UI Library")
```
# Tab Creating
```
local featuresTab = ui:addTab("Features")
```
# Adding a Label
```
ui:addLabel(featuresTab, "Welcome to the Features tab!")
```
# Adding a Button
```
ui:addButton(featuresTab, "Click Me", function()
    print("Button clicked!")
end)
```
# Adding a Toggle
```
ui:addToggle(featuresTab, "Toggle Option", function(state)
    if state then
        print("Toggle is On")
    else
        print("Toggle is Off")
    end
end)
```
# Adding an Text Input
```
ui:addTextbox(featuresTab, "Enter text here...", function(text)
    print("Textbox text:", text)
end)
```
