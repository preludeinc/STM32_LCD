# STM32_LCD
LCD configuration files were ported from files initially writen for the PIC18F4685. 
The author's name and course name are displayed and an alien character scrolls left and right across the second-line of the LCD screen.

This file doesn't contain every configuration file included in the project (such as stm32f4xx_hal_conf.h, stm32f4xx_it, stm32f4xx_hal_msp.c among others) as some were auto-generated by the STM32CubeIDE and the functionality contained in these files is not necessarily heavily utilized in this project - it doesn't make use of interrupts for example.
