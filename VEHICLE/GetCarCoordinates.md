# GET_CAR_COORDINATES
- **Side:** Client

## Declaration
```cpp
// 0x2D432EAB
void GET_CAR_COORDINATES(Vehicle vehicle);
```

### Arguments
- **Vehicle:** vehicle

### Results
- **float*:** pX
- **float*:** pY
- **float*:** pZ

## Description
Gives coords of the vehicle

```lua
local playerId = Game.GetPlayerId()
local playerChar = Game.GetPlayerChar(playerId)
local playerCar = Game.GetCarCharIsUsing(playerChar)
local x, y, z = Game.GetCarCoordinates(playerCar)
Console.Log(x..' '..y..' '..z)
```

```squirrel
local playerId = Game.GetPlayerId();
local playerChar = Game.GetPlayerChar(playerId);
local playerCar = Game.GetCarCharIsUsing(playerChar);
Game.FreezeCarPosition(playerCar, true);
```