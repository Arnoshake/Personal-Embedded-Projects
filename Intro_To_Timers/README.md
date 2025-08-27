# STM32 UART & Timer Learning Notes

This project documents my learning process with STM32 microcontrollers, focusing on:

- Understanding **UART** communication and how to send data to a PC.
- Using **PuTTY** to observe UART output and verify functionality.
- Configuring the **system clock** and timers to measure elapsed time accurately.

## Learning Summary

Through this project, I explored how to:

- Initialize peripherals using STM32CubeIDE.
- Send and format data over UART using `HAL_UART_Transmit`.
- Set up timers to measure microsecond-scale intervals.
- Understand the relationship between clock configuration, timer prescalers, and measured time.

## Reflections

- I experimented with reading timer values and calculating time displacement, which helped me understand timing and delays in embedded systems.
- Using PuTTY to visualize UART output reinforced how microcontrollers communicate with a PC in real time.
- Adjusting clock settings deepened my understanding of how MCU timing and peripheral behavior are interconnected.

This repository serves as a personal record of my hands-on experimentation and growing familiarity with STM32 peripherals, rather than as a step-by-step guide for others.

