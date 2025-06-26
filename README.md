# OmiGlass Firmware & Documentation Updates

## Firmware Updates

- **Multiple Flashing Methods:**
  - Added a cross-platform Python script (`flash_esp32.py`) for automated ESP32 firmware flashing, with port detection and bootloader instructions.
  - Added a shell script (`flash_esp32.sh`) for macOS/Linux users, with device auto-detection and user prompts.
  - Documented manual PlatformIO commands for advanced users and troubleshooting.
  - Improved Arduino IDE instructions, highlighting critical PSRAM configuration and common pitfalls.

- **Troubleshooting Guide:**
  - Comprehensive troubleshooting for flashing issues (port not found, connection errors, permission issues, bootloader mode problems).
  - Runtime troubleshooting for camera initialization, BLE connection, and power management.
  - Platform-specific solutions and command-line tips.

- **Firmware Architecture Documentation:**
  - Detailed explanation of BLE service and characteristic structure.
  - Camera configuration and PSRAM usage documented.
  - Photo streaming protocol and control commands described.
  - Pin mapping for XIAO ESP32-S3 Sense included.

- **Developer Experience Improvements:**
  - Clear, step-by-step instructions for all flashing methods.
  - Expected serial output examples for successful operation.
  - Expanded contribution guidelines for firmware, BLE, and documentation improvements.

## Summary of Improvements

- Enhanced accessibility for new users and advanced developers.
- Increased reliability and clarity in the flashing and setup process.
- Complete technical documentation of firmware and communication protocols.
- Systematic troubleshooting for common and advanced issues.
- Clear roadmap for future contributions and enhancements.

---

.
