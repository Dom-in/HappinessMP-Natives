# CLEAR_CHAR_TASKS

## Declaration
```cpp
// 0x4AB470F3
void CLEAR_CHAR_TASKS(Ped ped);
```

### Arguments
- **Ped:** ped

## Description
Stops characters tasks

```lua
local playerChar = Game.GetPlayerChar(Game.GetPlayerId())
Game.ClearCharTasks(playerChar)
```

```squirrel
local playerChar = Game.GetPlayerChar(Game.GetPlayerId());
Game.ClearCharTasks(playerChar);
```