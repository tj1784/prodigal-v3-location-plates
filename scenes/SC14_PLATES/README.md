# Scene 14, the feast: short location prompts

The Prodigal Son v3, 21 October AD 2026. Words only. Nothing in this set is owner-approved.

## What to make (6 pictures, in this order)

| # | prompt | tool | attach | what |
|---|---|---|---|---|
| 01 | prompts/01_A_plate.txt | image_edit 3:2 | sc02 01_A_plate, spot sc02_A_the_house_before_dawn | The same room at night, facing the hearth |
| 02 | prompts/02_A_right.txt | image_edit 3:2 | 01, this spot's plate | Quarter right, east through the doorway |
| 03 | prompts/03_A_reverse.txt | image_edit 3:2 | 01, this spot's plate | Half turn, south to the sleeping bench |
| 04 | prompts/04_A_left.txt | image_edit 3:2 | 01, this spot's plate | Quarter left, west to the jars and mill |
| 05 | prompts/05_A_low_corner.txt | image_edit 3:2 | 01, this spot's plate | Ground level at the south-west corner |
| 06 | prompts/06_A_macro.txt | image_edit 3:2 | 01, this spot's plate | Worn olive-wood table and the untouched round |

01 redraws the Scene 2 before-dawn plate. The hour changes to night. The stand point stays. 02–06 attach 01.

## Where the picture stands

Grid: +x east, +y north, metres. Origin (0, 0) is the lamp niche in the north gatepost. Heading 0 is east, 90 north, 180 west and 270 south. A quarter turn right subtracts 90 degrees.

`orbits/sc14/` has SPOTS.md and has no FIELDS.json. The spot already stands at the room's middle, (-35.8, -1.8), facing 90, which is the interior rule: the middle of the room, facing the hearth wall. Plate, right, reverse and left share that stand. Low and macro move, and each had its own digest.

| file | position | faces | landmark sides | light |
|---|---|---|---|---|
| 01 | (-35.8, -1.8), above the table | 90, north | Hearth CENTRE 2 m; niche and jars LEFT; water jar RIGHT 2 m; bread ahead LEFT; fold 14 m RIGHT, past the east wall | Hearth ahead, the only light inside. Niche flame in the arch. Yard fire, spit and torch off-frame RIGHT |
| 02 | (-35.8, -1.8) | 0, east | Door CENTRE 2 m; jar LEFT; yard fire CENTRE 6 m; torch LEFT 3 m; spit RIGHT 10 m; fold and gate LEFT; byre further LEFT; gate ahead 36 m | Looks into the yard fire. Hearth off the LEFT edge, on the jar. Torch and spit past the wall, spill on the jambs |
| 03 | (-35.8, -1.8) | 270, south | Bench RIGHT; mat and sling LEFT; mill RIGHT 2 m; set place ahead RIGHT; ovens LEFT 9 m; tree RIGHT 25 m; terrace ahead 31 m; floor LEFT 33 m | Hearth behind, dim falloff on the near wood. Yard fire LEFT, spit ahead LEFT, torch behind LEFT, all past the walls |
| 04 | (-35.8, -1.8) | 180, west | Oil jars RIGHT 2 m; mill LEFT 2 m; bench far LEFT; trees 19 m RIGHT and 25 m LEFT; terrace 36 m LEFT | Hearth off-frame RIGHT, the only interior light. Niche just outside on the RIGHT. Yard fires behind |
| 05 | (-37.05, -4.15), lens about 0.10 m | 45, north-east | Mill LEFT 1 m; bench RIGHT 1 m; table and bread LEFT 3 m; door RIGHT 4 m; torch ahead 5 m | Hearth ahead LEFT, 5 m, the only interior light. Niche ahead LEFT. Torch through the door. Yard fire RIGHT, past the wall |
| 06 | (-35.88, -1.62), on the table | 90, north | Untouched round fills the wood, slightly LEFT; stack behind RIGHT; hearth ahead 2 m; niche LEFT 3 m | Hearth ahead, the only light on the wood. Niche stays in the arch |

