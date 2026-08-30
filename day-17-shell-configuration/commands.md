# Day 17 Commands – Persisting Configuration

### 1. `nano ~/.bashrc`
**Syntax:** `nano ~/.bashrc`  
**What it does:** Opens the personal Bash configuration file for editing.  
**When I use it:** To add permanent aliases or environment variables.

### 2. `source ~/.bashrc`
**Syntax:** `source ~/.bashrc`  
**What it does:** Reloads the `.bashrc` file so changes take effect immediately.  
**When I use it:** After editing `.bashrc` without opening a new terminal.

### 3. `cat ~/.bash_profile`
**Syntax:** `cat ~/.bash_profile`  
**What it does:** Displays the content of `.bash_profile` (used for login shells).  
**When I use it:** Checking login shell configuration. (Note: Often missing on Ubuntu.)

### 4. `sudo nano /etc/environment`
**Syntax:** `sudo nano /etc/environment`  
**What it does:** Edits the system-wide environment variables file.  
**When I use it:** Setting variables that apply to all users.

### 5. `sudo nano /etc/bash.bashrc`
**Syntax:** `sudo nano /etc/bash.bashrc`  
**What it does:** Edits the system-wide Bash configuration file.  
**When I use it:** Making Bash settings available to all users.

### 6. `alias`
**Syntax:** `alias` or `alias name='command'`  
**What it does:** Lists current aliases or creates a new one.  
**When I use it:** Creating shortcuts for long commands.

### 7. `unalias`
**Syntax:** `unalias name`  
**What it does:** Removes an alias.  
**When I use it:** When I no longer need a temporary alias.

### 8. `type`
**Syntax:** `type command`  
**What it does:** Shows how a command is interpreted (alias, builtin, file, etc.).  
**When I use it:** Understanding what a command really is.

### 9. `which`
**Syntax:** `which command`  
**What it does:** Shows the full path of an executable.  
**When I use it:** Finding where a program is located.

### 10. `whereis`
**Syntax:** `whereis command`  
**What it does:** Locates the binary, source, and man page of a command.  
**When I use it:** Getting more complete location information about a program.