# Space Whiskey
An Open Game Launcher

## What is Space Whiskey
Space Whiskey is a game launcher for the Raspberry Pi and other systems.
It is designed to allow you to browse your games easily with only the addition of a simple config file.
It provides this functionality without the need to install any external libraries.

## How it Works
- Looks in the Games folder of the current user
- Looks in each folder for a metadata.json file
- Lists the games in a minimal user interface
- Provides a simple way to launch any of the games

## Sample metadata.json
This file should be included in your game directory:
```
{
  "title": "My Game",
  "description": "A great game",
  "image": "200x120-image-for-game.png*",
  "command": "start command for game"
}
```

* Must be either png or gif
