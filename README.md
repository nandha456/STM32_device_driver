# 🛠️ STM32F4 Series Device Drivers (Learning Repository)

> A bare-metal peripheral driver collection for the **STM32F4 microcontroller series**, designed specifically for **educational purposes** and hands-on embedded systems learning.

## 📖 Overview
This repository provides lightweight, well-documented drivers for common STM32F4 peripherals. The code is structured to be easily readable, modifiable, and extendable. Clone it, experiment with the registers, and adapt the drivers to fit your own projects or learning workflows.

## ✅ Currently Implemented Drivers
The following modules are complete and ready for integration:
- [x] **GCC** – ARM GCC toolchain configuration, startup files & linker scripts
- [x] **RCC** – Reset and Clock Control
- [x] **SYSCFG** – System Configuration Controller
- [x] **NVIC** – Nested Vectored Interrupt Controller
- [x] **EXTI** – External Interrupts/Events Controller
- [x] **USART** – Universal Synchronous/Asynchronous Receiver/Transmitter

## 🚀 Getting Started
1. **Clone the repository:**
   ```bash
   git clone https://github.com/nandha456/STM32_device_driver.git
   cd STM32_device_driver
   ```
2. **Integrate into your project:** Copy the contents of `/include` and `/src` into your bare-metal or RTOS workspace.
3. **Build & Flash:** Compile using `arm-none-eabi-gcc` and flash to your STM32F4 board via ST-Link, OpenOCD, or your preferred programmer.

> 💡 *Tip: Ensure your toolchain matches the `arm-none-eabi` architecture. Driver files are designed to be standalone and easy to drop into existing projects.*

## 🗺️ Roadmap & Future Development
This repository is actively maintained. Planned additions include:
- [ ] GPIO & Timer (TIM) drivers
- [ ] SPI, I2C & CAN peripherals
- [ ] DMA & ADC support
- [ ] Hardware abstraction layer (HAL) style wrappers
- [ ] Example projects & board-specific configurations

## 🤝 Contributing
Since this is a **learning-focused repository**, contributions and forks are highly encouraged! Whether you're optimizing a driver, adding a new peripheral, or fixing a bug:
- 🍴 Fork the repo
- 🌿 Create a feature branch
- 📤 Submit a Pull Request
- 💬 Open an Issue for discussions or feature requests

## 📜 License
This project is open-source and available under the [MIT License](LICENSE).  
*Feel free to use, modify, and distribute for personal, educational, or commercial projects.*

## 🙏 Acknowledgments
Thank you to the STM32 community, ARM documentation, and all developers who contribute to making embedded systems more accessible.  
**Happy coding & happy learning!** 🚀
