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

## 🛠️ Commands Used

`ssh`
---

## 📜 Step-by-Step Solution

For this game I will be using Windows and Putty. You can download putty at https://www.putty.org/. Its an SSH and Telnet client that we will use to connect to OTW.

![64bitputty](https://github.com/user-attachments/assets/38c549e3-6efd-4c3f-8db4-3c827706aae6)

### 1. Connect to the server

The first thing I did was to open up Putty.

![2025-05-27_12-46](https://github.com/user-attachments/assets/8bec0c44-739c-40c7-9707-d3abfede54f3)

As you can see in the image above you can input the host name and the port number that was given to us. The host name is bandit.labs.overthewire.org and the port number we will be using is 2220
make sure the connection type is set to SSH and the click Open. A termninal window will appear and ask us for our login. The login name that was given to use is bandit0, the password is the same as the username.

![logon](https://github.com/user-attachments/assets/a40d9804-dcd0-4694-9e0f-a58ec6a4cea7)

After you type in the password and press enter you will be successfully logged

![2025-05-27_12-50](https://github.com/user-attachments/assets/7fa75eba-4453-4ceb-be29-4ddbc6c5da7a)

On the bottom left you can see that we have logged in as the user bandit0
```bash
bandit0@bandit:~$
