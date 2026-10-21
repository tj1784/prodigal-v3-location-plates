# Scene 13, the father runs: short location prompts

The Prodigal Son v3, 21 October AD 2026. These are text deliverables for review. Nothing in this package is approved. Twenty-four future pictures, four spots. No images were made or attached.

## What to make (24 pictures, in this order)

| # | prompt | tool | attach | what |
|---|---|---|---|---|
| 01 | prompts/01_A_plate.txt | image_edit 3:2 | sc08 31_F_plate | Dusk gate from the open road, lamp lit |
| 02 | prompts/02_A_right.txt | image_edit 3:2 | 01 | North-northeast: road on the left, hill track on the left, open hillside |
| 03 | prompts/03_A_reverse.txt | image_edit 3:2 | 01 | East-southeast down the road, footpath on the right, front-lit |
| 04 | prompts/04_A_left.txt | image_edit 3:2 | 01 | South-southwest: footpath left, terrace and threshing floor right |
| 05 | prompts/05_A_low_corner.txt | image_edit 3:2 | 01 | Low on the road, looking back at the gate |
| 06 | prompts/06_A_macro.txt | image_edit 3:2 | 01 | The lit clay lamp in the north post's niche |
| 07 | prompts/07_B_plate.txt | image_edit 3:2 | sc06a 01_A_plate | Dusk village gate from the open slope |
| 08 | prompts/08_B_right.txt | image_edit 3:2 | 07 | South-southwest: slope, wall and houses on the left |
| 09 | prompts/09_B_reverse.txt | image_edit 3:2 | 07 | West-northwest up the hill path, trees both sides |
| 10 | prompts/10_B_left.txt | image_edit 3:2 | 07 | North-northeast: trees, slope right, Jericho road right |
| 11 | prompts/11_B_low_corner.txt | image_edit 3:2 | 07 | Low on the hill path, arch ahead |
| 12 | prompts/12_B_macro.txt | image_edit 3:2 | 07 | Worn top of the elders' bench |
| 13 | prompts/13_C_plate.txt | image_edit 3:2 | sc06b 07_B_plate | The road at dusk, sun ahead in the haze |
| 14 | prompts/14_C_right.txt | image_edit 3:2 | 13 | North: field wall right, thorn gully ahead, sun left |
| 15 | prompts/15_C_reverse.txt | image_edit 3:2 | 13 | East back down the road, wall left, front-lit |
| 16 | prompts/16_C_left.txt | image_edit 3:2 | 13 | South toward the wadi, sun right |
| 17 | prompts/17_C_low_corner.txt | image_edit 3:2 | 13 | Low on the road, sun ahead |
| 18 | prompts/18_C_macro.txt | image_edit 3:2 | 13 | One capstone of the field wall |
| 19 | prompts/19_D_plate.txt | image_edit 3:2 | sc02 19_D_plate | Night courtyard, yard fire and the house |
| 20 | prompts/20_D_right.txt | image_edit 3:2 | 19 | North-northeast: fold, calf pen, byre |
| 21 | prompts/21_D_reverse.txt | image_edit 3:2 | 19 | East-southeast toward the gate lamp |
| 22 | prompts/22_D_left.txt | image_edit 3:2 | 19 | South-southwest: spit fire, ovens, terrace |
| 23 | prompts/23_D_low_corner.txt | image_edit 3:2 | 19 | Low beside the basin, fire and doorway ahead |
| 24 | prompts/24_D_macro.txt | image_edit 3:2 | 19 | The worn rim of the clay basin |

Every plate is an image_edit of an earlier plate of the same place. Views 2–6 of a spot attach that spot's own plate. `orbits/sc13/FIELDS.json` does not exist, so the stands start from each spot's `pos` and `facing` in `ORBIT_SPOTS.json`.

## Where each picture stands

Grid: +x east, +y north, metres. Bearings are counterclockwise from east. A quarter turn right subtracts 90 degrees. Low corner and macro keep the plate's ground point and facing; the lens drops to a hand's breadth, or fills with one surface. Each stand was run through `orbit_spots.py --digest`.

**A. Eliab's gate at dusk.** `sc13_A_eliabs_gate_at_dusk`, from `sc08_F_the_gate_by_day`. Stand kept at (28.2, -11.5), on the open road about 29 m from the gate. The staged facing, 334 degrees, looks east-southeast down the road and leaves the gate behind the camera. The plate facing is turned to 154 degrees, west-northwest, so the whole gateway is in frame from that same open ground. The staged 334-degree view is the reverse. Sun from 180 degrees, low in the west. Digest: `--digest sc13_A_eliabs_gate_at_dusk 28.2 -11.5 154`.

