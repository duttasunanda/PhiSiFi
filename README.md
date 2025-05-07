<p align="center">
  <img src="https://raw.githubusercontent.com/duttasunanda/PhiSiFi/main/assets/phisiwe-banner.png" alt="PhiSiFi Banner" width="100%">
</p>

<h1 align="center">🔥 ZenInfiny 🔥</h1>

<p align="center">
  <b>WiFi Penetration Testing Tool using ESP8266</b> <br>
  <i>Combines Deauthentication & Evil Twin Attacks in One Powerful Package</i>
</p>

<p align="center">
  <img src="https://img.shields.io/github/license/duttasunanda/PhiSiFi?style=for-the-badge" alt="License">
  <img src="https://img.shields.io/github/stars/duttasunanda/PhiSiFi?style=for-the-badge" alt="Stars">
  <img src="https://img.shields.io/github/forks/duttasunanda/PhiSiFi?style=for-the-badge" alt="Forks">
</p>

---

## 🚀 Overview

**PhiSiFi** is a lightweight yet powerful firmware for the **ESP8266 NodeMCU**, built for **ethical WiFi penetration testing**. It allows users to **run Deauthentication Attacks** and simultaneously host an **Evil Twin Access Point** to capture credentials and test network vulnerabilities.

🔐 Developed by **Sunanda Dutta** for cybersecurity enthusiasts, students, and researchers.

> ⚠️ For educational and authorized testing only. Unauthorized use is prohibited.

---

## 🧩 Features

✅ Simultaneous **Deauth + Evil Twin** attack  
✅ Captures and verifies WiFi passwords  
✅ Web-based control panel (via captive portal)  
✅ Custom AP credentials (WiPhi_####)  
✅ No PC needed after setup — works standalone

---

## 🛠️ Setup Guide (Arduino IDE)

### 📌 Prerequisites

- Arduino IDE: [Download](https://www.arduino.cc/en/software)
- Board URL:  [Buy](https://robu.in/product/nodemcu-cp2102-board/)
### 📥 Installation Steps

1. Open **Arduino IDE**
2. Go to **File → Preferences** and paste the above board URL
3. Go to **Tools → Board → Boards Manager** and install `Deauther`
4. Clone this repo:  

5. Open the `.ino` file inside Arduino
6. Select `ESP8266 Deauther` as board
7. Choose the correct **COM port**
8. Hit **Upload**

---

## 🌐 How to Use

1. **Power your ESP8266**
2. Connect to WiFi:  
📶 SSID: `ZenInfiny`  
🔑 Password: `ZenInfiny123`
3. Visit `http://192.168.4.1`
4. Scan and select a target network
5. Click **Start Deauthing** or **Start Evil-Twin**
6. Capture and verify credentials
7. To stop, visit `http://192.168.4.1/admin` or reboot the board

---

## 🖼️ Interface Preview

<p align="center">
<img src="https://raw.githubusercontent.com/duttasunanda/PhiSiFi/main/assets/screenshot-ui.png" width="80%" alt="PhiSiFi UI">
</p>

---

## 📚 Credits

- [ESP8266 Deauther – SpacehuhnTech](https://github.com/SpacehuhnTech/esp8266_deauther)  
- [ESP8266 Evil Twin – M1z23R](https://github.com/M1z23R/ESP8266-EvilTwin)  
- [ESP8266 Captive Portal – adamff1](https://github.com/adamff1/ESP8266-Captive-Portal)

---

## 👩‍💻 Author

Made with ❤️ by **Sunanda Dutta**  
🔗 [GitHub Profile](https://github.com/duttasunanda)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🌟 Support the Project

If you found **PhiSiFi** useful:

🌟 Star the repo  
🍴 Fork it  
📢 Share with fellow hackers

---

