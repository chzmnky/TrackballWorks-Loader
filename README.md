# TrackballWorks™ Loader

Simple bootstrapping code to get Kensington TrackballWorks™ working on OSX (Mountain) Lion.


## Description

Due to changes in recent versions of OS X, The Kensington TrackballWorks™ driver no longer starts automatically. You can manually start it by opening the TrackballWorks System Preference pane, but who wants to do that every time they start their computer.

This script bypasses the problem, automatically loading the driver every time you log in. Currently this consists of a simple launchctl plist file, but an installer will follow shortly.

You must install the TrackballWorks™ driver separately, which you can [download here](http://www.kensington.com/kensington/ce/ca/s/1517/trackballworks%E2%84%A2-software-download.aspx).


## Installing 

1. Copy com.peanuthut.TrackballWorks.load.plist to /Library/LaunchAgents.
2. Reboot. (You can probably just log out and back in again - but I'm too lazy to test it.)
3. Enjoy you renewed status as a (track)baller.
4. Bug Kensington to update their drivers so we don't need this anymore.


## Uninstalling

1. Delete /Library/LaunchAgents/com.peanuthut.TrackballWorks.load.plist.
3. Reboot.
2. Enjoy the new fixed version of TrackballWorks that Kensington has bestowed upon us.


## Known Bugs

The default 'Back' and 'Forward' actions that get mapped to the secondary buttons no longer work, most likely due to changes in the OS. Other actions like Exposé and Snippets appear to be unaffected.


## License

MIT or something... do whatever the hell you want with it, just don't complain if your computer turns into a flaming ball of death.
