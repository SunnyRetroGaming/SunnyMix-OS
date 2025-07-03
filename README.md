# SunnyMix-OS – TrimUI Brick Port

Welcome to **SunnyMix-OS** – the open-source community port of CrossMix OS, especially for the TrimUI Brick!

---

## Status

⚠️ **Work in Progress!**  
SunnyMix-OS is still in the testing and development phase.  
I am currently testing, tweaking, and fixing the port on my own TrimUI Brick.  
It will still take some time before I consider the port “ready” for everyone.  
Feel free to follow my progress or test along, but please expect bugs and unfinished features for now!

---

## Motivation

Hi, I’m a retiree and long-time retro gaming fan.  
I want to get the very best out of my “modern Gameboy” (the TrimUI Brick) and learn more about open-source handheld software.  
For me, sharing and improving together with the community is the true spirit of open source – and that’s why I’m building this project in public.

---

## About this project

**SunnyMix-OS** is a dedicated, customized port of CrossMix OS for the TrimUI Brick, tuned for the hardware, the 1024x768 display, and classic button layout (no analog stick).

**Note:**  
There is **no support** for the TrimUI Smart Pro in this project.  
If you have a Smart Pro, please use the [original CrossMix OS project](https://github.com/cizia64/CrossMix-OS).

---

## Features

- Optimized for the TrimUI Brick’s 3.2" 1024x768 IPS display
- Classic button mapping: D-Pad + ABXY + Start/Select (**no analog stick**)
- Adapted system scripts and RetroArch configurations for the Brick
- Includes relevant bug fixes and improvements from OG firmware and CrossMix OS
- Features tweaked or removed if not available or meaningful on the Brick

---

## Installation

**Important:**  
SunnyMix-OS is designed for the TrimUI Brick only.  
Follow these steps carefully to avoid data loss or device issues!

### 1. Prepare your SD card

- **Backup your games, BIOS, and save files!**
- **Format your SD card to FAT32:**  
  - On Windows: Use the “SD Card Formatter” tool or “GUIformat” for cards larger than 32GB  
  - On macOS: Use “Disk Utility” → “MS-DOS (FAT)”  
  - On Linux: Use `mkfs.fat -F32 /dev/sdX`

### 2. Copy SunnyMix-OS files

- Download the latest **SunnyMix-OS** release from GitHub.
- Extract the ZIP archive (if needed).
- Copy **all files and folders** from the SunnyMix-OS package to the root of your empty, freshly formatted SD card.

### 3. Add your games, BIOS, and saves

- Copy your ROMs, BIOS files, and savegames (if needed) into the appropriate folders on the SD card.

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

- **No support for TrimUI Smart Pro**
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

