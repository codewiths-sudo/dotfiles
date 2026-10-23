# Dotfiles

My personal dotfiles for a minimal and lightweight Linux environment.

## System Details

* OS: Linux Mint 22.3 (zena)
* Window Manager: Openbox(openbox-wm)
* Status Bar: Polybar
* Wallpaper Setter: feh

``` File Structure
├── .bashrc
├── .xinitrc
├── README.md
└── config/
├── openbox/
└── polybar/
```
## Installation

1. Clone the repository into your home directory:

```bash
git clone [https://github.com/codewiths-sudo/dotfiles.git](https://github.com/codewiths-sudo/dotfiles.git)
```

## Create symlinks for the main dotfiles:

```ln -sf ~/dotfiles/.bashrc ~/.bashrc
   ln -sf ~/dotfiles/.xinitrc ~/.xinitrc
```

### .xinitrc starts Openbox and essential background processes.

### Polybar and feh are launched along with the Openbox session.


## License

This repository is unlicensed - see the [LICENSE](LICENSE) file for details.

---
