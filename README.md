# Vim Cheatsheet


- [File](#file)
- [Buffer](#buffer)
- [Editing](#editing)
- [Conversion](#conversion)
- [Cursor Movement](#cursor-movement)
- [Search/Replace](#searchreplace)
- [Spell Check](#spell-check)
- [Window](#window)
- [Search](#search)
- [Session](#session)
- [Terminal](#terminal)
- [Wrapping](#wrapping)


## File 

| Description                        | Command               | Keystroke             |
| ---------------------------------- | --------------------- | --------------------- |
| `--------------------------------` | `-------------------` | `-------------------` |
| Open/new file                      | `:e filepath`         |                       | 
| Reload file                        | `:e! filepath`        |                       |
| Find/open file                     | `:find filepath`      |                       |
| `--------------------------------` | `-------------------` | `-------------------` |
| Write file                         | `:w`/`:w!`            |                       | 
| Write file as                      | `:w filepath`         |                       | 
| Write all, then quit               | `:wqa`/`:x`           | `ZZ`                  |
| `--------------------------------` | `-------------------` | `-------------------` |
| Quit vim/close tab, buffer         | `:q`/`:q!`            |                       | 
| Quit vim/close all tab, buffer     | `:qa`/`:qa!`          |                       | 

[[top]](#vim-cheatsheet)



## Buffer

| Description                        | Command               | Keystroke             |
| ---------------------------------- | --------------------- | --------------------- |
| `--------------------------------` | `-------------------` | `-------------------` |
| List all buffers                   | `:ls`                 |                       | 
| `--------------------------------` | `-------------------` | `-------------------` |
| Go to buffer by number or file     | `:b#`, `b file`       |                       | 
| Go to next buffer                  | `:bn`                 |                       | 
| Go to previous buffer              | `:bp`                 |                       | 
| Move to last file in the list      | `:last`               |                       | 
| Move to first file in the list     | `:first`              |                       | 
| `--------------------------------` | `-------------------` | `-------------------` |
| Close current or # from buffer     | `:bd #`               |                       | 
| Wipe from buffer (close file)      | `:bw`/`:bw #`         |                       | 

* *This is an alternative to using tabs which holds list of files in a single window*

[[top]](#vim-cheatsheet)



## Editing

| Description                        | Command               | Keystroke             |
| ---------------------------------- | --------------------- | --------------------- |
| `--------------------------------` | `-------------------` | `-------------------` |
| Insert text (before cursor)        |                       | `[#]i[text]<esc>`     |
| Append text (after cursor)         |                       | `[#]a[text]<esc>`     |
| `--------------------------------` | `-------------------` | `-------------------` | 
| Copy selection                     |                       | `y`                   |
| Copy line                          |                       | `yy`                  |
| Copy line number                   | `:##,##y`             |                       |
| `--------------------------------` | `-------------------` | `-------------------` | 
| Paste after cursor                 |                       | `p`                   |
| Paste before cursor                |                       | `P`                   |
| `--------------------------------` | `-------------------` | `-------------------` | 
| Delete character                   |                       | `x`                   |
| Delete word (from beginning)       |                       | `dw`                  |
| Delete line                        |                       | `dd`                  |
| Delete to end of line              |                       | `d$`                  |
| Delete selection                   |                       | `d`                   |
| Delete between lines               | `:##,##d`             |                       |
| Delete between braces              |                       | `d%`                  |
| `--------------------------------` | `-------------------` | `-------------------` | 
| Select text                        |                       | `v`                   | 
| Select line                        |                       | `V`                   |
| Select block                       |                       | `ctrl+v`              |
| Select all                         |                       | `ggVG`                |
| `--------------------------------` | `-------------------` | `-------------------` |
| Undo                               |                       | `u`                   |
| Undo line                          |                       | `U`                   |
| Redo                               |                       | `ctrl+r`              |
| `--------------------------------` | `-------------------` | `-------------------` |
| Open new line below cursor         |                       | `o`                   |
| Open new line above cursor         |                       | `O`                   |
| `--------------------------------` | `-------------------` | `-------------------` |
| Delete a line break                |                       | `J`                   |

[[top]](#vim-cheatsheet)



## Conversion

| Description                        | Command               | Keystroke             |
| ---------------------------------- | --------------------- | --------------------- |
| `--------------------------------` | `-------------------` | `-------------------` |
| Convert to upper case              |                       | `gU`                  |
| Convert to lower case              |                       | `gu`                  |

[[top]](#vim-cheatsheet)



## Cursor Movement

| Description                        | Command               | Keystroke             |
| ---------------------------------- | --------------------- | --------------------- |
| `--------------------------------` | `-------------------` | `-------------------` |
| Move up                            |                       | `[#]k`, `↑`           | 
| Move down                          |                       | `[#]j`, `↓`           |
| Move left                          |                       | `[#]h`, `←`           | 
| Move right                         |                       | `[#]l`, `➡`           | 
| `--------------------------------` | `-------------------` | `-------------------` |
| Move to end of line                |                       | `$`                   | 
| Move to beginning of line          |                       | `0`                   | 
| Move to first non-block of line    |                       | `^`                   | 
| `--------------------------------` | `-------------------` | `-------------------` |
| Move next front of word            |                       | `[#]w`                | 
| Move previous front of word        |                       | `[#]b`                |
| Move next end of word              |                       | `[#]e`                | 
| Move previous end of word          |                       | `[#]ge`               | 
| `--------------------------------` | `-------------------` | `-------------------` |
| Jump to end of file                |                       | `G`                   | 
| Jump to beginning of file          |                       | `gg`                  | 
| Jump to line number                |                       | `#G`,`#gg`            | 
| `--------------------------------` | `-------------------` | `-------------------` |
| Jump forward one sentence          |                       | `)`                   | 
| Jump backward one sentence         |                       | `(`                   | 
| Jump forward one paragraph         |                       | `}`                   | 
| Jump backward one paragraph        |                       | `{`                   | 
| Jump to top of the screen          |                       | `H`                   | 
| Jump to bottom of the screen       |                       | `L`                   | 
| `--------------------------------` | `-------------------` | `-------------------` |
| Go to line                         | `:##`                 | `##G`,`##gg`          | 
| `--------------------------------` | `-------------------` | `-------------------` |
| Scrolls up half of screen          |                       | `ctrl+u`              | 
| Scrolls down half of screen        |                       | `ctrl+d`              | 

[[top]](#vim-cheatsheet)



## Search/Replace

| Description                        | Command               | Keystroke             |
| ---------------------------------- | --------------------- | --------------------- |
| `--------------------------------` | `-------------------` | `-------------------` | 
| Search/replace text                | `:%s/search/replace/g`|                       |
| Search forward                     | `:/pattern`           |                       |   
| Search backward                    | `:?pattern`           |                       |
| Search next                        |                       | `n`                   |
| Search previous                    |                       | `N`                   |
| Make insensitive search            | `:set ignorecase`     |                       |

[[top]](#vim-cheatsheet)



## Spell Check

| Description                        | Command               | Keystroke             |
| ---------------------------------- | --------------------- | --------------------- |
| `--------------------------------` | `-------------------` | `-------------------` | 
| Turn on spell checking             | `:set spell`          |                       | 
| Turn off spell checking            | `:set nospell`        |                       | 
| `--------------------------------` | `-------------------` | `-------------------` | 
| Move to next misspelled word       |                       | `]s`                  |
| Move to next previous word         |                       | `[s`                  |
| `--------------------------------` | `-------------------` | `-------------------` | 
| Get spelling suggestions           |                       | `z=`                  |
| Add to spelling file               |                       | `zg`                  |

[[top]](#vim-cheatsheet)



## Window

| Description                        | Command               | Keystroke             |
| ---------------------------------- | --------------------- | --------------------- |
| `--------------------------------` | `-------------------` | `-------------------` | 
| Create veritcal split              | `:vsp [path]`         |                       | 
| Create horizontal split            | `:sp [path]`          |                       | 
| `--------------------------------` | `-------------------` | `-------------------` | 
| Go to left panel                   |                       | `ctrl+w h`            | 
| Go to lower panel                  |                       | `ctrl+w j`            | 
| Go to upper panel                  |                       | `ctrl+w k`            | 
| Go to right panel                  |                       | `ctrl+w l`            | 
| `--------------------------------` | `-------------------` | `-------------------` | 
| Increase window height             | `:resize +1`          | `ctrl+w # +`          | 
| Decrease window height             | `:resize -1`          | `ctrl+w # -`          | 
| Increase window width              | `:vertical resize +1` | `ctrl+w # >`          | 
| Decrease window width              | `:vertical resize -1` | `ctrl+w # <`          | 
| `--------------------------------` | `-------------------` | `-------------------` | 
| Max current window vertical        |                       | `ctrl+w _`            | 
| Max current window horizontal      |                       | `ctrl+w \|`           | 
| Make all equal size                |                       | `ctrl+w =`            | 
| `--------------------------------` | `-------------------` | `-------------------` | 
| Close current window               | `:close`              |                       | 

*exit using `qa`*

[[top]](#vim-cheatsheet)


## Search

| Description                        | Command               | Keystroke             |
| ---------------------------------- | --------------------- | --------------------- |
| `--------------------------------` | `-------------------` | `-------------------` | 
| Search for occurrence of "string"  | `/string`             |                       | 
| Search "string" whole word only    | `/string\>`           |                       | 
| `--------------------------------` | `-------------------` | `-------------------` | 
| Find next occurrence               |                       | `n`                   | 
| Find previous occurrence           |                       | `N`                   | 
| `--------------------------------` | `-------------------` | `-------------------` | 
| Find matching `[]`,`{}`,`()`       |                       | `%`                   | 
| `--------------------------------` | `-------------------` | `-------------------` | 
| Highlight all matches in search    | `:set hlsearch`       |                       | 

[[top]](#vim-cheatsheet)



## Session

| Description                        | Command               | Keystroke             |
| ---------------------------------- | --------------------- | --------------------- |
| `--------------------------------` | `-------------------` | `-------------------` | 
| Create session                     | `:mksession filepath` |                       | 
| Open session                       | `:source filepath`    |                       | 
| Save changes                       | `:mks!`               |                       | 

[[top]](#vim-cheatsheet)



## Terminal

| Description                        | Command               | Keystroke             |
| ---------------------------------- | --------------------- | --------------------- |
| `--------------------------------` | `-------------------` | `-------------------` | 
| Open terminal new window           | `:term`               |                       |
| Open terminal vertically           | `:vert term`          |                       |
| Focus to next window               |                       | `Ctrl+w w`            |
| Go to terminal-normal mode         |                       | `Ctrl+w n`            |
| Go to next tab                     |                       | `Ctrl+w gt`           |
| Go to previous tab                 |                       | `Ctrl+w gT`           |
| Ends the job                       |                       | `Ctrl+w c`            |

[[top]](#vim-cheatsheet)



## Wrapping

| Description                        | Command               | Keystroke             |
| ---------------------------------- | --------------------- | --------------------- |
| `--------------------------------` | `-------------------` | `-------------------` |
| Toggle wrapping                    | `:set wrap`           |                       |
| Toggle no wrapping                 | `:set nowrap`         |                       |

[[top]](#vim-cheatsheet)

