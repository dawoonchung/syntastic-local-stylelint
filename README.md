# Local Stylelint for Syntastic
A simple plugin to load local Stylelint.

Installation Instructions
-------------------------
Using [Pathogen](https://github.com/tpope/vim-pathogen):
Clone this repository into `~/.vim/bundle`

Using [Vim plug](https://github.com/junegunn/vim-plug):
Add `Plug 'dawoonchung/syntastic-local-stylelint.vim'` to your vim-plug configuration file.

Note
----
This plugin *does not* enable Stylelint. You still need to add
```
let g:syntastic_css_checkers = ['stylelint']
```
and/or
```
let g:syntastic_scss_checkers = ['stylelint']
```
to enable the syntax checker for CSS and/or SCSS.

Thanks
------
Original work done by [@mtscout6](https://github.com/mtscout6/syntastic-local-eslint.vim).
