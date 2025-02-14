# CLEAR_CHAR_TASKS_IMMEDIATELY
- **Side:** Client

## Declaration
```cpp
// 0x3C116620
void CLEAR_CHAR_TASKS_IMMEDIATELY(Ped ped);
```

### Arguments
- **Ped:** ped

## Description
Force stops characters tasks

```lua
local playerChar = Game.GetPlayerChar(Game.GetPlayerId())
Game.ClearCharTasksImmediately(playerChar)
```

```squirrel
local playerChar = Game.GetPlayerChar(Game.GetPlayerId());
Game.ClearCharTasksImmediately(playerChar);
```
