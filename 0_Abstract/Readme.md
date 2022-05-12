# Wiper Control System
car wiper control system using the STM32F4xx-discovery board.

Car wipers have a DC motor that controls their action, but the STM32F4xx-discovery does not have any motor, so we are considering LEDs for this application, as the wiper control system.
There are four LEDs and a Push Button on the STM32F4xx-discovery board. These LEDs are orange, green, red, and blue in color. With the Discovery board, four user LEDs are connected to the PD12,PD13,PD14 and PD15 pins of PORTD through a current limiting resistor.
GPIO pins of STM32F407VG microcontroller will be configured as digital input pins to enable a push button to operate with STM32F4.
If you press the user button and hold it for two seconds, the Red LED turns on, indicating the ignition key is positioned at the ACC. In addition, the LEDs are blinking, which indicates the wipers are ON. 
