# Abb Night Watch 🌌

A highly stylized, sci-fi/Tek-themed web application designed to track in-game surface safe times and cycles for **ARK: Aberration**. 

Whether you're braving the surface for Blue/Red drops, farming element ore, or hunting surface reapers, this tool helps you keep precise track of when the surface is safe or burning.

---

## 🚀 Features

* **Cycle Calculation Math:** Automatically calculates surface schedules based on the last digit of your in-game day:
  * **Digits 0–3:** 50% Day / 50% Night
  * **Digits 4–6:** 90% Day / 10% Night
  * **Digits 7–9:** 10% Day / 90% Night (Optimal Yield)
* **Real-World Countdowns:** Dynamic, real-time countdowns that sync instantly with your current server time and custom day length configurations.
* **Immersive Aberration Aesthetic:** Built with a dark Tek terminal interface, complete with glowing bio-cyan accents, scanline styling, and animated pixel-art waterfalls and floating spores.
* **Lightweight & Mobile-Friendly:** Contained entirely within a single, fast-loading file designed to look and work great on both desktop and mobile web browsers.

---

## 🕹️ How to Use

1. Open the tracker in any web browser (or via your live GitHub Pages link).
2. Enter your current **Initial In-Game Day** (e.g., `17541`).
3. Enter your current **Initial In-Game Time** in `HH:MM` format (the colon will auto-format as you type).
4. Click **Initiate Sync** to launch the holographic display panel and live countdown timers!

---

## ⚙️ Configuration

If your unofficial server runs on a custom day/night speed, you can easily adjust the speed variable directly inside the `<script>` tag of the HTML file:
```javascript
const REAL_MINUTES_PER_DAY = 60; // Adjust to match your specific server settings
