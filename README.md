# OverTheWire – Bandit Level 0

**Challenge URL:**  
[https://overthewire.org/wargames/bandit/](https://overthewire.org/wargames/bandit/)

---

## 🧠 Goal

> The goal of this level is for you to log into the game using SSH. The host to which you need to connect is bandit.labs.overthewire.org, on port 2220. The username is bandit0 and the password is bandit0. Once logged in, go to the Level 1 page to find out how to beat Level 1.

---

## 🔑 Credentials

- **Username:** `bandit0`
- **Password:** `bandit0`
- **Host:** `bandit.labs.overthewire.org`
- **Port:** `2220`

---

## 🛠️ Tools Used

`ssh`, `ls`, `cat`, `find`, `strings`, `file`, `nc`, etc.

---

## 📜 Step-by-Step Solution

### 1. Connect to the server

For this game I will be using Windows and Putty. You can download putty at https://www.putty.org/. Its an SSH and Telnet client that we will use to connect to OTW.

```bash
ssh banditX@bandit.labs.overthewire.org -p 2220
