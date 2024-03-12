## MacOS Terminal Cheatsheet

### Shortcuts

| Key/Command | Description |
| ----------- | ----------- |
| Ctrl + A   | Go to the beginning of the line you are currently typing on.|
| Ctrl + E   | Go to the end of the line you are currently typing on.|
| Ctrl + L or CMD + K | Clears the Screen |
| Ctrl + U   | Cut everything backwards to beginning of line |
| Ctrl + K   | Cut everything forward to end of line |
| Ctrl + W   | Cut one word backwards using white space as delimiter |
| Ctrl + Y   | Paste whatever was cut by the last cut command |
| Ctrl + H   | Same as backspace |
| Ctrl + C   | Kill the current running process|
| Ctrl + D   | Exit the current shell when no process is running, or send EOF to a the running process |
| Ctrl + Z   | Puts whatever you are running into a suspended background process. fg restores it |
| Ctrl + _   | Undo the last command. (Underscore.  So it's actually Ctrl + Shift + minus) |
| Ctrl + T   | Swap the last two characters before the cursor |
| Ctrl + F or right arrow   | Move cursor one character forward |
| Ctrl + B or left arrow  | Move cursor one character backward |
| Option + →  | Move cursor one word forward |
| Option + ←  | Move cursor one word backward |
| Esc + T  | Swap the last two words before the cursor |
| Esc + Backspace | Cut one word backwards using none alphabetic characters as delimiters |
| Tab  | Auto-complete files and folder names |


### Core Commands

| Key/Command | Description |
| ----------- | ----------- |
| cd [folder] | Change directory e.g. `cd Documents` |
| cd or cd ~  |  Home directory (Users/username) |
| cd /  | Root of drive |
| cd -  | Previous directory |
| ls | Short listing of everything in the directory |
| ls -l | Long listing of everything in the directory |
| ls -a | Listing everything including hidden files |
| ls -lh| Long listing of everything with file sizes |
| ls -R | Entire content of folder in reverse alphabetical order |
| sudo [command] | Run command with the security privileges of the superuser |
| open [file] | Opens a file ( as if you double clicked it ) |
| top | Displays active processes. Press q to quit |
| nano [file] | Opens the file using the nano editor |
| vim [file] | Opens the file using the vim editor |
| clear |  Clears the screen |
| reset |  Resets the terminal display |