# Day 25 Commands – Process & Service Checkpoint

### 1. `ps aux | grep`
**Syntax:** `ps aux | grep process-name`  
**What it does:** Lists processes and filters them by name.  
**When I use it:** To quickly find a specific running process.

### 2. `systemctl status <svc>`
**Syntax:** `systemctl status service-name`  
**What it does:** Shows the detailed status of a service.  
**When I use it:** Checking whether a service is healthy and running.

### 3. `journalctl -u <svc> --since today`
**Syntax:** `journalctl -u service-name --since today`  
**What it does:** Shows today’s logs for a specific service.  
**When I use it:** Investigating recent activity or problems of a service.

### 4. `kill -0`
**Syntax:** `kill -0 PID`  
**What it does:** Checks if a process is alive without sending a real signal.  
**When I use it:** Liveness check of a process.

### 5. `uptime`
**Syntax:** `uptime`  
**What it does:** Shows how long the system has been running and the load average.  
**When I use it:** Quick health check of system availability.

### 6. `free -h`
**Syntax:** `free -h`  
**What it does:** Displays memory usage in human-readable format.  
**When I use it:** Checking available and used RAM.

### 7. `vmstat`
**Syntax:** `vmstat`  
**What it does:** Shows virtual memory, CPU, and process statistics.  
**When I use it:** Deeper look at system performance.

### 8. `iostat`
**Syntax:** `iostat`  
**What it does:** Shows CPU and disk I/O statistics.  
**When I use it:** Checking disk activity and performance.

### 9. `watch`
**Syntax:** `watch -n 2 command`  
**What it does:** Repeatedly runs a command and updates the output.  
**When I use it:** Live monitoring of a value (e.g. memory).

### 10. `crontab -e` / `crontab -l`
**Syntax:** `crontab -l` or `crontab -e`  
**What it does:** Lists or edits scheduled cron jobs.  
**When I use it:** Viewing or managing scheduled tasks.