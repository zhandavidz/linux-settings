# linux-settings

## ssh

### ssh keys

follow [this guide](https://www.digitalocean.com/community/tutorials/ssh-essentials-working-with-ssh-servers-clients-and-keys) to do ssh keys

## vim

### settings

use the settings in `.vimrc`, you should be able to edit the settings with:
```
vim ~/.vimrc
```

### theme

Atom's One Dark Theme - [main link](https://vimcolorschemes.com/joshdick/onedark.vim) - [github link](https://vimcolorschemes.com/joshdick/onedark.vim)

Some help with installing: [stackexchange might help](https://apple.stackexchange.com/questions/243078/where-is-the-folder-with-color-schemes-used-by-vim)

You may have to create the `~/.vim/colors` and `~/.vim/autoload` folders, can run:
```
mkdir -p ~/.vim/colors
```
and
```
mkdir -p ~/.vim/autoload
```
and use `sftp` to put the files in. You really only need the files in the github in `colors/onedark.vim` and `autoload/onedark.vim`

#### better syntax highlighting

Install `vim-polyglot` from [the github](https://github.com/sheerun/vim-polyglot), can copy paste this link

```
git clone --depth 1 https://github.com/sheerun/vim-polyglot ~/.vim/pack/plugins/start/vim-polyglot
```
