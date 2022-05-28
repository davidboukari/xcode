# xcode


## Sample 1
* https://developer.apple.com/library/archive/referencelibrary/GettingStarted/DevelopiOSAppsSwift/ConnectTheUIToCode.html#//apple_ref/doc/uid/TP40015214-CH22-SW1

## Check the swift version
* https://stackoverflow.com/questions/30790188/how-do-i-see-which-version-of-swift-im-using
* project name -> building settings -> swift compiler language


## TableViewMacOSX
* https://medium.com/@kicsipixel/simple-nstableview-using-model-in-swift-5-7db0685f2615


## Exec external cmd
* https://scriptingosx.com/2016/04/build-an-application-to-run-a-shell-command-in-xcode-and-swift-part-1/

## Troubleshooting
```
sudo port search openssh
Password:
Error: Current platform "darwin 21" does not match expected platform "darwin 19"
Error: If you upgraded your OS, please follow the migration instructions: https://trac.macports.org/wiki/Migration
OS platform mismatch
    while executing
"mportinit ui_options global_options global_variations"
Error: /opt/local/bin/port: Failed to initialize MacPorts, OS platform mismatch
poseidon:aws davidboukari$ sudo xcodebuild -license
xcode-select: error: tool 'xcodebuild' requires Xcode, but active developer directory '/Library/Developer/CommandLineTools' is a command line tools instance
```
=>
```
sudo xcode-select -s /Applications/Xcode.app/Contents/Developer
```
