# HackTheBox Vim Colorscheme


![](./palette.png)

![](./img.png)

Based on the [hackthebox theme
colors](https://marketplace.visualstudio.com/items?itemName=silofy.hackthebox) and the OneDark vim theme by
https://github.com/joshdick/onedark.vim

Looks best on terminals with TrueColor support. Best effort 256-color term alternative are provided
as well.

## Installation

Use your plugin manager's prefered installation method. For VimPlug:

```
Plug 'audibleblink/hackthebox.vim'
```
or just copy `colors/hackthebox.vim` into `~/.vim/colors`

## Windows Terminal

If you'd like this colorscheme in Windows Terminal, paste this into your settings.json

```json
{
  "schemes": [
    {
      "name": "HackTheBox",
      "background": "#1a2332",
      "foreground": "#a4b1cd",
      "black": "#000000",
      "brightBlack": "#666666",
      "white": "#ffffff",
      "brightWhite": "#ffffff",

      "red": "#ff3e3e",
      "brightRed": "#ff8484",
      "green": "#9fef00",
      "brightGreen": "#c5f467",
      "yellow": "#ffaf00",
      "brightYellow": "#ffcc5c",
      "blue": "#004cff",
      "brightBlue": "#5cb2ff",
      "purple": "#9f00ff",
      "brightPurple": "#c16cfa",
      "cyan": "#2ee7b6",
      "brightCyan": "#5cecc6",
      "selectionBackground": "#313f55",
      "cursorColor": "#313f55"
    }
  ]
}
```
## Xresources
You can paste this in your ~/.Xresources or ~/.Xdefaults file for using this
colorscheme in xterm, urxvt and st(with xresources patch)
```
! Hack the box
*.background:  #1a2332
*.foreground:  #a4b1cd
*.cursorColor: #313f55

*.color0:  #000000
*.color8:  #666666
*.color1:  #ff3e3e
*.color9:  #ff8484
*.color2:  #9fef00
*.color10: #c5f467
*.color3:  #ffaf00
*.color11: #ffcc5c
*.color4:  #004cff
*.color12: #5cb2ff
*.color5:  #9f00ff
*.color13: #c16cfa
*.color6:  #2ee7b6
*.color14: #5cecc6
*.color7:  #ffffff
*.color15: #ffffff
```

## Kitty
Color scheme adapted for kitty terminal. Paste this in your ~/.config/kitty/kitty.conf file
```conf

background  #1a2332
foreground  #a4b1cd
cursor      #3f8193

color0      #000000
color8      #666666
color1      #ff3e3e
color9      #ff8484
color2      #9fef00
color10     #c5f467
color3      #ffaf00
color11     #ffcc5c
color4      #004cff
color12     #5cb2ff
color5      #9f00ff
color13     #c16cfa
color6      #2ee7b6
color14     #5cecc6
color7      #ffffff
color15     #ffffff

selection_background #313f55
selection_foreground #ffffff
```

## Alacritty
Adaptation of colorscheme for alacritty terminal. 
```yaml
# alacritty.toml

[colors.primary]
background = "#1a2332"
foreground = "#a4b1cd"

[colors.selection]
text = "#ffffff"
background = "#313f55"

[colors.cursor]
text = '#eee9fc'
cursor = '#eee9fc'

[colors.normal]
black = "#000000"
red = "#ff3e3e"
green = "#9fef00"
yellow = "#ffaf00"
blue = "#5cb2ff"
magenta = "#9f00ff"
cyan = "#2ee7b6"
white = "#ffffff"

[colors.bright]
black = "#666666"
red = "#ff8484"
green = "#c5f467"
yellow = "#ffcc5c"
blue = "#5cb2ff"
magenta = "#c16cfa"
cyan = "#5cecc6"
white = "#ffffff"
```
