# My configuration for i3

This repository contains all my configuration for i3 WM (on Arch Linux).
I am currently using `i3-gaps` fork, available on GitHub, and as `i3-gaps-git` on
AUR for Arch Linux users.

## Requirements

- `i3blocks`: to customize contents displayed by i3bar (replacement for `i3status`)
- `i3lock` and `i3lock-fancy`: screen locker
- `rofi`: launcher (and more)
- `ttf-font-icons`: for icons in the bar
- `scrot`: screenshot utility used by `i3lock-fancy`
- `compton`: (optional) for transparency and other effects
- `jq`: required for renaming workspaces with `i3-renamews` script

## Try it!

On most distributions, you just need to put these files into `~/.config/i3/`.

Some features may not work out-of-the-box because in `config` you have to fix
the command used for them (e.g., for taking screenshots).

## Screenshot ##

![alt tag](https://raw.githubusercontent.com/childerico/my-i3-wm/master/screenshots/screenshot1.png)
