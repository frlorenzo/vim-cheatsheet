# Buffers

## Managing Buffers

- `:e file`     - open/new file into buffer
- `:ls`         - list all buffers
- `:b #`        - Display buffer by # 
- `:b file`     - Display buffer by file
- `:bd #`       - Close buffer #



## Managing Splits

- `:vertical rightbelow sf <file>`    - create vertical split, read file into buffer in right window
- `:vertical [leftabove] sf <file>`   - create vertical split, read file into buffer in left window



## Navigating Splits

- `Ctrl-w + hjkl` - Navigate between windows


## Buffer Switching using `:b <Tab>`

```
set wildchar=<Tab> wildmenu wildmode=full " :b then Tab
```

Add function keys map

```
set wildcharm=<C-Z>
nnoremap <F5> :buffer <C-Z> 
```

