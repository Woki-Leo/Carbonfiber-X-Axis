# Lightweight X Axis Mod for the Voron 2.4

**CURRENTLY UNDER DEVELOPMENT AND TESTING**

![grafik](Resources/Axis%20image.png)

## What the goal is:

- Removing lots of unnecessary weight to make the Printer go faster with better Quality
  - for a V2.4 350mm it drops the gantry weight from ~1350g to ~950g
    - 70g saved by removing the x drag chain
    - 150g saved by using the carbon tube
    - the rest is saved through the pinmod and other improvements
- Look good


<br/>

## What's different:

- XY joints changes:
  - derived from the [pinmod](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/hartk1213/Voron2.4_Pins_Mod)
  - room for MGN12 (heavily inspired by [arkeet](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/arkeet/mgn12))
  - adjustment slots for the tube
- Chain delete --> umbilical receivers required

<br/>

## Required hardware:

- 20x20 1mm wall thickness carbon fiber tube 
  - you can use the original Alu tube as well but it will be very heavy
- 4PCs 5x40mm Pins (Use Carbon fiber rod)
- 4PCs M5x40 SHCS
- 12PCs M5 Nut
- 6PCs M5x10 BHCS
- 2PCs M5x30 BHCS

Using Aluminium Hardware for M5 is recommended. Watch out for the right alloy and heat treat! 7075 T6 is strongly recommended!

For Rail mounting:
M3x8 SHCS + Nuts for the amount of screws you want (4-8 Recommended)

<br/>

## Required mods:

- arkeet's [mgn12](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/arkeet/mgn12) carriage or  jlas1' mgn12 [klicky](https://github.com/jlas1/Klicky-Probe/tree/main/Usermods/bluedragonx) carriage 
- some sort of y endstop on the gantry (click [here](https://github.com/hartk1213/MISC/tree/main/Voron%20Mods/Voron%202/2.4/Voron2.4_Y_Endstop_Relocation) for hartk's AB endstop)
- until a clockwork umbilical holder is available the [gallileo](https://github.com/JaredC01/Galileo) clockwork is also needed


the rest is stock

<br/>

## Printing:

for now you will have to orient the parts yourself! 
they are all printable without supports.

<br/>

## How to install it:

Coming soon!

<br/>

## Things to come

- [ ] MGN9 Support
- [ ] 20x20 1,5mm wall Carbon tube support
- [ ] Adjustability between XY joints and Carbon extrusion
- [ ] Rework M5 Nut holder inside the tube
- [ ] Tool to hold the M3 linear Rail nuts
- [ ] Umbilical Holder for Clockwork and Galileo (Chain Delete)
- [ ] In Depth resonance testing and comparison of different Setups
