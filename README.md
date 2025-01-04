# Nvim theme with Lualine and Nvim-Tree
This configuration provides a basic, user-friendly setup for `Neovim` with customized `lualine` and `Nvim-Tree`. If you're someone new to neovim or vim in general this would be a great starter template to begin your `vim` journey with. 

## Features
- **Ayu Theme**: Uses the Ayu theme - https://github.com/ayu-theme/ayu-vim

```markdown
![Default ayu-dark preview](Image_URL)
```

- **Lualine:** Employs a `slanted-gaps` theme with customized colors - https://github.com/nvim-lualine/lualine.nvim

```markdown
![Status Line Preview](Image_URL)
```

- **Nvim-Tree:** Integrates Nvim-Tree for navigation - https://github.com/nvim-tree/nvim-tree.lua.

```markdown
![Nvim-Tree Preview](Image_URL)
```

- **Note**: The font used is https://www.jetbrains.com/lp/mono/. 

## Pre-requisite
- Current stable version of `neovim` - https://neovim.io.
- `vim-plug` : package manager for neovim. Installation : https://github.com/junegunn/vim-plug
- Works when you have a terminal that supports a `termguicolors`. If your using `iterm2` or `warp` you should be fine. Does not work with default terminal.

## Installation
- Clone the repositry using `git clone https://github.com/rakshith077-bn/PEFT/edit/main/README.md`
- Delete the README.md using `rm -rf README.md`
- Assuming you have created a **~/.config/nvim** directory. Move the `init.vim` file to the directory with `mv init.vim ~/.config/nvim`
- Install the required plugins with `:PlugInstall` run as a nvim command
