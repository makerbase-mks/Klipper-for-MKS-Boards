# README
- Use Xloader upload firmware.hex file

# About pin settings
  | Items    | Function   | Marlin Pin | Klipper pin|
  |----------|------------|------------|------------|
  | Heater   | H-BED      | D8         | PH5        |
  | Heater   | HE0        | D10        | PB4        |
  | Heater   | HE1        | D7         | PH4        |
  | PWM FANs | FAN        | D9         | PH6        |
  | THM      | TH1        | A13        | PK5        |
  | THM      | TB         | A14        | PK6        |
  | THM      | TH2        | A15        | PK7        |
  | Steppers | X_EN       | D38        | PD7        |
  | Steppers | X_STEP     | A0(D54)    | PF0        |
  | Steppers | X_DIR      | A1(D55)    | PF1        |
  | Steppers | Y_EN       | A2(D56)    | PF2        |
  | Steppers | Y_STEP     | A6(D60)    | PF6        |
  | Steppers | Y_DIR      | A7(D61)    | PF7        |
  | Steppers | Z_EN       | A8(D62)    | PK0        |
  | Steppers | Z_STEP     | D46        | PL3        |
  | Steppers | Z_DIR      | D48        | PL1        |
  | Steppers | E0_EN      | D24        | PA2        |
  | Steppers | E0_STEP    | D26        | PA4        |
  | Steppers | E0_DIR     | D28        | PA6        |
  | Steppers | E1_EN      | D30        | PC7        |
  | Steppers | E1_STEP    | D36        | PC1        |
  | Steppers | E1_DIR     | D34        | PC3        |
  | Endstops | X-(XDIAG)  | D3         | PE5        |
  | Endstops | X+(E0DIAG) | D2         | PE4        |
  | Endstops | Y-(YDIAG)  | D14        | PJ1        |
  | Endstops | Y+(E1DIAG) | D15        | PJ0        |
  | Endstops | Z-(ZDIAG)  | D18        | PD3        |
  | Endstops | Z+         | D19        | PD2        |
  | EXP1_1   | BEERPER    | D37        | PC0        |
  | EXP1_2   | BTN_ENC    | D35        | PC2        |
  | EXP1_3   | LCD_EN     | D17        | PH0        |
  | EXP1_4   | LCD_RS     | D16        | PH1        |
  | EXP1_5   | LCD_D4     | D23        | PA1        |
  | EXP1_6   | LCD_D5     | D25        | PA3        |
  | EXP1_7   | LCD_D6     | D27        | PA5        |
  | EXP1_8   | LCD_D7     | D29        | PA7        |
  | EXP2_1   | MISO       | D50        | PB3        |
  | EXP2_2   | SCK        | D52        | PB1        |
  | EXP2_3   | BTN_EN1    | D31        | PC6        |
  | EXP2_4   | SD_SS      | D53        | PB0        |
  | EXP2_5   | BTN_EN2    | D33        | PC4        |
  | EXP2_6   | MOSI       | D51        | PB2        |
  | EXP2_7   | SD_DET     | D49        | PL0        |
  | TMC_UART | X_TX       | D40        | PG1        |
  | TMC_UART | X_RX       | A9(D63)    | PK1(Use it)|
  | TMC_UART | Y_TX       | A5(D59)    | PF5        |
  | TMC_UART | Y_RX       | A10(D64)   | PK2(Use it)|
  | TMC_UART | Z_TX       | D42        | PL7        |
  | TMC_UART | Z_RX       | A11(D65)   | PK3(Use it)|
  | TMC_UART | E0_TX      | D44        | PL5        |
  | TMC_UART | E0_RX      | A12(D66)   | PK4(Use it)|
  | TMC_UART | E1_TX      | D20        | PD1        |
  | TMC_UART | E1_RX      | D12        | PB6(Use it)|