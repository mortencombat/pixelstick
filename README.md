# Pixelstick

Pixelstick is a [GP2040-CE](https://gp2040-ce.info/) based retro joystick. It is a simple, high quality joystick with genuine arcade parts (Sanwa lever and 2-4 Qanba Gravity KS push buttons).

Being GP2040-CE based, it offers multi-platform compatibility, very low latency and endless customization possibilities.

The design is inspired by the awesome [Immortal Joystick](https://www.immortaljoysticks.co.uk/).

Common features:
- RP2040 Mini Breakout Board (for GP2040-CE)
- Sanwa JLX2 lever
- 2/4 action buttons (Qanba Gravity KS 30 mm push buttons)
- Modifier/Fn button (Qanba Gravity KS 24 mm push button)
- 2 rocker switches for Turbo and Focus Mode (or any other toggleable features supported by GP2040-CE)
- Detachable USB cable with push-pull locking system

Currently there are designs for these variants:
- Pixelstick S (right stick), compact size with stick on the right side, 2 action buttons
- Pixelstick S (left stick), same as above but with stick on the left side
- Pixelstick M (right stick), slightly larger size with stick on the right side, 4 action buttons

## Tools

- Drill stand with drill, or column drill machine
- Soldering iron
- **TBD**


## BoM

| Item | Quantity | Vendor(s) | Notes |
| --- | --- | --- | --- |
| Sanwa JLX2-TP-8YT lever | 1 | [SmallCab](https://smallcab.net/) | 1) |
| Ball/bat/bullet top | 1 | [SmallCab](https://smallcab.net/) | Choose type according to preference |
| Qanba Gravity KS push button, Clear Red D06 (30 mm) | 2 (S) / 4 (M) | [SmallCab](https://smallcab.net/) | 2) |
| Qanba Gravity KS push button, Clear Black E04 (24 mm) | 1 | [SmallCab](https://smallcab.net/) | |
| Hammond 1590XXBK (S) / 1590DBK (M) enclosure | 1 | [Mouser](https://mouser.com) | |
| E-Switch RR3130ABLKBLKFS rocker switch | 2 | [Mouser](https://mouser.com) | |
| [RP2040 Mini Breakout Board](https://github.com/OpenStickCommunity/Hardware/blob/main/Boards/GP2040-CE%20Official%20Boards/RP2040%20Mini%20Breakout%20Board/RP2040%20Mini%20Breakout%20Board%20-%20Passthrough/README.md) | 1 | [AdditiveArcade](https://additivearcade.com/products/rp2040-mini-breakout-board-v75e-usb-36011?variant=56231032488317) | Vertical 20-pin header |
| Mini Breakout Board Mount | 1 | [AdditiveArcade]( https://additivearcade.com/products/mini-breakout-board-mount?variant=58019940991357) | |
| 20-pin harness | 1 | [AdditiveArcade](https://additivearcade.com/products/breakout-board-cables?variant=57570094809469) | |
| M3x10 black countersunk bolts | 4 | Hardware store | For mounting of JLX2 |
| M3x8 black countersunk bolts + nuts | 2 | Hardware store | For mounting of NAUSB-W-B |
| JST PH 2.0 mm 3-pin female to bare wire, 100+ mm | 1 | Mouser | 1) |
| JST PH 2.0 mm 2-pin female to bare wire, 100+ mm | 2 | Mouser | 1) |
| JST PH 2.0 mm 2-pin male to bare wire, 100+ mm | 2 | Mouser | 1) |

### Notes

1. Other lever brands might be possible but verify mounting locations and clearance (the JLX2-TP-8YT has 4 screw holes close to the lever opening, the mounting plate is not needed and the screws are concealed by the dust cover)
2. Other brands might be possible but verify clearance especially in small enclosure (S model), the Qanba Gravity is a bit shallower than most other brands
3. Instead of this 3-pin to 2x 2-pin DIY detachable harness, you can use two pins from the 20-pin harness instead, although the fit on the rocker switch terminals is not quite as secure and the fit/clearance will be quite tight



## Assembly

**TBD**