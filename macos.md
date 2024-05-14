# Mac OS

`source ~/.zprofile` 
- adds /opt/homebrew/bin to path
- binaries of packages installed with brew are
under /opt/homebrew/bin

## Setting up keys like Windows
- Switch option and command keys
- Add app shortcuts: https://support.apple.com/guide/mac-help/create-keyboard-shortcuts-for-apps-mchlp2271/mac#:~:text=On%20your%20Mac%2C%20choose%20Apple,Keyboard%20Shortcuts%20on%20the%20right.&text=Select%20App%20Shortcuts%20on%20the,specific%20app%20or%20All%20Applications.
  - copy paste undo redo (CTRL - <>)

- Also useful (for vim): set Caps-Lock to ESC.

## Reformat Disk

- `diskutil list`
- `diskutil erasedisk FAT32 UBUNTU <disk, example: disk4>`

## Turn off alert sound
Turn alert volume all the way down in `Sound` > `Sound Effect` as explained here:
https://apple.stackexchange.com/questions/384025/why-is-my-macbook-pro-beeping-when-performing-a-keyboard-shortcut

## Get number of cores

- `sysctl -n hw.ncpu`
