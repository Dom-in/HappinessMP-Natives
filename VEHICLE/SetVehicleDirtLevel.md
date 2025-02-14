# SET_VEHICLE_DIRT_LEVEL
- **Side:** Client

## Declaration
```cpp
// 0x2A57428
void SET_VEHICLE_DIRT_LEVEL(Vehicle vehicle, float intensity);
```

### Arguments
- **Vehicle:** vehicle
- **float:** intensity

## Description
Sets vehicle dirt level

```lua
local currentCar = Game.GetCarCharIsUsing(Game.GetPlayerChar(Game.GetPlayerId()))
Game.SetVehicleDirtLevel(currentCar, 0.0)
```

```squirrel
local currentCar = Game.GetCarCharIsUsing(Game.GetPlayerChar(Game.GetPlayerId()))
Game.SetVehicleDirtLevel(currentCar, 0.0);
```