![tender](https://cloud.githubusercontent.com/assets/829859/18413534/f7cb472c-77aa-11e6-86bf-9c790aadd2df.png)
==============================================================================================================

A 24bit colorscheme for Vim, Airline and Lightline (generated by [Estilo](http://estilo.jacoborus.codes))


## Installation

Install manually or use a package manager:

```viml
" vim-plug
Plug 'jacoborus/tender'
" NeoBundle
NeoBundle 'jacoborus/tender'
" Vundle
Plugin 'jacoborus/tender'
```

Once your plugin is installed you can set the color scheme in your `.vimrc` or `init.vim`

Enable true color in neovim:

```viml
set termguicolors
```

Enable true color in vim v7.4.1770 or newer:

```viml
set guicolors
```

Fix for MacVim:

```viml
let macvim_skip_colorscheme=1
```

Use colorscheme:

```viml
colorscheme tender
```

Use [lightline](https://github.com/itchyny/lightline.vim) themes ('tender' and 'tenderplus'):

```viml
" enable tender lightline theme
let g:tender_lightline = 1
" set lighline theme (inside lightline config)
let g:lightline = { 'colorscheme': 'tender' }
```

Use [airline](https://github.com/vim-airline/vim-airline) themes ('tender' and 'tenderplus'):

```viml
" enable tender airline theme
let g:tender_airline = 1
" set airline theme
let g:airline_theme = 'tender'
```


## Screenshots

![javascript](https://cloud.githubusercontent.com/assets/829859/15333458/01b57d62-1c6a-11e6-8b2f-94ee49717922.png)
![nerdtree, json and yaml](https://cloud.githubusercontent.com/assets/829859/15333480/1ae0f442-1c6a-11e6-92a1-53fe5a264501.png)
![diff](https://cloud.githubusercontent.com/assets/829859/15333530/4cce7d9e-1c6a-11e6-8a66-f955c2a99681.png)
![lightline](https://cloud.githubusercontent.com/assets/829859/15333539/57e8d710-1c6a-11e6-9809-ef5768ca4103.png)
![gitcommit](https://cloud.githubusercontent.com/assets/829859/15333549/6372bb00-1c6a-11e6-901c-45dbcfc022c5.png)


<br><br>

---

© 2016 [jacoborus](http://jacoborus.codes) - Released under [MIT License](https://raw.github.com/jacoborus/nanobar/master/LICENSE)
