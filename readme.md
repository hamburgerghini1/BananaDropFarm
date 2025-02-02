# Banana Drop Farm

## About the installer
Remember to launch it as admin if you installed it to Program Files etc...

## Description
Banana Drop Farm is a game cheat for game Banana. This cheat can change the score in the game, bypass the idle bot check, spoof cps and much more.

## Showcase
![Showcase Image](/img/menu_v1.7.png)
![Showcase Image](/img/menu_v1.7_misc.png)

## Installation
For users who want to build the menu to a .exe, run `build.bat`. For users who want to use the source code, simply run `setup.bat` and then `python menu.py`.

## Prerequisites
- `pymem==1.13.1`
- `PyYAML==6.0.1`
- `psutil==5.9.8`
- `customtkinter==5.2.2`
- `pyinstaller` (optional, for those who want to build to .exe)

You can also install the dependencies listed in `requirements.txt`.

## Features
- **Score Changer**: Changes the score.

- **Reset Score**: Resets the score.

- **Bot Idle Check Bypass**: Bypasses the bot idle check.
    - **Bypass Methods**:
        - **Random increment** - Adds a random number from 1 to 25 to the current score.
        - **Random value** - Changes the current score to a random value.
        - **Increment** - Adds 1 to the current score.
    - **Delay** - Allows you to add a custom delay between executing selected method.

- **Spoof Cps**: Spoofes the cps.
    - **Spoof Methods**:
        - **Random** - Sets a random cps value.
        - **Random normal** - Sets a random cps value from 1 to 20.
        - **Static** - Sets a static cps value of 15.

- **Idle Timer Reset**: Automatically resets the game's internal idle timer every 5 seconds, preventing AFK detection.

- **Main Asset Changer**: Changes the main asset.

- **Drop Timer Changer**: Changes the drop timer.

- **Game Options**:
    - Open Game
    - Close Game
    - Crash Game
    - Restart Game

- **Fix Options**:
    - Fix Drop Timer - Fixes the drop timer
    - Fix Main Asset - Fixes the main asset

- **Multiple Banana Process Support**: Now supports handling multiple instances of the game.

- **Config Saving and Loading**: Save and load configurations to and from YAML files.

## Script: `multiplesteaminstances.py`
This script allows running multiple instances of Steam. It generates a batch script to start multiple Steam instances with unique IPC names.
- **Note**: Ensure you are logged out of Steam and fully exit Steam before running the generated `multiple_steam_instances.bat` script to avoid conflicts.
- **Usage**:
    - Run `multiplesteaminstances.py`.
    - Select the `steam.exe` file.
    - Enter the number of Steam instances to run (1-10).
    - A batch script will be created to start the specified number of Steam instances.

## Contributing
The project is open to contributors. Feel free to open an issue or submit a pull request.

## License
This project is licensed under the [GNU General Public License v3.0](https://opensource.org/license/GPL-3.0).
