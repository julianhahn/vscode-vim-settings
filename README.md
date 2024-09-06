# vscode-vim-settings
My personal setup for a good mixture of vim and vs code hotkeys.

The standard vim extension is blocking too many vs code hot keys for me, e.g `ctrl + k` cannot open the file finder anymore.  

# 1. Add the parts you want to your local settings.json and keyboard.json
*We use shortcuts defined either for vim, or defined for vs code directly.* Therefore the config is split in:
* Vim shortcuts: settings.json
* Vs code shortcuts: keybindings.json

Both are in the user settings, **not** in the workspace settings. Those can be found under:</br>
	-	Windows: `%APPDATA%\Code\User\` </br>
	-	macOS: `$HOME/Library/Application Support/Code/User/` </br>
	-	Linux: `$HOME/.config/Code/User/` </br>

# 2. enable repeating keyboard inputs
   To navigate easy with h,j,k,l and so on we need to enable on macOS the feature for repeated key inputs when holding down a button. As far as I know you can only enable and disable this for one application at a time. Here the command to enable it for vscode: `defaults write -g ApplePressAndHoldEnabled -bool false`. If you are not on mac you can skip this step.
