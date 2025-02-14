# SET_CHAR_NEVER_TARGETTED
- **Side:** Client

## Declaration
```cpp
// 0x5EA84115
void SET_CHAR_NEVER_TARGETTED(Ped ped, boolean set);
```

### Arguments
- **Ped:** ped
- **boolean:** set

## Description
Character will never be targeted by peds and police

```lua
local playerId = Game.GetPlayerId()
local playerChar = Game.GetPlayerChar(playerId)
Game.FreezeCharPosition(playerChar, true)
```

```squirrel
local playerId = Game.GetPlayerId();
local playerChar = Game.GetPlayerChar(playerId);
Game.FreezeCharPosition(playerChar, true);
```