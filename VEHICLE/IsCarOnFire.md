# IS_CAR_ON_FIRE
- **Side:** Client

## Declaration
```cpp
// 0x189A2BB1
boolean IS_CAR_ON_FIRE(Vehicle vehicle);
```

### Arguments
- **Vehicle:** vehicle

### Results
- **boolean**

## Description
Check if vehicle is on fire

```lua
local playerId = Game.GetPlayerId()
local playerChar = Game.GetPlayerChar(playerId)
local playerCar = Game.GetCarCharIsUsing(playerChar)
Game.IsCarOnFire(playerCar)
```

```squirrel
local playerId = Game.GetPlayerId();
local playerChar = Game.GetPlayerChar(playerId);
local playerCar = Game.GetCarCharIsUsing(playerChar);
Game.IsCarOnFire(playerCar);
```