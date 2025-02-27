# ALTER_WANTED_LEVEL
- **Side:** Client

## Declaration
```cpp
// 0x60C80EC9
void ALTER_WANTED_LEVEL(Player playerIndex, uint level);
```

### Arguments
- **Player:** playerIndex
- **uint:** level

## Description
Alters player wanted level

```lua
local playerId = Game.GetPlayerId();
Game.AlterWantedLevel(playerId, 0)
```

```squirrel
local playerId = Game.GetPlayerId();
Game.AlterWantedLevel(playerId, 0);
```