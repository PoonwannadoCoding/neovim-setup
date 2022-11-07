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
exit the init then
```
sudo apt-get install exuberant-ctags
```
For auto complete COC you have to add your language read the website there will have the command to install the command for each language
```
https://github.com/neoclide/coc.nvim/wiki/Using-coc-extensions
```
