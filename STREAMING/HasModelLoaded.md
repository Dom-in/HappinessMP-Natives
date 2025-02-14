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
while not Game.HasModelLoaded(model) do
    Thread.Pause(0)
end
```

```squirrel
while (!Game.HasModelLoaded(model)) {
    Thread.Pause(0);
}
```