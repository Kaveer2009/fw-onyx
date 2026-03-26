![Visitors](https://visitor-badge.laobi.icu/badge?page_id=Kaveer2009.fw-onyx&left_text=Visitors) ![Last Updated](https://img.shields.io/github/last-commit/Kaveer2009/fw-onyx?label=Last%20Updated)
# 📱 POCO F7 (Onyx) — Flashable Firmware

**Device:** POCO F7 / Redmi Turbo 4 Pro  
**Codename:** `onyx`

![HyperOS](https://img.shields.io/badge/HyperOS-Firmware-blue?style=for-the-badge&logo=xiaomi)
![Android](https://img.shields.io/badge/Android-15%2F16-green?style=for-the-badge&logo=android)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)

Flashable firmware packages for **POCO F7 / Redmi Turbo 4 Pro (onyx)**.  
Extracted from official releases — for custom ROM users who need updated firmware without flashing the full **MIUI / HyperOS** ROM.

---

## 👤 Credits

Firmware prepared by **[@p_i_a_l99](https://t.me/p_i_a_l99)**  
Thanks for extracting and packaging the firmware.

---

## 📱 Supported Device

| Device | Codename |
|--------|----------|
| POCO F7 / Redmi Turbo 4 Pro | **onyx** |

---

## 📦 Available Firmware

| HyperOS Version | Region | Android Base | Flash Method | Download |
|----------------|--------|--------------|:------------:|----------|
| HyperOS 2.0.204 | Global | Android 15 | Hybrid | [Download](https://github.com/Kaveer2009/fw-onyx/releases/download/Update-firmware-2/FW_ONYX_GLOBAL_OS2.0.204.VOLMIXM.zip) |
| HyperOS 3.0.3 | India | Android 16 | Hybrid | [Download](https://github.com/Kaveer2009/fw-onyx/releases/download/Update-firmware-2/FW_ONYX_INDIA_OS3.0.3.VOLINXM.zip) |
| HyperOS 3.0.5 | Global | Android 16 | Recovery Only | [Download](https://github.com/Kaveer2009/fw-onyx/releases/download/initial-firmware/fw_onyx_global_OS3_0_5_0_WOLMIXM.zip) |
| HyperOS 3.0.6 | Global | Android 16 | Hybrid | [Download](https://github.com/Kaveer2009/fw-onyx/releases/download/Update-firmware-2/FW_ONYX_GLOBAL_OS3.0.6.VOLMIXM.zip) |
| HyperOS 3.0.11 | China | Android 16 | Hybrid | [Download](https://github.com/Kaveer2009/fw-onyx/releases/download/Update-firmware-2/FW_ONYX_CHINA_OS3.0.11.WOLCNXM.zip) |

### 🔀 What is Hybrid Firmware?

> **Hybrid** firmware can be flashed in **two ways**:
> - ✅ **Via Custom Recovery** (OrangeFox / TWRP) — traditional method
> - ✅ **Via Fastboot** — without booting into recovery, using the included script
>
> This gives you flexibility depending on your device state and preferred flashing workflow.

---

## 🛠️ Installation

Choose your preferred flashing method below.

---

### Method 1 — 🔁 Custom Recovery (OrangeFox / TWRP)

> Supported by all firmware versions.

1. Download the desired firmware zip.
2. Boot into **custom recovery** (OrangeFox / TWRP).
3. Flash the firmware zip.
4. Flash your **custom ROM** if required.
5. Reboot to system.

---

### Method 2 — ⚡ Fastboot (Windows / Linux)

> Only supported by **Hybrid** firmware packages.  
> **Prerequisites:** ADB & Fastboot installed, USB debugging enabled, bootloader unlocked.

1. Download the firmware zip.
2. **Extract** the zip to a folder on your PC.
3. Boot your device into **Fastboot mode**:
   ```
   adb reboot bootloader
   ```
4. Connect your device via USB.
5. Run the flash script from inside the extracted folder:

   **Windows:**
   ```bat
   flash_all.bat
   ```

   **Linux / macOS:**
   ```bash
   chmod +x flash_all.sh
   ./flash_all.sh
   ```

6. Wait for all partitions to flash — **do not disconnect** the device.
7. The device will reboot automatically when done.

---

## 💬 Support

For help or issues, join our Telegram support group:

**[👉 Kaveer's Rom Factory Support](https://t.me/KaveerRomFactorySupport)**

---

> ⚠️ **Important**
>
> - Only for **POCO F7 / Redmi Turbo 4 Pro (onyx)**
> - Do **NOT** flash on other devices.
> - Firmware is recommended before flashing newer ROM builds.

---

## 📝 Notes

- Firmware is extracted from official HyperOS builds.
- Safe to flash on custom ROMs.
- Flash only if your ROM requires updated firmware.

---

## ⚖️ Disclaimer

I am **not responsible for bricked devices or data loss**.  
Flash at your own risk.

---

⭐ **If this repo helps you, consider giving it a star!** ⭐
