# dotfiles
## prerequisites
- Arch Linux installation: https://ftp.halifax.rwth-aachen.de/archlinux/iso/latest/
  - keyboard layout: `loadkeys de-latin1`
  - install script: `archinstall`
    - kernels: linux-lts, linux
    - audio: pipewire
## dependencies
- installation
  - nvidia: https://wiki.hypr.land/Nvidia/
    - `echo "options nvidia_drm modeset=1" | sudo tee /etc/modprobe.d/nvidia.conf`
    - `sudo vim /etc/mkinitcpio.conf`: MODULES=(nvidia nvidia_modeset nvidia_uvm nvidia_drm)
    - `sudo pacman -S linux-headers linux-lts-headers nvidia-open-dkms nvidia-utils egl-wayland`
  - shell
    - `sudo pacman -S zsh`
    - `chsh -s /usr/bin/zsh`
    - OhMyZsh: `sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`
    - DOTFILES
- `sudo pacman -S hyprland`
  hypr
