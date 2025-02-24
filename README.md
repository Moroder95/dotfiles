# My dotfiles

This directory contains the dotfiles for my system

## Requirements

Ensure you have the following installed on your system

### Stow

```
brew install stow
```
(depending on OS I use)

## Installation

First, check out the dotfiles repo in your $HOME directory using git

```
$ git clone git@github.com/Moroder95/dotfiles.git
$ cd dotfiles
```

then use GNU stow to create symlinks

```
$ stow .
```

Check [dreamsofautonomy's video on stow](https://www.youtube.com/watch?v=y6XCebnB9gs&ab_channel=DreamsofAutonomy)
