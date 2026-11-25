# 🏎️ Awesome Embedded Telemetry & Sim Racing Hardware

<p align="center">
  <img src="./assets/banner.svg" alt="Awesome Embedded Telemetry and Sim Racing Hardware Banner" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Embedded-Telemetry-Sim-Racing-Hardware"><img src="https://img.shields.io/badge/Awesome-Sim%20Racing%20Hardware-orange?style=for-the-badge&logo=awesome" alt="Awesome List"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Embedded-Telemetry-Sim-Racing-Hardware/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Embedded-Telemetry-Sim-Racing-Hardware?style=for-the-badge&logo=github&color=yellow" alt="GitHub stars" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Embedded-Telemetry-Sim-Racing-Hardware/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Embedded-Telemetry-Sim-Racing-Hardware?style=for-the-badge&logo=github&color=blue" alt="GitHub forks" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Embedded-Telemetry-Sim-Racing-Hardware/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge" alt="License: MIT"/></a>
  <a href="https://github.com/ishandutta2007"><img src="https://img.shields.io/github/followers/ishandutta2007?style=for-the-badge&logo=github&color=lightgrey" alt="GitHub followers" /></a>
</p>

---

## 🏁 Comprehensive Guide to Sim Racing Telemetry, DIY Embedded Hardware & Analytics Suites

> **A curated showcase of industry-leading SaaS platforms, commercial telemetry engines, open-source firmware, and DIY embedded electronics.**  
> *Targeted at sim racers, esports competitors, embedded systems engineers, and DIY rig builders building ESP32/Nextion cockpits, Direct-Drive FFB wheelbases, tactile bass shakers, and lap telemetry analysis rigs.*

**Last updated:** November 2026 🏎️💨

Welcome to the definitive, SEO-optimized knowledge base covering **Embedded Telemetry & Sim Racing Hardware**. Whether configuring UDP network packets from *Assetto Corsa*, *iRacing*, *Le Mans Ultimate*, *F1 25/26*, or *Gran Turismo 7*, flashing STM32/ESP32 microcontrollers for custom button boxes, or executing deep MoTeC i2 suspension histograms, this guide brings together all commercial leaders and top open-source projects in one place.

---

## 📑 Table of Contents

