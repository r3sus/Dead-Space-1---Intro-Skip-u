# Dead Space 1 - Intro Skip
A simple hack to skip an intro in Dead Space 1.  

Usage: Download project and extract contents of `Release` in game folder. 

[Direct link](https://github.com/r3sus/Dead-Space-1---Intro-Skip-u/archive/refs/heads/main.zip)

# Technical details

It is mainly SuiMachine's work with minor modifications. 

Current ds1 no intro dll uses static address for patching, which seems not working for Origin (altho I've tested it). The version for ds2 is more flexible and does replacement anywhere the target is. So this is version of ds2 modified for ds1. Hopefully this dll will work with Origin version, as well for any other. Compatible with mouse fix by default (changed name to version.dll).

Altho the code was changed, the previous Release is used with manually patched `IntroSkip.asi` for ds1.

For other applicable dll names see: [link](https://en.wikipedia.org/wiki/Microsoft_Windows_library_files#Win32_API), most would work.

# Credits
* SuicideMachine (programming)
* r3sus (reverse engineering / testing)
