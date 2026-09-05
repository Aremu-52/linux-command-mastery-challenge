# Day 24: Deeper Service Management & Logs

**Phase 5 – Process & Service Management | Day 24 of 30**

## Commands covered today
See [commands.md](./commands.md) for all 10 commands with syntax and my own explanation of what each one does and when I would reach for it.

## What I practiced
I listed all services and failed services, reloaded systemd, viewed and followed system logs with journalctl, filtered logs by service and priority, and followed traditional log files with tail -f.

## What surprised me
I was surprised how powerful `journalctl` is. Being able to filter by service, time, and priority makes troubleshooting much faster than reading raw log files.

## Evidence
Screenshots of the practice drill are stored in the [evidence](./evidence/) folder.

## Related
- Previous day: [day-23-systemctl-basics](../day-23-systemctl-basics/)
- Next day: [day-25-operational-snapshot-checkpoint](../day-25-operational-snapshot-checkpoint/)