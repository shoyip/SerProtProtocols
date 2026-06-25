# Microfabrication of PDMS chips

This protocol takes two to three days.

## Molding of chips

Time: 1h30 / 2h

### Materials

- [Momentive RTV615](https://www.neyco.fr/nos-produits/silicones-2/microfluidique-pdms/rtv615/rtv-615) (PDMS base "A" and curing agent "B")
- Disposable tray
- Spatula
- Weight scale
- Four Falcon 50mL tubes
- Centrifuge
- Vacuum machine
- Epoxy molds for the chips in Petri dishes
- Aluminium foil

### Procedure

1. Pour liquids "A" (135g) and "B" (15g) in a disposable
   tray on the weight scale and mix with the aid of a
   spatula for 1min. Pour the mix equally in four Falcon
   50mL tubes.
2. Centrifuge the Falcon 50mL tubes at 4000rpm for 15min.
3. Lay the molds on two perpendicular aluminium foils as
   wide as the molds as to form a cross. Fold the sheets on
   the edges to form a rim of half a centimeter.
4. Pour the content of each Falcon tube in each mold.
5. Put the molds in their Petri dishes and leave them in the
   vacuum chamber for approx. 1h.
6. Bake them in the oven overnight.

!!! warning
    If the room is too warm, the PDMS might polymerize
    during the centrifuging or the vacuum.

!!! tip
    If there are bubbles before baking, use P10 tips in
    order to pop them.

## Cutting, hole punching and plasma bonding

Time: 1h30 / 2h

### Materials

- PDMS chips
- Cutter
- Hole punching pens (0.75mm [green pen](https://www.fishersci.com/shop/products/sampling-tool-0-75mm/NC1310091) and 0.50mm [blue pen](https://www.fishersci.com/shop/products/sampling-tool-0-5mm/NC1310089))
- Cutting mat
- 50mm x 75mm pre-cleaned Millipore [microscope glass
  slide](https://www.ugap.fr/laboratoire-1/consommables-scientifiques-gauss-32634/microbiologie-analyses-mesures-36275/lames-de-microscopie-36402/lame-de-microscope-x-72-p2661264)
- Isopropanol, 70% ethanol, MilliQ water

### Procedure

1. Take the molds out of the oven. Remove the aluminium
   foil. Cut the chips out of the mold and gently lift the
   edges. If the chip is sticking to the mold, use
   isopropanol to ease the removal.

!!! warning
    If using wafer chips, be extremely careful at this step.
    Wafer chips are extremely delicate and easily break.
    Avoid putting shear stress on the PDMS while tearing the
    aluminium foil and while removing the PDMS.

2. Under the hood use the green (0.75mm, electrode holes)
   and blue (0.50mm, fluid holes) pens in order to punch
   holes. On the encapsulation chip there are only fluid
   holes. On the sorting chip the central row of holes are
   electrode holes, and the rest is for fluids. Holes should
   be punched vertically on a cutting mat.
3. Wash glass slides and the marked side of the chips using
   in the order isopropanol, ethanol and water, then dry the
   surface using compressed air. Deposit at most two glass
   slides in the plasma machine, then lay the PDMS chips on
   top with the marked side on top. Close the door of the
   plasma machine and turn the arrow shaped valve to the
   left.
4. Turn on the plasma machine by setting the switch to ON.
   Lift the red lever of the oxygen tank in order to open
   it. Turn the vacuum machine on and wait until the
   pressure drops below 1mbar. Then open the round valve on
   the plasma machine in order to let oxygen into the
   chamber for a couple of seconds. Wait until the pressure
   drops below 1mbar. Repeat 3/4 times.

!!! warning
    It is crucial to turn the plasma machine a bit before
    you actually use it, otherwise you might get uncomplete
    or unsuccessful bondings.

!!! tip
    If the vacuum machine is too slow, try wiping the seal
    of the chamber with a damp cloth.

5. Turn the dial on the plasma machine from OFF to HIGH.
   Turn off the lights in the room: you should see a purple
   / white glow in the chamber. Wait 45sec before turning
   the dial back to OFF and turn the switch to OFF as well.
   Put the red lever of the oxygen tank down. Turn the
   vacuum machine off. Turn the arrow shaped valve to the
   right in order to let the air in.

!!! warning
    A plasma cycle should not last more than 1min, otherwise
    the surface activation might not work at all. Keep it
    between 30sec and 1min.

6. Take the glass slides and chips out of the oven and, once
   at a time, flip both of them and let the marked side of
   the chip stick to the glass slide by gently pushing.
   Pushing too hard will result in blocked channels.

## Silane waterproofing and soldering

### Materials

- PDMS chips
- Tweezers
- [Sigmacote](https://www.ugap.fr/laboratoire-1/reactifs-gauss-129625/anatomo-cytopathologie-immunohistologie-129661/autres-reactifs-129665/sigmacoter-siliconizing-reagent-for-25-ml-p3751707) siliconizing reagent
- 1mL syringe
- Tubing
- [Indium solder wire](https://www.conro.com/solders-fluxes-and-preforms/solid-solder-wire/Indium-Solder-Wire-Indalloy-19-51In32-5Bi16-5Sn-Dia-0-020-Reel/)
- Hot plate
- Voltmeter
- Scotch tape

### Procedure

1. Under the hood, insert the tubing in the needle with the
   aid of a tweezer. Draw a small amount of siliconizing
   reagent using the syringe, then insert the other side of
   the tubing in the fluid holes and fill them with the
   liquid until they come out from another hole. At this
   point, aspirate back the liquid. Repeat for every hole of
   the chip.
2. Turn on the hot plate at 75°C. Leave the chips for 5-10
   minutes on top of the plate. Then insert the solder wire
   into the electrode hole with the aid of a tweezer: as
   soon as it will reach the glass slide it will start to
   melt. Check that the melted metal arrived at the second
   electrode, and repeat for each other electrode hole. At
   the end, install the electrodes by putting them in the
   holes.

!!! warning
    The electrodes should be installed as soon as the
    soldering is done. Installing electrodes when the
    soldered parts are cold might lead to a non-functional
    electrical circuit.

3. Check that the electrodes are working correctly. After a
   visual inspection, you can use the voltmeter by turning
   its dial to the diode symbol. Two by two, touch one
   electrode with one probe of the voltmeter and the other
   with another probe. The voltemeter beeps if the soldered
   circuit is connected.
4. Tape the circuits that have been tested and are ready to use.
