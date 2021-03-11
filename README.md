# Vim

Just my vim configuration.

Using pathogen : https://github.com/tpope/vim-pathogen

Clne the repo with all submoules

`git clone --recurse-submodules https://github.com/LexaNz/vim.git .vim`

Add new plugin with git submodule

`git submodule add -b master https://github.com/elzr/vim-json.git  bundle/vim-json`

Add this block to .vimrc to enable pathogen
```
" Enable vim-pathogen
runtime bundle/vim-pathogen/autoload/pathogen.vim
execute pathogen#infect()

```
