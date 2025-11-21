# My Mac setup with the yabai tiling window manager

1. Install stow via `brew install stow`.
2. Clone this repo into your ~ directory.
3. Install yabai via `brew install koekeishiya/formulae/yabai` 
3. Install skhd via `brew install koekeishiya/formulae/skhd` 
3. Run `cd ~/dotfiles`
4. Run `stow yabai`
5. Run `stow skhd`

## yabai commands

These are the commands for starting/stopping/restarting yabai:
- `yabai --start-service` (The first time you execute this, please grant yabai the needed permissions)
- `yabai --stop-service`
- `yabai --restart-service`

## skhd commands

Side note: skhd allows us to use keyboard shortcuts, e.g. vim keybindings.

These are the commands for starting/stopping/restarting skhd:
- `yabai --start-service` (The first time you execute this, please grant skhd the needed permissions)
- `yabai --stop-service`
- `yabai --restart-service`


