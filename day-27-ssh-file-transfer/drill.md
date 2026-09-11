# Day 27 Practice Drill

## Task
Generate an SSH key pair, copy the public key to a remote host, connect without a password, then securely copy a file to and from that server.

## Commands I ran

```bash
ssh-keygen -t ed25519
ssh-copy-id -i ~/.ssh/id_ed25519.pub localhost
ssh localhost
ssh -p 22 localhost
ssh -i ~/.ssh/id_ed25519 localhost
echo "Day 27 test" > file.txt
scp file.txt localhost:~/
scp localhost:~/file.txt ./file-back.txt
sftp localhost
rsync -avz file.txt localhost:~/
nano ~/.ssh/config
sudo nano /etc/ssh/sshd_config

Result

Generated SSH keys and set up password-less login to localhost.
Practiced different SSH connection options.
Transferred files using scp, sftp, and rsync.
Viewed SSH client and server configuration files.

What I learned
SSH keys + ssh-copy-id make remote access much more convenient and secure. scp, sftp, and rsync are the main tools for secure file transfer.