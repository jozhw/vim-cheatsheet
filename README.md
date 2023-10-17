# Vim Cheatsheet

For detailed information, please see the vim motion documentation [here](https://vimdoc.sourceforge.net/htmldoc/motion.html#motion.txt) by Bram Moolenaar.

## Default Vim Commands

### Deleting & Changing

| Mode  | Command | Action  | 
| ------------- |:------------------------:| ------------------------------------------------------------------------- |
| normal        | dd                       | delete line                                                               |
|               | dl                       | delete character                                                          |
|               | d\<motion\>              | delete -> ending position after \<motion\>                                |
|               | dw                       | delete character -> end of current word space (inclusive)                 |
|               | d$                       | delete character -> end of line (inclusive)                               |
|               | d^                       | delete character -> backward to first non-white-space character           |
|               | d$                       | delete character -> end of line (inclusive)                               |
|               | d$                       | delete character -> end of line (inclusive)                               |
|               | db                       | delete character -> beginning of current word                             |
|               | \<number\>dd             | delete \<number\> lines                                                   |
|               | \<number\>d\<motion\>    | delete character -> ending position after \<motion\> \<number\> times     |
|               |                          |                                                                           |
|               | cw                       | delete word and switch to insert mode                                     |
|               | \<number\>cw             | delete \<number\> words and switch to insert mode                         |
|               | cl                       | delete letter and switch to insert mode                                   |
|               | ci\<character\>          | delete within \<character\> and switch to insert mode                     |


