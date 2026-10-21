# Scene 0, the road under the field wall: location plates

The Prodigal Son v3, 21 October AD 2026. Nothing in this set is approved.

## What to make (6 pictures, in this order)

| # | prompt | tool | attach | what |
|---|---|---|---|---|
| 01 | prompts/01_A_plate.txt | image_gen 3:2 | text alone | THE FIRST PLATE: the roadside, wall, tamarisk, barley and falling slope at white noon |
| 02 | prompts/02_A_right.txt | image_edit 3:2 | 01 | quarter turn right: the gap, the yard and the farmhouse |
| 03 | prompts/03_A_reverse.txt | image_edit 3:2 | 01 | half turn: the road east and the slope down to the wadi |
| 04 | prompts/04_A_left.txt | image_edit 3:2 | 01 | quarter turn left: down the scree-and-thorn slope |
| 05 | prompts/05_A_low_corner.txt | image_edit 3:2 | 01 | a hand's breadth above the ditch, along the wall toward the tamarisk |
| 06 | prompts/06_A_macro.txt | image_edit 3:2 | 01 | one worn fieldstone lip fills the frame |

- Spot `sc00_A_the_road_under_the_field_wall` is the only Scene 0 entry. `from` is empty, so 01 is drawn from text.
- 02–06 attach 01, this spot's plate, as the only reference. Same design, same noon.
- Use each prompt word for word.

## Where the picture stands

Grid of `staging/places/foreign_farm.json`: +x east, +y north, metres, origin the tamarisk trunk at the ditch. Bearings: east 0°, north 90°, west 180°, south 270°. A quarter turn right subtracts 90°.

`orbits/sc00/FIELDS.json` sets the plate on open ground at (17, -3.5), facing 160°. The staging camera at (8.75, -0.25), facing 265°, is the teaser's close setup and stays as staged. The sun is the white noon sun, high in the south, `from_deg` 270. Shadows fall north on the ground in every view.

Digest command, exit 0: `orbit_spots.py --digest sc00_A_the_road_under_the_field_wall 17 -3.5 160`. It prints all four turns. Two further digests, both exit 0, cover the low corner and the macro heading.

| view | stands | faces | sun in this view | shadows |
|---|---|---|---|---|
| 01 plate | (17, -3.5) | 160°, west-northwest | high, behind on the LEFT | north, toward the RIGHT, onto the barley |
| 02 right | (17, -3.5) | 70°, north-northeast | high, behind the camera; the view lit from the front | away from the camera, slightly LEFT |
| 03 reverse | (17, -3.5) | 340°, east-southeast | high, ahead on the RIGHT | toward the camera and LEFT |
| 04 left | (17, -3.5) | 250°, south-southwest | high, ahead and slightly LEFT; the slope backlit | toward the camera and slightly RIGHT |
| 05 low corner | (8.5, 0.3) | 180°, west | high, to the LEFT | north, toward the RIGHT |
| 06 macro | same wall foot | into the southern face of one stone (sun heading 90°) | high, above and behind the camera | north, into the stone's recesses |

### Sides written from the digest

Distances are the digest's nearest sample, rounded.

- **01.** Road RIGHT 1 m. Slope LEFT 2 m. Ditch RIGHT 3 m. Gap and track RIGHT 5 m. Wall, barley and stubble RIGHT 8 m. Tamarisk near the centre, slightly LEFT, 17 m. Green fold RIGHT 27 m. Yard RIGHT 31 m.
- **02.** Road LEFT 1 m. Ditch LEFT 3 m. Stubble and gap LEFT 5 m. Track LEFT 8 m. Barley LEFT 13 m. Fold LEFT 26 m. Yard LEFT 30 m. Oven LEFT 41 m. House LEFT 44 m. Pantry door and bar LEFT 45 m. Vine table LEFT 45 m. Burnt ground continues on the RIGHT.
- **03.** Slope RIGHT 1 m. Road LEFT 2 m. Ditch LEFT 6 m. Thorn clump RIGHT 8 m. Stubble LEFT 9 m. Thorn near the centre 17 m. Thorn scrub RIGHT 45 m. Wadi RIGHT 86 m.
- **04.** Slope LEFT 1 m. Thorn RIGHT 17 m and near the centre 18 m. Thorn scrub LEFT 42 m. Sun ahead, slightly LEFT.
- **05.** Ditch, wall, barley and stubble RIGHT. Road LEFT 4 m. Slope LEFT 7 m. Tamarisk near the centre 9 m. Thorn LEFT 20 m. Fold RIGHT 28 m, a band above the wall.
- **06.** The heading-90 digest puts the sun behind the camera. The frame is the stone, so the farm that digest lists stays outside the crop.

