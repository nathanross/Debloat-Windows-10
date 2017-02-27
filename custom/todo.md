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

### software

1. install and configure a text editor (sublime or notepad)
1. download + install vlc
1. download + install sumatrapdf

## after update

1. restart
1. read the README in the parent dir for instructions on running scripts
1. run each script in the 'scripts' directory.
