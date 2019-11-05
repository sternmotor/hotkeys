Desktop Hotkey Proposal
=======================
Keyboard shortcut proposal for easy-to-learn, quick, mouse-free access with hands on keyboard under MacOS, Linux Desktops and Windows.

Description
-----------

Basically, all keyboard shortcuts listed here are just proposals. These have to be implemented in the MacOS/Linux/Windows Desktop by scripts or software. Following tools can be used to realize those proposals:

* MacOS: use [BetterTouchTool](https://folivora.ai/) - configuration is planned to be included in this repository in future
* Linux: Both [Cinnamon Desktop](https://linuxmint.com/download.php) and [Fluxbox|http://fluxbox.org/]  offer some good support for manipulating keyboard shortcuts. For some actions, scripts are needed. Some are provided in this repository.
* Windows: oops, sorry, no idea how to implement window manipulation and desktop management here. Maybe [AutoIT](https://www.autoitscript.com/site/autoit/)?

Key combos should not interfere with genuine setup under MacOS/Linux/Windows, but some adjustments may have to be taken. For example the unified approach to have `WIN/CMD`+`Cursor Keys` resize and move windows does not work under macOS where `CMD`+`Cursor Keys` cycles through desktop spaces. This can be switched to `CTRL`+`Cursor Keys` easily - just do it in case you happen to work on MacOS and linux desktop.

The modifiers work blind without needing to now if its mac or linux. IBM keyboard `CTRL`,`WIN`,`ALT` modifier keys are applied in the same order as `CTRL`,`ALT`,`CMD` on Apple keyboard. 

All gestures which look too hard to learn easily are left out. 


Words and abbreviations used here:

* Desktop: virtual desktop (fullscreen apps and space in mac os, workspaces in X windows) - usually across monitors
* Monitor: one desktop usually spawns across multiple monitors
* U/D/L/R: arrow keys up/ down/ left/right
* Wheel L/R: mouse wheel click left/right
* Thumb U/D: mouse thumb button up/down

For some parts, mouse wheel click respectively thumb button action proposals have been added which fit in nicely. Make sure to use a mouse with support of mousewheel click (left/right) and a set of two thumb buttons like for example a Logitech M500.

Preparations
------------

### MacOS

* Settings > Mission Control > Disable "Monitors use different spaces"
* BetterTouchTool: Disable `ALT`+`q` for closing apps - this is easily typed when trying to type `@`. Replace by `ALT`+`F4`.


Desktop Navigation ("x--", "xx-")
---------------------------------

Switching desktops  bases on using `CTRL` key, combined like
* `CTRL` + left/right or numbers for switching desktops  (memorize modifier key pattern "x--")
* `CTRL` + `WIN` (Mac: `ALT`) + left/right or numbers for moving windows between desktops (memorize modifier key pattern "xx-")


|Description              |Linux IBM Keyboard       | MacOS Keyboard          |Mouse Action                    |
|-------------------------|-------------------------|-------------------------|--------------------------------|
|Switch desktop/space     |`CTRL`+`L/R`             |`CTRL`+`L/R`             |`CTRL + Wheel L/R`              |
|+ move window to desktop |`CTRL`+`WIN`+`L/R`       |`CTRL`+`ALT`+`L/R`       |`CTRL`+`WIN/ALT`+`Wheel L/R`    |
|Switch to desktop 1      |`CTRL`+`1`               |`CTRL`+`1`               |                                |
|+ move window to desktop |`CTRL`+`WIN`+`1`         |`CTRL`+`ALT`+`1`         |                                |
|Switch to desktop 2      |`CTRL`+`2`               |`CTRL`+`2`               |                                |


Monitor Navigation ("^x-")
--------------------------

* `SHIFT` + `WIN` (Mac: `ALT`) + left/right for moving windows between monitors (memorize modifier key pattern "^x-")

|Description              |Linux IBM Keyboard       | MacOS Keyboard          |Mouse Action                    |
|-------------------------|-------------------------|-------------------------|--------------------------------|
|Move window to monitor   |`SHIFT`+`WIN`+`L/R`      |`SHIFT`+`ALT`+`L/R`      |`SHIFT`+`WIN/ALT`+`Wheel L/R`   |



Window Move Resize ("-x-", "-xx")
---------------------------------

Resizing and moving windows bases on using `WIN`/ `ALT` key, combined like
* Half size, maximize, move: memorize modifier key pattern "-x-"
* Quarter size: memorize modifier key pattern "-xx"
* Mouse resize window: memorize modifier key pattern "-x-"
* Mouse move window: memorize modifier key pattern "-xx"


|Description              |Linux IBM Keyboard       | MacOS Keyboard          |Mouse Action             |
|-------------------------|-------------------------|-------------------------|-------------------------|
|Half size left/right edge|`WIN`+`L/R`              |`ALT`+`L/R`              |                         |
|Maximize window          |`WIN`+`U`                |`ALT`+`Up`               |                         |
|Restore original size    |`WIN`+`D`                |`ALT`+`Down`             |                         |
|Quarter size in corner   |`WIN`+`ALT`+`L/R/U/D`    |`ALT`+`CMD`+`L/R/U/D`    |                         |
|Full screen              |`WIN`+`Enter`            |`ALT`+`Enter`            |                         |
|Sticky window            |`WIN`+`ALT`+`Enter`      |`ALT`+`CMD`+`Enter`      |                         |
|Freely resize window     |                         |                         |`WIN`/`ALT`+ MouseMove   |
|Freely move window       |                         |            |`WIN`/`ALT`+ `ALT`/`CMD`+ MouseMove   |


Window Tabs ("x-x")
--------------------------------

Switching window tabs or window instances bases on `ALT`/`CMD` key, combined like

Switching desktops  bases on using `CTRL` key, combined like
* `CTRL` + left/right or numbers for switching desktops  (memorize modifier key pattern "x--")
* `CTRL` + `WIN`/`ALT` + left/right or numbers for moving windows between desktops (memorize modifier key pattern "xx-")

In single application windows (e.g. browsers), navigate tabs with the key 
combinations below. For single-window applications (standard terminal, text 
editors) cycle through application instances.


|Description              |Linux IBM Keyboard       | MacOS Keyboard          |Mouse Action             |
|-------------------------|-------------------------|-------------------------|-------------------------|
|Tab/app window left/right|`ALT`+`L/R`              |`CMD`+`L/R`              |`Thumb U/D`              |
|                         |`ALT`+`</>`              |`CMD`+`</>`              |                         |
|Switch to tab 1          |`ALT`+`1`                |`CMD`+`1`                |                         |
|Cycle Tabs               |`CTRL`+`Tab`             |`CTRL`+`Tab`             |                         |
|Open Tab                 |`CTRL`+`t`               |`CTRL`+`t`               |`CTRL`+`ALT`/`CMD`+`Thumb U`|
|Close Tab                |`CTRL`+`w`               |`CTRL`+`w`               |`CTRL`+`ALT`/`CMD`+`Thumb D`|


Applications 
------------
```
Programs and utilities used while working. This modifiers work blind without needing to now if its mac or linux


|Description              |Linux IBM Keyboard         | MacOS Keyboard            |
|-------------------------|---------------------------|---------------------------|
|Main Terminal            |`CTRL`+`Esc`               |`CTRL`+`Esc`               |
|Second Terminal          |`SHIFT`+`Esc`              |`SHIFT`+`Esc`              |
|Calulator                |`SHIFT`+`Tab`              |`SHIFT`+`Tab`              |
|Main browser             |`CTRL`+`WIN`+`Space` (xx-) |`CTRL`+`ALT`+`Space` (xx-) |   
|Secondary browser        |`WIN`+`ALT`+`Space`  (-xx) |`ALT`+`CMD`+`Space`  (-xx) |  
|Mail                     |`CTRL`+`ALT`+`Space` (x-x) |`CTRL`+`CMD`+`Space` (x-x) |  
|Messenger                |`CTRL`+`WIN`+`ALT`+`Space` |`CTRL`+`ALT`+`CMD`+`Space` |  


Productivity
------------

Common shortcuts for working in desktop environment


|Description              |Linux IBM Keyboard         | MacOS Keyboard              |
|-------------------------|---------------------------|-----------------------------|
|Screen Shot (Area)       |`CTRL`+`SHIFT`+`s`  (x--)  |`CMD`+`SHIFT`+`s`    (--x)   |
|                         |`CTRL`+`Print`      (x--)  |                             |
|Copy/Cut/Paste           |`CTRL`+`c/x/v`      (x--)  |`CMD`+`c/x/v`        (--x)   |
|Show clipboard history   |`CTRL`+`WIN`+`v`    (x--)  |`CMD`+`ALT`+`v`      (--x)   |
|Search and Run           |`CTRL`+`Space`      (x--)  |`CMD`+`Space`        (--x)   |
|Zoom Text                |`CTRL`+`+/-`        (x--)  |`CMD `+`+/-`         (--x)   |


## System


### Applications

|Description              |Linux IBM Keyboard         | MacOS Keyboard           |
|-------------------------|---------------------------|--------------------------|
|Switch application       |`ALT`+`Tab` (--x)          |`CMD`+`Tab`  (--x)        |
|Cycle application windows|`ALT`+`</>` (--x)          |`CMD`+`</>`  (--x)        |
|Exit application         |`ALT`+`F4`  (--x)          |`CMD`+`F4`   (--x)        |
|New application window   |`CTRL`+`n`  (x--)          |`CMD`+`n`    (--x)        |

### Finder/ File manager settings

|Description              |Linux IBM Keyboard         | MacOS Keyboard           |
|-------------------------|---------------------------|--------------------------|
|Directory Up             |`CTRL`+`U`         (x--)   |`CMD`+`U`         (--x)   |
|Show hidden files        |`CTRL`+`h`         (x--)   |`CMD`+`h`         (--x)   |
|Create directory         |`CTRL`+`SHIFT`+`d` (^x--)  |`CMD`+`SHIFT`+`d` (^--x)  |
|Create file              |`CTRL`+`SHIFT`+`f` (^x--)  |`CMD`+`SHIFT`+`f` (^--x)  |

### System (xxx)

|Description              |Linux IBM Keyboard         | MacOS Keyboard           |
|-------------------------|---------------------------|--------------------------|
|Lock screen              |`CTRL`+`WIN`+`ALT`+`Up`    |`CTRL`+`ALT`+`CMD`+`Up`   |
|Sleep                    |`CTRL`+`WIN`+`ALT`+`Right` |`CTRL`+`ALT`+`CMD`+`Down` |
|Restart computer         |`CTRL`+`WIN`+`ALT`+`Left`  |`CTRL`+`ALT`+`CMD`+`Left` |
|Shut down                |`CTRL`+`WIN`+`ALT`+`Down`  |`CTRL`+`ALT`+`CMD`+`Right`|
