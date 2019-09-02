# Engravinator FAQ

## Why did you create the Engravinator?

It started with a conversation about woodworking. We wanted to be able to engrave a custom maker's mark on something large like furniture but most engravers assumed the material would be brought to the machine. This was not feasible in many cases. So the idea for a super-portable engraver with small working area that could be brought to the material was born.

To take things further, most engravers in the $200 - $400 price range were, in our opinion, of poor build quality and precision. Using simple wheels and belts for motion. So we sought to hit the same price point but with higher quality and precision motion components.

## What controls the Engravinator?

It was designed specifically to be used the popular [GRBL](https://github.com/gnea/grbl) firmware. It's simple to use, robust, and has a great community. As such you could technically use any GRBL controller but we recommend using our own [Platypus](https://github.com/ManiacalLabs/Platypus) GRBL board, which was designed specifically for use with the Engravinator.

However, we provide mounts for multiple control boards, all of which can be found in the [fabrication files](/Mk1/Fabrication/3D%20Printed/Controller%20Box). More details can be found in that directory along with each file.

## What do I need to build an Engravinator?

We tried to keep the design as simple and easy to build as possible. All the hardware can be easily ordered from the links provided in the [Bill of Materials](). All other components are either 3D printed (required core components) or laser cut (optional enclosure) and can be found in the [fabrication directory](/Mk1/Fabrication/). Please checkout the [3D printing](/3DPrinting.md) docs for more details on how to print those components.

Aside from the components above, you will require the following tools:

- 1.5, 2.5, and 4mm hex keys (ideally with a ball end)
- flush-cut snippers
- wire strippers
- soldering iron (only needed for limit switches)
- multi-meter can be helpful, but not required