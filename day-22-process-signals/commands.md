# Day 22 Commands – Controlling Processes with Signals

### 1. `kill`
**Syntax:** `kill PID`  
**What it does:** Sends a signal to a process (default is SIGTERM – polite termination request).  
**When I use it:** To stop a process using its Process ID.

### 2. `kill -9`
**Syntax:** `kill -9 PID`  
**What it does:** Forcefully kills a process (SIGKILL – cannot be ignored).  
**When I use it:** When a process does not respond to a normal kill.

### 3. `kill -HUP`
**Syntax:** `kill -HUP PID`  
**What it does:** Sends the Hang-Up signal (often used to reload configuration).  
**When I use it:** To ask a service to reload its settings without fully stopping.

### 4. `killall`
**Syntax:** `killall process-name`  
**What it does:** Kills processes by name instead of PID.  
**When I use it:** When I want to stop all processes with the same name.

### 5. `pkill`
**Syntax:** `pkill process-name`  
**What it does:** Kills processes by name or other attributes (more flexible than killall).  
**When I use it:** Stopping processes based on name or pattern.

### 6. `fg`
**Syntax:** `fg` or `fg %jobnumber`  
**What it does:** Brings a background or suspended job to the foreground.  
**When I use it:** When I want to interact with a job again.

### 7. `bg`
**Syntax:** `bg` or `bg %jobnumber`  
**What it does:** Resumes a suspended job in the background.  
**When I use it:** To continue a paused job without blocking the terminal.

### 8. `Ctrl + Z`
**Syntax:** Press `Ctrl + Z`  
**What it does:** Suspends (pauses) the currently running foreground process.  
**When I use it:** To temporarily pause a command.

### 9. `nohup`
**Syntax:** `nohup command &`  
**What it does:** Runs a command that continues even after you log out.  
**When I use it:** For long-running tasks that must survive terminal disconnection.

### 10. `disown`
**Syntax:** `disown` or `disown %jobnumber`  
**What it does:** Removes a job from the shell’s job table so it is not killed when the shell exits.  
**When I use it:** To keep a background process running after closing the terminal.