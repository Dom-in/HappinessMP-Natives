# HappinessMP Natives
- **How many natives got there meaning?**
```lua
As of now the statistics are 23/3027
```
- **How can i add sid use and examples?**
  
This is how we do it :)
````md
# HAS_MODEL_LOADED
- **Side:** Client

## Declaration
```cpp
// 0x4E61480A
bool HAS_MODEL_LOADED(int modelHashKey);
```

### Arguments
- **int:** modelHashKey

### Results
- **bool**

## Description
Return if a model is in memory.

```lua
Game.HasModelLoaded(model)
```

```squirrel
Game.HasModelLoaded(model);
```
````
