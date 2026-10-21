# Scene 9, when he had spent all: short location prompts

The Prodigal Son v3, 21 October AD 2026. These are text deliverables for review; nothing in this package is approved. Eighteen future pictures, three spots. No images were made or attached.

## What to make (18 pictures, in this order)

| # | prompt | tool | attach | what |
|---|---|---|---|---|
| 01 | prompts/01_A_plate.txt | image_edit 3:2 | sc07 19_D_plate | The last feast: whole court from open paving, facing the shrine |
| 02 | prompts/02_A_right.txt | image_edit 3:2 | 01 | South: service door centre, wall and street on the right |
| 03 | prompts/03_A_reverse.txt | image_edit 3:2 | 01 | West: the gate, the moon ahead, the beggar's corner on the right |
| 04 | prompts/04_A_left.txt | image_edit 3:2 | 01 | North: wall, street and house fronts on the left |
| 05 | prompts/05_A_low_corner.txt | image_edit 3:2 | 01 | Low on the paving: table left, brazier and Tyche ahead |
| 06 | prompts/06_A_macro.txt | image_edit 3:2 | 01 | The brazier's soot-darkened bronze lip |
| 07 | prompts/07_B_plate.txt | image_gen 3:2 | text alone | The rented room from its middle, facing the shutter wall |
| 08 | prompts/08_B_right.txt | image_edit 3:2 | 07 | West wall; shutter and noon bars on the left |
| 09 | prompts/09_B_reverse.txt | image_edit 3:2 | 07 | North wall; the cold lamp in its niche |
| 10 | prompts/10_B_left.txt | image_edit 3:2 | 07 | East wall; water jar left, travel bags and the door right |
| 11 | prompts/11_B_low_corner.txt | image_edit 3:2 | 07 | Low at the stripped bed, toward the shutter |
| 12 | prompts/12_B_macro.txt | image_edit 3:2 | 07 | The shutter's weathered timber and one bar of noon |
| 13 | prompts/13_C_plate.txt | image_gen 3:2 | text alone | The famine street, both stall rows, bare bins, the board |
| 14 | prompts/14_C_right.txt | image_edit 3:2 | 13 | Into the south stalls, sun ahead on the right |
| 15 | prompts/15_C_reverse.txt | image_edit 3:2 | 13 | Back west into the sun; the stone step on the left |
| 16 | prompts/16_C_left.txt | image_edit 3:2 | 13 | Into the north stalls, sun behind on the left |
| 17 | prompts/17_C_low_corner.txt | image_edit 3:2 | 13 | Low at the bare bins |
| 18 | prompts/18_C_macro.txt | image_edit 3:2 | 13 | The bare bin's split timber and grit |

01 is redrawn from Scene 7's court plate. 07 and 13 are drawn from text. Every other picture of a spot uses only that spot's own plate. The attachment lines describe future generation; this task performs none.

## Where each picture stands

Grid for every place: +x east, +y north, metres. Bearings run counterclockwise from east: 0 degrees east, 90 north, 180 west, 270 south. A quarter turn right subtracts 90 degrees. `orbits/sc09/FIELDS.json` does not exist, so each plate starts from its orbit spot and then takes the brief's stand: an interior at the middle facing the main wall, an exterior on open ground with the whole place in frame.

### A. The last feast — `sc09_A_the_last_feast`

`kallias_court:ext`, night, redrawn from `sc07_D_kalliass_court_at_night`. The orbit camera is setup S02 at (-5.65, -2.7), facing 228 degrees, a seated view of the tablet. That facing looks southwest at the service door, with the shrine behind the lens. The plate stands at (-10, 0), on the open paving ten metres west of the court centre, facing 0 degrees, due east, so the colonnades, the table, the brazier and Tyche are in one frame. Quarter turns stay there. The low lens and the macro move.

The moon's `from_deg` is 185, low in the west over the gate. The brazier is the one flame.

