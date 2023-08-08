# vimrc
Vim &amp; Neovim configuration for me.
&nbsp;
## How to use
### Create settings directory
```bash
mkdir -p ~/.vim ~/.vim/autoload ~/.vim/backup ~/.vim/colors ~/.vim/plugged
```
### Set color scheme
```bash
cd ~/.vim/colors
curl -o molokai.vim https://raw.githubusercontent.com/tomasr/molokai/master/colors/molokai.vim
```
### Install vim plugin manager (vim-plug)
```bash
curl -fLo ~/.vim/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```
### Initialize plugin manager
```vim
:PlugInstall
```
