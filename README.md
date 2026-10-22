# Dotfiles

Personal dotfiles for a lightweight Linux environment.

## Overview

This repository contains my personal system configuration files for a fast and minimal workflow.

* OS: Linux Mint
* Window Manager: Openbox (openboxWM)
* Panel: xfce4-panel
* Wallpaper Setter: feh

## Repository Structure

* bashrc - Shell configuration, aliases, and environment variables.
* xinitrc - Startup script for X session, Openbox, and feh wallpaper setup.
* README.md - Documentation for this repository.
* .gitignore - List of files ignored by Git.

## Setup Instructions

1. Clone the repository:
   git clone https://github.com/your-username/dotfiles.git

2. Create symlinks to your home directory:
   ln -s ~/dotfiles/bashrc ~/.bashrc
   ln -s ~/dotfiles/xinitrc ~/.xinitrc

3. Reload bash configuration:
   source ~/.bashrc

## License

This project is free to use and modify for personal setups.