| view | facing | landmarks | light |
|---|---|---|---|
| 01 plate | 154° | Road 1 m right; hill track 21 m centre; floor track 22 m centre; trough 28 m left; yard 29 m left; fig 29 m right; gate, lamp 29–30 m centre; wall and bench 31 m centre; cistern 35 m left; calf pen 36 m centre | Sun ahead, the view backlit. Lamp ahead, 30 m |
| 02 right | 64° | Road on the left; hill track 24 m left | Sun behind on the left. Lamp 30 m to the left |
| 03 reverse | 334° | Road 1 m left; footpath 24 m right | Sun behind the camera, front-lit. Lamp 30 m behind |
| 04 left | 244° | Footpath 23 m left; floor track 30 m right; terrace 33 m right; threshing floor 45 m right; far-field path 53 m right | Sun ahead on the right. Lamp 30 m to the right |
| 05 low | 154° | Same sides as the plate, lens on the road | Same backlit sun |
| 06 macro | niche | North post, lamp in the niche | Sun grazing from ahead |

The dog lies by the north post and the yoked oxen stand in the gateway. Both sit in the centre of the plate's view, taken from plan 0 of the staging, and fall outside the other three turns.

**B. The run past the village gate.** `sc13_B_the_run_past_the_village_gate`, from `sc06a_A_the_village_gate`. Stand (-25.04, 16.79), facing 326 degrees, on the open slope about 30 m from the arch. The whole arch is already in frame, so the staged facing is kept. Sun from 180 degrees. Digest: `--digest sc13_B_the_run_past_the_village_gate -25.04 16.79 326`.

| view | facing | landmarks | light |
|---|---|---|---|
| 07 plate | 326° | Hill path 1 m centre; slope 16 m centre; Jericho road 18 m centre; olive 24 m right; arch and wall 30 m centre; fig 30 m left; houses 32 m right; bench 33 m centre | Sun behind on the right |
| 08 right | 236° | Tree 10 m left; slope 19 m left; wall 34 m left; houses 35 m left | Sun ahead on the right |
| 09 reverse | 146° | Path under the lens; trees 23 m left, 26 m right, 38 m right, 40 m left; slope 43 m right | Sun ahead on the left |
| 10 left | 56° | Tree 11 m centre; tree 26 m left; slope 25 m right; Jericho road 33 m right | Sun behind on the left |
| 11 low | 326° | Same sides as the plate, lens on the path | Sun behind on the right |
| 12 macro | bench | Worn limestone of the elders' bench | Grazing light from behind-right |

**C. The road at dusk.** `sc13_C_the_road_at_dusk`, from `sc06b_B_the_road_at_the_bend`. Stand (702.6, -425.72), facing 178 degrees, on the road, the village ahead in the haze. Staged facing kept. Sun from 180 degrees, a pale disc straight up the road. Digest: `--digest sc13_C_the_road_at_dusk 702.6 -425.72 178`.

| view | facing | landmarks | light |
|---|---|---|---|
| 13 plate | 178° | Road 1 m left; stubble to the wadi 3 m left; field wall 6 m right; uphill stubble 7 m right; village 143 m centre; well, gate, pasture and farms far right | Sun ahead, the view backlit |
| 14 right | 88° | Wall 3 m right; uphill stubble 3 m right; thorn gully 198 m centre; pasture and hill track far left | Sun to the left |
| 15 reverse | 358° | Road 1 m right; wall and uphill stubble 3 m left; wadi stubble 7 m right | Sun behind the camera, front-lit |
| 16 left | 268° | Road 1 m centre; wadi stubble 3 m right; far buildings left and right | Sun to the right |
| 17 low | 178° | Same sides as the plate, lens on the road | Sun ahead, backlit |
| 18 macro | wall | One capstone of the field wall | Sun grazing the top from ahead |

The slabs named for the embrace and the orders are beat marks on the road. The prompts treat them as worn patches of the same packed earth.

**D. The courtyard at night.** `sc13_D_the_courtyard_at_night`, from `sc02_D_the_fold`. Stand (-25.8, -4.05), facing 165 degrees, in the yard, the house and the new fire in frame. Staged facing kept. There is no sun. The yard fire is the light that throws the shadows. The torch, the spit fire, the gate lamp, the lamps on the hill and eight smaller lamps stay where the digest puts them, because the screenplay has torches, the gate lamp and lamps coming up the hill. Digest: `--digest sc13_D_the_courtyard_at_night -25.8 -4.05 165`.

