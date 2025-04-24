# 💡 lumigrid-node-led: Control Your LEDs with Precision! 💡

Welcome to the lumigrid-node-led repository! 🚀 This is where the magic happens for controlling your addressable LED strips and PWM channels with the ESP32. Get ready to create dazzling lighting effects! 🌈

This node is part of the LumiGrid ecosystem, brought to you by Cube & Reclame Fabriek, with development led by DevSlavDev.

## 📂 What's Inside?

This repository contains everything you need to build and deploy the LED Controller Node:

* `app/`:  Source code for the ESP32 firmware (C++ with ESP-IDF). This includes the custom effect engine and web server. 💻
* `web/`:  Node-specific web UI components for controlling LED effects and settings. 💅
* `config/`:  Default configuration files for the LED Node. ⚙️
* `scripts/`:  Scripts for building and deploying the firmware to the ESP32. 🛠️
* `README.md`:  That's me! 👋 Your guide to this repository.

## 🛠️ Project Structure

Here's how things are organized:

lumigrid-node-led/
├── app/        💻 (ESP32 Firmware)
├── web/        💅 (Web UI)
├── config/     ⚙️ (Configuration)
├── scripts/    🛠️ (Build/Deploy Scripts)
└── README.md   📖 (You are here!)


## 🔗 Related Repositories

* [LumiGrid (Main Repository)](https://github.com/DevSlavDev/LumiGrid):  Contains shared resources and documentation. 🧠

## ✨ Features

* Controls up to 5 addressable LED strips. [cite: 26]
* Drives 16 PWM channels. [cite: 26]
* Supports popular addressable LED types (WS2812B, SK6812, etc.). [cite: 27]
* Provides a web interface and REST API for easy control. [cite: 28]
* Uses presets to define LED effects. [cite: 28]

## 🚀 Getting Started

1.  **Clone this repository:**

    ```bash
    git clone [https://github.com/DevSlavDev/lumigrid-node-led.git](https://github.com/DevSlavDev/lumigrid-node-led.git)
    cd lumigrid-node-led
    ```

2.  **Set up your ESP32 development environment:** You'll need the ESP-IDF framework.

3.  **Explore the code in the `app/` directory.**

4.  **Build and flash the firmware to your ESP32.**

5.  **Use the web UI to control your LEDs!**

## 🤝 Contributing

Contributions are welcome! If you have improvements to the LED effects, web interface, or any other part of the project, please submit a pull request. 💪

## 🐛 Issues

Please report any bugs or issues in this repository.

## 📜 License

\[License information will go here]

## Let's make some awesome light shows! ✨
