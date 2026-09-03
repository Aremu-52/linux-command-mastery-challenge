# Day 22 Practice Drill

## Task
Start a long-running command in the background, suspend it, resume it in the background, then start a second one that survives you logging out, using nohup.

## Commands I ran

```bash
sleep 300 &
jobs
sleep 200
# Press Ctrl + Z
jobs
bg
fg
# Press Ctrl + Z again if needed
bg
kill %1
sleep 100 &
kill -9 %1
sleep 50 &
sleep 50 &
killall sleep
# or
pkill sleep
nohup sleep 600 > nohup.out 2>&1 &
sleep 300 &
disown
jobs

Result

Started processes in the background.
Suspended a process with Ctrl+Z and resumed it with bg and fg.
Killed processes using kill, kill -9, killall and pkill.
Used nohup and disown so processes can continue after logout.

What I learned
nohup and disown are very useful when you need a process to keep running even after you close the terminal.