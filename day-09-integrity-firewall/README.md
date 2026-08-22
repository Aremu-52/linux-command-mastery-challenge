# Day 09: Integrity, Encryption & Firewalling

**Phase 2 – Permissions, Ownership & Security | Day 9 of 30**

## Commands covered today
See [commands.md](./commands.md) for all 10 commands with syntax and my own explanation of what each one does and when I would reach for it.

## What I practiced
I generated MD5 and SHA-256 checksums to verify file integrity, created a GPG key and practiced encrypting/decrypting a file, made a file immutable with `chattr +i`, and configured the firewall to allow only ports 22 and 443.

## What surprised me
I was surprised that after setting the immutable attribute with `chattr +i`, even the root user cannot delete or modify the file until the attribute is removed.

## Evidence
Screenshots of the practice drill are stored in the [evidence](./evidence/) folder.

## Related
- Previous day: [day-08-privilege-escalation](../day-08-privilege-escalation/)
- Next day: [day-10-security-audit-checkpoint](../day-10-security-audit-checkpoint/)