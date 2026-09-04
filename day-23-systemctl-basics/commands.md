# Day 23 Commands – Init Systems & systemctl Basics

### 1. `systemctl start`
**Syntax:** `sudo systemctl start service-name`  
**What it does:** Starts a service immediately.  
**When I use it:** To start a stopped service.

### 2. `systemctl stop`
**Syntax:** `sudo systemctl stop service-name`  
**What it does:** Stops a running service.  
**When I use it:** To stop a service temporarily.

### 3. `systemctl restart`
**Syntax:** `sudo systemctl restart service-name`  
**What it does:** Stops and then starts a service.  
**When I use it:** After changing configuration or when a service needs a full restart.

### 4. `systemctl reload`
**Syntax:** `sudo systemctl reload service-name`  
**What it does:** Reloads the service configuration without a full restart (if supported).  
**When I use it:** To apply configuration changes with minimal disruption.

### 5. `systemctl enable`
**Syntax:** `sudo systemctl enable service-name`  
**What it does:** Configures the service to start automatically at boot.  
**When I use it:** When I want a service to start every time the system boots.

### 6. `systemctl disable`
**Syntax:** `sudo systemctl disable service-name`  
**What it does:** Prevents the service from starting automatically at boot.  
**When I use it:** When I no longer want a service to auto-start.

### 7. `systemctl enable --now`
**Syntax:** `sudo systemctl enable --now service-name`  
**What it does:** Enables the service at boot and starts it immediately.  
**When I use it:** The fastest way to both enable and start a service.

### 8. `systemctl status`
**Syntax:** `systemctl status service-name`  
**What it does:** Shows detailed status of a service.  
**When I use it:** To check whether a service is running and see recent logs.

### 9. `systemctl is-active`
**Syntax:** `systemctl is-active service-name`  
**What it does:** Returns “active” or “inactive”.  
**When I use it:** Quick check if a service is currently running.

### 10. `systemctl is-enabled`
**Syntax:** `systemctl is-enabled service-name`  
**What it does:** Returns “enabled” or “disabled”.  
**When I use it:** To check if a service is set to start at boot.