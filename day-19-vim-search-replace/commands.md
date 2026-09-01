# Day 19 Commands – Vim Navigation & Search/Replace

### 1. `gg` / `G`
**Syntax:** `gg` or `G`  
**What it does:** `gg` jumps to the first line of the file. `G` jumps to the last line.  
**When I use it:** Quick navigation to the top or bottom of a file.

### 2. `:10` (go to line)
**Syntax:** `:10`  
**What it does:** Jumps directly to line number 10 (or any number you type).  
**When I use it:** When I know the exact line I need to edit.

### 3. `/` (search forward)
**Syntax:** `/pattern`  
**What it does:** Searches forward in the file for the given pattern.  
**When I use it:** Finding text quickly while moving downward.

### 4. `?` (search backward)
**Syntax:** `?pattern`  
**What it does:** Searches backward in the file for the given pattern.  
**When I use it:** Finding text while moving upward.

### 5. `n` / `N`
**Syntax:** `n` or `N`  
**What it does:** `n` goes to the next match, `N` goes to the previous match.  
**When I use it:** Jumping between all occurrences of a search.

### 6. `:%s/old/new/g`
**Syntax:** `:%s/old/new/g`  
**What it does:** Replaces every occurrence of “old” with “new” in the entire file.  
**When I use it:** Global search and replace.

### 7. `dw`
**Syntax:** `dw`  
**What it does:** Deletes the word under (or after) the cursor.  
**When I use it:** Quickly removing a word.

### 8. `x`
**Syntax:** `x`  
**What it does:** Deletes the single character under the cursor.  
**When I use it:** Removing individual characters.

### 9. `o` / `O`
**Syntax:** `o` or `O`  
**What it does:** `o` opens a new line below and enters Insert mode. `O` opens a new line above.  
**When I use it:** Adding new lines quickly.

### 10. `ZZ`
**Syntax:** `ZZ`  
**What it does:** Saves the file and quits Vim in one action.  
**When I use it:** Fast way to save and exit.