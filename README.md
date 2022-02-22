This project contains the design files for two cases for the Xilinx zc706 and zcu102 boards.
In the __pane_xdf__ folders, there are the vectorial files for the sides of the cases.
In the __corners__ folders, there are the 3D models of the corners to be glued to the panes.

# Building the corners
Models are designed with blender (.blend extension).
Models must be exported in .stl from blender.
STL models can be fed to __cura-lulzbot__ software to create the 3D printer specific model to be fed to the printer.
Printer models can be passed to the printer with an SD card.

# Building the panes
The Northeastern campus workshop provides cutting services for free.
You need to buy the plastic material, I used _Acrylic Plastic Sheet ZUVAS ZS01_.
The cutting task can be scheduled through this [link](https://docs.google.com/forms/d/e/1FAIpQLSfPmnPQYz9mszQH6EVhSFjhv6aymJODrvP0FqJ7bIy6zvabCA/viewform?pli=1).
After scheduling, material should be delivered to the workshop.

# Remarks from the latest printed release
## ZCX102
 - The large 3D printed corner provides holes in a position different from the cover.
 - The thickness of the plastic sheets obstruct the closing holes
 - the sheet on the sdcard side, has the opening for the sd card not aligned properly (too high or too low). Possible difference is 1/1.5 cm.
 - top panel should be longer on the open side (the one not blocked by the corner)
 - the open corner is very open. Should get it longer ~0.5 con the support side.

## ZC706
 - the large panes need to be enlarged of ~1mm on each side (4 sides).
 - the front bridge 3d printed has two dents (one per side) preventing the glueing with the bottom pane
 - back side is has the hole too high. It should be ~5mm lower
 - on the diagonals, the top pane should be outside as the holed part (2mm).
 - front-lower (small) side, is 2-3mm too high
 - on the back side, top pane should be ~3 mm longer

## Notes
 - You need clothing clippers to keep the pieces in place during glueing
 - one external one per corner is fine
 - glue the sides AFTER fixing the top pane to the corners (glued to the bottom pane)


## Both (IMPORTANT)
 - reduce the high of the lower support: the height between the bottom pane and the board!
 - power plug needs some extra room at the top for clicking
