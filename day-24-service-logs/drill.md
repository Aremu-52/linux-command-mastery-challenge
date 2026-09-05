# Day 24 Practice Drill

## Task
List every failed service on the box, then pull today's logs for one specific service, filtered to errors only, and follow it live for one minute.

## Commands I ran

```bash
systemctl list-units --type=service
systemctl list-units --state=failed
sudo systemctl daemon-reload
journalctl -n 20
journalctl -f
journalctl -u ssh
journalctl -u cron
journalctl --since today
journalctl -p err
journalctl -u ssh --since today -p err
sudo tail -f /var/log/syslog
sudo tail -f /var/log/auth.log

Result

Listed all services and checked for failed ones.
Viewed and filtered logs using journalctl.
Followed live logs with both journalctl and tail -f.

What I learned
journalctl combined with filters (-u, --since, -p) is a very effective way to troubleshoot services.
text