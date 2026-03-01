# 💻 Software Configuration – Search & Rescue FPV Drone

This section describes the firmware, configuration, and tuning performed for the FPV drone.

---

## 🧠 Flight Firmware

### Betaflight (Open Source Flight Control Firmware)

The drone is configured using **Betaflight firmware**, widely used for high-performance FPV drones.

Betaflight provides:
- Real-time flight stabilization
- PID tuning
- ESC calibration
- Receiver configuration
- OSD (On-Screen Display) integration
- Smart Audio VTX control

---

## ⚙️ Flight Controller Configuration

The SpeedyBee F405 V3 Mini was configured with:

- 6S battery voltage monitoring
- Motor direction setup
- ESC calibration
- Failsafe configuration
- Arming safety logic
- Receiver mapping (FlySky FS-i6X)

---

## 🎮 Receiver Setup

The FlySky FS-i6X transmitter was bound using the AFHDS2A protocol.

Configuration included:
- Channel mapping
- Throttle calibration
- AUX switch assignment for:
  - Arm/Disarm
  - Flight Modes
  - VTX power switching

---

## 📡 VTX Configuration

The AKK A1819 VTX was configured using Smart Audio via Betaflight.

Configured parameters:
- Output power selection (200/400/800/1000mW)
- Channel selection
- Frequency band setup
- OSD VTX power display

---

## 📊 OSD (On-Screen Display) Setup

The Betaflight OSD was configured to display:

- Battery voltage
- RSSI signal strength
- Flight time
- VTX power level
- Warning alerts

This allows real-time monitoring during SAR operations.

---

## 🛡 Safety Configuration

- Failsafe: Motor cutoff on signal loss
- Low battery voltage warning
- Arming disabled without stable signal
- Proper throttle calibration

---

## 🚀 Performance Tuning

PID tuning was performed to:

- Improve flight stability
- Reduce oscillations
- Improve throttle response
- Enhance maneuverability in confined environments

---

## 🧩 Software Design Philosophy

The software configuration was optimized for:

- Low latency response
- Stable hover capability
- Reliable long-range communication
- Safe SAR deployment
- Minimal pilot workload
