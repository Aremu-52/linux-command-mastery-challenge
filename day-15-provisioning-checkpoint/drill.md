# Day 15 Practice Drill – Users & Packages Checkpoint

## Task
Provision a complete new team member account (user, groups, password) and install the three tools they need for their role, in a single documented sequence.

## Commands I ran

```bash
sudo groupadd developers
sudo useradd -m -G developers -s /bin/bash newmember
id newmember
getent passwd newmember
sudo passwd newmember
apt list --installed | head -20
apt list --upgradable
sudo apt update && sudo apt install -y tree curl git
dpkg -l | grep -E "tree|curl|git"
sudo apt autoremove
history

Result

Successfully created a new user with home directory and group membership.
Set a password for the new account.
Installed the required tools (tree, curl, git).
Verified the packages and cleaned up unused dependencies.

What I learned
Provisioning a new team member and installing their required tools can be done cleanly in a short sequence of commands. This is a practical skill for real system administration work.
text