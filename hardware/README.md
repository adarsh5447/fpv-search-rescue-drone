# 🔧 Hardware Architecture – Search & Rescue FPV Drone

This section provides a detailed overview of the complete hardware stack used in the development of the Search & Rescue FPV Drone.

---

## 🏗 Frame Structure

**SpeedyBee Bee35 Pro Frame**

![Frame](../images/SpeedyBee-Bee35-Pro-Frame.jpeg))


- 2mm carbon fiber plate thickness
- Lightweight and impact-resistant
- Designed for high maneuverability
- Vibration-resistant structure

---

## 🧠 Flight Controller

**SpeedyBee F405 V3 Mini (20x20 Stack)**

![Flight Controller](../images/speedybee f405 v3 mini.jpeg)

- STM32 F405 processor
- Built-in Bluetooth
- Integrated barometer
- 6S LiPo compatible

Acts as the central processing unit managing stabilization and motor outputs.

---

## ⚙️ Propulsion System

### 🌀 Motors  
**Emax ECOII-2004-2400KV Brushless Motors (4x)**

![Motor](../images/Emax ECOII-2004-2400KV Brushless Moto.jpeg)

- High thrust-to-weight ratio
- Durable reinforced architecture
- Optimized for 6S LiPo configuration

---

## 🔋 Power System

**CNHL Black Series V2.0 1500mAh 22.2V 6S LiPo**

![Battery](../images/CNHL Black Series V2.0 1500mAh 22.2V 65 130C Lipo Battery.jpeg)

- 1500mAh capacity
- 22.2V (6S)
- 65C–130C discharge rate
- High current output for aggressive maneuvering

---

## 🎥 FPV Camera System

**RunCam Racer Nano 4 (Analog FPV Camera)**

![Camera](../images/runcam racer nano 4 fpv camera.jpeg)

- Ultra-low latency analog output
- High Dynamic Range
- Nano-size lightweight design

Provides real-time visual feed for SAR navigation.

---

## 📡 Video Transmission System

**AKK A1819 5.8GHz Long Range VTX**

![VTX](../images/AKK-A1819-5.8G-Long-Range-VTX-Switchable-Transmitter.jpeg)

- 200/400/800/1000mW switchable power
- Smart Audio supported
- Long-range analog transmission

Transmits camera feed to FPV goggles.

---

## 🎮 Remote Control System

**FlySky FS-i6X 10CH 2.4GHz Transmitter**

![Transmitter](../images/Flysky Fs-I6X 10Ch 2.4Ghz Rc Transmitter Controller with laB Receiver Upgrade Cable for Rc Boat Racing Drone.jpeg)

- AFHDS2A protocol
- Reliable long-range communication
- 10-channel capability

---

## 👓 Ground Viewing System

**Eachine EV800 FPV Goggles**

![Goggles](../images/Eachine EV800 FPV Goggles - Black.jpeg)

- 5.8GHz analog receiver
- Built-in diversity receiver
- Integrated DVR
- Low-latency live viewing

Receives real-time analog transmission from AKK VTX.

---

## 🛩 Complete Drone Assembly

### Drone Model

![Drone Model](../images/drone model.jpeg)

### System Architecture Diagram

![Architecture](../images/drone-architecture.jpeg)

### Final Output Model

![Output Model](../images/output real model.jpeg)

---

## 🔄 Hardware Signal Flow Overview

1. FlySky FS-i6X → Receiver  
2. Receiver → SpeedyBee F405 Flight Controller  
3. Flight Controller → ESC → Emax Motors  
4. RunCam Nano 4 → AKK A1819 VTX  
5. AKK VTX → Eachine EV800 Goggles  

---

## 🧩 Design Philosophy

The hardware selection was optimized for:

- Long-range analog reliability
- Ultra-low latency video
- High thrust-to-weight ratio
- Durable SAR deployment
- 6S high-performance power system
