# Day 13 Commands – APT Package Management

### 1. `apt update`
**Syntax:** `sudo apt update`  
**What it does:** Refreshes the local list of available packages from the repositories.  
**When I use it:** Before installing or upgrading any software.

### 2. `apt upgrade`
**Syntax:** `sudo apt upgrade`  
**What it does:** Upgrades all installed packages to their newer versions.  
**When I use it:** To keep the system up to date.

### 3. `apt full-upgrade`
**Syntax:** `sudo apt full-upgrade`  
**What it does:** Performs a full upgrade and may remove obsolete packages if needed.  
**When I use it:** When a normal upgrade is not enough.

### 4. `apt install`
**Syntax:** `sudo apt install package-name`  
**What it does:** Installs a new package.  
**When I use it:** When I need to add new software to the system.

### 5. `apt remove`
**Syntax:** `sudo apt remove package-name`  
**What it does:** Removes a package but keeps its configuration files.  
**When I use it:** When I want to remove a program but keep its settings.

### 6. `apt purge`
**Syntax:** `sudo apt purge package-name`  
**What it does:** Removes a package and its configuration files completely.  
**When I use it:** When I want to completely clean a package from the system.

### 7. `apt autoremove`
**Syntax:** `sudo apt autoremove`  
**What it does:** Removes packages that were installed as dependencies but are no longer needed.  
**When I use it:** After removing software to clean up leftover packages.

### 8. `apt search`
**Syntax:** `apt search keyword`  
**What it does:** Searches for packages by name or description.  
**When I use it:** When I want to find a package.

### 9. `apt show`
**Syntax:** `apt show package-name`  
**What it does:** Shows detailed information about a package.  
**When I use it:** Before installing a package, to understand what it does.

### 10. `dpkg -l` / `dpkg -L`
**Syntax:** `dpkg -l` or `dpkg -L package-name`  
**What it does:** Lists installed packages / shows all files installed by a specific package.  
**When I use it:** To check installed software or see the files a package owns.