| file/view | camera (x, y) m | facing | digest landmarks | light |
|---|---|---|---|---|
| 01 plate | (-10, 0) | 0, east | Mat 9 m left; columns 12 m left; wall 14 m left; lamps 14 m right; table 16 m centre; brazier 21 m centre; shrine 22 m centre; Tyche 24 m centre | Moon behind the camera, the view lit from the front. Brazier ahead, the view backlit. Lamps ahead on the right |
| 02 right | (-10, 0) | 270, south | Paving 3 m right; wall 7 m right; street 7 m right; service door 11 m centre; houses 14 m right | Moon to the right. Brazier to the left, 21 m. Lamps ahead on the left |
| 03 reverse | (-10, 0) | 180, west | Paving 2 m centre; gate 5 m centre; wall 5 m right; street 5 m centre; beggar's corner 6 m right; houses 11 m centre | Moon ahead, the view backlit. Brazier behind the camera. Lamps behind on the left |
| 04 left | (-10, 0) | 90, north | Paving 3 m left; wall 7 m left; street 7 m left; houses 14 m left | Moon to the left. Brazier to the right, 21 m. Lamps behind on the right |
| 05 low corner | (4.2, -1.5) | 18 | Table 3 m left; brazier 7 m centre; paving 8 m right; shrine 8 m right; Tyche 9 m centre; wall 11 m right | Moon behind the camera. Brazier ahead, backlit. Lamps behind on the right |
| 06 macro | (10.8, -0.85) | 90, at the bronze lip | Brazier 1 m centre; the lip fills the frame | Brazier ahead, backlit. Moon to the left |

The long couch at (4.8, 0) is unlabelled, so the digest omits it. On the plate it lies on the centre line, about fifteen metres ahead, just west of the table. The couch north of the table is on the LEFT; the couch south of the table is on the RIGHT. The gate leaf hinges on the north jamb and swings inward: facing west, that leaf is on the RIGHT. The two small torches inside the jambs are on the LEFT (south) and the RIGHT (north) in the reverse.

### B. The rented room — `sc09_B_the_rented_room`

`sc09:The rented room`, day, drawn from text. The orbit camera is S07 at (2.2, 2.25), facing 265 degrees, half a metre north of the middle. The room runs from (0, 0) to (4.2, 3.4), origin the south-west inner corner. The plate stands at the middle, (2.1, 1.7), facing 270 degrees, due south, at the wall that holds the shutter and the door. Noon sun `from_deg` 270, through the slats and the open door.

| file/view | camera (x, y) m | facing | digest landmarks | light |
|---|---|---|---|---|
| 07 plate | (2.1, 1.7) | 270, south | Bed 1 m right; shutter 2 m right; door 2 m left; yard 2 m centre; manger 5 m left | Ahead, the view backlit |
| 08 right | (2.1, 1.7) | 180, west | Noon bars 1 m left; shutter 2 m left; yard 3 m left; room 2 m right | Sun to the left |
| 09 reverse | (2.1, 1.7) | 90, north | Cold lamp 2 m centre; room 2 m centre | Behind the camera, lit from the front |
| 10 left | (2.1, 1.7) | 0, east | Bags 2 m right; water jar 2 m left; door 2 m right; yard 3 m right | Sun to the right |
| 11 low corner | (1.7, 1.15) | 265 | Bed 1 m right; shutter 1 m centre; room 1 m left; yard 1 m centre; manger 5 m left | Ahead, backlit |
| 12 macro | (0.95, 0.35) | 270, on the shutter | Shutter fills the frame | Ahead, backlit |

The jenny is tethered at (3.8, -2.4). From the plate and from the low lens she is on the LEFT, about four metres off, inside the field of view, beside the manger. She is outside the field of the three quarter turns, so those prompts leave her out.

### C. The famine market — `sc09_C_the_famine_market`

`sc09:The famine market`, day, drawn from text. Origin is the merchant's board. The orbit camera is S10 at (-1.3, -0.9), facing 35 degrees, a close view of the board. The plate stands in the open roadway at (-16, -2.3), facing 8 degrees, a little north of east, so both stall rows, the loose shutter, the bare bins and the board are in one frame. The staging wide S09 sits on the stone step against the south stalls; this stand is in the street so the two rows read together. Sun `from_deg` 215, hard pale afternoon through grit. The hot dry east wind drives the grit west.

