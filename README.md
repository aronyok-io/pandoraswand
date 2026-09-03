# pandoraswand
Just a silly wand~ why do u ask??

**Pandora'sWand** is an open-source experimental handheld electronic multitool built for learning, tinkering, hardware exploration, and cybersecurity research.

Or at least... that's what it *will* be.

Right now?

[ STATUS: COOKING... ]


## ✦ The Idea

One tiny handheld device.

A collection of tools.

An unreasonable amount of curiosity.

Pandora's Wand is my attempt to build a modular pocket-sized device from scratch while learning about:

- Embedded systems
- Electronics
- Microcontrollers
- PCB design
- Wireless communication
- NFC / RFID
- Infrared
- GPIO & hardware interfaces
- Firmware development
- Cybersecurity

The goal isn't to clone an existing device.

The goal is to understand how these things work and build my own.

## ✦ Planned Architecture

```text
                    Pandora'sWand
                          │
                   ┌──────┴──────┐
                   │   ESP32-S3  │
                   │     MCU     │
                   └──────┬──────┘
                          │
          ┌───────────────┼───────────────┐
          │               │               │
       Display          Input           Storage
       OLED/TFT        Controls         microSD
          │
    ┌─────┼────────┬──────────┬──────────┐
    │     │        │          │          │
    IR   NFC     Sub-GHz     GPIO      USB
```

✦ Current Hardware?

Nothing yet.

✦ Ethics

Pandora's Wand is intended for education, experimentation, hardware research, and authorized security testing.

Use it only with devices, systems, frequencies, and infrastructure that you own or have explicit permission to test.

You are responsible for following applicable laws and radio regulations.

✦ License

Firmware and software in this repository are licensed under the GNU General Public License v3.0, unless otherwise stated.

Future hardware design files may use a dedicated open-hardware license.

✦ Repository Structure

pandoraswand/
├── firmware/       # PandoraOS
├── hardware/       # Schematics & PCB
├── enclosure/      # CAD / enclosure designs
├── docs/           # Documentation
├── examples/       # Experiments
└── README.md
