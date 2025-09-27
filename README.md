# .dotfiles
#### This is my archlinux and Hyprland dots
![preview](https://github.com/ko-k1/.dotfiles/blob/main/preview.png)
>[!WARNING]
>**I don't recommend this for people who aren't developers.** Please apply these dots at your own risk. I will not be held responsible for any damage to your system.

## Requirement Packages
1. upgrade archlinux
```sh
sudo pacman -S archlinux-keyring && sudo pacman -Syyu
```

2. install aur helper
detail is [Arch Wiki](https://aur.archlinux.org/packages/paru) of aur helpers.
#### list
| name | dependencies |
| :- | :- |
| `paru` | `rustup` |
| `yay` | `gcc` |
- aur helpers dependencies
```sh
sudo pacman -S git fakeroot binutils make gcc
sudo pacman -S --needed git base-devel rustup
rustup default stable
```
- aur install
>paru
```sh
git clone https://aur.archlinux.org/paru.git
cd paru
makepkg -si
```
>yay
```sh
git clone https://aur.archlinux.org/yay.git
cd yay
makepkg -si
```

3. dotfiles package dependencies

| name | pacman | sh |
| :- | :- | :- |
| `ags` | `paru` | `paru -S aylurs-gtk-shell` |
| `alacritty` | `pacman` | `pacman -S alacritty` |
| `cava` | `pacman` | `pacman -S cava` |
| `cmatrix` | `pacman` | `pacman -S cmatrix` |
| `fcitx5` | `pacman` | `pacman -S fcitx5-im fcitx5-mozc` |
| `file roller` | `pacman` | `pacman -S file-roller` |
| `hyprcursor` | `pacman` | `pacman -S hyprcursor` |
| `hypridle` | `pacman` | `pacman -S hypridle` |
| `Hyprland` | `pacman` | `pacman -S Hyprland` |
| `hyprlock` | `pacman` | `pacman -S hyprlock` |
| `hyprshot` | `pacman` | `pacman -S hyprshot` |
| `kitty` | `pacman` | `pacman -S kitty` |
| `lolcat` | `pacman` | `pacman -S lolcat` |
| `loupe` | `pacman` | `pacman -S loupe` |
| `nwg dock` | `paru` | `paru -S nwg-dock-hyprland` |
| `gtk theming` | `pacman` | `pacman -S nwg-look` |
| `pavucontrol` | `paru` | `paru -S pavucontrol` |
| `pipes` | `paru` | `paru -S pipes.sh` |
| `rofi` | `paru` | `paru -S rofi-lbonn-wayland-git` |
| `starship` | `pacman` | `pacman -S starship` |
| `superfile` | `pacman` | `pacman -S superfile` |
| `swaync` | `pacman` | `pacman -S swaync` |
| `swww` | `pacman` | `pacman -S swww` |
| `thunar` | `pacman` | `pacman -S thunar` |
| `wlogout` | `paru` | `paru -S wlogout` |
| `waybar` | `pacman` | `pacman -S waybar` |
| `yazi` | `pacman` | `pacman -S yazi` |

## Authors
- [@ko-k1](https://www.github.com/ko-k1)
