# TDA2822-Bridge-Mode-Stereo-Audio-Amplifier-Module
Compact 5V USB-powered bridge stereo audio amplifier module based on the  TDA2822.

<img width="517" height="550" alt="image" src="https://github.com/user-attachments/assets/bbb5b7a7-8afc-472e-bc0d-ced42da1dbd0" />

---

## Overview

This project implements a compact low-voltage stereo audio amplifier designed for portable, educational, and embedded audio applications.

The amplifier is based on two TDA2822 audio amplifier ICs configured in bridge-tied load (BTL) mode, allowing increased output power while operating from a single 5V supply.

Audio signals are received through a stereo audio jack, adjusted using independent volume controls, and amplified to directly drive low-impedance speakers.

The module is powered from a standard USB Type-C connector and requires no additional power supply circuitry.

---

## Features

- USB Type-C powered (5V)
- Stereo audio amplification
- Bridge-Tied Load (BTL) configuration
- Dual TDA2822 amplifier ICs
- Independent left and right channel volume control
- Direct speaker drive capability
- Power status LED
- Compact PCB design
- Low component count
- Suitable for portable audio applications

---

## Applications

- USB-powered speaker systems
- Desktop audio amplifiers
- DIY speaker projects
- Educational audio electronics
- Portable audio devices
- Embedded systems audio output
- Analog circuit demonstrations

---

## Technical Specifications

| Parameter | Value |
|------------|------------|
| Supply Voltage | 5V USB |
| Quiescent Current | ~25 mA |
| Output Power (per channel) | ~0.35 W |
| Recommended Speaker Impedance | 4 Ω – 8 Ω |
| Closed-Loop Gain | 39 dB Typical |
| THD | 0.2% Typical |
| Input Resistance | 100 kΩ |
| PCB Dimensions | 50 mm × 50 mm |

---

## System Architecture

<img width="772" height="315" alt="image" src="https://github.com/user-attachments/assets/63a5d6c9-6cd5-4469-a79b-22e3727347ee" />

---

## Design Highlights

### Bridge-Tied Load (BTL) Operation

Each audio channel operates in bridge mode.

Benefits include:

- Increased output power
- Larger output voltage swing
- Elimination of output coupling capacitors
- Better utilization of the 5V supply

### Independent Channel Control

The left and right channels include individual trimmer potentiometers for:

- Volume adjustment
- Channel balancing
- Prototype flexibility

### USB-Powered Design

The amplifier is powered directly from a USB Type-C connector.

Advantages:

- Universal power source
- Portable operation
- Easy integration with power banks

---

## Main Components

| Component | Function |
|------------|------------|
| TDA2822 | Audio amplifier |
| 3386P Trimmers | Volume control |
| Audio Jack | Stereo input |
| USB Type-C | Power input |
| LED Indicator | Power status |

---

## Hardware Images

### 3D

<img width="418" height="480" alt="image" src="https://github.com/user-attachments/assets/598d477e-d049-43ac-abf3-246a652f35db" />

### PCB Top Side

<img width="426" height="464" alt="image" src="https://github.com/user-attachments/assets/f3c4875d-9043-42d5-9531-0b3ac50e7f32" />

---

## Electrical Characteristics

| Parameter | Min | Typ | Max |
|------------|------------|------------|------------|
| Supply Voltage | 4.5V | 5.0V | 5.5V |
| Output Power (per channel) | — | 0.35W | — |
| Load Impedance | 4Ω | — | 8Ω |
| Voltage Gain | 36dB | 39dB | 41dB |
| THD | — | 0.2% | — |

---
