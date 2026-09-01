# Day 19 Practice Drill

## Task
In a 50-line config file, jump straight to line 10, search for a keyword, jump between all matches, then replace every occurrence of one word with another across the whole file.

## Commands I practiced

```bash
vim day19.txt

gg and G to jump to top and bottom
:10 to go to line 10
/error to search forward
?error to search backward
n and N to move between matches
:%s/error/issue/g for global replace
dw to delete a word
x to delete a character
o and O to open new lines
ZZ to save and quit

Result

Successfully navigated the file using line numbers and search.
Performed a global search and replace.
Practiced deleting words/characters and opening new lines.

What I learned
Vim navigation commands (gg, G, :line, /, n) combined with :%s make editing large files much faster than using arrow keys alone.
text