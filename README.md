# this is a rice for arch/arch based linux distro
---------------------------------------------------------------
vast majoritys of code/aesthics/wallpapers and some other information is from https://github.com/diinki/diinki-retrofuture/tree/main
while at the moment this mostly exists as a fork of diinki's retro-futurism rice for arch-linux as of 1.0.0 modifications to it are to be expected

--------------------------------------------
## pre-install
while in the shell or terminal of your choice run "sudo pacman -S sway wofi waybar nemo nautilus kitty dconf dconf-editor" and "yay eww" to install the required components for this rice
install the "Maple Mono Font" - https://github.com/subframe7536/Maple-font


## installing
to install move the .config file into home/<user> there will most likely already be a .config file located here, either replace it or replace the dedicated files individually

## note as to the keybindings used 


mod = the super key, (the windows key, as some people refer to it as). You can re-bind mod to something else if you wish.

mod + Enter = launch terminal.

mod + D = launch application launcher.

mod + [any number, 1-9] = switch focus to the workspace equivalent to the number.

mod + Shift +  [any number, 1-9] = move the focused window to the workspace equivalent to the number.

mod + Shift +  Space = toggle floating mode for the focused window.

mod + Shift +  C = restart eww and all other things such as waybar and eww.

mod +  Q = Exit/Kill the focused window.

mod + F = toggle full-screen mode for the focused window.

mod + Right Mouse Button = re-size a window

mod + Left Mouse Button = move a window

## toolkit 
sway (The window manager)
hyprland (The alternate window manager)
wofi (Application Launcher)
waybar (Taskbar/Infobar)
dconf & dconf-editor (Used to edit gtk themes and cursors, and default softwares used)
nemo or nautilus (File explorer).
kitty (The terminal Emulator)
themix-oomix (Used to create the non GTK4 themes.)
network-manager-applet (Used for tray and other nm things, probably installed with your OS by default.)
eww (Widgets)

## note
most information included in this is from diinki so if looking for a video turtorial or turtorials on how to download/create and set up your own rice or linux set up i reccomend those videos and repos
