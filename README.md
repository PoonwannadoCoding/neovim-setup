# neovim-setup

Installation Step

Go to root dir

```
cd ~
```

Then
```
mkdir .config
cd .config
mkdir nvim
cd nvim
```
After that copy file into the folder then run this in the terminal
```
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```
After that 
```
nvim nvim.vim
```
Then we type
```
:PlugInstall
```
Then finish
