# STM32 Oven Control System

## Project Description
This is an STM32-based microcontroller project designed to control an oven system. The project includes functionalities such as:

- Temperature control
- Timer functionality
- Automation features for oven management

The project is developed using **STM32CubeMX** and **STM32CubeIDE** and leverages the **Hardware Abstraction Layer (HAL)** and **CMSIS** libraries.

## Project Contents
The repository contains the following files and directories:

- **Core/**: Contains the main application code (e.g., `main.c`, initialization files).
- **Drivers/**: Includes HAL libraries and CMSIS drivers.
- **Debug/**: Contains compiled files and debugging information.
- **oven_4.ioc**: The STM32CubeMX configuration file used to set up peripherals and pins.
- **STM32F103C6TX_FLASH.ld**: Linker script for memory configuration.

## Requirements
To run this project, you will need:

1. **STM32F103C6** microcontroller or a compatible board (e.g., Blue Pill).
2. **STM32CubeIDE** and **STM32CubeMX** installed on your computer.
3. Basic electronic components such as:
   - Temperature sensor (e.g., LM35 or similar)
   - Relays for controlling heating elements
   - Display module (e.g., LCD or OLED)

## How to Use
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/<your_username>/oven_controller_v4.git
   ```

2. **Open the Project**:
   - Open `oven_4.ioc` in **STM32CubeMX** to view or modify the configuration.
   - Open the project in **STM32CubeIDE** to build and flash the code.

3. **Compile and Flash**:
   - Connect your STM32 board via USB or ST-Link.
   - Compile the project in STM32CubeIDE and upload the firmware to the microcontroller.

4. **Connect Peripherals**:
   - Attach the required sensors and actuators to the pins as per the configuration in `oven_4.ioc`.

5. **Run the System**:
   - Power the system and observe the temperature readings, timer functionality, and relay operations.

## Folder Structure
```
oven_v4/
├── Core/                 # Main application code
├── Drivers/              # STM32 HAL and CMSIS drivers
├── Debug/                # Debugging files
├── oven_4.ioc            # CubeMX configuration file
├── STM32F103C6TX_FLASH.ld # Linker script
├── README.md             # Project documentation (this file)
```

## License
This project is open-source and licensed under the MIT License. Feel free to use, modify, and distribute it.

## Contribution
Contributions are welcome! If you have suggestions or improvements, please open an issue or submit a pull request.
