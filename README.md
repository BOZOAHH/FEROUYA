# FEROUYA
# Forge Emulator Port for OUYA

This repository contains the port of Forge Emulator, a fork of Dolphin, for 32-bit and 64-bit Android devices, specifically being ported to the OUYA gaming console.


## Overview

Forge Emulator is a highly optimized fork of the Dolphin Emulator, which is designed to run on Android devices. This project aims to bring the power of Forge Emulator to the OUYA, an Android-based gam[...]

## Features

- **32-bit and 64-bit Support**: Fully compatible with both 32-bit and 64-bit Android architectures.
- **Optimized for OUYA**: Specially tailored for the OUYA console to ensure the best performance.
- **High Compatibility**: Supports a wide range of GameCube and Wii games.
- **Customizable Controls**: Offers customizable on-screen controls and OUYA controller support.
- **Enhanced Graphics**: Includes various graphical enhancements and options for better visual quality.

## Early Access Notice

Please note that this project is in very early access. It is not yet fully optimized for the original OUYA hardware without hardware modification. As such, performance may not be optimal out of the bo[...]

### Settings Configuration

**CPU Section:**
- Dual Core: Enabled
- CPU Core: JIT ARM Recompiler

**Controller Settings:**
1. Go to GameCube Controller Bindings.
2. Choose Controller 1-4 depending on how many controllers are connected (e.g., do controller 1 for controller 1, do controller 2 for controller 2).
3. Click enable and modify the configuration to your liking.

**Video:**
- Backend: OpenGL ES
- Show FPS: On

**Enhancements:**
- Scaled EFB Copy: Enabled

**Hacks:**
- Ignore Format Changes: Enabled
- Fast Depth Calculation: Enabled

With these settings, you should experience improved performance and a better gaming experience.

## Installation

To install the Forge Emulator on your OUYA device, follow these steps:

1. **Download the APK**: Obtain the latest APK file from the [releases section](https://github.com/BOZOAHH/FEROUYA/releases).
2. **Transfer to OUYA**: Transfer the APK file to your OUYA console using a USB drive or network transfer.
3. **Install the APK**: On your OUYA, navigate to the file manager (or developer tab's more settings) and locate the transferred APK file. Select it to begin the installation.
4. **Launch the Emulator**: After installation, you can find the Forge Emulator in your apps list. Launch it and enjoy your favorite games!

## Usage

- **Loading Games**: To load a game, simply navigate to the game file within the emulator and select it to start playing.
- **Controller Configuration**: Configure your OUYA controller or on-screen controls through the settings menu for the best gaming experience.
- ![Controller Tutorial.](https://github.com/BOZOAHH/FEROUYA/blob/main/bandicam%202025-04-02%2018-58-37-735%20(online-video-cutter.com).gif)

## Contributing

We welcome contributions from the community. If you have suggestions, bug reports, or feature requests, please open an issue or submit a pull request. Make sure to follow the contribution guidelines.

## License

This project is licensed under the [MIT License](LICENSE).

## Credits

- **Dolphin Emulator Team**: For creating the original Dolphin Emulator.
- **Forge Emulator Team**: For their work in optimizing Dolphin for Android. (just me!)
- **OUYA Community**: For their support and feedback.

## Contact

For any questions or support, please contact us through the [GitHub Issues](https://github.com/BOZOAHH/FEROUYA/issues) page.

Enjoy gaming on your OUYA with Forge Emulator!
