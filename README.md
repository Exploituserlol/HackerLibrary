### Exemplo de Uso
### Library

```lua
local Library = require(script:WaitForChild("https://github.com/Exploituserlol/HackerLibrary/tree/main"))
```
### Window Gui

```lua
local gui, frame = Library:CreateMainGUI("NUPPJJ TEAM", UDim2.new(0, 1000, 0, 600))
```
### Tabs

```lua
-- Criando os Tabs
local tabs = Library:CreateTabs(frame, {"Tab 1", "Tab 2", "Tab 3"})
```
### Button

```lua
-- Adicionando conteúdo ao Tab 1
local button1 = Library:CreateButton(tabs["Tab 1"], "Click Me", UDim2.new(0.1, 0, 0.1, 0), UDim2.new(0, 200, 0, 50), function()
    print("Botão do Tab 1 clicado!")
end)
```
```lua
-- Adicionando botão de visibilidade
Library:CreateToggleVisibilityButton(gui, "1234567890", UDim2.new(0, 10, 0, 10), UDim2.new(0, 50, 0, 50))
```
