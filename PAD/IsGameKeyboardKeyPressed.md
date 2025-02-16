# IS_GAME_KEYBOARD_KEY_PRESSED
- **Side:** Client

## Declaration
```cpp
// 0x5FA96262
boolean IS_GAME_KEYBOARD_KEY_PRESSED(int key);
```

### Arguments
- **int:** key

### Results
- **boolean**

## Description
Checkes if X button has been released

```lua
Thread.Create(function()
    while true do
        Thread.Pause(0)

        -- This code spawns a SultanRS when the player presses the F1 key.
        if Game.IsGameKeyboardKeyJustPressed(59) then
            local model = Game.GetHashKey("SULTANRS")

            local x, y, z = Game.GetCharCoordinates(Game.GetPlayerChar(Game.GetPlayerId()))
            local heading = Game.GetCharHeading(Game.GetPlayerChar(Game.GetPlayerId()))

            Game.RequestModel(model)

            while not Game.HasModelLoaded(model) do
                Thread.Pause(0)
            end

            local car = Game.CreateCar(model, x, y, z, true)
            Game.SetCarHeading(car, heading)
            Game.SetCarOnGroundProperly(car)

            Game.WarpCharIntoCar(Game.GetPlayerChar(Game.GetPlayerId()), car)

            Game.MarkModelAsNoLongerNeeded(model)
            Game.MarkCarAsNoLongerNeeded(car)
        end
    end
end)
```

```squirrel
Thread.Create(function() {
    while (true) {
        Thread.Pause(0);

        // This code spawns a SultanRS when the player presses the F1 key.
        if (Game.IsGameKeyboardKeyJustPressed(59)) {
            local model = Game.GetHashKey("SULTANRS");

            local pos = Game.GetCharCoordinates(Game.GetPlayerChar(Game.GetPlayerId()));
            local heading = Game.GetCharHeading(Game.GetPlayerChar(Game.GetPlayerId()));

            Game.RequestModel(model);

            while (!Game.HasModelLoaded(model)) {
                Thread.Pause(0);
            }

            local car = Game.CreateCar(model, pos[0], pos[1], pos[2], true);
            Game.SetCarHeading(car, heading);
            Game.SetCarOnGroundProperly(car);

            Game.WarpCharIntoCar(Game.GetPlayerChar(Game.GetPlayerId()), car);

            Game.MarkModelAsNoLongerNeeded(model);
            Game.MarkCarAsNoLongerNeeded(car);
        }
    }
});
```