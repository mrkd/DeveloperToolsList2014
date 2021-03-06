DeveloperToolsList2014
======================

List of Software and Tools used

# Hardware
  * MacBook Pro Retina, 13-inch, Late 2013
  * 2.8 GHz Intel Core i7
  * 16 GB 1600 MHz DDR3
  * Intel Iris Graphics
  * Display - 13-inch (3360 x 2100)
  * 1 TB SSD 


# Software

## Browsers

I have used Chrome for the past few years. Recently it has been using more resources and seemingly slowing down a bit. On a laptop this causes more battery drain. Apple has put quite a bit of effort into making [Safari more energy efficient](https://www.apple.com/osx/advanced-technologies/) since the release of OS X Mavericks so I try to use Safari more and more.

* [Safari (preinstalled on Macs)](https://www.apple.com/safari/)
* [Chrome](https://www.google.com/chrome/browser/)
* [Firefox](https://www.mozilla.org/en-US/firefox/new/)
* [uBlock](https://www.ublock.org)
  * [uBlock Chrome](https://chrome.google.com/webstore/detail/ublock/epcnnfbjfcgphgdmggkamkmgojdagdnn/related)
* [Ghostery](https://www.ghostery.com/en/)


## App Launchers
* Alfred (pending removal: this has been [Sherlocked](http://www.urbandictionary.com/define.php?term=sherlocked) in OS X Yosemite)
  
  This has been built into Spotlight for the Yosemite OS X release. I'll review it this Fall to see if it can replace Alfred.

## Security

### Password Managers

Lastpass was the first password manager that I used. It has worked well for me, but I thought I would try out 1Password since they have a native Mac app.

1Password does offer [sync](https://guides.agilebits.com/1password-mac/5/en/topic/sync-preferences) through Dropbox, iCloud or folder syncing. With folder syncing you can keep your vault off any third party servers.

I may switch to 1Password since they do offer more control over sync.

* [Lastpass](https://lastpass.com)
* [1Password](https://agilebits.com/onepassword)


## Data Sync / Backup
  
  Currently I am using both Dropbox and Google Drive for file syncronization across multiple devices.

  * [Dropbox](http://dropbox.com/)
  * [Google Drive](http://www.google.com/drive/)
  
 Crashplan is the service I use for offsite backup. They have an unlimited family plan that I am currently using for  my multiple computers.

  * Crashplan 
    * http://www.code42.com/crashplan/


## Dev Tools

### homebrew

  * [homebrew](http://brew.sh/) The missing package manager for OS X.
  
  Cakebrew is a GUI for homebrew. I haven't tried it yet, but put it here so I remember to try it at some point.
  * https://www.cakebrew.com/

### iOS Development

  * [Prepo](https://itunes.apple.com/us/app/prepo/id476533227?mt=12&uo=4&at=10lqb3)
    * create app icons for all sizes needed. Supports @1x, @2x, and @3x
  * [iOS Console](http://lemonjar.com/iosconsole/)
    * nice way to view iOS console for connected devices
 
#### UI View Debuggers
 
 There are two main applications available [Spark Inspector](http://sparkinspector.com/) and [Reveal App](http://revealapp.com/). Currently I use Spark Inspector.
 

  * [Spark Inspector](http://sparkinspector.com/)
    * debugs Notifications as well as UI.
  * [Reveal App](http://revealapp.com/)


### Text Editors

Sublime Text is my preffered text editor. VSCode is making progress, especially with its built in Node debugging.
No other text editors can match Sublime Text's multiple cursors.

* Sublime Text - https://www.sublimetext.com/
* Visual Studio Code - https://code.visualstudio.com/
* Atom - https://atom.io/

### Ruby

  * Ruby environment mangement [rbenv](https://github.com/sstephenson/rbenv)
 
Node
  * nvm - https://github.com/creationix/nvm

### Source Control
I use [git](http://git-scm.com/) for all my version control.

#### Git GUIs

Source tree is my primary Git GUI that I use. It works very well on the Mac, but it does not perform well on Windows. Another option [Tower](http://www.git-tower.com/) has release version 2. I am keeping on eye on that one, but for now Sourcetree works well for me.

  * [Sourcetree](http://www.sourcetreeapp.com/)
  * [Tower](http://www.git-tower.com/)

### Other


* Charles Proxy
  * An http proxy debug tool
  * http://www.charlesproxy.com/latest-release/download.do
* [f.lux](https://justgetflux.com/)
  
  Adapts color of your display to the time of day. This helps out when coding late into the evenings! They even have a link to some [research](https://justgetflux.com/research.html) if you are skeptical.

## Graphics - Image Editing

* [Acorn](http://www.flyingmeat.com/acorn/)
* [Sketch](http://bohemiancoding.com/sketch/)
* [Pixelmator](http://www.pixelmator.com/)

## Utilities
* [Keyboard Maestro](http://www.keyboardmaestro.com/main/)
  * Macros
    * http://www.keyboardmaestro.com/main/macro-library#type-clipboard
      * this is handy for entering serial numbers or passwords into application that disabled pasting text (OS X            does this when trying to decrypt a disk with a key (password)
* [iStat Menu Meters](http://bjango.com/mac/istatmenus/)
* (<a href="https://itunes.apple.com/us/app/go2shell/id445770608?mt=12&uo=4" target="itunes_store">Go2Shell - Alice Dev Team</a>)
* [Bartender](http://www.macbartender.com/)
 * hide unnecessary menu bar items - clean up that clutter!
* [XtraFinder](http://www.trankynam.com/xtrafinder/)
* [Dropzone 3](https://aptonic.com/)

### Managing hard drive space usage
* [DaisyDisk](https://itunes.apple.com/us/app/daisydisk/id411643860?mt=12&uo=4) $9.99 Mac App Store
* [Disk Inventory X](http://www.derlien.com/)
  * These programs allow you to view where all of your hard drive space is being used. It scans your hard drive
    and gives a nice visual representation of your hard drive space usage.
  

* XtraFinder adds nice little features to the Finder app.
    * Arrange folders on top
    * Cut & Paste
    * "Copy Path", "Refresh", "New File"
  
  My XtraFinder preferences: [XtraFinder-Preferences.plist](config-files/XtraFinder-Preferences.plist)
* Quick Look Plugins
  * https://github.com/whomwah/qlstephen

* 

## Apple Development Resources

* http://support.apple.com/kb/HT6331?viewlocale=en_US&locale=en_US
* CPA
  * [Cocoa Packet Analyzer](http://www.tastycocoabytes.com/cpa/index.php) is a native OS X implementation of a network protocol analyzer and packet sniffer.

## Automated Setup References

* [OS X 10.10 Yosemite Development Setup](http://fredkelly.net/articles/2014/10/19/developing_on_yosemite.html)
* http://lapwinglabs.com/blog/hacker-guide-to-setting-up-your-mac
* https://github.com/bkuhlmann/osx
* 

## System Administration

* [github repo with list of sysadmin tools](https://github.com/n1trux/awesome-sysadmin)
