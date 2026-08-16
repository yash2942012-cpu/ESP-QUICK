# ESP-QUICK
This is a custom ESP32 development board featuring an integrated OLED display for real-time status monitoring, alongside an manual-switching LiPo battery charging circuit with its own USB port. For fast prototyping.

This is the OSHWLab view only link for this project

https://oshwlab.com/yash2942012/project_zcipnwhr

## Technical Specs
 - Main module - ESP32-WROOM-32E (8MB)
 - USB TO UART chip - CP2102N-A02-GQFN24R
 - USB - TYPE-C-31-M-12
 - Charging IC - TP4056_C382139
 - OLED Display - HS96L03W2C03
 - LDO - AP2112K-3.3TRG1_C23380830
 - Battery connector - S2B-PH-SM4-TB(LF)(SN)

 <img width="458" height="327" alt="Screenshot 2026-08-06 184804" src="https://github.com/user-attachments/assets/58eed62f-9d7e-4776-82c6-ec8cae3c0e55" />
  
  YOU CAN ALSO DOWNLOAD THE GERBER, CPL AND BOM FILE IN .zip FOR DIRECT PCB MANUFACTURING!

## HOW TO USE
 - Connect the battery  to the battery conector
 - There is a SPDT Switch for switching in USB and Battery mode
 - Use the IO22 and IO23 for OLED Display
 - There are two buttons RST stands for Reset and USR stands for Boot

## DESIGN

## SCHEMATIC

<img width="3295" height="2322" alt="SCH_ESP32 MODIFIED_1-Sheet_1_2026-08-15" src="https://github.com/user-attachments/assets/a9ee0d08-bc1c-4248-b4e8-f6a113f5b6a9" />


## PCB LAYOUT

<img width="2160" height="1796" alt="PCB_PCB_ESP32 MODIFIED_2026-08-15" src="https://github.com/user-attachments/assets/650a2469-1fa6-4853-b535-bed80d00b4ac" />

## TOP LAYER (SIGNAL)

<img width="2160" height="1796" alt="PCB_PCB_ESP32 MODIFIED_2026-08-15 (1)" src="https://github.com/user-attachments/assets/0408c979-9f59-4e32-8300-87ed0adbf906" />

## INNER 1 (SIGNAL)

<img width="2160" height="1796" alt="PCB_PCB_ESP32 MODIFIED_2026-08-15 (3)" src="https://github.com/user-attachments/assets/db5d4619-5830-4736-8550-316343413fe4" />

## INNER 2 (PLANE, GND)

<img width="2160" height="1796" alt="PCB_PCB_ESP32 MODIFIED_2026-08-15 (4)" src="https://github.com/user-attachments/assets/99a4f98d-7a49-4d47-8488-1946bf1916ae" />

## BOTTOM LAYER (SIGNAL)

<img width="2160" height="1796" alt="PCB_PCB_ESP32 MODIFIED_2026-08-15 (2)" src="https://github.com/user-attachments/assets/98f2fe13-48b4-4048-a9cd-4103bb273a8b" />

## BOM 

﻿Quantity	 	|Supplier	 |Part ID      |Price    	|link                                                                                                        |
-----------|----------|-------------|----------|------------------------------------------------------------------------------------------------------------|
"2"	       |"LCSC"	   |"C57369"  	  |"0.071"  	|"https://item.szlcsc.com/58403.html"                                                                        |
"1"	       |"LCSC"	  	|"C124378" 	  |"0.056"	  |"https://item.szlcsc.com/502959.html"                                                                       |
"1"	       |"LCSC"	  	|"C368809" 	  |"0.022"	  |"https://item.szlcsc.com/15869.html"                                                                        |
"5"	       |"LCSC"		  |"C1525"	     |"0.005"  	|"https://item.szlcsc.com/15869.html"                                                                        |
"3"       	|"LCSC"	  	|"C315248"	   |"0.055"	  |"https://item.szlcsc.com/15869.html"                                                                        |
"1"       	|"LCSC"		  |"C602037" 	  |"0.329"	  |"https://item.szlcsc.com/373011.html"                                                                       |
"2"	       |"LCSC"	  	|"C19702"	    |"0.041"	  |"https://item.szlcsc.com/362304.html"                                                                       |
"1"	       |"LCSC"		  |"C295747"	   |"0.215"	  |"https://item.szlcsc.com/280164.html"                                                                       |
"2"	       |"LCSC"		  |"C84256"	    |"0.013"   |"https://item.szlcsc.com/255094.html"                                                                       |
"1"	       |"LCSC"		  |"C2297"	     |"0.016"	  |"https://item.szlcsc.com/255094.html"                                                                       |
"1"	       |"LCSC"    |"C2297"      |"0.016"   |"https://item.szlcsc.com/88042.html"                                                                        |
"2"	       |"LCSC"		  |"C164886"	   |"0.017"	  |"https://www.lcsc.com/product-detail/C164886.html"                                                          |
"4"	       |"LCSC"		  |"C11702"	    |"0.002"  	|"https://item.szlcsc.com/323315.html"                                                                       |
"8"       	|"LCSC"		  |"C25744"	    |"0.002"  	|"https://item.szlcsc.com/323315.html"                                                                       |
"1"       	|"LCSC"	  	|"C43473"	    |"0.005"	  |"https://item.szlcsc.com/323315.html"                                                                       |
"1"	       |"LCSC"	  	|"C25896"	    |"0.002"  	|"https://item.szlcsc.com/323315.html"                                                                       |
"1"	       |"LCSC"	  	|"C25126"	    |"0.001"  	|"https://item.szlcsc.com/323315.html"                                                                       |
"3"	       |"LCSC"		  |"C25905"	    |"0.007"	  |"https://item.szlcsc.com/323315.html"                                                                       |
"1"	       |"LCSC"	  	|"C22765"	    |"0.011"	  |"https://www.lcsc.com/product-detail/C22765.html"                                                           |
"2"       	|"LCSC"	  	|"C23162"	    |"0.012"	  |"https://jlcpcb.com/partdetail/C23162"                                                                      |
"2"       	|"LCSC"		  |"C221869"	   |"0.418"	  |"https://item.szlcsc.com/279067.html"                                                                       |
"1"       	|"LCSC"		  |"C48601057"	 |"0.165"	  |"https://item.szlcsc.com/datasheet/SS12D06G5/50871453.html"                                                 |
"3"       	|"LCSC"		  |"C5246195"	  |"0.043"	  |"https://lcsc.com/product-detail/TVS_ESD5Z5V0C_C129211.html"                                                |
"1"	       |"LCSC"		  |"C969151"	   |"2.274"	  |"https://item.szlcsc.com/245167.html"                                                                       |
"1"	       |"LCSC"		  |"C701342"	   |"4.54"	   |"https://www.lcsc.com/product-detail/C701342.html"                                                          | 
"1"       	|"LCSC"		  |"C5248080"	  |"2.33"	   |"https://www.lcsc.com/product-detail/C5248080.html"                                                         |
"1"	       |"LCSC"		  |"C382139"	   |"0.119"	  |"https://www.mornsun.cn/html/pdf/SCM1501B.html"                                                             |
"1"	       |"LCSC"		  |"C23380830"	 |"0.11"    |"https://www.lcsc.com/product-detail/C23380830.html"                                                        |
"1"	       |"LCSC"		  |"C165948"	   |"0.186"  	|"https://item.szlcsc.com/datasheet/TYPE-C-31-M-12/177331.html"                                              |
"3"       	|"LCSC"		  |"C86471"    	|"0.404"	  |"https://item.szlcsc.com/366904.html"                                                                       |
