<!-- Header -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:283e51,100:485563&height=200&section=header&text=🐧%20Basic%20Linux%20Commands&fontSize=40&fontColor=ffffff&animation=twinkling"/>
</p>

---

## 📂 File & Directory Management

| Command | Description |
|---------|-------------|
| `pwd` | Print current working directory |
| `ls` | List files and directories |
| `ls -la` | List all files with details (including hidden) |
| `cd <dir>` | Change directory |
| `cd ..` | Move up one directory |
| `mkdir <dir>` | Create a new directory |
| `rmdir <dir>` | Remove an empty directory |
| `rm -rf <dir>` | Remove directory with contents (⚠️ dangerous) |
| `touch <file>` | Create an empty file |
| `cp <src> <dest>` | Copy files/directories |
| `mv <src> <dest>` | Move or rename files/directories |
| `rm <file>` | Delete file |

---

## 📖 File Viewing & Editing

| Command | Description |
|---------|-------------|
| `cat <file>` | Show file content |
| `tac <file>` | Show file content in reverse |
| `less <file>` | View file with scroll |
| `head <file>` | Show first 10 lines |
| `tail <file>` | Show last 10 lines |
| `tail -f <file>` | Watch file live (logs) |
| `nano <file>` | Edit file in Nano editor |
| `vim <file>` | Edit file in Vim editor |

---

## 🔍 Search & Find

| Command | Description |
|---------|-------------|
| `find /path -name <file>` | Find file by name |
| `locate <file>` | Quickly find file (uses index) |
| `grep "text" <file>` | Search text in file |
| `grep -r "text" /dir` | Recursive search in directory |
| `which <command>` | Show command location |
| `whereis <command>` | Show all locations of command |

---

## ⚙️ System Information

| Command | Description |
|---------|-------------|
| `uname -a` | Show system & kernel info |
| `hostname` | Show system hostname |
| `uptime` | Show system uptime |
| `date` | Show current date & time |
| `df -h` | Show disk usage |
| `du -sh <dir>` | Show size of directory |
| `free -h` | Show memory usage |
| `top` | Show running processes |
| `htop` | Interactive process viewer |

---

## 👤 User & Permissions

| Command | Description |
|---------|-------------|
| `whoami` | Show current user |
| `id` | Show user ID and group ID |
| `who` | Show logged in users |
| `adduser <name>` | Add new user |
| `passwd <name>` | Change user password |
| `chmod 755 <file>` | Change file permissions |
| `chown user:group <file>` | Change file ownership |
| `sudo <command>` | Run as superuser |

---

## 🌐 Networking

| Command | Description |
|---------|-------------|
| `ping <host>` | Test connectivity |
| `curl <url>` | Fetch data from URL |
| `wget <url>` | Download file from URL |
| `ifconfig` / `ip a` | Show network interfaces |
| `netstat -tulnp` | Show listening ports |
| `ss -tulnp` | Show socket stats |
| `scp <file> user@host:/path` | Secure copy files |
| `ssh user@host` | Connect to remote server |

---

## 📦 Package Management

### Debian/Ubuntu (APT)
| Command | Description |
|---------|-------------|
| `apt update` | Refresh package index |
| `apt upgrade` | Upgrade all packages |
| `apt install <pkg>` | Install package |
| `apt remove <pkg>` | Remove package |
| `apt search <pkg>` | Search package |

### RedHat/CentOS (YUM/DNF)
| Command | Description |
|---------|-------------|
| `yum install <pkg>` | Install package |
| `yum remove <pkg>` | Remove package |
| `yum update` | Update system |
| `dnf install <pkg>` | Install package (newer) |

---

## 📊 File Compression & Archiving

| Command | Description |
|---------|-------------|
| `tar -cvf file.tar dir/` | Create tar archive |
| `tar -xvf file.tar` | Extract tar archive |
| `tar -czvf file.tar.gz dir/` | Create compressed archive |
| `tar -xzvf file.tar.gz` | Extract compressed archive |
| `gzip <file>` | Compress file |
| `gunzip <file.gz>` | Decompress file |

---

## 🖥️ Process Management

| Command | Description |
|---------|-------------|
| `ps aux` | List all running processes |
| `kill <pid>` | Kill process by PID |
| `kill -9 <pid>` | Force kill process |
| `jobs` | Show background jobs |
| `fg %1` | Bring job to foreground |
| `bg %1` | Resume job in background |

---

## 🛠️ Useful Tricks

```bash
history        # Show command history
!!             # Run last command
!n             # Run command by history number
clear          # Clear terminal
alias ll='ls -la'  # Create shortcut for ls -la
