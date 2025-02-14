# GET_SCREEN_RESOLUTION

## Declaration
```cpp
// 0xD8A1BCF
void GET_SCREEN_RESOLUTION();
```

### Results
- **int*:** x/w
- **int*:** y/h

## Description
Outputs screen resolution

```lua
local w, h = Game.GetScreenResolution()
local IdentityGui = WebUI.Create("file://ivd_identity/html/index.html", w, h, true)
```

```squirrel
local w, h = Game.GetScreenResolution();
local IdentityGui = WebUI.Create("file://ivd_identity/html/index.html", w, h, true);
```
