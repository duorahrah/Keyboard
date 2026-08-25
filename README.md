# Custom 75% Mechanical Keyboard
Designed and built fully custom mechanical keyboard end-to-end, PCB design (KiCad), case design (Onshape) and 3D printing, and firmware (QMK on RP2040).\
<img width="353" height="128" alt="image" src="https://github.com/user-attachments/assets/d6153cfe-5eed-4602-bab4-caacfde0722e" />

## PCB Design
<img width="539" height="219" alt="image" src="https://github.com/user-attachments/assets/217463de-bb8e-4ffa-8f7e-20e498705dfc" />
<img width="203" height="150" alt="image" src="https://github.com/user-attachments/assets/7ae6235d-4f7e-4e62-8564-b6d8eb202858" />
<img width="332" height="148" alt="image" src="https://github.com/user-attachments/assets/0643f9e8-a754-483a-a976-f731d8e7cfec" />
<img width="295" height="166" alt="image" src="https://github.com/user-attachments/assets/7ff9d169-b1da-4953-b0fa-2151d0e63a41" /><br/>
-	Designed a RP2040-based custom mechanical keyboard PCB in KiCad with full keyboard matrix and USB-C connectivity
-	Includes full RP2040 support circuitry (crystal, QSPI flash, decoupling, reset and BOOTSEL)
-	Routed and manufactured the PCB

## Case Design
<img width="307" height="136" alt="image" src="https://github.com/user-attachments/assets/d922f731-d2cf-4608-8f65-9b2819f292df" />
<img width="323" height="189" alt="image" src="https://github.com/user-attachments/assets/460011c0-a930-4467-9488-63b0b44d4c7d" /><br/>
-	Modeled custom case in Onshape, accounting for PCB mounting points, USB-C cutout, and switch plate clearance 


## Firmware
-	Developed custom QMK firmware for the keyboard, including multi-layer keymap and matrix/layout configuration to match the custom PCB design


## Challenges
-	USB and RP2040 debugging – I encountered an issue where the keyboard could not be detected by my computer while trying to flash the firmware. I was able to identify the issue as a short between the D+/D- connections through systematic multimeter-based debugging and fix it.
-	3D printer calibration - Case was printed using secondhand ELEGOO Neptune 4 Max, a printer which is known to be finnicky. I did research and looked at experiences from others who had the same printer to learn how to properly calibrate the printer, including replacing the bed springs with silicon spacers, and altering the printer’s configuration file to automatically level the bed and generate a printing mesh. 
-	Obtaining tools and materials – I was unable to gain access to public/free 3D printers over the summer, so I purchased a secondhand printer off Facebook Marketplace. The PCB and parts were ordered from JLCPCB and DigiKey (including $40 for international shipping D:). 

## Results
-	Successfully designed, manufactured, and assembled a working mechanical keyboard for daily use
-	Gained experience across PCB design, mechanical design, manufacturing, firmware development, and hardware debugging 
