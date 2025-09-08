# Vim Wiki

## NerdTree

* `o` open in a new buffer or open/close a directory
* `i` open in a new horizontal split
* `s` open in a new vertical split

## commenting

While in `Normal Mode`

* comment a paragragh - `gcap`
* comment current line - `gcc`

While in `Visual Mode`

* `gc` - toggle commenting on current selection

While in `Command Mode`

* `:7,17Commentary` - to comment from line 7-17
* `:global` invocation like with `:g/TODO/Commentary`

## coding

Toggle single-line/multi-line code form

* `gS` to split a one-liner into multiple lines
* `gJ` (with the cursor on the first line of a block) to join a block into a single-line statement.

### folding

* `zO` Open all folds under the cursor recursively
* `zC` Close all folds under the cursor recursively.
*
* `zo` Open one fold under the cursor. When a count is given, that many folds deep will be opened.
* `zc` Close one fold under the cursor. When a count is given, that many folds deep are closed.
*
* `za` Toggle the fold under the cursor. When a count is given, that many closed folds are opened.
* `zA` When on a closed fold: open it recursively. When on an open fold: close it recursively and set 'foldenable'.
* `zv` View cursor line: Open just enough folds to make the line in which the cursor is located not folded.
*
* `zM` Close all folds
* `zR` Open all folds.
