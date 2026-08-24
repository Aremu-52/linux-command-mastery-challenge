# Day 11 Practice Drill

## Task
Create a new user with a home directory and Bash shell, set their password, add them to a secondary group, rename the account, then remove it along with its home directory.

## Commands I ran

```bash
sudo useradd -m -s /bin/bash testuser
id testuser
sudo ls /home/testuser
sudo adduser testuser2
sudo passwd testuser
sudo groupadd developers
sudo usermod -aG developers testuser
groups testuser
sudo usermod -s /bin/sh testuser
sudo usermod -l newtestuser testuser
id newtestuser
sudo userdel -r newtestuser
sudo userdel -r testuser2

Result

Successfully created users with home directories.
Set password and added user to a secondary group.
Renamed the account and then completely removed the users with their home directories.

What I learned
Creating users properly with useradd -m -s and managing them with usermod and userdel -r is essential for system administration.
text