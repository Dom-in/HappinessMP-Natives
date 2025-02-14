# GET_DISPLAY_NAME_FROM_VEHICLE_MODEL
- **Side:** Client

## Declaration
```cpp
// 0x404E0056
char* GET_DISPLAY_NAME_FROM_VEHICLE_MODEL(int modelHashKey);
```

### Arguments
- **int:** modelHashKey

### Results
- **char***

## Description
Gets the the model name of the vehicle.

```lua
local currentCar = Game.GetCarCharIsUsing(Game.GetPlayerChar(Game.GetPlayerId()))
Game.GetDisplayNameFromVehicleModel(currentCar)
```

```squirrel
local currentCar = Game.GetCarCharIsUsing(Game.GetPlayerChar(Game.GetPlayerId()));
Game.GetDisplayNameFromVehicleModel(currentCar);
```