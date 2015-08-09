# Snippets for Vim

## Description

The **vim-snippets** repository contains a collection of code snippets for **Vim**. In particular, it contains snippets for the following snippet engines:

* [snipMate](https://github.com/msanders/snipmate.vim)
* others in the future

It has been specialized for C and php, containing snippets for every standard function. Other languages are available to a different degree of completeness.

## Installation

### Vundle

Add the following lines to your **~/.vimrc**:

    Bundle 'chilicuil/vim-snippets'
    let g:snippets_dir = "~/.vim/bundle/vim-snippets/snipmate/"

Then run the following command in Vim:

    :BundleInstall

The snippets are loaded immediately if snipMate is active.
