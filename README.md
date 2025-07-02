# SunnyMix-OS – TrimUI Brick Port

Welcome to **SunnyMix-OS** – the open-source community port of CrossMix OS, specially tailored for the TrimUI Brick!

---

## Motivation

Recently, some companies have been selling commercial Brick ports based on the free and open-source CrossMix OS, bundled exclusively with expensive SD cards.  
I believe software like CrossMix OS should stay **free and open**—so everyone can enjoy and benefit from it.

With **SunnyMix-OS**, my goal is to ensure all Brick owners have access to a transparent, cost-free, and community-driven version, with no hidden costs or restrictions.

Development on the original project has unfortunately slowed since commercial versions started circulating.  
With this open-source port, I want to help keep the community active and independent!

---

## About this project

**SunnyMix-OS** is a dedicated, customized port of CrossMix OS for the TrimUI Brick, specifically tuned for the hardware, 1024x768 display, and classic button layout (no analog stick) of the Brick.

**Note:**  
There is **no support** for the TrimUI Smart Pro in this project.  
If you have a Smart Pro, please use the [original CrossMix OS project](https://github.com/cizia64/CrossMix-OS).

---

## Features

- Fully optimized for the TrimUI Brick’s 3.2" 1024x768 IPS display
- Classic button mapping: D-Pad + ABXY + Start/Select (**no analog stick**)
- Adapted system scripts and RetroArch configurations for the Brick
- Includes relevant bug fixes and improvements from OG Firmware 1.1.0 and CrossMix OS
- Features removed or tweaked if not available or meaningful on the Brick

---

## Installation

**Important:**  
SunnyMix-OS is designed for the TrimUI Brick only.  
Follow these steps carefully to avoid data loss or device issues!

### 1. Prepare your SD card

- **Backup your games, BIOS, and save files!**  
  If you have personal files (like ROMs, BIOS, or savegames) from your previous setup, copy them to your computer for safekeeping.
- **Format your SD card to FAT32:**  
  The SD card **must be formatted as FAT32** for the TrimUI Brick to work correctly.  
  - On Windows: Use the “SD Card Formatter” tool or “GUIformat” for cards larger than 32GB  
  - On macOS: Use “Disk Utility” → “MS-DOS (FAT)”  
  - On Linux: Use `mkfs.fat -F32 /dev/sdX`

### 2. Copy SunnyMix-OS files

- Download the latest **SunnyMix-OS** release from GitHub.
- Extract the ZIP archive (if needed).
- Copy **all files and folders** from the SunnyMix-OS package to the root of your empty, freshly formatted SD card.

### 3. Add your games, BIOS, and saves

- Copy your ROMs, BIOS files, and savegames (if needed) into the appropriate folders on the SD card, just as you did previously.

### 4. Eject and insert the SD card

- Safely eject the SD card from your computer.
- Insert the SD card into your TrimUI Brick.

### 5. First boot

- Turn on your TrimUI Brick.
- SunnyMix-OS will start automatically.
- The first boot may take a little longer as settings and files are initialized.

---

**Tip:**  
If something goes wrong (e.g., black screen, no boot):
- Reformat the SD card and start the installation again from scratch.
- Make sure all files were copied correctly and that the SD card is really FAT32.

---

**Warning:**  
SunnyMix-OS **is only for TrimUI Brick** – do not install it on other devices!  
All installation is at your own risk.

---

## Known differences & notes

- **No support for TrimUI Smart Pro!**
- No analog stick support
- Display resolution and controls fully adapted to the Brick
- Features or fixes from OG firmware were only merged if relevant and compatible with CrossMix OS  
  (See details in [CHANGES.md](CHANGES.md))

---

## Issues & Feedback

If you encounter any problems, **please open an issue** on GitHub.  
The more details you provide, the faster we can resolve it!

---

## Acknowledgments

- [cizia64/CrossMix-OS](https://github.com/cizia64/CrossMix-OS) – original project and inspiration
- The TrimUI community for feedback and support

---

## License

This project uses the same license as the original CrossMix OS (see [LICENSE](LICENSE) or [CrossMix OS GitHub](https://github.com/cizia64/CrossMix-OS)).

---
