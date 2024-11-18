# xorg-keyboard-config
Configuration files for X11 and vconsole, ensuring that the TTY login has the
correct layout, even before starting X11.

## File generation
The files can be generated with:
```
sudo localectl set-x11-keymap fr,ru pc104 "" "caps:escape,grp:alt_space_toggle"
```

## File locations
```
/etc/vconsole.conf
/etc/X11/xorg.conf.d/00-keyboard.conf
```
