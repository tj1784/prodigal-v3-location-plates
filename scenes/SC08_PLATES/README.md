# Scene 8, home — the calf and the rumour: short location prompts

The Prodigal Son v3, 21 October AD 2026. Words only. Nothing in this set is owner-approved.

## What to make (42 pictures, in this order)

| # | prompt | tool | attach | what |
|---|---|---|---|---|
| 01 | prompts/01_A_plate.txt | image_edit 3:2 | sc03 01_A_plate | Harvest afternoon, wheat on the floor |
| 02 | prompts/02_A_right.txt | image_edit 3:2 | 01 | Quarter right, terrace edge and footpath |
| 03 | prompts/03_A_reverse.txt | image_edit 3:2 | 01 | Half turn, path to the far field |
| 04 | prompts/04_A_left.txt | image_edit 3:2 | 01 | Quarter left, sheaves, ovens, house |
| 05 | prompts/05_A_low_corner.txt | image_edit 3:2 | 01 | Ground level across the wheat |
| 06 | prompts/06_A_macro.txt | image_edit 3:2 | 01 | Worn floor rim, chaff in the cracks |
| 07 | prompts/07_B_plate.txt | image_edit 3:2 | sc02 19_D_plate | Rain-dark dusk inside the fold |
| 08 | prompts/08_B_right.txt | image_edit 3:2 | 07 | Quarter right, house and ovens |
| 09 | prompts/09_B_reverse.txt | image_edit 3:2 | 07 | Half turn, yard wall and house |
| 10 | prompts/10_B_left.txt | image_edit 3:2 | 07 | Quarter left, calf pen and byre |
| 11 | prompts/11_B_low_corner.txt | image_edit 3:2 | 07 | Ground level, manger and wet flock |
| 12 | prompts/12_B_macro.txt | image_edit 3:2 | 07 | Rain-dark manger lip |
| 13 | prompts/13_C_plate.txt | image_edit 3:2 | sc05 07_B_plate | Same gate, rain-dark dusk, lamp lit |
| 14 | prompts/14_C_right.txt | image_edit 3:2 | 13 | Quarter right, bench, pen, fold |
| 15 | prompts/15_C_reverse.txt | image_edit 3:2 | 13 | Half turn, old fig and hill track |
| 16 | prompts/16_C_left.txt | image_edit 3:2 | 13 | Quarter left, road and tracks |
| 17 | prompts/17_C_low_corner.txt | image_edit 3:2 | 13 | Ground level at the wet threshold |
| 18 | prompts/18_C_macro.txt | image_edit 3:2 | 13 | Rain-darkened niche sill |
| 19 | prompts/19_D_plate.txt | image_gen 3:2 | nothing, from text | City square inside the west gate, dusk |
| 20 | prompts/20_D_right.txt | image_edit 3:2 | 19 | Quarter right, north side and side street |
| 21 | prompts/21_D_reverse.txt | image_edit 3:2 | 19 | Half turn, street and lamps |
| 22 | prompts/22_D_left.txt | image_edit 3:2 | 19 | Quarter left, camels, bales, cook-fire |
| 23 | prompts/23_D_low_corner.txt | image_edit 3:2 | 19 | Ground level from the inner gate |
| 24 | prompts/24_D_macro.txt | image_edit 3:2 | 19 | Hoof-scored flag |
| 25 | prompts/25_E_plate.txt | image_edit 3:2 | sc02 43_H_plate | Morning, the whole calf pen |
| 26 | prompts/26_E_right.txt | image_edit 3:2 | 25 | Quarter right, gate, bench, road |
| 27 | prompts/27_E_reverse.txt | image_edit 3:2 | 25 | Half turn, cistern and lower floor |
| 28 | prompts/28_E_left.txt | image_edit 3:2 | 25 | Quarter left, fold and house |
| 29 | prompts/29_E_low_corner.txt | image_edit 3:2 | 25 | Ground level under the rail |
| 30 | prompts/30_E_macro.txt | image_edit 3:2 | 25 | Rubbed pen rail |
| 31 | prompts/31_F_plate.txt | image_edit 3:2 | sc05 01_A_plate | Same gate, harvest afternoon |
| 32 | prompts/32_F_right.txt | image_edit 3:2 | 31 | Quarter right, bench, fig, byre |
| 33 | prompts/33_F_reverse.txt | image_edit 3:2 | 31 | Half turn, road east downhill |
| 34 | prompts/34_F_left.txt | image_edit 3:2 | 31 | Quarter left, trough in the wall shade |
| 35 | prompts/35_F_low_corner.txt | image_edit 3:2 | 31 | Ground level beside the trough |
| 36 | prompts/36_F_macro.txt | image_edit 3:2 | 31 | Water-dark trough lip |
| 37 | prompts/37_G_plate.txt | image_edit 3:2 | sc02 43_H_plate | Night, fold gate and its lamp |
| 38 | prompts/38_G_right.txt | image_edit 3:2 | 37 | Quarter right, yard and house |
| 39 | prompts/39_G_reverse.txt | image_edit 3:2 | 37 | Half turn, bedded flock and byre |
| 40 | prompts/40_G_left.txt | image_edit 3:2 | 37 | Quarter left, farm gate and its lamp |
| 41 | prompts/41_G_low_corner.txt | image_edit 3:2 | 37 | Ground level inside the fold gate |
| 42 | prompts/42_G_macro.txt | image_edit 3:2 | 37 | Sooted clay rim of the fold lamp |

