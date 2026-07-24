# ESP-QUICK
This is a custom ESP32 development board featuring an integrated OLED display for real-time status monitoring, alongside an auto-switching LiPo battery charging circuit with its own USB port. For fast prototyping.

## Technical Specs
 - Main module - ESP32-WROOM-32E (8MB)
 - USB TO UART chip - CP2102N-A02-GQFN24R
 - USB - TYPE-C-31-M-12
 - Charging IC - TP4056_C382139
 - OLED Display - HS96L03W2C03
 - LDO - AP2112K-3.3TRG1_C23380830
 - Battery connector - S2B-PH-SM4-TB(LF)(SN)

  <img width="561" height="355" alt="image" src="https://github.com/user-attachments/assets/ef78d967-f5d1-4c93-a489-7ac4c6bcd458" />
  
  YOU CAN ALSO DOWNLOAD THE GERBER, CPL AND BOM FILE IN .zip FOR DIRECT PCB MANUFACTURING!

## HOW TO USE
 - Connect the battery  to the battery conector
 - There is a SPDT Switch for switching in USB and Battery mode
 - Use the IO22 and IO23 for OLED Display
 - There are two buttons RST stands for Reset and USR stands for Boot

## DESIGN

## SCHEMATIC

<img width="1652" height="1170" alt="Schematic_ESP32-MODIFIED_2026-07-24" src="https://github.com/user-attachments/assets/5ccc563c-4102-439c-b741-b4a2f52ec6a8" />

## PCB LAYOUT

<img width="346" height="258" alt="image" src="https://github.com/user-attachments/assets/7e9cd68b-4c91-45b9-a39b-6d439db6fbb1" />

## TOP LAYER (SIGNAL)

 <img width="350" height="265" alt="image" src="https://github.com/user-attachments/assets/3375d9e1-c2ac-446d-a624-48bae6cc21b4" />

## INNER 1 (SIGNAL)

 <img width="345" height="269" alt="image" src="https://github.com/user-attachments/assets/81357c94-9819-4c40-8832-65c1371245b9" />

## INNER 2 (PLANE, GND)

 <img width="377" height="272" alt="image" src="https://github.com/user-attachments/assets/2e3cc47e-7fc7-4871-9324-f360812585d0" />

## BOTTOM LAYER (SIGNAL)

 <img width="392" height="260" alt="image" src="https://github.com/user-attachments/assets/9c732f2a-dd65-438f-af86-6e0e511db86b" />

## BOM 

<img width="2881" height="1074" alt="image" src="https://github.com/user-attachments/assets/26ab605e-66ad-4c49-bafb-7e5142e3a737" />
