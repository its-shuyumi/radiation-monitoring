<div align="center">

# ☢️ Radiation Monitor Dashboard

[![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-yellow?style=flat-square&logo=javascript)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![HTML5](https://img.shields.io/badge/HTML5-Canvas-orange?style=flat-square&logo=html5)](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/canvas)
[![CSS3](https://img.shields.io/badge/CSS3-Glassmorphism-blue?style=flat-square&logo=css3)](https://developer.mozilla.org/en-وس/docs/Web/CSS)
[![Status](https://img.shields.io/badge/Status-Archived%2Fsandbox-orange?style=flat-square)]()

*Frontend interface originally designed for an Arduino + ESP32 Geiger counter hardware setup.*  
*Веб-интерфейс, разрабатывавшийся под аппаратную связку счётчика Гейгера на базе Arduino и ESP32.*

[English](#-english) • [Русский](#-русский)

</div>

---

## 🇺🇸 English

### 📌 Background
This frontend part is designed to visualize real encrypted data on the radiation background coming from a UAV equipped with a Geiger counter via an ESP32 microcontroller. 

The interface was created by me in Figma and brought to a working state with data simulation, custom charts on Canvas, and Dark Glassmorphism UI.

### ✨ Features
- **Dark Glassmorphism UI:** Translucent panel layout with procedural SVG noise and dynamic glow.
- **Dynamic Gauge & Chart:** Custom HTML5 Canvas components for real-time dose indication and 60-second temporal trend analysis.
- **Simulation Mode:** Currently utilizes a local random walk generator to mimic hardware telemetry input.

---

## 🇷🇺 Русский

### 📌 Предыстория
Этот фронтенд-часть для визуализации реальных шифрованных данных радиационного фона, поступающих со БПЛА с счётчиком Гейгера через микроконтроллер ESP32. 

Интерфейс был создан мной в Figma и доведён до рабочего состояния с симуляцией данных, кастомными графиками на Canvas и эстетикой Dark Glassmorphism.

### ✨ Особенности
- **Дизайн Dark Glassmorphism:** Полупрозрачная панель с размытием, процедурным SVG-шумом и динамической подсветкой.
- **Интерактивные элементы (Canvas):** Самописные компоненты шкалы текущей дозы и графика динамики за последние 60 секунд.
- **Режим симуляции:** В текущей версии скрипт генерирует тестовые потоки данных для демонстрации интерфейса без физического железа.
---
