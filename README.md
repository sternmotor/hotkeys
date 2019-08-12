# Desktop Hotkey Guideline
Keyboard shortcut proposal for easy-to-learn, quick, mouse-free access with hands on keyboard under MacOS, Linux Desktops and Windows.

## Description
Basically, all keyboard shortcuts listed here are just proposals. These have to be implemented in the MacOS/Linux/Windows Desktop. 

There is some effort put in finding key combos which do not interfere with genuine setup under MacOS/Linux/Windows, but some adjustments may have to be taken. For example the unified approach to have `WIN/CMD + Cursor Keys` resize and move windows does not work under macOS where `CMD + Cursor Keys` cycles through desktop spaces. This can be switched to `CTRL + Cursor Keys` easily - just do it in case you happen to work on MacOS and linux desktop.

All gestures which look too hard to learn easly are left out. 

Following tools can be used to realize those proposals - examples will be provided in future.

* MacOS: use [BetterTouchTool](https://folivora.ai/) - configuration is planned to be included in this repository in future
* Linux: Both [Cinnamon Desktop](https://linuxmint.com/download.php) and [Fluxbox|http://fluxbox.org/]  offer some good support for manipulating keyboard shortcuts. For some actions, scripts are needed. These will be provided here in future.
* Windows: oops, sorry. Please support me with some insight on [AutoIT](https://www.autoitscript.com/site/autoit/) or similar - I have no experiences here

Words and abbreviations used here:

* Desktop: virtual desktop (fullscreen apps and space in mac os, workspaces in X windows) - may contain multiple screens
* Screen: for a two-monitor systems, you have two screens (left and right)
* U/D/L/R: arrow keys up/ down/ left/right
* MWheel L/R: mouse wheel click left/right
* ThumbB U/D: mouse thumb button up/down

For some parts, mouse wheel click respectively thumb button action proposals have been added which fit in nicely. Make sure to use a mouse with support of mousewheel click (left/right) and a set of two thumb buttons like for example a Logitech M500.


## Desktop Navigation (mainly CTRL)

|Description              | x86 Keyboard            | MacOS Keyboard          |Mouse Action             |
|-------------------------|-------------------------|-------------------------|-------------------------|
|Switch desktop/space     |CTRL + L/R               |CTRL + L/R               |MWheel L/R               |
| + move window and scope |CTRL + U/D               |CTRL + U/D               |CTRL + MWheel L/R        |
| + move window           |CTRL + ALT + L/R         |CTRL + CMD + L/R         |CTRL + ALT/CMD L/R       |
|Switch to desktop 1      |CTRL + 1                 |CTRL + 1                 |                         |
|Switch to desktop 2      |CTRL + 2                 |CTRL + 2                 |                         |


## Window Move Resize (mainly WIN/CMD)

|Description              | x86 Keyboard            | MacOS Keyboard          |Mouse Action             |
|-------------------------|-------------------------|-------------------------|-------------------------|
|Half size left/right edge|WIN + L/R                |CMD + L/R                |                         |
|Quarter size in corner   |ALT + WIN + L/R/U/D      |OPTION + CMD + L/R/U/D   |                         |
|Maximize window          |WIN + U                  |CMD + U                  |                         |
|Restore original size    |WIN + D                  |CMD + D                  |                         |
|Toggle full screen       |WIN + Enter              |CMD + Enter              |                         |
|Toggle sticky window     |ALT + WIN + Enter        |OPTION + CMD + Enter     |                         |
|Cycle through app windows|WIN + </>                |CMD + </>                |WIN/CMD + MWheel L/R     |
|Cycle through apps       |ALT + Tab                |OPTION + Tab             |ALT/OPTION + MWheel L/R  |


## Window Tabs (ALT/ OPTION modifier)

|Description              | x86 Keyboard            | MacOS Keyboard          |Mouse Action             |
|-------------------------|-------------------------|-------------------------|-------------------------|
|Switch Tabs              |ALT + </>                |OPTION + </>             |ThumbB U/D               |


## Applications (ALT/CMD/WIN)
Programs and utilities used while working. Make sure to switch to the desktop where
an application is running (by script or using MacOS)


|Description              | x86 Keyboard            | MacOS Keyboard          |
|-------------------------|-------------------------|-------------------------|
|Main Terminal            |CTRL + Esc               |CTRL + Esc               |
|Second Terminal          |SHIFT + Esc              |SHIFT + Esc              |
|Editor                   |WIN + Esc                |CMD + Esc                |
|Main Browser             |CTRL + Space             |CTRL + Space             |
|Secondary Browser        |CTRL ALT + Space         |SHIFT + Space            |
|Mail                     |WIN + Space              |OPTION + Space           |
|Calendar                 |WIN + ALT + Space        |OPTION + CMD + Space     |
|Calculator               |ALT + Space              |CMD + Space              |
|File Manager             |WIN + E                  |CMD + E                  |
|Music Player             |WIN + M                  |CMD + M                  |


## System


|Description              | x86 Keyboard            | MacOS Keyboard          |
|-------------------------|-------------------------|-------------------------|
|Close Window             |CTRL + w                 |CTRL + w                 |
|Copy/Cut/Paste           |WIN + C/X/V              |CMD + C/X/V              |
|Exit application         |ALT + F4                 |- (remove `OPTION + q`!  |
|Lock screen              |CTRL + WIN + ALT + U     |CTRL + OPTION + CMD + U  |
|Open Tab                 |CTRL + t                 |CTRL + t                 |
|Restart                  |CTRL + WIN + ALT + L     |CTRL + OPTION + CMD + L  |
|Screen Shot (Area)       |WIN + SHIFT + S          |CMD + SHIFT + S          |
|Search and Run           |WIN + R, ALT + Space     |CMD + Space              |
|Shut down                |CTRL + WIN + ALT + D     |CTRL + OPTION + CMD + D  |
|Sleep                    |CTRL + WIN + ALT + R     |CTRL + OPTION + CMD + R  |
|Switch Application       |(SHIFT + ) ALT + Tab     |(SHIFT + ) OPTION + TAB  |
|Zoom                     |CTRL + +/-               |CMD  + +/-               |

# Appendix: MacOs Trackpad/ Magic Mouse

MacOS users may find much use in [running a trackpad or magic mouse](https://medium.com/@arpitpalod/i-am-so-in-love-with-my-mac-trackpad-c3bbcecef41d) where 1/2/3 Finger swipes and 2 Finger TipTap may be configured via [BetterTouchTool](https://folivora.ai/) - this rocks but I gave it up in favour of a simple mouse which works on all systems.

General idea:
* 3Finger Swipes and Command-Key-Combinations act on applications, tabs, windows
* 4Finger Swipes and Control-Key-Combinations act on spaces and mission control
* 5Finger Swipes act on mac os system
* left-right movements and arrows switch tabs, windows and spaces
* up/down movements open/close something
* up is fullscreen, down restores size
* 3Finger tap and double tap is reserved for application-specific setup

# TODO

Example configurations and scripts for
* xorg
* mac os BTT
* windows (any chance to get this working?)

