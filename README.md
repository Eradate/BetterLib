-- Require the library
local library = loadstring(game:HttpGet("

-- Name of the libraryl
```
local ui = library.new("My UI Library")
```
-- Adding a tab
```
local featuresTab = ui:addTab("Features")
```
-- Adding a label
```
ui:addLabel(featuresTab, "Welcome to the Features tab!")
```
-- Adding a button
```
ui:addButton(featuresTab, "Click Me", function()
    print("Button clicked!")
end)
```
-- Adding a toggle button
```
ui:addToggle(featuresTab, "Toggle this", function(state)
    print("Toggle state:", state)
end)
```

-- Adding a text box
```
ui:addTextbox(featuresTab, "Enter text here...", function(text)
    print("Textbox input:", text)
end)
```
