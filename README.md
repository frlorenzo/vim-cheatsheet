# Vim Cheatsheet


- [File](#file)
- [Buffer](#buffer)
- [Copy/Paste](#copypaste)
- [Conversion](#conversion)
- [Cursor Movement](#cursor-movement)
- [Search/Replace](#searchreplace)
- [Spell Check](#spell-check)
- [Split Window](#split-window)
- [Tabs](#tabs)
- [Explore](#explore)
- [Session](#session)
- [Terminal](#terminal)
- [Wrapping](#wrapping)


## File 

| Description                        | Command               | Keystroke             |
| ---------------------------------- | --------------------- | --------------------- |
| `--------------------------------` | `-------------------` | `-------------------` |
| Open/new file                      | `:e filepath`         |                       | 
| Find/open file                     | `:find filepath`      |                       | 
| Save/write file                    | `:w`/`:w!`            |                       | 
| Save/write file as                 | `:w filepath`         |                       | 
| Save/write all, then quit          | `:wqa`                |                       | 
| Quit vim/close current tab         | `:q`/`:q!`            |                       | 
| Quit vim/close all                 | `:qa`/`:qa!`          |                       | 

[[top]](#vim-cheatsheet)



## Buffer

| Description                        | Command               | Keystroke             |
| ---------------------------------- | --------------------- | --------------------- |
| `--------------------------------` | `-------------------` | `-------------------` |
| List buffers                       | `:buffers`            |                       | 
| Remove from buffer (close file)    | `:bd`/`:bd #`         |                       | 
| Wipe from buffer (close file)      | `:bw`/`:bw #`         |                       | 

* *This is an alternative to using tabs which holds list of files in a single window*

[[top]](#vim-cheatsheet)



## Copy/Paste

| Description                        | Command               | Keystroke             |
| `--------------------------------` | `-------------------` | `-------------------` | 
| ---------------------------------- | --------------------- | --------------------- |
| Copy selection                     |                       | `y`                   |
| Copy line                          |                       | `yy`                  |
| Copy line number                   | `:##,##y`             |                       |
| `--------------------------------` | `-------------------` | `-------------------` | 
| Paste after cursor                 |                       | `p`                   |
| Paste before cursor                |                       | `P`                   |
| `--------------------------------` | `-------------------` | `-------------------` | 
| Cut selection                      |                       | `d`                   |
| Cut line                           |                       | `dd`                  |
| Cut/delete line number             | `:##,##d`             |                       |
| Delete between braces              |                       | `d%`                  |
| `--------------------------------` | `-------------------` | `-------------------` | 
| Select text                        |                       | `v`                   | 
| Select line                        |                       | `V`                   |
| Select block                       |                       | `ctrl+v`              |
| Select all                         |                       | `ggVG`                |
| `--------------------------------` | `-------------------` | `-------------------` | 
| Undo                               |                       | `u`                   |
| Redo                               |                       | `ctrl+r`              |

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
| Move to end of line                |                       | `$`                   | 
| Move to beginning of line          |                       | `0`                   | 
| Move forward by word               |                       | `w`                   | 
| Move backward by word              |                       | `b`                   |
| `--------------------------------` | `-------------------` | `-------------------` |
| Up one line                        |                       | `k`, `↑`              | 
| Down one line                      |                       | `j`, `↓`              |
| Left one character                 |                       | `h`, `←`              | 
| Right one character                |                       | `l`, `➡`              | 
| `--------------------------------` | `-------------------` | `-------------------` |
| Jump to end of file                |                       | `G`                   | 
| Jump to beginning of file          |                       | `gg`                  | 
| `--------------------------------` | `-------------------` | `-------------------` |
| Jump forward one sentence          |                       | `)`                   | 
| Jump backward one sentence         |                       | `(`                   | 
| Jump forward one paragraph         |                       | `}`                   | 
| Jump backward one paragraph        |                       | `{`                   | 
| Jump to top of the screen          |                       | `H`                   | 
| Jump to bottom of the screen       |                       | `L`                   | 
| `--------------------------------` | `-------------------` | `-------------------` |
| Go to line                         | `:##`                 | `##G`,`##gg`          | 

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



## Split Window

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
| Increase window height             |                       | `ctrl+w # +`          | 
| Decrease window height             |                       | `ctrl+w # -`          | 
| Increase window width              |                       | `ctrl+w # >`          | 
| Decrease window width              |                       | `ctrl+w # <`          | 
| `--------------------------------` | `-------------------` | `-------------------` | 
| Max current window vertical        |                       | `ctrl+w _`            | 
| Max current window horizontal      |                       | `ctrl+w \|`           | 
| Make all equal size                |                       | `ctrl+w =`            | 
| `--------------------------------` | `-------------------` | `-------------------` | 
| Close current window               | `:close`              |                       | 

*exit using `qa`*

[[top]](#vim-cheatsheet)



## Tabs

| Description                        | Command               | Keystroke             |
| ---------------------------------- | --------------------- | --------------------- |
| `--------------------------------` | `-------------------` | `-------------------` |
| Open/new files in tab              | `vim -p path/*.*`     |                       | 
| Open/new file in tab               | `:tabe filepath`      |                       | 
| Find/open file in tab              | `:tabf filepath`      |                       | 
| List all the open tabs             | `:tabs`               |                       |
| `--------------------------------` | `-------------------` | `-------------------` |
| Go to next tab                     | `:tabn`               | `gt`                  | 
| Go to previous tab                 | `:tabp`               | `gT`                  | 
| Go to indexed tab                  | `:tabn #`             | `#gt`                 | 
| Go to first tab                    | `:tabfirst`           |                       | 
| Go to last tab                     | `:tablast`            |                       | 
| `--------------------------------` | `-------------------` | `-------------------` |
| Move current tab to first          | `:tabm 0`             |                       | 
| Move current tab to last           | `:tabm`               |                       | 
| Move current tab to index          | `:tabm #`             |                       | 
| `--------------------------------` | `-------------------` | `-------------------` |
| Close current tab                  | `:tabc`/`:q`/`:q!`    |                       | 
| Close particular tab               | `:tabc #`.            |                       | 
| Close other tabs                   | `:tabo`               |                       | 

[[top]](#vim-cheatsheet)



## Explore

| Description                        | Command               | Keystroke             |
| ---------------------------------- | --------------------- | --------------------- |
| `--------------------------------` | `-------------------` | `-------------------` |
| Simple file explorer               | `vim path`            |                       | 
| Open explorer                      | `:Ex path`            |                       | 
| Open explorer in horizontal        | `:Sexplore`           |                       | 
| Open explorer in vertical          | `:Vexplore`           |                       | 

*exit using `qa`*

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

