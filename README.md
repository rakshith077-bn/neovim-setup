# Nvim theme with Lualine and Nvim-Tree
This configuration provides a basic, user-friendly setup for `Neovim` with customized `lualine` and `Nvim-Tree` for navigation. If you're someone new to neovim editor, this would be a great starter template to begin your `vim` journey with. 

## Features
- **Ayu Theme**: Uses the Ayu theme - https://github.com/ayu-theme/ayu-vim

![Default ayu-dark preview](https://github.com/rakshith077-bn/neovim-setup/blob/main/Photos/default.png)

- **Lualine:** Employs a `slanted-gaps` theme with customized colors - https://github.com/nvim-lualine/lualine.nvim

![Status Line Preview](https://github.com/rakshith077-bn/neovim-setup/blob/main/Photos/visual.png)


![Status Line Preview2](https://github.com/rakshith077-bn/neovim-setup/blob/main/Photos/insert.png)

- **Nvim-Tree:** Integrates Nvim-Tree for navigation - https://github.com/nvim-tree/nvim-tree.lua.

![Nvim-Tree Preview](https://github.com/rakshith077-bn/neovim-setup/blob/main/Photos/NvimTree.png)

- **Note**: The font used in the screenshot is https://www.jetbrains.com/lp/mono/. 

## Pre-requisite
- Current stable version of `neovim` - https://neovim.io
- `vim-plug` : package manager for neovim - https://github.com/junegunn/vim-plug
- Works with a terminal that supports a `termguicolors`. If your using `iterm2` or `warp` you should be fine. Does not work with default terminal.

## Installation
- Clone the repositry using `git clone https://github.com/rakshith077-bn/neovim-setup`
- Assuming you have created a `~/.config/nvim` directory. Move the `init.vim` file to the directory with `mv init.vim ~/.config/nvim`
- Install the required plugins with `:PlugInstall` run as a nvim command.
