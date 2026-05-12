# BareMetal-Drivers

Low-level bare-metal peripheral drivers for STM32 microcontrollers written completely from scratch using direct register access without vendor HAL libraries.

---

## Overview

`BareMetal-Drivers` is a collection of peripheral drivers and embedded firmware examples developed using pure bare-metal programming techniques.  
The project focuses on understanding the internal working of STM32 peripherals at the register level.

The repository includes drivers and examples for:

- GPIO
- UART
- SPI
- I2C
- ADC
- Timers
- SysTick
- Interrupts
- DMA
- Input Capture
- Output Compare

All implementations are developed without STM32 HAL or LL libraries.

---

## Features

- Direct register-level programming
- No STM32 HAL dependency
- Lightweight and fast
- Educational and reusable driver implementations
- Modular project structure
- Interrupt-driven communication support
- DMA support
- Timer peripheral applications
- ADC continuous and single conversion modes

---

## Repository Structure

```text
BareMetal-Drivers/
│
├── 0_led_toggle_addr/
├── 1_led_toggle_addr_struct/
├── 2_gpio_output/
├── 3_gpio_bsr/
├── 4_gpio_input/
├── 5_uart_tx/
├── 6_uart_printf/
├── 7_uart_modular/
├── 8_uart_rx/
├── 9_adc_single_conversion/
├── 10_adc_continuous_conversion/
├── 11_systick_delay/
├── 12_timers/
├── 13_outputCompare/
├── 14_inputCapture/
├── 15_timerInterrupt/
├── 16_uart_rx_interrupt/
├── 17_ADC_Interrupt/
├── 18_systick_interrupt/
├── 19_timer_interrupt/
├── 20_uart_tx_dma/
├── 21_i2c_adxl345/
├── 22_spi_adxl345/
│
├── LICENSE
└── README.md
```

---

## Technologies Used

- Embedded C
- ARM Cortex-M
- STM32 Microcontrollers
- CMSIS
- UART / SPI / I2C Protocols
- DMA
- Interrupt Programming

---

## Development Environment

### Hardware

- STM32 Nucleo Board
- STM32F4 Series MCU
- ADXL345 Accelerometer
- USB-UART Debug Interface

### Software

- STM32CubeIDE
- ARM GCC Toolchain
- OpenOCD / ST-Link

---

## Drivers Included

| Driver | Description |
|---|---|
| GPIO | Digital Input/Output Control |
| UART | Serial Communication |
| SPI | SPI Peripheral Communication |
| I2C | I2C Peripheral Communication |
| ADC | Analog to Digital Conversion |
| Timers | Delay, PWM, Capture, Compare |
| SysTick | Timing and Delay Functions |
| DMA | Peripheral Data Transfer |
| Interrupts | NVIC and ISR Handling |

---

## Learning Objectives

This project was developed to:

- Understand STM32 architecture deeply
- Learn peripheral register mapping
- Develop reusable embedded drivers
- Gain practical embedded systems experience
- Improve firmware development skills

---

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/Abinav2006/BareMetal-Drivers.git
```

### Open Project

Import the required example folder into STM32CubeIDE.

### Build and Flash

1. Connect STM32 board
2. Build the project
3. Flash using ST-Link
4. Monitor output through serial terminal if required

---

## Example Modules

### UART Transmission

- Polling-based UART TX
- Modular UART driver
- UART RX interrupt handling
- UART DMA transfer

### ADC

- Single conversion mode
- Continuous conversion mode
- ADC interrupt handling

### Timers

- Delay generation
- Timer interrupts
- Input capture
- Output compare

### Sensor Interfaces

- ADXL345 using I2C
- ADXL345 using SPI

---

## Why Bare-Metal Programming?

Bare-metal development provides:

- Better hardware understanding
- Lower memory overhead
- Faster execution
- Fine-grained peripheral control
- Strong embedded systems fundamentals

---

## Future Improvements

- PWM Driver
- RTC Driver
- CAN Driver
- USB Driver
- FreeRTOS Integration
- Generic Driver APIs
- Documentation for each peripheral

---

## License

This project is licensed under the MIT License.

---

## Author

**Abinav S**
