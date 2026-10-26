# bw16-safe
This project is about a proximity smart safe using both hardware and software. It uses a commercial smart ring and a BW16 microcontroller to unlock a 3D-printed safe via Bluetooth Low Energy (BLE).

How does it work?

The system continuously scans for BLE devices. When the smart ring comes within a specific signal threshold, the BW16 board triggers a solenoid lock to open the safe.

However, there are still some limitations and issues, such as spoofing. This is because the ring I used is a commercial ring, which means using UUID is not feasible 

Tools: 
Hardware: BW16 (RTL8720DN) Microcontroller, Smart Ring, Solenoid Lock, Flyback Diodes.
Software: C++ / Arduino IDE.
Design/Enclosure: KiCad (PCB), Blender/BambuStudio.


Media:

<img width="508" height="498" alt="Screenshot 2026-08-30 at 5 47 41 PM" src="https://github.com/user-attachments/assets/8e85a0bb-a148-4e09-a415-129b9a8f8b65" />


<img width="657" height="475" alt="Screenshot 2026-10-22 at 10 40 28 PM" src="https://github.com/user-attachments/assets/d44252c6-6f3d-4d83-bdd1-3bc5484bbd3f" />






