# Embedded Systems & RF Engineering

35+ years in embedded systems, telecommunications, and security. Specialized in **IoT**, **RF systems**, and **digital forensics**. Focus on practical, hardware-driven solutions with Arduino, ESP32, and telecom/SDR platforms. Based in Pomezia, Italy.

## Core Expertise

**Embedded Systems & Microcontrollers**
- ESP8266, ESP32, Arduino (ATmega328, NANO, MEGA), STM32
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
- **[ESP8266-BUG-I2S-MIC](https://github.com/aleiei/ESP8266-BUG-I2S-MIC)** (28 stars) — Real-time I2S MEMS microphone streaming over UDP. 16-bit stereo capture and transmission. Includes SoX integration for Linux recording.
- **[ESP32-BUG-I2S-MIC](https://github.com/aleiei/ESP32-BUG-I2S-MIC)** (22 stars) — Advanced version with 48 kHz stereo, async state machine, double-buffering. Professional streaming architecture.

### Video Streaming
- **[ESP32-CAM-RTSP](https://github.com/aleiei/ESP32-CAM-RTSP)** — Full RTSP/1.0 server (OPTIONS, DESCRIBE, SETUP, PLAY, TEARDOWN) with UDP/TCP transport negotiation. MJPEG 10 fps XGA.

### RF & Telecom Systems
- **[Calypso_BTS](https://github.com/aleiei/Calypso_BTS)** — GSM base station toolkit using CalypsoBTS + Osmocom. Automated install for Raspberry Pi with Tkinter GUI. Supports OsmocomBB phones.
- **[Loop_Mag_Auto_Tuner_FTDX-10](https://github.com/aleiei/Loop_Mag_Auto_Tuner_FTDX-10)** — Automatic magnetic loop tuner for Yaesu FTDX-10. Arduino MEGA with ILI9341 display, stepper control, SWR measurement, CAT protocol.
- **[DX_Patrol_PA_monitor](https://github.com/aleiei/DX_Patrol_PA_monitor)** — PA monitor (Power, SWR, Temperature) with rotary encoder menu. Three firmware variants (base / 4-wire / 3-wire fan). Polynomial calibration included.

### Wireless Control Systems
- **[TX-3-STEP-NANO-24L01](https://github.com/aleiei/TX-3-STEP-NANO-24L01)** & **[RX-3-STEP-NANO-24L01](https://github.com/aleiei/RX-3-STEP-NANO-24L01)** — Complementary TX/RX pair for 3-axis motorized slider control via nRF24L01 wireless link.
- **[Nano_Walkie_talkie_nRF24L01](https://github.com/aleiei/Nano_Walkie_talkie_nRF24L01)** — Digital walkie-talkie with nRF24L01 and RF24Audio. OLED UI with signal strength, channel selection, PTT control.

### Security & Tools
- **[Deep-search](https://github.com/aleiei/Deep-search)** — Forensic file search in disk images (.img). Tkinter GUI, pytsk3 backend, type filters, CSV export.
- **[Web_Scraper_pro](https://github.com/aleiei/Web_Scraper_pro)** — Chrome extension (Manifest V3) for CSS-based web scraping. Quick-scrape modes, CSV export, history.
- **[sysclock_gui](https://github.com/aleiei/sysclock_gui)** — System clock management GUI. Python + Tkinter, no dependencies. Dark and light themes.

## Tech Stack

**Languages**: C/C++, Python, Bash, JavaScript, VHDL  
**Platforms**: PlatformIO, Arduino IDE, Vivado  
**Protocols**: RTSP, RTP, TCP/IP, UDP, UART, SPI, I2C, RS-485, nRF24L01, WiFi, GSM/UMTS, CAT  
**Tools**: Git, Linux (primary), Wireshark, SoX, VLC  

## Design Approach

- Practical over theoretical — working hardware comes first
- No unnecessary abstractions — direct register access when needed
- Real-time constraints — proper timing analysis and optimization
- Tested on real platforms — ESP8266/32, Arduino NANO/MEGA, Raspberry Pi
