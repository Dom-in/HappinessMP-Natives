# SET_CHAR_COLLISION

## Declaration
```cpp
// 0x2A7413EB
void SET_CHAR_COLLISION(Ped ped, boolean set);
```

### Arguments
- **Ped:** ped
- **boolean:** set

## Description
Sets character collision

```lua
local playerChar = Game.GetPlayerChar(Game.GetPlayerId())
Game.SetCharCollision(playerChar, true)
```

```squirrel
local playerChar = Game.GetPlayerChar(Game.GetPlayerId());
Game.SetCharCollision(playerChar, true);
```