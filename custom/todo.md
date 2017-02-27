#to automate or do manually on each install

#STEPS

## begin setup

1. install chrome, login to correct chrome profile
1. start up windows update
1. authenticate with lastpass
1. navigate to this repo
1. download, unzip, and install dvorak num switch, set it as the default keyboard in the 'languages' setting
1. download and run all registry edit files.

## while updating

### ui - taskbar

1. right click taskbar -> settings:
    1. use small taskbar buttons - ON
    1. replace command prompt with powershell on right click start - ON
1. set cortana search to be an icon - right click search bar -> cortana -> show cortana icon
1. in cortana settings: (open cortana search, click the settings wheel on the left)
    1. Lock screen (use even when my screen is locked) - OFF
    1. Taskbar Tidbits (cortana popup ads) - OFF

### other

1. services console - disable Windows Search service, and SuperFetch service
1. in administrative settings:
    1. "Computer Configuration -> Administrative Templates -> Windows Components -> Search -> Do not allow Web Search : ENABLED"
1. cortana search 'appearance and performance' -> click first result
    1. click "Adjust for best performance"
    1. click "custom"
    1. check "Enable Peek"
    1. check "Show window contents while dragging"
1. adjust date/time to current timezone

### software

1. [download + install sumatrapdf](https://www.sumatrapdfreader.org/free-pdf-reader.html)
1. [download + install 7zip](http://www.7-zip.org/download.html)

#### Media Center PC
1. [download + install vlc](http://www.videolan.org/vlc/index.html)
1. [download + install NP++](https://notepad-plus-plus.org/download/)

#### Coding PC
1. [download + install sublime](https://www.sublimetext.com/3)

## after update

1. restart
1. read the README in the parent dir for instructions on running scripts
1. run each script in the 'scripts' directory.

## configuring software

### Notepad++
1. default spacing 4 spaces
1. dark color theme
1. use left nav bar, hide tab bar

### sublime

1. install package control
1. install autospell
1. install lightning
1. install whitespace
1. copy over configuration files into ```AppData/Roaming/SublimeText3```

## bitlocker

1. (if applicable) to enable use without TPM: Local Computer Policy > Computer Configuration > Administrative Templates > Windows Components > BitLocker Drive Encryption > Operating System Drives -> require additional authentication at startup: ENABLED

## faronix deepfreeze

## Windows subsystem for linux (after "creator" update)

1. search for developer, enable developer mode
1. search for add features, enable windows subsystem for linux
1. restart
1. type bash in a new powershell prompt
1. wait for download, set a username and password
1. apt-get -y update
1. apt-get -y upgrade
1. apt-get install -y git
