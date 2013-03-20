# TrackballWorks™ Loader

Simple bootstrapping code to get Kensington TrackballWorks™ working on OS X Lion (10.7) and newer.


## Description

Due to changes in recent versions of OS X, The Kensington TrackballWorks™ driver no longer starts automatically. You can manually start it by opening the TrackballWorks System Preference pane, but who wants to do that every time they start their computer. This little helper bypasses the problem, automatically loading the driver every time you log in.

You must install the TrackballWorks™ driver separately, which you can [download here](http://www.kensington.com/kensington/ce/ca/s/1517/trackballworks%E2%84%A2-software-download.aspx).


## Installation

1. Run the installer package.
2. Enjoy you renewed status as a (track)baller.
3. Bug Kensington to update their drivers so we don't need this anymore.


## Manual Installation

If for some reason you don't want to use the included installer, you can follow these steps to manually install the loader.

1. Copy src/com.peanuthut.TrackballWorks.load.plist to /Library/LaunchAgents.
2. In a terminal window type: "launchctl load /Library/LaunchAgents/com.peanuthut.TrackballWorks.load.plist".
3. Enjoy you renewed status as a (track)baller.
4. Bug Kensington to update their drivers so we don't need this anymore.


## Uninstallation

1. Delete /Library/LaunchAgents/com.peanuthut.TrackballWorks.load.plist.
2. Reboot.
3. Enjoy the new fixed version of TrackballWorks that Kensington has bestowed upon us.


## Known Bugs

The default 'Back' and 'Forward' actions that get mapped to the secondary buttons no longer work, most likely due to changes in the OS. Other actions like Exposé and Snippets work without any problems.


## License

MIT or something... do whatever the hell you want with it, just don't complain if your computer turns into a flaming ball of death.
