# iris-bundle

Unofficial bundled releases for [iris](https://github.com/SirMallard/Iris)

## Example

```lua
local Iris = loadstring(game:HttpGet("https://github.com/Cauze/iris-bundle/releases/latest/download/iris.lua"))();
Iris.Init();
Iris:Connect(Iris.ShowDemoWindow);
```

A minified version (`iris.min.lua`) will be included when a good enough minifier is available. Unfortunately, [darklua](https://github.com/seaofvoices/darklua) breaks it
