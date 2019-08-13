# rbxlx-to-rojo
Tool to convert existing Roblox games into Rojo projects by reading their `rbxlx` place files.

# Using rbxlx-to-rojo
## Setup
Before you can use rbxlx-to-rojo, you need at least Rojo 0.5.0 Alpha 12 to use the tool.
You also need a rbxlx place file that has a script. If there aren't any scripts in the rbxlx file, rbxlx-to-rojo will return an error.

Download the latest release of rbxlx-to-rojo here: https://github.com/rojo-rbx/rbxlx-to-rojo/releases
## Porting the game
Let's assume we have a rbxlx file named "game", with a script in ServerScriptService.

### Steps to port the game:
1. Double-click on rbxlx-to-rojo on wherever you installed it.
2. Select a place file.
3. Select the path where you want to place it.

If you followed the steps correctly, you should see something that looks like this:
![](assets/folder.png)

Congratulations, you successfully ported an existing game using rbxlx-to-rojo!

## License
rbxlx-to-rojo is available under The Mozilla Public License, Version 2. Details are available in [LICENSE.md](LICENSE.md).
