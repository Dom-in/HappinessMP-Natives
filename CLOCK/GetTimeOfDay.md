# GET_TIME_OF_DAY
- **Side:** Client

## Declaration
```cpp
// 0x384B3876
void GET_TIME_OF_DAY(uint* hour, uint* minute);
```

### Arguments

### Results
- **uint*:** hour
- **uint*:** minute

## Description
Outputs time of the day

```lua
local h, m = Game.GetTimeOfDay()
Chat.AddMessage(h..":"..m)
```

```squirrel
local h, m = Game.GetTimeOfDay();
Chat.AddMessage(h..":"..m);
```