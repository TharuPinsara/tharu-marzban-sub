# Custom Marzban Subscription Page

![Custom Sub](https://img.shields.io/badge/Tharu%20Paid%20Servers-%2300d4ff?style=for-the-badge&logo=shield)
![Marzban](https://img.shields.io/badge/Marzban-Subscription%20Template-1a6fff?style=for-the-badge)

A beautiful, modern cyber-style subscription page for **Marzban Panel**.

![Subscription Speedtest](https://github.com/TharuPinsara/tharu-marzban-sub/blob/main/Files/Screenshot%203.png)
---

## ✨ Features

- Modern neon cyberpunk design with animated background
- Real-time data usage gauge with color coding
- Built-in internet speed test (Ping, Download, Upload)
- Quick import links for Android, iOS, and Windows
- QR Code support for easy configuration
- One-click "Copy All Configs"
- Responsive design (works perfectly on mobile)
- Multiple VPN client guides

---

## 🛠 Installation

Run the following commands on your Server:

```bash
# 1. Download the template
sudo wget -N -P /var/lib/marzban/templates/subscription/ \
https://raw.githubusercontent.com/TharuPinsara/tharu-marzban-sub/main/subscription/index.html

# 2. Enable custom subscription template
echo 'CUSTOM_TEMPLATES_DIRECTORY="/var/lib/marzban/templates/"' | sudo tee -a /opt/marzban/.env
echo 'SUBSCRIPTION_PAGE_TEMPLATE="subscription/index.html"' | sudo tee -a /opt/marzban/.env

# 3. Restart Marzban
sudo marzban restart
```
## 📸 Screenshots

![Tharu Paid Servers Subscription Page](https://github.com/TharuPinsara/tharu-marzban-sub/blob/main/Files/Screenshot%201.png)
![Subscription Speedtest](https://github.com/TharuPinsara/tharu-marzban-sub/blob/main/Files/Screenshot%202.png)


---
