# Vim Cheatsheet

For detailed information, please see the vim motion documentation [here](https://vimdoc.sourceforge.net/htmldoc/motion.html#motion.txt) by Bram Moolenaar.

## Default Vim Commands

### \<d or D\> Commands

#### Deleting

| Mode   |        Command        | Action                                                                |
| ------ | :-------------------: | --------------------------------------------------------------------- |
| normal |          dd           | delete line                                                           |
|        |          dl           | delete character                                                      |
|        |      d\<motion\>      | delete -> ending position after \<motion\>                            |
|        |          dw           | delete character -> end of current word space (inclusive)             |
|        |          d$           | delete character -> end of line (inclusive)                           |
|        |          d^           | delete character -> backward to first non-white-space character       |
|        |          d$           | delete character -> end of line (inclusive)                           |
|        |          d$           | delete character -> end of line (inclusive)                           |
|        |          db           | delete character -> beginning of current word                         |
|        |     \<number\>dd      | delete \<number\> lines                                               |
|        | \<number\>d\<motion\> | delete character -> ending position after \<motion\> \<number\> times |

### \<c or C\> Commands

#### Changing

| Mode |     Command     | Action                                                |
| ---- | :-------------: | ----------------------------------------------------- |
|      |       cw        | delete word and switch to insert mode                 |
|      |  \<number\>cw   | delete \<number\> words and switch to insert mode     |
|      |       cl        | delete letter and switch to insert mode               |
|      | ci\<character\> | delete within \<character\> and switch to insert mode |

### \<g or G\> Commands

#### Navigation

| Mode          |        Command         | Action                                                                                                 |
| ------------- | :--------------------: | ------------------------------------------------------------------------------------------------------ |
| normal,visual |           gg           | navigate cursor to top of page                                                                         |
|               |           G            | navigate cursor to the bottom of the page                                                              |
| normal        | g\<navigation motion\> | navigate within a paragraph with no line breaks                                                        |
|               |           gi           | return to previous cursor position on insert mode and enter insert mode                                |
| visual        |           gv           | return to previous cursor position on visual mode and enter visual mode                                |
| normal        |       gq<enter>        | auto format paragraph with line breaks                                                                 |
|               |           gf           | if personal library string = file_name and same path or if given valid path then will open up the file |

#### Other

| Mode | Command | Action                                                        |
| ---- | :-----: | ------------------------------------------------------------- |
|      |   ga    | gives character encoding information on the current character |
|      |   g+    | redo                                                          |
|      |   g-    | undo                                                          |
|      |   g&    | redo substitution                                             |
