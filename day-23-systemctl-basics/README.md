# Day 23: Init Systems & systemctl Basics

**Phase 5 – Process & Service Management | Day 23 of 30**

## Commands covered today
See [commands.md](./commands.md) for all 10 commands with syntax and my own explanation of what each one does and when I would reach for it.

## What I practiced
I stopped a service, confirmed it was inactive, restarted it, enabled it to start at boot using `systemctl enable --now`, and verified both its active and enabled state.

## What surprised me
I was surprised how convenient `systemctl enable --now` is — it enables the service for boot and starts it immediately in a single command.

## Evidence
Screenshots of the practice drill are stored in the [evidence](./evidence/) folder.

## Related
- Previous day: [day-22-process-signals](../day-22-process-signals/)
- Next day: [day-24-service-logs](../day-24-service-logs/)