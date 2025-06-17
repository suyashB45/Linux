# 📘 Linux Commands Cheatsheet

## 📂 Directory & File Navigation

```bash
pwd                    # Print current working directory
ls                     # List directory contents
ls -l                  # Long listing format
cd /path/to/dir        # Change directory
cd ..                  # Go up one directory
cd ~                   # Go to home directory
tree                   # Show directory tree (if installed)
```

## 📄 File & Directory Management

```bash
touch file.txt         # Create an empty file
mkdir new_folder       # Create a directory
rm file.txt            # Delete a file
rm -r folder/          # Delete a directory and its contents
cp source.txt dest.txt # Copy file
mv oldname.txt newname.txt  # Rename or move file
```

## 📃 File Viewing

```bash
cat file.txt           # View file contents
less file.txt          # View file with scroll (q to quit)
head -n 10 file.txt    # First 10 lines
tail -n 10 file.txt    # Last 10 lines
```

## 🛠️ File Permissions

```bash
chmod +x script.sh     # Make script executable
chmod 755 file         # Set read/write/execute permissions
chown user:group file  # Change file owner
```

## 🔍 Searching

```bash
find . -name "*.txt"          # Find files by name
grep "text" file.txt          # Search for text in a file
grep -r "text" /path/to/dir   # Search recursively in directory
```

## 📦 Package Management

### Debian/Ubuntu (apt)

```bash
sudo apt update               # Update package list
sudo apt upgrade              # Upgrade packages
sudo apt install packagename  # Install package
sudo apt remove packagename   # Remove package
```

### RedHat/CentOS (yum)

```bash
sudo yum update               # Update system
sudo yum install packagename  # Install package
sudo yum remove packagename   # Remove package
```

## ⚙️ System Info

```bash
uname -a               # Kernel & system info
top                    # Task manager
htop                   # Better task manager (if installed)
df -h                  # Disk space usage
free -h                # Memory usage
whoami                 # Current user
```

## 🔧 Process Management

```bash
ps aux                 # View all running processes
kill <pid>             # Kill process by PID
kill -9 <pid>          # Force kill
```

## 🔄 Networking

```bash
ifconfig               # Show network interfaces (deprecated)
ip a                   # Show IP address
ping google.com        # Ping a server
netstat -tulnp         # Show active ports and services
curl http://example.com  # Get URL content
```

## 🧱 File Compression

```bash
tar -czvf file.tar.gz folder/   # Compress folder
tar -xzvf file.tar.gz           # Extract tar.gz file
zip -r file.zip folder/         # Zip a folder
unzip file.zip                  # Unzip a file
```

## 🖥️ Miscellaneous

```bash
history                # Show command history
clear                  # Clear terminal
alias ll='ls -la'      # Create a shortcut command
man ls                 # Show manual page for `ls`
```

