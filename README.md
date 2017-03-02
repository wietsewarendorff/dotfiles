# Ubuntu 16.04 setup

## Add repos & update
```sh
sudo apt-add-repository ppa:jtaylor/keepass
sudo add-apt-repository ppa:martin-frost/thoughtbot-rcm
sudo add-apt-repository ppa:webupd8team/sublime-text-3

sudo apt-get update
```

## install tools
```sh
sudo apt-get install cowsay dnsmasq filezilla fortune-mod git grc keepass2 mysql-workbench nautilus-dropbox rcm silversearcher-ag sublime-text-installer terminator unity-tweak-tool zsh-antigen
```

manual download and install:

- chrome: https://www.google.com/chrome/browser/desktop/
- spotify: https://www.spotify.com/nl/download/linux/
- docker-compose: https://docs.docker.com/compose/install/
- command-line fuzzy finder: https://github.com/junegunn/fzf

## remove unwanted software
```sh
sudo apt remove aisleriot cheese gnome-mahjongg gnome-mines gnome-sudoku imagemagick remmina rhythmbox shotwell simple-scan thunderbird transmission-common vino xterm
```

## cleanup
```sh
sudo apt autoremove
```

## setup
clone dotfiles-repo in home dir (~/dotfiles) and use it:

```sh
lsrc -d ~/dotfiles
rcup -v -d ~/dotfiles
```
