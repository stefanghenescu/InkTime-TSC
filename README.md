# InkTime TSC

## Block Diagram
![Block Diagram](./Images/Block%20diagram%20InkTime.png)

---

## Bill of Materials (BOM)

| Name | Component Type | Package | Part Number / Value | Qty | JLCPCB Part Link | Datasheet Link |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **U1** | MCU | AQFN-74 | NRF52840 | 1 | [View Part](https://jlcpcb.com/partdetail/NordicSemicon-NRF52840_QIAAR/C190794) | [View Datasheet](https://resources.ampheo.com/static/datasheets/nordic-semiconductor/nrf52840-qiaa-r-rev2.pdf) |
| **IC1** | LiPo Charger | DSBGA-8 | BQ25180YBGR | 1 | [View Part](https://jlcpcb.com/partdetail/TexasInstruments-BQ25180YBGR/C3682423) | [View Datasheet](https://www.ti.com/lit/ds/symlink/bq25180.pdf?ts=1776583277258) |
| **IC2** | Haptic Driver | DSBGA-9 | DRV2605YZFR | 1 | [View Part](https://jlcpcb.com/partdetail/TexasInstruments-DRV2605YZFR/C81079) | [View Datasheet](https://www.ti.com/lit/ds/symlink/drv2605.pdf) |
| **IC3** | IMU / Accelerometer | LGA-12 | BMA423 | 1 | [View Part](https://jlcpcb.com/partdetail/BoschSensortec-BMA421/C5242966) | [View Datasheet](https://files.pine64.org/doc/datasheet/pinetime/BST-BMA421-FL000.pdf) |
| **IC9** | DC/DC Converter | 15-WL-CSP | RT6160AWSC | 1 | [View Part](https://jlcpcb.com/partdetail/RichtekTech-RT6160AWSC/C7065276) | [View Datasheet](https://www.lcsc.com/datasheet/C7065276.pdf?spm=wm.sxq.inf.ggs___wm.ssy.bg.0.xh&lcsc_vid=RVILV1QAFgMLXlRXRFQPBVVeFgVaXwJQTwdfAlJXFAUxVlNRQVReUlFfQVZbUTsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D) |
| **U3** | Fuel Gauge | TDFN-8 | MAX17048G+T10 | 1 | [View Part](https://jlcpcb.com/partdetail/2777647-MAX17048GT10/C2682616) | [View Datasheet](https://www.analog.com/media/en/technical-documentation/data-sheets/max17048-max17049.pdf) |
| **ANT1** | Chip Antenna | ANTC3216 | 2450AT18B100E | 1 | [View Part](https://jlcpcb.com/partdetail/JohansonDielectrics-2450AT18B100E/C2917717) | [View Datasheet](https://www.johansontechnology.com/docs/1187/2450AT18B100_X8XXogU.pdf) |
| **J1** | FPC Connector | 5034802400 | 503480-2400 | 1 | [View Part](https://jlcpcb.com/partdetail/MOLEX-5034802400/C122434) | [View Datasheet](https://www.mouser.com/datasheet/2/276/2/5034802400_FFC_FPC_CONNECTORS-1112921.pdf?srsltid=AfmBOoqeIvrMEurBUIMiLpCQbdFw00xQXV8qCybaZ2IhZAIdW5Bf1d4q) |
| **J2** | Debug Connector | TC2030IDC | TC2030-IDC | 1 | - | [View Datasheet](https://www.tag-connect.com/wp-content/uploads/bsk-pdf-manager/2019/12/TC2030-IDC-Datasheet-Rev-B.pdf) |
| **J4** | USB-C Connector | KH-TYPE-C-16P | KH-TYPE-C-16P | 1 | [View Part](https://jlcpcb.com/partdetail/Shenzhen_KinghelmElec-KH_TYPE_C16P/C709357) | [View Datasheet](https://www.lcsc.com/datasheet/C709357.pdf) |
| **Q1** | P-Channel MOSFET | SOT23-3 | DMG2305UX-7 | 1 | [View Part](https://jlcpcb.com/partdetail/DiodesIncorporated-DMG2305UX7/C150470) | [View Datasheet](https://www.lcsc.com/datasheet/C150470.pdf?spm=wm.sxq.inf.ggs___wm.ssy.bg.0.xh&lcsc_vid=RVILV1QAFgMLXlRXRFQPBVVeFgVaXwJQTwdfAlJXFAUxVlNRQVReUVxRQFhXUzsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D) |
| **Q3** | N-Channel MOSFET | SC-70 / SOT-323 | SI1308EDL-T1-GE3 | 1 | [View Part](https://jlcpcb.com/partdetail/VishayIntertech-SI1308EDL_T1GE3/C469327) | [View Datasheet](https://www.lcsc.com/datasheet/C469327.pdf?spm=wm.sxq.inf.ggs___wm.ssy.bg.0.xh&lcsc_vid=RVILV1QAFgMLXlRXRFQPBVVeFgVaXwJQTwdfAlJXFAUxVlNRQVReUVBWQ1VdVDsOAxUeFF5JWBYZEEoKFBINSQcJGk4eFQsCAgIaSgADAwAHC0slQFFYUlZRQU8GEwkK) |
| **D2, D4, D5** | Schottky Diode | SOD-123 | MBR0530 | 3 | [View Part](https://jlcpcb.com/partdetail/78464-MBR0530/C77336) | [View Datasheet](https://www.onsemi.com/pdf/datasheet/mbr0530-d.pdf) |
| **D3** | ESD Protection | SOT23-6 | USBLC6-2SC6Y | 1 | [View Part](https://jlcpcb.com/partdetail/STMicroelectronics-USBLC62SC6Y/C2969755) | [View Datasheet](https://www.st.com/resource/en/datasheet/usblc6-2sc6y.pdf) |
| **SW_DN, SW_ENT, SW_UP** | Tactile Button | SMD | EVP-AKE31A | 3 | [View Part](https://jlcpcb.com/partdetail/PANASONIC-EVPAKE31A/C569760) | [View Datasheet](https://docs.rs-online.com/b6df/A700000008633059.pdf) |
| **X1** | Crystal | 2016 | 32MHz | 1 | [View Part](https://jlcpcb.com/partdetail/357115-X201232768KJD2SI/C383843) | [View Datasheet](https://www.lcsc.com/datasheet/C383843.pdf?spm=wm.sxq.inf.ggs___wm.ssy.bg.0.xh&) |lcsc_vid=RVILV1QAFgMLXlRXRFQPBVVeFgVaXwJQTwdfAlJXFAUxVlNRQVReX1FSQlVdUDsOAxUeFF5JWBYZEEoKFBINSQcJGk4eFQsCAgIaSgADAwAHC0slQ1BWUFVTQU8GEwkK |
| **X2** | Crystal | 3215 | 32.768kHz | 1 | [View Part](https://jlcpcb.com/partdetail/YXC_CrystalOscillators-X322532MOB4SI/C9009) | [View Datasheet](https://www.lcsc.com/datasheet/C9009.pdf?spm=wm.sxq.inf.ggs___wm.ssy.bg.0.xh&) |lcsc_vid=RVILV1QAFgMLXlRXRFQPBVVeFgVaXwJQTwdfAlJXFAUxVlNRQVReX1BTRFhZXjsOAxUeFF5JWBYZEEoKFBINSQcJGk4eFQsCAgIaSgADAwAHC0slRlheUF1SWQkaCgg%3D |
| **L1** | Inductor | 0402 | 3.9nH | 1 | [View Part](https://jlcpcb.com/partdetail/MurataElectronics-LQG15HS3N9S02D/C77109) | [View Datasheet](https://static.chipdip.ru/lib/273/DOC012273635.pdf) |
| **L2** | Inductor | 0402 | 10uH | 1 | [View Part](https://jlcpcb.com/partdetail/MurataElectronics-LQW15DN100M00D/C910650) | [View Datasheet](https://www.farnell.com/datasheets/2616941.pdf) |
| **L3** | Inductor | 0402 | 15nH | 1 | [View Part](https://jlcpcb.com/partdetail/MurataElectronics-LQG15HS15NJ02D/C86059) | [View Datasheet](https://eu.mouser.com/datasheet/3/76/3/JELF243B_0010.pdf) |
| **L5** | Inductor | 4828 | 744043680 | 1 | [View Part](https://jlcpcb.com/partdetail/MurataElectronics-LQG15HS27NJ02D/C12669) | [View Datasheet](https://search.murata.co.jp/Ceramy/image/img/P02/JELF243B-0010.pdf) |
| **L7** | Inductor | INDC2016 | FTC252012SR47MBCA | 1 | [View Part](https://jlcpcb.com/partdetail/MurataElectronics-LQW15CNR47K10D/C913544) | [View Datasheet](https://www.mouser.com/datasheet/2/281/1/JELF243A_0096-1380927.pdf?srsltid=AfmBOoqV6fhARUu0Dwcpb8MI3Hh8C0bkpxE3anHGJVMFYBgkCz1oDBQZ) |
| **SJ1** | Solder Jumper | SMD | Jumper | 1 | - | - |
| **R2, R3, R4** | Resistor | 0201 | 0Ω | 3 | [View Part](https://jlcpcb.com/partdetail/YAGEO-RC0201FR070RL/C106227) | [View Datasheet](https://www.mouser.com/catalog/specsheets/YAGEO_PYu_RC_Group_51_RoHS_L_12.pdf?_gl=1*9j379c*_gcl_au*MTAzNzQ1MDU5LjE3NzY2NjMyNjQ.*_ga*NjY5NTI4MTAxLjE3NzY2NjMyNjQ.*_ga_15W4STQT4T*czE3NzY2NjY1ODckbzIkZzEkdDE3NzY2Njc2MjYkajYwJGwwJGgw) |
| **R1_EP_DR** | Resistor | 0201 | 0.47Ω | 1 | [View Part](https://jlcpcb.com/partdetail/21809-25121WF470LT4E/C21097) | [View Datasheet](https://www.royalohm.com/assets/pdf/products/smd/1.pdf) |
| **R_TYPE_SEL** | Resistor | 0201 | 2.2Ω | 1 | [View Part](https://jlcpcb.com/partdetail/YAGEO-RC0201FR072R2L/C138154) | [View Datasheet](https://www.mouser.com/catalog/specsheets/YAGEO_PYu_RC_Group_51_RoHS_L_12.pdf) |
| **R17, R18** | Resistor | 0201 | 3.3kΩ | 2 | [View Part](https://jlcpcb.com/partdetail/YAGEO-AC0201FR073K3L/C226534) | [View Datasheet](https://ro.mouser.com/datasheet/3/508/1/PYU_AC_51_ROHS_L.pdf) |
| **R1_USB, R2_USB** | Resistor | 0201 | 5.1kΩ | 2 | [View Part](https://jlcpcb.com/partdetail/YAGEO-RC0201JR075K1L/C163490) | [View Datasheet](https://yageogroup.com/component-documentation/download/specsheet/RC0201JR-075K1L) |
| **R2_EP_DR, R9, R_PWR_EPD** | Resistor | 0201 | 10kΩ | 3 | [View Part](https://jlcpcb.com/partdetail/TEConnectivity-CPF0201D10KC1/C4187156) | [View Datasheet](https://www.te.com/commerce/DocumentDelivery/DDEController?Action=showdoc&DocId=Data+Sheet%7F1773200%7FM%7Fpdf%7FEnglish%7FENG_DS_1773200_M.pdf) |
| **C3, C4** | Capacitor | 0201 | 1pF | 2 | [View Part](https://jlcpcb.com/partdetail/MurataElectronics-GRM0335C1H1R0BA01D/C85893) | [View Datasheet](https://ro.mouser.com/datasheet/3/76/1/GRM0335C1H1R0BA01-01A.pdf) |
| **C1, C2, C17, C18** | Capacitor | 0201 | 12pF | 4 | [View Part](https://jlcpcb.com/partdetail/MurataElectronics-GRM0335C1H120JA01D/C85890) | [View Datasheet](https://docs.rs-online.com/0636/A700000008615927.pdf) |
| **C11** | Capacitor | 0201 | 100pF | 1 | [View Part](https://jlcpcb.com/partdetail/MurataElectronics-GRM0335C1E101JA01D/C76917) | [View Datasheet](https://docs.rs-online.com/3c16/A700000008615521.pdf) |
| **C9** | Capacitor | 0201 | 820pF | 1 | [View Part](https://jlcpcb.com/partdetail/197002-GRM033R71E821KA01D/C185597) | [View Datasheet](https://docs.rs-online.com/7ce9/A700000008614975.pdf) |
| **C10, C13, C16, C22** | Capacitor | 0201 | 47nF | 4 | [View Part](https://jlcpcb.com/partdetail/MurataElectronics-GRM033R60J473KE19D/C85925) | [View Datasheet](https://datasheet.octopart.com/GRM033R60J473KE19D-Murata-datasheet-44105416.pdf) |
| **C5, C7, C8, C12, C19** | Capacitor | 0201 | 100nF | 5 | [View Part](https://jlcpcb.com/partdetail/MurataElectronics-GRM033R60J104KE19D/C76928) | [View Datasheet](https://search.murata.co.jp/Ceramy/image/img/A01X/G101/ENG/GRM033R60J104KE19-01.pdf) |
| **C23, C27, C29, C30, C31, C32, C34, C37, C38, C42** | Capacitor | 0201 | GRM011R60J152KE01L | 10 | [View Part](https://jlcpcb.com/parts/componentSearch?searchTxt=GRM011R60J152KE01L) | [View Datasheet](https://datasheet.octopart.com/GRM011R60J152KE01L-Murata-datasheet-138731756.pdf) |
| **EPD_C5** | Capacitor | 0201 | 0.1uF/50V | 1 | [View Part](https://jlcpcb.com/partdetail/6103901-500R07W104KV4T_0_1uF50v/C5337557) | [View Datasheet](https://www.mouser.com/catalog/specsheets/johanson_joha-s-a0008490164-1.pdf?_gl=1*1dgyi5u*_gcl_au*MTAzNzQ1MDU5LjE3NzY2NjMyNjQuOTYzMzIyOTQ0LjE3NzY2NzA0NDUuMTc3NjY3MDQ0NQ..*_ga*NjY5NTI4MTAxLjE3NzY2NjMyNjQ.*_ga_15W4STQT4T*czE3NzY2NjY1ODckbzIkZzEkdDE3NzY2NzA0NDgkajQ3JGwwJGgw) |
| **C15** | Capacitor | 0402 | 1.0uF | 1 | [View Part](https://jlcpcb.com/partdetail/MurataElectronics-GRM155R60J105KE19D/C15684) | [View Datasheet](https://datasheet4u.com/pdf/1279553/GRM155R60J105KE19D.pdf) |
| **C6, C14, C20, C21, C43** | Capacitor | 0402 | 4.7uF | 5 | [View Part](https://jlcpcb.com/partdetail/MurataElectronics-GRM155R60J475KE96D/C76995) | [View Datasheet](https://www.lcsc.com/datasheet/C76995.pdf?spm=wm.sxq.inf.ggs___wm.ssy.bg.0.xh&lcsc_vid=RVILV1QAFgMLXlRXRFQPBVVeFgVaXwJQTwdfAlJXFAUxVlNRQVReVFNRR1VbVjsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D) |
| **C2-EP-DR** | Capacitor | 0402 | 4.7uF/25V | 1 | [View Part](https://jlcpcb.com/partdetail/DMBJ-RVT1E4R7M0405_4_7UF25V/C970600) | [View Datasheet](https://www.lcsc.com/datasheet/C2895731.pdf?spm=wm.sxq.inf.ggs___wm.ssy.bg.0.xh&lcsc_vid=RVILV1QAFgMLXlRXRFQPBVVeFgVaXwJQTwdfAlJXFAUxVlNRQVReVFdRRVlcUjsOAxUeFF5JWBYZEEoKFBINSQcJGk4eFQsCAgIaSgADAwAHC0slRVlXUlNVRk8GEwkK) |
| **C1-EP-DR, C24, C39** | Capacitor | 0402 | 10uF | 3 | [View Part](https://jlcpcb.com/partdetail/MurataElectronics-GRM155R60J106ME44D/C76991) | [View Datasheet](https://www.mouser.com/catalog/specsheets/murata_03052018_GRM_Series_1.pdf?_gl=1*8xgmsh*_gcl_au*MTAzNzQ1MDU5LjE3NzY2NjMyNjQuOTYzMzIyOTQ0LjE3NzY2NzA0NDUuMTc3NjY3MDQ0NQ..*_ga*NjY5NTI4MTAxLjE3NzY2NjMyNjQ.*_ga_15W4STQT4T*czE3NzY2NjY1ODckbzIkZzEkdDE3NzY2NzA4NzEkajU5JGwwJGgw) |
| **C25, C33** | Capacitor | 0402 | 22uF | 2 | [View Part](https://jlcpcb.com/partdetail/408393-GRM155R60J226ME11D/C415703) | [View Datasheet](https://ro.mouser.com/datasheet/3/76/2/GRM155R60J226ME11_01A.pdf) |
| **EPD_C1, EPD_C2, EPD_C6–12**| Capacitor | 0402 | 1uF/50V | 9 | [View Part](https://jlcpcb.com/partdetail/25795-0201WMJ0100TCE/C25052) | [View Datasheet](https://www.lcsc.com/datasheet/C25052.pdf?spm=wm.sxq.inf.ggs___wm.ssy.bg.0.xh&lcsc_vid=RVILV1QAFgMLXlRXRFQPBVVeFgVaXwJQTwdfAlJXFAUxVlNRQVReUVVSQFBcUjsOAxUeFF5JWBYZEEoKFBINSQcJGk4eFQsCAgIaSgADAwAHC0slRlNcU1dSWQkaCgg%3D) |
| **TP_3.3V, TP_3V3, TP_BAT_GND, TP_GND, TP_ON, TP_OP, TP_RESET, TP_SCL, TP_SDA, TP_SWDCLK, TP_SWDIO, TP_SWO, TP_VBAT, TP_VREG** | Test Pad | TP20R | Test Pad | 14 | - | - |

---

## Hardware Functionality

This section describes the main hardware subsystems of the InkTime smartwatch, focusing on component choices, overall architecture, and how the design is optimized for low power consumption.

---

### 1. Core Processing & RF

**Microcontroller (MCU):**  
The system is built around the **Nordic nRF52840 (ARM Cortex-M4F)**. It was chosen mainly because it already includes Bluetooth Low Energy (BLE 5.0) and USB support, so no extra external communication chips are needed.

**Clocking System:**  
A dual-crystal setup is used:
- 32 MHz crystal for normal processing and wireless communication  
- 32.768 kHz crystal for the real-time clock (RTC) during low-power sleep modes  

This allows the system to keep accurate time while consuming very little energy when idle.

**Wireless Connectivity:**  
A small 2.4 GHz chip antenna is placed at the edge of the PCB. A matching network is used to improve RF performance and ensure stable BLE communication with a phone or other devices.

---

### 2. Power Management Architecture

The power system is designed to keep energy usage as low as possible while maintaining stable operation.

**Charging & Input:**  
Power is supplied through a USB-C connector, with ESD protection for safety. A **BQ25180 power management IC** handles LiPo charging and automatically switches between USB power and battery operation.

**Voltage Regulation:**  
Since battery voltage changes during discharge, an **RT6160 converter** is used to generate a stable 3.3V rail. This ensures the system works reliably across the entire battery range without brownouts.

**Battery Monitoring:**  
A **MAX17048 fuel gauge** estimates battery level. It reads voltage directly, avoiding the need for a current-sense resistor, which helps reduce power loss and saves space.

---

### 3. Display Subsystem

**E-Paper Panel:**  
The visual output is handled by an e-paper display, selected because it offers very good readability in sunlight and keeps the image without consuming power.

**Power Control:**  
The display requires higher voltages for operation, but it is only powered during refresh cycles. The rest of the time, the MCU completely switches it off using a MOSFET-based power gating circuit. This significantly reduces idle power consumption.

---

### 4. Sensing & User Interaction

**Motion Tracking:**  
A BMA42x IMU is used to detect motion, steps, and general activity. Instead of being read continuously, it can generate interrupt signals that wake the MCU only when movement is detected (for example, wrist movement).

**Haptic Feedback:**  
A DRV2605 haptic driver controls a vibration motor. Rather than generating signals manually, the MCU only triggers predefined vibration patterns stored in the driver.

**Tactile Inputs:**  
Three physical buttons are used for user interaction. They include hardware debounce filtering so that inputs remain stable without needing constant software correction.

---

### 5. Communication Buses

To keep the PCB simple and organized, communication is divided based on speed requirements:

**Shared I2C Bus:**  
Used for low-speed peripherals such as the IMU, fuel gauge, charger IC, and haptic driver. This reduces the number of required MCU pins and keeps routing simple.

**Dedicated SPI Bus:**  
Used only for the e-paper display, since it needs higher data throughput during screen updates. Additional control signals (reset, data/command, busy) are used to manage the display operation.

**Debug Interface:**  
Firmware programming and debugging are handled through a SWD interface, which provides full access without requiring a large permanent header on the PCB.

---

### 6. Power Consumption (Estimation)

The system is mainly optimized for low-power operation, with most components active only for short periods and the MCU spending most of the time in sleep mode.

Typical currents:
- nRF52840 active: ~10–15 mA  
- E-paper refresh (peak): ~20–40 mA (short bursts)  
- IMU: ~0.1 mA  
- Haptic motor: ~50–70 mA (very short pulses)  
- Deep sleep: ~2–5 µA  

With a ~180 mAh LiPo battery and a mostly idle usage pattern (sleep + occasional updates), the estimated battery life is around **5 days**.

---
## nRF52840 Pin Mapping
| Pin | Component / Block | Purpose |
|:--- |:--- |:--- |
| **---** | **Power & Regulation** | **---** |
| **VDD** | MCU Power | Main 3.3V supply for the microcontroller. |
| **VDDH** | MCU Power | High-voltage supply input. |
| **VSS / VSS_PA / VSS_PAD** | Ground | Ground connections for MCU and RF stages. |
| **DEC[1..6] / DEC3V3** | Internal Regulation | Decoupling pins for internal regulators and 3.3V rail stability. |
| **DCC** | DC/DC | Support pins for the internal DC/DC converter. |
| **---** | **Clock & RF** | **---** |
| **XC1 / XC2** | System Clock | 32 MHz crystal oscillator for main operation. |
| **XL1 / XL2** | System Clock | 32.768 kHz crystal for RTC and low-power modes. |
| **ANT** | Antenna | Connection to the 2.4 GHz RF output. |
| **---** | **E-Paper Display (SPI)** | **---** |
| **P0.02** | E-Paper Display | SPI clock (SCK) for display communication. |
| **P0.03** | E-Paper Display | SPI data line (MOSI) for sending pixel data. |
| **P0.05** | E-Paper Display | Chip select to enable the display on the SPI bus. |
| **P0.15** | E-Paper Display | Selects between command and data mode. |
| **P0.16** | E-Paper Display | Hardware reset for the display controller. |
| **P0.17** | E-Paper Display | Busy signal used to synchronize display updates. |
| **P1.01** | E-Paper Display | Controls power gating for the display. |
| **---** | **I2C Bus** | **---** |
| **P0.06** | IMU, Fuel Gauge, Charger, Haptic Driver | Shared I2C data line (SDA) for all peripherals. |
| **P0.07** | IMU, Fuel Gauge, Charger, Haptic Driver | Shared I2C clock line (SCL). |
| **---** | **Sensors & Power ICs** | **---** |
| **P0.08** | IMU | Primary interrupt for motion and wake-up events. |
| **P1.08** | IMU | Secondary interrupt for advanced events. |
| **P0.11** | LiPo Charger | Interrupt line for charge status and fault detection. |
| **P0.10** | Fuel Gauge | Alert signal for low battery or voltage thresholds. |
| **---** | **User Interface** | **---** |
| **P0.12** | Haptic Driver | Enable signal for the vibration motor driver. |
| **P0.13** | Button | User input |
| **P0.14** | Button | User input |
| **P1.02** | Button | User input |
| **---** | **System & SWD** | **---** |
| **P0.18** | System | Global reset line for the microcontroller. |
| **SWDIO** | SWD Interface | Data line for programming and debugging. |
| **SWDCLK** | SWD Interface | Clock line for the debugging interface. |
| **P1.00** | SWD Interface | SWO trace output for advanced debugging. |
| **---** | **USB Interface** | **---** |
| **D+ / D-** | USB Interface | Differential data lines for USB communication. |
| **VBUS** | USB Interface | Used to detect USB connection. |
---
*Note: All other nRF52840 pins not listed in this table are unused and reserved for future hardware revisions.*


## Renders

### PCB Renderings
![PCB 2D](./Images/InkTime_PCB_2D.png)
![PCB 3D](./Images/InkTime_PCB_3D_Angle.png)

### Component Placement in Case
![Case Fit](./Images/Exploded_View_InkTime.png)
![Components](./Images/InkTime_No_Case.png)
