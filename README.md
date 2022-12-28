# WEACT_H743

WEACT_H743 board definition for Micropython.

Build steps:
- Go to the `ports/stm32` directory
- Run `make BOARD=WEACT_H743`
- Connect the board to the PC using ST-Link
- Flash the `firmware.hex` or `firmware.bin` from the subdir `build-WEACT_H743` using a favorite flashig app (e.g. STM32CubeProgrammer)
- Disconnect the ST-Link device
- Connect the board to the PC using USB
- Reset the board

The configuration is far from complete, it serves as a reference for creating the [WEACT_H750](https://github.com/jahr/WEACT_H750) board definition, so it is not optimal.
