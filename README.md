# pyfzf

A small fzf frontend for pacman and yay written in bash.

# Dependencies

* [fzf](https://github.com/junegunn/fzf)
* [yay](https://github.com/Jguer/yay)
* pacman-contrib (optional, for paccache)

# Features

The program contains options to -

* Interactively choose packages in official repo to install.
* Uninstall (recently) installed official or AUR packages.
* Clear uninstalled packages from cache (requires paccache).
* Remove unneeded dependencies.
* Show news from Archlinux homepage.

# Motivation

This utility was created just to ease some of the frequent package management
related tasks.
