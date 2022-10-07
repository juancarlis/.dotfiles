# Running NeoVIM with LUA

## Install Vim and Neovim
**Debian**
```
sudo apt install vim neovim
```
**Arch**
```
sudo pacman -Syu vim neovim
```

## Remove packer_compiled.lua file if exists:
```bash
rm ~/.config/nvim/plugin/packer_compiled.lua
```

## Install Packer
Follow the installation guide in the repository:
https://github.com/wbthomason/packer.nvim

## Clean, updates and compiles plugins
PackerSync
