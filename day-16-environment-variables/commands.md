# Day 16 Commands – Environment Variables

### 1. `printenv`
**Syntax:** `printenv`  
**What it does:** Displays all environment variables.  
**When I use it:** To see the full environment of the current session.

### 2. `printenv HOME`
**Syntax:** `printenv VARIABLE`  
**What it does:** Shows the value of a specific environment variable.  
**When I use it:** When I need the value of one particular variable.

### 3. `echo $VAR`
**Syntax:** `echo $VARIABLE`  
**What it does:** Prints the value of a variable.  
**When I use it:** Quick way to check a variable’s value.

### 4. `export`
**Syntax:** `export NAME=value`  
**What it does:** Creates or updates an environment variable.  
**When I use it:** When I want a variable to be available to child processes.

### 5. `unset`
**Syntax:** `unset NAME`  
**What it does:** Removes an environment variable.  
**When I use it:** When I no longer need a temporary variable.

### 6. `env`
**Syntax:** `env`  
**What it does:** Displays the current environment variables.  
**When I use it:** Similar to printenv, useful for inspecting the environment.

### 7. `source`
**Syntax:** `source filename`  
**What it does:** Runs a script in the current shell so that variables and settings take effect immediately.  
**When I use it:** Loading variables or configuration from a file.

### 8. `echo $PATH`
**Syntax:** `echo $PATH`  
**What it does:** Shows the list of directories the shell searches for commands.  
**When I use it:** Checking or troubleshooting command locations.

### 9. `export PATH=$PATH:`
**Syntax:** `export PATH=$PATH:/new/directory`  
**What it does:** Adds a new directory to the PATH for the current session.  
**When I use it:** Making my own scripts executable from anywhere.

### 10. `cat /etc/environment`
**Syntax:** `cat /etc/environment`  
**What it does:** Displays system-wide environment variables.  
**When I use it:** Viewing variables that apply to all users.