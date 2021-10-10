# macOS package management (MacPorts, Homebrew)
 
[![Linguistic Mind - macOS package management (MacPorts, Homebrew)](https://img.youtube.com/vi/vC6ykcyTzLg/0.jpg)](https://www.youtube.com/watch?v=vC6ykcyTzLg)
 
Recorded on 2021-04-25<br>
Released on 2021-10-06 #1
 
## Description
 
How to install Macports and Homebrew on a Mac. I go in depth on the peculiarities of each package manager, why you might prefer one over another and explain how to customize their installation in a way that might offer a cleaner way of working with and backing up those package managers.<br>
On Linguistic Mind we talk a lot about various tech solutions to language learning. This video is a general tech guide to help viewers of this channel install software that I talk about in other videos as well as anyone else who would like to learn how to install and use package managers on MacOS.
 
## Chapters
 
[0:00](https://www.youtube.com/watch?v=vC6ykcyTzLg&t=0m0s "Intro") Intro<br>
[0:47](https://www.youtube.com/watch?v=vC6ykcyTzLg&t=0m47s "General information about package managers") General information about package managers<br>
[1:47](https://www.youtube.com/watch?v=vC6ykcyTzLg&t=1m47s "Backup your system") Backup your system<br>
[3:35](https://www.youtube.com/watch?v=vC6ykcyTzLg&t=3m35s "Install Xcode and its command line tools") Install Xcode and its command line tools<br>
[5:42](https://www.youtube.com/watch?v=vC6ykcyTzLg&t=5m42s "Default way of installing MacPorts and Homebrew") Default way of installing MacPorts and Homebrew<br>
[8:17](https://www.youtube.com/watch?v=vC6ykcyTzLg&t=8m17s "Some of the differences between MacPorts and Homebrew") Some of the differences between MacPorts and Homebrew<br>
[14:35](https://www.youtube.com/watch?v=vC6ykcyTzLg&t=14m35s "Customized installation of MacPorts and Homebrew") Customized installation of MacPorts and Homebrew<br>
[17:12](https://www.youtube.com/watch?v=vC6ykcyTzLg&t=17m12s "Instructions for installing to custom prefix on package managers' websites") Instructions for installing to custom prefix on package managers' websites<br>
[19:44](https://www.youtube.com/watch?v=vC6ykcyTzLg&t=19m44s "My scripts for installing MacPorts and Homebrew to custom prefixes]") My scripts for installing MacPorts and Homebrew to custom prefixes]<br>
[20:02](https://www.youtube.com/watch?v=vC6ykcyTzLg&t=20m2s "port-install") port-install<br>
[24:57](https://www.youtube.com/watch?v=vC6ykcyTzLg&t=24m57s "brew-install") brew-install<br>
[26:14](https://www.youtube.com/watch?v=vC6ykcyTzLg&t=26m14s "Setting PATH and MANPATH variables") Setting PATH and MANPATH variables<br>
[35:40](https://www.youtube.com/watch?v=vC6ykcyTzLg&t=35m40s "Basic usage of MacPorts and Homebrew") Basic usage of MacPorts and Homebrew<br>
[52:15](https://www.youtube.com/watch?v=vC6ykcyTzLg&t=52m15s "Outro") Outro
 
## Links
 
MacPorts Guide: https://guide.macports.org/<br>
Homebrew Documentation - Installation: https://docs.brew.sh/Installation
 
Xcode - Support: https://developer.apple.com/support/xcode/<br>
Xcode on AppStore: https://itunes.apple.com/us/app/xcode/id497799835<br>
Download any version of Xcode: https://developer.apple.com/download/
 
rmtree for Homebrew (to remove a package and its dependencies): https://github.com/beeftornado/homebrew-rmtree
 
Setting PATH tutorial (Corey Schafer): https://www.youtube.com/watch?v=PUIE7CPANfo&t=8m44s
 
## Notes
 
I haven't tested this, but when installing MacPorts to a custom prefix, it might make sense to enable startup items if that will be your main installation of MacPorts. Instructions for installing multiple MacPorts copies recommend setting the option --without-startupitems to "avoid conflicts in /Library/LaunchAgents or /Library/LaunchDaemons". I installed my copy of MacPorts with that option set and haven't needed to enable startup items yet, but it might become necessary. <br>
My script 'port-install' has the option set, so if you want to try unsetting it, you could change it in the script yourself. But, like I said, I haven't tested this.<br>
Check out this section of the MacPorts Guide for more information: https://guide.macports.org/#installing.macports.source.multiple
 
## Support Linguistic Mind
 
Patreon: https://patreon.com/linguisticmind<br>
Ko-fi: https://ko-fi.com/linguisticmind
