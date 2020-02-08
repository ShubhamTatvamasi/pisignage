# pisignage

1. [Purchase the Hardware](#1-purchase-the-hardware)
1. [Download piplayer Image](#2-download-piplayer-image)
1. [Install](#3-install)
1. [login to piplayer](#4-login-to-piplayer)


### 1. Purchase the Hardware

The following are the suggested components needed to assemble the piSignage Player.

1. Raspberry Pi model 3 (recommended although others models are supported)
1. USB power supply with micro USB cable (with 2A capacity, TV USB power may not be sufficient)
1. Class 10, 8GB+ microSD card from reputed vendor
1. Good quality HDMI cable (CEC supported)
1. LAN cable or Pi compatible USB wi-fi adapters if wifi is not built-in

**Buy:** Pi 4 1GB Starter Kit - 32GB - $79.95

https://www.canakit.com/raspberry-pi-4-starter-kit.html

Reference: https://pisignage.com/homepage/documentation.html

---
### 2. Download piplayer Image

https://pisignage.s3.amazonaws.com/pisignage-images/pisignage_2.6.1.img.zip

Reference: https://github.com/colloqi/pisignage

---
### 3. Install

- **For Mac**

  check the disk drive you want to install in using:
  ```bash
  diskutil list
  ```
  > connect your sd card before checking drives

  rip image to SD card:
  ```bash
  sudo dd bs=1m if=pisignage_2.6.1.img of=/dev/disk2
  ```

- **For Windows**

  Use [Win32DiskImager](http://sourceforge.net/projects/win32diskimager/) utility in administator mode.

---

### 4. login to piplayer

Search for the piplayer on your Wifi network, then connect with it.

Wifi Pass: piplayer

Browser http://192.168.100.1:8000/

ID: pi

Pass: pi

