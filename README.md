# neovim-setup
my neovim setup

### setup neovim on debian
```shell
# install neovim
sudo apt install neovim

# install vim-plug
curl -fLo ~/.local/share/nvim/site/autoload/plug.vim --create-dirs \
 https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim

# create a neovim config directory
mkdir ~/.config/nvim
```

### get the config
```
curl -o ~/.config/nvim/init.vim https://raw.githubusercontent.com/xamfy/neovim-setup/master/init.vim
```

### To install plugins using vim-plug
```
nvim +PlugInstall
```

### Install Ubuntu Nerd Font complete
Download font from [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts/tree/master/patched-fonts/Ubuntu/Regular/complete) and install.

### Coc extensions
[Using Coc extensions](https://github.com/neoclide/coc.nvim/wiki/Using-coc-extensions)

### For C++ install clangd language server
```
sudo apt install clangd-10
```
