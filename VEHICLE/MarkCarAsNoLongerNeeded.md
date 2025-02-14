# MARK_CAR_AS_NO_LONGER_NEEDED
- **Side:** Client

## Declaration
```cpp
// 0x20C76FD1
void MARK_CAR_AS_NO_LONGER_NEEDED(Vehicle& pVehicle);
```

### Arguments
- **Vehicle&:** pVehicle

## Description
Tells the game that this script no longer needs this vehicle.

```lua
local model = Game.GetHashKey('SULTANRS')
local x, y, z = Game.GetCharCoordinates(Game.GetPlayerChar(Game.GetPlayerId()))
local heading = Game.GetCharHeading(Game.GetPlayerChar(Game.GetPlayerId()))
local car = Game.CreateCar(model, x, y, z, true)
Game.MarkCarAsNoLongerNeeded(car)
```

```squirrel
local model = Game.GetHashKey('SULTANRS');
local player = Game.GetPlayerChar(Game.GetPlayerId());
local x, y, z = Game.GetCharCoordinates(player);
local heading = Game.GetCharHeading(player);
local car = Game.CreateCar(model, x, y, z, true);
Game.MarkCarAsNoLongerNeeded(car);
```