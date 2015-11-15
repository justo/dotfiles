# dotfiles
My OS X dotfiles with help from [mathiasbynens](https://github.com/mathiasbynens/dotfiles) and many others.

###Installation
1. Install [Homebrew](http://brew.sh/)
2. Run `./brew.sh`
2. Install [NVM](https://github.com/creationix/nvm) (follow manual install)
4. Install [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)
5. Run `./dotfiles.sh` to symlink all dotfiles to $HOME. Files **won't** be overridden, so watch out. Safe to run repeatedly if needed.

#####Optional
`./osx_settings.sh` and then reboot.

Install [RVM](https://rvm.io/)

#####Tips
Check your git --version

#####Manual Installs:
* Global npm packages listed in `src/npm-global-packages.txt`
* Sublime Text config: Contents of `src/sublime` go in `~/Library/Application Support/Sublime Text 3/Packages/User`. Syncing this with Dropbox does not work well. Install ST > Install package control > Move `Package Control.sublime-settings` over, restart ST, wait for packages to install > Quit ST, move rest of preference files > Profit.
* ~/.gitconfig (contains private token)
* OS X Terminal theme at `src/Novel-custom.terminal`
* `dropbox/dropbox-private` contents
* Mac apps
	* [Chrome](https://www.google.com/chrome/), [Canary](https://www.google.com/chrome/browser/canary.html)
	* [Sublime Text](http://www.sublimetext.com/3), [Package control](https://packagecontrol.io/installation)
	* [Firefox](https://www.mozilla.org/en-US/firefox/new/), [Dev edition](https://www.mozilla.org/en-US/firefox/developer/)
	* [Dropbox](https://www.dropbox.com/downloading)
	* [Flux](https://justgetflux.com/news/pages/macquickstart/)
	* [Alfred](https://www.alfredapp.com/) (Dropbox sync)
	* [Notational Velocity](http://notational.net/) _Export settings somehow_
	* [Atom](https://atom.io/), `sync-settings` package
	* [ImageAlpha](https://pngmini.com/)
	* [ImageOptim](https://imageoptim.com/)
	* [The Unarchiver](http://wakaba.c3.cx/s/apps/unarchiver)
	* xScope v3.x
* Fonts
	* [Source Code Pro latest](https://github.com/adobe-fonts/source-code-pro/releases/latest)
	* [Bitstream Vera Mono](http://ftp.gnome.org/pub/GNOME/sources/ttf-bitstream-vera/1.10/)


#####TODO:
* set src files to open with bash syntax highlighting
* ~~keep a list of npm -g somewhere~~ _Can make this better though_
	* ~~maybe even a list of /repositories~~
* ~~integrate brew.sh~~
* quicklook extensions
* automate some manual installs
* ~~sublime text~~ and atom configs
* ~~add fonts for setup to manual part (eg. source code pro)~~
* finish osx script (set hot-corners, )
* ~~alfred configs~~
* ~~Terminal app config, with fonts~~
* set default login shell?
* make sure permissions are in order

#####MAINTENENCE
* npm ls -g --depth=0 > src/npm-global-packages.txt

Helpful links:

[dotfiles and github faq](https://dotfiles.github.io/)
