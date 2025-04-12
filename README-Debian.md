
# 🐧 Debian/Ubuntu Essential Linux Commands

A handy collection of frequently used Linux commands for Debian-based systems like Ubuntu. Ideal for system administrators, developers, and everyday power users.

---

## 📋 Command Overview

| 🏷️ Task | 🔧 Command |
|--------|-----------|
| 🔍 Update package index | `sudo apt update` |
| ⬆️ Upgrade all packages | `sudo apt upgrade -y` |
| 🧼 Full upgrade with dependencies | `sudo apt full-upgrade -y` |
| 🧹 Remove unused packages | `sudo apt autoremove -y` |
| ❌ Remove a package | `sudo apt remove <package-name>` |
| 🔎 Search for a package | `apt search <package-name>` |
| 📦 Install a package | `sudo apt install <package-name>` |
| 🔄 Reconfigure a package | `sudo dpkg-reconfigure <package-name>` |
| 📁 Show disk usage | `df -h` |
| 🧠 Show memory usage | `free -h` |
| 👤 Show logged-in users | `who` |
| 🔁 Reboot system | `sudo reboot` |
| 📴 Shutdown system | `sudo poweroff` |

---

## 🔧 Most Used Commands

### 🔍 Update Package Index
```bash
sudo apt update
```
Refreshes the list of available packages and their versions.

---

### ⬆️ Upgrade All Packages
```bash
sudo apt upgrade -y
```
Upgrades all installed packages to the latest available version.

---

### 🕖 Update Package Index && Upgrade All Packages
```bash
sudo apt update && sudo apt upgrade -y
```
Refreshes the list of available packages and their versions & Upgrades all installed packages to the latest available version.

---

### 🧼 Clean Up Unused Packages
```bash
sudo apt autoremove -y
```
Removes packages that were installed automatically but are no longer required.

---

### 📦 Install a Package
```bash
sudo apt install <package-name>
```
Replaces `<package-name>` with the software package you want to install.

---

### ❌ Remove a Package
```bash
sudo apt remove <package-name>
```
Uninstalls a package while keeping its configuration files.

---

### 🔁 Reboot or Shutdown
```bash
sudo reboot
# or
sudo poweroff
```
Use `reboot` to restart the system or `poweroff` to shut it down completely.

---

## 💡 Pro Tips

- Use `apt` instead of `apt-get` for interactive and user-friendly outputs.
- Combine update and upgrade: `sudo apt update && sudo apt upgrade -y`
- Check logs: `journalctl -xe` or `dmesg | less`
- Use `htop` or `top` to monitor system processes in real-time.

---

## 📄 License

This cheat sheet is released under the MIT License. Feel free to use and contribute!

---

## 🤝 Contributions Welcome

Found something useful missing? Feel free to submit a pull request with your favorite Debian commands!
