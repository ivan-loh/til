You can reset the launchpad arrangement on El Capitan with the following command.
```
defaults write com.apple.dock ResetLaunchPad -bool true; killall Dock
```


Alternatively just add it to your .bashrc for quick access
```
alias resetlaunchpad="defaults write com.apple.dock ResetLaunchPad -bool true; killall Dock"
```
