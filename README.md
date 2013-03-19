# TrackballWorks Loader

Simple bootstrapping code to get Kensington TrackballWorks working on OSX Mountain Lion.


## Description

The Kensington TrackballWorks driver (mostly) works in Lion and Mountain Lion, however a bug prevents it from automatically loading. You can manually start it by opening the TrackballWorks System Preference pane. This script bypasses the problem, automatically loading the drivers every time you log in.

Currently this consists of a simple launchctl plist file, but an installer will follow shortly.


## Installing 

1. Copy com.peanuthut.TrackballWorks.load.plist to /Library/LaunchAgents.
2. Reboot. (You can probably just log out and back in again - but I'm too lazy to test it.)
3. Enjoy you renewed status as a (track)baller.
4. Bug Kensington to update their drivers so we don't need this anymore.
