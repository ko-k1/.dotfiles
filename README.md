# .dotfiles
#### This is my archlinux and Hyprland dots
![App Screenshot](https://github.com/ko-k1/.dotfiles/blob/main/preview.png)
>[!WARNING]
>**I don't recommend this for people who aren't developers.** Please apply these dots at your own expense. I will not be held responsible for any damage to your system.
## Requirement Packages

1. upgrade archlinux
```sh
sudo pacman -S archlinux-keyring && pacman -Syyu
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
| `Hyprland` | `pacman` | `pacman -S Hyprland` |
| `waybar` | `pacman` | `pacman -S waybar` |
| `kitty` | `pacman` | `pacman -S kitty` |
| `alacritty` | `pacman` | `pacman -S alacritty` |
| `thunar` | `pacman` | `pacman -S thunar` |
| `cava` | `pacman` | `pacman -S cava` |
| `cmatrix` | `pacman` | `pacman -S cmatrix` |
| `pipes` | `paru` | `paru -S pipes.sh` |
| `lolcat` | `pacman` | `pacman -S lolcat` |
| `swaync` | `pacman` | `pacman -S swaync` |
| `wlogout` | `paru` | `paru -S wlogout` |
| `rofi` | `paru` | `paru -S rofi-lbonn-wayland-git` |
| `starship` | `pacman` | `pacman -S starship` |
| `fcitx5` | `pacman` | `pacman -S fcitx5-im fcitx5-mozc` |
| `hyprcursor` | `pacman` | `pacman -S hyprcursor` |
| `hypridle` | `pacman` | `pacman -S hypridle` |
| `hyprlock` | `pacman` | `pacman -S hyprlock` |
| `hyprshot` | `pacman` | `pacman -S hyprshot` |
| `loupe` | `pacman` | `pacman -S loupe` |
| `superfile` | `pacman` | `pacman -S superfile` |
| `yazi` | `pacman` | `pacman -S yazi` |


## Authors
- [@ko-k1](https://www.github.com/ko-k1)
