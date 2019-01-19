# STM32-ublox-UART
In this project, **STM32F407** recieved GPS data from **ublox-neo-7M** GPS receiver module in **UBX** format.

### Features
* **STM32CubeMX** software used to config STM32F407 microcontroller.
* **HAL** library used.
* **UART** interface used for communication.
* Data received in UBX format.
* Required data fetched from **NAV-PVT**'s class of GPS receiver.
* As a result, important parameters(Lat, Long, Altitude and NED velocities) displayed on serial terminal. 

### Configuration
* **UART2** used for displaying data on serial terminal.
* **UART3** used for communicating with GPS module.

