# SET_CAR_HEADING
- **Side:** Client

## Declaration
```cpp
// 0x75E40528
void SET_CAR_HEADING(int vehicleIndex, float newHeading);
```

### Arguments
- **int:** vehicleIndex
- **float:** newHeading

### Results

## Description
Sets the car's heading in degrees.

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