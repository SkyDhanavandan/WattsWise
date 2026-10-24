# WattsWise
ESP32-based energy monitoring prototype with LCD, Blynk IoT, appliance-load estimation, alerts and energy history.
# WattsWise – Smart Energy Monitoring System

## Project Overview
WattsWise is an ESP32-based prototype for monitoring electrical parameters, estimating energy consumption, and displaying results through an LCD and Blynk IoT dashboard.

## Objectives
- Monitor voltage, current, and calculated power.
- Estimate appliance-level energy consumption.
- Calculate estimated electricity costs.
- Demonstrate overload and tamper-suspect alerts.
- Retain selected energy records using ESP32 NVS.
- Demonstrate daily, weekly, and monthly energy summaries.

## Hardware and Software
- ESP32 DevKit
- 16x2 I2C LCD
- Voltage and current sensor inputs
- Wokwi test buttons and simulated loads
- VS Code and PlatformIO
- Blynk IoT

## Prototype Status
The current version demonstrates its functions using Wokwi simulation and test-button inputs. Physical sensor calibration and real-household validation are future development tasks.

## Project Structure
- platformio.ini: PlatformIO configuration
- src/main.cpp: Main firmware
- diagram.json: Wokwi circuit, if included
- docs/: Test results and supporting documentation

## Running the Project
1. Open the project folder in VS Code.
2. Install the PlatformIO IDE extension.
3. Check the library dependencies in platformio.ini.
4. Configure your own Blynk credentials privately.
5. Build and run the simulation using the supported Wokwi workflow.

## Safety and Limitations
This is a prototype, not a certified electricity meter. Do not connect the prototype directly to mains power without suitable isolation, protection, and qualified supervision.
