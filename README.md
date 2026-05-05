# iris-bundle

Unofficial bundled releases for [iris](https://github.com/SirMallard/Iris)

> [!NOTE]
> Currently, releases are not minified as there is not a good enough minifier available. \
> Unfortunately, [darklua](https://github.com/seaofvoices/darklua) breaks it.

## Example

```lua
local Iris = loadstring(game:HttpGet("https://github.com/Cauze/iris-bundle/releases/latest/download/iris.lua"))();
Iris.Init();
Iris:Connect(Iris.ShowDemoWindow);
```
