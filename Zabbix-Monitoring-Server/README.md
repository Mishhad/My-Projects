# Zabbix Monitoring Project

## 📌 Overview

This project demonstrates the installation and configuration of a Zabbix monitoring server using Ubuntu Server in Oracle VirtualBox.

The setup includes:
- Zabbix Server
- Zabbix Agent
- Apache Web Server
- MySQL Database
- Zabbix Web Dashboard

The project simulates how real companies monitor servers and systems from a centralized dashboard.

---

## 🎯 Objectives

- Install Ubuntu Server in VirtualBox
- Configure Zabbix Server
- Set up MySQL database for Zabbix
- Enable Zabbix web interface
- Monitor Ubuntu system resources
- Access monitoring dashboard from host machine browser

---

## 🖥️ Lab Environment

| Component | Details |
|---|---|
| Hypervisor | Oracle VirtualBox |
| Operating System | Ubuntu Server 24.04 LTS |
| Monitoring Tool | Zabbix |
| Web Server | Apache2 |
| Database | MySQL |
| Host Machine | Windows |

---

## ⚙️ Technologies Used

- Linux Administration
- Zabbix Monitoring
- Apache2
- MySQL
- VirtualBox
- Networking
- System Monitoring

---

## 🌐 Accessing the Dashboard

The Zabbix frontend was accessed from the Windows host browser using:

```bash
http://<SERVER-IP>/zabbix
```

Example:

```bash
http://192.168.X.X/zabbix
```

---

## 📊 Features Configured

- Zabbix Server installation
- Zabbix Agent installation
- Database configuration
- Web frontend setup
- Service management using systemctl
- System resource monitoring

---

## ✅ Skills Learned

- Linux server setup
- Monitoring infrastructure
- Service management
- Web dashboard configuration
- Basic troubleshooting
- Real-world monitoring concepts

---

## 🚀 Project Outcome

Successfully deployed and configured a working Zabbix monitoring environment capable of monitoring system resources through a centralized dashboard.
