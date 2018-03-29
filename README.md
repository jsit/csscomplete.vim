Sass Omni Complete Function
===================================

Includes all of othree/csscomplete.vim, plus Sass additions.

Installation
------------

Use pathogen or vundle is recommended. Vundle:

    Plugin 'jsit/sasscomplete.vim'

### Configure

Set `omnifunc` to `sasscomplete#CompleteSass`

    autocmd FileType css,sass,scss setlocal omnifunc=sasscomplete#CompleteSass noci

License
-------

Same as VIM
