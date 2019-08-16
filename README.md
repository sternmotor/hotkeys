# Desktop Hotkey Proposal
Keyboard shortcut proposal for easy-to-learn, quick, mouse-free access with hands on keyboard under MacOS, Linux Desktops and Windows.

## Description
Basically, all keyboard shortcuts listed here are just proposals. These have to be implemented in the MacOS/Linux/Windows Desktop. 

There is some effort put in finding key combos which do not interfere with genuine setup under MacOS/Linux/Windows, but some adjustments may have to be taken. For example the unified approach to have `WIN/CMD`+`Cursor Keys` resize and move windows does not work under macOS where `CMD`+`Cursor Keys` cycles through desktop spaces. This can be switched to `CTRL`+`Cursor Keys` easily - just do it in case you happen to work on MacOS and linux desktop.

All gestures which look too hard to learn easly are left out. 

Following tools can be used to realize those proposals - examples will be provided in future.

* MacOS: use [BetterTouchTool](https://folivora.ai/) - configuration is planned to be included in this repository in future
* Linux: Both [Cinnamon Desktop](https://linuxmint.com/download.php) and [Fluxbox|http://fluxbox.org/]  offer some good support for manipulating keyboard shortcuts. For some actions, scripts are needed. These will be provided here in future.
* Windows: oops, sorry. Please support me with some insight on [AutoIT](https://www.autoitscript.com/site/autoit/) or similar - I have no experiences here

Words and abbreviations used here:

* Desktop: virtual desktop (fullscreen apps and space in mac os, workspaces in X windows) - may contain multiple screens
* Screen: for a two-monitor systems, you have two screens (left and right)
* U/D/L/R: arrow keys up/ down/ left/right
* Wheel L/R: mouse wheel click left/right
* Thumb U/D: mouse thumb button up/down

For some parts, mouse wheel click respectively thumb button action proposals have been added which fit in nicely. Make sure to use a mouse with support of mousewheel click (left/right) and a set of two thumb buttons like for example a Logitech M500.

## Manual setup


### MacOS

* Settings > Mission Control > Disable "Monitors use different spaces"
* BetterTouchTool: Disable `ALT`+`q` for closing apps - this is easily typed when trying to type `@`. Replace by `ALT`+`F4`.


## Desktop Navigation (mainly CTRL)

|Description              |Linux IBM Keyboard       | MacOS Keyboard          |Mouse Action                    |
|-------------------------|-------------------------|-------------------------|--------------------------------|
|Switch desktop/space     |`CTRL`+`L/R`             |`CTRL`+`L/R`             |`Wheel L/R`                     |
|+ move window to desktop |`CTRL`+`U`ALT`+`L/R      |`CTRL`+`ALT`+`L/R`       |`CTRL`+`WIN/ALT`+`Wheel L/R`    |
|Switch to desktop 1      |`CTRL`+`1`               |`CTRL`+`1`               |                                |
|Switch to desktop 2      |`CTRL`+`2`               |`CTRL`+`2`               |                                |


## Window Move Resize (mainly WIN/CMD)

|Description              |Linux IBM Keyboard       | MacOS Keyboard          |Mouse Action             |
|-------------------------|-------------------------|-------------------------|-------------------------|
|Half size left/right edge|`WIN`+`L/R`              |`CMD`+`L/R`              |                         |
|Quarter size in corner   |`ALT`+`WIN`+`L/R/U/D`    |`ALT`+`CMD`+`L/R/U/D`    |                         |
|Maximize window          |`WIN`+`Up`               |`CMD`+`Up`               |                         |
|Restore original size    |`WIN`+`Down`             |`CMD`+`Down`             |                         |
|Toggle full screen       |`WIN`+`Enter`            |`CMD`+`Enter`            |                         |
|Toggle sticky window     |`ALT`+`WIN`+`Enter`      |`ALT`+`CMD`+`Enter`      |                         |
|Freely resize window     |`CTRL`+`WIN`+MouseMove   |`CTRL`+`ALT`+MouseMove   |see left columns         |
|Freely move window       |`WIN`+`ALT`+MouseMove    |`ALT`+`CMD`+MouseMove    |see left columns         |

```
modifier kombos for applications and window res^ize:

this modifiers work blind without needing to now if its mac or linux
replace shift-ctrl by ctrl-win
replace shift-CMD by alt-cmd

`CTRL`+`WIN`       =  `CTRL`+`ALT`        xx-  
`WIN`+`ALT`        =  `ALT`+`CMD`	  -xx
`CTRL`+`ALT`       =  `CTRL`+`CMD`        x-x  
`CTRL`+`WIN`+`ALT` =  `CTRL`+`ALT`+`CMD`  xxx


SHIFT  +ESC
CTRL + ESC
SHIFT + TAB
```


## Window Tabs (ALT/ ALT modifier)

|Description              |Linux IBM Keyboard       | MacOS Keyboard          |Mouse Action             |
|-------------------------|-------------------------|-------------------------|-------------------------|
|Cycle Tabs               |`CTRL`+`Tab`             |`CTRL`+`Tab`             |`Thumb`+`U/D`            |
|Open Tab                 |`CTRL`+`t`               |`CTRL`+`t`               |`CTRL`+`Thumb`+`U`       |
|Close Tab                |`CTRL`+`w`               |`CTRL`+`w`               |`CTRL`+`Thumb`+`D`       |


## Applications 
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


## Productivity

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
|Directory Up             |`CTRL`+`Up`        (x--)   |`CMD`+`Up`        (--x)   |
|Show hidden files        |`CTRL`+`h`         (x--)   |`CMD`+`h`         (--x)   |
|Create directory         |`CTRL`+`n`         (x--)   |`CMD`+`n`         (--x)   |
|Create file              |`CTRL`+`SHIFT`+`n` (x--)   |`CMD`+`SHIFT`+`n` (--x)   |

### System (xxx)

|Description              |Linux IBM Keyboard         | MacOS Keyboard           |
|-------------------------|---------------------------|--------------------------|
|Lock screen              |`CTRL`+`WIN`+`ALT`+`Up`    |`CTRL`+`ALT`+`CMD`+`Up`   |
|Sleep                    |`CTRL`+`WIN`+`ALT`+`Right` |`CTRL`+`ALT`+`CMD`+`Down` |
|Restart computer         |`CTRL`+`WIN`+`ALT`+`Left`  |`CTRL`+`ALT`+`CMD`+`Left` |
|Shut down                |`CTRL`+`WIN`+`ALT`+`Down`  |`CTRL`+`ALT`+`CMD`+`Right`|
