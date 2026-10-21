# Scene 6B, the departure and the bend: short location prompts

The Prodigal Son v3, 21 October AD 2026. Text only. Nothing in this package is approved. Twelve prompts, two spots. No image was made.

## What to make (twelve pictures, in this order)

| # | prompt | tool | attach | what |
|---|---|---|---|---|
| 01 | prompts/01_A_plate.txt | image_edit 3:2 | sc02 25_E_plate | Dawn gate from the open road, whole gateway in frame |
| 02 | prompts/02_A_right.txt | image_edit 3:2 | 01 | North: fig at centre, hill track right, fold left |
| 03 | prompts/03_A_reverse.txt | image_edit 3:2 | 01 | East: road and hill track on the right, mist in the valley, sun ahead |
| 04 | prompts/04_A_left.txt | image_edit 3:2 | 01 | South: floor track and threshing floor on the right |
| 05 | prompts/05_A_low_corner.txt | image_edit 3:2 | 01 | Low on the road-side threshold, looking west through the opening |
| 06 | prompts/06_A_macro.txt | image_edit 3:2 | 01 | East face of the north gatepost |
| 07 | prompts/07_B_plate.txt | image_edit 3:2 | sc02 31_F_plate | Morning bend: road and spur at centre, boulders on the right |
| 08 | prompts/08_B_right.txt | image_edit 3:2 | 07 | Straight road east on the left, sun ahead |
| 09 | prompts/09_B_reverse.txt | image_edit 3:2 | 07 | South-west slope, two distant farm buildings |
| 10 | prompts/10_B_left.txt | image_edit 3:2 | 07 | Back up the valley: road and spur right, village left, gate far at centre |
| 11 | prompts/11_B_low_corner.txt | image_edit 3:2 | 07 | Low at the roadside, boulders at centre |
| 12 | prompts/12_B_macro.txt | image_edit 3:2 | 07 | East face of the spur's boulder |

01 and 07 are redrawn from earlier plates. Views 02–06 attach 01. Views 08–12 attach 07.

## Where each picture stands

Grid for both places: +x east, +y north, metres. Origin is the lamp niche in the north gatepost. Bearings run counterclockwise from east: 0 east, 90 north, 180 west, 270 south. A quarter turn right subtracts 90 degrees. `orbits/sc06b/FIELDS.json` does not exist. The performance cameras in `ORBIT_SPOTS.json` are the scene's working setups, too close for an exterior plate, so each plate stands on open ground with the whole place in frame. Every view below was run through `orbit_spots.py --digest`.

### Spot A, `sc06b_A_the_gate_at_dawn`

`eliab_farm:ext`, dawn. Sun from 5 degrees, first light low from the east. Performance setup S03 is at (-0.45, -1.85), facing 96 degrees, inside the opening: the digest there puts the yard at 0 m and the gate at 2 m. The plate uses the establishing stand already chosen for this gateway in `orbits/sc02/FIELDS.json` for `sc02_E_the_gate_at_dusk`: (8, -1.8), facing 180 degrees, eight metres outside on the road. The hour changes from dusk to dawn. The stand matches the attached plate.

| file | camera (x, y) m | facing | digest landmarks | light |
|---|---|---|---|---|
| 01 plate | (8, -1.8) | 180, west | Road 1 m left; gate, trough, bench and wall 8 m (trough left, bench and wall right, gate centre); calf pen 13 m right; byre 15 m right; cistern 16 m left; fold 20 m right; fold gate 24 m right; floor track 27 m left; threshing floor 33 m left | Behind the camera, front-lit |
| 02 right | (8, -1.8) | 90, north | Hill track 5 m right; fig 10 m centre; wall 10 m left; calf pen and byre 15 m left; fold 24 m left | To the right |
| 03 reverse | (8, -1.8) | 0, east | Hill track 2 m right; road 3 m right; village footpath 42 m right | Ahead, backlit |
| 04 left | (8, -1.8) | 270, south | Road 1 m centre; hill track 2 m left; floor track 2 m right; yard 11 m right; footpath and terrace 31 m centre; threshing floor 33 m right; far-field path 42 m right | To the left |
| 05 low | (2.2, -1.8) | 180, west | Road 1 m left; gate 2 m centre; wall 3 m right; cistern 12 m left; fold 14 m right; fold gate 18 m right; ovens 33 m centre; eaves 35 m centre; house and door 36 m centre | Behind the camera, front-lit |
| 06 macro | (0.95, 0.05) | 180, west | Gate 1 m centre; first-light patch 1 m left; yard wall 1 m right. The post's east face fills the frame | Behind the camera, grazing |

