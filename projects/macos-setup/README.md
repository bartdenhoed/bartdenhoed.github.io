# My MacOS Setup

This is a multi-part blog by [Bart den Hoed](http://bartdenhoed.nl):
1. **My MacOS Setup**
2. [My Android Setup](https://github.com/bartdenhoed/android-setup)
3. [My Personal Archive](https://github.com/bartdenhoed/personal-archive)

## Introduction
My personal development setup for my **MacBook Pro** touch-bar late 2016 (**MacOS** 10.13 High Sierra). This setup is mainly for **Java** and **Web**-development. It's based on the setup from [**Nicolas Hery**](https://github.com/nicolashery/mac-dev-setup) and the tutorial instructions from [**GetGrav**](https://getgrav.org/blog/macos-sierra-apache-multiple-php-versions).

We will setup the **MacOS** settings, general & development **applications** and a **PHP**, **Apache** & **MySQL** environment. I also would like to build scripts to automate this setup in the future.

## Table of Content
- [System preferences](#system-preferences)
    - [Settings](#settings)
    - [Touch Bar](#touch-bar)
    - [Menu Bar](#menu-bar)
    - [Dock](#dock)
    - [Finder](#finder)
    - [Desktop](#deskop)
    - [Emojis](#emojis)
    - [Fonts](#fonts)
    - [Others](#others)
- [Applications](#applications)
    - **General:**
    - **Development:**
    - **Tools:**
- [Development](#development)
    - [Homebrew](#homebrew)
    - [Git](#git)
    - [Vim](#vim)
- [Links](#links)

## System preferences
### Settings
**General:**
- General > Use dark menu bar and Dock (On)
- General > Sidebar icon size (Large)
- General > Show scroll bars (When scrolling)

<img src="images/settings/1-general.jpg" alt="Settings general" width="600">

#
**Desktop & Screen Saver:**
- Desktop & Screen Saver > Screen Saver (Message)
- Desktop & Screen Saver > Screen Saver > Show with clock (On)

<img src="images/settings/2-desktop&screen-saver.jpg" alt="Settings desktop & screen saver" width="600">

#
**Dock:**
- Dock > Prefer tabs when opening documents (Always)
- Dock > Automatically hide and show the Dock (On)

<img src="images/settings/3-dock.jpg" alt="Settings dock" width="600">

#
**Mission Control:**
- Mission Control > Automatically rearrange Spaces based on most recent use (Off)

<img src="images/settings/4-mission-control.jpg" alt="Settings mission control" width="600">

#
**Language & Region:**
- Language & Region > Preferred languages: English - Primary & Dutch (Netherlands)

<img src="images/settings/5-language&region.jpg" alt="Settings language & region" width="600">

#
**Security & Privacy:**
- Security & Privacy > General > Require password (immediately) after sleep or screen saver begins
>
- Security & Privacy > Firewall > On

<img src="images/settings/6-security&privacy-1.jpg" alt="Settings security & privacy" width="600">

<img src="images/settings/6-security&privacy-2.jpg" alt="Settings security & privacy" width="600">

#
**Displays:**
- Displays > Scaled (More Space)

<img src="images/settings/7-displays.jpg" alt="Settings displays" width="600">

#
**Energy Saver:**
- Energy Saver > Battery > Turn display off after (10 min)
<img src="images/settings/8-energy-saver-1.jpg" alt="Settings energy saver 1" width="600">

- Energy Saver > Power Adapter > Turn display off after (15 min)
- Energy Saver > Power Adapter > Enable Power Nap while plugged into a power adapter (Off)
<img src="images/settings/8-energy-saver-2.jpg" alt="Settings energy saver 2" width="600">

#
**Keyboard:**
- Keyboard > Keyboard > Key Repeat (Fast)
- Keyboard > Keyboard > Delay Until Repeat (Short)
- Keyboard > Keyboard > Adjust keyboard brightness in low light (Off)
- Keyboard > Keyboard > Press Fn key to (Expand Control Strip)
<img src="images/settings/9-keyboard-1.jpg" alt="Settings keyboard 1" width="600">

- Keyboard > Modifier Keys > Caps Lock (⇪) Key: (Escape)
<img src="images/settings/9-keyboard-6.jpg" alt="Settings keyboard 6" width="600">

- Keyboard > Shortcuts > Full Keyboard Access (All controls)
- Keyboard > Shortcuts > Move focus to next window (⌘ + §)
<img src="images/settings/9-keyboard-3.jpg" alt="Settings keyboard 3" width="600">

- Keyboard > Input Sources > U.S. International
<img src="images/settings/9-keyboard-4.jpg" alt="Settings keyboard 4" width="600">

- Keyboard > Dictaction > Dictation (Off)
- Keyboard > Dictaction > Shortcut (Off)
<img src="images/settings/9-keyboard-5.jpg" alt="Settings keyboard 5" width="600">

#
**Trackpad:**
- Trackpad > Point & Click > Look up & data detectors (Off)
- Trackpad > Point & Click > Tap to click (On)
- Trackpad > Point & Click > Click (Medium)
- Trackpad > Point & Click > Tracking speed (8)
- Trackpad > Point & Click > Force Click and haptic feedback (Off)
<img src="images/settings/10-trackpad-1.jpg" alt="Settings trackpad 1" width="600">

- Trackpad > Scroll & Zoom > Scroll direction (Off)
- Trackpad > Scroll & Zoom > Smart zoom (Off)
<img src="images/settings/10-trackpad-2.jpg" alt="Settings trackpad 2" width="600">

- Trackpad > More Gestures > Swipe between full-screen apps (Swipe left or right with four fingers)
- Trackpad > More Gestures > Mission Control (Swipe up with four fingers)
- Trackpad > More Gestures > App Exposé (Swipe down with four fingers)
<img src="images/settings/10-trackpad-3.jpg" alt="Settings trackpad 3" width="600">

#
**Sound:**

<img src="images/settings/11-sound-1.jpg" alt="Settings sound 1" width="600">

#
**App Store:**
- App Store > Install app updates (On)
- App Store > Install macOS updates (On)
- App Store > Free Downloads (Save Password)
<img src="images/settings/12-app-store.jpg" alt="Settings app store" width="600">

#
**Users & Groups:**
- Users & Groups > Guest User (Off)
<img src="images/settings/13-users&groups-1.jpg" alt="Settings users & groups 1" width="600"><img src="images/settings/13-users&groups-2.jpg" alt="Settings users & groups 2" width="600">

#
**Siri:**
- Siri > Enable Siri (Off)
<img src="images/settings/14-siri.jpg" alt="Settings siri" width="600">

#
### Touch Bar
Nowadays I use this Touch Bar setup:
![Touch Bar](images/visual/touch-bar-1.jpg)
Full settings bar:
![Touch Bar](images/visual/touch-bar-2.jpg)

#
### Menu Bar
I use [Bartender 3](#bartender-3) to hide the most applications in the Menu Bar, so I only see the important one. You can click on the three little dots to see the extended Menu Bar.
![Menu Bar](images/visual/menu-bar-1.jpg)
Extended with [Bartender 3](#bartender-3):
![Menu Bar](images/visual/menu-bar-2.jpg)

#
### Dock
I keep 7 applications in the dock. From left to right:
- [Finder](#finder)
- [Enpass](#enpass)
- [Trello](#trello)
- [Atom](#atom)
- [Whatsapp](#whatsapp)
- [Spotify](#spotify)
- [Google Chrome](#google-chrome)

And I also add a little space between those apps and other open apps: `defaults write com.apple.dock persistent-apps -array-add '{tile-data={}; tile-type="spacer-tile";}'`
![Dock](images/visual/dock.jpg)

- Super-fast dock animation: `defaults write com.apple.dock autohide-time-modifier -float 0.12;`
- No dock animation: `defaults write com.apple.dock autohide-time-modifier -int 0;`
- Default dock animation: `defaults delete com.apple.dock autohide-time-modifier;`

To see this changes run: `killall Dock;`

#
### Finder
- General > Hard disks (On)
- General > CD's (Off)
- General > Connected servers (On)
- General > New Finder windows shows: (Home folder)
>
- Advanced > Show all filename extensions (On)
- Advanced > Show warning before changing an extension (Off)
- Advanced > Remove items from the Trash after 30 days (On)
- Advanced > Keep folders on top when sorting by name (On)
>
**Enable:**
- View > Show Tab Bar
- View > Show Path Bar
- View > Show Status Bar

TODO:
![Finder](images/apps/finder-settings-1.jpg)
![Finder](images/apps/finder-settings-2.jpg)
![Finder](images/apps/finder-menu.jpg)

#
### Desktop
Show View Options:
- Show item info (On)
- Sort By (Snap to Grid)

TODO: Background

#
### Emojis
Add this to the favorites:
- ˆ = Control key (ctrl)
- ⌘ = Command key (cmd)
- ⌥ = Option key
- ⎋ = ESC key
- ⇧ = Shift key
- ⇪ = Caps lock key
- ⏎ = Return key
- ⌫ = Delete key
- € = Euro character

![Emojis](images/apps/emojis.jpg)

#
### Fonts
You can download this fonts at [fonts.google.com](http://fonts.google.com)

- [Roboto Mono](https://fonts.google.com/specimen/Roboto+Mono)

## Applications
### Google Chrome
[Google Chrome](https://www.google.com/chrome/) One fast, simple, and secure browser for all your devices.

**Extensions:**
- [Application Launcher for Drive (by Google)](https://chrome.google.com/webstore/detail/application-launcher-for/lmjegmlicamnimmfhcmpkclmigmmcbeh)
- [Bookmark Manager](https://chrome.google.com/webstore/detail/bookmark-manager/gmlllbghnfkpflemihljekbapjopfjik)
- [Docs](https://chrome.google.com/webstore/detail/docs/aohghmighlieiainnegkcijnfilokake)
- [Enpass Password Manager](https://chrome.google.com/webstore/detail/enpass-password-manager/kmcfomidfpdkfieipokbalgegidffkal)
- [HTTPS Everywhere](https://chrome.google.com/webstore/detail/https-everywhere/gcbommkclmclpchllfjekcdonpmejbdp)
- [Inbox by Gmail](https://chrome.google.com/webstore/detail/inbox-by-gmail/gkljgfmjocfalijkgoogmfffkhmkbgol)
- [LiveReload](https://chrome.google.com/webstore/detail/livereload/jnihajbhpnppcggbcgedagnkighmdlei)
- [Momentum](https://chrome.google.com/webstore/detail/momentum/laookkfknpbbblfpciffpaejjkokdgca)
- [Pushbullet](https://chrome.google.com/webstore/detail/pushbullet/chlffgpmiacpedhhbkiomidkjlcfhogd)
- [Sheets](https://chrome.google.com/webstore/detail/sheets/felcaaldnbdncclmgdcncolpebgiejap)
- [Slides](https://chrome.google.com/webstore/detail/slides/aapocclcgogkmnckokdopfmhonfmgoek)
- [uBlock](https://chrome.google.com/webstore/detail/ublock/epcnnfbjfcgphgdmggkamkmgojdagdnn)
- [Website IP](https://chrome.google.com/webstore/detail/website-ip/ghbmhlgniedlklkpimlibbaoomlpacmk)

**Menu Bar:**
In the menu bar from left to right: Bookmark, Inbox, LiveReload, uBlock, Enpass
![Chrome](images/apps/chrome-bar.jpg)

**Settings:**
- Enable "Warn Before Quitting (⌘Q)"

#
### Google Backup and Sync
[Google Backup and Sync](https://www.google.com/drive/download/backup-and-sync/) Safely back up your files.

#
### Enpass
[Enpass](https://www.enpass.io/) Password manager for all platforms.

**Settings:**
![Enpass](images/apps/enpass-settings-1.jpg)
![Enpass](images/apps/enpass-settings-2.jpg)
![Enpass](images/apps/enpass-settings-3.jpg)

#
### Magnet
[Magnet](http://magnet.crowdcafe.com/) The best window manager for Mac.

**Settings:**
![Magnet](images/apps/magnet-settings.jpg)

#
### Bartender 3
[Bartender 3](https://www.macbartender.com/) Organize your menu bar apps.

TODO: **Settings:**

#
### iTerm2
[iTerm2](https://www.iterm2.com/) Terminal emulator for macOS that does amazing things.

**Settings:**
- Profiles > Colors > Color Presets > [Solarized Dark](http://ethanschoonover.com/solarized)
- Change Black Bright color to: `#586e75` (Green Bright)

#
### Alfred 3
[Alfred 3](https://www.alfredapp.com/) Spotlight replacer.

**Settings:**
First disable Spotlight & set Alfred hotkey
- Keyboard > Shortcuts > Spotlight > Show Spotlight search (disable)
- Keyboard > Shortcuts > Spotlight > Show Finder search window (disable)
- Set Alfred hotkey: ⌘ + Space

#
### Atom
[Atom](https://atom.io/) A hackable text editor for the 21st Century.

**My current plugins:**
- [atom-beautify](https://atom.io/packages/atom-beautify)
- [atom-ide-ui](https://atom.io/packages/atom-ide-ui)
- [autocomplete-paths](https://atom.io/packages/autocomplete-paths)
- [busy-signal](https://atom.io/packages/busy-signal)
- [editorconfig](https://atom.io/packages/editorconfig)
- [emmet](https://atom.io/packages/emmet)
- [file-icons](https://atom.io/packages/file-icons)
- [highlight-selected](https://atom.io/packages/highlight-selected)
- [ide-java](https://atom.io/packages/ide-java)
- [ide-php](https://atom.io/packages/ide-php)
- [ide-typescript](https://atom.io/packages/ide-typescript)
- [livereload](https://atom.io/packages/livereload)
- [minimap](https://atom.io/packages/minimap)
- [pigments](https://atom.io/packages/pigments)
- [platformio-ide-terminal](https://atom.io/packages/platformio-ide-terminal)
- [todo-show](https://atom.io/packages/todo-show)

**Disabled plugins:**
- [autoclose-html](https://atom.io/packages/autoclose-html)
- [atom-commander](https://atom.io/packages/atom-commander)
- [color-picker](https://atom.io/packages/color-picker)
- [debug](https://atom.io/packages/debug)
- [goto-definition](https://atom.io/packages/goto-definition)
- [intentions](https://atom.io/packages/intentions)?
- [language-apache](https://atom.io/packages/language-apache)
- [linter](https://atom.io/packages/linter)
- [linter-csslint](https://atom.io/packages/linter-csslint)
- [linter-eslint](https://atom.io/packages/linter-eslint)
- [linter-htmlhint](https://atom.io/packages/linter-htmlhint)
- [linter-php](https://atom.io/packages/linter-php)
- [linter-ui-default](https://atom.io/packages/linter-ui-default)
- [minimap-linter](https://atom.io/packages/minimap-linter)
- [vim-mode-plus](https://atom.io/packages/vim-mode-plus)

TODO: **Settings**:
- Theme: One Dark
- Project Home: ~/Sites
- Font Family: Roboto Mono
- Tab Length: 4
- Scroll Past End > checked
- Menubar > Atom > Install Shell Commands

#
### IntelliJ IDEA
[IntelliJ IDEA](https://www.jetbrains.com/idea/) The Java IDE for developers.

TODO: **Settings:**
- Java 9 (http://www.oracle.com/technetwork/java/javase/downloads/index.html)
- TMC

#
### Navicat Premium
[Navicat Premium](https://www.navicat.com/en/products/navicat-premium) The best GUI database development tool.

TODO: **Settings:**

#
### Noti
[Noti](https://noti.center/) Native macOS notifications from Pushbullet.

#
### Parallels Desktop
[Parallels Desktop](https://www.parallels.com/products/desktop/) Run Windows on Mac.

#
### Slack
[Slack](https://slack.com/) Business chat application.

#
### Spotify
[Spotify](https://www.spotify.com) Music for everyone.

#
### STACK
[STACK](https://www.transip.nl/stack/) Online storage for everyone.

#
### Tower
[Tower](https://www.git-tower.com/mac/) Powerful Git client.

TODO: **Settings:**

#
### Transmit
[Transmit](https://panic.com/transmit/) Nice macOS file transfer.

#
### Trello
[Trello](https://trello.com/) Project management application.

#
### Tunnelblick
[Tunnelblick](https://tunnelblick.net/) Free software for OpenVPN.

#
### iStat Menus
[iStat Menus](https://bjango.com/mac/istatmenus/) Control and monitor your Mac.

You can see the CPU and clock widget in my menu bar:
![Menu Bar](images/visual/menu-bar-1.jpg)

When you click on the CPU widget you see:
![iStat Menus](images/apps/istat-menus.jpg)

#
### CleanMyMac 3
[CleanMyMac 3](https://cleanmymac.com/) The ultimate cleaner for Mac.

#
### Etcher
[Etcher](https://etcher.io/) Burn images to SD cards & USB drives, safely and easily.

#
### MacPass
[MacPass](https://mstarke.github.io/MacPass/) A KeePass client for macOS.

#
### Postman
[Postman](https://www.getpostman.com/) Developing APIs is hard Postman makes it easy.

#
### Simpel Note
[Simpel Note](https://simplenote.com/) The simplest way to keep notes.

#
### Kite
[Kite](https://kite.com/) The smart copilot for programmers.

#
### CheatSheet
[CheatSheet](https://www.mediaatelier.com/CheatSheet/) Know your short cuts.

#
### FireFox
[FireFox](https://www.mozilla.org/nl/firefox/) Firefox Quantum browser.

## Development
### Homebrew
#### Installing
First download you need to install Xcode:
`xcode-select --install`

Now you can install Homebrew:
```bash
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

One thing we need to do is tell the system to use programs installed by Hombrew (in /usr/local/bin) rather than the OS default if it exists. We do this by adding /usr/local/bin to your $PATH environment variable:
```bash
$ echo 'export PATH="/usr/local/bin:$PATH"' >> ~/.bash_profile
```

Make sure Homebrew works to run:
```bash
$ brew doctor
```

#### Usage
- To install a package (Formula):
```bash
brew install <package>
```

- To update Homebrew:
```bash
brew update
```

- To see if any of your packages need to be updated:
```bash
brew outdated
```

(Do this about every month or more often):
```bash
brew update && brew upgrade `brew outdated`
```

- To upgrade a package:
```bash
brew upgrade <package>
```

- Homebrew keeps older versions of packages installed, in case you want to roll back. That rarely is necessary, so you can do some cleanup to get rid of those old versions:
```bash
brew cleanup
```

- To see what you have installed:
```bash
brew list --versions
```

- To search a package:
```bash
brew search <package>
```

#
### Git
Download the [.gitconfig](https://github.com/bartdenhoed/macos-setup/blob/master/.gitconfig) file to optimize Git.

Define Git user:
```bash
$ git config --global user.name "Your Name Here"
$ git config --global user.email "your_email@youremail.com"
```

Save credentials
```bash
$ git config --global credential.helper osxkeychain
```

#
### MAMP
Tutorial: https://getgrav.org/blog/macos-sierra-apache-multiple-php-versions.

My Apache, PHP & MySQL installation script (based on the GetGrav tutorial above): [setup-development.sh](https://github.com/bartdenhoed/macos-setup/blob/master/setup-development.sh)

#### Apache
**Server:**
- Start Apache server: `sudo apachectl start`
- Stop Apache server: `sudo apachectl stop`
- Restart Apache server: `sudo apachectl -k restart`

**Virtual Hosts:**
Virtual hosts file: `/usr/local/etc/httpd/extra/httpd-vhosts.conf`

Example:
```bash
<VirtualHost *:80>
    DocumentRoot "/Users/username/Sites/example"
    ServerName example.dev
</VirtualHost>
```

#### PHP
**php.ini:**
- Set date.timezone in `/usr/local/etc/php/<version>/php.ini` (Part of [setup-development.sh](https://github.com/bartdenhoed/macos-setup/blob/master/setup-development.sh)

**Xdebug:**
Add to `/usr/local/etc/php/<version>/php.ini`
- `xdebug.var_display_max_depth = -1`
- `xdebug.var_display_max_children = -1`
- `xdebug.var_display_max_data = -1`

**Switch PHP:**
- Change PHP version with `sphp <version>`

#### MariaDB
- Start MySQL server: `mysql.server start`
- Stop MySQL server: `mysql.server stop` 
- Set password: `mysql_secure_installation` (Part of [setup-development.sh](https://github.com/bartdenhoed/macos-setup/blob/master/setup-development.sh)
- To have launchd start mysql now and restart at login: `brew services start mariadb` (Part of [setup-development.sh](https://github.com/bartdenhoed/macos-setup/blob/master/setup-development.sh)

#
### Packages
This Homebrew packages I recommend:
- [Xdebug](https://xdebug.org/): `brew install homebrew/php/php<version>-xdebug` (eq: `brew install homebrew/php/php56-xdebug`
- [Completion](): `brew install bash-completion` (`brew tap homebrew/completions`)
- [Dnsmasq](http://www.thekelleys.org.uk/dnsmasq/doc.html):
```bash
brew install dnsmasq
echo 'address=/.test/127.0.0.1' > /usr/local/etc/dnsmasq.conf
sudo brew services start dnsmasq
sudo mkdir -v /etc/resolver
sudo bash -c 'echo "nameserver 127.0.0.1" > /etc/resolver/test'
```
- [Wget]():
```bash
brew install wget
```
- [Tldr]():
```bash
brew install tldr
```
- [Composer]():
```bash
brew install composer
```
- [P7zip](http://brewformulas.org/P7zip):
```bash
install: brew install p7zip
compress: 7z a [filename].7z [folder]
uncompress: 7z x [filename].7z
```
- [YouTube DL](https://rg3.github.io/youtube-dl/):
```bash
install: brew install youtube-dl && brew install ffmpeg
usage: youtube-dl [url] (mp4)
usage: youtube-dl --extract-audio --audio-format mp3 [url] (mp3)
```

#
### Commands
- The `whereis` utility checks the standard binary directories for the specified programs, printing out the paths of any it finds:
- The `which` utility takes a list of command names and searches the path for each executable file that would be run had these commands actually been invoked.

- Show/Hide hidden files in Finder: `⌘ + ⇧ + .`

- Change default screen capture type: `defaults write com.apple.screencapture type jpg` (TODO: In scrypt like mysql-secure-install)
- Encrypt files: `encrypt (change path): openssl enc -aes-256-cbc -e -in {path-in} -out {path-out}`
- Decrypt files: `decrypt (change path): openssl enc -aes-256-cbc -d -in {path-in} -out {path-out}`
- Disable/enable Gatekeeper: `sudo spctl --master-disable` & `sudo spctl --master-enable`

## Links
- **Markdown Cheatsheet:** [https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- **GitHub Hub:** [https://hub.github.com/](https://hub.github.com/)
- **BrewFormulas:** [http://brewformulas.org/](http://brewformulas.org/)
- **Web Development Environment:** [https://mallinson.ca/osx-web-development/](https://mallinson.ca/osx-web-development/)