# Linux-Control-Based-Text-Editors
Editing files with VI

Here’s a cleaner, organized version of your notes on VI editor basics:

## VI editor overview
vi is a text editor available by default on many Linux systems.
It is useful when working on remote Linux servers, especially for editing config files.


VI has three main modes:

Command mode: default mode when you open a file. Used for navigation, copying, pasting, deleting, searching, and other commands.
Insert mode: used to type and edit file contents.
Last line mode: used for commands like save, quit, and search.

Switching modes
Press i to enter insert mode.
Press Esc to return to command mode.

Basic navigation
Arrow keys work.

h = left
j = down
k = up
l = right

Basic editing commands
x = delete a character.
dd = delete the entire line.
yy = copy a line.
p = paste below the current line.

Scrolling
Ctrl + u = scroll up.
Ctrl + d = scroll down.

Last line commands
Press : to enter last line mode, then use:

:w = save.
:w filename = save as a new file.
:q = quit without saving.
:wq = save and quit.
:q! = quit without saving changes.

Searching
/text = search for text.
n = jump to the next match.
