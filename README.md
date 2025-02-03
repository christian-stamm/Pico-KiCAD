# RP2040-DebugProbe

The **DebugProbe** project aims to re-imagine Raspberry Pi Debug Probe.

## RP2040-DebugProbe Board

The **RP2040-DebugProbe** board is a 4-layer design intended to accommodate the popular Raspberry Pi RP2040 MCU with all required component to function identically to Raspberry Pi Debug Probe.

This board features target JTAG connector and PC host USB Type-C connector. It also has a SWD connector and UART connector for the main MCU debugging. The board is pin-compatible with Raspberry Pi Debug Probe and can be used with the same picoprobe SW.

You can view the [Schematics in PDF format](doc/RP2040-DebugProbe.pdf) for detailed information.

Features:

- Very small form-factor of about 50x25mm (25x40mm).
- Raspberry Pi RP2040 MCU as a heart of the board.
- 2x5 1.27mm JTAG connector for programming and debugging.
- USB Type-C connector for power and communication.
- Several LEDs to indicate power and status.
- BOOTSEL button to enter the bootloader mode for flashing new picoprobe SW.
- Pin-compatible with Raspberry Pi Debug Probe.

## Links

- [Raspberry Pi RP2040 information page](https://www.raspberrypi.com/documentation/microcontrollers/rp2040.html).
- [Raspberry Pi Debug Probe information page](https://www.raspberrypi.com/documentation/microcontrollers/debug-probe.html).
- [Picoprobe SW for the board](https://github.com/raspberrypi/picoprobe).