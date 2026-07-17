# LAB_14
Simple Bootloader STM32 Programming with STM32F103C8T6 Blue Pill C++ in STM32
**Software Requirements**
STM32CubeIDE
STM32CubeMX (Integrated with STM32CubeIDE)
STM32 HAL Drivers
GNU Arm Embedded Toolchain
STM32CubeProgrammer (Optional)
USB Serial Terminal (PuTTY, Tera Term, RealTerm, or Serial Monitor)  
**STM32CubeMX Configuration**
Create a new project for STM32F103C8Tx.
Enable the USB Device (Full Speed) peripheral.
Select Communication Device Class (CDC).
Configure the USB clock to 48 MHz.
Enable the USB Device middleware.
Configure the system clock.
Generate the project using C++.
**Project Features**
USB CDC (Virtual COM Port) implementation
Object-Oriented C++ design
USB initialization using STM32 HAL
Bidirectional USB serial communication
USB transmit and receive APIs
Interrupt-driven data reception
Circular buffer for efficient data handling
Reusable USB Serial Port driver
**
Repository Structure**
├── Core
│   ├── Inc
│   └── Src
├── USB_DEVICE
│   ├── App
│   └── Target
├── Middlewares
├── Drivers
├── .ioc
├── README.md
└── LICENSE

If you have any questions, suggestions, or encounter any issues while using this project, feel free to reach out.
**Email: ahsanbasharatali38@gmail.com**
I'll be happy to help and will respond as soon as possible.
