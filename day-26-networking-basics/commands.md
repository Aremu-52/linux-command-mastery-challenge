# Day 26 Commands – Networking Basics

### 1. `ip a`
**Syntax:** `ip a`  
**What it does:** Shows all network interfaces and their IP addresses.  
**When I use it:** To find the IP address of the machine.

### 2. `ip route`
**Syntax:** `ip route`  
**What it does:** Displays the routing table, including the default gateway.  
**When I use it:** To see how traffic is routed and find the gateway.

### 3. `ping -c`
**Syntax:** `ping -c 4 host`  
**What it does:** Sends a limited number of ICMP packets to test connectivity.  
**When I use it:** Quick check if a host is reachable.

### 4. `curl`
**Syntax:** `curl URL`  
**What it does:** Fetches the content of a URL.  
**When I use it:** Downloading or testing web content from the terminal.

### 5. `curl -I`
**Syntax:** `curl -I URL`  
**What it does:** Fetches only the HTTP headers of a URL.  
**When I use it:** Checking response headers without downloading the body.

### 6. `wget`
**Syntax:** `wget URL`  
**What it does:** Downloads a file from a URL.  
**When I use it:** Downloading files non-interactively.

### 7. `netstat -tulnp`
**Syntax:** `sudo netstat -tulnp`  
**What it does:** Lists listening TCP/UDP ports and the processes using them.  
**When I use it:** Older way to see open ports.

### 8. `ss -tulnp`
**Syntax:** `sudo ss -tulnp`  
**What it does:** Modern tool to list listening ports and processes.  
**When I use it:** Preferred way to check open ports on modern systems.

### 9. `hostname`
**Syntax:** `hostname`  
**What it does:** Shows the current hostname of the system.  
**When I use it:** Quickly checking the machine’s name.

### 10. `hostnamectl`
**Syntax:** `hostnamectl`  
**What it does:** Shows detailed hostname and system information.  
**When I use it:** Viewing or changing the system hostname and related settings.