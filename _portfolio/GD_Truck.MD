---
title: "Generative Design Skateboad Truck"
excerpt: "Creating a lightweight but sturdy electric longboard truck using Fusion 360's generative design workflow."
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
* Powder bed fusion is a form of SLS (selective laser sintering) manufacturing. It places layers of thermoplastic powder and targets the desired areas with a laser to melt and fuse them.

# Applying PBF and GD in Tandem
* The combination of these two technologies can be used in automative and aerospace applications, such as the (General Motors seat belt bracket)[https://kingsburyuk.com/what-are-the-applications-of-powder-bed-fusion/].

# Pros and Cons of GD
* Pros:
1. Achieves geometries that would be very difficult or impossible to design by hand.
2. Works based on the constraints you give it, so if your constraints are correct, there is less room for error than in designing by hand.
* Cons:
1. User must know the magnitude, direction, and location of all forces that will be exerted on the designed part.
2. Takes hours to calculate a generative design study. Long wait time before you can edit/iterate on the design.
3. Sometimes does not precisely honor the obstacle and preserve geometries.
4. May require additional editing/post-processing of the design.

# Design Considerations
* Obstacle geometries
1. I marked all surrounding components of the longboard as obstacles (wheels, gears, etc.)
* Preserve geometries
1. I created a sphere in the caivty for the pivot point of the truck and marked it as a preserve geometry.
2. I also created a cylindrical housing around the axle of the skateboard and marked it as a preserve geometry.
* I created four load cases:
1. Static load, with a rider standing on the board and gravity pulling on the board.
2. Torsion 1, with forces pulling up on the left side of the axle and down on the right side.
3. Torsion 2, with forces pulling up on the right side of the axle and down on the left side.
4. Moment, with rotational force on the motor mount.
* One area for improvement is in the area surrounding the gears on the left side, which would be connected by a belt in the final assembly. I marked this as a preserve geometry, when in reality it should have been an obstacle geometry. In the model below, there is no way for the gears to turn without rotating the entire truck.
* The model below was generated for fabrication with the material Aluminum AlSi10Mg.

# CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6ee223e11f01ab81fb?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

# Gallery
{% include gallery caption="Renderings of the generative design truck with surrounding electric longboard parts." %}

