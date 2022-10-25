# Truong's Nvim
----------------------------------------------------------
# Screenshots
<img src="https://github.com/NT912/MyNvimNew/blob/main/img/Screen%20Shot%202022-10-24%20at%2021.07.18.png">
<img src="https://github.com/NT912/MyNvimNew/blob/main/img/Screen%20Shot%202022-10-24%20at%2021.09.59.png">
<img src="https://github.com/NT912/MyNvimNew/blob/main/img/Screen%20Shot%202022-10-24%20at%2021.08.16.png">
<img src="https://github.com/NT912/MyNvimNew/blob/main/img/Screen%20Shot%202022-10-24%20at%2021.08.30.png">

# Requirements
- Neovim (version >= 0.6.0 or nightly version), run nvim -v to check neovim version.
- A terminal that supports [nerdfonts.](https://github.com/ryanoasis/nerd-fonts)

# Installation
Step 1: Install packer.nvim for install and manage the plugins:
```
git clone https://github.com/wbthomason/packer.nvim ~/.local/share/nvim/site/pack/packer/start/packer.nvim
```
Step 2: Run these following commands:
```
rm -rf ~/.config/nvim
git clone https://github.com/NT912/MyNvimNew.git ~/.config/nvim
```
Step 3: Run this following command:
```
nvim +PackerInstall
```
Step 4: Chose Y to install this Nvim and wait your computer to work.

Step 5: Done!

# LSP Configuration
1. Install LSP language servers with `npm`:
```
sudo npm install -g bash-language-server pyright vscode-langservers-extracted typescript typescript-language-server
```
2. Install additional packages for plugins support:

C, C++:

 - [clang](https://clangd.llvm.org/installation.html) for use LSP with [clangd.](https://github.com/neovim/nvim-lspconfig/blob/master/doc/server_configurations.md#clangd)
 - [ctags](https://github.com/universal-ctags/ctags) to view tags with [Tagbar.](https://github.com/preservim/tagbar)

Python:

 - [pynvim](https://github.com/neovim/pynvim)

3. Open a source file of one of the supported languages with Neovim, and run command [:LspInfo](https://github.com/neovim/nvim-lspconfig#built-in-commands) for testing the LSP support.

Languages Currently Supported

 Lua - [builtin](https://neovim.io/doc/user/lua.html)

 Bash - [bashls](https://github.com/neovim/nvim-lspconfig/blob/master/doc/server_configurations.md#bashls)

 Python - [pyright](https://github.com/neovim/nvim-lspconfig/blob/master/doc/server_configurations.md#pyright)

 C, C++ - [clangd](https://github.com/neovim/nvim-lspconfig/blob/master/doc/server_configurations.md#clangd)

 HTML, CSS, JSON - [vscode-html](https://github.com/neovim/nvim-lspconfig/blob/master/doc/server_configurations.md#html)
 
 JavaScript, TypeScript - [tsserver](https://github.com/neovim/nvim-lspconfig/blob/master/doc/server_configurations.md#tsserver)

# Optional

You can see more keymaps at the file path: `~/.config/nvim/lua/core/keymaps.lua` or more file in my config.

