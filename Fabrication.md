# Fabricating Engravinator Components

The Engravinator is specifically designed to utilize the benefits of 3D printed components as much as possible. All of the core, required, non-metal components can be printed on most commodity 3D printers. If you do not access to a 3D printer there are many online services such as [MakeXYZ](https://makexyz.com) or [Shapeways](https://shapeways.com) that could print them for you. However, going the online service route could add significant cost. We recommend first trying to find a makerspace, library, or school in your area that might have a printer you can use.

## Print Settings

**PLEASE NOTE:** All Engravinator components have be design specifically with the given print settings in mind. There are features of the models that depend on these settings and may not print correctly if not followed.

All components should be printed in PLA with the following settings:

- 0.4mm nozzle diameter
- 0.2mm layer height
- 20% Grid Infill
- Top & Bottom layers Rectilinear Infill

Any other settings would depend on your particular filament and printer capability but we recommend using high quality filament with consistent diameter. We are partial to Atomic Filament or Prusa brands (though are in no way sponsored by those companies).

Final word on quality and accuracy: The Engravinator is designed with relatively tight tolerances so your prints need to be as accurate as possible. If you are unsure, we recommend printing this [calibration cube](https://www.thingiverse.com/thing:1586206) with the filament you want to us first as a test, with the above settings. If any dimension deviates from 20mm by more than 0.1mm, you should spend some time dialing in your extrusion settings for that filament until it is within 0.1mm tolerance.

## Core Components

The core, required components can be found under [/Mk1/Fabrication/3D_Printed/Core_Components](/Mk1/Fabrication/3D_Printed/Core_Components).

If you have an i3-style printer with a print plate equal to or larger than 205mm x 225mm (only 45mm required in the Z axis) then you can simply load this file:

[CorePrintPlate.stl](/Mk1/Fabrication/3D_Printed/Core_Components/CorePrintPlate.stl)

It includes everything in a single file, already laid out for maximum print efficiency.