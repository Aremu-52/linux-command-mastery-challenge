# Day 9 Practice Drill

## Task
Generate a SHA-256 checksum for a downloaded file to verify its integrity, make a file immutable with chattr, then open only port 22 and port 443 on the firewall.

## Commands I ran

```bash
echo "This is a test file for Day 9" > testfile.txt
md5sum testfile.txt
sha256sum testfile.txt
sha256sum testfile.txt > testfile.sha256
sha256sum -c testfile.sha256

gpg --gen-key
gpg --encrypt --recipient your-email@example.com testfile.txt
gpg --decrypt testfile.txt.gpg

sudo chattr +i testfile.txt
lsattr testfile.txt
sudo chattr -i testfile.txt

sudo ufw enable
sudo ufw allow 22
sudo ufw allow 443
sudo ufw status

Result

Successfully generated and verified SHA-256 checksum.
Made a file immutable with chattr +i and confirmed with lsattr.
Enabled the firewall and allowed only ports 22 and 443.

What I learned
SHA-256 is a reliable way to verify file integrity. The immutable attribute is a strong protection, and UFW makes firewall management simple.
text