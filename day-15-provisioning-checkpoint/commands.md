# Day 15 Commands – Users & Packages Checkpoint

### 1. `id <user>`
**Syntax:** `id username`  
**What it does:** Shows the user ID, group ID, and all groups the user belongs to.  
**When I use it:** To verify a user’s identity and group memberships.

### 2. `getent passwd <user>`
**Syntax:** `getent passwd username`  
**What it does:** Displays the full account details of a user.  
**When I use it:** To check home directory, shell, and other account information.

### 3. `useradd -m -G`
**Syntax:** `sudo useradd -m -G groupname -s /bin/bash username`  
**What it does:** Creates a new user with a home directory and adds them to specified groups.  
**When I use it:** When provisioning a new team member.

### 4. `passwd <user>`
**Syntax:** `sudo passwd username`  
**What it does:** Sets or changes a user’s password.  
**When I use it:** After creating a new account.

### 5. `apt list --installed`
**Syntax:** `apt list --installed`  
**What it does:** Lists all packages currently installed on the system.  
**When I use it:** To see what software is present.

### 6. `apt list --upgradable`
**Syntax:** `apt list --upgradable`  
**What it does:** Shows packages that have available updates.  
**When I use it:** To check what can be upgraded.

### 7. `apt update && apt install -y`
**Syntax:** `sudo apt update && sudo apt install -y package1 package2`  
**What it does:** Updates the package list and installs packages without asking for confirmation.  
**When I use it:** When installing software quickly or in scripts.

### 8. `dpkg -l | grep`
**Syntax:** `dpkg -l | grep package-name`  
**What it does:** Searches the list of installed packages.  
**When I use it:** To confirm whether a specific package is installed.

### 9. `apt autoremove`
**Syntax:** `sudo apt autoremove`  
**What it does:** Removes packages that are no longer needed.  
**When I use it:** Cleaning up after installing or removing software.

### 10. `history`
**Syntax:** `history`  
**What it does:** Shows the list of commands run in the current session.  
**When I use it:** Reviewing work done for documentation or troubleshooting.