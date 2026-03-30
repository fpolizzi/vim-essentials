# Vim Essentials

## Saving And Quitting

| Shortcut | Action                   |
| -------- | ------------------------ |
| **:w**   | write file               |
| **:wq**  | write file and quit      |
| **:q**   | quit                     |
| **:q!**  | quit and discard changes |

## Navigating

| Shortcut | Action                                            |
| -------- | ------------------------------------------------- |
| **h**    | move cursor left                                  |
| **j**    | move cursor down                                  |
| **k**    | move cursor up                                    |
| **l**    | move cursor right                                 |
| **gg**   | moves up to the beginning of the file             |
| **G**    | moves down to the end of the file                 |
| **0**    | move to the beginning of the line                 |
| **^**    | move to the first non space character of the line |
| **$**    | move to the end of the line                       |

## Editing

| Shortcut     | Action                                   |
| ------------ | ---------------------------------------- |
| **I**        | insert mode at the beginning of the line |
| **i**        | insert mode at the cursor                |
| **a**        | append after the cursor                  |
| **A**        | Append at the end of line                |
| **o**        | insert line below current line           |
| **O**        | insert line above current line           |
| **u**        | undo last change                         |
| **dd**       | delete current line                      |
| **ctrl + r** | redo last undo                           |
| **yy**       | copy current line                        |
| **p**        | paste copied line                        |

## Search And Replace

| Shortcut                  | Action                               |
| ------------------------- | ------------------------------------ |
| **/**                     | search                               |
| **n**                     | go to next occurrence                |
| **N**                     | go to previous occurrence            |
| **:%s/search/replace/g**  | search and replace                   |
| **:%s/search/replace/gc** | search and replace with confirmation |

## Visual Mode

| Shortcut     | Action                |
| ------------ | --------------------- |
| **v**        | select a character    |
| **V**        | select an entire line |
| **ctrl + v** | select a block        |
| **y**        | yank (copy) selection |
| **p**        | paste selection       |
