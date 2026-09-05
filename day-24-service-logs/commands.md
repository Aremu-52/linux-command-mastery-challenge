# Day 24 Commands – Deeper Service Management & Logs

### 1. `systemctl list-units --type=service`
**Syntax:** `systemctl list-units --type=service`  
**What it does:** Lists all service units on the system.  
**When I use it:** To see every service managed by systemd.

### 2. `systemctl list-units --state=failed`
**Syntax:** `systemctl list-units --state=failed`  
**What it does:** Shows only services that are in a failed state.  
**When I use it:** Quickly finding services that have problems.

### 3. `systemctl daemon-reload`
**Syntax:** `sudo systemctl daemon-reload`  
**What it does:** Reloads systemd manager configuration.  
**When I use it:** After creating or modifying service files.

### 4. `journalctl`
**Syntax:** `journalctl`  
**What it does:** Displays the systemd journal (system logs).  
**When I use it:** Viewing system and service logs.

### 5. `journalctl -f`
**Syntax:** `journalctl -f`  
**What it does:** Follows the journal live (real-time).  
**When I use it:** Monitoring logs as they are written.

### 6. `journalctl -u`
**Syntax:** `journalctl -u service-name`  
**What it does:** Shows logs for one specific service.  
**When I use it:** Troubleshooting a particular service.

### 7. `journalctl --since`
**Syntax:** `journalctl --since today`  
**What it does:** Shows logs since a given time.  
**When I use it:** Limiting logs to a specific period.

### 8. `journalctl -p err`
**Syntax:** `journalctl -p err`  
**What it does:** Shows only error-level messages and above.  
**When I use it:** Focusing on important problems.

### 9. `tail -f /var/log/syslog`
**Syntax:** `sudo tail -f /var/log/syslog`  
**What it does:** Follows the traditional system log live.  
**When I use it:** Monitoring classic system messages.

### 10. `tail -f /var/log/auth.log`
**Syntax:** `sudo tail -f /var/log/auth.log`  
**What it does:** Follows the authentication log live.  
**When I use it:** Watching login attempts and sudo usage.