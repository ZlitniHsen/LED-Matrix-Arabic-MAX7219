# Changelog

All notable changes to LED Matrix Arabic MAX7219 are documented in this file.

## [1.2] - 2026-09-20

First public release prepared for distribution.

### Added

- Arabic Unicode text display with automatic contextual letter shaping.
- Support for 1 to 8 chained MAX7219 8×8 LED matrices.
- Support for GENERIC and FC16 matrix modules.
- Variable-width Arabic and ASCII text.
- Lam-Alif ligatures.
- Tatweel support.
- Arabic-Indic digit conversion with preserved numerical order.
- Right, Center and Left text alignment.
- Arabic, ASCII and Arabic-Indic text scrolling.
- Auto, LTR and RTL scrolling directions.
- Mixed text composition with up to five independent groups.
- Unicode icons rendered using the native MicroBlocks font.
- Dissolve, wipe, row wipe and curtain text effects.
- Configurable text blinking with independent ON/OFF durations and repetition count.
- Display rotation, brightness and power controls.
- Educational examples and hardware documentation.

### Hardware validation

Hardware-tested configurations:

- GENERIC ×1
- GENERIC ×4
- FC16 ×1
- FC16 ×4
- FC16 ×8

The library architecture supports chains from 1 to 8 matrices.

### Notes

- Arabic glyphs and Arabic-Indic digit glyphs are original designs by ZLITNI Hsen.
- ASCII/Latin characters and Unicode icons use the native MicroBlocks font.
- A complete Unicode Bidirectional Algorithm is intentionally not implemented. For multi-digit numbers mixed with Arabic text, use the `Arabic digits` reporter or separate Mixed groups.