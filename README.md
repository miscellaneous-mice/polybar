# polybar

## Nord Theme

![nord_gif](https://github.com/miscellaneous-mice/polybar/assets/79500624/7cc64efc-fa5b-4494-ae92-31dae6e51724)

- Located in polybar_nord

## Catppuccin Theme

![cat_gif](https://github.com/miscellaneous-mice/polybar/assets/79500624/55caf8be-eec3-4c42-bcce-92c86b9077e0)

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
