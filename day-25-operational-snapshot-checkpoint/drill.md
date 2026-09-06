# Day 25 Practice Drill – Process & Service Checkpoint

## Task
Build a one-screen operational snapshot of a server covering uptime, memory, the status of three key services, and any scheduled cron jobs.

## Commands I ran

```bash
ps aux | grep ssh
ps aux | grep cron
systemctl status ssh
systemctl status cron
systemctl status rsyslog
journalctl -u ssh --since today
journalctl -u cron --since today
pgrep bash
kill -0 $(pgrep -n bash)
uptime
free -h
vmstat 1 5
iostat
watch -n 2 free -h
crontab -e

Result

Created a clear operational snapshot of the server.
Checked uptime, memory, key services, logs, and cron jobs.

What I learned
A few well-chosen commands can give a complete picture of a server’s health in less than a minute.