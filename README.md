# Lightweight X Axis Mod for the Voron 2.4 and Trident

**ALMOST DONE WITH DEVELOPMENT AND TESTING!**

![grafik](Resources/Axis%20image.png)

## What the goal is:

**Caution: the carbon tube will start soften at and above 60c chamber temperature!!**

- Removing lots of unnecessary weight to make the Printer go faster with better Quality
  - for a V2.4 350mm it drops the gantry weight from ~1350g to ~950g
    - 70g saved by removing the x drag chain
    - 150g saved by using the carbon tube
    - the rest is saved through the pinmod and other improvements
- Look good
- be usable for both MGN9 and MGN12


<br/>

## What's different:

- XY joints changes:
  - derived from the [pinmod](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/hartk1213/Voron2.4_Pins_Mod)
  - room for MGN12 (heavily inspired by [arkeet](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/arkeet/mgn12))
  - adjustment slots for the tube
  - removed unnecessary cutouts unter the y carriages (actually saves weight)
    - cut the corners at 45° here as well. Removes material that does nothing. 
- Chain delete --> umbilical receivers required

<br/>

## Required hardware:

- 20x20 1mm wall thickness carbon fiber tube 
  - you can use the original Alu tube as well but it will be very heavy
  - [you can find a fabricated tube here](https://www.aliexpress.com/item/1005004037790448.html?spm=a2g0o.productlist.0.0.4fa74aefiTnfIH&algo_pvid=06e6d075-0f3a-4506-aa12-01960cc75d43&algo_exp_id=06e6d075-0f3a-4506-aa12-01960cc75d43-0&pdp_ext_f=%7B%22sku_id%22%3A%2212000027826580135%22%7D&pdp_npi=2%40dis%21EUR%21%2139.79%21%21%21%21%21%402100bdca16533793818795594efcb7%2112000027826580135%21sea)
- 4PCs 5x40mm Pins (Use Carbon fiber rod)
- 4PCs M5x40 SHCS
- 8PCs M5 Nut
- 4PCs M5x10 BHCS
- 2PCs M5x30 BHCS

Using aluminium hardware for M5 is recommended. Watch out for the right alloy and heat treat! 7075 T6 is strongly recommended!

For rail mounting:
M3x8 SHCS + Nuts for the amount of screws you want (4-8 Recommended)

<br/>

## Required mods:

- MGN12: arkeet's [MGN12](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/arkeet/mgn12) carriage or  jlas1' mgn12 [klicky](https://github.com/jlas1/Klicky-Probe/tree/main/Usermods/bluedragonx) carriage 
- MGN9: Ellis' [MGN9H](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/Ellis/Single_MGN9H_Carriage) mod
- some sort of y endstop on the gantry (click [here](https://github.com/hartk1213/MISC/tree/main/Voron%20Mods/Voron%202/2.4/Voron2.4_Y_Endstop_Relocation) for hartk's AB endstop)
- until a clockwork umbilical holder is available the [gallileo](https://github.com/JaredC01/Galileo) clockwork is also needed


the rest is stock

<br/>

## Printing:

Please make sure you choose the right version for you printer!
Normally you should need the R2 Version with a new build. 
They are all printable without supports.
Settings: 
Standard voron settings.
or: drop perimeters and/or infill down to save weight 
3 perimeters and 20% infill tested

<br/>

## How to install it:

**Please be carefull with cf dust! Wear a respirator and safety glasses!**

1. Cut the carbon tube to your printers stock length (330mm for 250mm version for example)
2. (Drillpress recommended) Drill holes from the front through the tube centered using the rail as template. Use the choose the spacing to you liking. Center using the printed tool and measuring on either end. 3mm drill. Drill all the way through the tube. ![grafik](Resources/drill%20front.jpg)
3. Remove rail. Flip over and Drill from the back. Drill size has to be bigger than you M3 socket (12.5mm in my case). Take is slow to keep the blockout in the tube down.![grafik](Resources/drill%20back.jpg)
4. Drill holes for the M5 Screws with 5.5mm drill
5. Debur
6. Assemble!

<br/>

## Things to come

- [x] MGN9 support
- [x] Adjustability between XY joints and carbon extrusion
- [x] Rework M5 nut holder inside the tube
- [ ] Umbilical holder for Clockwork and Galileo (Chain Delete)
- [ ] Alignment tool for drilling 5.5mm holes
- [ ] Drag chain mount on the carbon tube (for now you can glue it on)
- [ ] ~~20x20 1,5mm wall Carbon tube support~~ no benefit
- [ ] ~~Nut installing tool~~ not need since holes from the back make it so much simpler to install the M3 nuts for the rail

<br/>

##Contact

Feel free to reach out with any questions/suggestions you have!
Discord: Woki | Leo #8734