| view | facing | landmarks | light |
|---|---|---|---|
| 19 plate | 165° | Basin at the right edge; yard fire 4 m centre; eaves 7 m left; house, torch and door 8 m centre; wall 10 m right; trees 29 m centre and 32 m left; terrace 43 m left | Fire ahead, the house backlit. Gate lamp and hill lamps behind the camera. Spit fire ahead on the left |
| 20 right | 75° | Basin and the dog close on the left; fold 8 m centre; fold gate 11 m right; wall 14 m left; calf pen 19 m right; byre 21 m right; hill track 55 m right | Yard fire to the left. Gate lamp and hill lamps ahead on the right |
| 21 reverse | 345° | Fold and gate 13 m left; calf pen 19 m left; cistern 20 m centre; byre 22 m left; threshing floor 25 m right; gate, lamp and road 26 m left; trough 27 m centre; bench 27 m left | Yard fire behind the camera. Gate lamp ahead |
| 22 left | 255° | Spit fire 4 m right; ovens 7 m right; yard 9 m right; threshing floor 25 m left; terrace 29 m left; far-field path 30 m left; tree 32 m right | Spit fire ahead. Yard fire and torch to the right. Gate lamp behind on the left |
| 23 low | 165° | Same sides as the plate, lens beside the basin | Yard fire ahead |
| 24 macro | basin | Worn clay rim, warm water | Fire grazing the near lip |

The flock is in the barred fold, the fatted calf stands by the pen, and the dog lies near the basin. Those are the animals the staging keeps at this hour, and they appear only in the turns that face them.

## The locked design

- **The farm gate (A, and the gate seen from D):** one gateway in the east yard wall, dry-stone fieldstone about 1.7 m high. Two posts about a metre square, a timber lintel, a clear opening a little under three metres. The olive-wood leaf hinges on the south post and folds into the yard. A clay lamp burns in the arched niche of the north post. A stone bench runs outside, north of the gate. A stone trough stands south of it. The old fig is outside to the northeast. The cistern, the calf pen, the ox byre and the fold sit inside the yard. The round threshing floor lies on the south terrace. At dusk the lamp is lit, a dog lies by the north post, and two yoked oxen stand in the gateway.
- **The village gate (B):** the same stone arch, village wall, flat-roofed houses, elders' bench, old olive, fig, hill path and Jericho road as the morning plate. The hour is dusk. The morning sale cloth and balance are of that earlier hour, and this hour's prompts stay with the gate, the bench, the trees and the two roads. The bench is bare stone.
- **The road (C):** the same road east, packed earth, a low field wall of piled stones, stubble uphill on one side and stubble falling to the wadi on the other. The village, the well and the village gate sit far ahead in the haze. The low sun is straight up the road.
- **The courtyard (D):** the same farmyard, now at night. The new wood fire burns on the open earth in front of the house. A torch burns at the eaves. A spit fire is laid by the ovens. A clay basin of warm water sits on the yard. The fold is barred, with the flock inside. The gate lamp still burns, and lamps burn on the road up from the village.

Eliab's room, Kallias's court and the pig fields are outside this scene. The owner's map instruction for those three places is left to their own scenes.

## Earlier plates

| spot | drawn from | what changes |
|---|---|---|
| A | sc08 `31_F_plate`, the gate by day, stand (2.3, -1.65) facing 194° | Hour to dusk, lamp lit, stand moved out to the road and turned to face the gate |
| B | sc06a `01_A_plate`, the village gate in the morning, stand (-0.11, 0.39) facing 289° | Hour to dusk, stand moved out onto the slope |
| C | sc06b `07_B_plate`, the road at the bend in the morning, stand (1040.99, -581.2) facing 57° | Hour to dusk, stand moved up the road toward the village, sun ahead |
| D | sc02 `19_D_plate`, the fold at dawn, stand (-24.0, 0.2) facing 25° | Hour to night, stand moved into the courtyard, yard fire lit |

## Look

One source for the three dusk spots: the low sun from 180 degrees, through haze, with deep shadow over a third of the frame. At night the yard fire throws the shadows, and the smaller flames stay the practicals the hour holds. Every wide view ends on the fixed look line. Each macro ends on the short grain line. Aspect 3:2 is on every tool line.

Read: the short-prompts brief, the Scene 1 plate package, `ORBIT_SPOTS.json`, `orbits/sc13/SPOTS.md`, `SC13_STAGING.json`, the shared place files the digest reads, the screenplay from the road home into Scene 13, design note §2c and §2d, the owner's map instruction, and bible §4. The staging PNG was left unread. Sides come from the digest commands above.
