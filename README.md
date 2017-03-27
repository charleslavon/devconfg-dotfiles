#to support quickly moving my custom application configs between machines


#### sublime
Install sublime3, add license, etc.

rm -rf ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User


ln -s ~/.dotfiles/sublime/User/ ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User



#### iterm2
Install iterm, then

rm -rf ~/Library/Preferences/com.googlecode.iterm2.plist

ln -s ~/.dotfiles/iterm2/com.googlecode.iterm2.plist ~/Library/Preferences/com.googlecode.iterm2.plist

