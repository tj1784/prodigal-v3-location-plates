# Scene 3, the threshing floor at evening: location plates

The Prodigal Son v3, 21 Oct 2026. Nothing in this package is approved.

One spot. Six pictures. The plate is redrawn from Scene 2's threshing-floor plate. Every other picture is drawn from this plate.

## What to make (6 pictures, in this order)

| # | file | tool | attach | what |
|---|---|---|---|---|
| 01 | prompts/01_A_plate.txt | image_edit 3:2 | sc02 07_B_plate | THE PLATE: the whole circle from the north, evening |
| 02 | prompts/02_A_right.txt | image_edit 3:2 | 01 | quarter turn right, west along the terrace |
| 03 | prompts/03_A_reverse.txt | image_edit 3:2 | 01 | half turn, north into the yard |
| 04 | prompts/04_A_left.txt | image_edit 3:2 | 01 | quarter turn left, east toward the road |
| 05 | prompts/05_A_low.txt | image_edit 3:2 | 01 | same spot, lens a hand's breadth above the ground |
| 06 | prompts/06_A_macro.txt | image_edit 3:2 | 01 | the winnowing fork on the north-east rim |

## Where the picture stands

Grid of `staging/sc03/SC03_STAGING.json`: +x east, +y north, metres, origin the lamp niche in the north gatepost. The circle's centre is (-14, -26.5). The sun comes from 195°: evening, low in the west-south-west. The wind comes from the west.

The scene's working camera sits on the circle at (-13.77, -25.37), facing 263°. That point is too close for a plate of the whole place. The plate stands 6.6 m from it, on open terrace north of the rim and south of the yard wall: **(-11.5, -19.2), facing 263°** (just west of south). The circle's centre is 8 m ahead.

Digest command, plate and the three turns:

`D:/Dev/Tools/Python312/python.exe -I location-plates/orbit_spots.py --digest sc03_A_the_threshing_floor_at_evening -11.5 -19.2 263`

- **Plate and low (263°):** sheaves 2 m on the LEFT, fork and floor track 5 m on the LEFT, husks 5 m on the LEFT, heap 6 m at centre, circle 8 m at centre, footpath 11 m on the LEFT, terrace edge 14 m at centre, far-field path 16 m on the RIGHT. Sun ahead on the RIGHT.
- **Right (173°, just north of west):** yard 5 m on the RIGHT, terrace edge 20 m on the LEFT, ovens 22 m on the RIGHT, eaves 25 m on the RIGHT, farmhouse 27 m on the RIGHT, doorway 28 m on the RIGHT, yard wall 31 m on the RIGHT, far-field path 33 m on the LEFT, trees 42 m at centre and 49 m on the RIGHT. Sun ahead, the view backlit.
- **Reverse (83°, just east of north):** yard 4 m at centre, cistern 11 m on the RIGHT, trough 18 m on the RIGHT, the one gate 19 m on the RIGHT, floor track 20 m on the RIGHT, road east 21 m on the RIGHT, fold 23 m at centre, fold gate 23 m on the LEFT, yard wall 23 m on the RIGHT, bench 24 m on the RIGHT, calf pen 25 m at centre, hill track 26 m on the RIGHT, ox byre 28 m at centre, old fig 33 m on the RIGHT. Sun behind on the LEFT.
- **Left (353°, just north of east):** yard 5 m on the LEFT, floor track 5 m on the RIGHT, husks 7 m on the RIGHT, footpath 13 m on the RIGHT, terrace edge 16 m on the RIGHT, road east 24 m on the LEFT, hill track 26 m on the LEFT. Sun behind the camera, the view lit from the front.

The low view keeps this stand point and facing, and drops the lens to a hand's breadth above the ground. Its sides are the plate's.

The macro stands a hand's breadth east of the fork, at (-10.15, -23.75), facing 220° (west-south-west) along the shaft. Digest:

`D:/Dev/Tools/Python312/python.exe -I location-plates/orbit_spots.py --digest sc03_A_the_threshing_floor_at_evening -10.15 -23.75 220`

Husks 1 m on the LEFT, heap 3 m at centre, circle 5 m at centre, terrace edge 10 m on the LEFT. Sun ahead, the close view backlit.

## The locked design

The floor is Scene 2's: a nine-metre circle of hard worked earth, edged with low set limestone, on the terrace's south side. The yard wall is about 1.7 m of rough fieldstone. The farmhouse is low and earth-roofed. The one gate has two fieldstone posts, a timber lintel, and a south-hinged olive-wood leaf swung open into the yard. The fold is straw-floored, with a barred gate. The cistern, trough, ovens, calf pen, ox byre and old fig stay where the farm map puts them.

At this hour the circle holds the evening's work: a low heap of threshed barley, husks drifted east and downhill on the wind from the west, a wooden winnowing fork on the north-east rim, and barley sheaves still to thresh. Other threshing floors lie about 1.1 km south, across the valley. The screenplay's gold on the chaff is the low sun on pale husks, kept inside the muted earth palette.

The place is empty. The dawn bread basket and the flail belong to Scene 2's hour, and this evening's staging leaves them out.

## Redrawn from

`sc03_A_the_threshing_floor_at_evening` is redrawn from `sc02_B_the_threshing_floor_before_dawn`, file `sc02/prompts/07_B_plate.txt`. Both the hour and the stand point change: before dawn on the south-east ground, facing north-west, becomes evening on the north ground, facing just west of south. The circle, the stones and the farm stay the same design.
