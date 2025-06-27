# 🛡️ INSE 6190 - Wireless Network Security

A team project submitted for the course **INSE 6190 Wireless Network Security** under the supervision of **Professor Dr. Ayda Basyouni** at Concordia University. This project demonstrates various Wi-Fi security attacks and countermeasures using practical lab environments.

## 🔍 Overview

This project explores real-world wireless LAN security vulnerabilities through controlled simulations and attack demonstrations. Key topics covered include:

- Deauthentication Attacks
- WPA Handshake Capture & Password Recovery
- DNS Spoofing through Man-in-the-Middle (MITM)
- Rogue Access Point Setup and Traffic Interception

---

## 👥 Team Members & Contributions

| Name                  | Student ID | Contribution |
|-----------------------|------------|--------------|
| **Vaishnavi Kalathur** | 40292270   | **Deauthentication & Password Recovery**<br>- Enabled monitor mode using `airmon-ng`.<br>- Captured WPA handshake using `aireplay-ng` and `airodump-ng`.<br>- Successfully cracked the Wi-Fi password using `aircrack-ng`. |
| **Hariharan Duraisingh** | 40303001   | **DNS Spoofing through MITM**<br>- Configured DNS spoofing with `dnsspoof`.<br>- Redirected victims to fake login pages hosted via Apache.<br>- Demonstrated phishing via ARP and DNS spoofing in a local network. |
| **Raghu Pavan Annam** | 40303699   | **Fake Access Point (Evil Twin)**<br>- Set up rogue AP using `airbase-ng`, `dnsmasq`, and `hostapd`.<br>- Logged DNS spoofed traffic in a controlled lab setup.<br>- Enabled NAT and packet forwarding using `iptables`. |

---

## 🧪 Tools & Technologies

- Kali Linux
- `aircrack-ng` Suite
- `airodump-ng`, `aireplay-ng`
- `dnsspoof`, `dnsmasq`, `hostapd`
- Apache Server
- Wi-Fi Adapter in Monitor Mode

---

## ⚠️ Disclaimer

This project was conducted in a controlled academic environment. All attacks were performed on personal networks with proper permissions. **Never attempt these attacks on unauthorized networks.**

---

## 📂 Repository Structure (if applicable)

