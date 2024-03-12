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
| nano [file] | Opens the file using the nano editor |
| vim [file] | Opens the file using the vim editor |
| clear |  Clears the screen |
| reset |  Resets the terminal display |


### File Management

| Key/Command | Description |
| ----------- | ----------- |
| touch [file] |   Create a new file |
| pwd | Full path to working directory |
| . |  Current directory |
| .. | Parent directory|
| cat [file] | Display contents of file to terminal|
| rm [file] |  Remove a file |
| rm -i [file] | Remove with confirmation |
| rm -r [dir] | Remove a directory and contents |
| rm -f [file] | Force removal without confirmation |
| cp [file] [newfile] | Copy file to newfile |
| cp [file] [dir] | Copy file to directory |
| mv [file] [new filename] | Move file or move a file to itself (renaming) |
| pbcopy < [file] | Copies file contents to clipboard |
| pbpaste | Paste clipboard contents |
| pbpaste > [file] | Paste clipboard contents into file|
| less [file]|  Output file content delivered in screensize chunks |
|head [file]| Output first 10 lines of a file|


### Directory Management

| Key/Command | Description |
| ----------- | ----------- |
| mkdir [dir] | Create new directory |
| mkdir -p [dir]/[dir] |  Create nested directories |
| rmdir [dir] | Remove directory ( only operates on empty directories ) |
| rm -r [dir] | Remove directory and contents |


### Redirection

| Key/Command | Description |
| ----------- | ----------- |
| [command] > [file] |  Sets file as STDOUT, overwrites current file contents (creates file if non-existent)|
| [command] >> [file] | Sets file as STDOUT, appends to current file (creates file if non-existent)|
| [command] < [file] | Sets file as STDIN to command |


### Piping

| Key/Command | Description |
| ----------- | ----------- |
| [command a] \| [command b] | Run command a and then pass the output as input to command b|
| [command a] \| tee [file] \| [command b] |Split the output of command a, sending it simultaneously to both a file and the input of command b|


### Chaining

| Key/Command | Description |
| ----------- | ----------- |
| [command a]; [command b] | Run command a and then b, regardless of success of a |
| [command a] && [command b] | Run command b if a succeeded |
| [command a] \|\| [command b] | Run command b if a failed |
| [command a] & | Run command a in background |

### History

| Key/Command | Description |
| ----------- | ----------- |
| history | Shows history of stuff typed|
|up arrow / down arrow| shows last/next stuff typed|
| Ctrl + r  | Interactively search through previously typed commands |
| ![value] |  Execute the last command typed that starts with ‘value’ |
| ![value]:p |  Print to the console the last command typed that starts with ‘value’ |
| !! |  Execute the last command typed |
| !!:p |  Print to the console the last command typed |


### Search

| Key/Command | Description |
| ----------- | ----------- |
| find [dir] -name "file"| Find all files named "file" inside [dir]
(use wildcards [*] to search for parts of
filenames, e.g. "file.*")|
|grep "text" [file]| Output all occurrences of "text" inside
[file] (add -i for case-insensitivity|
|grep -rl "text" [dir]|Search for all files containing "text"
inside [dir]|


### Network

| Key/Command | Description |
| ----------- | ----------- |
|ping [host]| Ping host and display status|
|whois [domain]| Display whois information for a domain|
| curl -O [url/to/file]|Download file from URL into currently working directory|


### Processes

| Key/Command | Description |
| ----------- | ----------- |
| ps ax | Output currently running processes|
| top | Displays live info about active processes. Press q to quit |
|kill [pid]| Kill current process with ID pid|


