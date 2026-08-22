# Day 9 Commands – Integrity, Encryption & Firewalling

### 1. `md5sum`
**Syntax:** `md5sum filename`  
**What it does:** Generates an MD5 checksum (fingerprint) of a file.  
**When I use it:** Quick integrity check of a file.

### 2. `sha256sum`
**Syntax:** `sha256sum filename`  
**What it does:** Generates a stronger SHA-256 checksum of a file.  
**When I use it:** Verifying that a downloaded file has not been corrupted or changed.

### 3. `gpg --gen-key`
**Syntax:** `gpg --gen-key`  
**What it does:** Creates a new GPG public and private key pair.  
**When I use it:** When I want to start encrypting and signing files.

### 4. `gpg --encrypt`
**Syntax:** `gpg --encrypt --recipient email file`  
**What it does:** Encrypts a file so only the owner of the private key can read it.  
**When I use it:** Protecting sensitive files.

### 5. `gpg --decrypt`
**Syntax:** `gpg --decrypt file.gpg`  
**What it does:** Decrypts a GPG-encrypted file.  
**When I use it:** Reading a file that was encrypted for me.

### 6. `chattr +i`
**Syntax:** `sudo chattr +i filename`  
**What it does:** Makes a file immutable (cannot be modified, deleted, or renamed).  
**When I use it:** Protecting important configuration or system files.

### 7. `lsattr`
**Syntax:** `lsattr filename`  
**What it does:** Shows special attributes of a file (including the immutable flag).  
**When I use it:** Checking whether a file is immutable.

### 8. `ufw enable`
**Syntax:** `sudo ufw enable`  
**What it does:** Turns on the Uncomplicated Firewall.  
**When I use it:** Activating basic firewall protection.

### 9. `ufw allow`
**Syntax:** `sudo ufw allow 22`  
**What it does:** Allows traffic on a specific port.  
**When I use it:** Opening only the ports I need (SSH, HTTPS, etc.).

### 10. `ufw status`
**Syntax:** `sudo ufw status`  
**What it does:** Shows the current firewall status and rules.  
**When I use it:** Verifying which ports are open.