# STM32 Lab Exercises | STM32 实验集

Complete STM32 lab exercises for Diploma EE students. Each lab includes CubeMX config, HAL code, and wiring diagrams.

STM32 实验完整代码，每个实验包含 CubeMX 配置、HAL 代码和接线图。

---

## Labs | 实验列表

| Lab | Topic | Peripherals |
|-----|-------|-------------|
| 01 | LED Blink | GPIO Output |
| 02 | Button Input | GPIO Input, EXTI |
| 03 | UART Serial | USART2, printf |
| 04 | ADC Read | ADC1, Potentiometer |
| 05 | PWM Output | TIM2, LED brightness |
| 06 | I2C OLED | I2C1, SSD1306 display |
| 07 | SPI Sensor | SPI1, temperature sensor |
| 08 | Timer Interrupt | TIM3, periodic callback |
| 09 | Multi-task | All peripherals combined |
| 10 | RTOS Basics | FreeRTOS, task scheduling |

## Hardware | 硬件

- MCU: STM32F103C8T6 (Blue Pill) or STM32F446RE (Nucleo)
- Debugger: ST-Link V2
- IDE: STM32CubeIDE

## How to Use | 使用方法

1. Open STM32CubeIDE
2. Import project: File → Import → Existing Projects
3. Select the lab folder
4. Build and flash

## Wiring | 接线

Each lab folder contains a `wiring.txt` file with pin connections.

## Project Structure | 项目结构

```
Lab_01_LED_Blink/
├── Core/Src/main.c        # Main code
├── Core/Inc/main.h        # Header
├── .ioc                   # CubeMX config
└── wiring.txt             # Pin connections
```

## License

MIT
