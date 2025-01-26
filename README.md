# over-hackintosh

## Getting Started

Welcome to **over-hackintosh**, a Hackintosh setup designed for AMD Ryzen systems! This repository is tailored for users who want to run macOS on a system with a Ryzen 5 5600, Radeon RX 6700 XT,Follow the steps below to set up your Hackintosh environment and enjoy a seamless macOS experience.

## Hardware Specifications

Here’s a quick rundown of the hardware I used for this Hackintosh build:

- **CPU**: AMD Ryzen 5 5600
- **GPU**: Radeon RX 6700 XT
- **LAN**: Realtek LAN network card
- **Power Supply**: Corsair CV 550
- **Motherboard**: Gigabyte A520M DS3H
- **PC Case**: Krux Vortex
- **CPU Cooler**: Endorfy Spartan 5 Max

---

## Project Overview

**over-hackintosh** is a Hackintosh guide and EFI setup designed for users with AMD Ryzen CPUs and Radeon GPUs. The project provides all necessary files, kexts, and configuration settings to run macOS on compatible hardware.

### Features

- **OpenCore EFI configuration** for AMD Ryzen 5 5600 and Radeon RX 6700 XT.
- Support for **Realtek LAN** and other peripherals.
- Full installation guide for **macOS** on AMD hardware.
- Detailed troubleshooting tips for common issues.

---

## Requirements

Before starting, make sure you have the following:

- **Compatible hardware**: As listed above (Ryzen 5 5600, RX 6700 XT, etc.)
- **A USB drive** (16GB or larger)
- **macOS installation files** (downloaded from the Mac App Store)
- **OpenCore bootloader** (provided in this repository)

---

## Installation Guide

1. **Prepare your USB drive**:
   - Download the macOS installer from the Mac App Store.
   - Use **OpenCore** or **Clover** to create a bootable USB drive.

2. **Configure OpenCore EFI**:
   - Download the OpenCore EFI folder from this repository and copy it to your USB drive.

3. **Download MacOS image**
   - Use the MacOS download section from the [Dortania guide](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/windows-install.html#downloading-macos)   

4. **Boot from USB**:
   - Insert the USB drive into your Hackintosh.
   - Boot from the USB drive and follow the installation steps.

5. **Post-installation**:
   - After installation, make sure to run post-installation scripts (if provided) to apply necessary patches and configuration changes.

---

## Usage

After installation, you should be able to boot macOS on your system with full GPU acceleration, networking support, and more.

You can update OpenCore and EFI configurations as new macOS updates are released. For AMD-specific tweaks and patches, refer to the troubleshooting section.

---

## Support

For assistance, please raise an issue on this repository or contact **wiktator.olszewski@gmail.com**.

---

## Roadmap

- Support for newer versions of **macOS (New versions if any come out)**.
- Further optimizations for **Radeon** graphics.
- Improve compatibility with additional **AMD Ryzen CPUs**.

---

## Contributing

I welcome contributions! If you want to help improve this project, please follow these steps:

1. Fork this repository.
2. Create a branch and make your changes.
3. Submit a pull request with a detailed explanation of what was changed.

Make sure your changes do not break the existing Hackintosh setup.

---

## Authors and Acknowledgments

- **overspend**: Creator of the over-hackintosh project and AMD Ryzen Hackintosh enthusiast.
- Special thanks to the **OpenCore** project and the **Hackintosh community** for continuous support and contributions.

---

## License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

---

## Project Status

Development is ongoing! The Hackintosh community is always evolving, so expect continuous updates as new macOS versions are released and new patches are required.

---

Feel free to make changes as necessary to match your setup more closely! Let me know if you'd like to expand on any sections.
