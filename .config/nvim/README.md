# Running NeoVIM with LUA

## Install Vim and Neovim
**Debian/Ubuntu**
Install vim
```bash
sudo apt install vim
```
Install neovim last stable version
```bash
sudo apt-get install software-properties-common
sudo add-apt-repository ppa:neovim-ppa/stable
sudo apt-get update
sudo apt-get install neovim
```
**Arch**
Install vim and neovim
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
:PackerSync


## LSP Servers

**On Debian**
```bash
sudo apt install npm
apt install python3.10-venv
```

**Use command: ":LspInstallInfo"**
Language servers in use:
- html
- jedi_language_server (python)
- pyright (python)
