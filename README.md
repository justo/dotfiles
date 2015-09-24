# dotfiles
My OS X dotfiles with help from [mathiasbynens](https://github.com/mathiasbynens/dotfiles) and many others.

###Installation
1. Install [Homebrew](http://brew.sh/)
2. Run `./brew.sh`
2. Install [NVM](https://github.com/creationix/nvm) (follow manual install)
4. Install [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)
5. Run `./dotfiles.sh` to symlink all dotfiles to $HOME. Files **won't** be overridden, so watch out. Safe to run repeatedly if needed.

#####Optional
`./osx_settings.sh` and then reboot. _Ignore for now_

Install [RVM](https://rvm.io/)

#####Tips
Check your git --version

#####Manual Installs:
* ~/.gitconfig (contains private token)


#####TODO:
* set src files to open with bash syntax highlighting
* keep a list of npm -g somewhere
	* maybe even a list of /repositories
* ~~integrate brew.sh~~
* quicklook extensions
* automate manual installs?
* sublime text and atom configs
* finish osx script (set hot-corners, )
* alfred configs?
* Terminal app config, with fonts
* set default login shell?
* make sure permissions are in order



Helpful links:

[dotfiles and github faq](https://dotfiles.github.io/)
