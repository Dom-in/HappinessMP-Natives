# TASK_PLAY_ANIM
- **Side:** Client

## Declaration
```cpp
// 0x28EE78D8
void TASK_PLAY_ANIM(int charIndex, char* animName, char* animDictName, float speed, bool flag1, bool flag2, bool flag3, bool flag4, int timeToPlay);
```

### Arguments
- **int:** charIndex
- **char*:** animName
- **char*:** animDictName
- **float:** speed (usually 8.0)
- **bool:** flag1
- **bool:** flag2
- **bool:** flag3
- **bool:** flag4
- **int:** timeToPlay (-1 for infinite)

## Description
Plays an anim on the specified char.

```lua
local playerId = Game.GetPlayerId()
local playerChar = Game.GetPlayerChar(playerId)
Game.TaskPlayAnim(playerChar, "Give_Money", "AMB@CARWASH", 1.0, false, false, false, false, 0)
```

```squirrel
local playerId = Game.GetPlayerId();
local playerChar = Game.GetPlayerChar(playerId);
Game.TaskPlayAnim(playerChar, "Give_Money", "AMB@CARWASH", 1.0, false, false, false, false, 0);
```