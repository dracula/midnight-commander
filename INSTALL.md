## [Midnight Commander (mc)](https://midnight-commander.org/)

Note that this theme is entirely dependent on having installed the relevant dracula theme for your terminal too. This theme uses the color pallette fixed by your terminal.

See [iTerm](https://draculatheme.com/iterm/) and [Gnome Terminal](https://draculatheme.com/gnome-terminal/) themes for example.


### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

    git clone https://github.com/dracula/mc.git
    cd ~/.local/share/mc/skins/
    ln -s ~/dracula-theme/mc/skins/dracula.ini


### Install manually

Download the latest [raw file](https://raw.githubusercontent.com/dracula/mc/master/skins/dracula.ini) and save it as `~/.local/share/mc/skins/dracula.ini`

### Activating theme

Update your mc settings

Option 1: edit `~/.config/mc/ini` and add `skin=dracula` to the `[Midnight-Commander]` section..

    [Midnight-Commander]
    ...
    skin=dracula

Option 2: choose the skin through the mc UI with F9 > Options > Appearance

Boom! It's working
