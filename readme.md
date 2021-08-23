# xcsimapps
### Apps Designed for the Xcode Simulator, not on real devices
## What?
Xcode on macOS offers simulators, mainly to test applications. These simulators do not emulate the native devices, so apps compiled for the simulator aren't ARM-based. They're like normal apps, but x86_64 based instead.
## Why?
Simulators are more flexible, thanks to the entire system "partition" being inside a folder:
```/Applications/Xcode.app/Contents/Developer/Platforms/<insert platform>.platform/Library/Developer/CoreSimulator/Profiles/Runtimes/< insert runtime>.simruntime/Contents/Resources/RuntimeRoot```
and
```/Library/Developer/CoreSimulator/Profiles/Runtimes/<insert simruntime>/Contents/Resources/RuntimeRoot```
This way, system files can be modified easily, offering a jailbreak-like experience. It's also fun to just run iOS, tvOS, and watchOS on your computer.
## How?
Install the application by placing it in the `/Applications/` folder of any RuntimeRoot. The paths above show runtime root folders, at least in Xcode 12.
## Source codes?
I don't plan to showcase source codes for the apps published here, but I might.
