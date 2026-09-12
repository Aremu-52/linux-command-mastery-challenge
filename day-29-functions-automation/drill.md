# Day 29 Practice Drill

## Task
Turn yesterday’s script into a reusable function that accepts a service name as an argument, checks its status, restarts it if stopped, and schedule it to run hourly with cron.

## Commands I ran

```bash
nano day29.sh
chmod +x day29.sh
./day29.sh cron
./day29.sh ssh
crontab -e
crontab -l
nohup ./day29.sh cron &
logger "Day 29 practice completed"

Result

Created a reusable function that accepts a service name.
Checked service status and restarted it when needed.
Scheduled the script to run hourly with cron.
Used nohup, trap, and logger.

What I learned
Functions + arguments + cron turn a simple script into real automation.