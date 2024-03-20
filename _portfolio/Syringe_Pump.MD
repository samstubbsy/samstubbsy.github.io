---
title: "Syringe Pump"
excerpt: "A DIY syringe pump that can achieve varying flow rates."
header:
  image: assets/img/pump-render.png
  teaser: assets/img/pump-render.png
gallery:
  - image_path: assets/img/pump-render.png
    alt: "Syringe pump rendering"
   
---

# Features

* Can accomodate varying syringe sizes.
* Can be programmed to achieve varying flow rates.

# Operating instructions

* Manually set your syringe diameter and desired flow rate in the Arduino code
* Fill syringe with liquid
* Secure front of syringe in slot of front barrel stablizer and back of plunger in carriage cutout
* Press on/off button
* Pumping will stop when carriage hits limit switch on back barrel stabilizer

# CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6e3a88846cffcd0187?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

# Arduino Code
<iframe src="https://docs.google.com/document/d/e/2PACX-1vSY45HmhXlK-GK7BBKmvlS7KyzTpgHUF3dQzUy6mMNF2LgMfBJjd6ALjxcJCUHS4gYRhCX21G6iZOkU/pub?embedded=true" width="100%" height="600"></iframe>

# Supplies
Off-the-shelf parts

| Part | Description |
| --- | --- |
| NEMA 17 Motor | Create rotational motion |
| Breadboard | Facilitate electrical connections |
| Elegoo UNO R3 | Contains the "smarts" of the device |
| Syringe | Holds liquid to be pumped out by the device |
| Lead Screw TR 8x8x250mm | Extends rotational motion of motor |
| Nut TR8x8-4 | Translates rotational motion of lead screw to linear motion of carriage |
| F688ZZ Flanged Ball Bearing (x2) | Holds lead screw in barrel stabilizers |
| Flexible coupler | Connects motor shaft to lead screw |
| Linear rod | Keeps carriage, back of barrel stablizer, and motor mounting plate aligned |
| LM8UU Linear bearing | Allows carriage to slide along rod |
| Lock collar | Hold linear rod in place |
| M3x8mm Thread-forming Screw (many) | Various fastenings |
| M3x8mm Bolt (many) | Various fastenings |
| M3x10mm Bolt (x4) | Fasten motor to motor mounting plate |
| M5 Tee Nut (x10) | Fasten custom components to aluminum extrusion |
| Power supply | Powers device |
| On-off button | Toggles power to device |
| V-Slot 20x40x350mm | Aluminum extrusion used to hold and align motor mounting plate and barrel stabilizers |

Custom-designed parts

| Part | Description |
| --- | --- |
| Enclosure | House all electrical components |
| Enclosure lid | Barrier between electrical components and linear actuator |
| Barrel stabilizer | Hold middle of barrel up and level with the aluminum extrusion |
| Back of barrel stabilizer | Hold back end of barrel up and level with the aluminum extrusion |
| Motor mounting plate | Hold motor up and level with the aluminum extrusion |
| Breadboard fastener (x2) | Hold breadboard in place in enclosure |
| Carriage | Moves linearly as screw rotates, compressing syringe plunger |


{% include gallery caption="Rendering of Syringe Pump" %}
