# Scene 6A, the village gate: short location prompts

The Prodigal Son v3, 21 October AD 2026. Nothing in this package is approved.

## What to make (6 pictures, in this order)

| # | prompt | tool | attach | what |
|---|---|---|---|---|
| 01 | prompts/01_A_plate.txt | image_gen 3:2 | nothing | The stone arch from the open square, porch, bench and cloth in frame |
| 02 | prompts/02_A_right.txt | image_edit 3:2 | 01 | Quarter right: old olive centre, village wall left, slope right |
| 03 | prompts/03_A_reverse.txt | image_edit 3:2 | 01 | Half turn: road centre, hill path left, sunlit slope beyond |
| 04 | prompts/04_A_left.txt | image_edit 3:2 | 01 | Quarter left: fig centre, road and slope left, houses and donkey right |
| 05 | prompts/05_A_low_corner.txt | image_edit 3:2 | 01 | Lens a hand's breadth above the ground, looking in through the arch |
| 06 | prompts/06_A_macro.txt | image_edit 3:2 | 01 | Worn limestone of the southwest pier, one surface filling the frame |

01 is drawn from text. 02–06 are drawn from 01, so the arch, walls, houses, cloth, bench and morning light stay one design. Use each prompt word for word. Every picture is 3:2.

## Where the picture stands

One spot: `sc06a_A_the_village_gate`, place `village_gate:ext`, morning, drawn from text. `orbits/sc06a/FIELDS.json` is absent, so the stand was chosen here.

The local grid is +x east, +y north, metres, origin at the centre of the arch's outer face. The gate faces northwest, 135°, up the hill path. The sun comes from 330°, east-southeast, about 18° up. The working camera S02 stands at (−0.11, 0.39) facing 289°, inside the opening, where the digest puts the arch at 0 m. The exterior rule wants open ground with the whole gate in frame, so the plate stands at the map's own square, anchor `gate_square` (−4.24, 4.24), exactly 6 m from the arch, facing 315° southeast into the gate. That point is about 5.6 m from S02.

Digest of that stand (`orbit_spots.py --digest sc06a_A_the_village_gate -4.24 4.24 315`):

| view | facing | what the digest puts on each side | light |
|---|---|---|---|
| 01 plate | 315° southeast | Arch 6 m centre; shade 6 m centre; cloth 7 m centre; houses 7 m left and right; village wall 8 m right; elders' bench 9 m right; door 9 m centre; further houses 13–15 m | Ahead on the left, the view backlit (sun 15° left of the axis) |
| 02 right | 225° southwest | Shade 6 m centre; wall 9 m left; houses 9 m and 12 m left; slope 10 m right; old olive 10 m centre; village houses 18 m left; a tree 24 m right | Sun to the left |
| 03 reverse | 135° northwest | Shade 3 m right; road east 5 m centre; hill path 6 m left; slope 8 m centre; trees 24 m left, 25 m centre, 45 m right, then nearer the shoulder | Behind the camera, a little to the right; the view lit from the front |
| 04 left | 45° northeast | Shade 2 m left; road 6 m left; slope 10 m left; fig 12 m centre; houses 10 m, 12 m and 18 m right | Sun to the right |
| 05 low corner | 315° from (−1.06, 1.06), a metre outside the stone | Arch 1 m centre; shade 2 m right; cloth 2 m right; houses 4 m left and right; bench 5 m right; door 5 m centre | Ahead on the left, the view backlit |
| 06 macro | 315° from (−2.72, −2.08), under half a metre from the southwest pier | The limestone fills the frame; the arch reads at 0 m, the sun ahead | Ahead, backlit, raking the arris |

Three objects sit in the staging and share the same bearing rule, and the digest's printed list leaves them out: the second porch slab has no label (9 m, just left of the door); the coal pot is an unlabeled fire, so the digest prints the sun and keeps the flame line back (8 m, near centre); the donkey is the tethered animal of this hour (7 m on the left in the plate, on the right in the left turn). The low view's field leaves the donkey outside it.

## The locked design

- **The arch.** One broad limestone arch, about seven metres across and four and a half metres high, between piers under a metre thick. The village wall is about two and a half metres high and a metre thick, with a flat top, running southwest and northeast from the piers. Flat-roofed houses of stone and mud brick stand behind it. The porch paving runs about three metres back under the arch.
- **The porch.** The elders' bench is a worn slab 2.05 m by 0.5 m at (0.58, −3.31). A matching slab sits the other side of the timber door. The door, at (2.33, −2.33), stands open, its leaf swung onto the village street. On the paving, a faded cloth holds a bronze balance, a pouch of stone weights and a low wooden stool. A small clay pot of banked coals sits beside them. The sun is the only light of the picture; the coals stay banked under ash.
- **Outside.** Trodden earth. An old olive to the southwest, a fig to the northeast. A donkey stands tethered at a ring in the northeast wall. The hill path, about a metre and a half wide, climbs northwest toward the shoulder; Eliab's farm lies about 470 m beyond that shoulder, outside these frames. The road east, three metres wide, runs toward Jericho.
- **The hour.** Morning. The wall and the arch throw their shade across the square, about seven metres out, and the slope beyond that shade stands in the sun. Dust off the road hangs in the low light, and a breath of wind lifts the cloth. The place is empty of people. The donkey is the animal this hour keeps here.
- **Later.** Scene 13 returns to this gate. Its plate, when it is written, redraws from 01. This package attaches nothing from another scene.

## The look

Bible §4 and design note §2c–§2d: one low morning sun, real deep shadow over a third of the frame, a muted sun-faded earth palette, a pale warm-grey haze, fine grain, a wide lens and deep focus. The macro keeps the earth colours and the grain, and fills the frame with one worn surface.