Every view names one plate. These are future attachment lines. This folder is text. Source numbers follow six prompts per spot: sc03 A is 01, sc02 D is 19, sc02 H is 43, sc05 A is 01, sc05 B is 07.

## Where each picture stands

Farm grid: +x east, +y north, metres. Origin (0, 0) is the lamp niche in the north gatepost. Heading 0 is east, 90 north, 180 west, 270 south. A quarter right subtracts 90 degrees. The square uses its own origin, the inner mouth of the city's west gate, same axis.

`orbits/sc08/` has SPOTS.md and no FIELDS.json. Plates start from each spot's registered `pos` and `facing`. Spot E's registered camera, (-7.25, 6.3) facing 308, is the action camera inside the pen: its wide front sees the rail and the gate, and the barley manger falls in the left turn. The exterior rule puts E's plate on open yard at (-6.2, 1.5), facing 90, so the rail, the calf, the manger and the byre are one view. The registry digest was run and kept as evidence. Spot D's plate stays at the registered square camera. Its low corner moves to the inner gate so the kneeling camels are in that frame. Spot G's macro stands half a metre from the fold lamp; closer than three-tenths of a metre, the digest drops the flame.

| file | position | faces | light from the digest front |
|---|---|---|---|
| 01 | (-18.6, -29.8) | 36 | Sun behind the camera, the view lit from the front. Wheat CENTRE 2 m, floor CENTRE 6 m, terrace RIGHT, yard LEFT |
| 02 | same | 306 | Sun to the right. Terrace edge RIGHT 4 m, footpath LEFT 15 m |
| 03 | same | 216 | Sun ahead, backlit. Far-field path LEFT 3 m, terrace LEFT, tree RIGHT 36 m |
| 04 | same | 126 | Sun to the left. Sheaves RIGHT 2 m, ovens and house CENTRE, fold RIGHT |
| 05 | (-17.6, -29.2), lens about 0.12 m | 36 | Same sun, lit from the front. Wheat CENTRE 1 m |
| 06 | (-17.9, -29.5), on the rim | 36 | Same sun. The rim fills the frame; wider landmarks fall outside |
| 07 | (-21.2, 5.35) | 329 | Sun behind on the right. Manger RIGHT 1 m, basket LEFT 3 m, fold gate CENTRE 4 m. Gate lamp ahead, slightly left, about 22 m |
| 08 | same | 239 | Sun ahead on the right. Fold LEFT, house and doorway RIGHT 13–14 m |
| 09 | same | 149 | Sun ahead on the left. Fold LEFT 4 m, yard wall RIGHT, house LEFT |
| 10 | same | 59 | Sun behind on the left. Fold and wall LEFT, pen and byre RIGHT |
| 11 | (-24.2, 4.0), lens about 0.12 m | 50 | Sun behind on the left. Manger RIGHT 4 m, flock ahead |
| 12 | (-20.3, 4.25), on the manger | 210 | Sun ahead, backlit. The wet lip fills the frame |
| 13 | (1.45, 1.3) | 232 | Sun ahead on the right. Gate CENTRE 2 m, wall RIGHT, road LEFT. Lamp ahead, slightly right, about 2 m |
| 14 | same | 142 | Sun ahead on the left. Bench CENTRE 1 m, pen CENTRE, fold LEFT |
| 15 | same | 52 | Sun behind on the left. Fig CENTRE 8 m, hill track RIGHT |
| 16 | same | 322 | Sun behind on the right. Road RIGHT 3 m, tracks CENTRE |
| 17 | (0.7, 0.15), lens about 0.12 m | 232 | Sun ahead on the right. Gate RIGHT 1 m, road LEFT. Lamp above-right |
| 18 | (0.22, 0.08), on the sill | 200 | Sun ahead, backlit. The sill fills the frame |
| 19 | (21.6, 1.75) | 155 | Sun ahead on the left. Sun-shaft CENTRE, square and houses RIGHT, cook-fire LEFT 13 m, west gate LEFT 23 m. Lamps behind on the right |
| 20 | same | 65 | Sun behind on the left. Square RIGHT, side street LEFT 11 m |
| 21 | same | 335 | Sun behind on the right. Street RIGHT 2 m, shops RIGHT, lamps LEFT 8 m |
| 22 | same | 245 | Sun ahead on the right. Shops LEFT, cook-fire RIGHT 13 m, camels RIGHT 14 m |
| 23 | (0.5, -2.2), lens about 0.12 m | 345 | Sun behind, the view lit from the front. Camels CENTRE 11 m, cook-fire LEFT, shops RIGHT, lamps LEFT 29 m |
| 24 | (11.0, -7.2), on a flag | 180 | Sun ahead, backlit. One flag fills the frame |
| 25 | (-6.2, 1.5) | 90 | Sun behind on the right. Rail CENTRE 4 m, manger CENTRE 7 m, byre CENTRE 8 m, fold LEFT |
| 26 | same | 0 | Sun ahead, backlit. Gate RIGHT 6 m, bench CENTRE, fig LEFT |
| 27 | same | 270 | Sun ahead on the left. Gate and trough LEFT, cistern CENTRE, floor RIGHT 29 m |
| 28 | same | 180 | Sun behind, lit from the front. Fold RIGHT, house CENTRE 28 m |
| 29 | (-6.5, 4.6), lens about 0.12 m | 90 | Sun behind on the right. Rail LEFT 1 m, manger CENTRE 4 m |
| 30 | (-6.4, 5.28), on the rail | 0 | Sun ahead, backlit. The rail fills the frame |
| 31 | (2.3, -1.65) | 194 | Sun ahead, backlit. Road CENTRE 1 m, wall shade LEFT, gate CENTRE 2 m, yard RIGHT |
| 32 | same | 104 | Sun behind on the left. Gate LEFT, bench CENTRE 4 m, fig RIGHT, byre CENTRE |
| 33 | same | 14 | Sun behind, lit from the front. Road RIGHT, tracks RIGHT, footpath far RIGHT |
| 34 | same | 284 | Sun ahead on the right. Wall shade CENTRE, trough RIGHT 4 m, floor RIGHT 30 m |
| 35 | (1.6, -4.8), lens about 0.12 m | 250 | Sun ahead on the right. Trough RIGHT 1 m, shade CENTRE |
| 36 | (1.15, -5.45), on the lip | 190 | Sun ahead, backlit. The lip fills the frame |
| 37 | (-14.55, 5.85) | 262 | Fold lamp ahead, backlit, 2 m. Fold and barred gate CENTRE. Gate lamp is outside this frame |
| 38 | same | 172 | Fold lamp to the left, 2 m. Fold LEFT, house and doorway LEFT, yard RIGHT |
| 39 | same | 82 | Fold lamp behind, the view lit from the front, 2 m. Byre RIGHT, yard CENTRE |
| 40 | same | 352 | Fold lamp to the right, 2 m. Pen LEFT, farm gate RIGHT 16 m, fig LEFT |
| 41 | (-15.2, 4.15), lens about 0.12 m | 90 | Fold lamp behind, lit from the front, 1 m. Byre RIGHT |
| 42 | (-15.15, 3.95), on the lamp | 241 | Fold lamp ahead, backlit, 1 m. The clay rim fills the frame |

