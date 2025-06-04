# 🚀 Custom ESP32 Development Board – Designed in KiCad

Welcome to the hardware design repo of a **fully custom ESP32-WROOM-32 development board**, engineered for rapid prototyping, compact integration, and modern embedded applications. Designed from the ground up using **KiCad**, this board blends functionality, minimalism, and scalability in one neat package.

---

## ✨ Key Features

- 🔌 **USB Type-C** interface with ESD protection and auto-reset
- 📡 **ESP32-WROOM-32** SoC (Wi-Fi + BLE, dual-core MCU)
- 🔋 **Onboard 3.3V LDO** regulator for stable low-noise operation
- 🎛️ **Accessible I/O headers**: UART, SPI, I2C, ADC, DAC, and GPIOs
- 📐 **Compact PCB layout** – Breadboard compatible
- 🛡️ **Proper antenna clearance & keep-out zone**
- 💾 Designed 100% in **KiCad 7.x**

---

## 🧠 Technical Overview

| Component         | Details                                             |
|------------------|-----------------------------------------------------|
| **MCU**          | ESP32-WROOM-32 (ESP32-D0WDQ6)                       |
| **USB Interface**| USB-C (via CH340/CP2102 + reset circuit)            |
| **Power Input**  | 5V via USB-C                                        |
| **Voltage Reg.** | AP2112 / AMS1117-3.3 LDO Regulator                  |
| **Reset Circuit**| BOOT & EN push buttons with RC logic                |
| **Connectivity** | UART, I2C, SPI, ADC, DAC, PWM exposed               |
| **Mounting**     | 2x M2 screw holes for enclosure compatibility       |
| **Board Size**   | ~74mm x 32mm                                        |

---

---

## 🛠️ Getting Started

### 🖥️ Open Project
- Clone this repo and open `custom_esp32.kicad_pro` in **KiCad 7.x**

### 🧾 Generate Gerbers
- Go to **File → Plot** → Generate files for your PCB manufacturer

### 🔧 Program the Board
- Use Arduino IDE / ESP-IDF
- Connect via USB-C
- Use `BOOT` + `EN` buttons for flashing if needed

---

## 📦 Fabrication Tips

- Board designed with **antenna clearance**
- Clean **silkscreen labeling** for easy assembly
- No component under USB port for low-profile casing
- Test points can be added if needed for production

---

## 💡 Applications

- IoT Device Development
- Sensor Gateway Nodes
- Home Automation
- Robotics Controller
- Custom Wireless Modules

---


## 🤝 Credits & Contact

Designed by **Shivansh Chauhan**  
📧 Email: `shivanshchauhan.228@gmail.com`  
🔗 LinkedIn: https://www.linkedin.com/in/shivanshchauhan2001

If you like this project, consider giving it a ⭐ on GitHub!

---

> “Great hardware begins with thoughtful design.”


