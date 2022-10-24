# Truong's Nvim
----------------------------------------------------------
# Screenshots
<img src="https://github.com/NT912/MyNvimWithLua/blob/main/ScreenShot/Screen%20Shot%202022-04-28%20at%2010.18.37.png">
<img src="https://github.com/NT912/MyNvimWithLua/blob/main/ScreenShot/Screen%20Shot%202022-04-28%20at%2010.18.59.png">
<img src="https://github.com/NT912/MyNvimWithLua/blob/main/ScreenShot/Screen%20Shot%202022-04-28%20at%2010.19.42.png">

# Requirements
- Neovim (version >= 0.6.0 or nightly version), run nvim -v to check neovim version.
- Tree-sitter.
- Ripgrep.
- A terminal that supports [nerdfonts.](https://github.com/ryanoasis/nerd-fonts)

# Installation
Step 1: Run this following command:
```
git clone https://github.com/wbthomason/packer.nvim ~/.local/share/nvim/site/pack/packer/start/packer.nvim
```
Step 2: Run these following commands:
```
rm -rf ~/.config/nvim
git clone https://github.com/NT912/MyNvimWithLua.git ~/.config/nvim
```
Step 3: Run this following command:
```
nvim +PackerInstall
```
Step 4: Chose Y to install this Nvim and wait your computer to work.

Step 5: Done!

# Optional
If you're a C/C++ programmer, you may want to install `clang` for C/C++ language support. Neovim will provide you some autocompletion, errors, warnings,... when you code C/C++ programs.
