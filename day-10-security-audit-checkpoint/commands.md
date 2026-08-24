# Day 10 Commands – Security Checkpoint & Audit

### 1. `find / -perm /4000`
**Syntax:** `find / -perm /4000 2>/dev/null`  
**What it does:** Finds all files with the SUID bit set.  
**When I use it:** During security audits to locate programs that can run with elevated privileges.

### 2. `last`
**Syntax:** `last`  
**What it does:** Shows the recent login history of users.  
**When I use it:** To see who has logged into the system recently.

### 3. `lastlog`
**Syntax:** `lastlog`  
**What it does:** Shows the last login time of every user account.  
**When I use it:** To find accounts that have never logged in.

### 4. `w`
**Syntax:** `w`  
**What it does:** Shows who is logged in right now and what they are doing.  
**When I use it:** To see current activity on the system.

### 5. `who`
**Syntax:** `who`  
**What it does:** Shows who is currently logged in.  
**When I use it:** Quick check of active users.

### 6. `groups`
**Syntax:** `groups`  
**What it does:** Shows the groups the current user belongs to.  
**When I use it:** To check group membership.

### 7. `passwd`
**Syntax:** `passwd`  
**What it does:** Changes a user’s password.  
**When I use it:** When a password needs to be updated.

### 8. `chage -l`
**Syntax:** `chage -l username`  
**What it does:** Shows password aging information for a user.  
**When I use it:** To check when a password was last changed and when it will expire.

### 9. `lastb`
**Syntax:** `sudo lastb`  
**What it does:** Shows failed login attempts.  
**When I use it:** To detect possible unauthorized access attempts.

### 10. `history | grep sudo`
**Syntax:** `history | grep sudo`  
**What it does:** Shows all sudo commands used in the current session.  
**When I use it:** To review privileged commands that were run.