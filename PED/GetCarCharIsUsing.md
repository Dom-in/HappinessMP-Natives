# GET_CAR_CHAR_IS_USING
- **Side:** Client

## Declaration
```cpp
// 0x1B067237
void GET_CAR_CHAR_IS_USING(Ped ped);
```

### Arguments
- **Ped:** ped

### Results
- **Vehicle*:** pVehicle

## Description
Returns the vehicle character is using

```lua
local playerId = Game.GetPlayerId()
local playerChar = Game.GetPlayerChar(playerId)
local playerCar = Game.GetCarCharIsUsing(playerChar)
Game.FixCar(playerCar)
```

```squirrel
local playerId = Game.GetPlayerId();
local playerChar = Game.GetPlayerChar(playerId);
local playerCar = Game.GetCarCharIsUsing(playerChar);
Game.FixCar(playerCar);
```