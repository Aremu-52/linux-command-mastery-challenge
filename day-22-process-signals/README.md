# Day 22: Controlling Processes with Signals

**Phase 5 – Process & Service Management | Day 22 of 30**

## Commands covered today
See [commands.md](./commands.md) for all 10 commands with syntax and my own explanation of what each one does and when I would reach for it.

## What I practiced
I started a long-running process in the background, suspended it with Ctrl+Z, resumed it with `bg` and `fg`, killed processes using `kill`, `kill -9`, `killall` and `pkill`, and used `nohup` and `disown` so a process can continue running after logout.

## What surprised me
I was surprised that `nohup` allows a process to keep running even after I close the terminal or log out.

## Evidence
Screenshots of the practice drill are stored in the [evidence](./evidence/) folder.

## Related
- Previous day: [day-21-viewing-processes](../day-21-viewing-processes/)
- Next day: [day-23-systemctl](../day-23-systemctl/)