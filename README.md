# SmartProject HC-SR04
A repository for smart project development

This project is to test sensor SC-HR04 with STM32L452RE Controller, using HAL library Input Capture function.

Step:

1.  Using STM32CubeMX generate UART1 with DMA, purpose to show the output at COM PORT TERMINAL. 
2.  Using STM32CubeMX activate input capture peripheral. 
    PORTC GPIO4 selected as trigger pin to HC-SR04. 
    PORTA GPIO8 is Timer1 input capture pin, connected to Echo pin at HC-SR04.
3.  After setup everything, using docklight to view the output.


