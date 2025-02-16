# FREEZE_CAR_POSITION
- **Side:** Client

## Declaration
```cpp
// 0x295C4C52
void FREEZE_CAR_POSITION(Vehicle vehicle, boolean frozen);
```

### Arguments
- **Vehicle:** vehicle
- **boolean:** frozen

## Description
Freezes the car in position it is now

```lua
local playerId = Game.GetPlayerId()
local playerChar = Game.GetPlayerChar(playerId)
local playerCar = Game.GetCarCharIsUsing(playerChar)
Game.FreezeCarPosition(playerCar, true)
```

```squirrel
local playerId = Game.GetPlayerId();
local playerChar = Game.GetPlayerChar(playerId);
local playerCar = Game.GetCarCharIsUsing(playerChar);
Game.FreezeCarPosition(playerCar, true);
```