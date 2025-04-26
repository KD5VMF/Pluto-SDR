# 🛱 Pluto-SDR Setup Guide

Welcome!  
This guide provides the necessary files and instructions to get your PlutoSDR up and running quickly and easily.

---

## 📂 Files Included:

| File | Description |
|:-----|:------------|
| `baseclock_cpu750_ddr525.tar.gz` | Full SD card image for the PlutoSDR. Copy this to a FAT32-formatted SD card and insert it into the PlutoSDR to boot. |
| `sdrpp_windows_x64.zip` | A ready-to-use Windows SDR program similar to SDR#, but with built-in support for PlutoSDR. Just unzip and run. |
| `PlutoSDR-M2k-USB-Drivers.exe` | Official Analog Devices drivers for PlutoSDR on Windows systems. Required for proper USB connection. |
| `libiio-0.26.ga0eca0d2-setup.exe` | The libiio runtime installer for Windows. Required to allow SDR software to communicate with the PlutoSDR through USB. |

---

## 📋 Installation Instructions:

### 🔹 1. Prepare the PlutoSDR Firmware (Optional but Recommended)

- Format an SD card as **FAT32**.
- Extract the contents of `baseclock_cpu750_ddr525.tar.gz` onto the SD card.
- Insert the SD card into the PlutoSDR and reboot it.
- This loads a stable CPU 750MHz and DDR 525MHz firmware.

---

### 🔹 2. Install the Drivers (Windows Users)

- Run `PlutoSDR-M2k-USB-Drivers.exe` and follow the installation prompts.
- Then run `libiio-0.26.ga0eca0d2-setup.exe` to install the libiio libraries.

✅ After installation, your PlutoSDR should appear properly in Windows Device Manager (under "Universal Serial Bus Devices").

---

### 🔹 3. Install the SDR++ Software (Windows)

- Extract `sdrpp_windows_x64.zip` anywhere on your PC (example: Desktop or Downloads folder).
- Open the extracted folder.
- Run `sdrpp.exe`.

✅ SDR++ will automatically recognize your PlutoSDR as a source.  
✅ You can start tuning, receiving, and listening immediately!

---

## 🔥 Quick Start Tips:

- Set **sample rate** to around **2.5 MSPS** to begin (Pluto handles this well).
- Set **gain** manually if needed (start around 30 dB for FM radio).
- Tune to a known strong FM station (e.g., 103.3 MHz) to verify reception.
- Always connect the PlutoSDR to a **good USB port** directly, not through a cheap hub.

---

## 🚰 Additional Resources:

- Official Analog Devices PlutoSDR Wiki:  
  [https://wiki.analog.com/university/tools/pluto](https://wiki.analog.com/university/tools/pluto)

- SDR++ Official GitHub (latest source and Windows builds):  
  [https://github.com/AlexandreRouma/SDRPlusPlus](https://github.com/AlexandreRouma/SDRPlusPlus)

---

# 🚀 You Are Ready to Explore the Radio Spectrum!

Have fun using your PlutoSDR!  
Feel free to experiment with different antennas, sample rates, and frequencies!

---

# ✨