Animals are staged as living markers, so the digest's landmark list omits them. Their sides are measured from those staging positions against the digested heading. The unlabeled "one more small lamp" on the farm at dusk and night is the gate lamp at (0, 0). Prompts name it only in the views that reach it.

## The locked design

- **The farm:** terrace above the valley. Yard about 34 m east to west and 30 m north to south, inside rough fieldstone walls about 1.7 m high and 0.7 m thick. Packed earth. The road east leaves the gate and falls toward the village. The old fig is at (6.5, 8).
- **The one gate:** clear opening 2.7 m between 0.9 m posts, one timber lintel. One olive-wood leaf hinges on the south post and folds inward, west, into the yard. From outside looking west, the leaf is LEFT and the north post, with the arched niche and clay lamp, is RIGHT. Bench at (0.65, 1.95). Trough at (0.9, -5.6). The leaf stays open.
- **The house:** west of the yard, doorway at (-34, -1.8). Interior exactly 7 by 4 paces, 5.25 m by 3.0 m. From the middle, facing the hearth wall: FRONT the hearth ring, pot and arched niche; RIGHT the timber doorway and water jar; BEHIND the sleeping bench with sheepskins and blankets; LEFT the storage jars, oil jars and hand mill on its reed mat with spilled flour; the olive-wood table and stools in the middle. Distant prompts show the open doorway as a dark rectangle. They do not unpack that room.
- **The floor:** nine-metre stone circle at (-14, -26.5), below the yard. Harvest afternoon: wheat spread on it, sheaves stacked at (-19, -28.3), chaff in the south-west sun because the wheat is on the floor.
- **The fold:** (-25 to -11, 3.5 to 13.65), barred south gate. Rain dusk: the ewe with the torn ear at the manger (-20.5, 4.15), barley basket, wet flock. Night: clay lamp on the east fold-gate post at (-15.4, 3.5), a young black goat and the she-goat inside the gate, the flock bedded to the north.
- **The calf pen:** low timber rail, (-9 to -3.4, 5.2 to 9), open to the ox byre on the north. Morning: the red calf at (-6.3, 7.5), barley in the manger at (-6.2, 8.6). Barley dust at the muzzle comes from the feeding.
- **The square:** paved limestone inside the west gate, city wall, houses and shops, a side street, the street east where the lamps come on. Cook-fire at (9, -1.6), smoke pulled west by the hot east wind. Kneeling camels and roped bales on the south side. Last sun level through the gate; the square otherwise in the wall's shadow.
- **Who stays out:** the prompts hold the places and the animals the hour keeps there. The dog lies at the rain-dark gate, facing the road. The harvest-afternoon trough keeps the camel and the donkey with sheaves. People stay out of every frame.

