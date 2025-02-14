# SET_POLICE_IGNORE_PLAYER

## Declaration
```cpp
// 0x619D51D3
void SET_POLICE_IGNORE_PLAYER(Player playerIndex, boolean value);
```

### Arguments
- **Player:** playerIndex
- **boolean:** value

## Description
Disables police in game for specific player

```lua
local playerId = Game.GetPlayerId()
Game.SetPoliceIgnorePlayer(playerId, true)
```

```squirrel
local playerId = Game.GetPlayerId();
Game.SetPoliceIgnorePlayer(playerId, true);
```