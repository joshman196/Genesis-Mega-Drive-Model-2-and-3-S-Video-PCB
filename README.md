# Sega Genesis/Mega Drive Model 2 & 3 S-Video Mod PCB

Simple PCB that carries Luma, Chroma, and Ground lines with their respective components. Available as a standard through hole version or a nano/super nano surface-mount version. If unsure, just go with the Standard PCB. This should work on consoles that contain the following video encoders: Sony CXA1645, Fujitsu MB3514, and Sony CXA2075. This will **NOT** work with Model 2 consoles that contain a Samsung KA2195D video encoder, this is due to that encoder not carrying the necessary lines to drive S-Video. Only the CXA1645 in a VA4 Model 2 has been tested with these PCBs so far. If you have a model 1 Genesis/Mega Drive with a CXA1145 encoder, use the [Model 1 S-Video PCB](https://github.com/joshman196/Simple-Genesis-Model-1-S-Video-Private/tree/main).

**It is recommended to use 28 AWG wire for this install.**

![261792600-3bed8a33-aab6-450d-a3d2-a9f45ef2fed9](https://i.imgur.com/lE0joEZ.png)

## Parts Needed

**Only order the parts you need for the board type you are building for.**

### "Standard" PCB

- 2x 220µF 6.3v Capacitors
- 2x 75 Ohm Resistors

You can buy these components in a kit from [console5.com](https://console5.com/store/cxa1645-s-video-mod-kit.html). Make sure to also pick up an S-Video jack as well, and conveniently enough console5 also offers these in either [socket](https://console5.com/store/mini-din-in-line-socket-4-pin-female-black-pin-type-s-video-s-vhs.html) or [panel mount](https://console5.com/store/s-video-jacks-panel-mount-black-plastic-housing-solder-type.html) configurations. The version you get depends on whether you want to drill the outer shell of your console (flush mount) or not (socket).

### "Nano" and "Super Nano" PCBs

- 2x 220µF 6.3v 1411 (3528 Metric) Tantalum Capacitors (Tantalum Polymers recommended) - [Digikey Part](https://www.digikey.com/en/products/detail/kyocera-avx/TCJB227M006R0070/2615437)
- 2x 75 Ohm 0805 (2012 Metric) Resistors - [Digikey Part](https://www.digikey.com/en/products/detail/yageo/RC0805FR-0775RL/728132)

Make sure to also pick up an S-Video jack as well. You can get these from console5.com in either [socket](https://console5.com/store/mini-din-in-line-socket-4-pin-female-black-pin-type-s-video-s-vhs.html) or [panel mount](https://console5.com/store/s-video-jacks-panel-mount-black-plastic-housing-solder-type.html) configurations. The version you get depends on whether you want to drill the outer shell of your console (flush mount) or not (socket).

## Installation Steps

1. Add the capacitors/resistors to the PCB and find a suitable place inside your console to put the assembled board at. You may want to put kapton tape on the area of the main board where you plan on setting the PCB at. You may also choose to set it somewhere off of the main board.
2. Connect a wire from pin 15 of the CXA1645/MB3514 to "C In" on the S-Video PCB.
3. Connect a wire from pin 16 of the CXA1645/MB3514 to "Y In" on the S-Video PCB.
4. Connect a wire from pin 1 of the CXA1645/MB3514 to "GND" on the S-Video PCB.
5. If you have heatshrink tubing that you want to use, you should prepare them on the next set of wires below before soldering the other ends of those wires. **Do not apply the heat to the tubing until after testing your install!**
6. Connect a wire from "C Out" on the S-Video PCB to the Chroma pin on the back of the S-Video jack.
7. Connect a wire from "Y Out" on the S-Video PCB to the Luma/Y pin on the back of the S-Video jack.
8. Connect a wire from "CGND" on the S-Video PCB to the Chroma-Ground pin on the back of the S-Video jack.
9. Connect a wire from "YGND" on the S-Video PCB to the Luma/Y-Ground pin on the back of the S-Video jack.
10. With the wiring all done, stick some more kapton tape from the sides over the PCB to stick it down onto the main board itself, setting the PCB on top of the other layer of kapton tape you put earlier. DO NOT SET THE PCB DOWN ON THE BARE MAIN BOARD WITHOUT SOME KIND OF INSULATION UNDER THE S-VIDEO PCB TO PREVENT POTENTIAL SHORTS. Electrical tape may work but that tends to leave a nasty residue, so I wouldn't recommend it.
11. You're done!

## Board Types

### "Standard" Through-Hole PCB (~33.274mm x ~16.891mm)

![261792600-3bed8a33-aab6-450d-a3d2-a9f45ef2fed9](https://i.imgur.com/lE0joEZ.png)

### "Nano" Surface-Mount PCB (~16.002mm x ~8.179mm)

![261790786-92c2d6f9-c247-4f60-914e-0ed08982a316](https://i.imgur.com/zUiHxmx.png)

### "Super Nano" Surface-Mount PCB (~9.423mm x ~7.468mm)

![261792600-3bed8a33-aab6-450d-a3d2-a9f45ef2fed9](https://i.imgur.com/lO1IA0U.png)
