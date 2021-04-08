# PIC18F-MCU-with-a-DC-Motor-Using-PWM-Mode-and-C

## Description:

It is desired to change the speed of a DC motor by dynamically changing its pulse
width using a potentiometer connected at bit 0 of PORTB. Note that
the PWM duty cycle is controlled by the potentiometer. 

Write a PIC18F assembly language program that will input the potentiometer voltage via the PIC18F4321’s on‑chip A/D converter using interrupts, generate the PWM waveform on the
CCP1 pin, and then change the speed of the motor as the potentiometer voltage is
varied.
