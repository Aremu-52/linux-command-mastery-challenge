# Day 21 Practice Drill

## Task
Find the PID of a running process by name, view it in top, show it as part of the process tree, and identify which process is using port 80.

## Commands I ran

```bash
ps aux
ps -ef
ps -u $USER
top
htop
pgrep bash
pstree
sudo lsof -i
sudo lsof -i :80
sudo lsof -i :22
jobs
nice -n 10 sleep 60 &
renice -n 5 $(pgrep -n sleep)

Result

Successfully listed and monitored running processes.
Found PIDs by name using pgrep.
Viewed the process tree.
Checked which processes were using network ports.

What I learned
Commands like ps, pgrep, pstree, and lsof give a clear picture of what is running on a Linux system and which resources they are using.
text