### Moonlight theme for Wezterm
This is a port of the Moonlight theme for Wezterm. Inspiration from [Koalight](https://github.com/Koalhack/koalight.nvim) and [Moonlight](https://github.com/atomiks/moonlight-vscode-theme)

### Screenshot
![Screenshot](https://raw.githubusercontent.com/jacobrreed/moonlight-wezterm/master/screenshot.png)

### Installation
1. Download the `moonlight.toml` file from this repository and place it in your `~/.config/wezterm/colors` directory. (if it doesnt exist, create it)
2. Add the following to your `~/.config/wezterm/wezterm.lua` file:
```lua
local wezterm = require 'wezterm';
config.color_scheme = "Moonlight"
return config
```