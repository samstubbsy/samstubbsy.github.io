---
title: "Multimaterial Pliers"
excerpt: "Print-in-place, dual-extruded flexible pliers."
header:
  image: assets/img/pliers.heic
  teaser: assets/img/pliers.heic
gallery:
  - image_path: assets/img/devicejpg.jpg
    alt: "PDMS molded uFluidic device"
  - image_path: assets/img/moldjpg.jpg
    alt: "Resin VPP printed uFluidic device mold"
  - image_path: assets/img/uflu_detail.png
    alt: "Pyramid detail in CAD model of uFluidic mold straight channel"
  - image_path: assets/img/ulfu2_detail.png
    alt: "Pyramid detail in CAD model of uFluidic mold channel with shaped obstacles"
   
---

# Features
* Mixes two liquids over a short distance.
* Bi-directional: liquid can enter through either end of the the device (with differing mixing efficacy).

# Intro to Print-in-Place
* There are many situations in which homogenous mixing of small volumes of fluids is necessary, particularly in biomedical fields. One practical example is in the creation of bioinks: https://www.mdpi.com/2310-2861/7/4/227.
* Maximizing mixing over a minimal distance allows for conservation of expensive fluids. A long serpentine path would be an effective mixer, but it requires a lot of fluid to be held up in the device for that mixing to occur. Thus, a short, effective mixing section can be a major money saver.

# Pliers in Action
![](assets/img/gif-1.gif)
![](assets/img/gif02.gif)

# Design decisions
* Channel width = 0.35 mm: wide enough for accurate print resolution, thin enough for highly effective mixing
* Serpentine channel provides greater opportunity for mixing (effective)
* Pyramids carved out of straight channel allow for 3D mixing - fluid "folds over" itself (effective)
* Various shaped obstacles (some with 3D pyramid cutouts) intended to increase mixing (ineffective)

# Fabrication instructions
* Print mold on a VPP resin printer with sufficient resolution using black or high-temp resin.
* Wash device for 5 minutes on the print bed.
* Remove device from bed and wash for another 5 minutes in fresh IPA.
* Let your device dry for 30 minutes before curing. Confirm that the inside of the mold
has a homogenous sheen. Glossy areas indicate that uncured resin is still present, which
will inhibit the crosslinking of PDMS.
* Gently blow off any debris between your uFluidic’s channel. Use compressed air if necessary. Do not touch the inside of the uncured mold.
* Perform a 10 second surface cure.
* Coat mold in parylene.
* Cast device in mold using PDMS.
* Plasma bond glass slide to PDMS device. 

# CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6ee89ec95aa46b5c65?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

# Videos
<iframe width="560" height="315" src="https://www.youtube.com/embed/RxSdNnKR72w?si=_03tpEWzyIVhuD1p" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
<iframe width="560" height="315" src="https://www.youtube.com/embed/zdfmGJGKx-Y?si=MGBBL_vXAGIoeX_M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

{% include gallery caption="uFluidic device, mold, and CAD channel pyramid details in mold" %}
