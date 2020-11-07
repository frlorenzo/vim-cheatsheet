# Vim Keys


## Input Text 
- **`i`**        insert before the cursor
- **`a`**        append after the cursor
- **`o`**        insert line below the cursor, place at the beginning
- **`O`**        insert line above the cursor, place at the beginning


## Exit Vim
- `:q[!]`     quit, force
- `:w[q]`     write, quit
- `:x`        write and exit


## Copy, Delete, Paste
- `yy`        yanks (copies) current line
- `#yy`       yanks current and # lines after
- `p`         paste after the current line
- `P`         paste above the current line
- `dd`        delete current line
- `#dd`       delete # of lines


## Movement
- `hjkl`    move left, down, up, right
- `Ctrl+f`  page forward
- `Ctrl+b`  page backward
- `gg`      move to the top of document
- `G`       move to the end of document
- `w`       move to start word
- `W`       move to start word ignore word terminators
- `e`       move to end word
- `E`       move to end word ignore word terminators
- `b`       move to back word
- `B`       move to back word ignore word terminators
- `)(`      move by sentence
- `}{`      move by paragraph
- `0`       go to the beginning of line
- `$`       go to the end of line


# Undo, Redo, and Repeat
- `.`       repeat last edit
- `u`       undo edits
- `Ctrl+r`  redo edits


## Select, Change, Delete Blocks of Text
- `cit`       change inner tag between very first "<" and very last ">"
- `dit`       delete inner tag between very first "<" and very last ">"
- `ci<`       change contents if inside angle brackets
- `ciw`       change a word
- `daw`       delete a word

