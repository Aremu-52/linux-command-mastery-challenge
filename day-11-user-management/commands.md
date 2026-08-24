# Day 11 Commands – Creating & Managing Users

### 1. `useradd`
**Syntax:** `sudo useradd username`  
**What it does:** Creates a new user account (basic method).  
**When I use it:** Quick user creation when I don’t need extra options.

### 2. `useradd -m`
**Syntax:** `sudo useradd -m username`  
**What it does:** Creates a new user and also creates a home directory.  
**When I use it:** When the user needs a home directory.

### 3. `useradd -m -s`
**Syntax:** `sudo useradd -m -s /bin/bash username`  
**What it does:** Creates a user with home directory and sets the login shell.  
**When I use it:** This is the recommended way to create a normal user.

### 4. `adduser`
**Syntax:** `sudo adduser username`  
**What it does:** Interactive and user-friendly way to create a user (common on Ubuntu/Debian).  
**When I use it:** When I prefer a guided process.

### 5. `passwd`
**Syntax:** `sudo passwd username`  
**What it does:** Sets or changes a user’s password.  
**When I use it:** After creating a new user or when a password needs to be updated.

### 6. `usermod -aG`
**Syntax:** `sudo usermod -aG groupname username`  
**What it does:** Adds a user to a secondary group without removing existing groups.  
**When I use it:** When giving a user extra group membership (e.g. developers, sudo).

### 7. `usermod -s`
**Syntax:** `sudo usermod -s /bin/bash username`  
**What it does:** Changes the login shell of a user.  
**When I use it:** When a user needs a different shell.

### 8. `usermod -l`
**Syntax:** `sudo usermod -l newname oldname`  
**What it does:** Renames a user account.  
**When I use it:** When an account name needs to be changed.

### 9. `userdel`
**Syntax:** `sudo userdel username`  
**What it does:** Deletes a user account (home directory is left behind).  
**When I use it:** When removing a user but keeping their files.

### 10. `userdel -r`
**Syntax:** `sudo userdel -r username`  
**What it does:** Deletes a user account and their home directory.  
**When I use it:** When completely removing a user and all their data.