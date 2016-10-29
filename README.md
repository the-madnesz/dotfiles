# README #

Welcome to my dotfile repository. Right now, there's only a configuration for Vim.
This is mainly meant for personal usage.

### What if I want the exact same dotfiles? ###

#### Dependencies ####
- Linux or macOS (It might work in cygwin or Bash on Windows, but idk)
- Gnu Stow (availible in your package manager (Linux) or in Homebrew (Mac))
- Vim 7.4+
- The Solarized theme set up in your terminal
 
#### Setup ####
First, clone this repo:

    git clone https://github.com/tcarbonclocks/dotfiles ~/dotfiles
    
After that, you can just use Stow for the symlinking. For example:

    stow ~/dotfiles/vim

will use stow to symlink the correct configuration files.

A script is included to install vim-plug. After installing vim-plug, don't forget to run :PlugInstall.
