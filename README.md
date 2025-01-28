# Tutorial Abaixo

# Library: local Library = require(script:WaitForChild("https://raw.githubusercontent.com/Exploituserlol/Mylibrary/refs/heads/main/Library.txt"))

-- Criando a GUI principal
local gui, frame = Library:CreateMainGUI("NUPPJJ TEAM", UDim2.new(0, 1000, 0, 600))

-- Criando os Tabs
local tabs = Library:CreateTabs(frame, {"Tab 1", "Tab 2", "Tab 3"})

-- Adicionando conteúdo ao Tab 1
local button1 = Library:CreateButton(tabs["Tab 1"], "Click Me", UDim2.new(0.1, 0, 0.1, 0), UDim2.new(0, 200, 0, 50), function()
    print("Botão do Tab 1 clicado!")
end)

-- Adicionando conteúdo ao Tab 2
local button2 = Library:CreateButton(tabs["Tab 2"], "Hello World", UDim2.new(0.1, 0, 0.1, 0), UDim2.new(0, 200, 0, 50), function()
    print("Botão do Tab 2 clicado!")
end)

-- Adicionando botão de Minimize
Library:CreateToggleVisibilityButton(gui, "ID DA FOTO AQUI", UDim2.new(0, 10, 0, 10), UDim2.new(0, 50, 0, 50))
