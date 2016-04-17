# My personal dotfiles

Works for OSX and Linux

## Installing

```
git clone git@github.com:ksarunas/dotfiles.git ~/dotfiles
cd ~/dotfiles/install
chmod +x *
```

### Stuff of your choice

```
./sublime.sh
./sublime-ruby-test.sh
./git.sh

# requires rbenv to be installed
./rbenv-rehash.sh
./rbenv-default-gems.sh

# node
./node-npm.sh
```

### Bash/Zshrc profile

Append your `.bash_profile`/`.zshrc` file with:

```
# dotfiles
source "$HOME/dotfiles/bashrc/sources/terminal"
source "$HOME/dotfiles/bashrc/sources/ctags"
source "$HOME/dotfiles/bashrc/sources/git"
source "$HOME/dotfiles/bashrc/sources/postgres"
source "$HOME/dotfiles/bashrc/sources/rbenv"
source "$HOME/dotfiles/bashrc/sources/ruby"
source "$HOME/dotfiles/bashrc/sources/npm"
```
