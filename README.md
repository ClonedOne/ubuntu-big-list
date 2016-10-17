# Ubuntu big list of stuff I like
The big list of things I (probably you too) really want on Ubuntu.

I'm making this list since in the last few weeks I've switched to Ubuntu as "main os" and by using it I've stumbled upon a lot of good software which made my system run waaay better than it did at the beginning. 

I'm by no means a pro linux user (I'm working on it) so this list is just a check list for myself when a format/reinstall is due. I will leave it here because I believe it may be useful for n00bs like myself, who need to work with Linux and do not know how to make it look good and feel smooth.

This is just the first attempt at the list, it will grow with time and, hopefully, get better.
Anyone having an opinion/comment on how to make Ubuntu a better place to live, should feel totally free to propose anything :)

####Ok lets start with the graphics.
The default theme and icons are ugly. I mean, it's obviously just my optinion, but yeah it's really ugly, sorry.

* Install [Unity Tweak Tool](https://apps.ubuntu.com/cat/applications/unity-tweak-tool/). I find it way easier to use than compiz. You can find it in Ubuntu's own sw center.
* To make it definetely better my standard approach is to use the [arc-theme](https://github.com/horst3180/arc-theme). Arc darker is so nice.
* As icon pack I usually go with [numix-circle](http://me4oslav.deviantart.com/art/Numix-Circle-Linux-Desktop-Icon-Theme-414741466).
* Do change default wallpaper.

####Launchers and flashy stuff

Again, totally my own opinion, but the default launcher may need some revamping.

* Install [Albert](https://github.com/ManuelSchneid3r/albert). Yep, it's like alfred but with less Batman's money. Use Arc Dark theme (really).
* Make ubuntu standard launcher disappear, using system's settings, and bind Albert to comfortable shortcut.
* Add Wikipedia and other useful search engines in Albert configuration, select folders to index and enjoy the magicx.

####Terminal and Shell

* [Guake](https://github.com/Guake/guake) is really good. Really. Use Solarized Dark theme, 20% transparency, and fullscreen. Uh and remove tab bar on the bottom. Really, do it, fast.
* Install [zsh](http://www.zsh.org/) if you don't already have it. `$ chsh zsh` will be needed.
* Install [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh). Remember to set plugins (don't forget `z`).
* As theme I use [Bullet Train](https://github.com/caiogondim/bullet-train-oh-my-zsh-theme).
* You will need some powerline [font](https://github.com/powerline/fonts) for the theme to work properly.
* [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) is a very helpful/colorful plugin to import, you will want it.
* If not already there, install [tmux](https://tmux.github.io/). An easy example configuration file for tmux is in my [dotfiles repo](https://github.com/ClonedOne/c1-dotfiles), but you can probably find better examples online.

####Command line utilities

* `cat` is useful, like a whole lot. But again, it's ugly. Solution: install [python-pygments](http://pygments.org/) and alias `pygmentize -g` to `ccat`.
* [fzf](https://github.com/junegunn/fzf) is another valuable tool which you may want. It replacese stard command search in terminal with a cooler fuzzy apporach.
* If you happen to work with ssh install `sshfs` using `apt`.
* Use [GNU Stow](https://www.gnu.org/software/stow/) to manage configuration files.
* To record and share terminal sessions over the interwebz go with [asciinema](https://asciinema.org/). It's fun and way more useful than it seems.
* [ranger](https://github.com/ranger/ranger) is a very nice file manager which works directly in the temrinal.

####System status

* Install `lm-sensors` and `hddtemp` using `apt` to monitor system temperature. 
* `powertop` and [`tlp`](http://linrunner.de/en/tlp/tlp.html) are useful to keep and eye on the power usage.

####Random stuff

* Workspaces are great. The icon is quite ugly. There is no way from system settings to remove the icon without removing workspaces. To achieve that follow this [guide](http://askubuntu.com/questions/38789/how-do-i-add-and-remove-the-workspace-switcher-launcher-from-the-unity-launcher)
