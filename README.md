```
 \
 /     ^     ^     ^     ^     ^     ^     ^
 \    /_\   /_\   /_\   /_\   /_\   /_\   /_\
 /     |     |     |     |     |     |     |
 \
 /  _             __           _           _  __
 \ | |  _  _ _  _|  | ___ __  |_| __  ___ | |/ /
 / | |_| || | \/ | _ | __|   \ _ / _\/  _||   |
 \ |___|____|____|___|___|_|\_\ |____\____|_|\_\
 /                            | |
 \                            | |
 /                            | |  /|
 \                            | | /||
 /                            |_|/ ||
 \                           |___  ||
 /                            |_|\ ||
 \                                \||
 /                                 \|
```
# lumberjack.vim
lumberjack.vim is a bearded Vim color scheme based on some classic colors associated with the logging industry.

This scheme should work on 256-color terminals and in GVim, even if you are a hipster.

## Installation
You can use your favorite plugin manager or go with the awesome [vim-plug](https://github.com/junegunn/vim-plug) then do the following:

1. Add `Plug 'yamafaktory/lumberjack.vim'` to .vimrc
2. Run `:PlugInstall`

## Vim
In order to get the correct color values mapped in vim accordingly, you need to add these lines to your .Xresources:
```
! lumberjack theme

URxvt*color0: #1a1a1a
URxvt*color8: #212121

URxvt*color1: #bd2a2a
URxvt*color9: #c76440

URxvt*color2: #5d875d
URxvt*color10: #9acd32

URxvt*color3: #947463
URxvt*color11: #f0e95d

URxvt*color4: #9bcbeb
URxvt*color12: #858585

URxvt*color5: #b56124
URxvt*color13: #303030

URxvt*color6: #2e2e2e
URxvt*color14: #757475

URxvt*color7: #fffefc
URxvt*color15: #ffffff

URxvt*background: #1a1a1a
URxvt*foreground: #858585

URxvt*cursorColor: #9bcbeb

URxvt*highlightColor: #9acd32
URxvt*highlightTextColor: #fffefc
```
