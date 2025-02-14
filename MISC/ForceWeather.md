# FORCE_WEATHER
- **Side:** Client

## Declaration
```cpp
// 0x7EFB5077
void FORCE_WEATHER(uint weather);
```

### Arguments
- **uint:** weather

## Description
Force sets weather in game
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
Game.ForceWeather(0)
```

```squirrel
Game.ForceWeather(0);
```