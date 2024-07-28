# Prerequirements:
- vimplug installed
  - using ```sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'```
- neovim installed
  - using ```sudo snap install neovim``` -> snap can be installed bu using ```sudo apt install snap```
- nerdfonts installed

# Installation:
- clone the repository to your config directory (~/.config/nvim)
```cd ~
mkdir ~/.config && cd ~/.config
git clone https://github.com/Auresol/nvim-config.git
mv nvim-config nvim
```
- run ```PlugInstall``` in neovim

# If coc give error "build/index.js not found"
- run ```:call coc#util#install()``` to install all required dependency
