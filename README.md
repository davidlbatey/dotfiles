# Install

git clone git@github.com:davidlbatey/dotfiles.git ~/dotfiles

## Bash

Add:

```
. ~/dotfiles/bashrc
```

To:
~/.bashrc

Add:

```
if [ -f ~/.bashrc ];
then
  source ~/.bashrc
fi
```

To:
~/.bash_profile

To set up the vim files

## Vim

link to the vim files

```
  ln -s ~/dotfiles/vim ~/.vim
  ln -s ~/dotfiles/vimrc ~/.vimrc
  ln -s ~/dotfiles/irbrc ~/.irbrc
```
