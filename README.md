# .dotfiles
My dotfiles

The directory structure used in this repository was thought so as to 
use stow to generate the symlinks to the home directory.


## Install stow
**Debian based*
```bash
sudo apt install stow
```
**Arch based*
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
