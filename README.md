# RFID-Card-Clone

## Use

1. Connect to serial port at `115200` baud.
2. Input command at serial：
    - `R`：read
    - `W`：write/clone
    - `U`：show cache

## Burn

1. Download library：
   - [MFRC522 driver (v1.4.9)](https://github.com/miguelbalboa/rfid/tree/1.4.9)
2. Use pin layout：
    | Signal | MFRC522 Pin | Arduino Pin |
    | :-: | :-: | :-: |
    | RST/Reset | RST | D9 |
    | SPI SS | SDA(SS) | D10 |
    | SPI MOSI | MOSI | D11 |
    | SPI MISO | MISO | D12 |
    | SPI SCK | SCK | D13 |
3. Upload
