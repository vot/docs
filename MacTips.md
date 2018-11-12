# Mac OS Tips

## Spotlight

Spotlight helps you open applications or documents on your Mac and perform certain tasks for you.

**Open Spotlight**

Hit `Cmd+Space` on your keyboard or click on magnifying glass icon in the menu bar.

**Calculator**

You can perform basic maths operations right in Spotlight.

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

The above Cmds will create Screenshots directory on your Desktop and start saving them there.

## Finder

**Keyboard navigation**

In Finder you can select files with your arrow keys as expected.

* Hitting `Enter` (`Return`) will trigger a file rename process.
* To step into a directory press `Cmd+Down` arrow.
* To go a directory up press `Cmd+Up` arrow.
* To switch between the views you can use `Cmd+1` (as Icons), `Cmd+2` (as List), `Cmd+3` (as Columns), `Cmd+4` (as Cover Flow).

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

## Make applications to always minimise to Dock

* Use Spotlight to open Dock preferences
* Select “Minimize windows into application icon”

You should also look at “Show indicators for open applications” on the same screen.

This setting will draw a dot next to the icons of open applications.


## Navigate with keyboard to all elements of the window

By default you will not be able to reach certain elements of the interface with your keyboard.

You can force all elements of the interface to be reachable this way by adjusting a setting in Keyboard preferences.

* Use Spotlight to open Keyboard preferences
* Go to “Shortcuts” tab
* Switch “Full Keyboard Access” to “All controls”


## Other tips

* You can preview most document types by selecting their icon and pressing `Space`.
* Whenever you need to type an accented character you can hold down the appropriate letter. A list of relevant options will pop up.
* To switch audio output press `Alt` when clicking on volume icon in menu bar. The same thing works to view more details about WiFi or Bluetooth.
* To adjust volume in smaller increments hold `Shift+Alt` as you hit the `Volume Up/Down` keys. This works for brightness too.
* In Safari you can press `Control` key, then double-click inside the video to see the "Enter Picture-in-Picture" option.
* `Control+ Shift+Power/Eject` will put your Mac to sleep.
* You can use Preview to crop your images. Select the area you want and press `Cmd+K` to crop. You’ll see “edited” next to the file name in the title bar. Press `Cmd+S` to save the modified version.
* You can close current window with `Cmd+W`. To close the whole application press `Cmd+Q`.
* You can enable “Do not disturb” mode for notifications by clicking on notifications icon in the menu bar while holding `Alt` key down.
* You can use Quick Time to record your screen.

## Modifier keys

The following are the modifier keys on Macs with alternative labels next to them. These symbols are used interchangably.

* `⌘` = `Cmd` = `Cmd`
* `⌥` = `Alt` = `Option`
* `Ctrl` = `Control`
* `⇧` = `Shift`
