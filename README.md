# Ernest Slave Node Schematics
Eagle files for data collection nodes

[Master Project Repo](https://github.com/rschlaikjer/Ernest)

## What is this
Ernest is the next step of the [ArNest](https://github.com/rschlaikjer/ArNest),
and takes it from a single-location thermostat to a many node system consisting
of a base station and one or more smaller nodes that collect and report
atmospheric data to the base. This way the system can monitor multiple rooms, as
well as the outside conditions.

These EAGLE files show the schematic for hooking up the slave nodes, as well as
a board layout for printing your own slave boards.

For the code to run on the slave nodes,
[see here](https://github.com/rschlaikjer/ernest-slave-code).

## Parts list
(All prices per unit and approximate)

- ($2.00) Atmega 328P (with arduino-style bootloader)
- ($3.19) USB FTDI programmer
- ($1.50) BMP180 breakout board
- ($13.75) (Optional) HIH-6130 humidity sensor
- ($0.98) nrf24L01 wireless transciever
- ($0.39) LM1117 3.3V regulator
- ($0.07) 16 MHz crystal oscillator
- ($0.03) 22pF capacitors
- ($0.08) Momentary reset switch
- ($0.32) 4-pin DIP switch
- ($0.01) 320 Ohm resistors
- ($0.03) LEDs
- ($0.30) 2.5mm barrel jack (for power)

**Total BOM: Approx. $5.86 per board** + 13.75 for humidity, as well as the cost
of PCB manufacture.

## Pretty Pictures

![Schematic](/ernest_schematic.png?raw=true "Schematic")

![Board Layout](/ernest_board.png?raw=true "Board Layout")

![Current Prototype](/rev4.jpg?raw=true "Current prototype")
