# Day 12 Commands – Groups & Access Circles

### 1. `groupadd`
**Syntax:** `sudo groupadd groupname`  
**What it does:** Creates a new group on the system.  
**When I use it:** When I need a new group for shared access or permissions.

### 2. `groupdel`
**Syntax:** `sudo groupdel groupname`  
**What it does:** Deletes a group from the system.  
**When I use it:** When a group is no longer needed.

### 3. `gpasswd -a`
**Syntax:** `sudo gpasswd -a username groupname`  
**What it does:** Adds a user to a group.  
**When I use it:** When giving a user membership in a group.

### 4. `gpasswd -d`
**Syntax:** `sudo gpasswd -d username groupname`  
**What it does:** Removes a user from a group.  
**When I use it:** When a user no longer needs access to a group.

### 5. `getent group`
**Syntax:** `getent group groupname`  
**What it does:** Displays information about a group, including its members.  
**When I use it:** To confirm group membership.

### 6. `getent passwd`
**Syntax:** `getent passwd username`  
**What it does:** Displays information about a user account.  
**When I use it:** To check details of a user.

### 7. `groups`
**Syntax:** `groups username`  
**What it does:** Shows the groups a user belongs to.  
**When I use it:** Quick check of a user’s group memberships.

### 8. `id -Gn`
**Syntax:** `id -Gn username`  
**What it does:** Shows only the group names of a user.  
**When I use it:** When I only need the list of group names.

### 9. `newgrp`
**Syntax:** `newgrp groupname`  
**What it does:** Temporarily switches the current group for the session.  
**When I use it:** When I need to work under a different group temporarily.

### 10. `cat /etc/group`
**Syntax:** `cat /etc/group`  
**What it does:** Displays the full list of groups on the system.  
**When I use it:** To view all groups and their members.