
# Automatic Room Light Control

## Overview

The **Automatic Room Light Control** project is designed to conserve energy by automatically turning room lights on or off based on the presence or absence of individuals in the room. This project uses Arduino to implement an energy-efficient system that is both simple and cost-effective.

## Features

- **Automatic Light Control**: The system automatically controls room lights based on motion or presence detection.
- **Energy Efficiency**: Helps save energy by ensuring lights are off when no one is in the room.
- **Easy to Build**: Designed for hobbyists, students, and professionals with minimal components and simple setup.
- **Customizable**: The code and hardware setup can be easily modified to suit specific use cases.

## Project Structure

The repository contains the following files:

1. **`Automatic_Room_Light_Control.ino`**: The Arduino sketch implementing the light control logic.
2. **`How to make Power Saving Automatic Room Light Control.png`**: A visual diagram or image illustrating the project or wiring setup.
3. **`LICENSE`**: Licensing details for the project.
4. **`README.md`**: Documentation file (this file).

## Hardware Requirements

- Arduino board (e.g., Arduino Uno)
- PIR (Passive Infrared) motion sensor
- Relay module
- Light bulb or LED
- Jumper wires
- Breadboard
- Power supply (for Arduino and light source)

## Software Requirements

- Arduino IDE
- USB cable for uploading the code to the Arduino board

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/automatic-room-light-control.git
cd automatic-room-light--control
```

### 2. Open the Arduino Code

- Open `Automatic_Room_Light_Control.ino` in the Arduino IDE.

### 3. Upload the Code

1. Connect your Arduino to your computer via a USB cable.
2. Select the correct **Board** and **Port** in the Arduino IDE.
3. Upload the code to the Arduino board.

### 4. Hardware Setup

- Connect the PIR sensor to the Arduino for motion detection.
- Connect the relay module to control the light.
- Wire the components as per the diagram provided in `How to make Power Saving Automatic Room Light Control.png`.

### 5. Test the System

- Place the PIR sensor in the room.
- Observe how the light automatically turns on when motion is detected and turns off when the room is empty.

## How It Works

1. The PIR sensor detects motion or the presence of individuals in the room.
2. The Arduino reads the signal from the PIR sensor.
3. Based on the signal, the Arduino triggers the relay module to turn the light on or off.

## Code Explanation

The Arduino sketch uses basic logic to detect motion and control the relay module. Key components of the code include:

- Reading input from the PIR sensor.
- Controlling the relay output for the light.
- Adjustable delay to define how long the light stays on after no motion is detected.

## Diagram

Refer to the file `How to make Power Saving Automatic Room Light Control.png` for a detailed wiring diagram.

## Applications

- Residential energy management
- Office spaces
- Warehouses and storage rooms
- Public restrooms

## License

This project is licensed under the terms of the [MIT License](LICENSE).

## Contributing

For contributions to enhance this project! Feel free to:

- Report bugs
- Suggest features
- Submit pull requests

