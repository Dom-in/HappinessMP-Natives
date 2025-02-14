# SET_CAR_ON_GROUND_PROPERLY

## Declaration
```cpp
// 0xE717E98
bool SET_CAR_ON_GROUND_PROPERLY(int carIndex);
```

### Arguments
- **int:** carIndex

### Results
- **bool**

## Description
Sets the car on the ground taking into account the angle of the ground.

```lua
local model = Game.GetHashKey('SULTANRS')
local x, y, z = Game.GetCharCoordinates(Game.GetPlayerChar(Game.GetPlayerId()))
local heading = Game.GetCharHeading(Game.GetPlayerChar(Game.GetPlayerId()))
local car = Game.CreateCar(model, x, y, z, true)
Game.SetCarOnGroundProperly(car)
```

```squirrel
local model = Game.GetHashKey('SULTANRS');
local player = Game.GetPlayerChar(Game.GetPlayerId());
local x, y, z = Game.GetCharCoordinates(player);
local heading = Game.GetCharHeading(player);
local car = Game.CreateCar(model, x, y, z, true);
Game.SetCarOnGroundProperly(car);
```