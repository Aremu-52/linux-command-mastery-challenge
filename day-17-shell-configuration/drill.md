# Day 17 Practice Drill

## Task
Add a permanent environment variable and a custom alias to your `.bashrc`, reload it without opening a new terminal, and confirm both persist in a fresh session.

## Commands I ran

```bash
nano ~/.bashrc
source ~/.bashrc
echo $MYCOURSE
ll
cat ~/.bash_profile
cat ~/.profile
sudo nano /etc/environment
sudo nano /etc/bash.bashrc
alias
unalias ll
source ~/.bashrc
type ll
type ls
type cd
which ls
which nano
whereis ls
whereis bash

Result

Successfully added a permanent environment variable and alias to .bashrc.
Reloaded the configuration with source.
Confirmed the changes worked.
Noted that .bash_profile does not exist on this Ubuntu system (normal behavior).

What I learned
Persistent configuration is done mainly through .bashrc on Ubuntu. Using source is the fastest way to apply changes immediately.
text