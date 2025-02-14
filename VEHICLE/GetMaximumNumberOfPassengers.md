# GET_MAXIMUM_NUMBER_OF_PASSENGERS
- **Side:** Client

## Declaration
```cpp
// 0x554014F1
void GET_MAXIMUM_NUMBER_OF_PASSENGERS(Vehicle vehicle);
```

### Arguments
- **Vehicle:** vehicle

### Results
- **uint*:** pMax

## Description
Returns maximum of passangers in specific vehicle

```lua
local playerId = Game.GetPlayerId()
local playerChar = Game.GetPlayerChar(playerId)
local playerCar = Game.GetCarCharIsUsing(playerChar)
if Game.GetMaximumNumberOfPassengers(playerCar) == Game.GetNumberOfPassengers(playerCar) then
    -- Do some when passanger max == actual number
end
```

```squirrel
local playerId = Game.GetPlayerId();
local playerChar = Game.GetPlayerChar(playerId);
local playerCar = Game.GetCarCharIsUsing(playerChar);
if (Game.GetMaximumNumberOfPassengers(playerCar) == Game.GetNumberOfPassengers(playerCar)) {
    // Do some when passenger max == actual number
}
```