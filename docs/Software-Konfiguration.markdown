---
layout: default
title: 1. Software-Konfiguration
nav_order: 2
permalink: /Software-Konfiguration/
---

# Soft- und Hardware Konfiguration

## Software

- Basis Code in C++ (Arduino)
- Hardware API per <Arduino-ESP32 Core>
- Integriertes Echtzeitbetriebssystem im Core (FreeRTOS)
- GUI per GuiSlice Library

## Hardware

- Menübedienung über Touch-Funktion des Displays oder per Eingabe von Buttons und Encoder
- Statusanzeigen über addresierbare RGB-Leds
- Steuerung der weiteren Module des DAB-Radios
    - Bluetooth Modul(UART)
    - Sound Prozessor(I2C)
    - Charger-Board(I2C)
    - Fuel Gauge(I2C)
- inkl. erweiterbare I/O's per Port Expander (MCP23017 - I2C)
