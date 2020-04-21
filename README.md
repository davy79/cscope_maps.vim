cscope_maps.vim
===============

My revision to vim plugin cscope_maps.vim with some personal tweaks

# Installation

## Vundle

1. Add `Bundle davy79/cscope_maps.vim` to .vimrc
2. Run `:BundleInstall`

# Features

## Auto update cscope database

- Auto load cscope database (recursive) on startup.
- Auto update cscope database after saving a buffer.
  - added support for makefile cscope target for project specific file collection

## More key mappings

Borrowing some useful key mappings from gtags-cscope.vim.

