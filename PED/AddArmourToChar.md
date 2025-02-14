# ADD_ARMOUR_TO_CHAR
- **Side:** Client

## Declaration
```cpp
// 0x1C623537
void ADD_ARMOUR_TO_CHAR(Ped ped, uint amount);
```

### Arguments
- **Ped:** ped
- **uint:** amount

## Description
Sets character armour

```lua
local playerId = Game.GetPlayerId()
local playerChar = Game.GetPlayerChar(playerId)
Game.AddArmourToChar(playerChar, 200)
```

```squirrel
local playerId = Game.GetPlayerId();
local playerChar = Game.GetPlayerChar(playerId);
Game.AddArmourToChar(playerChar, 200);
```