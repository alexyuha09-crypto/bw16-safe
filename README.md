# bw16-safe
This project is about a proximity smart safe using both hardware and software. It uses a commercial smart ring and a BW16 microcontroller to unlock a 3D-printed safe via Bluetooth Low Energy (BLE).

**How does it work? **
The system continuously scans for BLE devices. When the smart ring comes within a specific signal threshold, the BW16 board triggers a solenoid lock to open the safe.

However, there are still some limitations and issues, such as spoofing. 

Tools: 
Hardware: BW16 (RTL8720DN) Microcontroller, Smart Ring, Solenoid Lock, Flyback Diodes.
Software: C++ / Arduino IDE.
Design/Enclosure: KiCad (PCB), Blender/BambuStudio.


Media:

<img width="508" height="498" alt="Screenshot 2026-08-30 at 5 47 41 PM" src="https://github.com/user-attachments/assets/8e85a0bb-a148-4e09-a415-129b9a8f8b65" />


<img width="654" height="531" alt="Screenshot 2026-10-20 at 8 31 45 AM" src="https://github.com/user-attachments/assets/7a524939-35c8-478f-81e3-1c19020b3267" />


