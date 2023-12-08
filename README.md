<div align="center">
  <a href="https://github.com/2dgirlismywaifu/My-Linux-Ricing">
    <img class="avatar" alt="2dgirlismywaifu" src="https://images.weserv.nl/?url=raw.githubusercontent.com/2dgirlismywaifu/My-Linux-Ricing/main/assets/elysia/Elysia.png&h=300&w=300&fit=cover&mask=circle&maxage=7d" width="200" height="200"/>
  </a>

<h3 align="center", style="font-size:25px">My Hyprland Linux Ricing</h3>
  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Caveat&size=30&pause=1000&color=E462F7&center=true&vCenter=true&random=false&width=435&lines=%F0%9F%92%95+FROM+ELYSIA+WITH+LOVE+%F0%9F%92%95" alt="Typing SVG" /></a>
  <br />
  <a href="https://github.com/linuxmobile/hyprland-dots", style="font-size:20px"><strong>Inspired from @linuxmobile Ricing</strong></a>
<hr>

</div>

- **Window Manager** • [Hyprland](https://github.com/hyprwm/Hyprland)🎨 Window Tiles
  Everywhere!
- **Shell** • [Zsh](https://www.zsh.org) 🐚 theme with
  [starship](https://github.com/starship/starship) Cross Shell Platform!
- **Terminal** • [WezTerm](https://github.com/wez/wezterm) 💻 A powerful term
  with gpu support!
- **Panel** • [Waybar](https://aur.archlinux.org/packages/waybar-hyprland-git)🍧
  Patched waybar following hyprland faq!
- **Notify Daemon** • [Dunst](https://github.com/dunst-project/dunst) 🍃
  Minimalist and functional!
- **Launcher** • [Rofi](https://github.com/davatorium/rofi) 🚀 Beautiful list launcher
  customizable!
- **File Manager** • [Ranger](https://github.com/ranger/ranger)🔖 Based Catppuccin theme!


## 🌸 Setup

![1](./assets/screen-short-01.png)![2](./assets/screen-short-02.png)

## Install steps (Take care about it. This is RTFM)
<div align="left">

### Hyprland Stuff

<details>

###### To get started, let's make sure we have all the necessary prerequisites. In this case, I'm using Yay as the AUR helper, you can use any other helper like Paru or install the packages manually.

- Installation using yay

```sh
yay -S hyprland-git hyprpicker-git waybar-git dunst nwg-look wf-recorder wlogout wlsunset swaylock-effects
```
</details>

### Dependencies
<details>

- Installation using yay

```sh
yay -S colord tumbler fnm ffmpegthumbnailer gnome-keyring grimblast-git sdbus-cpp gtk-engine-murrine imagemagick kvantum pamixer playerctl polkit-gnome qt5-quickcontrols qt5-quickcontrols2 qt5-graphicaleffects qt5-wayland qt6-wayland swww ttf-font-awesome tumbler ttf-jetbrains-mono ttf-icomoon-feather xdg-desktop-portal-hyprland-git xdotool xwaylandvideobridge cliphist qt5-imageformats qt5ct
```

</details>

### Apps & More
<details>

#### CLI & Tools
```sh
yay -S btop neofetch noise-suppression-for-voice rofi-lbonn-wayland-git rofi-emoji starship zsh viewnior ocs-url
```
#### Browser & File Explorer

```sh
yay -S firefox file-roller noto-fonts noto-fonts-cjk noto-fonts-emoji ranger thunar thunar-archive-plugin thunar-volman wezterm ttf-iosevka ttf-iosevka-nerd
```
#### VSCode

```sh
yay -S visual-studio-code-bin
```
#### Theme Based

```sh
yay -S catppuccin-gtk-theme-macchiato catppuccin-gtk-theme-mocha papirus-icon-theme sddm-git swaylock-effects-git kvantum kvantum-theme-catppuccin-git
```
#### Pipewire & OBS

```sh
yay -S obs-studio-rc ffmpeg-obs cef-minimal-obs-rc-bin pipewire pipewire-alsa pipewire-audio pipewire-pulse pipewire-jack wireplumber gst-plugin-pipewire pavucontrol
```

</details>

</div>

<div align="left">

### DOTFILES

<details>


###### Now that we have all the dependencies installed, let's clone the repository and copy the files to the home directory

```sh
git clone --branch hyprland https://github.com/2dgirlismywaifu/My-Linux-Ricing.git
cd My-Linux-Ricing
rsync -avxHAXP --exclude '.git*' .* ~/
```

</details>
</div>

## Credits
<div align="center">

  <p float="left">
    <img alt="from-elysia-with-love" src="https://raw.githubusercontent.com/2dgirlismywaifu/My-Linux-Ricing/main/assets/elysia/elysia-hi.png" width="200" height="200"/>
    <img alt="from-elysia-with-love" src="https://raw.githubusercontent.com/2dgirlismywaifu/My-Linux-Ricing/main/assets/elysia/from-elysia-with-love.png" width="200" height="200"/>
    <img alt="from-elysia-with-love" src="https://raw.githubusercontent.com/2dgirlismywaifu/My-Linux-Ricing/main/assets/elysia/elysia-music.png" width="200" height="200"/>
  </p>
</div>

_Beauty community: [r/unixporn](https://www.reddit.com/r/unixporn)._

**©** Elysia is a character from Honkai Impact 3rd, a game by Hoyoverse (miHoYo)

**©** Picture used in this sources come from Pixiv and N0va Desktop

**©** This repository is forked from [linuxmobile](https://github.com/linuxmobile/hyprland-dots) with clean-up some useless shell script.
