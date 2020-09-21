---
layout: default
title: Software-Konfiguration
nav_order: 4
has_children: true
permalink: /Software-Konfiguration/
---

# Software Konfiguration

## Übersicht
Die Software besteht aus folgenden Komponenten:

- Basis Code in C++
- Hardware API per <Arduino-ESP32 Core>
- Integriertes Echtzeitbetriebssystem im Core (FreeRTOS)
- GUI per GuiSlice Library
- Menübedienung über Touch-Funktion des Displays oder per Eingabe von Buttons und Encoder
- Statusanzeigen über addresierbare RGB-Leds
- Steuerung der weiteren Module des DAB-Radios
---Bluetooth Modul(UART), Sound Prozessor(I2C), Charger-Board(I2C) und Fuel Gauge(I2C)

- inkl. erweiterbare I/O's per Port Expander (MCP23017 - I2C)

## Requirements

[Visual Studio Code](https://mcjohnffs.github.io/Visual%20Studio%20Code%20mit%20Arduino%20(Extension)/){: .btn .btn-purple } oder [Arduino](https://mcjohnffs.github.io/Arduino%20IDE/){: .btn .btn-blue }

