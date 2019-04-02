# vim
## vim basics commands 
**Source: https://linuxgazette.net/152/srinivasan.html**
Different Modes: Insert,normal and visual<br/>
```vim filename``` - *open vim* <br/>
```gvim filename``` - *GUI interface* <br/>
```:``` - *normal mode* <br/>
```:q``` - *quit vim* <br/> 
```:q!``` - *quit vim without saving* <br/>
```:w``` - *followed by :q OR :wq - Save and exit* <br/>	
```h``` ```j``` ```k``` ```l``` - ***for moving around left, down, up, right*** <br/>
```i``` - *to insert at a location*  --- **AVOID using escape and arrow keys** <br/>
```i``` - *insert BEFORE Cursor* <br/>
```a``` - *insert AFTER Cursor (append)* <br/>
```shift+i (or I)``` - *insert at BEGINNING of line* <br/>
```shift+a (or A)``` - *append at the END of line* <br/>
```o``` - *create a new line BELOW the current line, and put the cursor at the start of
                 the new line* <br/>
```r``` - *replace the char at the cursor position and come back into escape mode* <br/>
```shift+r (or R)``` - *replace mode* --- **Have a look at how the backspace works in this mode** <br/>
```x``` - *remove char under the cursor. Similar to **delete*** <br/>
```shift+x (or X)``` - *remove char before cursor. Works like **backspace*** <br/>
```v``` - *visual mode - use ```h``` ```j``` ```k``` ```l``` to select text* <br/>
```y``` - *yank in visual mode --- **copying*** <br/>
```p``` - *paste in visual mode* <br/>
```u``` - *Undo* <br/>
```Control+R``` - *Redo* <br/>
```:earlier 10m``` OR ```:earlier 2h``` - *will take you **back** undoing all changes back to that specific time* <br/>
```:later``` - *will take you ahead **redoing** all changes to that specific time* <br/>
```<ESC>``` or ```Control+[``` - *when you are done OR you want to navigate somewhere else - **back to normal mode*** <br/>

