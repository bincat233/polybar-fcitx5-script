# polybar-fcitx5-script.sh

A script to show Fcitx5 status. Fork from `polybar-fcitx-scripts` on ArchLinux AUR and I can't find it now. I adapt it to fcitx5.

![](./screenshots/en.png)
![](./screenshots/en_uppercase.png)
![](./screenshots/rime.png)
![](./screenshots/rime_uppercase.png)

# Setup

Copy `polybar-fcitx5-script.sh` to your `~/.config/polybar` folder and add this to your config file:

``` ini
[module/fcitx]
type = custom/script
exec = ~/.config/polybar/polybar-fcitx5-script.sh
tail = true
interval = 0
format-prefix = "KBD"
```

You can replace format-prefix with the symbol you like.
