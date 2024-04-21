---
title: "Generative Design Skateboad Truck"
excerpt: "Using Fusion 360's generative design workflow to create a lightweight but sturdy longboard truck."
header:
  image: assets/img/truck-render-1.png
  teaser: assets/img/truck-render-1.png
gallery:
  - image_path: assets/img/truck-render-1.png
    alt: "Front view of rendered truck with surrounding electric longboard parts."
  - image_path: assets/img/truck-render-2.png
    alt: "Side/back view of rendered truck with surrounding electric longboard parts."
   
---

# About Generative Design
* Generative design is a CAD workflow that uses algorithms to create a design with organic geometries given user-defined constraints.
* These contraints include:
1. Obstacle geometries — regions the design must not encroach upon
2. Preserve geometries — regions which must be included in the design
3. Load cases — forces that the design must be able to withstand
4. Material — aluminum, nylon, etc. 
5. Manufacturing process - additive, milling, etc. 
6. Goal — minimize mass or maximize stiffness

# About Powder Bed Fusion
* x

# Applying PBF and GD in Tandem
* x

# Pros and Cons of GD
* x

# Design Considerations
* <obstacles>
* <preserves>
* <load cases>
* One area for improvement is in the area surrounding the gears on the left side, which would be connected by a belt in the final assembly. I marked this as a preserve geometry, when in reality it should have been an obstacle geometry. In the model below, there is no way for the gears to turn without rotating the entire truck.
* The model below was generated for use with the material Aluminum AlSi10Mg.

# CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6ee223e11f01ab81fb?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

# Gallery
{% include gallery caption="Renderings of the generative design truck with surrounding electric longboard parts." %}

