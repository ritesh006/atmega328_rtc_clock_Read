# ATmega328 RTC Clock Read

This repository contains code for reading time from RTC modules DS1307 and DS3231 using an ATmega328 microcontroller. The code utilizes a custom UART library for serial communication to display time data on the serial monitor.

## Getting Started

### Open the project in VS Code with PlatformIO or Arduino IDE

1. **Connect the RTC Module:**
   - Connect the DS1307 or DS3231 RTC module to the Arduino Uno board.

2. **Open Project:**
   - Open the `atmega328_rtc_clock_Read` project in either VS Code with PlatformIO or Arduino IDE.

3. **Upload Code:**
   - Upload the code to the Arduino Uno board.

4. **View Time:**
   - Open the serial monitor to view the time read from the RTC module.

## Custom UART Library

The custom UART library provides the following functionalities:

- Initialize UART communication.
- Send and receive data.
- Display time data on the serial monitor.

## Contributing

Contributions are welcome! Fork this repository and submit pull requests for improvements or bug fixes.

## Acknowledgements

- Inspiration from various RTC interfacing projects and custom UART library implementations.
- Thanks to the open-source community for providing valuable resources and tools.

## Contact

For questions or inquiries, please contact [ritesh.kumar0793@gmail.com](mailto:ritesh.kumar0793@gmail.com).
