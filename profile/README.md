# 🧠 Neural Kinetic Sculpture

Welcome to the official GitHub organization for the **Neural Kinetic Sculpture** — an interdisciplinary senior design project combining art, neuroscience, and engineering. Our goal is to create a responsive LED-based kinetic installation that visually and physically reacts to brainwave signals, blending interactive technology with human emotion and motion.

---

## 🚀 Project Overview

The Neural Kinetic Sculpture translates **EEG signals** (with a focus on alpha waves) into real-time control of:

- 💡 **LED illumination**  
- 🔊 **Sound playback**  
- 🕺 **Panel movement**

These elements work in harmony to create a dynamic and immersive experience that responds to neural activity — perfect for installations, performances, and experimental art spaces.

---

## 🔧 Core Components

### 1. **EEG Signal Processing**
- Captured via a **LiveAmp Brain Cap**
- Filtered using a **4th-order Butterworth filter** (Python)
- Focus on **alpha**, **beta**, **delta**, and **theta** bands
- Real-time processing using **Lab Streaming Layer (LSL)**

### 2. **Mobile App (React Native + Supabase)**
- User login/auth via Supabase
- Config interface for mapping EEG ranges to visual/audio effects
- Archived waveform viewer simulating real-time playback
- WIFI communication with hardware controller

### 3. **Embedded System**
- Arduino/microcontroller controls LED brightness and panel motion
- Receives commands via WIFI from the mobile app
- LED intensity and movement speed are mapped from EEG signal strength

### 4. **Cloud Storage**
- Configurations stored and retrieved from Supabase

---

## 🧩 Repositories in this Org

| Repo | Description |
|------|-------------|
| [`control-app`](https://github.com/Neural-Kinetic-Sculpture/control-app) | Mobile app to control configurations, view EEG recordings, and connect via WIFI |
| [`signal-filter`](https://github.com/Neural-Kinetic-Sculpture/signal-filter) | EEG filter with H-Infinity, low/high band pass filtering to filter live EEG signals |
| [`motor-control`](https://github.com/Neural-Kinetic-Sculpture/motor-control) | Motor control to raise or lower panels in the sculpture |
| [`LED-control`](https://github.com/Neural-Kinetic-Sculpture/LED-control) | LED control to change colors and brightness of LEDs in the sculpture |
| [`ESP-NOW`](https://github.com/Neural-Kinetic-Sculpture/ESP-NOW) | WIFI/Bluetooth module to connect and send signals with the mobile app |

---

## 🎯 Goals

- Enable live EEG-driven interactions during performances
- Support pre-recorded EEG playback for rehearsals and demos
- Make neural feedback accessible for creative, therapeutic, or experimental use

---

## 🌐 Future Vision

We're collaborating with dance companies and artistic institutions to showcase the sculpture in live performances — creating new forms of storytelling through brainwave-driven environments.

---

## 🤝 Contributors

This project is being developed by:
- Katrina Viray (https://www.linkedin.com/in/katrina-viray/)
- Carolina Mims
- Letzy Mota
- Ashley Nguyen
- Karina Montero
- Melina Moore
---

## 📬 Contact

Have questions or collaboration ideas?  
