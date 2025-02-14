# CREATE_OBJECT
- **Side:** Client

## Declaration
```cpp
// 0x4DE152A0
void CREATE_OBJECT(int modelHashKey, float x, float y, float z, bool registerAsNetworkObject);
```

### Arguments
- **int:** modelHashKey
- **float:** x
- **float:** y
- **float:** z
- **bool:** registerAsNetworkObject

### Results
- **int*:** objectIndex

## Description
Create an object with an offset (from the root the base) at the given coord.

```lua
Game.CreateObject(0x2718C626, -22, 22, 22, true)
```

```squirrel
Game.CreateObject(0x2718C626, -22, 22, 22, true);
```