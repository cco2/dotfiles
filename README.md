# dotfiles
## nvim
1. Install prereqs
```
sudo dnf install -y ripgrep neovim

git clone --depth 1 https://github.com/wbthomason/packer.nvim\
 ~/.local/share/nvim/site/pack/packer/start/packer.nvim
```
1. Create symlink from `nvim` directory to `~/.config/nvim`
1. Enter nvim on `packer.lua`, `:so`, `:PackerSync` to obtain the packer modules

