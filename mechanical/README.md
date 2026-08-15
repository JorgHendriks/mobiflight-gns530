# Enclosure and controls

## Hardware

| Part | Quantity |
|---|---:|
| M2 x 8 mm screw | 5 |
| M2 x 4 mm screw | 4 |
| M2 x 9 mm, 3 mm body standoff | 5 |
| M2 x 4 mm, 3 mm body standoff | 4 |
| M2 x 11 mm, 3 mm body standoff | 4 |

## Printed parts

| File | Quantity | Material |
|---|---:|---|
| [`GNS530_case.3mf`](GNS530_case.3mf) | 1 | Matte-black PLA |
| [`GNS530_back_cover.3mf`](GNS530_back_cover.3mf) | 1 | Matte-black PLA |
| [`GNS530_faceplate.3mf`](GNS530_faceplate.3mf) | 1 | White PLA, painted matte black |
| [`GNS530_button.3mf`](GNS530_button.3mf) | 12 plus spares | White PLA, painted matte black |
| [`GNS530_button_rng.3mf`](GNS530_button_rng.3mf) | 1 plus a spare | White PLA, painted matte black |
| [`GNS530_knob_inner.3mf`](GNS530_knob_inner.3mf) | 2 | Black PLA |
| [`GNS530_knob_outer.3mf`](GNS530_knob_outer.3mf) | 2 | White PLA, painted matte black |
| [`GNS530_knob_volume.3mf`](GNS530_knob_volume.3mf) | 2 | White PLA, painted matte black |

The complete editable model is [`GNS530.FCStd`](GNS530.FCStd). Editable knob
sources are [`GNS530_encoder_dual.FCStd`](GNS530_encoder_dual.FCStd) and
[`GNS530_encoder_volume.FCStd`](GNS530_encoder_volume.FCStd).

## Printing

Print several spare knobs and buttons. They require little filament or paint, and achieving correct laser alignment may take more than one attempt.
Print inner knobs with their top surfaces facing down on a smooth PEI plate.

| Button setting | Value |
|---|---|
| Wall generator | Arachne |
| Initial-layer flow ratio | 1.06 |
| Bottom-surface pattern | Hilbert curve |
| Elephant-foot compensation | 0.08 mm |

Print the buttons and the faceplate with its visible face upward and enable ironing at 23% flow.

## Painting and laser engraving

Apply thin coats of matte-black paint to the white PLA parts. Let the paint cure fully before engraving.

The artwork is [`GNS530_laser.svg`](GNS530_laser.svg).

Reference settings for a Mecpow X3 Pro 10 W diode laser:

| Operation | Power | Speed |
|---|---:|---:|
| Faceplate and button raster | 15% | 2800 mm/min |
| Positioning outline | 50% | 2000 mm/min |

Run separate sessions for the faceplate, knobs, standard buttons, and range rocker.
Focus on the part surface, remove the part, engrave its positioning outline onto a sacrificial surface, then replace the part inside the outline and run the raster engraving.

