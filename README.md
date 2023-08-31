# System-76-Keyboard-Configurations

Holds all my configs for key mappings and layer layout

## Colors

### Green

- `h`  - move cursor left
- `j`  - move cursor down
- `k`  - move cursor up
- `l`  - move cursor right
- `f`  - jump to next occurrence of character
- `F`  - jump to the previous occurrence of character
- `gg` - go to the first line of the document
- `G`  - go to the last line of the document
- `H`  - move to top of screen
- `M`  - move to middle of screen
- `L`  - move to bottom of screen
- `w`  - jump forwards to the start of a word
- `W`  - jump forwards to the start of a word (words can contain punctuation)
- `e`  - jump forwards to the end of a word
- `E`  - jump forwards to the end of a word (words can contain punctuation)
- `%`  - move cursor to matching character (default supported pairs: '()', '{}', '[]' - use :h matchpairs in vim for more info)
- `0`  - jump to the start of the line
- `^`  - jump to the first non-blank character of the line
- `$`  - jump to the end of the line
- `b`  - jump backwards to the start of a word
- `B`  - jump backwards to the start of a word (words can contain punctuation)
- `n`  - repeat search in same direction
- `N`  - repeat search in opposite direction

### Red

- `r`         - replace a single character.
- `p`         - put (paste) the clipboard after cursor
- `yy`        - yank (copy) a line
- `y$` or `Y` - yank (copy) to end of line
- `u`         - undo
- `s`         - delete character and substitute text
- `d`         - delete marked text
- `x`         - delete (cut) character

#### Blue

- `c`         - change (replace) entire line
- `i`          - insert before the cursor
- `a`          - insert (append) after the cursor
- `o`          - append (open) a new line below the current line

### Yellow

- `v` - start visual mode, mark lines, then do a command (like y-yank)
