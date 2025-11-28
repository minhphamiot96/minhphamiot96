# 👋 Hi, I’m Minh – Embedded & IoT Firmware Engineer  

🔌 I help **hardware startups** turn unstable prototypes into **field-ready IoT devices**.  
⚙️ I design **ultra low power firmware** for STM32 / nRF5340 / nRF52 / custom MCUs with smart sampling, logging, and efficient wireless uplink.  
🚀 I like taking products from **concept → something that can ship**: firmware, hardware integration, RF, UI, validation, and power/cost optimization.

---

## 🧩 What I Build

- 🔋 **Battery-powered sensor nodes**  
  Wake up → read sensors → log to internal / external SPI Flash → send compressed data → back to deep sleep.

- 🌐 **Gateways / telemetry units**  
  Aggregate min / max / average / vector-averaged wind direction, etc.  
  Send **summaries every X minutes** instead of streaming raw high-rate data.

- 🏭 **Industrial HVAC / building controllers**  
  BACnet MS/TP over RS-485 with **on-device UI** for configuration and status.

- 🎛 **High-performance Cortex-M7 control / DSP workloads**  
  Real-time audio / synthesis / I2S streaming with DMA and tight timing constraints.

> 💡 Goal: **Save battery**, **reduce airtime cost**, and still deliver **actionable analytics** for wind, temperature, humidity, vibration, GPS, and other environmental data.

---

## 🧱 Typical Features I Deliver

- 🕒 Power-aware scheduling with clear **state machines** and **event-driven logic**  
- 🧬 **Full stack ownership**: bootloader, BSP, low-level drivers, app logic, comms, data logging, OTA  
- 📀 Timestamped logging to Flash / SPI Flash with **batch uploads**  
- 🔐 Encrypted wireless transfer, pairing / session control  
- 🔁 Remote firmware update flows + **production test hooks** for manufacturing  
- 📊 LVGL dashboards, alarms, calibration & maintenance screens **running directly on MCUs** (not only Linux)

---

## 🔋 Low Power & Telemetry

- 🌙 Deep sleep / standby, peripheral gating, dynamic clock scaling  
- 📉 Strict duty cycling of radios and sensors  
- 📦 Data is **batched, compressed, summarized** before uplink  
- 🎯 Target: **multi-day → multi-month runtime** on battery (depending on hardware budget)

---

## 🛠 Tech I’m Fluent In

### 🧠 MCUs

- 🔷 **Nordic nRF52 / nRF5340**  
  - BLE central & peripheral  
  - Multi-node low power sensor networks  
  - nRF SDK & nRF Connect SDK (Zephyr)  
  - Custom BLE services, pairing, encrypted transfer

- 🟦 **STM32 (incl. Cortex-M7)**  
  - High-performance control / DSP  
  - Timing-critical industrial comms  
  - Real-time audio via **I2S + DMA**

- 🧩 **AT32F403A & uncommon MCUs**  
  - Bare-metal bring-up (little/no vendor HAL)  
  - GNU ARM toolchain, custom CMake build, startup code, linker scripts  
  - Drivers: clock / GPIO / UART / I2C / SPI / timers / DMA  
  - J-Link + Ozone integration (live registers, tracing)  
  - Delivered as **internal SDKs** for future reuse

- 📶 **ESP32** – Wi-Fi / Wi-Fi+BLE gateways  
- 🕰 **MSP430 & similar ultra-low-power MCUs** – long-life battery loggers  
- 🐧 **Embedded Linux-class SoCs** – edge gateways, protocol translation, local processing

---

## 🧵 OS / Runtimes

- 🧪 Bare metal  
- 🪶 Zephyr, FreeRTOS, RIOT OS  
- 🧬 Custom lightweight schedulers for deep sleep systems  
- 🐧 Embedded Linux (Yocto-style rootfs) for gateway / controller devices

---

## 📡 Connectivity & Protocols

### 🌍 Wireless / field networking

- 🔵 BLE  
- 📡 LoRaWAN  
- 🛰 Sigfox  
- 🪂 Fanet  
- 📶 Wi-Fi  
- 🏢 BACnet MS/TP over RS-485 (HVAC / building automation)

### 🏭 Industrial / vehicle / building interfaces

- 🚗 CAN / CAN FD  
- 🔁 Modbus  
- 📏 SENT  
- 🌐 Ethernet  
- ⚙️ EtherCAT (SOES, IgH)  
- 🧱 BACnet object mapping  
  - AI / AO / Multi-state values into building controllers

---

## 🖥 User Interface / HMI on MCU

- 📊 **LVGL dashboards** – charts, alarms, calibration & maintenance tools  
- ✋ Capacitive multi-touch (FT series), gestures, smooth scrolling  
- 🖼 TFT / RGB / SPI / DWIN panels  
- 🎨 Screen flows & assets designed in **SquareLine Studio**, merged back into firmware  
- 🛠 Includes:
  - Configuration pages  
  - Live sensor status  
  - Manual override panels  
  - Firmware update & service screens for field technicians

---

## 🧪 Production, Test & Support

- 🧑‍🔧 Work directly with hardware during validation & manufacturing  
- 🧷 Tools: Segger J-Link, ST-Link, Lauterbach, Segger Ozone  
- 📡 Logic analyzer / oscilloscope for:
  - I2S audio timing  
  - SPI timing  
  - Sensor readout timing  
  - RF handshake timing  
- 🥾 Bootloader & field firmware update flows  
- 🏭 Production test hooks & manufacturing bring-up  
- 🧾 Hardware review for manufacturability & BOM cost  
  - RF module choice  
  - Antenna layout  
  - Sensor selection  

---

## 📂 What You’ll Find on This GitHub

- 🔬 **Firmware for sensor nodes & gateways** (low-power focused)  
- 🧱 **Reusable drivers & internal SDKs** for MCUs like nRF52, STM32, AT32F403A  
- 📡 **Connectivity demos** (BLE, Sigfox, LoRaWAN, BACnet, EtherCAT, RS-485, etc.)  
- 🖼 **LVGL + SquareLine HMI projects** for embedded displays  
- 🧪 **Test utilities** for manufacturing, logging, and debugging

---

## 📫 Contact

- 💼 Open to **freelance / contract** work on embedded & IoT projects  
- 🌍 Comfortable working with **remote hardware startups** and distributed teams  
- 🇻🇳 _Tiếng Việt: Tôi cũng nhận dự án firmware/IoT và có thể trao đổi hoàn toàn bằng tiếng Việt._

If you’re building hardware that needs **reliable, low-power, field-ready firmware**, feel free to reach out or open an issue in one of the repos here. 🙂

<hr>

<h3> 🤝🏻 Connect with Me </h3>
<p align="left">
<a href="https://www.linkedin.com/in/minh-ph%E1%BA%A1m-ng%E1%BB%8Dc-980749188/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Minh%20Pham-blue?style=flat-square&logo=linkedin"></a>
</p>

<hr>


