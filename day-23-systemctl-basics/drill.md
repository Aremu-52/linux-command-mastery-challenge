# Day 23 Practice Drill

## Task
Pick a service, stop it, confirm it is inactive, restart it, enable it to auto-start at boot in a single combined command, and confirm both its active and enabled state.

## Commands I ran

```bash
systemctl status cron
sudo systemctl stop cron
systemctl is-active cron
sudo systemctl start cron
sudo systemctl restart cron
sudo systemctl reload cron
sudo systemctl disable cron
sudo systemctl enable --now cron
systemctl status cron
systemctl is-active cron
systemctl is-enabled cron

Result

Successfully stopped and restarted a service.
Used systemctl enable --now to enable and start in one step.
Confirmed the service was both active and enabled.

What I learned
systemctl is the modern and standard way to manage services on most Linux systems. The combination of enable --now, is-active, and is-enabled makes service management clear and efficient.