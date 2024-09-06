# vscode-vim-settings
My personal setup for a good mixture of vim and vs code hotkeys.

The standard vim extension is blocking too many vs code hot keys for me, e.g `ctrl + k` cannot open the file finder anymore.  

*We use shortcuts defined either for vim, or defined for vs code directly.* Therefore the config is split in:
* Vim shortcuts: settings.json
* Vs code shortcuts: keybindings.json

Both are in the user settings, **not** in the workspace settings. Those can be found under:</br>
	-	Windows: `%APPDATA%\Code\User\` </br>
	-	macOS: `$HOME/Library/Application Support/Code/User/` </br>
	-	Linux: `$HOME/.config/Code/User/` </br>
