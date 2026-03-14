# Ansible Role: Load Balancer

This role installs and configures a load balancer for distributing traffic across backend servers.

---

## 📌 Overview

The **balancer** role automates deployment of a load balancing service used to distribute requests across multiple backend servers, improving scalability and availability.

---

## 🚀 Features

* Load balancing configuration
* Backend server management
* Traffic distribution
* Infrastructure automation ready

---

## 🧰 Requirements

* Ansible >= 2.9
* Linux server

---

## ⚙️ Role Variables

Example variables:

```yaml
balancer_port: 80

backend_servers:
  - 192.168.1.10
  - 192.168.1.11
```

---

## ▶️ Example Playbook

```yaml
- hosts: load_balancers
  become: true
  roles:
    - gustavoohrodrigues.balancer
```

---

## 📦 Installation

```bash
ansible-galaxy install gustavoohrodrigues.balancer
```

---

## Author

**Gustavo Henrique Rodrigues**
SysAdmin

LinkedIn
https://www.linkedin.com/in/gustavo-henrique-rodrigues-3070a5260

---

## 📜 License

MIT
