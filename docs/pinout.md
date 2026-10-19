# Pinout

Mapping of ATmega2560 pins to the signals used by each supported system and peripheral.

| Arduino | Alt. Arduino | ATMega2560 | Game Boy | GBA | NES | SNES | snesCIC | N64 ROM | N64 Controller | N64 EEP | Master System | Megadrive | PCE/TG16 | Wonderswan | Loopy | LED | SD Card | OLED | LCD | Button | Rotary Encoder | Neopixel | 16bit Flash | 8bit Flash | 16bit Flash in 8bit Mode | 27C322 Eprom |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| A0 | D54 | PF0 | A0 | AD0 | M2 | A0 |  | AD0 |  |  | A0 | A1 | A0 | A-1 | D10 |  |  |  |  |  |  |  | A0 | A0 | D15 | A0 |
| A1 | D55 | PF1 | A1 | AD1 | PRG_CE | A1 |  | AD1 |  |  | A1 | A2 | A1 | A0 | D8 |  |  |  |  |  |  |  | A1 | A1 | A0 | A1 |
| A2 | D56 | PF2 | A2 | AD2 | CHR_WR | A2 |  | AD2 |  |  | A2 | A3 | A2 | A1 | D6 |  |  |  |  |  |  |  | A2 | A2 | A1 | A2 |
| A3 | D57 | PF3 | A3 | AD3 | CIRAM_CE | A3 |  | AD3 |  |  | A3 | A4 | A3 | A2 | D4 |  |  |  |  |  |  |  | A3 | A3 | A2 | A3 |
| A4 | D58 | PF4 | A4 | AD4 | CHR_/A13 | A4 |  | AD4 |  |  | A4 | A5 | A4 | A3 | D14 |  |  |  |  |  |  |  | A4 | A4 | A3 | A4 |
| A5 | D59 | PF5 | A5 | AD5 | CHR_RD | A5 |  | AD5 |  |  | A5 | A6 | A5 | A4 | D3 |  |  |  |  |  |  |  | A5 | A5 | A4 | A5 |
| A6 | D60 | PF6 | A6 | AD6 | IRQ | A6 |  | AD6 |  |  | A6 | A7 | A6 | A5 | D2 |  |  |  |  |  |  |  | A6 | A6 | A5 | A6 |
| A7 | D61 | PF7 | A7 | AD7 | PRG_RW | A7 |  | AD7 |  |  | A7 | A8 | A7 | A6 | RESET |  |  |  |  |  |  |  | A7 | A7 | A6 | A7 |
| A8 | D62 | PK0 | A8 | AD8 | D0 | A8 |  | AD8 |  |  | A8 | A9 | A8 | A7 | D0 |  |  |  |  |  |  |  | A8 | A8 | A7 | A8 |
| A9 | D63 | PK1 | A9 | AD9 | D1 | A9 |  | AD9 |  |  | A9 | A10 | A9 | A8 | A0 |  |  |  |  |  |  |  | A9 | A9 | A8 | A9 |
| A10 | D64 | PK2 | A10 | AD10 | D2 | A10 |  | AD10 |  |  | A10 | A11 | A10 | A9 | A1 |  |  |  |  |  |  |  | A10 | A10 | A9 | A10 |
| A11 | D65 | PK3 | A11 | AD11 | D3 | A11 |  | AD11 |  |  | A11 | A12 | A11 | A10 | A21 |  |  |  |  |  |  |  | A11 | A11 | A10 | A11 |
| A12 | D66 | PK4 | A12 | AD12 | D4 | A12 |  | AD12 |  |  | A12 | A13 | A12 | A11 | A3 |  |  |  |  |  |  |  | A12 | A12 | A11 | A12 |
| A13 | D67 | PK5 | A13 | AD13 | D5 | A13 |  | AD13 |  |  | A13 | A14 | A13 | A12 | A20 |  |  |  |  |  |  |  | A13 | A13 | A12 | A13 |
| A14 | D68 | PK6 | A14 | AD14 | D6 | A14 |  | AD14 |  |  | A14 | A15 | A14 | A13 | A15 |  |  |  |  |  |  |  | A14 | A14 | A13 | A14 |
| A15 | D69 | PK7 | A15 | AD15 | D7 | A15 |  | AD15 |  |  |  | A16 | A15 | A14 | A13 |  |  |  |  |  |  |  | A15 | A15 | A14 | A15 |
| D0 | RX0 | PE0 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| D1 | TX0 | PE1 |  |  |  |  |  |  |  |  |  |  |  |  |  | build-in (LCD blink) |  |  |  |  |  |  |  |  |  |  |
| D2 | PWM | PE4 |  |  |  | WRAM |  |  |  |  |  | (YS) |  | IO | D11 |  |  |  |  |  |  |  |  |  |  |  |
| D3 | PWM | PE5 |  |  |  | REFRESH |  |  |  |  |  | CAS2 |  | CLK | D9 |  |  |  |  |  |  |  |  |  |  |  |
| D4 | PWM | PG5 |  |  |  | EXPAND |  |  |  |  |  | ASEL |  | Int | D15 |  |  |  |  |  |  |  |  |  |  |  |
| D5 | PWM | PE3 |  |  |  |  |  |  |  |  |  | EDCLK |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| D6 | PWM | PH3 | CS | CS_ROM |  | CS |  |  |  |  | A15/M0-7 | CS | OE | CART | RAMWE |  |  |  |  |  |  |  | BYTE | OE | OE |  |
| D7 (1K Pullup) | PWM | PH4 | Sound | IRQ |  | IRQ |  |  | DATA | DATA |  | WR HIGH | IRQ2 | MMC | RAMCS2 |  |  |  |  |  |  |  | WE |  |  |  |
| D8 | PWM | PH5 | WR | WR |  | WR |  | WR |  |  | WR | WR LOW | WR | WE |  |  |  |  |  |  |  |  | WP | WE | WE | To NPN transistor controlling VPP 12V stepup regulator module |
| D9 | PWM | PH6 | RD | RD |  | RD |  | RD |  |  | OE | OE |  | OE |  |  |  |  |  |  |  |  | CE | CE | CE | CE |
| D10 | PWM | PB4 |  |  |  |  |  |  |  |  |  |  |  |  |  | Blue (OLED blink) |  |  | Reset |  |  |  |  |  |  |  |
| D11 | PWM | PB5 |  |  |  |  |  |  |  |  |  |  |  |  |  | Green |  |  | DC/A0 |  |  |  |  |  |  |  |
| D12 | PWM | PB6 |  |  |  |  |  |  |  |  |  |  |  |  |  | Red |  |  | CS |  |  |  |  |  |  |  |
| D13 | PWM | PB7 |  |  |  |  |  |  |  |  |  |  |  |  |  | build-in (Serial blink) |  |  |  |  |  | Neopixel |  |  |  |  |
| D14 | TX3 | PJ1 |  |  |  | PAWR |  |  |  |  |  | AS |  |  | D12 |  |  |  |  |  |  |  |  |  |  |  |
| D15 | RX3 | PJ0 |  |  |  | PARD |  |  |  |  |  | Time |  |  | D13 |  |  |  |  |  |  |  |  |  |  |  |
| D16 | TX2 | PH1 | CLK | CLK |  |  |  |  |  |  | CLK | VCLK |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| D17 | RX2 | PH0 | Reset | CS_RAM |  | Reset |  | Reset |  | Reset | Reset | (MRES),VRES | RST | Reset |  |  |  |  |  |  |  |  | Reset | Reset | Reset |  |
| D18 | TX1 | PD3 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | ENC1 |  |  |  |  |  |
| D19 | RX1 | PD2 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | ENC2 |  |  |  |  |  |
| D20 | SDA | PD1 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | SDA |  |  |  |  |  |  |  |  |
| D21 | SCL | PD0 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | SCL |  |  |  |  |  |  |  |  |
| D22 |  | PA0 |  |  | A8 | PA0 |  |  |  |  |  | D8 |  | D8 | D1 |  |  |  |  |  |  |  | D8 |  |  | D8 |
| D23 |  | PA1 |  |  | A9 | PA1 |  |  |  |  |  | D9 |  | D9 | A2 |  |  |  |  |  |  |  | D9 |  |  | D9 |
| D24 |  | PA2 |  |  | A10 | PA2 |  |  |  |  |  | D10 |  | D10 | A4 |  |  |  |  |  |  |  | D10 |  |  | D10 |
| D25 |  | PA3 |  |  | A11 | PA3 |  |  |  |  |  | D11 |  | D11 | A19 |  |  |  |  |  |  |  | D11 |  |  | D11 |
| D26 |  | PA4 |  |  | A12 | PA4 |  |  |  |  |  | D12 |  | D12 | A18 |  |  |  |  |  |  |  | D12 |  |  | D12 |
| D27 |  | PA5 |  |  | A13 | PA5 |  |  |  |  |  | D13 |  | D13 | A16 |  |  |  |  |  |  |  | D13 |  |  | D13 |
| D28 |  | PA6 |  |  | A14 | PA6 |  |  |  |  |  | D14 |  | D14 | A17 |  |  |  |  |  |  |  | D14 |  |  | D14 |
| D29 |  | PA7 |  |  |  | PA7 |  |  |  |  |  | D15 |  | D15 | A14 |  |  |  |  |  |  |  | D15 |  |  | D15 |
| D30 |  | PC7 | D7 | A23 |  | D7 |  |  |  |  | D7 | D7 | D7 | D7 |  |  |  |  |  |  |  |  | D7 | D7 | D7 | D7 |
| D31 |  | PC6 | D6 | A22 |  | D6 |  |  |  |  | D6 | D6 | D6 | D6 |  |  |  |  |  |  |  |  | D6 | D6 | D6 | D6 |
| D32 |  | PC5 | D5 | A21 |  | D5 |  |  |  |  | D5 | D5 | D5 | D5 |  |  |  |  |  |  |  |  | D5 | D5 | D5 | D5 |
| D33 |  | PC4 | D4 | A20 |  | D4 |  |  |  |  | D4 | D4 | D4 | D4 |  |  |  |  |  |  |  |  | D4 | D4 | D4 | D4 |
| D34 |  | PC3 | D3 | A19 |  | D3 |  |  |  |  | D3 | D3 | D3 | D3 | A12 |  |  |  |  |  |  |  | D3 | D3 | D3 | D3 |
| D35 |  | PC2 | D2 | A18 | CIRAM_A10 | D2 |  |  |  |  | D2 | D2 | D2 | D2 | A10 |  |  |  |  |  |  |  | D2 | D2 | D2 | D2 |
| D36 |  | PC1 | D1 | A17 |  | D1 |  | ALE_H |  |  | D1 | D1 | D1 | D1 | A8 |  |  |  |  |  |  |  | D1 | D1 | D1 | D1 |
| D37 |  | PC0 | D0 | A16 |  | D0 |  | ALE_L |  |  | D0 | D0 | D0 | D0 | A6 |  |  |  |  |  |  |  | D0 | D0 | D0 | D0 |
| D38 |  | PD7 |  |  |  |  |  |  |  |  |  |  |  |  |  | HW5 status LED |  |  |  | Button1 (10K Pullup) |  |  |  |  |  |  |
| D39 |  | PG2 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Button 2 (10K Pullup) | ENC Button |  |  |  |  |  |
| D40 |  | PG1 |  |  |  |  | Reset In (Pin 4) |  |  |  |  |  |  |  | D5 |  |  |  |  |  |  |  |  |  |  |  |
| D41 |  | PG0 |  |  |  |  | Reset Out Host (Pin 3) |  |  |  |  |  |  |  | D7 |  |  |  |  |  |  |  |  |  |  |  |
| D42 |  | PL7 |  |  | A7 | A23 |  |  |  |  |  |  | Card Detect |  | CE |  |  |  |  |  |  |  |  |  |  |  |
| D43 |  | PL6 |  |  | A6 | A22 |  |  |  |  |  | A23 | Audio In |  | OE |  |  |  |  |  |  |  |  |  | A21 |  |
| D44 | PWM | PL5 |  |  | A5 | A21 |  |  |  |  |  | A22 | HSM |  |  |  |  |  |  |  |  |  | A21 | A21 | A20 |  |
| D45 | PWM | PL4 |  |  | A4 | A20 |  |  |  |  |  | A21 | CE |  |  |  |  |  |  |  |  |  | A20 | A20 | A19 | A20 |
| D46 | PWM | PL3 |  |  | A3 | A19 |  |  |  |  |  | A20 | A19 | A18 | A11 |  |  |  |  |  |  |  | A19 | A19 | A18 | A19 |
| D47 |  | PL2 |  |  | A2 | A18 |  |  |  |  |  | A19 | A18 | A17 | A9 |  |  |  |  |  |  |  | A18 | A18 | A17 | A18 |
| D48 |  | PL1 |  |  | A1 | A17 |  |  |  |  | CE | A18 | A17 | A16 | A7 |  |  |  |  |  |  |  | A17 | A17 | A16 | A17 |
| D49 |  | PL0 |  |  | A0 | A16 |  |  |  |  |  | A17 | A16 | A15 | A5 |  |  |  |  |  |  |  | A16 | A16 | A15 | A16 |
| D50 | MISO | PB3 |  |  |  |  |  |  |  |  |  |  |  |  |  |  | MISO |  |  |  |  |  |  |  |  |  |
| D51 | MOSI | PB2 |  |  |  |  |  |  |  |  |  |  |  |  |  |  | MOSI |  | MOSI |  |  |  |  |  |  |  |
| D52 | SCK | PB1 |  |  |  |  |  |  |  |  |  |  |  |  |  |  | SCK |  | SCK |  |  |  |  |  |  |  |
| D53 | SS | PB0 |  |  |  |  |  |  |  |  |  |  |  |  |  |  | SS |  |  |  |  |  |  |  |  |  |
| CLK0 |  |  |  |  |  | CLK |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| CLK1 |  |  |  |  |  | CPUCLK |  |  |  | EEP CLK |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| CLK2 |  |  |  |  |  | CICCLK | CLK (Pin 2) |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  |  |  |  |  | Reset In | Reset Out Slave (Pin 5) |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  |  |  |  |  | CIC1 | CIC1 (Pin 6) |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  |  |  |  |  | CIC0 | CIC0 (Pin 7) |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| GND |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | BYTE |  |
