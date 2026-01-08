---
layout: post
title: Draw komplex footprints
slug: footprints
excerpt: "Das ist die Kurzfassung meines Artikels."
---

# Hallo
hier ist ein Intro
# Hallo2


1. create sketch in Fusion and 
2. export it by rightclicking on the sketch as .dxf file. In the export menu uncheck all three boxes
3. create new footprint in KiCad
4. import DXF: File -> Import -> Graphics.. (CTRL+SHIFT+F). Leave the import scale as 1 and uncheck "group supported items"
5. select all the shapes belonging to one pad
6. right click "create from selection" -> "create polygon from selection.." and use the option "use centerlines"
7. change created pads to copper
8. create new pads and fit them inside the shape
9. right click on the pad and select "edit Pad as Graphic Shapes" or CTRL+E
10.Press CTRL+E to leave the Pad Edit Mode

The pad now should have the right shape