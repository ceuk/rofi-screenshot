## rofi-screenshot (Wayland)

![](https://imgur.com/7io5BKJ.gif)

I got sick of not having a simple solution to take screenshots and screencasts. 

Plus, there's so many different things I might want to do I struggle to find key bindings for all of them. So, I created a script to show and execute various screen capture related commands in Rofi.

### Features
* Capture a region to the clipboard or a directory
* Capture the whole screen to the clipboard or a directory
* Record a specific region and save as a gif or MP4
* Record the whole screen and save as a gif or MP4

### Installation
Make sure you have the required [dependencies](#dependencies) installed.

Download the rofi-screenshot source code, save as rofi-screenshot and make it executable
```bash
$ curl -L https://git.io/rofi-screenshot > rofi-screenshot && chmod u+x rofi-screenshot
```
Then move rofi-screenshot to somewhere in your $PATH for example:
```bash
$ sudo mv rofi-screenshot /usr/local/bin/
```

### Usage
Show the rofi menu
```bash
$ rofi-screenshot
```

Stop recording
```bash
$ rofi-screenshot -s
```
**Tip**: Add a keybinding for both of the above commands

### Dependencies

* [rofi](https://github.com/davatorium/rofi)
* [ffcast](https://github.com/lolilolicon/FFcast)
* [slop](https://github.com/naelstrof/slop)
* [grim](https://sr.ht/~emersion/grim)
* [wf-recorder](https://github.com/ammen99/wf-recorder)
