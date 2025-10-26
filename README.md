# 🪟 Windows PE Custom Build

A lightweight, customized Windows Preinstallation Environment (WinPE) with various built-in tools and features for system maintenance, recovery, and deployment.

---

## 📦 Download

You can download the current build here:

🔗 **[Download from Mega.nz](https://mega.nz/folder/qVklkQaA#3SsqJ5FvnddSI_mypIPDhQ)**

---

## 💿 How to Create a Bootable USB

Follow these steps carefully to prepare your USB drive and use this WinPE build:

1. **Prepare your USB drive**
   - Use a **FAT32-formatted** USB drive.
   - The drive must be **less than 32 GB** in size.
   - Ensure it’s empty before proceeding (this process overwrites existing data).

2. **Copy the WinPE files**
   - Download and extract the archive from the link above.
   - Inside the extracted folder, find the `Media` directory.
   - **Copy everything under the `Media` folder** directly to the **root** of your USB drive.

   Example:
   USB_DRIVE:
    ├── boot
    ├── sources
    ├── EFI
    ├── bootmgr
    └── bootmgr.efi

3. **Boot from USB**
- Insert the USB drive into your target PC.
- Boot from the USB (use BIOS/UEFI boot menu).
- WinPE will start automatically.

---

## 🪄 Usage

Once booted into the environment:

- Press the **Windows key** on your keyboard.
- Navigate through the available tools via the **Start menu** and **dropdown menus**.
- Explore included utilities for recovery, diagnostics, and deployment.

---

## ⚠️ Notes and Disclaimer

- This project is provided **as-is** for educational and testing purposes.  
- **Do not redistribute** Microsoft binaries or files separately — users must build or download from official sources when possible.  
- I am not affiliated with Microsoft. Windows and WinPE are trademarks of Microsoft Corporation.  
- Use at your own risk.

---

## 🧰 Build Information

This repository contains:
- Scripts and configuration files used to build this WinPE image.
- Documentation for customization and usage.
- External link to prebuilt binaries (for convenience).

---

## 📝 License

This project’s source code and scripts are released under the [MIT License].

---

**Author:** *Timothy Y*  
**Version:** 0.1.0
**Repository:** [[https://github.com/yourusername/your-repo-name](https://github.com/Timothy099qw/TPE-ARM-64/)]([https://github.com/yourusername/your-repo-name](https://github.com/Timothy099qw/TPE-ARM-64/))

---

⭐ If you find this project useful, consider giving it a star on GitHub!
