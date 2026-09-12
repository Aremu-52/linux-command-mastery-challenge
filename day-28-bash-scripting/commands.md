# Day 28 Commands – Bash Scripting Foundations

### 1. `#!/bin/bash` (shebang)
**Syntax:** `#!/bin/bash`  
**What it does:** Tells the system to run the script with Bash.  
**When I use it:** As the first line of every Bash script.

### 2. `chmod +x script.sh`
**Syntax:** `chmod +x script.sh`  
**What it does:** Makes the script executable.  
**When I use it:** Before running a new script.

### 3. `./script.sh`
**Syntax:** `./script.sh`  
**What it does:** Executes the script from the current directory.  
**When I use it:** Running a script I just created.

### 4. `VAR=value`
**Syntax:** `NAME="Tijani"`  
**What it does:** Creates a variable and stores a value.  
**When I use it:** Storing data to use later in the script.

### 5. `$( )` command substitution
**Syntax:** `TODAY=$(date)`  
**What it does:** Runs a command and stores its output in a variable.  
**When I use it:** Capturing the result of another command.

### 6. `read -p`
**Syntax:** `read -p "Enter your name: " NAME`  
**What it does:** Asks the user for input and stores it.  
**When I use it:** Making scripts interactive.

### 7. `if / elif / else / fi`
**Syntax:** `if [ condition ]; then ... else ... fi`  
**What it does:** Runs different code based on a condition.  
**When I use it:** Making decisions in a script.

### 8. `-gt` / `-lt` / `-eq`
**Syntax:** `[ $a -gt $b ]`  
**What it does:** Compares numbers (greater than, less than, equal).  
**When I use it:** Numeric conditions in if statements and loops.

### 9. `for` loop
**Syntax:** `for item in list; do ... done`  
**What it does:** Repeats commands for each item in a list.  
**When I use it:** Performing the same action on multiple items.

### 10. `while` loop
**Syntax:** `while [ condition ]; do ... done`  
**What it does:** Repeats commands as long as a condition is true.  
**When I use it:** Repeating actions until a condition changes.