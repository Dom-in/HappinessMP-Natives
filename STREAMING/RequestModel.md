# REQUEST_MODEL
- **Side:** Client

## Declaration
```cpp
// 0x502B5185
void REQUEST_MODEL(int modelHashKey);
```

### Arguments
- **int:** modelHashKey

## Description
Request streaming to load a model.

```lua
local model = Game.GetHashKey("SULTANRS")
Game.RequestModel(model)
```

```squirrel
local model = Game.GetHashKey("SULTANRS");
Game.RequestModel(model);
```