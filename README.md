# ✨ LumiGrid - LED Controller Node ✨

---

## 💡 What is this Node?

This is the heart of the LumiGrid lighting control! ❤️ The LED Controller Node is built on the versatile ESP32 platform and is dedicated to bringing your lighting ideas to life, from dazzling addressable effects to subtle static colors. ✨🌈💡

Developed with passion by **DevSlavDev** 👨‍💻 in collaboration with **Cube & Reclame Fabriek** 🏢.

---

## 🚀 Key Features

* **Addressable LED Control:** Drive addressable LED strips (like WS2812B, SK6812) with high precision using the ESP32's RMT peripheral! 🎇
    * **2 Independent Channels:** Control up to two separate addressable strips or configurations! 💪
* **PWM Output:** Control standard 12V/24V LED strips, spotlights, or other dimmable loads.
    * **5 PWM Channels:** Specifically designed for **R/G/B/W/WW** configurations, offering full-spectrum control! 💡🟡🔵🟢🔴⚪
* **Integrated Sequencer Control:** Each addressable and PWM channel appears as its own sub-track in the main LumiGrid sequencer.
    * **Independent Sequencing:** Sequence each channel separately for complex and dynamic lighting scenes! 🎬
    * **Channel Enable Buttons:** Easily enable or disable individual channels directly from the UI! ☑️
* **Addressable Display Capability:** Can also handle basic addressable display functions, sharing some core logic with the Display Node. 🔢
* **Control Modes:** Supports External (Art-Net, MQTT), Sync (Master/Slave), and Independent modes. 🚦
* **Calendar-Based Playback:** Equipped with an RTC for scheduled sequences. 🗓️
* **REST API & Web UI:** Configurable and controllable via local network. 🌐

---

## 🧠 Technology Stack

* **Hardware:** ESP32-WROOM 🤖
* **Firmware:** ESP-IDF (C++)
* **Peripherals:** RMT for Addressable LEDs, I2C for PWM chip.
* **Communication:** WiFi, HTTP/REST, mDNS, UDP (for Sync).

---

## 🚧 Work In Progress (WIP)! 🚧

This node is currently under active development. 🌱 We are working on implementing the core control logic, the custom effect engine, and seamless integration with the sequencer and API.

Currently focusing on getting the core Display Node and Sync working first, but this node is next up for the ESP32 phase! 💪

---

## 🤝 Contributions

Currently, contributions are not being actively accepted for this specific node. We are focusing on building the core system structure.

**HOWEVER!** We are building this with future collaboration in mind! 🎉 Once the main code is complete and stable, we plan to open up contributions. Keep an eye on the main LumiGrid repository for updates! 👀

---

## 🔗 Stay Tuned!

Follow the main LumiGrid repository for updates on our progress! 😊

---

Made with ❤️ by DevSlavDev for Cube & Reclame Fabriek
