#### to support quickly moving my custom application configs between machines


#### sublime
Install sublime3 and add license.

Install theme https://github.com/kkga/spacegray
Be sure to double check that User Settings in Preferences -> Settings contains the following

{
  "theme": "Spacegray.sublime-theme",
  "color_scheme": "Packages/Theme - Spacegray/base16-ocean.dark.tmTheme"
}


then...

rm -rf ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User


ln -s ~/.dotfiles/sublime/User/ ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User



#### iterm2
Install iterm, then install oh-my-zsh https://github.com/robbyrussell/oh-my-zsh

rm -rf ~/Library/Preferences/com.googlecode.iterm2.plist

ln -s ~/.dotfiles/iterm2/com.googlecode.iterm2.plist ~/Library/Preferences/com.googlecode.iterm2.plist