## The light

Bible section 4: one broad source at the real hour, deep shadow over a third of the frame or more, muted sun-faded earth, pale warm-grey haze, fine grain. Non-macros end on the brief's look line. Macros end on the short line. Each tool line is 3:2.

- **A and F:** harvest-afternoon sun, 215° and 210°. Chaff comes from the wheat. At F the trough sits in the wall's shade.
- **B and C:** rain-dark dusk from 195°, plus the gate lamp as the one small flame. Rain darkens the stone. At C the wind off the western hills bends the flame eastward, and moths come to it.
- **D:** last sun from 192° through the west gate. The cook-fire and the street lamps are local flames with a short reach. The east wind carries the smoke west.
- **E:** morning sun from 330°, over the east side of the yard. The calf's coat takes that light.
- **G:** night. The fold lamp is the near flame, reach about 2 m. The gate lamp is a separated flame at the niche when a view reaches the gate. Village fires are tiny points about 600 m down the hill. They do not light the fold.

Measured luma, colour and grain belong to future pictures. These files are words.

## Redraw chain

- sc03_A, future sc03/prompts/01_A_plate.txt, evening floor, becomes 01. Hour becomes harvest afternoon. Stand moves to the south-west rim. The stone floor stays.
- sc02_D, future sc02/prompts/19_D_plate.txt, the fold at sunrise, becomes 07. Hour becomes rain-dark dusk. Stand moves inside the fold.
- sc05_B, future sc05/prompts/07_B_plate.txt, the gate at first light, becomes 13. Hour becomes rain-dark dusk. Stand moves close to the north side of the gate.
- 19 is drawn from text. The square has no earlier plate.
- sc02_H, future sc02/prompts/43_H_plate.txt, the gate late at night, becomes 25 and 37. 25 changes the hour to morning and the stand to the calf pen. 37 keeps the night and moves the stand into the fold, adding the fold-post lamp.
- sc05_A, future sc05/prompts/01_A_plate.txt, the gate at night, becomes 31. Hour becomes harvest afternoon. Stand is just outside the gateway.

Views 02–06 attach 01; 08–12 attach 07; 14–18 attach 13; 20–24 attach 19; 26–30 attach 25; 32–36 attach 31; 38–42 attach 37.

Read: SHORT_PROMPTS_BRIEF.md; packages/SC01_PLATES; ORBIT_SPOTS.json; orbits/sc08/SPOTS.md; staging/sc08/SC08_STAGING.json; staging/places/eliab_farm.json and eliab_house.json; the screenplay from the Scene 8 heading through the fold at night; PRODIGAL_V3_DESIGN_NOTE.md sections 2c–2d and the Scene 8 row; staging/atlas/BRIEF_scene_maps.md, the owner's room and the later-map lines; REVENANT_CINEMATOGRAPHY_BIBLE.md section 4.

