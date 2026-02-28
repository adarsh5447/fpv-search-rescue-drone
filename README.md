# 🛩️ Search and Rescue FPV Drone

A high-performance, long-range analog FPV drone designed for real-time surveillance and search & rescue (SAR) operations in disaster environments.

---

## 📌 Project Objective

To develop a compact, agile FPV drone capable of entering confined or collapsed spaces and providing uninterrupted real-time video feed to assist rescue teams.

---

## 🧩 System Architecture

![FPV Drone Architecture](images/drone-architecture.jpeg)

---

## 🔍 System Components

### ⚙️ Flight Controller
**SpeedyBee F405 V3 Mini**
- F405 processor
- Built-in Bluetooth
- Barometer
- 20x20 stack configuration

### 🌀 Motors
**Emax ECOII-2004-2400KV Brushless Motors (x4)**
- High thrust-to-weight ratio
- Reinforced architecture for durability

### 🎥 FPV Camera
**RunCam Racer Nano 4**
- Low latency analog video output

### 📡 Video Transmitter
**AKK A1819 5.8GHz VTX**
- 200/400/800/1000mW switchable
- Smart Audio supported
- Long-range analog transmission

### 🔋 Battery
**CNHL Black Series V2.0**
- 1500mAh
- 22.2V (6S)
- 65C–130C discharge rate

### 🎮 Transmitter
**FlySky FS-i6X (10CH, 2.4GHz)**

### 👓 Ground Station
Analog VR FPV Goggles for low-latency real-time viewing.

---

## 🔄 Signal Flow

1. Pilot Input → FlySky Transmitter  
2. Receiver → Flight Controller  
3. Flight Controller → ESC → Motors  
4. Camera → VTX → Analog FPV Goggles  

---

## 💻 Software

The drone is configured using **Betaflight Firmware**.

### Configuration Performed:
- PID tuning
- ESC calibration
- Receiver binding
- Smart Audio VTX control
- OSD configuration
- Voltage monitoring

Betaflight ensures low-latency flight response and stable performance.

---

## 🚀 Key Features

- Long-range analog transmission
- Low latency video feed
- Compact carbon fiber structure
- High agility and maneuverability
- SAR-optimized architecture

---

## 📊 Evaluation Parameters

- Communication reliability
- Flight stability
- Response time
- Coverage area per battery cycle

---

## 📸 Project Images

(Add real images inside the images folder)

---

## 📚 What I Learned

- High-performance FPV system integration
- 6S LiPo power management
- VTX tuning & Smart Audio configuration
- PID optimization using Betaflight
- Structural balancing and vibration reduction
- SAR deployment constraints
