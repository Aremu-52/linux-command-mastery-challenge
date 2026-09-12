# Day 28 Practice Drill

## Task
Write and execute a script that reads the user's name, checks whether a config file exists using an if statement, and loops through three server names pinging each one.

## Commands I ran

```bash
nano day28.sh
chmod +x day28.sh
./day28.sh

#!/bin/bash

COURSE="Linux Command Mastery"
read -p "Enter your name: " NAME
echo "Hello $NAME, welcome to $COURSE"

TODAY=$(date)
echo "Today is: $TODAY"

if [ -f /etc/passwd ]; then
    echo "Config file /etc/passwd exists"
else
    echo "Config file does not exist"
fi

echo "Pinging servers..."
for server in 8.8.8.8 1.1.1.1 google.com
do
    echo "Pinging $server"
    ping -c 1 $server
done

count=1
while [ $count -le 3 ]
do
    echo "While loop count: $count"
    count=$((count + 1))
done

echo "Script finished"

Result

Successfully created and executed a Bash script.
Read user input, checked for a file, and pinged three servers in a loop.

What I learned
Bash scripting allows me to combine many commands into one reusable tool.
text