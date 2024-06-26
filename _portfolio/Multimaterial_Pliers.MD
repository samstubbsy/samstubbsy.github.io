---
title: "Multimaterial Pliers"
excerpt: "Print-in-place, dual-extruded flexible pliers."
header:
  image: assets/img/pliers.jpg
  teaser: assets/img/pliers.jpg
gallery:
  - image_path: assets/img/gif-1.gif
    alt: "Using pliers to pick up a paperclip"
  - image_path: assets/img/pliers-internal.png
    alt: "CAD view of the middle layer of the pliers, showing the interlocking spring"
  - image_path: assets/img/pliers-external.png
    alt: "CAD view of the top of the pliers, concealing the interlocking spring"
  - image_path: assets/img/gif02.gif
    alt: "Pliers opening and closing"
   
---

# About the Project
* Print-in-place is a design methodology for 3D printing devices that require joints or motion. Under this methodology, devices are designed such that they are assembled through the printing process rather than through post-processing. This may be achieved through building clearance into the design to create multiple components or including a flexible element in the design. Print-in-place designs are often used for devices that depend on [gears](https://thangs.com/designer/3dprintingworld/3d-model/Gift%20Box%20%237%20Print-in-Place-518615) or [bearings](https://core-electronics.com.au/guides/print-in-place-tips/).
* In this project, I designed a pair of print-in-place pliers using a flexible component. The approach I used to achieve flexibility was using a flexible plastic, 95A TPU. However, the jaws and handle of the pliers needed to be sturdier, so I printed those sections out of PLA. This multimaterial design was printed on a dual-extrusion printer in Vanderbilt’s Digital Fabrication Lab. This dual-extrusion capability allowed me to achieve geometries that would not have been possible If I printed each component separately. In other words, my design could not have been assembled by hand.
* When selecting materials for a multimaterial print, it is important to consider their [properties](https://www.reddit.com/r/3Dprinting/comments/1alci8m/compatibility_of_fdm_polymers_at_multimaterial/).


# Design Considerations
* To interlock the spring with the body of the pliers, I originally designed a curved claw style locking mechanism. However, since the claws got thinner as they got farther from the square of the spring, they were not an optimal locking mechanism. Instead, I created my own take on the classic dovetail joint, incorporating the curvature aspect from my original design, but making the fingers of the joint get wider as the got farther from the spring square. Thus, with the plier body filling in the gaps, the spring would not come loose when pulled. To enhance the security of the spring in the z-axis, I added layers of PLA covering the joints between the spring and pliers on both the top and bottom of the device. The layer adhesion between PLA and TPU also helps the spring stay secured in the body of the pliers.
* I added (or, rather, subtracted) relief cutouts around each corner of the spring to ensure greater flexibility.

# Key Design Specs
* Jaw length: 40.625mm
* Jaw capacity: 10.624mm
* Spring inner square width: 25mm
* Spring finger height: 10mm

# Print Settings
* To vary the level flexibility in the spring, adjust infill settings before printing.

# CAD Model: Pliers
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6e18ad48dceab920b5?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

# CAD Model: Internal Spring
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6e4cb22dce40be087c?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

{% include gallery caption="Pliers in action, internal interlocking spring" %}
