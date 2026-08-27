# Day 13 Practice Drill

## Task
Refresh the package index, search for and install a small utility, inspect its package details, then purge it completely along with its configuration files.

## Commands I ran

```bash
sudo apt update
sudo apt upgrade
sudo apt full-upgrade
apt search tree
apt show tree
sudo apt install tree
dpkg -l | grep tree
dpkg -L tree
sudo apt remove tree
sudo apt purge tree
sudo apt autoremove