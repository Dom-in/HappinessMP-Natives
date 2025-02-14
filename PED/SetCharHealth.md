# SET_CHAR_HEALTH

## Declaration
```cpp
// 0x575E2880
void SET_CHAR_HEALTH(Ped ped, uint health);
```

### Arguments
- **Ped:** ped
- **uint:** health

## Description
Sets character health

```lua
local playerId = Game.GetPlayerId()
local playerChar = Game.GetPlayerChar(playerId)
Game.SetCharHealth(playerChar, 300)
```

```squirrel
local playerId = Game.GetPlayerId();
local playerChar = Game.GetPlayerChar(playerId);
Game.SetCharHealth(playerChar, 300);
```