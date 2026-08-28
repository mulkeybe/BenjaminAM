# BenjaminAM

Custom firmware releases for Mutable Instruments Braids.

## Braids BenjaminAM 2.01

The current firmware release includes:

- Quick octave adjustment (OCTV)
- Configurable menu timeout
- Display brightness initialization fix
- Press-and-turn menu timeout adjustment

### Firmware Files

The official 2.01 HEX and WAV binaries are published with the
[eurorack 2.01 release](https://github.com/mulkeybe/eurorack/releases/tag/2.01).

- **HEX** — firmware image for STM32/ST-Link programming.
- **WAV** — audio firmware file for the Braids audio bootloader.

## 2.01 Changes

- **Quick OCTV adjustment** — provides rapid octave adjustment without entering the normal settings menu.
- **Configurable menu timeout** — adds selectable menu timeout behavior.
- **Press-and-turn timeout adjustment** — while adjusting MTO, turn the encoder to select:
  - 5 seconds
  - 10 seconds
  - 15 seconds
  - 20 seconds
- **Display brightness initialization fix** — retained in this release.
- **Firmware update compatibility** — the 2.01 WAV was generated using the working STM audio bootloader/QPSK process and validated as mono, 16-bit, 48 kHz.

## Previous Release

### Braids BenjaminAM 2.0

The previous firmware release included:

- Quick octave adjustment (OCTV)
- Configurable menu timeout
- Display brightness initialization fix

For the original 2.0 HEX and WAV files, see the Braids BenjaminAM 2.0 release:

https://github.com/mulkeybe/BenjaminAM/releases/tag/2.0

## Source Code

The BenjaminAM firmware source code and development history are maintained in the eurorack repository:

https://github.com/mulkeybe/eurorack/tree/benjaminam-octave-timeout

The `benjaminam-octave-timeout` branch contains the source modifications, build configuration, and WAV-generation tooling used for the BenjaminAM firmware releases.
