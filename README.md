# ~MHz ERCF Filament Rack/Buffer Tube Array

Being inspired by having drama with the ERCP Filament Buffer assemblies, coupled with watching a [RMU video on Chris's Basement channel](https://www.youtube.com/watch?v=tYeIUff-35k), I decided to undertake the endeavor of fabricobbling a KISS buffer solution that didn't rely on multiple loops of filament.  With that, I present the following to y'all for your consideration of how one gent went about tackling same.

![~MHz ERCF Filament Rack/Buffer Tube Assy](https://github.com/TodWulff/-MHz-ERCF-Filament-Rack-Buffer-Tube-Assy/blob/main/20220315_233601.jpg)

The 'buffer tubes' are [Betaduct 75mm*25mm solid wall raceways](https://github.com/TodWulff/-MHz-ERCF-Filament-Rack-Buffer-Tube-Assy/blob/main/PN_09240000Y.pdf).  I got a set of [8ea 2m long pieces for roughly $120 from Newark](https://www.newark.com/betaduct/09240000y/solid-wall-duct-pvc-blk-75x25mm/dp/24AJ3284?ICID=I-RP-STM7REC-1).  The PVC flavor is what I bought.  The Noryl flavor is roughly [5x more expensive](https://www.newark.com/betaduct/23473000n/solid-wall-duct-noryl-blk-75x25mm/dp/24AJ3781?ICID=I-RP-STM7REC-1) - be careful.  The buffer tubes pictured above are cut to 36" in length.  
- [Engineering Drawing](https://github.com/TodWulff/-MHz-ERCF-Filament-Rack-Buffer-Tube-Assy/blob/main/betaduct_pvc_solid_wall_75_x_25_drawing.pdf)  
- [Step File from Cablecraft (OEM}](https://github.com/TodWulff/-MHz-ERCF-Filament-Rack-Buffer-Tube-Assy/blob/main/03-1709.STEP)

I cobbled the [endcap assy's together in PrusaSlicer](https://github.com/TodWulff/-MHz-ERCF-Filament-Rack-Buffer-Tube-Assy/blob/main/MHzBufferTubeEndCapAssy.3mf) (/me != 3D CAD skills).

![Endcap Platter](https://i.imgur.com/0STDYvz.png)

![Endcap Sliced](https://i.imgur.com/st7ro1q.png)

![~MHz Filament Buffer Tube Endcap Assy](https://github.com/TodWulff/-MHz-ERCF-Filament-Rack-Buffer-Tube-Assy/blob/main/bq9zRUO.png)

Each assembled Endcap needs 2ea [PC4-M10](https://www.amazon.com/ExcelFu-Straight-Pneumatic-Connector-Long-Distance/dp/B07P2XRCC1), 1ea [608RS Bearing](https://www.amazon.com/gp/product/B073ST742Z), 1ea M3 Heat insert, 5ea M3x10 screws (4 to attach the hanger halves to the lid, one for the bearing axis).

The bowden comb is an extra that I added to the model - ensures that one has more than enough if multiple end caps are printed.

For the frame, I ordered a set of [10ea 1000mm lengths of 2020](https://www.amazon.com/Montex-Aluminum-Extrusion-European-Standard/dp/B093FDT2QN), in addition to a couple additional pieces I had stock on - used for the bottom anti-tip supports - printed feet/end caps (sharp edges will cut a toe or three off).  The 4 up rights are 1000mm, the lateral pieces are 650-ish mm.

I used a ton of [roll-in M5 t-nuts](https://www.amazon.com/gp/product/B07VHNGBWJ) and 2 sets of these to tie it all together: https://smile.amazon.com/KOOTANS-Bracket-Connection-Aluminum-Profile/dp/B07RPT9X8X , along with a set of these for the top of the verticals: https://smile.amazon.com/Befenybay-Connector-Aluminum-Extrusion-2020s-Black/dp/B092YS1SX3.

The 4 members holding the buffer tubes are just the left overs from lobbing the lateral pieces down to 650mm, trimmed to length to allow ample spacing between the buffers - I may actually squeeze the buffer wings tighter and trim the metal down more - tbd - this was a **finalize-the-design-while-building** evolution.

At the top of each buffer tube, I used this type of bit to plow a hole through on each side (used an extra printed cap as a guide) and then dyked the top of the material away to allow the cap to be slid on/off without having to unscrew anything - makes servicing a breeze.

![Buffer Tube - Endcap Interface](https://i.imgur.com/PGYzGqM.png)

M5x8 with roll-ins round it out and hold the tubes to the wings.  The bowden tube I used is here:  https://smile.amazon.com/MUYI-Chemical-Electrical-Medical-Equipment/dp/B019PZ5MY4.  It's 2mm ID but my orbiter v1.5 has plenty of pulling power, so no issues for me, with #4/#5 tophats driven by a NMEA 17 gear stepper (Y axis servo from my E3v2 in the printer graveyard).

Note:  Expect to have to do some post processing - Might want to make the bowden comb's cutouts (the negative volume modifiers) a bit larger - i.e. increase diameter by 0.2mm.  I had to go back and redrill all of them so the bowden tubes would slide in.

![Endcap Printing takes a while...](https://i.imgur.com/LFh2irl.png)
