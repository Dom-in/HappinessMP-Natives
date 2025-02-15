# GET_CAR_MODEL
- **Side:** Client
## Declaration
```cpp
// 0x5FF84497
void GET_CAR_MODEL(int vehicleIndex, int* modelHashKey);
```

### Arguments
- **int:** vehicleIndex

### Results
- **int*:** modelHashKey

## Description
Get the model hash for the car.

```lua
Game.GetCarModel(carWashState.car)
```

```squirrel
Game.GetCarModel(carWashState.car);
```