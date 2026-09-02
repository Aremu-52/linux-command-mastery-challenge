# Day 21 Commands – Viewing Processes

### 1. `ps aux`
**Syntax:** `ps aux`  
**What it does:** Shows a detailed list of all running processes.  
**When I use it:** To see everything that is currently running on the system.

### 2. `ps -ef`
**Syntax:** `ps -ef`  
**What it does:** Lists all processes in full format.  
**When I use it:** Alternative to `ps aux` with different columns.

### 3. `ps -u`
**Syntax:** `ps -u username`  
**What it does:** Shows processes belonging to a specific user.  
**When I use it:** To check only my own processes or another user’s processes.

### 4. `top`
**Syntax:** `top`  
**What it does:** Shows a live, updating view of processes and resource usage.  
**When I use it:** Monitoring CPU and memory usage in real time.

### 5. `htop`
**Syntax:** `htop`  
**What it does:** A more user-friendly and interactive version of `top`.  
**When I use it:** Preferable when available for easier process monitoring.

### 6. `pgrep`
**Syntax:** `pgrep process-name`  
**What it does:** Finds the PID of a process by its name.  
**When I use it:** Quickly getting the Process ID of a running program.

### 7. `pstree`
**Syntax:** `pstree`  
**What it does:** Displays processes in a tree structure showing parent-child relationships.  
**When I use it:** Understanding how processes are related.

### 8. `lsof -i`
**Syntax:** `lsof -i` or `lsof -i :port`  
**What it does:** Lists open network connections and which process is using a port.  
**When I use it:** Finding which process is listening on a specific port.

### 9. `jobs`
**Syntax:** `jobs`  
**What it does:** Shows background jobs in the current terminal session.  
**When I use it:** Checking jobs I started in the background.

### 10. `nice` / `renice`
**Syntax:** `nice -n value command` / `renice -n value PID`  
**What it does:** Starts a process with a modified priority or changes the priority of a running process.  
**When I use it:** Controlling how much CPU time a process gets.