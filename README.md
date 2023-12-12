# polybar

## Nord Theme

![nord_gif](https://github.com/miscellaneous-mice/polybar/assets/79500624/3a027c37-2770-4d1d-96e7-f8c9f98dfc4f)

- Located in polybar_nord

## Catppuccin Theme

![Cat_gif](https://github.com/miscellaneous-mice/polybar/assets/79500624/703ac932-a4d3-466a-9635-533c80410d9e)

- Located in polybar_catppuccin

## Installation
- Git clone the repo
```
$ git clone https://github.com/miscellaneous-mice/polybar.git
$ cd polybar
```
- Replace the contents of your polybar with your preferred {theme -> polybar_catppuccin/polybar_nord}
```
$ mkdir -p ~/Backup/polybar
$ mv ~/.config/polybar/* ~/Backup/polybar
$ mv {theme}/* ~/.config/polybar/
```
- Copy the required fonts into your fonts folder. If you have these fonts installed you may skip this step
```
$ sudo cp -r ~/.config/polybar/fonts/* /usr/share/fonts/
```
- Make all the scripts executable
```
$ chmod +x ~/.config/polybar/scripts/launcher
$ chmod +x ~/.config/polybar/scripts/powermenu_alt
$ chmod +x ~/.config/polybar/launch.sh
$ chmod +x ~/.config/polybar/scripts/monster/start.sh
$ chmod +x ~/.config/polybar/scripts/pacman/start.sh
```

## How to Use
- In your window manager config file, add this line to your startup processes
```
~/.config/polybar/launch.sh
```

## Credits
- Polybar : https://github.com/VaughnValle/blue-sky
- Polybar animation : https://github.com/itsoctotv/polybar-pacman-animation
