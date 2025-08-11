# 🧊 Cubiron — DIY Tiny FDM 3D Printer (70x70x70mm)

Cubiron is a fully DIY, ultra-compact FDM 3D printer designed for low-cost building, small-format printing, and hands-on learning. It's built entirely from open-source parts and the cheapest components available, using custom printable mechanics and Klipper firmware.

![Cubiron](images/cubiron_final_cad.jpg)

---

## 🔧 Features

- 🧠 **Klipper firmware** on a **Raspberry Pi Zero 2W**
- 🦾 **MGN9C 100mm rails** on all axes
- 🔥 **Bambu clone hotend** + **Hummingbird extruder** (HGX-Lite)
- ⚙️ **Handmade 3mm 2GT belts**
- 🧊 **Cold print bed** (mechanically attached)
- 🧰 **Mellow Fly Micro4** + **NEMA 14 steppers**
- 🔌 Powered via **USB-C PD — 20V, 100W** input
- 💡 **PLA-only** design for simplicity
- 📐 Includes **CAD files, BOM, STLs, printer.cfg**, and **slicer profiles**

---

## 📦 Included in this Repo

| Folder/File       | Description                           |
|-------------------|---------------------------------------|
| `CAD/`            | Source and STEP files                 |
| `STLs/`           | Printable parts                       |
| `firmware/`       | Klipper configuration (`printer.cfg`) |
| `slicer/`         | Slicer profile for PLA                |
| `docs/`           | Build manual, wiring diagrams, etc.   |
| `BOM.md`          | Bill of materials                     |
| `LICENSE`         | CERN-OHL-S v2 license                 |
| `README.md`       | You're here!                          |

---

## 🛠 Specifications

| Feature        | Value                          |
|----------------|--------------------------------|
| Build Volume   | 70 × 70 × 70 mm                |
| Motion System  | MGN9C 100mm rails              |
| Drive Belts    | 2GT 3mm wide                   |
| Extruder       | Hummingbird w/ HGX-Lite parts  |
| Hotend         | BambuLab clone hotend          |
| Board          | Mellow Fly Micro4              |
| SBC            | Raspberry Pi Zero 2W           |
| Filament       | PLA only                       |
| Print Bed      | Cold, mechanical mount         |
| Firmware       | Klipper                        |
| Power Supply   | USB-C PD 20V 100W              |

---

## 🚧 Getting Started

0. **Read the "Printing Guidelines" section in the build guide!**
1. **3D print the STLs** in `STLs/`
2. **Follow the build guide** in `docs/build_manual.pdf`
3. **Flash Klipper** on your Pi Zero 2W
4. **Upload `printer.cfg`** and tune as needed
5. **Slice using the included profile** in `slicer/`


---

## 🙏 Acknowledgements

- Inspired by the DIY 3D printing community
- Thanks to the creators of Klipper, Hummingbird, and open hardware pioneers

---

## 💬 Contribute

This is a passion project — feedback, pull requests, remixes, and improvements are welcome!

---

## 🧾 License

Cubiron is licensed under the **CERN-OHL-S v2** license.

> This means you can use, modify, build, and sell it — but you must share changes under the same license.

📄 [License Overview](LICENSE-OVERVIEW.md)  
📜 [Full License Text](LICENSE)

[![License: CERN-OHL-S v2](https://img.shields.io/badge/License-CERN--OHL--S%202.0-blue.svg)](https://ohwr.org/cern_ohl)