The digest lists at most fourteen landmarks. From (8, -1.8) facing west the house doorway is on the gate axis about 42 m ahead at centre, past that cap, so 01 names it from the place lock. The jenny at (0.5, -2.6) is about 8 m away, just left of centre. The farm dog at (0.85, -0.95) is about 7 m away, just right of centre. From the low lens those two sit about 2 m away, jenny left and dog right. The lens at 05 is a hand's breadth, about 12 cm, above the threshold.

### Spot B, `sc06b_B_the_road_at_the_bend`

`eliab_valley:ext`, morning. Sun from 350 degrees, low, a little south of where it rose. Performance setup S11 is at (1040.99, -581.2), facing 57 degrees, on the road: the digest there sees the road at 1 m and the spur at 4 m, and the boulders fall outside the front view. The plate steps back to open slope at (1020, -592), facing 60 degrees, so the road, the spur and the boulders are all in frame.

| file | camera (x, y) m | facing | digest landmarks | light |
|---|---|---|---|---|
| 07 plate | (1020, -592) | 60 | Road 18 m centre; spur 20 m centre; boulders 23 m right | Ahead on the right |
| 08 right | (1020, -592) | 330 | Road 30 m left | Ahead, backlit |
| 09 reverse | (1020, -592) | 240 | Building 447 m centre; building 879 m right | Behind on the left |
| 10 left | (1020, -592) | 150 | Road 20 m right; spur 23 m right; thorn gully 445 m right; building 494 m right; village 492 m left; well 570 m centre; village gate 725 m centre; hill pasture 1013 m right; hill track 1131 m centre; far-field path 1181 m centre; far field 1196 m centre; other farms 1562 m centre | Behind the camera, front-lit |
| 11 low | (1034, -582) | 55 | Road 4 m left; spur 6 m left; boulders 6 m centre | Ahead on the right |
| 12 macro | (1038.7, -576.75) | 180 | Boulder and spur 1 m centre; road 3 m left. The east face fills the frame | Behind the camera, grazing |

The low lens is a hand's breadth above the roadside dust. The bend anchor is (1040, -580), 1.2 km east of the gate.

## The locked design

**The gate.** One yard, 34 m east to west and 30 m north to south, inside a dry-stone fieldstone wall about 1.7 m high. The east wall has one gateway: a 2.7 m opening between posts 0.9 m square under a timber lintel. The olive-wood leaf hangs on the south post and stands open into the yard. The lamp niche is a small arch through the north post. At this dawn the clay lamp in it is cold. The stone bench runs along the outer wall north of the north post. The trough stands outside, south of the south post. The house doorway is on the gateway's axis, 34 m west of the gate. The fold, calf pen and ox byre are on the yard's north side. The fold gate is barred. The cistern, ovens and threshing floor lie to the south. The old fig and the hill track are outside, north-east of the gate.

**At this hour, the gate.** A grey jenny stands in the gateway's south half with two leather bags, the silver sewn into the seams. The farm dog lies at the north post. The farm flock is in the chest-high fold. Oven smoke rises straight in the still air. Mist lies in the valley to the east. The millstones are inside the house; the plates show the house, and the stones stay indoors. People are left out of every prompt.

**The bend.** The road east to Jericho rounds the last spur of the hill at (1040, -580) and then runs straight and open toward the east. Boulders sit at the spur's foot. The slope falls south to the valley floor. Morning haze lies over the valley. Dust in the ruts comes from the morning passage along the road. The cloak and the jenny travel with the cast and are not fixtures of the bend, so these plates leave them out.

## Earlier plates

- 01 redraws `sc02_E_the_gate_at_dusk`, file `sc02 25_E_plate`. Same gateway, same road stand, dusk changed to dawn. The cold lamp, the loaded jenny, the dog, the flock, the oven smoke and the mist belong to this dawn.
- 07 redraws `sc02_F_the_valley_at_night`, file `sc02 31_F_plate`. Same valley. The hour changes from deep night to morning, and the stand moves from the high hillside at (-40, 80) to the bend.

Scene 6B's dusk return at the gate is the same place and the same hour as `sc02_E_the_gate_at_dusk`, which `used_by` already lists for 6B, 2 and 8. It is not a third spot in this folder. That earlier field describes a cold wick. The screenplay at this dusk lights the niche. See REPORT.md.

## Look

One natural source at the scene's hour. Dawn at the gate is the sun from 5 degrees. Morning at the bend is the sun from 350 degrees. Deep shadow covers more than a third of each wide view. Muted sun-faded earth, pale warm-grey haze, fine grain, wide lens, deep focus. Each macro ends on the short grain line. Every tool line states 3:2.
