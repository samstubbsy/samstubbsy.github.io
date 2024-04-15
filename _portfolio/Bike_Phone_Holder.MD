---
title: "Top-Down Bike Phone Holder"
excerpt: "Multi-component bike phone mount designed using top-down modeling."
header:
  image: assets/img/bike-phone-angle-ROTATE.jpg
  teaser: assets/img/bike-phone-angle-ROTATE.jpg
gallery:
  - image_path: assets/img/bike-phone-gif.gif
    alt: "Changing orientation of phone holder in bike mount."
  - image_path: assets/img/bike-phone-back.jpg
    alt: "Back angle of assembled bike phone mount."
  - image_path: assets/img/bike-phone-side.png
    alt: "Side angle of assembled bike phone mount."
  - image_path: assets/img/bike-phone-cross.jpg
    alt: "Cross-section of the securing/rotating mechanism."
  - image_path: assets/img/bike-phone-parts.jpg
    alt: "Printed parts of the bike phone mount prior to assembly."
   
---

# About Top-Down Modeling
* x

# Design Considerations
* The design takes a TPU phone case I had previously designed and adds a four-pronged extension ("spinner") to it, which is able to be secured vertically or horizontally (and rotated between the two) in a PLA "spin holder." The spin holder had claws that secure it to an adjustable TPU strap.
* When searching for inspiration for my design, I appreciated the design of a device similar to the one pictured [here](https://a.co/d/7i6rYRS). I started my design with a TPU grip around the handlebar, enclosed by a PLA shell, which was attached to a TPU strap. I later realized that this design could be simplified by making the grip and strap one piece and eliminating the PLA shell. However, the spin holder that secures the phone case and allows it to be rotated was originally part of that PLA shell. Thus, I turned the spin holder into its own part and added claws to secure it to the handlebar grip.
* I designed the spinner (cross section view available in the gallery below) with the intention that the four big bump-outs would fit securely in the four big cavities (designed with clearance and fillets), and to rotate the phone, they would need to overcome the small bump-outs of the spin holder. However, once I printed a cross-section to test this, I realized the fit was very loose when aligning the big bump-outs with the big cavities. However, when I rotated the inner piece, I realized that a secure fit was achieved when the TPU bump-outs were pinned in place by the small PLA bump-outs. Thus, I adjusted the orientation of the spinner section of the phone case by 45 degrees in order to achieve horizontal and vertical phone angles with the current design.
* I also originally designed the spinner with a wide base in the x-y plane to prevent movement in the z-direction. However, the spinner cross proved secure enough that this was not necessary, and I simplified the design accordingly. 
* One future improvement on this design could be to model the TPU handlebar grip as flat instead of curved. This way, it could easily accomodate handlebars of different diameters. It would also make the part easier to print and post-process — the current curved design required a lot of support material which was difficult to remove without damaging the strap. Based on this new proposed design, it might make sense to make the grip thinner in order to ensure graeter flexibility around the handlebar.
* Another potential improvement would be to extend the claws of the PLA part to wrap around the flat edges of the TPU grip more in order to better secure it in place. However, the thinning of the grip proposed above may impede this. In that case, a different mechanism to secure the PLA spin holder to the TPU bar grip without claws may be useful.

# Assembly Instructions
* Place the TPU grip on the handlebar. Pull the strap tight and hold one of its holes at angle in order to wrap it around the TPU knob.
* Place your phone in the phone case. Insert the phone case's spinner into the PLA spin holder at a 45 degree angle. Then, turn the phoen 45 degrees in either direction to lock it into place.
* Secure the claws of the PLA spin holder around the TPU grip on the handlebar.

# Material Choice
* TPU allows for grip on the handlbar and flexibility to wrap the strap around it. The TPU knob is thick enough to sturdily affix the strap to through one of its holes.
* TPU also allows enough flexibilty to insert a phone into the phone case, while still providing a secure fit.
* The TPU-PLA interface between the spinner and spin holder is key to this design. The small PLA bump outs indent the big TPU bump-outs enough to hold it in place. The TPU is still flexible enough that the device can be rotated between positions easily.

# CAD Model


{% include gallery caption="Printed bike phone mount" %}

