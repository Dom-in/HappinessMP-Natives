# CREATE_CAR

## Declaration
```cpp
// 0x2F1D6843
void CREATE_CAR(int modelHashKey, float x, float y, float z, int* vehicleIndex, bool registerAsNetworkObject);
```

### Arguments
- **int:** modelHashKey
- **float:** x
- **float:** y
- **float:** z
- **bool:** registerAsNetworkObject

### Results
- **int*:** vehicleIndex

## Description
Creates a car at the specified coords.

```lua
local model = Game.GetHashKey('SULTANRS')
local x, y, z = Game.GetCharCoordinates(Game.GetPlayerChar(Game.GetPlayerId()))
local heading = Game.GetCharHeading(Game.GetPlayerChar(Game.GetPlayerId()))
local car = Game.CreateCar(model, x, y, z, true)
Game.SetCarHeading(car, heading)
```

```squirrel
local model = Game.GetHashKey('SULTANRS');
local player = Game.GetPlayerChar(Game.GetPlayerId());
local x, y, z = Game.GetCharCoordinates(player);
local heading = Game.GetCharHeading(player);
local car = Game.CreateCar(model, x, y, z, true);
Game.SetCarHeading(car, heading);
```