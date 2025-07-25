# 🛡️ Cybersecurity Course – Day 3  
## 📂 Basic Linux Commands Used in Kali Linux

---

### 🐧 Introduction

Kali Linux is a Debian-based OS tailored for cybersecurity professionals. It comes pre-installed with many tools, but to use them effectively, a solid understanding of basic Linux commands is essential.

---

### 📌 Categories of Basic Linux Commands

#### 2. Directory Navigation
| Command | Description |
|--------|-------------|
| `pwd` | Print current working directory |
| `ls` | List directory contents |
| `ls -l` | Long listing format |
| `ls -a` | Includes hidden files |
| `cd [directory]` | Change directory |
| `cd ~` | Go to home directory |
| `cd ..` | Move one directory up |

#### 3. File Management
| Command | Description |
|--------|-------------|
| `touch file.txt` | Create an empty file |
| `cat file.txt` | View file content |
| `cp file1 file2` | Copy file1 to file2 |
| `mv file1 file2` | Move or rename a file |
| `rm file.txt` | Delete a file |
| `mkdir folder` | Create a new directory |
| `rmdir folder` | Remove an empty directory |

#### 4. User Management
| Command | Description |
|--------|-------------|
| `whoami` | Display current logged-in user |
| `id` | Show user and group IDs |
| `adduser username` | Create a new user |
| `passwd username` | Change user password |
| `su` | Switch user |
| `sudo` | Run command as superuser |

#### 5. Permissions
| Command | Description |
|--------|-------------|
| `ls -l` | View file permissions |
| `chmod 755 file.sh` | Change permissions |
| `chown user:group file` | Change file ownership |

#### 6. Networking
| Command | Description |
|--------|-------------|
| `ip a` or `ifconfig` | Show network interfaces/IP |
| `ping 8.8.8.8` | Check network connectivity |
| `netstat -tuln` | List open ports |
| `nmap [target]` | Scan network/host |
| `curl [url]` | Fetch data from a URL |
| `wget [url]` | Download file from the web |

#### 7. Process Management
| Command | Description |
|--------|-------------|
| `ps aux` | Show running processes |
| `top` / `htop` | Real-time process monitor |
| `kill PID` | Kill process by ID |
| `killall name` | Kill all processes with a name |

#### 8. Package Management
| Command | Description |
|--------|-------------|
| `apt update` | Refresh package list |
| `apt upgrade` | Upgrade packages |
| `apt install [pkg]` | Install a package |
| `apt remove [pkg]` | Uninstall a package |

---

### 🧪 Practice Task

Try these commands on your Kali Linux system:
```bash
cd /etc
ls -l
cat passwd
🧠 Pro Tips
Use man [command] to explore full documentation.

Use TAB for autocomplete and faster typing.

Combine commands with |, &&, ; to enhance efficiency.

✅ Summary
These basic Linux commands form the foundation of almost every cybersecurity operation. Becoming comfortable with them will allow you to interact with Kali Linux tools and services more effectively.

