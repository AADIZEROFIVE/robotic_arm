# STM32CubeIDE Installation Guide

This guide provides step-by-step instructions for installing STM32CubeIDE on Windows, Linux, and macOS.

## 1. Download STM32CubeIDE

-   Visit the official STMicroelectronics website: [https://www.st.com/en/development-tools/stm32cubeide.html](https://www.st.com/en/development-tools/stm32cubeide.html)
-   Choose the version compatible with your operating system (Windows, macOS, or Linux).

## 2. Installation on Windows

1.  Run the downloaded `.exe` installer.
2.  Follow the on-screen instructions, accepting the license agreement.
3.  Select the desired installation directory and click "Next."
4.  Complete the installation and launch STM32CubeIDE.
5.  Configure your workspace when prompted.

## 3. Installation on Linux

1.  Open a terminal and navigate to the download directory.
2.  Make the installer executable:

    ```bash
    chmod +x SetupSTM32CubeIDE-*.linux
    ```

3.  Run the installer:

    ```bash
    ./SetupSTM32CubeIDE-*.linux
    ```

    (Replace `SetupSTM32CubeIDE-*.linux` with the actual filename.)
4.  Follow the on-screen instructions to complete the installation.
5.  For ST-LINK debugging, you may need to install `libusb`:

    ```bash
    sudo apt-get install libusb-1.0-0-dev
    ```
    or for fedora based systems
    ```bash
    sudo dnf install libusb-devel
    ```
    You may also need to add udev rules to allow access to the st-link programmer.

## 4. Installation on macOS

1.  Open the downloaded `.dmg` file.
2.  Drag and drop the STM32CubeIDE application into the "Applications" folder.
3.  Launch STM32CubeIDE from the "Applications" folder.

## 5. Install Required Drivers (Optional, but Recommended)

-   Install the ST-LINK drivers for debugging: [https://www.st.com/en/development-tools/stsw-link009.html](https://www.st.com/en/development-tools/stsw-link009.html)

## 6. Verify Installation

-   Launch STM32CubeIDE.
-   Create a new STM32 project to test the installation.
-   If you encounter any issues, consult the official STM32CubeIDE documentation or reinstall the drivers.
