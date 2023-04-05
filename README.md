# Tokamac LC/Sonnet Presto 040
  
This is a recreation of the Tokamac LC accelerator. Sonnet sold the same board as the Presto 040.
Supported Macs are the LC, LCII and Color Classic and their Performa variants.
The schematics have been reverse engineered and a new PCB was created based on the schematics.
  
![fully populated board](/TokamacLC_Populated.jpg)
  
The provided PCB files are licensed under CC-BY-NC-SA - they are NOT intended for commercial use.  
  
  
  
# Notes
  
The only programmable part on this accelerator is a XC1736 PROM at U15 that holds the configuration for the XC3030 FPGA.
Reset polarity should be set to high when programming the ROM.
  
# Board Files
  
The provided gerber files have been generated using the JLCPCB EAGLE cam job files.  

# Partlist

Part|Value|Package
---|---|---
AR1|100|R1206
AR2|100|R1206
C1|  100nF|  C1206
C2|  100nF|  C1206
C3|  100nF|  C1206
C4|  100nF|  C1206
C5|  100nF|  C1206
C6|  100nF|  C1206
C7|  100nF|  C1206
C8|  100nF|  C1206
C9|  100nF|  C1206
C10|100nF|  C1206
C11|100nF|  C1206
C12|100nF|  C1206
C13|100nF|  C1206
C14|100nF|  C1206
C15|100nF|  C1206
C16|100nF|  C1206
C17|100nF|  C1206
C18|100nF|  C1206
C19|100nF|  C1206
C20|100nF|  C1206
C21|100nF|  C1206
C22|100nF|  C1206
C23|100nF|  C1206
C24|100nF|  C1206
C25|100nF|  C1206
C26|100nF|  C1206
C27|100nF|  C1206
C28|100nF|  C1206
C29|100nF|  C1206
C30|100nF|  C1206
C31|100nF|  C1206
C32|22uF|    C/6032
C33|22uF|    C/6032
C34|22uF|    C/6032
K1|  DIN41612 96pin
L1|  inductor/choke|L1812
L2|  inductor/choke|L1812
QG1 |    50MHz 5V oscillator  |   DIL14S
R1|  10k|R1206
R2|  10k|R1206
R3|  10k|R1206
R4|  10k|R1206
R5|  10k|R1206
R6|  10k|R1206
R7|  10k|R1206
R8|  10k|R1206
R9|  10k|R1206
R10|10k|R1206
R11|1M| R1206
R12|1k|  R1206 
R13|10k|R1206
R14|10k|R1206
R18|62  (22-82)|     R1206
R19|62  (22-82)|     R1206
U1|  68040RC25|PGA179
U2|  74FCT244 |    SO20W
U3|  74ACT374  |   SO20W
U4|  74ACT374  |   SO20W
U5|  74ACT244  |   SO20W
U6|  74FCT521  |   SO20W
U7|  74F125D|  SO14
U8|  74ACT244DW   |  SO20W
U9|  74ACT244DW  |   SO20W
U10|74ACT244DW  |   SO20W
U11|XC3030-100|QFP-100
U13|74ACT04D| SO14
U14|74ACT74D| SO14
U15|XC1736|   DIL8
U16|MC88915|  PLCC-28
U17|74F00D|   SO14
