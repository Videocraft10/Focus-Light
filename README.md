# Focus-Light
Custom Made Desk Light (with a disco mode)

## Features
<img width="2480" height="3508" alt="Videocraft Focus Light Zine" src="https://github.com/user-attachments/assets/2b213746-0c68-46ec-aff4-bfd138511eaa" />


1. Smooth light dimming
2. Aproxx 400 to 500 lumens of brightness
3. Buttons to control lights
4. Disco Mode!!

## Why?

I wanted to create a incredibly usful project that I would use basicly every single day that could live on my desk at home. Addionaly this project will help me fully understand how lights work with voltages and how wiring helps etc.

## The PCB

The PCB for this project was created within EasyEDA for easy parts and footprint integration.

### The Schematic

<img width="1884" height="605" alt="image" src="https://github.com/user-attachments/assets/df856dbe-267f-4c63-92e8-65b799bc10de" />

### The PCB

*USB Hub and Chip Section*

**Front**


<img width="823" height="781" alt="Screenshot 2026-06-18 111459" src="https://github.com/user-attachments/assets/5bf7e139-d580-456a-87c0-76653da38d10" />



**Back**


<img width="787" height="794" alt="Screenshot 2026-06-18 111507" src="https://github.com/user-attachments/assets/509ad759-4741-4de1-a918-472962b163fb" />


**3D**


<img width="783" height="759" alt="image" src="https://github.com/user-attachments/assets/62499b4f-61a8-482c-8c38-611f51c67ab8" />



*LED Section*


**Front**


<img width="956" height="743" alt="image" src="https://github.com/user-attachments/assets/6cc91984-1f09-4165-b52c-159c81b4b971" />


**Back**


<img width="953" height="742" alt="image" src="https://github.com/user-attachments/assets/92d7d682-a47a-4579-8873-04fd4eb39682" />


**3D**


<img width="996" height="739" alt="image" src="https://github.com/user-attachments/assets/621cb367-3c02-4e67-a4ea-5e59984efb34" />



## The Case


## Firmware?


## BOM
*Cost is for TWO PCBs (minimum amount for pcba)*

| Item | LCSC # / Item Links | Single Cost | Amount Used | Fees/Notes | Total Price |
| ---------- | ---------- | ---------- | ---------- | ---------- | ---------- |
| 1uF Capacitor | [C15849](https://www.lcsc.com/product-detail/C15849.html?s_z=n_q_C15849&globalKeyword=C15849) | $0.0148 | 16 | ---------- | $0.2368 |
| 100nF Capacitor | [C14663](https://www.lcsc.com/product-detail/C14663.html?s_z=n_q_C14663&globalKeyword=C14663) | $0.0094 | 6 | ---------- | $0.0564 |
| 56k Resistor | [C23206](https://www.lcsc.com/product-detail/C23206.html?s_z=n_q_C23206&globalKeyword=C23206) | $0.0020 | 16 | ---------- | $0.032 |
| 5.1k Resistor | [C23186](https://www.lcsc.com/product-detail/C23186.html?s_z=n_q_C23186&globalKeyword=C23186) | $0.0018 | 4 | ---------- | $0.0072 |
| 330 Resistor | [C23138](https://www.lcsc.com/product-detail/C23138.html?s_z=n_q_C23138&globalKeyword=C23138) | $0.0016 | 2 | ---------- | $0.0032 |
| **OPSCO Optoelectronics SK6812MINIRGBW-NW-P6** | [C7423107](https://www.lcsc.com/product-detail/C7423107.html?s_z=n_q_C7423107&globalKeyword=C7423107) | $0.1301 | 160 (80 per) | Forced to buy 162 | $14.2884 |
| **CoreChips SL2.1s** | [C2684433](https://www.lcsc.com/product-detail/C2684433.html?s_z=n_q_C2684433&globalKeyword=C2684433) | $0.2494 | 2 | Forced to buy 5 | $1.247 |
| **TI SN74AHCT125DR** | [C155176](https://www.lcsc.com/product-detail/C155176.html?s_z=n_q_C155176&globalKeyword=C155176) | $0.3489 | 2 | ---------- | $0.6978 |
| **SHOU HAN TYPE-C16PIN** | [C393939](https://www.lcsc.com/product-detail/C393939.html?s_z=n_q_C393939&globalKeyword=C393939) | $0.0653 | 10 | ---------- | $0.6530 |
| ***Seeed Studio XIAO-ESP32 C3 DIP*** | [AliExpress](https://www.aliexpress.us/item/3256805951491414.html?channel=twinner ) | $8.48 | 2 | Excluding shipping and aliexpress fees | $16.96 |
|  |  |  |  |  |  |
| Part Total: | ---------- | ---------- | ---------- | ---------- | $34.1818 |
|  |  |  |  |  |  |
| ***Addional Fees*** | ---------- | ---------- | ---------- | ---------- | ---------- |
| PCB Price | ---------- | ---------- | ---------- | ---------- | $6 ($2 coupon, $8 normally) |
|  |  |  |  |  |  |
| **PCBA Price** | (Is for both PCBs. Chip part and LED Part) | ---------- | ---------- | ---------- | **$35.52** |
| ---------- | Setup Fee | ---------- | ---------- | $16.36 | |
| ---------- | Stencil | ---------- | ---------- |  $3.06  | |
| ---------- | Extended Componets fee (boldfaced componets) | ---------- | ---------- | $12.28 |  |
| ---------- | SMT Assembly | ---------- | ---------- | $2.12 |  |
| ---------- | Nitrogen Reflow Soldering | ---------- | ---------- | $1.70 |  |
|  |  |  |  |  |  |
| Shipping Fees | ---------- | ---------- | ---------- | ---------- | $22.60 |
| Sales Tax | ---------- | ---------- | ---------- | ---------- | $6 |
|  |  |  |  |  |  |
| ***GRAND TOTAL (for 2)*** | ---------- | ---------- | ---------- | ---------- | $104.3018 (gah dam) |

## How to use!
### LED's

Simply plug the lamp on! The LEDs will turn on automaticly, ensure you are plugging into the non usb hub ports (the 5 lower ports)

### USB Hub

Simply plug your computer into the lower usb port closest to the raised one, and plug any accessories into the other lower ones to the right.

## How to Build

Download the easyeda file from [here](https://github.com/Videocraft10/Focus-Light/blob/main/PCB%20Files/ProPrj_Videocraft%20Focus%20Light.epro2) and upload it to easyeda's pcb fabrication service.
Click PCBA, and select how many you want assembled (minimun 2)
Then download all case files from [here](

## Software Used

