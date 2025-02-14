# GET_DRIVER_OF_CAR
- **Side:** Client

## Declaration
```cpp
// 0x22457083
void GET_DRIVER_OF_CAR(Vehicle vehicle);
```

### Arguments
- **Vehicle:** vehicle

### Results
- **Ped*:** pPed

## Description
Tells you who is the driver of the car

```lua
local currentCar = Game.GetCarCharIsUsing(Game.GetPlayerChar(Game.GetPlayerId()))
if Game.GetDriverOfCar(currentCar) == Game.GetPlayerChar(Game.GetPlayerId()) then
    Game.DeleteCar(currentCar)
end
```

```squirrel
local currentCar = Game.GetCarCharIsUsing(Game.GetPlayerChar(Game.GetPlayerId()))
if (Game.GetDriverOfCar(currentCar) == Game.GetPlayerChar(Game.GetPlayerId())) {
    Game.DeleteCar(currentCar);
}
```