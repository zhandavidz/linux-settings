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

#### Simple Setup

Visit the [GitHub repo for Atom's One Dark Theme](https://github.com/joshdick/onedark.vim/tree/main).

In the repo, download specifically `colors/onedark.vim` and `autoload/onedark.vim`.

Make the `~/.vim/colors` and `~/.vim/autoload` folders by running:
```
mkdir -p ~/.vim/colors
```
and
```
mkdir -p ~/.vim/autoload
```

Use `sftp` to put the files in. First, `lcd` to the current local directory. Then, `put` each `onedark.vim` file in the folders you just made.

#### other one dark setup tools

Atom's One Dark Theme - [main link](https://vimcolorschemes.com/joshdick/onedark.vim) - [github link](https://github.com/joshdick/onedark.vim/tree/main)

Some help with installing: [stackexchange might help](https://apple.stackexchange.com/questions/243078/where-is-the-folder-with-color-schemes-used-by-vim)

### better syntax highlighting

Install `vim-polyglot` from [the github](https://github.com/sheerun/vim-polyglot), can copy paste this link

```
git clone --depth 1 https://github.com/sheerun/vim-polyglot ~/.vim/pack/plugins/start/vim-polyglot
```
