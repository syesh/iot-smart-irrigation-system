# Smart Plant Monitoring & Precision Irrigation System

An autonomous Internet of Things (IoT) precision plant monitoring and closed-loop irrigation system. Designed for **ESP32** and **NodeMCU ESP8266** platforms, featuring multi-sensor environmental telemetry, intelligent hysteresis-based watering, hardware safety protections, and an interactive web interface.

---

## 📌 Project Overview

Traditional plant watering relies on manual estimation or static timers. Manual watering leads to human error (under-watering or root rot from over-watering), while timer-based systems waste significant water by running even when the soil is already saturated.

This project implements an **autonomous closed-loop IoT irrigation system** that:
1. Continuously monitors soil moisture, ambient temperature, relative humidity, and water reservoir levels.
2. Automatically triggers water delivery only when substrate moisture falls below calibrated thresholds.
3. Incorporates **dual-threshold hysteresis control** to eliminate relay chattering and mechanical wear.
4. Includes **dry-run safety protection** to prevent motor burnout if the water tank is depleted.
5. Provides an interactive live web dashboard and dedicated hardware workbench for real-time monitoring and control.

