# Fabricating Engravinator Components

The Engravinator is specifically designed to utilize the benefits of 3D printed components as much as possible. All of the core, required, non-metal components can be printed on most commodity 3D printers. If you do not access to a 3D printer there are many online services such as [MakeXYZ](https://makexyz.com) or [Shapeways](https://shapeways.com) that could print them for you. However, going the online service route could add significant cost. We recommend first trying to find a makerspace, library, or school in your area that might have a printer you can use.

While there are links to individual files listed here we recommend downloading the entire [Engravinator repository](https://github.com/ManiacalLabs/Engravinator/archive/master.zip) which will include all required files.

## Print Settings

**PLEASE NOTE:** All Engravinator components have be design specifically with the given print settings in mind. There are features of the models that depend on these settings and may not print correctly if not followed.

All components should be printed in PLA with the following settings:

- 0.4mm nozzle diameter
- 0.2mm layer height
- 20% Grid Infill
- Top & Bottom layers Rectilinear Infill

Any other settings would depend on your particular filament and printer capability but we recommend using high quality filament with consistent diameter. We are partial to Atomic Filament or Prusa brands (though are in no way sponsored by those companies).

Final word on quality and accuracy: The Engravinator is designed with relatively tight tolerances so your prints need to be as accurate as possible. If you are unsure, we recommend printing this [calibration cube](https://www.thingiverse.com/thing:1586206) with the filament you want to use first as a test, with the above settings. If any dimension deviates from 20mm by more than 0.1mm, you should spend some time dialing in your extrusion settings for that filament until it is within 0.1mm tolerance.

## Core Components

The core, required components can be found under [/Mk1/Fabrication/3D_Printed/Core_Components](/Mk1/Fabrication/3D_Printed/Core_Components).

If you have an i3-style printer with a print plate equal to or larger than 205mm x 225mm (only 45mm required in the Z axis) then you can simply load this file:

[CorePrintPlate.stl](/Mk1/Fabrication/3D_Printed/Core_Components/CorePrintPlate.stl)

It includes everything in a single file, already laid out for maximum print efficiency.

If you either have a smaller printer or just want to print individual components you can use the files listed below to print as desired. *Note that for components prefixed with a number (such as `x4_RodHolder.stl`) that value is the number of copies required for the component.*

- [HeightTool.stl](/Mk1/Fabrication/3D_Printed/Core_Components/HeightTool.stl)
- [x4_RodHolder.stl](/Mk1/Fabrication/3D_Printed/Core_Components/x4_RodHolder.stl)
- [X_Back_Plate.stl](/Mk1/Fabrication/3D_Printed/Core_Components/X_Back_Plate.stl)
- [X_Front_Plate.stl](/Mk1/Fabrication/3D_Printed/Core_Components/X_Front_Plate.stl)
- [X_Motor_Mount.stl](/Mk1/Fabrication/3D_Printed/Core_Components/X_Motor_Mount.stl)
- [X_Tensioner.stl](/Mk1/Fabrication/3D_Printed/Core_Components/X_Tensioner.stl)
- [Y_Drive_Main.stl](/Mk1/Fabrication/3D_Printed/Core_Components/Y_Drive_Main.stl)
- [Y_Drive_Plate.stl](/Mk1/Fabrication/3D_Printed/Core_Components/Y_Drive_Plate.stl)
- [Y_Idle_Main.stl](/Mk1/Fabrication/3D_Printed/Core_Components/Y_Idle_Main.stl)
- [Y_Idle_Plate.stl](/Mk1/Fabrication/3D_Printed/Core_Components/Y_Idle_Plate.stl)
- [Y_Motor_Mount.stl](/Mk1/Fabrication/3D_Printed/Core_Components/Y_Motor_Mount.stl)
- [Y_Pulley_Mount.stl](/Mk1/Fabrication/3D_Printed/Core_Components/Y_Pulley_Mount.stl)
- [Y_Tensioner.stl](/Mk1/Fabrication/3D_Printed/Core_Components/Y_Tensioner.stl)

## Controller Mount

Since there are multiple options for supported controllers, you will need to at least print one of the following base plates, for your controller:

- [Maniacal Labs Platypus](https://github.com/ManiacalLabs/Platypus) -> [BasePlate_Platypus.stl](/Mk1/Fabrication/3D_Printed/Controller_Box/BasePlate_Platypus.stl)
- [Bart Dring Pen/Laser Controller](https://www.tindie.com/products/33366583/penlaser-bot-controller/) -> [BasePlate_BartDring_PenLaserController.stl](/Mk1/Fabrication/3D_Printed/Controller_Box/BasePlate_BartDring_PenLaserController.stl)

Then, optionally print the cover which fits on all provided base plates:

[ControllerCover.stl](/Mk1/Fabrication/3D_Printed/Controller_Box/ControllerCover.stl)


## Enclosure

The full enclosure is an optional (but **HIGHLY RECOMMENDED!**) addon for the Engravinator. When made with the correct type of acrylic you can reasonably use the machine without worrying about safety glasses. If you do not opt to use the full enclosure **NEVER** use the Engravinator without all people in the room wearing appropriate safety glasses.

__*DISCLAIMER*__: *Our research has shown that the suggested acrylic below will block any and all dangerous light coming from the laser, making it safe to use without special glasses. However, without acquiring laboratory tested (and much more expensive) acrylic that is specifically validated for this use we cannot guarantee your complete eye safety. Maniacal Labs assumes no responsibility for any damage or injury caused by use of these designs.*

### Enclosure - Laser Cut Parts

As designed, the enclosure is constructed of 3mm (1/8 inch) thick `2422 Amber` acrylic. Acrylic naturally blocks nearly all UV light and this amber variety blocks most of the remaining visible light. You could, in theory, also use transparent red or green with much the same effect. But we have tested the `2422 Amber` and know it works. Plus it looks cool :)

If you do not have a laser cutter of your own, we recommend first trying to find a local makerspace and use theirs. Most online acrylic suppliers will carry 2422 sheets as will most local plastic suppliers if you have one nearby. You should be able to get everything you need out of a single 24" x 48" (1220mm x 610mm) sheet.

If the above is not an option, there are a number of online laser cutting services you could use such as [Ponoko](https://www.ponoko.com/laser-cutting) or [Pololu](https://www.pololu.com/product/749), most of which should carry 2422 acrylic.

You will need to cut one each of the following DXF files:

- [BackPanel.dxf](/Mk1/Fabrication/Laser_Cut/BackPanel.dxf)
- [FilterHolder.dxf](/Mk1/Fabrication/Laser_Cut/FilterHolder.dxf)
- [FrontPanel.dxf](/Mk1/Fabrication/Laser_Cut/FrontPanel.dxf)
- [LeftPanel.dxf](/Mk1/Fabrication/Laser_Cut/LeftPanel.dxf)
- [RightPanel.dxf](/Mk1/Fabrication/Laser_Cut/RightPanel.dxf)
- [TopPanel.dxf](/Mk1/Fabrication/Laser_Cut/TopPanel.dxf)

Optionally, we've designed a bottom panel that aids with aligning the laser (since the working area is not centered to the machine). The actual working area position is dependent on the laser module in use. Select the necessary one below based on the module X,Y dimensions:

- 33mm x 33mm -> [TargetingFrame_33x33.svg](/Mk1/Fabrication/Laser_Cut/TargetingFrame_33x33.svg)

Note that the linked file is an SVG instead of DXF. This is because the black lines should be cut but the red lines just need to be engraved as they are simple measurement markings.

### Enclosure - 3D Printed Parts

Next, you need to print some additional components using the same settings described above. As before, we provide an all-in-one file to print:

[EnclosurePrintPlate.stl](/Mk1/Fabrication/3D_Printed/Enclosure/EnclosurePrintPlate.stl)

You can, however, find the individual files below. *Note that for components prefixed with a number (such as `x8_PanelClips.stl`) that value is the number of copies required for the component.*

- [x2_Handles.stl](/Mk1/Fabrication/3D_Printed/Enclosure/x2_Handles.stl)
- [x4_ExtensionBracket.stl](/Mk1/Fabrication/3D_Printed/Enclosure/x4_ExtensionBracket.stl)
- [x4_Feet.stl](/Mk1/Fabrication/3D_Printed/Enclosure/x4_Feet.stl)
- [x8_PanelClips.stl](/Mk1/Fabrication/3D_Printed/Enclosure/x8_PanelClips.stl)

Note, if you are not going to use the optional framing panel (see more below), you do not need to print `x4_Feet.stl`.