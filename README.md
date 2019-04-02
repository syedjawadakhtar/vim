# vim
## vim basics commands 
**Source: https://linuxgazette.net/152/srinivasan.html**

```vim filename``` - *open vim*
```gvim filename``` - *GUI interface* 
insert,normal and visual modes
: - normal mode
:q - quit vim 
:q! - quit vim without saving
:w followed by :q OR :wq - Save and exit	
hjkl - for moving around left, down, up, right
i - to insert at a location  ---- AVOID using escape and arrow keys
 i               insert BEFORE Cursor
 a               insert AFTER Cursor (append)
shift+i (or I)  insert at BEGINNING of line
shift+a (or A)  append at the END of line
 o               create a new line BELOW the current line, and put the cursor at the start of
                 the new line.
 r               replace the char at the cursor position and come back into escape mode.
shift+r (or R)   replace mode. Vim is pretty 
                        intelligent. Have a look at how the backspace works in this mode.
x               remove char under the cursor. Similar to delete.
shift+x (or X)  remove char before cursor. Works like backspace.
v		visual mode - use hjkl to select text
y		yank in visual mode (copying)
p		paste in visual mode
u		undo 
Control+R 	Redo 
:earlier 10m OR 
:earlier 2h 	will take you back undoing all changes back to the specific time
:later 		"	"	ahead	"	"	"	"	"	"
<ESC> or Control+[ - when you are done OR you want to navigate somewhere else - back to normal mode

