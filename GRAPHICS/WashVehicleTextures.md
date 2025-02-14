# WASH_VEHICLE_TEXTURES
- **Side:** Client

## Declaration
```cpp
// 0x69491CFA
void WASH_VEHICLE_TEXTURES(Vehicle vehicle, uint intensity);
```

### Arguments
- **Vehicle:** vehicle
- **uint:** intensity

## Description
Sets vehicle wash level

```lua
local currentCar = Game.GetCarCharIsUsing(Game.GetPlayerChar(Game.GetPlayerId()))
Game.WashVehicleTextures(currentCar, 255)
```

```squirrel
local currentCar = Game.GetCarCharIsUsing(Game.GetPlayerChar(Game.GetPlayerId()))
Game.WashVehicleTextures(currentCar, 255);
```