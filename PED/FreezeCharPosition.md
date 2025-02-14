# FREEZE_CHAR_POSITION
- **Side:** Client

## Declaration
```cpp
// 0x20266A86
void FREEZE_CHAR_POSITION(Ped ped, boolean frozen);
```

### Arguments
- **Ped:** ped
- **boolean:** frozen

## Description
Freezes Character In Position they are in

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