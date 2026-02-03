
# **🔋 Battery Charging Safety Alert – Interaction Prototype**

---

A user-centric interaction prototype designed to promote safe and healthy device charging habits through clear, state-based alerts and overheating warnings.



## 📌 Overview

Battery Charging Safety Alert helps users make better charging decisions by translating battery level and temperature data into simple, actionable notifications.

In addition to charging alerts, the system also warns users when the device begins to overheat—helping protect battery health and overall device safety.

This project focuses on interaction logic and UX design, not hardware-level implementation.

---

## ⚙️ How It Works

The system continuously monitors battery level and device temperature and responds using clearly defined states.

---

## 🔋 Battery States

🔴 Below 20%
→ Charge reminder to prevent sudden shutdown

🟢 20% – 80%
→ Safe charging zone (no alerts shown)

🔔 Above 80%
→ Unplug alert to reduce overcharging

🌡️ Temperature State

⚠️ Overheating Detected
→ Safety warning suggesting unplugging or cooling the device

All alerts are designed to be clear, timely, and non-intrusive, avoiding unnecessary interruptions.































| State                | Description                              |
| -------------------- | ---------------------------------------- |
| 🔴 Low Charging  | Battery below 20%, charging recommended  |
| 🟢 Normal        | Battery within safe usage range          |
| 🔔 High Charging | Battery above 80%, unplug suggested      |
| ❌ Bad Charging   | Overcharging or unsafe charging detected |
| ✅ Good Charging | Optimal charging conditions              |
| 🌡️ Overheating  | Device temperature exceeds safe limit    |