- [🏎️ Awesome Embedded Telemetry & Sim Racing Hardware](#️-awesome-embedded-telemetry--sim-racing-hardware)
  - [🏁 Comprehensive Guide to Sim Racing Telemetry, DIY Embedded Hardware & Analytics Suites](#-comprehensive-guide-to-sim-racing-telemetry-diy-embedded-hardware--analytics-suites)
  - [📑 Table of Contents](#-table-of-contents)
  - [📊 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
  - [☁️ SaaS & Commercial Telemetry Platforms](#️-saas--commercial-telemetry-platforms)
  - [💻 Open-Source GitHub Projects](#-open-source-github-projects)
  - [🔍 Core Tech Stack & Protocols](#-core-tech-stack--protocols)
  - [🛠️ How to Contribute](#️-how-to-contribute)
  - [⚠️ Disclaimer](#️-disclaimer)
  - [💖 Support & Thank You](#-support--thank-you)

---

## 📊 Sector Overview & Market Dynamics

The global **Sim Racing Hardware and Motorsport Telemetry market** is estimated at **$1.4B–$1.8B in 2026**, registering a brisk compound annual growth rate (**CAGR of ~12%–16%**) spurred by rapid consumer adoption of direct-drive wheelbases, active load-cell pedals, and esports sim coaching platforms.

The market displays a distinct dual-layer competitive structure:
- **Hardware Manufacturing Layer (Moderately Concentrated):** Peripheral hardware (wheelbases, pedals, cockpits) is dominated by established giants like Corsair (Fanatec), Logitech G, Thrustmaster, Moza Racing, and Simucube/Granite Devices, where brand loyalty, production scale, and console licensing form significant moats.
- **Telemetry & Software Layer (Highly Fragmented):** Telemetry software, embedded displays, and driver analytics remain **highly fragmented**. Unlike a winner-take-all monopoly, the landscape is partitioned across high-end motorsport acquisition suites (Bosch/MoTeC, AiM Sportline), cloud-native subscription coaching portals (VRS, Popometer), indie utilities (SimHub, Z1), and a thriving grassroots open-source ecosystem (OpenFFBoard, FreeJoy, ESP32 custom firmware).

---

## ☁️ SaaS & Commercial Telemetry Platforms

*The table below compares prominent commercial and SaaS sim racing telemetry platforms, sorted in descending order by parent company scale (annual revenue / valuation).*

| 🏢 Platform | 📝 Description | 📈 Company Scale (Valuation / Revenue) | 💳 Pricing (Starting Paid Tier) | 🎁 Free Tier / Free Trial Limits |
| :--- | :--- | :--- | :--- | :--- |
| **[Fanatec FanaLab (Corsair)](https://fanatec.com)** 🎮 | Official tuning suite driving telemetry LEDs, OLED rev-gauges, and dynamic force feedback profiles on Fanatec wheelbases. | **~$1.35B Annual Revenue** (Acquired by NASDAQ: CRSR / Corsair Gaming) | **$0.00** (Software bundled 100% free with Fanatec hardware; entry hardware starts at **$399.00**) | **100% Free Software Forever** (Unlimited usage for all Fanatec hardware owners; no subscription or feature lock) |
| **[Assetto Corsa Telemetry Engine](https://assettocorsa.it)** ⏱️ | Native shared-memory physics telemetry pipeline powering external dashes, motion platforms, and MoTeC data exporters. | **~$120M+ Parent Revenue** (Kunos Simulazioni / Digital Bros Group) | **$0.00** (Shared memory API & ACTI logger bridge included with base game, typically **$19.99–$39.99**) | **100% Free API Forever** (Unlimited access to real-time 333 Hz physics and suspension data; zero subscription fees) |
| **[MoTeC i2 Pro](https://motec.com.au)** 🏎️ | Gold-standard professional motorsport telemetry suite used in Formula 1/WEC and integrated via community loggers in iRacing and ACC. | **~$60M–$100M Scale** (Motorsport division of Bosch Group) | **$0.00** (Free desktop download; commercial hardware data loggers start from **$1,500.00+**) | **100% Free Forever for Sim Analysis** (Full access to i2 Pro telemetry math channels, suspension velocity histograms, and track mapping at zero software cost) |
| **[AiM Race Studio 3](https://aim-sportline.com)** 🏁 | Professional motorsport data acquisition, track mapping, and digital dashboard designer software compatible with sim telemetry converters. | **~$50M–$80M Annual Revenue** (Global Italian motorsport electronics manufacturer) | **$0.00** (Free software; physical AiM MXG/MXS automotive dashes start at **$1,200.00+**) | **100% Free Forever** (Full access to Race Studio 3 analysis, GPS mapping, math channels, and display configuration without expiration) |
| **[SimCommander (SimXperience)](https://simxperience.com)** 🕹️ | Enterprise motion simulator controller, AccuForce direct-drive FFB tuning, and tactile SimVibe bass-shaker telemetry engine. | **~$15M–$30M Estimated Revenue** (Leading US motion-rig & sim hardware vendor) | **$89.00 one-time license** for SimCommander 4 (or bundled free with SimXperience hardware rigs) | **No Perpetual Free Plan; Demo Mode Only** (Requires valid product key; software without key functions only in basic preview mode with no motion/vibe output) |
| **[VRS Telemetry (Virtual Racing School)](https://vrs.racing)** 🚀 | SaaS cloud-based sim racing telemetry analytics, AI corner-by-corner coaching, and telemetry datapack comparisons for iRacing and ACC. | **~$10M–$20M Valuation** (~$3M–$6M estimated ARR) | **$4.99 / month** (Single Dedicated Car plan) or **$9.99 / month** (Competitive All-Cars subscription) | **Forever Free Rookie Tier** (Unlimited personal telemetry logging + free access to all official Rookie series datapacks; 14-day free trial on premium tiers) |
| **[Popometer](https://popometer.io)** 📈 | Modern browser-based telemetry comparison tool, pro setup marketplace, and automated corner analysis for ACC, iRacing, and LMU. | **~$5M–$10M Valuation** (~$1M–$3M estimated ARR) | **€4.99 / month (~$5.40/mo)** for Telemetry Pro (or setup datapacks from **€3.50 each**) | **Forever Free Basic Tier** (Upload unlimited personal laps, inspect throttle/brake traces, and compare against your own personal bests with no time limit) |
| **[SimHub](https://simhubdash.com)** 💡 | Universally loved sim-racing telemetry bridge driving ESP32/Arduino LCD screens, Nextion displays, wind simulators, and bass shakers. | **~$5M–$12M Scale** (Dominant independent sim software ecosystem) | **€6.00 one-time donation (~$6.50)** (Permanently unlocks 60 FPS hardware refresh rate across all devices) | **Forever Free Unlicensed Edition** (Full features including 70+ games, Arduino sketch generator, and bass shakers, capped at **10 FPS** display refresh) |
| **[Z1 Dashboard & Analyzer](https://z1simwheel.com)** 🖥️ | Multi-screen digital sim dashboard, track map radar, tire heat monitor, and pit-stop strategist for 30+ racing titles. | **~$2M–$5M Scale** (Pioneer sim-racing digital instrumentation software) | **$24.99 / year** (Dashboard license) or **$59.99 one-time** (Bundled Dashboard + Telemetry Analyzer) | **15-Minute Free Trial Per Session** (Complete feature set available for free with unlimited session launches, automatically exiting after **15 minutes per session**) |
| **[Race Element](https://elementfuture.com)** 🏎️ | Telemetry-powered HUD overlays, real-time tire pressure spotters, and hardware LED controller for ACC and iRacing. | **Indie / Community Sponsored** (Sustained via Patreon & community donations) | **$0.00** (Optional Patreon tiers starting at **$3.00 / month** for early access builds) | **100% Free Forever** (All live HUD telemetry widgets, fuel calculators, and controller LED bridges are completely free) |

---

## 💻 Open-Source GitHub Projects

*Open-source firmware, libraries, and applications for DIY sim racers and embedded engineers. Sorted descending by GitHub star count.*

| 🛠️ Project & Repository | ⭐ Stargazers | 📜 License & Cost | 🆓 Free / Self-Hosted Limits | 🔍 Focus & Capabilities |
| :--- | :--- | :--- | :--- | :--- |
| **[Ultrawipf/OpenFFBoard](https://github.com/Ultrawipf/OpenFFBoard)** ⚡ | [![Stars](https://img.shields.io/github/stars/Ultrawipf/OpenFFBoard?style=social&color=white)](https://github.com/Ultrawipf/OpenFFBoard/stargazers) | **GPL-3.0** ($0 firmware; DIY hardware ~$120–$350) | **100% Free Forever** (Unlimited motor current tuning, TMC4671 driver configuration, and high-speed USB HID FFB) | Universal open-source force-feedback interface for DIY Direct-Drive steering wheels using STM32 microcontrollers and industrial servo/stepper motors. |
| **[FreeJoy-Team/FreeJoy](https://github.com/FreeJoy-Team/FreeJoy)** 🎛️ | [![Stars](https://img.shields.io/github/stars/FreeJoy-Team/FreeJoy?style=social&color=white)](https://github.com/FreeJoy-Team/FreeJoy/stargazers) | **GPL-3.0** ($0 firmware; STM32 BluePill ~$3–$6) | **100% Free Forever** (Up to 8 analog axes, 128 buttons, 4 shift registers, and dual-rate rotary encoders per board) | Versatile open-source USB-HID controller firmware for STM32F103 microcontrollers, powering DIY sim-racing button boxes, load-cell pedals, and shifters. |
| **[kutu/pyirsdk](https://github.com/kutu/pyirsdk)** 🐍 | [![Stars](https://img.shields.io/github/stars/kutu/pyirsdk?style=social&color=white)](https://github.com/kutu/pyirsdk/stargazers) | **MIT License** ($0 open-source library) | **100% Free Forever** (Unlimited 60 Hz iRacing shared-memory extraction and custom Python analytics) | Python wrapper around the official iRacing C++ SDK; extracts real-time telemetry, session timers, and broadcast camera commands for data science and AI coaching. |
| **[Winzarten/SecondMonitor](https://github.com/Winzarten/SecondMonitor)** 📊 | [![Stars](https://img.shields.io/github/stars/Winzarten/SecondMonitor?style=social&color=white)](https://github.com/Winzarten/SecondMonitor/stargazers) | **MIT License** ($0 open-source suite) | **100% Free Forever** (Full live timing, telemetry logging, suspension histograms, and fuel calculation on secondary PC/monitors) | Comprehensive open-source timing and car monitoring telemetry application supporting Assetto Corsa, ACC, Automobilista 2, Project CARS, and rFactor 2. |
| **[caa1211/esp32-gt7-dashboard](https://github.com/caa1211/esp32-gt7-dashboard)** 📟 | [![Stars](https://img.shields.io/github/stars/caa1211/esp32-gt7-dashboard?style=social&color=white)](https://github.com/caa1211/esp32-gt7-dashboard/stargazers) | **MIT License** ($0 firmware; ESP32-S3 board ~$15–$25) | **100% Free Forever** (Unlimited wireless UDP decryption, 60 FPS gauge rendering, and multi-screen layout support) | Embedded ESP32-S3 firmware decoding encrypted Gran Turismo 7 UDP telemetry packets over Wi-Fi to render real-time RPM, speed, fuel, and tire heat on physical LCDs. |
| **[SpeedHQ/RaceIQ](https://github.com/SpeedHQ/RaceIQ)** 🏁 | [![Stars](https://img.shields.io/github/stars/SpeedHQ/RaceIQ?style=social&color=white)](https://github.com/SpeedHQ/RaceIQ/stargazers) | **MIT License** ($0 open-source tool) | **100% Free Forever** (Live web dashboard, AI coaching feedback, lap comparison, and community car tune repository) | Modern sim-racing telemetry & lap analysis suite supporting Forza Motorsport, F1 25/26, ACC, and Assetto Corsa Evo with ghost replay playback. |
| **[touchgadget/simracing-telemetry-esp8266](https://github.com/touchgadget/simracing-telemetry-esp8266)** 📡 | [![Stars](https://img.shields.io/github/stars/touchgadget/simracing-telemetry-esp8266?style=social&color=white)](https://github.com/touchgadget/simracing-telemetry-esp8266/stargazers) | **MIT License** ($0 firmware; ESP8266 ~$3–$5) | **100% Free Forever** (Low-overhead UDP parsing, OLED I2C display drivers, and multi-LED shift lights) | Lightweight embedded telemetry receiver running on low-cost ESP8266 microcontrollers to power external OLED displays and WS2812B rev lights. |
| **[jake-dog/opensimdash](https://github.com/jake-dog/opensimdash)** 🏎️ | [![Stars](https://img.shields.io/github/stars/jake-dog/opensimdash?style=social&color=white)](https://github.com/jake-dog/opensimdash/stargazers) | **MIT License** ($0 open-source library) | **100% Free Forever** (Cross-platform UDP/shared-memory abstraction for custom client dashboards) | Extensible open-source telemetry library and dashboard framework bridging UDP telemetry streams into customizable desktop and embedded interfaces. |
| **[shfonic/ShfonicDash](https://github.com/shfonic/ShfonicDash)** 🍓 | [![Stars](https://img.shields.io/github/stars/shfonic/ShfonicDash?style=social&color=white)](https://github.com/shfonic/ShfonicDash/stargazers) | **MIT License** ($0 software; Raspberry Pi ~$35–$60) | **100% Free Forever** (Cockpit-mounted HDMI touchscreens, session logging, and companion web interface) | Dedicated sim-racing telemetry dashboard designed for cockpit-mounted Raspberry Pi displays, receiving UDP from F1 games, PCARS 2, Forza, and GT7. |
| **[tatewamola-web/lapsmith](https://github.com/tatewamola-web/lapsmith)** ⏱️ | [![Stars](https://img.shields.io/github/stars/tatewamola-web/lapsmith?style=social&color=white)](https://github.com/tatewamola-web/lapsmith/stargazers) | **MIT License** ($0 open-source analyzer) | **100% Free Forever** (Ghost playback, corner delta maps, and braking point comparison) | Self-hosted sim racing telemetry analysis tool delivering interactive lap comparisons and corner-by-corner coaching for competitive sim racers. |
| **[t-hovestadt/sim-teleport](https://github.com/t-hovestadt/sim-teleport)** 🌐 | [![Stars](https://img.shields.io/github/stars/t-hovestadt/sim-teleport?style=social&color=white)](https://github.com/t-hovestadt/sim-teleport/stargazers) | **MIT License** ($0 networking daemon) | **100% Free Forever** (Low-latency UDP telemetry forwarding across LAN/WLAN to secondary SimHub rigs) | Lightweight network utility streaming telemetry from 35+ sim titles (iRacing, ACC, AC EVO, Wreckfest 2) to remote SimHub PCs and offloaded dashboards. |
| **[Carlos-Diaz-07/simbridge](https://github.com/Carlos-Diaz-07/simbridge)** 🐧 | [![Stars](https://img.shields.io/github/stars/Carlos-Diaz-07/simbridge?style=social&color=white)](https://github.com/Carlos-Diaz-07/simbridge/stargazers) | **GPL-3.0** ($0 open-source software) | **100% Free Forever** (Native Linux telemetry parsing, bass-shaker audio synthesis, and HUD dashboards) | Native Linux sim-racing telemetry bridge and audio effects engine functioning as an open-source SimHub alternative for Steam Deck and Linux sim racers. |
| **[EKSIMRacing/OpenSR](https://github.com/EKSIMRacing/OpenSR)** 🔄 | [![Stars](https://img.shields.io/github/stars/EKSIMRacing/OpenSR?style=social&color=white)](https://github.com/EKSIMRacing/OpenSR/stargazers) | **GPL-3.0** ($0 open-source middleware) | **100% Free Forever** (Universal game-in to hardware-out routing for motion systems and custom wheel rims) | Open Sim Relay middleware engineered to bridge telemetry data from game engines to robotic motion simulators, steering wheels, and external displays. |
| **[stevendaniluk/SimRacingInputs](https://github.com/stevendaniluk/SimRacingInputs)** ⌨️ | [![Stars](https://img.shields.io/github/stars/stevendaniluk/SimRacingInputs?style=social&color=white)](https://github.com/stevendaniluk/SimRacingInputs/stargazers) | **MIT License** ($0 Arduino C++ library) | **100% Free Forever** (Debounced matrix scanning, rotary encoder acceleration, and multi-position switch handling) | Dedicated Arduino library simplifying the integration of rotary encoders, pushbuttons, toggle switches, and potentiometers for custom sim cockpits. |

---

## 🔍 Core Tech Stack & Protocols

```
┌────────────────────────────────────────────────────────┐
│             Sim Racing Game Engines                    │
│   (Assetto Corsa, iRacing, ACC, Le Mans Ultimate, GT7) │
└───────────────────────────┬────────────────────────────┘
                            │
            ┌───────────────┴───────────────┐
            ▼                               ▼
  ┌───────────────────┐           ┌───────────────────┐
  │ UDP Broadcasts    │           │ Shared Memory     │
  │ (Wi-Fi / LAN)     │           │ (Windows MMF API) │
  └─────────┬─────────┘           └─────────┬─────────┘
            │                               │
            ▼                               ▼
  ┌───────────────────┐           ┌───────────────────┐
  │ Embedded Displays │           │ Telemetry Hubs    │
  │ (ESP32, ESP8266,  │           │ (SimHub, MoTeC,   │
  │  Nextion, VOCORE) │           │  VRS, Popometer)  │
  └───────────────────┘           └─────────┬─────────┘
                                            │
                                            ▼
                                  ┌───────────────────┐
                                  │ Direct-Drive &    │
                                  │ Tactile Feedback  │
                                  │ (OpenFFBoard,     │
                                  │  Bass Shakers)    │
                                  └───────────────────┘
```

- **Data Channels:** Suspension travel, tire carcass temperature, brake disc heat, yaw rate, lateral/longitudinal G-forces, slip angle, engine RPM, gear indicator, ABS/TC pulse frequency, and fuel consumption.
- **Embedded Hardware:** ESP32-S3 (Wi-Fi/BLE), STM32F407 (OpenFFBoard Direct-Drive), STM32F103 (FreeJoy HID), Arduino Pro Micro (ATmega32U4), Raspberry Pi 4/5, VOCORE 4.3"/5.0" USB LCDs, and Nextion HMI displays.
- **Actuation & Haptics:** TMC4671 field-oriented control drivers, Mige/Bafang brushless servo motors, Dayton Audio TT25-16 / BST-1 tactile bass shakers, and dual-haptic pedal rumble motors.

---

## 🛠️ How to Contribute

We actively welcome contributions from the sim-racing community, embedded engineers, and telemetry analysts! 🤝

1. 🍴 **Fork the Repository** on GitHub.
2. 🌿 **Create a Feature Branch:** `git checkout -b feature/add-new-project`
3. 📝 **Add Your Entry:** Ensure commercial products include explicit **Starting Paid Tier Pricing** and concrete **Free Tier / Trial Limits**. For open-source repos, provide repository URL, star badge, and descriptive summary.
4. 🚀 **Commit & Push:** `git commit -m "feat: add [Project Name]"`
5. 📬 **Submit a Pull Request** with details on the hardware platform or telemetry protocol supported!

---

## ⚠️ Disclaimer

All product names, trademarks, logos, and brands mentioned herein are property of their respective owners. Fanatec, Corsair, MoTeC, Bosch, AiM, SimHub, SimXperience, Virtual Racing School, Popometer, Assetto Corsa, and iRacing are registered trademarks used here solely for descriptive, comparative, and identification purposes.

---

## 💖 Support & Thank You

If you find this curated collection helpful for your DIY sim-racing rig or telemetry engineering projects:
- ⭐ **Star this repository** to support discoverability!
- 🔀 **Fork & share** with your local racing league or maker club.
- 💬 **Open an issue or PR** to suggest new hardware dashboards, firmware projects, and telemetry tools.

*Happy Racing & Happy Building! 🏁 Keep the throttle pinned and the apex tight!*
