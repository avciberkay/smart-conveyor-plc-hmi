# smart-conveyor-plc-hmi
Industrial automation demo using Omron PLC, Delta HMI, sensor and motor. Detects objects, handles jams, and simulates real-world control logic. #PLC #HMI #IndustrialAutomation #Omron #DeltaTFT

# 🚀 Smart Conveyor System – PLC + HMI Project

An industrial automation system built during my electrical engineering internship using:
- 🟢 Omron CJ2M-CPU31 PLC
- 📺 Delta HMI (DOPSoft)
- 🧠 Ladder logic with counters, timers, and alarm handling

## 🎯 Project Overview

This system:
- Counts product detections using a sensor
- Starts motor when 5 items are counted
- Detects jams (sensor stuck > 9s) and enters alarm mode
- Alarm disables motor and shows red blinking button
- User must press and hold to reset the system
- HMI shows progress bar and motor status

## 🔧 Tools & Components

- CX-One (CX-Programmer)
- DOPSoft (Delta HMI design)
- 3-phase motor + inverter
- Omron PLC, sensor, lamp, 2 buttons
- Power supply + real wiring

## 🧠 Folder Structure

| Folder      | Description |
|-------------|-------------|
| `/logic/`   | Ladder logic files (.cxp + screenshots) |
| `/hmi/`     | HMI screen images |
| `/diagrams/`| I/O wiring map + block diagrams |
| `/docs/`    | Logic explanation in markdown |
| `/photos/`  | Real project hardware photos |
| `/logbook/` | Daily summaries & learning log |

## 📸 Example Screenshots

![HMI Alarm](hmi/hmi_alarm_screen.png)
![Ladder Overview](logic/ladder_overview.png)

## 📝 Author
Berkay Avcı – Electrical & Electronics Engineering intern  
[LinkedIn](https://linkedin.com/in/berkay-avci-istanbul) – [GitHub](https://github.com/avciberkay)

## 💡 Future Plans

- Add variable motor speed control  
- Build web dashboard using Node-RED  
- Add MODBUS communication to second PLC



