# LED Dot Matrix Scrolling Display using AT89C51

An embedded C project that implements a scrolling alpjanumeric message display using the AT89C51 microcontroller and four 8x8 LED dot matrix displays.
The project was developed as part of the EE 3008 Microcontrollers course to apply microcontroller programming, timer interrupts, shift registers, display multiplexing and hardware input handling.

## Features
1. Displays a scrolling aplhanumeric message across four 8x8 LED dot matrix displays
2. Supports upper letters A-Z
3. supports numbers 0-9
4. Uses a 5x7 character lookup table for character patterns
5. Scrolls the message continuously across the display
6. Supports bidirectional scrolling
7. Push buttons control to reverse the scrolling direction
8. Push button control to paues the resume the display
9. Uses Timer 0 interrupts for display refreshing
10. Uses shift registers to send display data
11. Uses Row multiplexing to control the lED matrices

## Hardware and Software
Microcontroller: AT89C51
Complier: keil C51 complier for 8051
Display: Four 8x8 LED dot matrix displays (Total display width - 32 coloumns)
SHift RegisterL 74HC595 serial-in parallel out registers
User Controls: 
Button 1 - reverse Scrolling Direction
Button 2 - Pause or resume scrolling

## Display Message
The message displayed by the program is: WELCOME TO ABU 2026
The message is stored in the program as: unsigned char code message[] = "      WELCOME TO ABU 2026 "
