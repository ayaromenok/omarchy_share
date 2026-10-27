# Oomarchy Share
List of useful settings, plugins, etc for omarchy linux

### All shotcuts

[Shot cuts](https://github.com/omacom/omarchy/blob/v4.0.6/manual/07-hotkeys.md)

### Plug-ins

| Description | command line |
| ------------| ------------ |
| TaskBar     | `omarchy plugin add https://github.com/joeyvigil/omarchy-taskbar.git --enable` |
| Alt-tab window switch | `omarchy plugin add https://github.com/qempexe/omarchy-altscape.git  --enable`|



### Config

#### Screensaver

`nano ~/.config/omarchy/shell.json`

```"idle": {
  "screensaver": 150,
  "lock": 300
}``

```omarchy restart shell```