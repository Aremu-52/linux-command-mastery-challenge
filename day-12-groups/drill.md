# Day 12 Practice Drill

## Task
Create a group named `devs`, add two users to it, confirm membership with `getent`, remove one member, then delete the group entirely.

## Commands I ran

```bash
sudo groupadd devs
sudo useradd -m -s /bin/bash user1
sudo useradd -m -s /bin/bash user2
sudo gpasswd -a user1 devs
sudo gpasswd -a user2 devs
getent group devs
groups user1
groups user2
id -Gn user1
getent passwd user1
cat /etc/group | grep devs
sudo gpasswd -d user2 devs
getent group devs
sudo groupdel devs
sudo userdel -r user1
sudo userdel -r user2