# Install

git clone git@github.com:davidlbatey/dotfiles.git ~/dotfiles

Add:
. ~/dotfiles/bashrc
To:
~/.bashrc

Add:
if [ -f ~/.bashrc ];
then
  source ~/.bashrc
fi
To:
~/.bash_profile
