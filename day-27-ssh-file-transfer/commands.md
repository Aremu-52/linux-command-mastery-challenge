# Day 27 Commands – Remote Access & File Transfer

### 1. `ssh`
**Syntax:** `ssh user@host`  
**What it does:** Connects securely to a remote machine.  
**When I use it:** Logging into remote servers.

### 2. `ssh -p`
**Syntax:** `ssh -p port user@host`  
**What it does:** Connects using a custom SSH port.  
**When I use it:** When the server is not using the default port 22.

### 3. `ssh -i`
**Syntax:** `ssh -i /path/to/key user@host`  
**What it does:** Connects using a specific private key.  
**When I use it:** When I have multiple SSH keys.

### 4. `ssh-keygen`
**Syntax:** `ssh-keygen -t ed25519`  
**What it does:** Generates a new SSH key pair.  
**When I use it:** Creating keys for password-less authentication.

### 5. `ssh-copy-id`
**Syntax:** `ssh-copy-id -i key.pub user@host`  
**What it does:** Copies the public key to a remote server.  
**When I use it:** Setting up password-less SSH login.

### 6. `scp`
**Syntax:** `scp file user@host:/path/`  
**What it does:** Securely copies files over SSH.  
**When I use it:** Transferring individual files to/from a server.

### 7. `sftp`
**Syntax:** `sftp user@host`  
**What it does:** Starts an interactive secure file transfer session.  
**When I use it:** When I need to browse and transfer multiple files interactively.

### 8. `rsync`
**Syntax:** `rsync -avz file user@host:/path/`  
**What it does:** Efficiently synchronizes files and directories.  
**When I use it:** Backups and deployments (only transfers differences).

### 9. `~/.ssh/config`
**Syntax:** Edit `~/.ssh/config`  
**What it does:** Stores SSH connection shortcuts and options.  
**When I use it:** Simplifying frequent SSH connections.

### 10. `sshd_config` hardening
**Syntax:** `sudo nano /etc/ssh/sshd_config`  
**What it does:** Configures the SSH server for better security.  
**When I use it:** Hardening the SSH service (disable root login, change port, etc.).