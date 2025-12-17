# HA Display ESP32-S3-Touch-LCD-2

This project is based on the **ESP-32-S3-Touch-LCD-2** board from **Waveshare**.  
It provides a compact display solution that shows various values from **Home Assistant** on a built-in LCD screen, with physical buttons for interaction.

## Features
- 📊 Display sensor data and status from Home Assistant.
- 🖥️ Integrated LCD screen with clear layout.
- 🔘 Touch buttons and controls to trigger Home Assistant actions.
- 🔌 Integration via **ESPHome**.

## Purpose
The goal of this project is to complement Home Assistant by offering a quick, at‑a‑glance overview of important values and enabling simple control without opening the app. In my case: show inside and outside temperature, a button to turn on/off standard light scene and two buttons enabling heating in our cars before driving.

## Installation
1. Add the provided configuration to your ESPHome setup.
2. Compile and flash it to the ESP-32-S3-Touch-LCD-2 board.
3. Connect the device to your Home Assistant system.
4. Customize which values to display and what the buttons should do.

## Examples
- Show current temperature and humidity.
- Buttons to toggle lights or activate scenes.
- Quick overview of energy consumption.

## Screenshots
Here are some example screenshots of the display in action:

![Main screen placeholder](images/main_screen.png)  
*Main screen showing temperature and humidity.*

✨ The project is under development and doesn't 100% work. I still have problems with touch.
