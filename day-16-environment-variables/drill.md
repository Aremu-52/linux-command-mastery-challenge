# Day 16 Practice Drill

## Task
Set a temporary environment variable, confirm it exists, unset it, then add a directory to your PATH for the current session only and prove the shell can now find a script inside it.

## Commands I ran

```bash
printenv
printenv HOME
echo $HOME
export MYNAME="Tijani"
echo $MYNAME
unset MYNAME
env | head -20
echo 'export COURSE="Linux Mastery"' > myvars.sh
source myvars.sh
echo $COURSE
echo $PATH
mkdir -p ~/mybin
echo 'echo Hello from my script' > ~/mybin/hello.sh
chmod +x ~/mybin/hello.sh
export PATH=$PATH:~/mybin
hello.sh
cat /etc/environment

Result

Successfully created and removed a temporary environment variable.
Added a custom directory to the PATH.
Confirmed the shell could find and run a script from that directory.

What I learned
Environment variables and the PATH are powerful. Being able to temporarily extend the PATH is very useful when working with personal scripts.
text