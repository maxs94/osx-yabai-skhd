# i3wm like OSX
i3wm like configuration files for mac osx with yabai, skhd and iterm2


# Installation 
howto: https://piratefache.ch/chunkwm-is-dead-reborn-as-yabai/

 - Yabai https://github.com/koekeishiya/yabai#install
 - SKHD (Keyboard Shortcuts) https://github.com/koekeishiya/skhd
 - iTerm2 https://github.com/gnachman/iTerm2
 
 - Copy the yabairc file from this repository to ~/.yabairc 
 - Copy the skhdrc file from this repository to ~/.skhdrc 
 
 - Create your spaces to use in MacOS: (Mission Control -> Add spaces)
 
 restart yabai and skhd
 ```
 $ brew services restart yabai
 $ brew services restart skhd
 ```
 

# Hints
you might want to change the shortcut for taking screenshots as CMD - SHIFT + 4 sends the focussed window to space #4

-> System Preferences -> Keyboard -> Shortcuts -> Screenshots

# Screenshot
![screen](/screen.png?raw=true)
