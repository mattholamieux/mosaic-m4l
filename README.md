# mosaic-m4l
a melodic max for live sequencer that converts rgb values to midi

- an image is uploaded an pixelated to 16x8 resolution
- each pixel can be "played" via connected monome grid by pressing on the corresponding pad
- red values are mapped to pitch, green values mapped to velocity, and blue values mapped to sustain length
- each layer (r, g, and b) can be independently transformed with [jit.rota](https://docs.cycling74.com/max8/refpages/jit.rota)
- three different midi playheads can be sequenced, as can layer transformations
