Candy Crush Chronicle
==========
A Vim colorscheme for 256 colors terminal and GUI

![screenshot](https://github.com/lleaff/candy-crush-chronicle.vim/blob/resources/candycrushchronicle_screenshot02.png?raw=true)

_Forked from [Lucius](https://github.com/jonathanfilip/vim-lucius) by [jonathanfilip](https://github.com/jonathanfilip)_

### Installation  

###### Using Vundle:

Add this line to your `.vimrc`:  

    Plugin 'lleaff/candy-crush-chronicle.vim'

Then run `vim +PluginInstall +qall`  

###### Manual:

Copy the content of `colors` in `~/.vim/colors/`

###### Usage

    colorscheme candy-crush-chronicle
	" Options:
    let g:candycrushchronicle_term_bg = 1

### Options

* `g:candycrushchronicle_term_bg` (default: `0`)
 
   Use transparent background in terminal.

* `g:candycrushchronicle_use_bold` (default: `1`)
 
   Use bold fonts for some items.
 
* `g:candycrushchronicle_use_underline` (default: `1`)
 
   Use underlined fonts for some items.
