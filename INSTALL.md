### [Midnight Commander (mc)](https://midnight-commander.org/)

Note that this theme is entirely dependent on having installed the relevant dracula theme for your terminal too. This theme uses the color palette fixed by your terminal.

See [iTerm](https://draculatheme.com/iterm/) and [Gnome Terminal](https://draculatheme.com/gnome-terminal/) themes for example.

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

    # clone anywhere you like, but adjust paths as needed
    mkdir ~/dracula-theme && cd ~/dracula-theme
    git clone https://github.com/dracula/midnight-commander.git
    
    mkdir -p ~/.local/share/mc/skins && cd ~/.local/share/mc/skins
    ln -s ~/dracula-theme/mc/skins/dracula.ini
    ln -s ~/dracula-theme/mc/skins/dracula256.ini


#### Install manually

For 8/16 colors; download the latest [raw file](https://raw.githubusercontent.com/dracula/midnight-commander/master/skins/dracula.ini) and save it as `~/.local/share/mc/skins/dracula.ini`

For 256 colors; download the latest [raw file](https://raw.githubusercontent.com/dracula/midnight-commander/master/skins/dracula256.ini) and save it as `~/.local/share/mc/skins/dracula256.ini`

#### Activating theme

Update your mc settings..

Option 1: edit `~/.config/mc/ini` and add `skin=dracula` to the `[Midnight-Commander]` section..

    [Midnight-Commander]
    # for 8/16 color..
    skin=dracula
    # for 256 color..
    skin=dracula256

Option 2: choose the skin through the mc UI with F9 > Options > Appearance

Boom! It's working
