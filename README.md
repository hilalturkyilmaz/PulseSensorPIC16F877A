# Pulse Sensor for PIC16F877A

This project was prepared for the **Istanbul Medipol University 2023-2024 Spring Semester Microprocessors Course** by:

- **Vagif Jafarlı** 61210018
- **Yusuf Emir Fil** 64210102
- **Hilal Türkyılmaz** 9A190001

## Project Overview

The circuit design involves connecting the pulse sensor to the analog input pin of the **PIC16F877A** microcontroller. The **20 MHz crystal** and **33pF capacitors** are connected to the oscillator pins of the microcontroller to provide the necessary clock signal. A **4.7k resistor** is used as a pull-up resistor for the microcontroller's input pin. The **16x2 LCD** is connected to the digital output pins of the microcontroller, and a **10k potentiometer** is used to control the contrast of the LCD.

## Software and Microcontroller Setup

The software for the microcontroller is written in **C**, utilizing the **MPLAB IDE** and **XC8 compiler**. The program includes initialization routines for both the **LCD** and **ADC (Analog-to-Digital Converter)**, as well as an interrupt service routine to handle the input from the pulse sensor. The heart rate is calculated by measuring the time interval between consecutive pulses and is then displayed on the LCD.

## System Functionality

The heart rate measurement system successfully measures and displays the heart rate of an individual in real-time. The use of the **PIC16F877A microcontroller**, along with the supporting components, ensures accurate and reliable performance.

## Future Improvements

This project demonstrates the effective use of a microcontroller and peripheral components to design a functional heart rate measurement system. The system can be further enhanced by adding features such as:

- Data logging
- Wireless transmission of heart rate data
- Integration with mobile applications for extended monitoring capabilities

## Conclusion

By leveraging the capabilities of the **PIC16F877A microcontroller**, this project provides a solid foundation for further exploration and development in the field of **biomedical engineering** and **health monitoring systems**.

