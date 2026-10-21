# Scene 4A, the hillside at sunset: location plates

The Prodigal Son v3, 21 Oct 2026. Nothing in this set is approved.

## What to make (12 pictures, in this order)

| # | prompt | tool | attach | what |
|---|---|---|---|---|
| 01 | prompts/01_A_plate.txt | image_edit 3:2 | sc01 01_A_plate (package 01_gate_plate) | sunset redraw of the gate, from outside |
| 02 | prompts/02_A_right.txt | image_edit 3:2 | 01 | quarter turn right, downhill along the wall |
| 03 | prompts/03_A_reverse.txt | image_edit 3:2 | 01 | half turn, into the exterior grove |
| 04 | prompts/04_A_left.txt | image_edit 3:2 | 01 | quarter turn left, uphill along the wall |
| 05 | prompts/05_A_low_corner.txt | image_edit 3:2 | 01 | lens a hand's breadth up, at the uphill pier |
| 06 | prompts/06_A_macro.txt | image_edit 3:2 | 01 | rope lashing of the uphill leaf |
| 07 | prompts/07_B_plate.txt | image_edit 3:2 | sc01 07_B_plate (package 02_olive_plate) | sunset redraw from uphill of the ledge |
| 08 | prompts/08_B_right.txt | image_edit 3:2 | 07 | quarter turn right, toward the gate |
| 09 | prompts/09_B_reverse.txt | image_edit 3:2 | 07 | half turn, uphill at the near wall |
| 10 | prompts/10_B_left.txt | image_edit 3:2 | 07 | quarter turn left, down the slope |
| 11 | prompts/11_B_low_corner.txt | image_edit 3:2 | 07 | lens a hand's breadth up, at the ledge |
| 12 | prompts/12_B_macro.txt | image_edit 3:2 | 07 | worn upper lip of the limestone ledge |

## Where each picture stands

Grid from `staging/places/hillside.json`: +x toward the gate, +y downhill to the lake, origin the limestone ledge. The sun comes from 140°: sunset, low and red over the far hills.

Stand points are Sol's, in `location-plates/orbits/sc04a/FIELDS.json`. Sides and light are from `orbit_spots.py --digest` at those points.

### Gate spot A (01–06)

Stands at (33, 0), faces 180°. Open earth six metres outside the gateway, the whole gate and the hillside through it in frame. Redrawn from sc01_A. The hour changes from late afternoon to sunset. The stand matches the Scene 1 package gate camera.

| view | heading | light | digest sides |
|---|---|---|---|
| plate | 180° | ahead on the right | gate 6 m centre; wall 6 m right; loose stone 7 m right; shadow 18 m left; stones 32 m centre; ledge 33 m centre; olive 36 m centre; lake 39 m right |
| right | 90° | ahead on the left | trunk 3 m right; wall 8 m left; trunks 8 m left and right, 9 m right, 14 m right; lake 31 m centre |
| reverse | 0° | behind on the left | trunk 3 m right; trunks 8 m left and 8 m right |
| left | 270° | behind on the right | trunk 3 m left; trunk 6 m right; wall 8 m right; trunk 8 m left; trunk 10 m centre; shadow 18 m right |
| low | 175° from (27.9, −1.6) | ahead on the right | wall and gate 1 m centre; shadow 14 m left; stones 27 m centre; ledge 28 m centre; olive 31 m centre; lake 38 m right |
| macro | the uphill leaf's rope lashing | the same sun, grazing | one worn surface |

The low lens sits just outside the uphill pier, so that pier rises along the left edge while the gate itself stays at the centre.

### Olive spot B (07–12)

Stands at (−2, −10), faces 60°. Open ground uphill of the ledge, one metre downhill of the Scene 1 package olive camera at (−2, −11). Redrawn from sc01_B. The hour changes to sunset.

| view | heading | light | digest sides |
|---|---|---|---|
| plate | 60° | to the left | shadow 5 m right; stones 9 m left; ledge 10 m left; wall 11 m left; olive 11 m left; gate 30 m right; loose stone 32 m right; trunks 38 m right; lake 41 m left |
| right | 330° | behind the camera, the view lit from the front | shadow 6 m left; wall 8 m right; gate 30 m left; trunks 33–44 m left |
| reverse | 240° | to the right | wall 2 m right; rising terraces beyond it |
| left | 150° | ahead, the view backlit, 10° right of the axis | wall 3 m left; shadow 8 m right; lake 41 m right |
| low | 120° from (1.5, −1.2) | ahead, the view backlit, 20° left of the axis | stones 1 m left; ledge 2 m left; shadow 3 m right; olive 5 m left; wall 8 m left; lake 32 m right |
| macro | the worn upper lip of the ledge | the same sun, grazing | one worn surface |

The reverse digest names only the wall. The rising hillside beyond it is the uphill ground of the same place.

## The locked design

The same hillside as Scene 1.

- **The wall:** waist-high dry-stone, rough unmortared fieldstone, around the terraced gathering ground.
- **The gate:** two square fieldstone piers. The staging runs from (27, −1.6) to (27, 1.6). The prompts say a three-metre opening, the reference plate's wording. One weathered timber leaf, diagonal brace and rope lashings, hinged on the uphill pier, swung outward. The threshold is scuffed earth.
- **The ledge:** natural pale limestone bedrock at (0, 0), 2.3 by 1.4 m, knee-high, worn smooth. A torn barley round and crumbs lie on the top.
- **The olive:** ancient twisted trunk at (−2.6, 1.4), a low silver-grey crown.
- **The loose fieldstone:** on the wall top at (27, 2.6), the stone of this scene and Scene 16.
- **The ground:** stones in the dust near the ledge, dry grass, ochre earth, and the olive's long shadow across the terraces.
- **Outside the gate:** the old olive grove. **Beyond the downhill wall:** the pale lake and the grey far hills.
- **The air:** a breeze off the lake lifts fine dust from the dry terrace lips. Fallen leaves, shrivelled olives and dry twigs lie under the crowns.
- **The light:** one sunset sun. Deep shade covers a third of the frame and more.
- **Empty:** the plates are empty and still. The donkey tethered at (25, −2.8) is staged with the gathering, and these plates leave it out, as the Scene 1 plates do. Scenes 11 and 16 add the fire. This hour has the sun alone.

## Redrawn from

- **01** comes from `sc01_A_the_hillside_above_the_lake`: short-prompt file `sc01 01_A_plate`, the package gate plate `01_gate_plate`. What changes is the hour.
- **07** comes from `sc01_B_the_hillside_above_the_lake`: short-prompt file `sc01 07_B_plate`, the package olive plate `02_olive_plate`. What changes is the hour, and the camera stands one metre downhill of that plate.

## The look

Every wide view ends: "Muted sun-faded earth colours, a pale warm-grey haze, fine film grain, wide lens, deep focus. The place is empty and still."

Each macro ends: "Muted sun-faded earth colours, fine film grain."

Bible §4: one natural source, real deep shadow, a muted sun-faded earth palette, a pale warm-grey hazy sky, fine grain. Measured targets: luma 0.28–0.36; shadow at least 18%; colourfulness 24 or less; warmth R−B +0.06 to +0.14; sharpness 750 or less; grain 1.0 or more.
