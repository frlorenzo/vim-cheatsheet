# Operators

Operators can work on words, lines, sentence, paragraphs. Similar to cut/copy/paste (delete/yank/put).

```
Operator + Scope = Command
```


## Delete Operator

- `dd` 	delete current line
- `de`	from cursor to the end of the current word
- `dw`	from cursor to the beginning of the next word
- `db` 	from the letter before the cursor backward
- `d$` 	from the cursor to the end of the line
- `d0`	from before the cursor to the beginning of line
- `d)`	from cursor to the beginning of next sentence
- `d(`	from before the cursor back to the beginning of sentence
- `d{`	from cursor to the end of a paragraph
- `d}`	from before the cursor back to the beginning of paragraph


## Change Operator

- `cc` 	change current line
- `ce`	from cursor to the end of the current word
- `cw`	from cursor to the beginning of the next word
- `cb` 	from the letter before the cursor backward
- `c$` 	from the cursor to the end of the line
- `c0`	from before the cursor to the beginning of line
- `c)`	from cursor to the beginning of next sentence
- `c(`	from before the cursor back to the beginning of sentence
- `c{`	from cursor to the end of a paragraph
- `c}`	before the cursor back to the beginning of paragraph


## Yank Operator

- `yy` 	yank current line
- `ye`	from cursor to the end of the current word
- `yw`	from cursor to the beginning of the next word
- `yb` 	from the letter before the cursor backward
- `y$` 	from the cursor to the end of the line
- `y0`	from before the cursor to the beginning of line
- `y)`	from cursor to the beginning of next sentence
- `y(`	from before the cursor back to the beginning of sentence
- `y{`	from cursor to the end of a paragraph
- `y}`	before the cursor back to the beginning of paragraph
- `#y`  from cursor yank number of lines


## Put Operator

- `p` 	Puts whatever was last deleted/yanked after cursor
- `P`	Puts whatevet was last deleted/yanked before cursor

