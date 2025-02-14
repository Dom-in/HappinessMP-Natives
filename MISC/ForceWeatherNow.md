# FORCE_WEATHER_NOW
- **Side:** Client

## Declaration
```cpp
// 0x63737D31
void FORCE_WEATHER_NOW(uint weather);
```

### Arguments
- **uint:** weather

## Description
Force instant weather in the game
0 - Extra sunny
1 - Sunny
2 - Sunny and windy
3 - Cloudy
4 - Raining
5 - Drizzle
6 - Foggy
7 - Thunderstorm
8 - Extra sunny 2
9 - Sunny and windy 2

```lua
Game.ForceWeatherNow(0)
```

```squirrel
Game.ForceWeatherNow(0);
```