# download
```{bash}
$ mkdir ~/.vim
$ mkdir ~/.vim/bundle
$ git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/vundle
```

# install
```{bash}
$ vi ~/.vimrc
...
" vundle
set nocompatible
filetype off
set rtp+=$HOME/.vim/bundle/Vundle.vim
call vundle#begin('$HOME/.vim/bundle')
Plugin 'VundleVim/Vundle.vim'
call vundle#end()
filetype plugin indent on

:wq

$ vi ~/.vimrc
:PluginInstall
:wq
```

# cmd of vundle
```{text}
:PluginList
:PluginInstall
:PluginSearch
:PluginClean
```
