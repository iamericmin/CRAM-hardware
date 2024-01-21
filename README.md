# CRAM-hardware
CRAM Altium design files

# CRAM (Compact Rapid Acquisition Machine)
A simple microcontroller board designed for data acquisition and transmission over CAN bus.

## PERIPHERALS
STM32F407VET6 running at 168MHz

16MB SPI PSRAM

16MB SPI Flash

32Kb I2C EEPROM

2x TJA1051 CAN transceivers

DS3231 I2C RTC with battery backup

micro SD slot

2x Neopixels

## POWER SUPPLY
TSR1-2450 DC/DC buck converter, 6.5V - 32V DC in, 5V out

LM1117 3.3V linear voltage regulator, 3.3V out

LM317 adjustable linear voltage regulator

LTC4412 power management IC. Automatically switches to USB power if both battery and USB is connected

LT1054 charge pump regulator, -5V out

## CONNECTORS
15 Analog In, 2 Analog Out, 47 Digital in/out with two 2x14 2.54mm pitch male pin headers

2x5 1.27mm pitch Cortex debug header

Pi Pico debug probe connectors for both serial and SWD

micro SD slot

12mm coin cell battery connector for RTC backup

2x Molex Picoblade 4-pin connectors for CAN bus

2x JST-SH 4-pin connectors for WHAM power supply

2x7 2.54mm pitch male pin headers for power supply

XT-30 battery connector

Mini-USB connector

#

Purdue Formula SAE

Designed by Eric Min