The digest prints fourteen items. The same bearing test, inside the 104° field, puts these farther landmarks on the plate's RIGHT, and the prompts name them there: the well, the vine table, the main doorway, the clay-deity niche and the farmhouse. The bread oven and the pantry fall outside that plate field, so they appear in 02, on the LEFT, where the digest sees them. The well falls outside 02's field, so 02 leaves it out. At the low corner the near wall hides the yard, so 05 names the fold above the crest and leaves the hens to 01 and 02.

## The locked design

- **Road.** East-west, 3.8 m wide, centre near y = -2.5. Southern lip near y = -4.4. Pale grit, wheel-worn earth.
- **Ditch.** Shallow and dry, about 1.15 m wide, between the road and the wall. Exposed stones, root fibres, fallen twigs.
- **Wall.** Waist-high, loosely piled fieldstone, about 0.9 m thick, along y = 1.0. The short noon shadow falls on the barley side. The road stays in the sun.
- **Gap and track.** The opening runs from (11, 1) to (14.5, 1), 3.5 m. A 2.5 m earth track climbs north through it.
- **Tamarisk.** One trunk at (0, 0), about 0.35 m thick, low crown about 7.6 m across, dusty olive-grey sprays, roots in the ditch.
- **Field.** Last standing barley north of the wall and west of the gap. Pale cut stubble around it and east of the gap.
- **Slope.** South of the lip, burnt-brown scree and thorn, a grey thorn belt from about y = -46, the dry wadi near y = -86.5.
- **Farm.** The green fold is on its own spring. The yard keeps a few hens, standing still. The low farmhouse is fieldstone, mud brick, worn lime plaster, and a flat timber, reed and earth roof, from x = -14 to 9.5 and y = 40 to 47. The well is at (-18, 33). The long table is under the vine at (-6, 35.2). The bread oven is at (12, 37); on 02 a thin thread of smoke rises from it. The main doorway is at (-6, 40), the clay deity in its niche just east of that door, an oil dish on the sill. The pantry door at (6.75, 40) stands open, its timber bar beside it.
- **Air.** Grit lifts off the road and the scree in a dry breeze. The oven smoke has the oven as its cause. The haze is the noon haze.
- **Macro.** One pale fieldstone on the southern face: rubbed lip, mineral grains, pits, a hairline fracture, road dust in the recesses.
- **Empty of people.** The teaser's beating stays out of these plates. The screenplay's place at this hour is the field wall, the dust and the white noon, on the shared foreign farm.

## Earlier plates

`from` is empty. 01 is the first plate of this place in this run, drawn from text. 02–06 come from 01. Scene 0 has no cross-scene attachment.

## Screenplay, map and look

The locked screenplay opens on this road at noon, then cuts to the hillside. These six pictures are the empty location for that opening. Eliab's room, Kallias's court and the pig fields are other places; this spot uses the foreign-farm map.

Bible §4 and the brief: one high southern sun, deep shadow across a third of the frame or more, muted sun-faded earth, a pale warm-grey haze, fine grain. Wider views end on the long look line. The macro ends on "Muted sun-faded earth colours, fine film grain."

Body lengths: 230, 229, 221, 220, 223 and 150 words.
