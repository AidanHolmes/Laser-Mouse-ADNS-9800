# Amiga-Laser-Mouse-ADNS-9800

Project description: based on PIC18f23k22 microcontroller and ADNS-9800 Laser Gaming Sensor

PCB for the project: https://www.pcbway.com/project/shareproject/Amiga_Laser_Mouse.html

Updated to support V1.2 of the PCB on PCBWay. Reassigned pins to work correctly with board.

# Toolchain:
This project has been slightly modified for building on Raspberry Pi Debian Linux
SDCC 4.5.0
gputils 1.5.2
Flashed with Pickle 5.01

The bat files are unmodified and can run simulator and other code. These are unlikely to work with Windows as the makefile has updated.

# Build
make clean
make

builds amiga_mouse.hex in main directory.

Prebuild hex exists in builds directory. Flash this with Pickle using: p16 lvp program amiga_mouse.hex
