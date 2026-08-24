# Day 10 Practice Drill – Security Checkpoint

## Task
Produce a one-page mini security audit of a server: who has logged in recently, who is logged in right now, which accounts have never logged in, and every sudo command run in this session.

## Commands I ran

```bash
find / -perm /4000 2>/dev/null | head -20
last
lastlog
w
who
groups
passwd -S $USER
chage -l $USER
sudo lastb | head -10
history | grep sudo

Result

Checked recent and current logins.
Identified accounts that have never logged in.
Reviewed password aging information.
Listed SUID files and all sudo commands used in the session.

What I learned
A useful security overview of a Linux system can be produced quickly with a small set of simple commands.