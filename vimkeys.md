# Vim Keys


## Basic Changes
- **`x`**       delete one character at the cursor
- **`#x`**      delete # number of characters at the cursor
- **`r`**       replace one character at the cursor
- **`dd`**      delete current line
- **`#dd`**     delete # of lines


## Text Insertion 
- **`i`**       insert before the cursor
- **`a`**       append after the cursor
- **`o`**       insert line below the cursor, place at the beginning
- **`O`**       insert line above the cursor, place at the beginning


## Write/Exit
- **`:w`**      write to file
- **`:w[q]`**   write and quit
- **`:q[!]`**   quit, without writing
- **`:x`**      write and exit
- **`ZZ`**      write and exit


## Copy/Paste
- **`yy`**      yanks (copies) current line
- **`#yy`**     yanks current and # lines after
- **`p`**       paste after the current line
- **`P`**       paste above the current line


## Cursor Position 
- **`hjkl`**    move left, down, up, right
- **`w`**       move to start of word (**W** ignore non-alpha)
- **`b`**       move to back of word (**B** ignore non-alpha)
- **`e`**       move to end of word (**E** ignore non-alpha)
- **`0$`**      go to beginning, end of line


## Cursor Page Movement
- `Ctrl+f`  page forward
- `Ctrl+b`  page backward
- `gg`      move to the top of document
- `G`       move to the end of document
- `)(`      move by sentence
- `}{`      move by paragraph


# Undo, Redo, and Repeat
- `.`       repeat last command
- `u`       undo last command
- `Ctrl+r`  redo last command


## Select, Change, Delete Blocks of Text
- `cit`       change inner tag between very first "<" and very last ">"
- `dit`       delete inner tag between very first "<" and very last ">"
- `ci<`       change contents if inside angle brackets
- `ciw`       change a word
- `daw`       delete a word

