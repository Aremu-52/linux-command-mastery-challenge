# Day 14 Practice Drill

## Task
On an Amazon Linux or RHEL box, install a package with dnf, confirm it with rpm -qa, then compare the workflow against the equivalent apt steps from Day 13.

## Commands I ran

```bash
sudo dnf update
sudo dnf install tree
sudo dnf remove tree
dnf search tree
sudo yum install tree
rpm -qa | head -10
sudo snap install hello-world
hello-world
sudo add-apt-repository ppa:deadsnakes/ppa -y
sudo apt update
wget http://archive.ubuntu.com/ubuntu/pool/main/h/hello/hello_2.10-3build1_amd64.deb
sudo dpkg -i hello_2.10-3build1_amd64.deb
hello
pip3 install requests --break-system-packages
sudo npm install -g cowsay
cowsay "Day 14 completed"

Result

Practiced DNF/YUM/RPM commands (expected limited success on Ubuntu).
Successfully used Snap, dpkg, pip, and npm.
Compared alternative installation methods with the APT workflow from Day 13.

What I learned
Different Linux distributions use different package managers. Knowing alternatives like Snap, dpkg, pip, and npm is useful when working across multiple systems.