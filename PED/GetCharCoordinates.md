# GET_CHAR_COORDINATES
- **Side:** Client

## Declaration
```cpp
// 0x2B5C06E6
void GET_CHAR_COORDINATES(int charIndex, float* pX, float* pY, float* pZ);
```

### Arguments
- **int:** charIndex

### Results
- **float*:** pX
- **float*:** pY
- **float*:** pZ

## Description
Allows you to get the coordinates of the player

```lua
Game.GetCharCoordinates(Game.GetPlayerChar(Game.GetPlayerId()))
```

```squirrel
Game.GetCharCoordinates(Game.GetPlayerChar(Game.GetPlayerId()));
```