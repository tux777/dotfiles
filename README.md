# Info :information_source:
My rice is based on another guy's rice, janleigh. You can find his dotfiles here.
Anyways, here's the information
* WM: [bspwm](https://github.com/baskerville/bspwm)
* Shell: [fish](https://github.com/fish-shell/fish-shell)
* Terminal: [alacritty](https://github.com/alacritty/alacritty)
* Bar: [polybar](https://github.com/polybar/polybar)
* Browser: [Microsoft Edge](https://aur.archlinux.org/packages/microsoft-edge-stable-bin)
* Launcher: [rofi](https://github.com/davatorium/rofi)
* Notifications: [dunst](https://github.com/dunst-project/dunst)
* File Manager: [thunar](https://github.com/xfce-mirror/thunar)

# How to get this :arrow_down:
## Installing Dependencies 📋
```paru -S rofi-git jgmenu-git picom-animations-git alacritty polybar dunst otf-code-new-roman bspwm-git sxhkd-git pfetch-git neovim fish-git microsoft-edge-stable-bin```

Clone this repository and copy everything in ```.config/``` to ```~/.config/```

## Setting Color Scheme 🎨
[janleigh's color scheme](https://github.com/janleigh/dotfiles#art-colorscheme)

Copy the ```.Xresources``` file to your home directory aka. ```~```

### Setting GTK theme
Copy the janleigh-phocus folder located in ```.themes/``` to ```~/.themes/``` 

>For some reason with me, I can't set this theme with lxappearance. I was able to set the GTK theme using the ```~/.config/gtk-3.0/settings.ini``` file, setting the ```gtk-theme-name``` property to ```janleigh-phocus```

## Font 🇫
Copy the ```Sofia_Pro_Regular.otf``` located in ```.fonts/``` file to ```~/.fonts/```

# Credits ❤️
* [janleigh]() (Based my rice off of his so ty)
* Linus Torvalds (For creating linux obviously)
* Developers of jgmenu, rofi, picom, etc.
