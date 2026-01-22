# ⚙️ Intel 8086 Microsystem

This project builds a complete **Intel 8086-based microsystem**, combining external **memory**, classic **I/O peripherals**, and **8086 assembly** drivers to control real devices (serial + parallel I/O, keypad, LEDs, 7-seg).

---

## ✨ Highlights

- 🧠 **Intel 8086** CPU-based microsystem (full bus + control logic)
- 🧩 **External memory** (EPROM/SRAM) with **address decoding**
- 🔌 **Serial communication** via **8251 USART**
- 🎛️ **Parallel I/O** via **8255 PPI**
- ⌨️ **Keypad input** + 💡 **LED output**
- 🔢 **6-digit 7-segment display** driving (multiplexed / port-controlled)
- 🧾 **8086 assembly subroutines** for init + read/write routines

---

## 🧱 Hardware Overview

- ⏱️ Clock / reset support (classic 8086 microsystem approach)
- 🧷 Address/data **demultiplexing** + buffering for stable buses
- 🗺️ Memory + I/O **mapping** (documented in the project report)
- 🔁 Peripheral interfacing through dedicated control lines and ports

---

## 🧪 Software (8086 Assembly)

- 🟦 **Peripheral initialization** (USART / PPI)
- 🔤 **Serial TX/RX** routines (send/receive characters)
- 📤 **Parallel output** routines
- ⌨️ **Keypad scan** + debounce-style handling
- 💡 **LED control** (on/off patterns)
- 🔢 **7-segment display** routines (show digits / hex)

---

## 🛠 Tools & Tech

- 🧾 **8086 Assembly**
- 🧩 Classic support ICs: **8251**, **8255** (and standard bus logic)
- 🧰 Schematic design tool (project schematic included)
- 📄 Documentation: memory/I/O map + usage details in the report

---

## 📁 Repository Structure (example)

- `docs/` 📄 report, memory map, notes
- `hardware/` 🔌 schematic / diagrams
- `asm/` 🧾 source code (drivers + demos)

---

## 🚀 Getting Started

1. 📥 Clone the repo  
2. 📄 Read `docs/` for the memory/I/O map and peripheral configuration  
3. 🧾 Explore `asm/` for driver routines and demo programs  
4. 🧪 Run demos to test: serial I/O, parallel I/O, keypad, LEDs, 7-seg

---

## 📌 Notes

This is an educational hardware/software integration project focused on:
**bus interfacing**, **memory decoding**, **peripheral programming**, and **low-level I/O control** using the Intel 8086 ecosystem.

---
