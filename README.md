# Macbook Bootstrap

## Installations

### Essencial
- Mac OS Newest version installed? Check for update
- Xcode (App Store)
  - Install Command line tools (Includes GIT)
- Change Terminal Shell to **ZSH**
- Install Homebrew [[Download](http://mxcl.github.io/homebrew/)]
- Copy .ssh folder from the old HD
- Create ~/dev folder
- Install dotfiles [[Download](https://github.com/djalmaaraujo/dotfiles)]
- Install Dropbox [[Download](http://dropbox.com/)]
- Install 1Password [[Download](https://agilebits.com/onepassword)]
	- Use archive file from Dropbox

### System config
- Set tap to click in Trackpad (Prefs/Trackpad/Point & Click) [Preview](http://cl.ly/image/3W1B0A1B2d0x)
- Set scrol to natural in Trackpad (Prefs/Trackpad/Scroll & Zoom) [Preview](http://cl.ly/image/2n3N1Q3x2c3N)
- Change computer name to djalmaaraujo in (Prefs/Sharing) [Preview](http://cl.ly/image/1d260L3n3o2F)
- Set computer to never sleeps in Power Adapter (Prefs/Energy Saver) [Preview](http://cl.ly/image/3s391f06031r)
- Enable access for assistive devices in (Prefs/Acessibility) [Preview](http://cl.ly/image/1x0C2i250n29)
- Configure Mission Control in (Prefs/Mission Control/Hot Corners) [Preview](http://cl.ly/image/0P1z2R1J2X2k)
- Set All Controls radion button option in (Prefs/Keyboard) [Preview](http://cl.ly/image/1u3H1C1E2U1k)
- Set all notifications to Banners (It's less confuse) (Prefs/Notifications) [Preview](http://cl.ly/image/2n3N1Q3x2c3N)
- Show hidden files
```
defaults write com.apple.Finder AppleShowAllFiles YES
```
- Organize my Finder Favorites like the preview [Preview](http://cl.ly/image/2V3s3I0i3O2n)

### Other Applications
- Install Mou App [[Download](http://mouapp.com/)]
- Install MPlayerX (App Store)
- Install Reeder (App Store)
- Install Sublime Text 2 [[Download](http://www.sublimetext.com/2)]
	- Install package control [[Download](http://wbond.net/sublime_packages/package_control)]
- Install Sequel Pro [[Download](http://www.sequelpro.com/)]
- Install Cloud App (App Store)

### PHP Environment
#### PHP
* brew tap homebrew/dupes
* brew tap josegonzalez/homebrew-php
* brew install php54 --with-mysql --wihout-apache
* brew install php54-memcached php54-apc php54-xdebug

#### MYSQL
* brew install mysql
* mysql_install_db --verbose --user=`whoami` --basedir="$(brew --prefix mysql)" --datadir=/usr/local/var/mysql --tmpdir=/tmp
* mysql.server start
* /usr/local/Cellar/mysql/5.5.27/bin/mysqladmin -u root password 'new-password'
* brew info mysql


### Ruby Environment
- Soon...
