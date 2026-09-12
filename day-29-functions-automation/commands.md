# Day 29 Commands – Functions, Arguments & Automation

### 1. `function_name() { }`
**Syntax:** `check_service() { ... }`  
**What it does:** Defines a reusable function.  
**When I use it:** When I want to reuse the same block of code.

### 2. `$1` / `$2`
**Syntax:** `$1`, `$2`  
**What it does:** Represents the first and second arguments passed to the script or function.  
**When I use it:** Receiving input values in scripts.

### 3. `$#` / `$*` / `$@`
**Syntax:** `$#`, `$@`  
**What it does:** `$#` = number of arguments, `$@` = all arguments.  
**When I use it:** Handling multiple inputs.

### 4. `$0`
**Syntax:** `$0`  
**What it does:** Contains the name of the script.  
**When I use it:** Displaying usage information.

### 5. `$?`
**Syntax:** `$?`  
**What it does:** Holds the exit code of the last command (0 = success).  
**When I use it:** Checking if a command succeeded or failed.

### 6. Crontab syntax
**Syntax:** `minute hour day month weekday command`  
**What it does:** Defines when a cron job should run.  
**When I use it:** Scheduling recurring tasks.

### 7. Cron scheduling (`0 * * * *`)
**Syntax:** `0 * * * * /path/to/script`  
**What it does:** Runs a command at the start of every hour.  
**When I use it:** Hourly automation.

### 8. `nohup script.sh &`
**Syntax:** `nohup ./script.sh &`  
**What it does:** Runs a script in the background and keeps it running after logout.  
**When I use it:** Long-running background tasks.

### 9. `trap`
**Syntax:** `trap "command" SIGNAL`  
**What it does:** Catches signals (e.g. Ctrl+C) and runs a command.  
**When I use it:** Cleaning up when a script is interrupted.

### 10. `logger`
**Syntax:** `logger "message"`  
**What it does:** Writes a message to the system log.  
**When I use it:** Recording important events from scripts.