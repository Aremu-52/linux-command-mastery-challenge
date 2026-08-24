# Day 10: Security Checkpoint & Audit

**Phase 2 – Permissions, Ownership & Security | Day 10 of 30**

## Commands covered today
See [commands.md](./commands.md) for all 10 commands with syntax and my own explanation of what each one does and when I would reach for it.

## What I practiced
I performed a mini security audit of the system. I checked recent logins, current logged-in users, accounts that have never logged in, password aging information, failed login attempts, SUID files, and every sudo command used in the session.

## What surprised me
I was surprised how much useful security information can be gathered with simple commands like `last`, `lastlog`, `w`, and `history | grep sudo`.

## Evidence
Screenshots of the security audit are stored in the [evidence](./evidence/) folder.

## Related
- Previous day: [day-09-integrity-firewall](../day-09-integrity-firewall/)
- Next day: [day-11-user-management](../day-11-user-management/)