The digest lists angle and the nearest sampled distance, capped at fourteen landmarks. It does not test walls. Prompts keep the house walls: the west and south walls are solid, and the east doorway is the one opening. The yard fire at six metres aligns with that opening from the table. The torch and the spit sit north and south of the jambs, so the wall stands between the table and those two fires. From the low corner the torch ray passes the north side of the opening. The fold, byre, ovens, trees, terrace and threshing floor stay beyond the walls.

The two unlabeled flames in every digest are the hearth fire at (-35.8, 0.25) and the niche lamp at (-36.85, 0.72). Their sides were taken with the same angle rule as the digest. The one gate, about thirty-six metres due east of the table, is on the axis and fell past the fourteen-landmark cap.

## The locked design

- **The room:** Eliab's one room, exactly 7 by 4 paces, 5.25 by 3.0 metres inside. Mud brick, patchy lime plaster, soot-dark beams. The middle of the table is (-35.8, -1.8).
- **FRONT, north:** fire-blackened hearth ring, clay pot, arched lamp niche on the left of that wall.
- **RIGHT, east:** open timber doorway, leaf folded in on the north jamb, clay water jar beside it. The yard, the dance-ring fire, the calf on the spit and the eaves torch are beyond it.
- **BEHIND, south:** mud-brick sleeping bench with rolled sheepskins and folded wool blankets; the mat and the sling peg along the east side.
- **LEFT, west:** sealed storage jars and oil jars to the north, stone hand mill on its reed mat with flour to the south.
- **Centre:** low heavy olive-wood table, 0.75 by 1.4 metres, and four wooden stools.
- **This hour:** bread stacked on the table, one round untouched on the north-west of the top, a bowl and a round set at the south end. Hearth burning. Niche lamp lit. The yard fires and the eaves torch burning outside.
- **Screened life:** the ewe is at the fold, beyond the east wall from these interiors. The plates leave the fold outside the frame.

## The light and look

Bible section 4 and design note sections 2c and 2d. One interior source: the hearth, soot-brown and restrained, glow about 1.7 metres, so the south half of the room falls dark. The niche lamp is the small flame the staging puts in the arch, and its reach stays there. Through the east view the yard fire is the flame in the opening. The spit and the torch light their own ground outside. More than a third of every wide is in deep shadow. The macro is the rubbed table, grazed by the hearth, with deep contact shadow in the grain. Each wide ends on the brief's look line. The macro ends on the short line. Each tool line states 3:2.

## Redraw chain

sc02_A_the_house_before_dawn, prompt sc02/prompts/01_A_plate.txt, to 01_A_plate. The design and the stand point stay. Before dawn becomes the feast night. 02–06 attach 01.

## Digest execution evidence

All six commands exited 0. Prefix: `D:/Dev/Tools/Python312/python.exe -I work/prodigal-v3-20261019/location-plates/orbit_spots.py`. Each command also printed the other three turns. The front of each is the view.

### 01 plate

`--digest sc14_A_the_feast -35.8 -1.8 90`

front (heading 90°) · light: Yard fire, the dance ring: to the right, 6 m; The calf on the spit: behind on the right, 10 m; Torch at the eaves: ahead on the right, 3 m; 2 more small lamps or fires around the place

sees: Asher's bread, untouched (prop), 0 m, left; Water jar (prop), 2 m, right; Oil jars (prop), 2 m, left; Hearth (FRONT) (slab), 2 m, centre; Eliab's house (eliab_house) (building), 3 m, right; Storage jars (LEFT) (prop), 3 m, left; Lamp niche (prop), 3 m, left; Eaves (area), 3 m, right; Yard (area), 3 m, right; Yard wall, about 1.7 m (wall), 4 m, right; The fold (area), 14 m, right

### 02 right

`--digest sc14_A_the_feast -35.8 -1.8 0`

front (heading 0°) · light: Yard fire, the dance ring: ahead, the view backlit, 6 m; The calf on the spit: ahead on the right, 10 m; Torch at the eaves: ahead, the view backlit, 3 m; 2 more small lamps or fires around the place

