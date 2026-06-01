# Private Red Spectrum Meter 🌅📱

A private, secure, and lightweight web application built to measure ambient red light dominance in real-time using a smartphone camera. This tool helps identify the peak wavelength intensity during **golden hour** (sunrise and sunset) without tracking user data.

---

## ✨ Features
* **Live Calculations:** Dynamically processes frames to isolate and calculate the percentage of red light dominance.
* **Easy-to-Read UI:** Displays real-time calculations in large, high-visibility text.
* **Rolling Line Graph:** Plots a 30-point live history to track when the spectrum levels out at its highest peak.
* **Audio Alerts:** Built-in text-to-speech engine announces current levels every 15 seconds and alerts you when the spectrum peaks past 45%.
* **100% Private:** Runs entirely client-side inside your browser memory. No tracking scripts, no external servers, and no data collection.

---

## 🛠️ Hardware Limitations & Calibration
Modern smartphone camera lenses use UV-blocking filters and cannot act as ultraviolet light detectors without external hardware attachments. 

However, they excel at capturing the visible light spectrum:
1. **Midday Light (Baseline):** Pointing the app at a white wall during the day should yield an even split of **~30% to 35%** per RGB channel.
2. **Golden Hour (Peak):** As the sun rises or sets, the spectrum shifts drastically. When your meter hits **45% to 50%**, you have hit the peak infrared/red spectrum.

---

## 🚀 How to Use It
1. Open the secure link provided by your GitHub Pages hosting.
2. Tap the bright red **START METER** button to bypass browser security and initialize the engines.
3. Grant the browser temporary permission to use your back camera.
4. Keep your phone screen active while monitoring the live graph or relying on the automated audio readouts!

5. 
