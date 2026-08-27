# Day 13: APT Package Management (Debian/Ubuntu)

**Phase 3 – Users, Groups & Package Management | Day 13 of 30**

## Commands covered today
See [commands.md](./commands.md) for all 10 commands with syntax and my own explanation of what each one does and when I would reach for it.

## What I practiced
I refreshed the package index, searched for a package, inspected its details, installed it, listed its files with dpkg, then removed and purged it completely along with unused dependencies.

## What surprised me
I was surprised how cleanly `apt purge` removes both the package and its configuration files, and how useful `dpkg -L` is for seeing exactly which files a package installed.

## Evidence
Screenshots of the practice drill are stored in the [evidence](./evidence/) folder.

## Related
- Previous day: [day-12-groups](../day-12-groups/)
- Next day: [day-14-dnf-yum](../day-14-dnf-yum/)