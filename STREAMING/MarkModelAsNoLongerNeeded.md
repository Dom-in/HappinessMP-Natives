# MARK_MODEL_AS_NO_LONGER_NEEDED

## Declaration
```cpp
// 0xFA0E33
void MARK_MODEL_AS_NO_LONGER_NEEDED(int modelHashKey);
```

### Arguments
- **int:** modelHashKey

## Description
Tell streaming that this script no longer needs this model.

```lua
local model = Game.GetHashKey('SULTANRS')
local x, y, z = Game.GetCharCoordinates(Game.GetPlayerChar(Game.GetPlayerId()))
local heading = Game.GetCharHeading(Game.GetPlayerChar(Game.GetPlayerId()))
local car = Game.CreateCar(model, x, y, z, true)
Game.MarkModelAsNoLongerNeeded(model)
```

```squirrel
local model = Game.GetHashKey('SULTANRS');
local player = Game.GetPlayerChar(Game.GetPlayerId());
local x, y, z = Game.GetCharCoordinates(player);
local heading = Game.GetCharHeading(player);
local car = Game.CreateCar(model, x, y, z, true);
Game.MarkModelAsNoLongerNeeded(model);
```