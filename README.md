# Set and Save MacOS window positions

When I wake my laptop with external monitors plugged in, the previous window positions are not restored.  This automation will save and restore them.

`save_window_positions.js` will save positions to a local file.

`save_window_positions_and_sleep.js` will also save the window positions but also sleep the computer.

`set_window_positions.js` will restore the saved positions from the same file.

Credit to https://macmost.com/saving-and-recalling-window-positions-with-automator.html for the head start with this.  This code differs in that it also matches the window name (for multiple chrome windows for example).  It's also less user friendly in that it doesn't prompt for filename to save/read from, etc.  Use at your own risk.
