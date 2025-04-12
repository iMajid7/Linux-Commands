
# 📦 Docker Linux Commands Guide

A curated collection of useful Docker commands for managing and interacting with Linux-based containers — specifically `npmplus` and `3x-ui`. Perfect for DevOps, sysadmins, and developers working with lightweight container setups.

---

## 📋 Command Overview

| 🏷️ Task | 🔧 Command |
|--------|-----------|
| 🧾 Check OS in `npmplus` | `docker exec -it npmplus cat /etc/os-release` |
| 🔄 Update package lists | `docker exec -it npmplus apt-get update` |
| 📥 Install `sqlite3` | `docker exec -it npmplus apt-get install -y sqlite3` |
| 🐚 Open Shell in `npmplus` | `docker exec -it npmplus /bin/sh` |
| 🐚 Open Shell in `3x-ui` | `docker exec -it 3x-ui /bin/sh` |

---

## 🧠 Command Details

### 🧾 Check OS Information
```bash
docker exec -it npmplus cat /etc/os-release
```
Displays the Linux distribution used inside the `npmplus` container.

---

### 🔄 Update Package Lists
```bash
docker exec -it npmplus apt-get update
```
Fetches the latest list of packages available from the repositories inside `npmplus`.

---

### 📥 Install `sqlite3`
```bash
docker exec -it npmplus apt-get install -y sqlite3
```
Installs the lightweight SQLite3 database engine inside the container.

---

### 🐚 Open a Shell in `npmplus`
```bash
docker exec -it npmplus /bin/sh
```
Opens an interactive shell session in the `npmplus` container.

---

### 🐚 Open a Shell in `3x-ui`
```bash
docker exec -it 3x-ui /bin/sh
```
Opens an interactive shell session in the `3x-ui` container.

---

## ⚠️ Notes & Tips

- Make sure your containers are **running** before executing these commands.
- These commands assume the containers use **Debian/Ubuntu**-based distributions.
- If `/bin/sh` doesn't work, try `/bin/bash` or check the container's base image.

---

## 📄 License

This guide is released under the [MIT License](LICENSE). You are free to use, modify, and share it.

---

## 💡 Contribute

Feel free to open a pull request or issue to suggest improvements or add more container command tips.
