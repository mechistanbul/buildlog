# QOL56

## Features

The QOL56 is a 56-key keyboard with an nearly ortholinear array.
The ortholinear keyboard is famous for planck, but it has 2 rows and 8 keys more than planck.
Arranging 6 keys that can be pressed naturally with the thumb inevitably required 14 rows.
As a result, you can perform frequent key operations such as shift, space, enter, and layer switching with your thumb.
In addition, it is designed with thumb shift input in mind, solves various problems in current thumb shift input, incorporates the latest keyboard trends, and comfortably thumb shift input just by connecting. It is a keyboard that aims to be able to do it.

! [qol56] (qol56-7.jpg)

## Supports thumb shift input

Users of thumb shift input are making efforts such as purchasing an expensive dedicated keyboard, looking for a so-called B-cracked keyboard, and shifting the right hand key of the orz array by one row, but by making it yourself The purpose is to realize the best keyboard for thumb shift.
At the same time, we are aiming to break away from the traditional row staggered asymmetric keyboard layout and move to a more efficient layout.
I think that the key layout should be symmetrical especially when pressing the thumb shift at the same time.
There are many more ergonomic keyboard layouts, but first I tried to make it a simple and easy-to-use orthogonal grid layout.
The 6 keys to be pressed with the thumb are lowered by 0.25U so that they can be pressed comfortably with the thumb at the same time.

In addition, additional software is usually required for thumb shift input.
As software for thumb shift, there are software such as Yamabuki R and Lacaille.
The firmware QMK for homebrew keyboards is so sophisticated that it supports thumb shift input at the firmware level.
Thumb shift input is possible without additional software.

## LED

The backlight and underglow LEDs are cool and satisfy your desire for ownership, so you can install 71 full-color LEDs (56 backlights, 15 underglows) so that you can fully enjoy QMK animation. It has become.

## Implementation features

* Place Pro Micro under the key to minimize footprint
* 54 keys that do not overlap with Pro Micro adopt a socket to make the key switch replaceable
* Con-through compatible, Pro Micro can be attached and detached
* Be careful not to make the whole thick by tilting

## About production

Since there is no kit sale etc., it is necessary to have the manufacturer produce parts such as PCB, but we have released Gerber files and eps files for acrylic cutting.
It is not suitable for beginners, but parts can be easily procured with some knowledge.

Parts list

|          Part name                  | Specifications          | Quantity |
| ----------------------------------- | ----------------------- | -------- |
| PCB top plate                       | 1.6mm                   | 1        |
| PCB board                           | 1.6mm                   | 1        |
| 3 types of acrylic bottom plates    | 2mm                     | 1 set    |
| Key switch                          | MX compatible           | 56       |
| Keycap                              | 1U                      | 56       |
| Screws                              | M2 x 4mm                | 12       |
| Screws                              | M2 x 10mm               | 4        |
| Spacer                              | M2 x 7mm                | 8        |
| Pro Micro                           | ATmega32U4 5V 16MHz     | 1        |
| Diode                               | 1N4148W or 1N4148       | 56       |
| Kailh PCB Socket                    | CPG151101S11            | 54       |
| Tact switch                         | 2 poles SMD 4x3x2mm     | 1        |

When attaching the LED, prepare the following parts. It works without it.

| Part name | Specifications     | Quantity           |
| --------- | ------------------ | ------------------ |
| LED       | SK6812 mini 3535   | 56                 |
| LED tape  | WS2812             | 25cm 15 pieces     |

For reference price, I ordered 3 items of PCB, top plate and bottom plate from elecrow, but it was less than $ 100 including 5 sets of minimum unit and shipping fee.
Other common parts of homebrew keyboards such as Cherry MX compatible switches, keycaps, Pro Micros, diodes, sockets and M2 screws are used.
In addition, the kicad file is also open to the public, so you can freely modify it to create your own layout.
The QMK code can be found on [GitHub] (https://github.com/eswai/qmk_firmware/tree/master/keyboards/eswai/qol56) so you can modify the keymap.

! [qol56] (qol56-parts.jpg)

! [qol56] (qol56-pcb1.png)

! [qol56] (qol56-pcb2.png)

! [qol56] (qol56-1.jpg)

! [qol56] (qol56-2.jpg)

! [qol56] (qol56-3.jpg)

! [qol56] (qol56-4.jpg)

! [qol56] (qol56-6.jpg)
