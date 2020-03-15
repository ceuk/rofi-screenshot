## rofi-screenshot

![](https://imgur.com/7io5BKJ.gif)

I got sick of not having a simple solution to take screenshots and screencasts. Plus there's so many different things I might want to do I struggle to find key bindings for all of them.

This script will allow you to select one of the following via Rofi:

* Copy a region to the clipboard
* Save a region to a directory
* Copy the whole screen to the clipboard
* Save the whole screen to a directory
* Record a specific region and save as a gif
* Record a specific region and save as a MP4
* Record the whole screen and save as a gif
* Record the whole screen and save as an MP4

### Usage

* [Download `rofi-screenshot`](https://raw.githubusercontent.com/ceuk/rofi-screenshot/master/rofi-screenshot) and add somewhere in $PATH (e.g. /usr/local/bin)
* Make it executable `chmod u+x /usr/local/bin/rofi-screenshot`
* Show the menu with `rofi-screenshot`
* Stop recording with `rofi-screenshot -s`
* (optional) Add a keybinding for both of the above commands

### Dependencies

* [rofi](https://github.com/davatorium/rofi)
* [ffcast](https://github.com/lolilolicon/FFcast)
* [slop](https://github.com/naelstrof/slop)
* [xclip](https://github.com/astrand/xclip)

