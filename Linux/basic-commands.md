Linux Basic Commands – Practical Lab
1. Navigation commands
Command	Purpose
pwd	Displays current directory
ls	Lists files and directories
ls -la	Lists all files, including hidden files
cd /home	Moves to home directory path
cd ..	Moves one directory backward
clear	Clears terminal

2. File and directory management
Command	Purpose
mkdir test	Creates a directory
touch file.txt	Creates an empty file
cat file.txt	Displays file contents
nano file.txt	Opens file in Nano editor
cp file.txt backup.txt	Copies a file
mv file.txt new.txt	Renames or moves a file
rm file.txt	Deletes a file
rmdir test	Deletes an empty directory

3. User and permission commands
Command	Purpose
whoami	Displays current username
id	Displays user and group IDs
sudo	Executes a command with elevated privileges
chmod 755 file.sh	Changes file permissions
chown user:user file.txt	Changes file ownership
passwd	Changes user password

4. Networking commands
Command	Purpose
ip addr	Displays IP addresses
ip route	Displays routing table
ping 8.8.8.8	Tests network connectivity
ss -tuln	Displays listening TCP/UDP sockets
nslookup google.com	Queries DNS
hostname	Displays system hostname

5. System information commands
Command	Purpose
uname -a	Displays system information
uptime	Shows system running time
free -h	Displays memory usage
df -h	Displays disk space
top	Displays running processes
ps aux	Lists running processes
history	Displays command history

6. Package management (Kali Linux)
Command	Purpose
sudo apt update	Updates package lists
sudo apt upgrade	Upgrades installed packages
sudo apt install nmap	Installs Nmap
sudo apt remove nmap	Removes Nmap
