# Day 26 Practice Drill

## Task
Identify my machine's IP address and default gateway, test connectivity to a public host, fetch a URL's headers only, and list every port currently listening.

## Commands I ran

```bash
ip a
ip route
ping -c 4 8.8.8.8
ping -c 4 google.com
curl https://google.com
curl -I https://google.com
wget https://portal.com -O example.html
sudo netstat -tulnp
sudo ss -tulnp
hostname
hostnamectl