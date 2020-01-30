# SerialChiller
> ESP32 and MAX3232 based wireless RS232 adapter for the Internet of old things.

<img src="https://i.imgur.com/FYeBvYt.png" width="480">
<img src="https://i.imgur.com/sKjFjxz.jpg" width="480">
<img src="https://i.imgur.com/4ShiExd.jpg" width="480">

## Build video
[![DuinoDCX Demo Video](https://img.youtube.com/vi/_-YNTO3l9uc/0.jpg)](https://www.youtube.com/watch?v=_-YNTO3l9uc)

## Wiring
The wiring is implemented as DTE. RS232 TX and RX are connected to the default Serial2 pins IO16 and IO17. RTS is connected to IO21 and CTS to IO22.

## Partlist
| Part         | Value          | Package      | Part #           |
| ------------ | -------------- | ------------ | ---------------- |
| C1           | 0.1uF          | C0603        | C0603X104K5RAC   |
| C2           | 0.1uF          | C0603        | C0603X104K5RAC   |
| C3           | 0.1uF          | C0603        | C0603X104K5RAC   |
| C4           | 0.1uF          | C0603        | C0603X104K5RAC   |
| C5           | 0.1uF          | C0603        | C0603X104K5RAC   |
| C6           | 22uf           | A/3216-18R   | T491A226M010AT   |
| C7           | 22uf           | A/3216-18R   | T491A226M010AT   |
| C8           | 22uF           | C1206        | LMK316ABJ226KL-T |
| C9           | 0.1uF          | C0603        | C0603X104K5RAC   |
| C10          | 0.1uF          | C0603        | C0603X104K5RAC   |
| ESP-WROOM-32 | ESP-WROOM-32   | ESP-WROOM-32 | ESP-WROOM-32     |
| IC1          | LM1117IMPX-3.3 | SOT223       | NCV1117ST33T3G   |
| MAX3232      | MAX3232CSE     | SO16         | MAX3232IDR       |
| R1           | 10k            | R0603        | NRC06J103TRF     |
| RS232        | 56F402-001     | 56F402-001   | 56F402-001       |
| S1           | B3U-1000P      | SW_B3U-1000P | B3U-1000P        |
| S2           | B3U-1000P      | SW_B3U-1000P | B3U-1000P        |
| SERIAL       | Serial         | 1X02         | pinhead          |
| VIN          | Power          | 1X02         | pinhead          |

## PCB Thickness
Use 0.8mm thick pcb to make the board align horisontally with the case.

## Other components
### Case
<img src="https://i.imgur.com/vMuh47L.jpg" width="300">

The plastic housing is taken from a cheap vga break out board available from multiple different vendors. Search eBay or Aliexpress for `DB15 breakout`. 

### USB to TTL Cable
<img src="https://i.imgur.com/Rv4BXdY.jpg" width="400">
USB to TTL serial adapter cable for powering and flashing the board.

### Strain Relief
<img src="https://i.imgur.com/pojF2cD.png" width="400">
Print the strain_relief.stl out of any plastic material to properly secure the cable to the housing.

### Cord Sleeve
<img src="https://i.imgur.com/vxLgsbd.jpg" width="200">

The black 4mm cord sleeve is available from multiple different vendors. Snip the end off to make it fit. Search eBay or Aliexpress for `4mm cord sleeve` or `4mm strain relief`.

## Installation
Make sure that the thumb screws are properly tightened or remove them completely. A loose thumb screw may short circuit the electronics.

When used with an extension cable the thumb screws can be replaced with #4-40 jackscrews.

<img src="https://i.imgur.com/62l8ALO.jpg" width="400">

## Power Supply
Any standard usb charger will work fine. The average power consumption is under 500mA.

## Example projects
https://github.com/lasselukkari/DuinoDCX

https://github.com/AlphaLima/ESP32-Serial-Bridge

## License
Creative Commons — Attribution 4.0 International
