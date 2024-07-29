# Loading the Library

```
local MyLibrary = loadstring(game:HttpGet("https://raw.githubusercontent.com/Eradate/BetterLib/main/mainfile"))()
```
# Name of the library
```
local lib = MyLibrary.new("My UI Library")
```
# Tab Name/ Create tabs
```
local tab1 = lib:addTab("Features")

local tab2 = lib:addTab("Settings")
```
# Creating Labels
```
lib:addLabel(tab1, "Welcome to the features tab!")
```
# Creating Buttons
```
lib:addButton(tab1, "Click Me", function() 
print("Button clicked!") 
end)
```
# Creating Toggles
```
lib:addToggle(tab2, "Enable Feature",
function(state) 
print("Feature enabled:", state) 
end)
```
