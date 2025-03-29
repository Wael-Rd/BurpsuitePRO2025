#  BurpSuitePro v2025 

## Overview

![overview](https://github.com/Wael-Rd/BurpsuitePRO2025/blob/main/overview.png?raw=true)

[Overview](https://portswigger.net/burp/pro)

------

### Steps:

1. Make the script executable:

   ```sh
   chmod +x install.sh
   ```

2. Run the installation script:

   ```sh
   ./install.sh
   ```

3. Run Burp Suite:

   ```sh
   burpsuitepro
   ```

> Select the default Java version:

```sh
sudo update-alternatives --config java
```

**Note:** Copy the license from loader to the Burp Suite > Manual Activation > Copy Burp Suite request key to loader request > Copy response key to the Burp Suite.

------

#  Windows Installation

### Steps:

1. Create a `Burp` directory in `C Drive` for faster access.

2. Download [install.ps1](https://codeload.github.com/xiv3r/Burpsuite-Professional/zip/refs/heads/main) and extract the contents to `C:\Burp`.

3. Open `PowerShell` as administrator and execute the following command to set Script Execution Policy:

   ```sh
   Set-ExecutionPolicy -ExecutionPolicy Bypass -Scope Process
   ```

4. Navigate to the `Burp` directory in PowerShell:

   ```sh
   cd C:\Burp
   ```

5. Execute `install.ps1` to complete the installation:

   ```sh
   ./install.ps1
   ```

6. Ensure the loader is in the new Burp folder.

7. Change the icon of `loader`:

   - Create a shortcut on the Desktop.
   - Right-click `loader` and go to the Shortcut tab.
   - Click `Change Icon` and choose `burp-suite.ico` from `C:\Burp\`.

------

## Thanks to:

- [xiv3r](https://github.com/xiv3r)
- [rabin-thami](https://github.com/rabin-thami)
- [ruban-s](https://github.com/ruban-s)
- [powerstone666](https://github.com/powerstone666)# BurpsuitePRO2025
