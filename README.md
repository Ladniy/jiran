# jiran-breakoff
 Jiran is a 6x4 matrix ergo keyboard with additional 3 thumb and 1 pinky keys.

<img src="https://i.imgur.com/HnA2Onc.png" data-canonical-src="Render" height="430"/>

Based on the [Jian](https://github.com/KGOH/Jian-Info) keyboard.

* __Author:__ [t.me/ladniys](https://t.me/ladniys) [u/Ladniy](https://reddit.com/u/Ladniy)
* __Layout:__ [keyboard-layout-editor.com](http://www.keyboard-layout-editor.com/#/gists/0547cd126f61f8c3f76b0a9952901da4)
* __Hardware Availability:__ open source, t.me/ladniys
* __Firmware:__ [QMK](https://github.com/Ladniy/qmk_firmware)
* __Building guide:__ not available yet
* __Parts (BOM):__

| Name           | Value         | Package           | Count        | Optional  | Comment            |
| :------------- | ------------: | :---------------- | -----------: | :-------- | :----------------- |
| Pro micro      | 5V 16MHz      |     17.78x33.02mm | 2            |           |                    |
| Switch         |               | MX/Alps/Choc      | 56           |           |                    |
| Diode          | 1N4148        | THT/SMD (SOD-123) | 56           |           |                    |
| Resistor       | 4.7k          | THT/SMD (1206)    | 2            |  yes      | Must be placed on the master half |
| TRRS jack      |               | PJ-320A           | 2            |           | Optional if you're building only one half  
| Tact switch    |               | DIP 3X6X4,3mm     | 2            |  yes      |                    |
| Mosfet         | 2N7002        | SOT-123           | 2            |  yes      | Optional for LED's |
| Resistor       | 10k           | THT/SMD (1206)    | 2            |  yes      | Optional for LED's |
| Resistor       | 330           | THT/SMD (1206)    | 56           |  yes      | Optional for LED's |
| LED            |               | THT 1.8mm         | 56           |  yes      | Optional           |

[![MechChurch](https://i.imgur.com/QHzKmkz.png)](https://t.me/s/mechchurch) Supported by [MechChurch](https://t.me/s/mechchurch) community
