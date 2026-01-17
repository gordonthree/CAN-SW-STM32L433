# DC Power Distribution Module Controller
Compact controller board intended to interface with as many as four smart switch modules. Analog inputs for current and voltage sensing allow the controller to interrupt a load in place of a mechanical fuse or circuit breaker. An isolated CAN-FD interface provides expansion capability with other boards, displays and sensors.

<img src="https://github.com/gordonthree/CAN-SW-STM32L433/blob/main/CAN-SW-STM32L433.png?raw=true" width=480 alt="3d rendering of circuit board">

# Control Node
* STM32L433 Microcontroller
* 3-pin terminal block for CANBUS connection with drain
* Pin-header connections for Profet Smart Switch modules
* Analog inputs for voltage and current sensing
* Jumper selected CAN terminator resistor
* LED indicator for 3.3v power
* LED indicator for status, controlled by the micro
* Bidirectional transient voltage protection diode for harsh environments
* Debugging header for UART1 serial port as well as SWLINK programming 

  
