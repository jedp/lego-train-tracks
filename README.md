## LEGO Train Tracks

Parametric models for Lego train tracks.

- [F3D](./lego-train-tracks.f3d) (Original)
- [STL](./lego-train-tracks.stl) (Export)

![model](./r56-body.png)

Should be fairly printer agnostic, though I've only tested on my Prusa i3 MK3S.
There are slop parameters that can be adjusted for some of the finer details.

I have only printed this with PLA filament. I don't think PETG (my normal
day-to-day material) would perform reliably for the couplings, but I haven't
tried.

Snaps together well with that ever-pleasing brick click, with both real Lego
tracks and bricks, even when using the SPEED setting on my printer. It's a
happy coincidence that all Lego measurements are multiples of 0.2mm, and a
standard printer nozzle is 0.4mm in diameter.

![print](./tracks-joined.png)

### Components

Small bits you can copy around to make larger bits.

Unit measurement is the length of the edge of a standard Lego 1x1 block.

- 2x8 sleeper
- 1x8 coupling sleeper
- 1x4 rail
- 1x3 rail
- 1x1 rail
- 1x1+ coupling rail end

Print the 1x8 coupling sleeper and verify that it snaps into your real Lego
tracks. If it doesn't, spend some time with your slicer and/or adjust the slop
parameters in the model.

Bodies jumbled around the origin so you can imagine how to copy and move them
to build tracks:

![models](./jumble-of-bodies.png)

(If you end up assembling your own, make sure when you move and rotate that
track coupling you check that the pivot point is on one of the right edges.
This is the only piece whose length is not a multiple of the standard Lego 1x1
brick.)

### Complete Models

- 8x16 straight rail segment (Lego standard: ME901-ST)
- 8x20 straight rail segment
- 8x20, 56 stud radius (Lego standard: ME901-56)

I will continue add more as I construct them.


