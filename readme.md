## rofi-screenshot

![](https://imgur.com/7io5BKJ.gif)
I got sick of not having a simple solution to take screenshots and screencasts. Plus there's so many different things I might want to do I struggle to find key bindings for all of them.

### Features:
* Capture a region to the clipboard or directory
* Capture the whole screen to the clipboard or directory
* Record a specific region and save as a gif or MP4
* Record the whole screen and save as a gif or MP4

### Dependencies

* [rofi](https://github.com/davatorium/rofi)
* [ffcast](https://github.com/lolilolicon/FFcast)
* [slop](https://github.com/naelstrof/slop)
* [xclip](https://github.com/astrand/xclip)

### Installation
```
# Download the rofi-screenshot source code, save as rofi-screenshot
# and make it executeable
$ curl -L https://git.io/rofi-screenshot > rofi-screenshot && chmod u+x rofi-screenshot

# Then move rofi-screenshot to somewhere in your $PATH
# Here is an example
$ mv rofi-screenshot ~/scripts/
```

### Usage
Show the menu
```bash
$ rofi-screenshot
```

Stop recording
```bash
$ rofi-screenshot -s
```
**Tip**: Add a keybinding for both of the above commands


