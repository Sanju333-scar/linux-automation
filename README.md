# 🚀 Automated Linux Server Setup using Ansible

## 📌 Project Overview

This project automates the setup of a Linux server using Ansible. With a single command, it installs required software, configures security settings, and prepares the server for production use.

---

## 🎯 Features

* 📦 Install essential packages:

  * NGINX (Web Server)
  * Docker
  * Git
  * UFW Firewall

* 👤 User Management:

  * Creates a new admin user (`adminuser`) with sudo privileges

* 🔐 Security Hardening:

  * Disables root SSH login
  * Configures secure SSH access

* 🔥 Firewall Configuration:

  * Enables UFW
  * Opens ports:

    * 22 (SSH)
    * 80 (HTTP)
    * 443 (HTTPS)

---

## 🛠️ Technologies Used

* Linux (Ubuntu)
* Ansible
* Bash
* VirtualBox

---

## 📁 Project Structure

```
linux-automation/
│── setup.yml
│── inventory.ini
│── README.md
│── screenshots/
```

---

## ⚙️ How to Run

### 1️⃣ Clone the repository

```bash
git clone https://github.com/yourusername/linux-automation.git
cd linux-automation
```

### 2️⃣ Run the Ansible Playbook

```bash
ansible-playbook -i inventory.ini setup.yml --ask-become-pass
```

---

## 🧪 Expected Output

After running the playbook:

* ✅ NGINX installed and running
* ✅ Docker installed
* ✅ New sudo user created
* ✅ SSH secured (root login disabled)
* ✅ Firewall enabled and configured

---

## 🌐 Verify Setup

Open in browser:

```
http://localhost
```

👉 You should see the **NGINX Welcome Page**

---

## 📸 Screenshots

### NGINX Running

![NGINX](screenshots/nginx-running.png)

---

## 💼 Use Case

This project demonstrates:

* Linux system administration
* Infrastructure automation
* DevOps fundamentals
* Server security best practices

---

## 👨‍💻 Author

Sanju Sebastian

---


