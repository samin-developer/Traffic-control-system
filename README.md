# 🚦 Traffic Control System

A realistic Traffic Signal Control System built using a **Moore State Machine** model. 
The system simulates real-world traffic light behavior with proper state transitions 
and a live countdown timer for each signal phase.

## 🔴 Live Demo
👉 [https://trafficcontrol-sigma.vercel.app/](https://trafficcontrol-sigma.vercel.app/)

## ✨ Features
- 🚥 Realistic traffic signal simulation (RED / YELLOW / GREEN)
- 🔄 Moore State Machine based logic for smooth state transitions
- ⏱️ Live countdown timer for each signal state
- 📊 Current state display (e.g., S0 - RED)
- ⚡ Fast and responsive UI
- ☁️ Deployed on Vercel

## 🧠 How It Works
The system uses a **Moore Machine**, where the output depends only on the current state.
Each state represents a traffic signal condition:

| State | Signal | Description |
|-------|--------|-------------|
| S0    | 🔴 RED | Vehicles stopped |
| S1    | 🟡 YELLOW | Ready to go |
| S2    | 🟢 GREEN | Vehicles moving |

The timer automatically counts down and transitions to the next state.

## 🛠️ Tech Stack
- HTML / CSS / JavaScript
- Moore State Machine Logic
- Vercel (Deployment)

## 🚀 Run Locally
```bash
git clone https://github.com/samin-developer/Traffic-control-system.git
cd Traffic-control-system
# open index.html in browser
