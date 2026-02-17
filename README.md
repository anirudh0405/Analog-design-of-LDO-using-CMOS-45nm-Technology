# Analog-design-of-LDO-using-CMOS-45nm-Technology
# 🔋 Analog Design of Low Dropout Regulator (LDO) in 45nm CMOS

## 📌 Project Overview

This project presents the complete analog IC design flow of a PMOS-based Low Dropout Regulator (LDO) implemented in 45nm CMOS technology using Cadence Virtuoso.

The work includes:
- Schematic design
- DC & Transient simulation
- Layout implementation
- DRC verification
- LVS verification
- Parasitic RC extraction (Quantus)
- Post-layout validation

---

## 🎯 Key Specifications

- Technology: 45nm CMOS
- Output Voltage: 2.45 V
- Load Current: ~49 µA
- PSRR: 13.62 dB
- Architecture: PMOS Pass Transistor
- Compensation: Internal Miller Compensation

---

## 🧠 Architecture

- Reference Voltage Generator
- Folded Cascode Error Amplifier
- PMOS Pass Transistor
- Feedback Divider
- Internal Compensation Network

---

# 📊 Simulation Results

## 1️⃣ Transient Response

- Smooth startup
- No overshoot
- Stable settling
- Capacitor-less stability verified

Output settles at ≈ 2.45 V.

---

## 2️⃣ DC Sweep Analysis

- Correct dropout behavior
- Stable regulation after Vin > Vout + Vdrop
- Smooth transition from dropout to regulation region

---

## 3️⃣ PSRR Calculation

PSRR = 20 log (VR_supply / VR_out)

Calculated PSRR = 13.62 dB

---

# 🧱 Physical Verification

## ✅ DRC
- Zero violations

## ✅ LVS
- Layout matches schematic

## ✅ RC Extraction
- Quantus extraction completed
- Post-layout simulations stable

---

# 🛠 Tools Used

- Cadence Virtuoso
- Spectre Simulator
- ADE
- Assura DRC/LVS
- Quantus QRC

---

# 📈 Applications

- SoC Power Management
- IoT Devices
- RF Blocks
- Mixed-Signal ICs
