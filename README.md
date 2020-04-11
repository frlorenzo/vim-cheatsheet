# Vim Cheatsheet


- [File](#file)
- [Copy/Paste](#copypaste)
- [Conversion](#conversion)
- [Cursor Movement](#cursormovement)
- [Search/Replace](#searchreplace)
- [Splits](#splits)
- [Tabs](#tabs)
- [Explore](#explore)
- [Wrapping](#wrapping)


## File 

| Description                   | Command               | Keystroke     |
| ----------------------------- | --------------------- | ------------- | 
| `---------------------------` | `-------------------` | `-----------` | 
| Open/new file                 | `:e filepath`         |               | 
| Find/open file                | `:find filepath`      |               | 
| Save/write file               | `:w`/`:w!`            |               | 
| Save/write file as            | `:w filepath`         |               | 
| Save/write all, then quit     | `:wqa`                |               | 
| Quit vim/close current tab    | `:q`/`:q!`            |               | 
| Quit vim/close all            | `:qa`/`:qa!`          |               | 

[[top]](#vim-cheatsheet)



## Copy/Paste

| Description                   | Command               | Keystroke     |
| ----------------------------- | --------------------- | ------------- | 
| `---------------------------` | `-------------------` | `-----------` | 
| Select text                   |                       | `v`           | 
| Select line                   |                       | `V`           |
| Select block                  |                       | `ctrl+v`      |
| Select all                    |                       | `ggVG`        |
| Copy selection                |                       | `y`           |
| Copy line                     |                       | `yy`          |
| Paste after cursor            |                       | `p`           |
| Paste before cursor           |                       | `P`           |
| Cut selection                 |                       | `d`           |
| Cut line                      |                       | `dd`          |
| Undo                          |                       | `u`           |
| Redo                          |                       | `ctrl+r`      |

[[top]](#vim-cheatsheet)



## Conversion

| Description                   | Command               | Keystroke     |
| ----------------------------- | --------------------- | ------------- | 
| `---------------------------` | `-------------------` | `-----------` | 
| Convert to upper case         |                       | `gU`
| Convert to lower case         |                       | `gu`

[[top]](#vim-cheatsheet)



## Cursor Movement

| Description                   | Command               | Keystroke     |
| ----------------------------- | --------------------- | ------------- | 
| `---------------------------` | `-------------------` | `-----------` | 
| Go to line                    | `:{i}`                | `{i}G`,`{i}gg`| 
| Move to end of line           |                       | `$`           | 
| Move to beginning of line     |                       | `0`           | 
| Move to forward by word       |                       | `w`           | 
| Move to backward by word      |                       | `b`           | 
| Move up one line              |                       | `k`, `↑`      | 
| Move down one line            |                       | `j`, `↓`      | 
| Move left one character       |                       | `h`, `←`      | 
| Move right one character      |                       | `l`, `➡`      | 
| Jump to end of file           |                       | `G`           | 
| Jump to beginning of file     |                       | `gg`          | 
| Jump forward one sentence     |                       | `)`           | 
| Jump backward one sentence    |                       | `(`           | 
| Jump forward one paragraph    |                       | `}`           | 
| Jump backward one paragraph   |                       | `{`           | 
| Jump to top of the screen     |                       | `H`           | 
| Jump to bottom of the screen  |                       | `L`           | 

[[top]](#vim-cheatsheet)



## Search/Replace

| Description                   | Command               | Keystroke     |
| ----------------------------- | --------------------- | ------------- | 
| `---------------------------` | `-------------------` | `-----------` | 
| Search/replace text           | `:%s/search/replace/g`|               |
| Search forward                | `:/pattern`           |               |   
| Search backward               | `:?pattern`           |               |
| Search next                   |                       | `n`           |
| Search previous               |                       | `N`           |
| Make insensitive search       | `:set ignorecase`     |               |

[[top]](#vim-cheatsheet)



## Splits

| Description                   | Command               | Keystroke     |
| ----------------------------- | --------------------- | ------------- | 
| `---------------------------` | `-------------------` | `-----------` | 
| Create veritcal split         | `:vsp [path]`         |               | 
| Create horizontal split       | `:sp [path]`          |               | 
| Go to left panel              |                       | `ctrl+w h`    | 
| Go to lower panel             |                       | `ctrl+w j`    | 
| Go to upper panel             |                       | `ctrl+w k`    | 
| Go to right panel             |                       | `ctrl+w l`    | 

*exit using `qa`*

[[top]](#vim-cheatsheet)



## Tabs

| Description                   | Command               | Keystroke     |
| ----------------------------- | --------------------- | ------------- | 
| `---------------------------` | `-------------------` | `-----------` | 
| Open/new files in tab         | `vim -p path/*.*`     |               | 
| Open/new file in tab          | `:tabe filepath`      |               | 
| Find/open file in tab         | `:tabf filepath`      |               | 
| Go to next tab                | `:tabn`               | `gt`          | 
| Go to previous tab            | `:tabp`               | `gT`          | 
| Go to indexed tab             | `:tabn {i}`           | `{i}gt`       | 
| Go to first tab               | `:tabfirst`           |               | 
| Go to last tab                | `:tablast`            |               | 
| List all the open tabs        | `:tabs`               |               | 
| Close current tab             | `:tabc`/`:q`/`:q!`    |               | 
| Close particular tab          | `:tabc {i}`           |               | 
| Close other tabs              | `:tabo`               |               | 
| Move current tab to first     | `:tabm 0`             |               | 
| Move current tab to last      | `:tabm`               |               | 
| Move current tab to index     | `:tabm {i}`           |               | 

[[top]](#vim-cheatsheet)



## Explore

| Description                   | Command               | Keystroke     |
| ----------------------------- | --------------------- | ------------- | 
| `---------------------------` | `-------------------` | `-----------` | 
| Simple file explorer          | `vim path`            |               | 
| Open explorer                 | `:Explore path`       |               | 
| Open explorer in horizontal   | `:Sexplore`           |               | 
| Open explorer in vertical     | `:Vexplore`           |               | 

*exit using `qa`*

[[top]](#vim-cheatsheet)



## Wrapping

| Description                   | Command               | Keystroke     |
| ----------------------------- | --------------------- | ------------- |
| `---------------------------` | `-------------------` | `-----------` | 
| Toggle wrapping               | `:set wrap`           |               |
| Toggle no wrapping            | `:set nowrap`         |               |

[[top]](#vim-cheatsheet)

