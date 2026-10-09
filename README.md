
<p align="left">
  <img src="rainbow.svg" width="800" alt="Moving Rainbow Gradient Text" />
</p>

An ultra fast speed run made Dev board!


Oki so this is a Speedrun dev board so the readme is also going to be Speedrun!
I started with the not so hard schematic! <img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/87986993-ccde-4139-9dc2-ba4a83f69820" /> Schematic!!!


I then continued to the PCB and the layout part so I know where I want things (roughly lol) once I finished that I started to route from the RP2040 outward and then realized that if I wanted this to be ultra compact and cute I needed 4 layers soooo. I did that lol and I continued to do it and then I'm here writing this readme and about to do BOM! Thanks! <img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/1b2d55e2-b3e1-48da-a0c4-f42f58affb2d" /> PCB Photo!!! 
<img width="1723" height="992" alt="image" src="https://github.com/user-attachments/assets/1d38d977-149d-4537-bec6-211e511089ab" /> 3D Render!


  ![GitHub Repo stars](https://img.shields.io/github/stars/bobert3d/speed-dev?style=flat&logo=github&logoColor=white)  [![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/019866aa-94f8-4ef8-be5c-21f2c10331d5" /> BOM!


#BOM!
| Id | Designator                              | Footprint                           | Quantity | Designation                 | Supplier and ref |   |   |
|----|-----------------------------------------|-------------------------------------|----------|-----------------------------|------------------|---|---|
| 1  | SW1                                     | SW_Push_SPST_NO_Alps_SKRK           | 1        | SW_Push                     |                  |   |   |
| 2  | C8,C17                                  | C_0402_1005Metric                   | 2        | 1uF                         |                  |   |   |
| 3  | C11,C15,C7,C16,C13,C12,C9,C10,C5,C14,C6 | C_0402_1005Metric                   | 11       | 0.1uF                       |                  |   |   |
| 4  | Y1                                      | Crystal_SMD_3225-4Pin_3.2x2.5mm     | 1        | 12 MHz                      |                  |   |   |
| 5  | U4                                      | SOT-23                              | 1        | MCP1700x-330xxTT            |                  |   |   |
| 6  | R2,R5,R1,R6                             | R_0402_1005Metric                   | 4        | 5.1K                        |                  |   |   |
| 7  | J3                                      | PinHeader_1x03_P2.54mm_Vertical     | 1        | Conn_01x03                  |                  |   |   |
| 8  | R4                                      | R_0402_1005Metric                   | 1        | 10K                         |                  |   |   |
| 9  | U3                                      | QFN-56-1EP_7x7mm_P0.4mm_EP3.2x3.2mm | 1        | RP2040                      |                  |   |   |
| 10 | C2,C1                                   | C_0201_0603Metric                   | 2        | 10uF                        |                  |   |   |
| 11 | J2,J4                                   | PinHeader_1x20_P2.54mm_Vertical     | 2        | Conn_01x20                  |                  |   |   |
| 12 | R3                                      | R_0402_1005Metric                   | 1        | 1K                          |                  |   |   |
| 13 | U2                                      | SOIC-8_5.3x5.3mm_P1.27mm            | 1        | W25Q128JVS                  |                  |   |   |
| 14 | J1                                      | USB_C_Receptacle_HRO_TYPE-C-31-M-12 | 1        | USB_C_Receptacle_USB2.0_14P |                  |   |   |
| 15 | C4,C3                                   | C_0603_1608Metric                   | 2        | 15pF                        |                  |   |   |

## FAQ

#### BOM?

There are 2 BOM technically one has the LCSC part numbers and the others is a quote from LCSC with links to parts too!

#### Is this good for beginners?

Yes!!! ITS THE BENCHY PCB EQUIVALENT!!

#### How many layers is the PCB?

This is a 4 layer PCB!

#### Can I contribute?

YES YOU CAN!!!! Take a peek at the Contributing section for a better guide on contributing!

## Authors

- [@bobert3d](https://www.github.com/Bobert3D)

- [@vms-hc](https://www.github.com/VMS-HC)

