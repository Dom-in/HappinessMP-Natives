# IS_MODEL_IN_CDIMAGE
- **Side:** Client

## Declaration
```cpp
// 0x771C2838
bool IS_MODEL_IN_CDIMAGE(int model);
```

### Arguments
- **int:** model

### Results
- **bool**

## Description
Return if model is available in one of the streaming image files.

```lua
if not Game.IsModelInCdimage(model) then
    Chat.AddMessage("Error: Unknown model")
    return
end
```

```squirrel
if (!Game.IsModelInCdimage(model)) {
    Chat.AddMessage("Error: Unknown model");
    return;
}
```