# USBSocket project

USB Socket board came into existence as alternative to cheap miniUSB adapters which we not good enough for me.
These cheap boards do not care about D+/D- traced being equally long which is essential for USB wiring.
I had to design my own microUSB adapter board to fit my needs.

## USBSocket_Type1_v1.0

**USBSocket_Type1_v1.0** is a simple microUSB adapter board, which mostly designed to be breadboard friendly.

Preview:

![USBSocket_Type1_v1.0 preview](USBSocket_Type1_v1.0.png)

[Schematics in PDF format](USBSocket_Type1_v1.0.pdf)

Features:

- breadboard friendly
- small size
- includes decoupling capacitor
- includes power LED indicator
- 3mm mount holes

CAM files are available.

## USBSocket_Type2_v1.0

**USBSocket_Type2_v1.0** is a simple microUSB adapter board mostly usable for smaller or cable applications.

Preview:

![USBSocket_Type2_v1.0 preview](USBSocket_Type2_v1.0.png)

[Schematics in PDF format](USBSocket_Type2_v1.0.pdf)

Features:

- 0.1" raster board friendly
- even smaller size
- suitable for cable mount
- shrink-tube friendly

CAM files are available.

## BOM

Bill Of Materials is currently available only for LCSC Electronic Components Distributor, which is probably cheapest anyway.

### LCSC BOM

|Designator  |Part/Value      |Package/Footprint    |LCSC #  |
|------------|----------------|---------------------|--------|
|CN1         |MOLEX 473460001 |SMD                  |C132560 |
|C1\*        |Cap. 47uF       |0805                 |C109461 |
|C2\*        |Cap. 100nF      |0402                 |C60474  |
|LED1\*      |LED Green       |0603                 |C364559 |
|R1\*        |Res. 1K         |0402                 |C384390 |

\*) These passive components are optional but it's recommended to install them.

## How to help

Your contributions as code, resources or finances are welcome!
Please contact me directly over e-mail andriy.golovnya@gmail.com or over [GitHub profile](https://github.com/red-scorp).
Link for [Paypal donations](http://paypal.me/redscorp), which are always welcome.
Thanks in advance!
