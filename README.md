# VGA-Card

Replica of a VGA card

# PCB Revision History

- V0.1 Initial revision 2021 made with Sprint-Layout
- V0.2 Second board revision with tidied up components, new numbering and improved Silk screen

# Specs

This replica of a VGA graphics card is based on the AVGA1 or CL-GD5401 graphics chip.
The video memory is 265kb. The card work in 8 and 16 bit systems.

# Images

Top view
[![](images/complete.jpg 'top view')](#topview)

8-Bit mode
[![](images/8bit.jpg '8bit test')](#8bit)

16-Bit mode
[![](images/16bit.jpg '16bit test')](#16bit)

# Bill of materials

| Quantity | Description              | PCB/Schematic's Reference                   |
| -------- | ------------------------ | ------------------------------------------- |
| 2        | CAP CER 220PF            | C1, C2                                      |
| 6        | CAP CER 47PF             | C3, C4, C5, C6, C7, C8                      |
| 2        | CAP ELKO 2,2UF RM 2,5    | C9, C10                                     |
| 3        | CAP ELKO 22UF RM 2,5     | C11, C12, C13                               |
| 9        | CAP CER 100NF            | C14, C15, C16, C17, C18, C19, C20, C21, C22 |
| 1        | CONN HEADER 15POS FEMALE | CN1                                         |
| 4        | DIODE 1N4148             | D1, D2, D3, D4                              |
| 3        | FERRITE                  | L1, L2, L3                                  |
| 1        | 2N3904                   | Q1                                          |
| 1        | TL431                    | Q2                                          |
| 2        | RES 33 OHM 5% 1/4W       | R1, R2                                      |
| 1        | RES 360 OHM 5% 1/4W      | R3                                          |
| 1        | RES 1.0K OHM 5% 1/4W     | R4                                          |
| 3        | RES 150 OHM 5% 1/4W      | R5, R6, R7                                  |
| 1        | RES 1 OHM 5% 1W          | R8, R11                                     |
| 2        | RES 75 OHM 5% 1/4W       | R9, R10                                     |
| 1        | IC AVGA1 OR CL-GD5401    | U1                                          |
| 2        | IC HY534256 RAM          | U2, U3                                      |
| 1        | IC 74LS244               | U4                                          |
| 1        | IC 27C256 EPROM          | U5                                          |

# Licence

The project is available for free use
