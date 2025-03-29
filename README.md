# BurpSuitePro v2025

## Overview

![overview](https://github.com/Wael-Rd/BurpsuitePRO2025/blob/main/overview.png?raw=true)

[Official Overview](https://portswigger.net/burp/pro)

---

## Installation Guide

### For Linux/MacOS:

1. **Make the installation script executable**:
   ```sh
   chmod +x install.sh
   ```

2. **Run the installation script**:
   ```sh
   ./install.sh
   ```

3. **Start Burp Suite**:
   ```sh
   burpsuitepro
   ```

4. **Set the default Java version** (if necessary):
   ```sh
   sudo update-alternatives --config java
   ```

   > **Note:** Copy the license key from the loader and follow these steps:
   > - Navigate to `Burp Suite > Manual Activation`.
   > - Copy the Burp Suite request key to the loader request field.
   > - Paste the response key from the loader into Burp Suite.

---

### For Windows:

1. **Prepare the Directory:**
   - Create a folder named `Burp` in the `C:\` drive for easier access.

2. **Download Required Files:**
   - Download [install.ps1](https://github.com/Wael-Rd/BurpsuitePRO2025/blob/main/install.ps1) and extract its contents into `C:\Burp`.

3. **Set Script Execution Policy:**
   - Open `PowerShell` as an administrator and execute:
     ```sh
     Set-ExecutionPolicy -ExecutionPolicy Bypass -Scope Process
     ```

4. **Navigate to the Directory:**
   ```sh
   cd C:\Burp
   ```

5. **Execute the Installation Script:**
   ```sh
   ./install.ps1
   ```

6. **Verify the Loader Placement:**
   - Ensure the `loader` file is located in the `C:\Burp` folder.

7. **Customize the Icon:**
   - Create a shortcut to the `loader` file on your desktop.
   - Right-click the shortcut, go to the `Shortcut` tab, and click `Change Icon`.
   - Select `burp-suite.ico` from `C:\Burp`.

---

## Acknowledgements

Special thanks to these contributors for their valuable resources:

- [xiv3r](https://github.com/xiv3r)
- [rabin-thami](https://github.com/rabin-thami)
- [ruban-s](https://github.com/ruban-s)
- [powerstone666](https://github.com/powerstone666)
