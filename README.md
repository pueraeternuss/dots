
<div align="center">
  <img src="https://user-images.githubusercontent.com/93146783/138937351-3e53ed33-e40b-4816-858b-624224f01252.png"></img>
</div>

## environment

- **dist** ~ Arch
- **term** ~ foot
- **launcher** ~ rofi
- **wm** ~ sway-borders-git
- **bar** ~ waybar
- **fonts** ~ Cantarell & Cascadia code 
- **Resolution** ~ 1366x768 (if you have different resolutions, adjust the paddings and margins in waybar/style.css file and gaps in sway/config to fit you screen)

## dependencies

- **waybar**
- **sway-borders-git**
- **xob** (requires you install pulsectl using pip)
- **rofi**
- **foot** (optional, but it's recommended for wayland)

## Setup

- **important** if you already have .local/bin path exported, make sure you comment out the export lines in the install script. it's not a big deal, just to avoid duplicate lines in your shell configs.

- backup your .config & .local folders. 
- clone this repo in your home directory.
- make sure you install the fonts and dependencies mentioned above.
- run the install script.

```
cd dots && ./install

```
- reload your session.

- **Keybind** ~ windowsKey+x to spawn terminal. use it to find the rest of the keybindings in .config/sway/config