## Digest commands

Prefix: `D:/Dev/Tools/Python312/python.exe -I work/prodigal-v3-20261019/location-plates/orbit_spots.py --digest`. Each command below was run and exited 0. The front light and the sides in the table are that front. Quarter turns of a plate are the same stand with the turned heading.

- 01 `--digest sc08_A_the_wheat_on_the_floor -18.6 -29.8 36`
- 02 `--digest sc08_A_the_wheat_on_the_floor -18.6 -29.8 306`
- 03 `--digest sc08_A_the_wheat_on_the_floor -18.6 -29.8 216`
- 04 `--digest sc08_A_the_wheat_on_the_floor -18.6 -29.8 126`
- 05 `--digest sc08_A_the_wheat_on_the_floor -17.6 -29.2 36`
- 06 `--digest sc08_A_the_wheat_on_the_floor -17.9 -29.5 36`
- 07 `--digest sc08_B_the_rains_and_the_winter -21.2 5.35 329`
- 08 `--digest sc08_B_the_rains_and_the_winter -21.2 5.35 239`
- 09 `--digest sc08_B_the_rains_and_the_winter -21.2 5.35 149`
- 10 `--digest sc08_B_the_rains_and_the_winter -21.2 5.35 59`
- 11 `--digest sc08_B_the_rains_and_the_winter -24.2 4.0 50`
- 12 `--digest sc08_B_the_rains_and_the_winter -20.3 4.25 210`
- 13 `--digest sc08_C_the_rains_and_the_winter 1.45 1.3 232`
- 14 `--digest sc08_C_the_rains_and_the_winter 1.45 1.3 142`
- 15 `--digest sc08_C_the_rains_and_the_winter 1.45 1.3 52`
- 16 `--digest sc08_C_the_rains_and_the_winter 1.45 1.3 322`
- 17 `--digest sc08_C_the_rains_and_the_winter 0.7 0.15 232`
- 18 `--digest sc08_C_the_rains_and_the_winter 0.22 0.08 200`
- 19 `--digest sc08_D_the_square_by_the_west_gate 21.6 1.75 155`
- 20 `--digest sc08_D_the_square_by_the_west_gate 21.6 1.75 65`
- 21 `--digest sc08_D_the_square_by_the_west_gate 21.6 1.75 335`
- 22 `--digest sc08_D_the_square_by_the_west_gate 21.6 1.75 245`
- 23 `--digest sc08_D_the_square_by_the_west_gate 0.5 -2.2 345`
- 24 `--digest sc08_D_the_square_by_the_west_gate 11.0 -7.2 180`
- 25 `--digest sc08_E_the_calf_pen -6.2 1.5 90`
- 26 `--digest sc08_E_the_calf_pen -6.2 1.5 0`
- 27 `--digest sc08_E_the_calf_pen -6.2 1.5 270`
- 28 `--digest sc08_E_the_calf_pen -6.2 1.5 180`
- 29 `--digest sc08_E_the_calf_pen -6.5 4.6 90`
- 30 `--digest sc08_E_the_calf_pen -6.4 5.28 0`
- registry E, not a prompt: `--digest sc08_E_the_calf_pen -7.25 6.3 308`
- 31 `--digest sc08_F_the_gate_by_day 2.3 -1.65 194`
- 32 `--digest sc08_F_the_gate_by_day 2.3 -1.65 104`
- 33 `--digest sc08_F_the_gate_by_day 2.3 -1.65 14`
- 34 `--digest sc08_F_the_gate_by_day 2.3 -1.65 284`
- 35 `--digest sc08_F_the_gate_by_day 1.6 -4.8 250`
- 36 `--digest sc08_F_the_gate_by_day 1.15 -5.45 190`
- 37 `--digest sc08_G_the_fold_at_night -14.55 5.85 262`
- 38 `--digest sc08_G_the_fold_at_night -14.55 5.85 172`
- 39 `--digest sc08_G_the_fold_at_night -14.55 5.85 82`
- 40 `--digest sc08_G_the_fold_at_night -14.55 5.85 352`
- 41 `--digest sc08_G_the_fold_at_night -15.2 4.15 90`
- 42 `--digest sc08_G_the_fold_at_night -15.15 3.95 241`
