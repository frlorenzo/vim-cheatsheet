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


## Write
- **`:w [file]`**       write to file
- **`:[#,#]w [file]`**  write section to file


## Write/Exit
- **`:w[q]`**   write and quit
- **`:q[!]`**   quit, without writing
- **`:x`**      write and exit
- **`ZZ`**      write and exit


## Copy/Paste
- **`yy`**      yanks (copies) current line
- **`#yy`**     yanks current and # lines after
- **`p`**       paste after the current line
- **`P`**       paste above the current line


## Cursor Movement (Character)
- **`hjkl`**    move left, down, up, right


## Cursor Movement (Word)
- **`wb`**      move cursor forward, back one word 
- **`WB`**      move curose forward, back one word ignore non-alpha
- **`e`**       move cursor forward (end) of word (**E** ignore non-alpha)
- **`0`**       moves cursor to the beginning of line
- **`$`**       moves cursor to the end of line


## Cursor Movement (Line)
- **`Ctrl+d`**  scroll the cursor down (12 lines)
- **`Ctrl+u`**  scroll the cursor up (12 lines)
- **`Ctrl+f`**  scroll the cursor forward (down) (24 lines)
- **`Ctrl+b`**  scroll the cursor back (up) (24 lines)


## Cursor Movement (Position)
- **`gg`**      move cursor to the top of the file
- **`G`**       move cursor to the end of the file
- **`#G`**      move cursor to given line #
- **`)(`**      move by sentence
- **`}{`**      move by paragraph


## Search
- **`/xxx`**    search forward for occurence of `xxx`
- **`/xxx\>`**  search forward for occurence of `xxx` whole word only
- **`n`**       search for next occurence 
- **`N`**       search for previous occurence 
- **`?xxx`**    search backward for occurence of `xxx`
- **`?xxx\>`**  search backward for occurence of `xxx` whole word only


# Undo, Redo, and Repeat
- **`u`**       undo last command
- **`Ctrl+r`**  redo last command
- **`.`**       repeat last command


## Select, Change, Delete Blocks of Text
- `cit`       change inner tag between very first "<" and very last ">"
- `dit`       delete inner tag between very first "<" and very last ">"
- `ci<`       change contents if inside angle brackets
- `ciw`       change a word
- `daw`       delete a word

