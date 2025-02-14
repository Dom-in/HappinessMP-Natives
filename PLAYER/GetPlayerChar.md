# GET_PLAYER_CHAR
- **Side:** Client

## Declaration
```cpp
// 0x511454A9
void GET_PLAYER_CHAR(Player playerIndex, Ped* pPed);
```

### Arguments
- **Player:** playerIndex

### Results
- **Ped*:** pPed

## Description
Allows you to get player character

```lua
Game.GetPlayerChar(Game.GetPlayerId())
```

```squirrel
Game.GetPlayerChar(Game.GetPlayerId());
```