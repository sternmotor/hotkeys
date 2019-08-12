# hotkeys
Keyboard shortcut proposal for easy-to-learn, quick, mouse-free access with hands on keyboard under Mac OS, Linux Desktops and Windows.

## Description
If possible, use a mouse with support of mousewheel click (left/right) and a set of two thumb buttons like for example a Logitech M500. Such a setup may replace the need for Trackpad


Words and abbreviations used here:

* Desktop: virtual desktop (fullscreen apps and space in mac os, workspaces in X windows) - may contain multiple screens
* Screen: for a two-monitor systems, you have two screens (left and right)
* U/D/L/R: arrow keys up/ down/ left/right
* MWheel L/R: mouse wheel click left/right
* ThumbB U/D: mouse thumb button up/down


## Desktop Navigation (mainly CTRL)
* Switch to desktop L/R 
    * `CTRL + L/R`
    * `MWheel L/R`

    CTRL + U/D: Move current window and scope to desktop L/R
    CTRL + MWheel L/R: Move current window and scope to desktop L/R
    SHIFT + CTRL + U/D: Move current window to desktop L/R, stay on same desktop
    SHIFT + CTRL + MWheel L/R: Move current window to desktop L/R

## Window Move Resize (mainly WIN/CMD)


|Description              | x86 Keyboard            | MacOS Keyboard          |
|-------------------------|-------------------------|-------------------------|

|Description                    |       x86 Keyboard        |      MacOS Keyboard       |
|-------------------------------|---------------------------|---------------------------|
|Half size left/right           |WIN + cursor left/right    |CMD + cursor left/right    |
|Quarter size in edge           |WIN + CTRL + cursor        |CMD + CTRL + cursor       |
|Third size left/middle/right   |WIN + SHIFT + cursor       |CMD + SHIFT + cursor|
|Maximize                       |WIN + cursor up      |WIN + cursor up            |CMD + cursor up            |
|Normal size                    |WIN + cursor down|WIN + cursor down          |CMD + cursor up            |
|Sticky window|||



    Switch tmux sessions
    WIN + </>: Switch application windows (+ SHIFT: reverse direction)
    WIN + MWheel L/R: Switch application windows
    WIN + L/R: half screen size on left/right side of screen
    WIN + U: maximize to top
    WIN + D: restore original windows size
    SHIFT + WIN + L/R/U/D: same as WIN + L/R/U/D, but quarter size
    CTRL + WIN + L/R: move window to left/right screen
    CTRL + WIN + MWheel L/R: move window to left/right screen
    WIN + ENTER: fullscreen mode
    ALT + Tab: Cycle through applications (+ SHIFT: reverse direction)

## Window Tabs (ALT/ OPTION keys)

|Description              | x86 Keyboard            | MacOS Keyboard          |Mouse Action             |
|-------------------------|-------------------------|-------------------------|-------------------------|
|Switch Tabs              |ALT + </>                |ALT + </>                |ThumbB U/D: Switch Tabs  |

## Tmux panes

For tmux panes, there is no equivalent in window or desktop handling. Therefore 
nothing is proposed here - just stick to the usual `CTRL + b + L/R/U/D`

## Applications (ALT/CMD/WIN)
Programs and utilities used while working. Applications may have mutiple windows and multiple tabs or panes within. 


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
|Exit application         |ALT + F4                 |OPTION + Q               |
|Lock screen              |CTRL + WIN + ALT + U     |CTRL + OPTION + CMD + U  |
|Open Tab                 |CTRL + t                 |CTRL + t                 |
|Restart                  |CTRL + WIN + ALT + L     |CTRL + OPTION + CMD + L  |
|Screen Shot (Area)       |WIN + SHIFT + S          |CMD + SHIFT + S          |
|Search and Run           |WIN + R, ALT + Space     |CMD + Space              |
|Shut down                |CTRL + WIN + ALT + D     |CTRL + OPTION + CMD + D  |
|Sleep                    |CTRL + WIN + ALT + R     |CTRL + OPTION + CMD + R  |
|Switch Application       |(SHIFT + ) ALT + Tab     |(SHIFT + ) OPTION + TAB  |
|Zoom                     |CTRL + +/-               |CMD  + +/-               |

## TODO

Example configurations and scripts for
* xorg
* mac os BT

