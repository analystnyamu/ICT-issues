# ICT Troubleshooting Guide

Welcome to the **ICT Troubleshooting Repository**! This repository contains helpful resources and guides on how to troubleshoot common computer issues, including steps to follow when your computer fails to boot.

## Table of Contents

- [Overview](#overview)
- [Troubleshooting Guides](#troubleshooting-guides)
  - [1. Computer Fails to Boot](#1-computer-fails-to-boot)
  - [2. Safe Mode Access](#2-safe-mode-access)
  - [3. Backing Up Data via Command Prompt](#3-backing-up-data-via-command-prompt)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

This repository provides step-by-step guides for resolving various computer issues. Whether you're experiencing a boot failure, data corruption, or need to back up important files using the **Command Prompt**, we've got you covered!

## Troubleshooting Guides

### 1. Computer Fails to Boot

If your computer doesn't boot normally, follow these steps to resolve the issue:

- **Force Shutdown & Restart**:
  1. Press and hold the **power button** for 10 seconds to force shutdown.
  2. Try restarting your computer 2-3 times.
  3. If it still doesn't boot, follow the steps below to access **Advanced Startup Options**.

- **Accessing Advanced Startup Options**:
  1. On startup, hold the **Shift** key and press **Restart**.
  2. Navigate to **Troubleshoot > Advanced Options**.
  3. From here, you can try repairing Windows, booting in Safe Mode, or using the Command Prompt.

- **Additional Steps**:
  - Try resetting the BIOS by pressing **F2** or **DEL** during startup.
  - Check if your boot drive is detected in BIOS.
  - Use a Windows installation media to attempt startup repair.

### 2. Safe Mode Access

Safe Mode is useful when your system won’t start normally. Here's how to access it:

- **Boot into Safe Mode**:
  1. Press **Shift + Restart** from the login screen.
  2. Go to **Troubleshoot > Advanced Options > Startup Settings > Restart**.
  3. After reboot, press **F4** to enter **Safe Mode** or **F5** for Safe Mode with Networking.

- **Use Safe Mode for Troubleshooting**:
  - Uninstall problematic software or drivers.
  - Run antivirus scans in Safe Mode.
  - Roll back recent changes or restore from a restore point.

### 3. Backing Up Data via Command Prompt

If your computer won’t boot and you need to back up critical files, you can do so using **Command Prompt** in recovery mode:

- **Accessing Command Prompt**:
  1. From **Advanced Startup Options**, select **Command Prompt**.
  2. Connect an external USB drive or hard drive.
  
- **Backup Commands**:
  - Use `xcopy` to back up your Desktop,
  
## View the document in different formats

[Read as html format](index.html)
