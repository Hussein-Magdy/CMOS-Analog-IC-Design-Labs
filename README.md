# CMOS Analog IC Design Labs & OTA Project

**Author:** Hussein Magdy

This repository contains my practical implementation, simulations, and technical reports for the **CMOS Analog IC Design** track. It highlights foundational analog circuits and features a complete, verified design of a **Two-Stage Miller Operational Transconductance Amplifier (OTA)**.

## 🛠️ Tools & Technologies
* **EDA Tool:** Cadence Virtuoso (ADE XL)
* **Technology Node:** 0.18 um CMOS Process
* **Design Methodology:** gm/ID using the Analog Designer's Toolbox (ADT)

## 📂 Repository Structure
* **Lab 01 - Lab 06 (Fundamentals):** MOSFET characterization, current mirrors, single-stage amplifiers, and differential pairs.
* **Lab 09 (Mini Project 1): Two-Stage Miller OTA**
  * *Open-Loop Analysis:* DC operating point, differential/common-mode gain, CMRR (via XF analysis), and CMIR extraction.
  * *Closed-Loop Analysis:* Unity-gain buffer configuration, STB analysis (Loop Gain & Phase Margin), and Transient Analysis (Slew Rate & Settling Time).

## 📊 Key Performance Results (Two-Stage OTA)

| Parameter | Simulated Result | Target Spec |
| :--- | :--- | :--- |
| **DC Open-Loop Gain** | 68.99 dB | > 66 dB |
| **Gain-Bandwidth Product (GBW)** | 7.329 MHz | > 5.0 MHz |
| **Phase Margin (PM)** | 78.75° | > 70° |
| **CMRR @ DC** | 77.19 dB | > 74 dB |
| **Slew Rate** | 4.542 V/us | ~ 5.0 V/us |

---
*Developed as part of my advanced training and preparation for graduation projects in Analog and Mixed-Signal IC Design.*
