# bw16-safe
This project is about a proximity smart safe using both hardware and software. It uses a commercial smart ring and a BW16 microcontroller to unlock a 3D-printed safe via Bluetooth Low Energy (BLE).

**How does it work? **
The system continuously scans for BLE devices. When the smart ring comes within a specific signal threshold, the BW16 board triggers a solenoid lock to open the safe.

However, there are still some limitations and issues, such as spoofing. 

Hardware: BW16 (RTL8720DN) Microcontroller, Smart Ring, Solenoid Lock, Flyback Diodes.
Software: C++ / Arduino IDE.
design/enclosure: KiCad (PCB), Blender/BambuStudio.


Media:

