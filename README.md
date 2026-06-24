# Embedded Systems & RF Engineering

Experience in embedded systems, telecommunications, and security. Work focused on **IoT**, **RF systems**, and **digital forensics**, with ATmega328P, ATmega2560, ESP32, STM32, Broadcom SoCs, and telecom/SDR platforms. Based in Rome, Italy.

## Core Expertise

**Embedded Systems & Microcontrollers**
- ESP8266, ESP32, ATmega328P, ATmega2560, STM32
- Real-time audio/video streaming and control systems
- I2C, SPI, UART, RS-485 protocol implementation
- Power management, EEPROM persistence, sensor integration

**RF & Radio Systems**
- GSM/cellular base station infrastructure (Osmocom/CalypsoBTS)
- Antenna design and automatic tuning systems
- RF parameter monitoring (Power, SWR, spectrum analysis)
- Wireless protocols: nRF24L01, WiFi, Bluetooth
- CAT protocols and amateur radio integration

**IoT & Streaming**
- Audio streaming over UDP/TCP (16/48 kHz, stereo)
- RTSP/MJPEG video streaming over WiFi
- Asynchronous I/O patterns and double-buffering
- Network protocol implementation and optimization

**Security & Digital Forensics**
- Disk image forensic analysis (pytsk3)
- OSINT and targeted data collection
- EnCase/HELIX-compatible evidence handling

## Featured Projects

### Audio Streaming
- **[ESP8266-BUG-I2S-MIC](https://github.com/aleiei/ESP8266-BUG-I2S-MIC)** — Real-time I2S MEMS microphone streaming over UDP. 16-bit stereo capture and transmission. Includes SoX integration for Linux recording.
- **[ESP32-BUG-I2S-MIC](https://github.com/aleiei/ESP32-BUG-I2S-MIC)** — ESP32 version with 48 kHz stereo, asynchronous state machine, and double-buffering.

### Video Streaming
- **[ESP32-CAM-RTSP](https://github.com/aleiei/ESP32-CAM-RTSP)** — Full RTSP/1.0 server (OPTIONS, DESCRIBE, SETUP, PLAY, TEARDOWN) with UDP/TCP transport negotiation. MJPEG 10 fps XGA.

### RF & Telecom Systems
- **[Calypso_BTS](https://github.com/aleiei/Calypso_BTS)** — GSM base station toolkit based on CalypsoBTS and Osmocom. Includes an automated install and a Tkinter GUI. Supports OsmocomBB phones.
- **[Loop_Mag_Auto_Tuner_FTDX-10](https://github.com/aleiei/Loop_Mag_Auto_Tuner_FTDX-10)** — Automatic magnetic loop tuner for Yaesu FTDX-10. ATmega2560-based controller with ILI9341 display, stepper control, SWR measurement, and CAT protocol.
- **[DX_Patrol_PA_monitor](https://github.com/aleiei/DX_Patrol_PA_monitor)** — PA monitor for power, SWR, and temperature with rotary encoder menu. Three firmware variants are available: base, 4-wire, and 3-wire fan.

### Wireless Control Systems
- **[TX-3-STEP-NANO-24L01](https://github.com/aleiei/TX-3-STEP-NANO-24L01)** & **[RX-3-STEP-NANO-24L01](https://github.com/aleiei/RX-3-STEP-NANO-24L01)** — TX/RX pair for 3-axis motorized slider control over nRF24L01.
- **[Nano_Walkie_talkie_nRF24L01](https://github.com/aleiei/Nano_Walkie_talkie_nRF24L01)** — Digital walkie-talkie with nRF24L01 and RF24Audio. Includes OLED interface, signal strength, channel selection, and PTT control.

### Security & Tools
- **[Deep-search](https://github.com/aleiei/Deep-search)** — File search for disk images (.img). Tkinter GUI, pytsk3 backend, type filters, CSV export.
- **[Web_Scraper_pro](https://github.com/aleiei/Web_Scraper_pro)** — Chrome extension (Manifest V3) for CSS-based web scraping. Includes quick-scrape modes, CSV export, and history.
- **[sysclock_gui](https://github.com/aleiei/sysclock_gui)** — System clock management GUI in Python and Tkinter, with light and dark themes.

## Tech Stack

**Languages**: C/C++, Python, Bash, JavaScript, VHDL  
**Platforms**: PlatformIO, AVR toolchains, Vivado, Broadcom SoCs  
**Protocols**: RTSP, RTP, TCP/IP, UDP, UART, SPI, I2C, RS-485, nRF24L01, WiFi, GSM/UMTS, CAT  
**Tools**: Git, Linux (primary), Wireshark, SoX, VLC  

## Design Approach

- Practical over theoretical
- Direct implementation when needed
- Real-time constraints and timing analysis
- Tested on ESP8266/32, ATmega328P/ATmega2560, and Broadcom SoCs
