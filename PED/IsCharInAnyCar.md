# IS_CHAR_IN_ANY_CAR
- **Side:** Client

## Declaration
```cpp
// 0x71184DA3
boolean IS_CHAR_IN_ANY_CAR(Ped ped);
```

### Arguments
- **Ped:** ped

### Results
- **boolean**

## Description
Returns true/false if character is in any vehicle

```lua
local playerId = Game.GetPlayerId()
local playerChar = Game.GetPlayerChar(playerId)
if Game.IsCharInAnyCar(playerChar) then
    local playerCar = Game.GetCarCharIsUsing(playerChar)
    Game.FixCar(playerCar)
end
```

```squirrel
local playerId = Game.GetPlayerId();
local playerChar = Game.GetPlayerChar(playerId);
if (Game.IsCharInAnyCar(playerChar)) {
    local playerCar = Game.GetCarCharIsUsing(playerChar);
    Game.FixCar(playerCar);
}
```