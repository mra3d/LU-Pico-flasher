# LU Pico Flasher

**Professional board management and firmware flashing for RP2350 development boards.**

LU Pico Flasher is a Windows desktop utility designed to simplify the preparation, identification, and firmware deployment workflow for supported Raspberry Pi RP2350-based hardware. The application provides a guided experience for connecting boards, selecting the correct target profile, and applying official UF2 firmware packages with minimal manual steps.

Powered by **[Legit Unlocks](https://www.legitunlocks.com/)**.

---

## Overview

Modern microcontroller workflows should be reliable, repeatable, and accessible. LU Pico Flasher focuses on operational clarity:

- Automatic detection of connected boards (BOOTSEL and runtime states)
- Guided flashing through the UF2 mass-storage path
- Built-in tooling bootstrap for required utilities
- Multi-language interface and a clean, enterprise-ready UI
- Serial console visibility for post-flash diagnostics

This project is intended for technicians, engineers, and partners who need a consistent Windows-side companion for RP2350 board preparation.

---

## Supported hardware

Primary targets include common RP2350 boards used in current tooling pipelines:

| Board | Notes |
|-------|--------|
| Waveshare RP2350 USB-A | Recommended host-capable platform |
| Waveshare RP2350 Zero | Compact RP2350 module |
| Pimoroni TINY2350 | Compact RP2350 module |
| Raspberry Pi Pico 2 | Official Raspberry Pi RP2350 board |

Board availability and firmware packages may evolve over time as the ecosystem expands.

---

## Downloads

**Latest release:** [v1.0.0](https://github.com/mra3d/LU-Pico-flasher/releases/tag/v1.0.0)

- Download: [LU-Pico-flasher.zip](https://github.com/mra3d/LU-Pico-flasher/releases/download/v1.0.0/LU-Pico-flasher.zip)
- Platform: Windows 10/11 x64
- Run as Administrator

Please download only from this repository's **Releases** page.

---

## Technology

Built as a native **Windows desktop** product with an enterprise tooling stack:

| Layer | Technology |
|-------|------------|
| Language | **C#** |
| Runtime | **.NET Framework 4.8** |
| UI | **Windows Forms** |
| Architecture | **Windows x64** only |
| Distribution | Standalone protected executable (ZIP release) |

The application integrates standard RP2350 flashing workflows (UF2 mass-storage and related host utilities) behind a guided operator UI.

---

## Getting started

1. Download the latest release for Windows (x64).
2. Run the application.
3. Connect your RP2350 board (BOOTSEL mode when flashing).
4. Select the matching board profile (or Auto where available).
5. Flash the firmware and follow on-screen status messages.

For best results, use a quality USB cable and avoid interrupting power during flash operations.

---

## Acknowledgments

We gratefully acknowledge the researchers, engineers, and open-source contributors whose work makes this tooling ecosystem possible.

### Security research

Special thanks to the **Paradigm Shift** research team for responsible investigation and public technical disclosure of the underlying USB controller research that informed related platform tooling. Their work advanced industry understanding of low-level USB host/device interaction and boot-path analysis.

### Firmware and platform engineering

We also thank **[Paradigm Shift / prdgmshift](https://github.com/prdgmshift/usbliter8)** and contributors to the **usbliter8** project for producing and maintaining the RP2350 UF2 firmware packages used by compatible board workflows. Their engineering effort enables practical deployment across Waveshare, Pimoroni, and Raspberry Pi Pico 2 platforms.

### Ecosystem foundations

Additional appreciation to the broader open hardware community, including the **Raspberry Pi** Pico SDK and **picotool** projects, board vendors, and independent contributors who continue to improve documentation, tooling, and board support.

---

## Brand and community

**Powered by [Legit Unlocks](https://www.legitunlocks.com/)**

Official presence and community updates are available via Legit Unlocks channels.

Thank you for trusting LU Pico Flasher.

---

## Disclaimer

LU Pico Flasher is provided for legitimate board management and firmware flashing purposes on supported RP2350 hardware. Users are responsible for complying with applicable laws, platform policies, and hardware vendor terms. This software and related materials are provided "as is," without warranties of any kind. Legit Unlocks and contributors are not liable for misuse, data loss, hardware damage, or regulatory non-compliance arising from use of this software.

---

## Support

- Website: [https://www.legitunlocks.com/](https://www.legitunlocks.com/)
- Releases: see the **Releases** tab of this repository

---

(c) Legit Unlocks / LU TEAM. All rights reserved.