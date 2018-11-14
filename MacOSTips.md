# macOS Tips

## Spotlight

Spotlight helps you open applications or documents on your Mac and perform certain tasks for you.

**Open Spotlight**

Hit `Cmd+Space` on your keyboard or click on magnifying glass icon in the menu bar.

**Calculator**

You can perform basic mathematical operations right in Spotlight.

Just start adding numbers together and Spotlight will show you the result.

**Unit conversions in Spotlight**

Type “$1300” or “12 pounds” in Spotlight to see automatic unit conversion.


## Taking screenshots

* `Shift+Cmd+3` for full desktop
* `Shift+Cmd+4` for selected area
* `Shift+Cmd+4`, then `Space` for a single window

These screenshots will be saved as png files on your desktop.

**Setting custom directory for screenshots**

Open Terminal

```
mkdir $HOME/Desktop/Screenshots
defaults write com.apple.screencapture location $HOME/Desktop/Screenshots
killall SystemUIServer
```

The above commands will create Screenshots directory on your Desktop and set it as a target location for new screenshots.

<br /><br />


## Recording your screen

* Open QuickTime Player
* Dismiss the initial window that prompts you to open a file (click "Done")
* While the application is still open select File > New screen recording (`Ctrl+Cmd+N`) in the menu bar
* In the "Screen Recording" window click the red button and follow instructions
* You can record your entire screen or just a selected area
* After you're done click on the "stop" icon in the menu bar
* If you're happy with your recording save it or export to another format.


## Finder

**Keyboard navigation**

In Finder you can select files with your arrow keys as expected.

* `Enter` (`Return`) will trigger a file rename process.
* `Cmd+Down arrow` Step into selected directory or open selected file.
* `Cmd+Up arrow` To go one level up in directory tree.
* To switch between the views you can use `Cmd+1` (as Icons), `Cmd+2` (as List), `Cmd+3` (as Columns), `Cmd+4` (as Cover Flow).
* `Space` will display the currently selected item in a QuickLook window.

**Hide/show sidebar**

To toggle display of the left sidebar in Finder window use `Cmd+Alt+S`.


## Dock

**Hide/show Dock**

To toggle display of the Dock use `Cmd+Alt+D`.

**Insert a blank spacer into Dock**

Open Terminal

```
defaults write com.apple.dock persistent-apps -array-add '{"tile-type"="spacer-tile";}'
killall Dock
```

<br /><br />


## Make applications to always minimise to Dock

* Open Dock preferences (System Preferences > Dock)
* Select “Minimize windows into application icon”

You should also look at “Show indicators for open applications” on the same screen.

This setting will draw a dot next to the icons of open applications.


## Navigate with keyboard to all window elements

By default you will not be able to reach certain elements of the interface with your keyboard.

You can force all elements of the interface to be accessible.

* Open Keyboard preferences (System Preferences > Keyboard)
* Go to “Shortcuts” tab
* Switch “Full Keyboard Access” to “All controls”


## Quick tips

* You can preview most document types by selecting their icon and pressing `Space`.
* Whenever you need to type an accented character you can hold down the appropriate letter. A list of relevant options will pop up.
* To switch audio output press `Alt` when clicking on volume icon in menu bar. The same thing works to view more details about WiFi or Bluetooth.
* To adjust volume in smaller increments hold `Shift+Alt` as you hit the `Volume Up/Down` keys. This works for brightness too.
* In Safari you can press `Control` key, then double-click inside the video to see the "Enter Picture-in-Picture" option.
* `Control+Shift+Power/Eject` will put your Mac to sleep.
* You can use Preview to crop your images. Select the area you want and press `Cmd+K` to crop. You’ll see “edited” next to the file name in the title bar. Press `Cmd+S` to save the modified version.
* You can close current window with `Cmd+W`. To close the whole application press `Cmd+Q`.
* You can enable “Do not disturb” mode for notifications by clicking on notifications icon in the menu bar while holding `Alt` key down.

<br />

## Modifier keys

The following are the modifier keys on Macs with alternative labels next to them. These symbols are used interchangably.

* `⌘` = `Cmd` = `Command`
* `⌥` = `Alt` = `Option`
* `^` = `Ctrl` = `Control`
* `⇧` = `Shift`

<br />

## About this document

**Version 2 (13th November 2018)**

License: [CC-BY-SA-4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.en_US)


The newest version of this file can be downloaded from [github.com/vot/docs](https://github.com/vot/docs/raw/master/MacOSTips.pdf).