sees: Water jar (prop), 2 m, left; Doorway (RIGHT) (door), 2 m, centre; door (door), 2 m, centre; Eliab's house (eliab_house) (building), 2 m, right; Eaves (area), 2 m, centre; Yard (area), 2 m, centre; Torch at the eaves (lamp), 3 m, left; Yard fire, the dance ring (fire), 6 m, centre; The calf on the spit (fire), 10 m, right; The fold (area), 12 m, left; Fold gate, barred (gate), 19 m, left; Yard wall, about 1.7 m (wall), 20 m, left; Calf pen (wall), 28 m, left; Ox byre (building), 29 m, left

### 03 reverse

`--digest sc14_A_the_feast -35.8 -1.8 270`

front (heading 270°) · light: Yard fire, the dance ring: to the left, 6 m; The calf on the spit: ahead on the left, 10 m; Torch at the eaves: behind on the left, 3 m; 2 more small lamps or fires around the place

sees: Amos's place, set (prop), 0 m, right; Stools (prop), 1 m, centre; Hand mill (prop), 2 m, right; Asher's mat (prop), 2 m, left; Sleeping bench (BEHIND) (slab), 2 m, right; Eliab's house (eliab_house) (building), 3 m, left; Yard (area), 3 m, left; Peg, sling (prop), 3 m, left; Eaves (area), 3 m, left; Ovens (prop), 9 m, left; tree (tree), 25 m, right; Terrace edge (wall), 31 m, centre; Threshing floor (slab), 33 m, left; Floor track (track), 34 m, left

### 04 left

`--digest sc14_A_the_feast -35.8 -1.8 180`

front (heading 180°) · light: Yard fire, the dance ring: behind the camera, the view lit from the front, 6 m; The calf on the spit: behind on the left, 10 m; Torch at the eaves: behind the camera, the view lit from the front, 3 m; 2 more small lamps or fires around the place

sees: Oil jars (prop), 2 m, right; Hand mill (prop), 2 m, left; Eliab's house (eliab_house) (building), 2 m, left; tree (tree), 19 m, right; tree (tree), 25 m, left; Terrace edge (wall), 36 m, left

### 05 low

`--digest sc14_A_the_feast -37.05 -4.15 45`

front (heading 45°) · light: Yard fire, the dance ring: ahead on the right, 8 m; The calf on the spit: ahead on the right, 10 m; Torch at the eaves: ahead, the view backlit, 5 m; 2 more small lamps or fires around the place

sees: Sleeping bench (BEHIND) (slab), 1 m, right; Hand mill (prop), 1 m, left; Stools (prop), 2 m, centre; Peg, sling (prop), 2 m, right; Amos's place, set (prop), 2 m, left; Asher's mat (prop), 2 m, right; Table · orbit centre (prop), 3 m, left; Bread stacked high (prop), 3 m, left; Asher's bread, untouched (prop), 3 m, left; Eliab's house (eliab_house) (building), 3 m, right; Eaves (area), 3 m, right; Yard (area), 3 m, right; Oil jars (prop), 4 m, left; Doorway (RIGHT) (door), 4 m, right

### 06 macro

`--digest sc14_A_the_feast -35.88 -1.62 90`

front (heading 90°) · light: Yard fire, the dance ring: to the right, 7 m; The calf on the spit: behind on the right, 10 m; Torch at the eaves: ahead on the right, 3 m; 2 more small lamps or fires around the place

sees: Oil jars (prop), 2 m, left; Water jar (prop), 2 m, right; Hearth (FRONT) (slab), 2 m, centre; Storage jars (LEFT) (prop), 2 m, left; Eliab's house (eliab_house) (building), 2 m, left; Lamp niche (prop), 3 m, left; Eaves (area), 3 m, right; Yard (area), 3 m, right; Yard wall, about 1.7 m (wall), 4 m, right; The fold (area), 14 m, right

The untouched round lies 0.24 metres ahead of the macro lens, inside the digest's 0.3 metre exclusion, so the close subject is absent from that sees list on purpose.
