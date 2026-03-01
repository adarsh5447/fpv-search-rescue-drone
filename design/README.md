# 📐 Design Overview – Search & Rescue FPV Drone

This section explains the engineering design decisions and structural planning behind the development of the FPV Search & Rescue Drone.

---

## 🎯 Design Objective

The drone was designed to:

- Operate in confined and obstructed environments
- Provide uninterrupted real-time analog video
- Maintain high maneuverability
- Ensure structural durability
- Support long-range communication

---

## 🧩 Structural Design

The drone uses a 3.5-inch carbon fiber frame optimized for:

- Lightweight construction
- High structural strength
- Minimal vibration transmission
- Compact footprint for narrow entry spaces

Component placement was arranged to:

- Maintain proper center of gravity
- Reduce vibration on flight controller
- Improve flight stability
- Protect electronics during impact

---

## ⚙️ Propulsion Design Strategy

The selection of 2400KV brushless motors with a 6S LiPo battery ensures:

- High thrust-to-weight ratio
- Rapid throttle response
- Stable hover performance
- Efficient power distribution

The motor-to-frame ratio was optimized for agility rather than heavy payload.

---

## 🎥 Analog FPV Transmission Design

Analog transmission was intentionally selected over digital systems because:

- Lower latency
- Reduced video freezing
- Better signal behavior in obstructed environments
- More reliable in disaster scenarios

The AKK A1819 VTX with adjustable power allows:

- Power optimization for different range requirements
- Battery conservation when high power is not needed

---

## 🔋 Power Distribution Design

The 6S 22.2V LiPo system provides:

- High discharge capability (up to 130C)
- Stable voltage during aggressive maneuvers
- Efficient energy delivery to ESC and motors

Battery placement was centered to maintain balance and flight symmetry.

---

## 👓 Ground System Design

The Eachine EV800 goggles were selected because:

- Reliable 5.8GHz analog reception
- Built-in diversity for better signal stability
- Low-latency immersive viewing
- Field deployable and easy to operate

---

## 🛡 Safety & Reliability Considerations

- Proper motor mounting to reduce vibration
- Secure wiring to prevent signal interruption
- Failsafe configuration for signal loss
- Durable frame for crash resistance

---

## 🚀 Design Philosophy

The overall design prioritizes:

- Reliability over complexity
- Low latency over high-definition video
- Stability over excessive speed
- Practical SAR functionality over racing performance
