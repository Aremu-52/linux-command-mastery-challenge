# Day 20 Commands – Text Processing & Pipes

### 1. `grep`
**Syntax:** `grep pattern file`  
**What it does:** Searches for a pattern and shows matching lines.  
**When I use it:** Finding specific text inside files.

### 2. `grep -r`
**Syntax:** `grep -r pattern directory`  
**What it does:** Searches for a pattern recursively in all files under a directory.  
**When I use it:** Searching across many files at once.

### 3. `grep -i`
**Syntax:** `grep -i pattern file`  
**What it does:** Searches while ignoring case.  
**When I use it:** When I don’t know if the text is uppercase or lowercase.

### 4. `sort`
**Syntax:** `sort file`  
**What it does:** Sorts lines alphabetically.  
**When I use it:** Organizing text output.

### 5. `sort -n`
**Syntax:** `sort -n file`  
**What it does:** Sorts lines numerically.  
**When I use it:** Sorting numbers correctly.

### 6. `uniq`
**Syntax:** `uniq`  
**What it does:** Removes consecutive duplicate lines.  
**When I use it:** Usually after `sort` to get unique lines.

### 7. `cut -d',' -f`
**Syntax:** `cut -d',' -f1 file`  
**What it does:** Extracts specific columns using a delimiter.  
**When I use it:** Working with CSV or delimited data.

### 8. `awk '{print $1}'`
**Syntax:** `awk '{print $1}' file`  
**What it does:** Prints selected columns from each line.  
**When I use it:** Extracting fields from structured text.

### 9. `sed 's/old/new/g'`
**Syntax:** `sed 's/old/new/g' file`  
**What it does:** Replaces text on each line.  
**When I use it:** Quick find-and-replace in files or pipelines.

### 10. Pipe chains (`|`)
**Syntax:** `command1 | command2 | command3`  
**What it does:** Sends the output of one command as input to the next.  
**When I use it:** Building powerful one-line text processing workflows.