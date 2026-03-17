# dotfiles
## dependencies
- Arch ISO: https://ftp.halifax.rwth-aachen.de/archlinux/iso/latest/
- installation
  - `loadkeys de-latin1`
  - `archinstall`
    - linux-lts kernel
    - pipewire
- reboot and login
  - `sudo pacman -S zsh`
  - `chsh -s /usr/bin/zsh`
  - OhMyZsh: `sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`
    - DOTFILES
  - `sudo pacman -S curl git vim`
  - `sudo pacman -S hyprland`