| file/view | camera (x, y) m | facing | digest landmarks | light |
|---|---|---|---|---|
| 13 plate | (-16, -2.3) | 8 | Street and north stalls 3 m left; loose shutter 4 m left; south stalls 4 m right; bare bins 7 m right; board 16 m centre | Behind the camera, lit from the front |
| 14 right | (-16, -2.3) | 278 | Street and stalls 3 m centre; mouths at 3 m centre, 4 m right, 4 m left | Ahead on the right |
| 15 reverse | (-16, -2.3) | 188 | Street and stalls 3 m left; mouth 4 m left; stalls and mouth 4 m right; stone step 5 m left | Ahead, the view backlit |
| 16 left | (-16, -2.3) | 98 | Street and stalls 3 m centre; mouth 3 m centre and 4 m left | Behind on the left |
| 17 low corner | (-9.5, -3.7) | 270, south at the bins | Bare bins 1 m centre; street 1 m right; stalls 1 m left | Ahead on the right |
| 18 macro | (-9.5, -4.35) | 270, on the bin rim | The rim fills the frame | Ahead on the right |

## The locked design

**Kallias's court.** A Greek peristyle, thirty metres east to west and twenty-one metres north to south, the open paved court twenty-four by fourteen and a half. Twenty-six limestone columns, clay-tile roofs over the walks, an open stone shrine of Tyche at the east end, the crowned effigy at (13.5, 0), the round bronze brazier at (10.8, 0). The west gate is a 2.2 metre opening; its iron-bound leaf hinges on the north jamb and opens inward. A service door pierces the south wall near the west end. Outside is a paved street and the house fronts. The feast furniture stays where Scene 7 set it: the long couch west of the low table, side couches, cups, a wax tablet and stylus, the musicians' mat with flutes and a drum, lamps in the colonnade bays, a torch inside each gate jamb. On this night the long couch stands cleared. The air is smoke from the brazier and the lamps. The thin new moon is the hour's change; the brazier remains the one flame.

**The rented room.** 4.2 by 3.4 metres. South wall: slatted timber shutter on the west, open timber door on the east, the white yard beyond, a manger and the tethered jenny. Stripped corded bed under the shutter. East side: corded travel bags and a clay water jar. North wall: a cold clay lamp in a niche. One light, the noon sun through the slats and the door. Dust in the bars has the yard as its cause.

**The famine market.** A long street between two rows of shuttered stalls. The loose shutter is on the north row. The grain stall's bins stand bare on the south side, flies on the rims, the cause the bare grain. The merchant's board stands in the street with a bare top. A stone step marks the west end. The hot dry east wind drives the grit west. The picture shows the bare stall in place of millstones. The afternoon sun is the one light.

People are omitted. The jenny stays, because the room keeps her tethered at the manger at this hour.

## Earlier plates

- 01 comes from `sc07 19_D_plate`, Scene 7's fourth spot, `sc07_D_kalliass_court_at_night`, the first plate of this court. What changes is the stand point and the thin new moon. The architecture, materials and objects stay.
- 07 and 13 have an empty `from`. Their views attach 07 and 13.

The gate-night beat of Scene 9 is `sc07_F_the_court_gate_another_night`. Its `scene` field is 7, so it is outside this package. These eighteen files cover the three spots whose `scene` is 9.

## The look

One source at the real hour: the brazier at the feast, the noon door and shutter in the room, the afternoon sun on the market. Deep shadow over a third of each wide frame. Muted sun-faded earth, pale warm-grey haze, fine grain, wide lens, deep focus. Each macro ends on the shorter grain line. 3:2 is in every tool line. This task is words only, so no photographic measurement is claimed.

Read: the short-prompt brief; the Scene 1 plate package; `ORBIT_SPOTS.json`; `orbits/sc09/SPOTS.md`; `SC09_STAGING.json` and its map; `staging/places/kallias_court.json`; the screenplay from the Scene 9 heading through the gate night; design note sections 2c and 2d; the owner's map instruction on Kallias's court; cinematography bible section 4. Every view's sides were taken from `orbit_spots.py --digest` at the stand in the tables above.
