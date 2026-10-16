# ChickenFPS

A 2D space shooter built in C# Monogame. Designs based on https://www.youtube.com/@Oyyou. Inspired by game series Chicken Invaders.

## Installation

With Visual Studio:

```powershell
cd C:\Users\%user%\Documents\GitHub\ChickenFPS
dotnet run --project .\ChickenFPS\HyVo_ChickenFPS.csproj --launch-profile HyVo_ChickenFPS
```

## Usage

https://youtu.be/KHgl4HLKW8s

| Feature | Description |
|---------|-------------|
| **Mode** | 2D space shooter supporting singleplayer or two players sharing a keyboard. |
| **Player 1 Controls** | WASD to move, Space to shoot. |
| **Player 2 Controls** | Arrow keys to move, Enter to shoot. |
| **Shooting** | Hold the shoot key to fire approximately every 0.25 seconds. |
| **Player Health** | Each player starts with 10 health. |
| **Damage** | Enemy bullet: -1 health. Chicken collision: -3 health. |
| **Enemies** | Red and blue chickens spawn from the right approximately every 2.5 seconds. |
| **Enemy Movement** | Chickens move left at randomized speeds and disappear after leaving the screen. |
| **Enemy Limit** | Maximum of 10 chickens on screen at once. |
| **Enemy Health** | Each chicken has 10 health. |
| **Bullet Damage** | Each player bullet deals 1 damage. |
| **Scoring** | Destroying a chicken awards 1 point to the shooter. Colliding with a chicken also removes it and awards 1 point. |
| **Game Over** | When all players are dead, each player's score is saved and the high-score screen opens. |
| **Exit Game** | Press Escape to return to the menu without normally saving the current run. |

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.