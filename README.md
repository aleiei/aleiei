# Embedded Systems & RF Engineering

Background in embedded systems, telecommunications, and security, with a focus on **IoT**, **RF systems**, and **digital forensics**. Work covers ATmega328P, ATmega2560, PIC, ESP32, STM32, Broadcom SoCs, and Ettus USRP B210/B200 SDR systems. Based in Rome, Italy.

## Core Expertise

**Embedded Systems, Microcontrollers & Desktop Tools**
- ESP8266, ESP32, ATmega328P, ATmega2560, PIC, STM32, and other SoCs
- STM32CubeIDE / STM32CubeMX for STM32 development
- PIC microcontrollers with MPLAB X and XC toolchains
- Real-time audio/video streaming and control systems
- I2C, SPI, UART, and RS-485 protocol implementation
- Power management, EEPROM persistence, sensor integration

**RF & Radio Systems**
- GSM/cellular base station infrastructure (Osmocom BTS, CalypsoBTS), validated with upstream repositories
- srsRAN 4G/5G infrastructure, validated with upstream repositories
- Antenna design and automatic tuning
- RF parameter monitoring (Power, SWR, spectrum analysis)
- SDR platforms: Ettus USRP B210/B200 series
- Radio astronomy and satellite tracking systems (rotator control via rotctld/Hamlib)
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
- **[ESP8266-BUG-I2S-MIC](https://github.com/aleiei/ESP8266-BUG-I2S-MIC)** — Real-time I2S MEMS microphone streaming over UDP; 16-bit stereo capture and transmission; SoX integration for Linux recording.
- **[ESP32-BUG-I2S-MIC](https://github.com/aleiei/ESP32-BUG-I2S-MIC)** — 48 kHz stereo capture; asynchronous state machine; double-buffering.

### Video Streaming
- **[ESP32-CAM-RTSP](https://github.com/aleiei/ESP32-CAM-RTSP)** — RTSP/1.0 server (OPTIONS, DESCRIBE, SETUP, PLAY, TEARDOWN) with UDP/TCP transport negotiation; MJPEG 10 fps XGA.

### RF & Telecom Systems
- **[Rotator7](https://github.com/aleiei/Rotator7)** — Antenna rotator controller based on SARCnet MK1 Mini Rotator; LSM303AGR magnetometer/accelerometer sensor; RS-485 link over MAX485; rotctld/Hamlib protocol; compatible with SDRangel Star Tracker, Satellite Tracker, and Radio Astronomy plugins.
- **[Calypso_BTS](https://github.com/aleiei/Calypso_BTS)** — Osmocom BTS toolkit based on CalypsoBTS and Osmocom; automated install; Tkinter GUI; OsmocomBB support; validated with upstream repositories.
- **[LibreSDRB210](https://github.com/lmesserStep/LibreSDRB210)** — Vivado FPGA recompilation and adaptation of a B210 clone (AD9361, XC7A100T) with DAC7311IDCKR support for external reference input.
- **[Loop_Mag_Auto_Tuner_FTDX-10](https://github.com/aleiei/Loop_Mag_Auto_Tuner_FTDX-10)** — Automatic magnetic loop tuner for Yaesu FTDX-10; ATmega2560-based controller; ILI9341 display; stepper control; SWR measurement; CAT protocol.
- **[DX_Patrol_PA_monitor](https://github.com/aleiei/DX_Patrol_PA_monitor)** — PA monitor for power, SWR, and temperature; rotary encoder menu; firmware variants for base, 4-wire, and 3-wire fan configurations.
- **[rf_spectrum_art](https://github.com/aleiei/rf_spectrum_art)** — Python Tkinter desktop app that converts text/images into SDR waterfall audio (WAV), with playback, CAT/PTT radio control (Yaesu/XIEGU/FT-736R), presets, and profile management.

### Wireless Control Systems
- **[TX-3-STEP-NANO-24L01](https://github.com/aleiei/TX-3-STEP-NANO-24L01)** & **[RX-3-STEP-NANO-24L01](https://github.com/aleiei/RX-3-STEP-NANO-24L01)** — TX/RX pair for 3-axis motorized slider control over nRF24L01.
- **[Nano_Walkie_talkie_nRF24L01](https://github.com/aleiei/Nano_Walkie_talkie_nRF24L01)** — Digital walkie-talkie with nRF24L01 and RF24Audio; OLED interface; signal strength, channel selection, and PTT control.

### Security & Tools
- **[Deep-search](https://github.com/aleiei/Deep-search)** — File search for disk images (.img); Tkinter GUI; pytsk3 backend; type filters; CSV export.
- **[Web_Scraper_pro](https://github.com/aleiei/Web_Scraper_pro)** — Chrome extension (Manifest V3) for CSS-based web scraping; quick-scrape modes; CSV export; history.
- **[sysclock_gui](https://github.com/aleiei/sysclock_gui)** — System clock management GUI in Python and Tkinter; light and dark themes.

## Tech Stack

**Languages**: C/C++, Python, Bash, JavaScript, VHDL  
**Platforms**: PlatformIO, AVR toolchains, STM32CubeIDE, MPLAB X, Vivado, Broadcom SoCs  
**Protocols**: RTSP, RTP, TCP/IP, UDP, UART, SPI, I2C, RS-485, nRF24L01, WiFi, GSM/UMTS, CAT  
**Tools**: Git, Linux (primary), Wireshark, SoX, VLC  

## Design Approach

- Preference for practical implementations when appropriate
- Direct use of low-level interfaces when required
- Attention to real-time constraints and timing analysis
- Validated on ESP8266/32, ATmega328P/ATmega2560, Broadcom SoCs, Ettus USRP B210/B200 SDR systems, and other SoCs
