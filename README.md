# vim-cheat-sheet

Vim is my favorite editor. Here's the basics, just what you need to know to use vi/vim.

## Navigation
`h` - left  
`j` - down  
`k` - up  
`l` - right  
 
`<CTRL> d` - page down  
`<CTRL> u` - page up 
 
`gg` - top of page  
`G` - bottom of page 
 
`^` - beginning of line  
`$` - end of line 

## Undo/redo/repeat/delete
`u` - undo  
`<CTRL> r` - redo  
`.` - repeats last thing you just did  
`x` - deletes current char  
`X` - backspace chars  
`dd` - deletes line  
`D` or `d$` - delete to end of line  

## Insert mode
`i` - start inserting  
`I` - insert at beginning of line  
`A` - insert at end of line  
`o` - insert new line below  
`O` - insert new line above  

## Replace mode
`s` - replace current char, and insert  
`cw` - replace current word, and insert  
`S` or `cc` - replace current line, and insert  
`C` - replace to end of line, and insert  
`r` - replace one char  
`R` - replace all chars  

## Copy/paste
`p` - paste at cursor (or below)  
`P` - paste above line  
`yy` - copy a line  
`yw` - copy a word 

## Visual mode
`v` - begin visual block  
`V` - select full line  
`<CTRL> v` - begin a block  
