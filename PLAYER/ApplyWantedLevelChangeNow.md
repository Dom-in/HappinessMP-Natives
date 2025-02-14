# APPLY_WANTED_LEVEL_CHANGE_NOW
- **Side:** Client

## Declaration
```cpp
// 0x705A6ED9
void APPLY_WANTED_LEVEL_CHANGE_NOW(Player playerIndex);
```

### Arguments
- **Player:** playerIndex

## Description
Force sets wanted level on player

```lua
local playerId = Game.GetPlayerId()
Game.ApplyWantedLevelChangeNow(playerId)
```

```squirrel
local playerId = Game.GetPlayerId();
Game.ApplyWantedLevelChangeNow(playerId);
```