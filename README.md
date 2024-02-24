# Thimulator
A multi protocol mocking & testing tool for IoT device simulations. Written in ZIG.

# OSs
- X64 Linux with glibc
- X64 Linux with musl
- Aarch64 Linux with glibc
- Aarch64 Linux with musl
- Aarch64 Linux with uclibc
- Aarch64 MacOS with glibc

# Features
- client only
- device profiles & pre-set point tables
- data pub/sub & req/rsp simulation
- multi-threads & multi-nodes

# UIs
- web: bun & elysia & vue & quasar
- tui: ncurse
- gui: lvgl
- cli: zig-cli

# Protocols
- MQTT v5.0
- OPC UA
- Websocket
- MODBUS (ASCII/TCP)
- CANBUS

# Tested CPUs & MCUs & SoBs
- Broadcom B2711 (RaspberryPi 4B)
- Broadcom B2712 (RaspberryPi 5B)
- Renesas RZ/G2L (Myir RemiPi)
- SemiDrive D9Pro (Myir D9360 EV Board)
- Intel i7-13700H (Thinkpad P16v)

# Todo
- Support SparkPlugB
- Support PackML
- Support S7 protocol
- Support ESP32-C3/C6/S3 MCUs (IDF)
- Support RTOS & RT-Thread OSs