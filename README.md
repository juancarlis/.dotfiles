# Dotfiles
My dotfiles

The directory structure used in this repository was thought so as to 
use stow to generate the symlinks to the home directory.


## Install stow
**Debian based**
```bash
sudo apt install stow
```
**Arch based**
```bash
sudo pacman -Syu stow
```

## Clone the repository on the user's home directory: /home/user/.dotfiles
```bash
git clone https://github.com/juancarlis/.dotfiles.git
```

## Run stow command to generate the symlinks
```bash
cd .dotfiles
stow .
```

## Edit ZSH configuration

### Install Oh-My-Zsh
**Ubuntu**
```bash
sudo apt install wget curl zsh

sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
*Zsh docs: https://github.com/ohmyzsh/ohmyzsh/wiki*

Move plugins to ZSH local plugin folder
Example in Manjaro
```bash
mv zsh_plugins/* /usr/share/zsh/plugins
```
Add to .zshrc:
```
source ~/.zsh_plugins/git/git.plugin.zsh
source ~/.zshrc_aliases
```

#### Install Powerlevel10k
*https://github.com/romkatv/powerlevel10k*

#### Make zsh default
Command (without sudo)
```bash
chsh -s $(which zsh)
```
Log out and log in back


## View markdown files from terminal
```bash
sudo apt install pandoc lynx -y
```
