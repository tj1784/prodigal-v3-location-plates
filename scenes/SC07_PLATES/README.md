# Scene 7, the road east and the city: location plates

The Prodigal Son v3, 21 Oct 2026. Nothing in this package is approved.

Six spots, thirty-six pictures. Stand points are Sol's choices in `location-plates/orbits/sc07/FIELDS.json`. Sides and light come from `orbit_spots.py --digest` at those stands, read against `staging/sc07/SC07_STAGING.json`. The staging map PNG was left unread.

## What to make (36 pictures, in this order)

| # | prompt | tool | attach | what |
|---|---|---|---|---|
| 01 | prompts/01_A_plate.txt | image_gen 3:2 | nothing | THE FIRST PLATE: the crest at sunrise, from the south shoulder |
| 02-06 | prompts/02-06 | image_edit | 01 | the crest turned right, reversed, turned left, low corner, macro |
| 07 | prompts/07_B_plate.txt | image_gen 3:2 | nothing | the Jordan ford at noon, from the west bank |
| 08-12 | prompts/08-12 | image_edit | 07 | the ford turned right, reversed, turned left, low corner, macro |
| 13 | prompts/13_C_plate.txt | image_gen 3:2 | nothing | the bare plain at evening, from the north rise |
| 14-18 | prompts/14-18 | image_edit | 13 | the plain turned right, reversed, turned left, low corner, macro |
| 19 | prompts/19_D_plate.txt | image_gen 3:2 | nothing | Kallias's court at night, facing the shrine |
| 20-24 | prompts/20-24 | image_edit | 19 | the court turned right, reversed, turned left, low corner, macro |
| 25 | prompts/25_E_plate.txt | image_edit | 19 | the same court at grey dawn |
| 26-30 | prompts/26-30 | image_edit | 25 | the dawn court turned right, reversed, turned left, low corner, macro |
| 31 | prompts/31_F_plate.txt | image_edit | 19 | the court gate from the street, another night |
| 32-36 | prompts/32-36 | image_edit | 31 | the gate turned right, reversed, turned left, low corner, macro |

01, 07, 13 and 19 are drawn from text. 25 and 31 are redrawn from 19, so the court stays one design. Every other picture is drawn from its own spot's plate.

## Where each picture stands

Grid for the road: +x east, +y north. Grid for the court: +x east, +y north, origin the centre of the open paving.

- **Crest (01, 02-06):** stands at (-16, -4), on the south shoulder, facing 4°. Sunrise from 5°, almost straight down the road.
  - Plate (4°): the road climbs ahead, a scrub tree 10 m on the LEFT, two more beyond the crest (23 m centre, 28 m LEFT). Backlit.
  - Right (274°): open south shoulder. Sun to the LEFT.
  - Reverse (184°): the road west, 4 m ahead on the RIGHT. Sun behind the camera.
  - Left (94°): the north shoulder, the road 3 m ahead in the centre, the near scrub 10 m on the RIGHT. Sun to the RIGHT.
- **Jordan (07, 08-12):** stands at (-12.5, -3), dry ground on the west bank, facing 10°. Noon sun from 270°, high in the south.
  - Plate (10°): the river 3 m ahead on the RIGHT, the ford entry 5 m on the LEFT, the east bank 22 m ahead. Sun to the RIGHT.
  - Right (280°): downstream. The west-bank thicket 3 m on the RIGHT, the current 4 m on the LEFT. Backlit.
  - Reverse (190°): the dry west approach, the bank 4 m ahead on the RIGHT. Sun to the LEFT.
  - Left (100°): upstream. The ford and the water on the RIGHT, the bank on the LEFT, the north tamarisk 9 m in the centre. Sun behind the camera.
- **Plain (13, 14-18):** stands at (-14, 25), the low rise north of the road, facing 330°. Evening sun from 195°.
  - Plate (330°): the near thorn 2 m on the RIGHT, the road 27 m on the RIGHT, three further thorns on the RIGHT, the dust whirl a little to the LEFT, the city 3 km ahead on the LEFT. Sun behind on the RIGHT.
  - Right (240°): the western road 27 m on the LEFT. Sun ahead on the RIGHT.
  - Reverse (150°): open upper rise. Sun ahead on the LEFT.
  - Left (60°): open ground to the north-east. Sun behind on the LEFT.
- **Court at night (19, 20-24):** stands at (-4, 0), on the open paving, facing 0° (east, toward the shrine). The brazier is the great flame.
  - Plate (0°): the mat 4 m on the LEFT, the table 10 m in the centre, the brazier 15 m in the centre, Tyche 18 m in the centre, the wall 14 m on the LEFT. Brazier ahead, the view backlit. The southern lamp is ahead on the RIGHT, 9 m.
  - Right (270°): the south colonnade, the service door 13 m on the RIGHT, the street 15 m on the RIGHT. Brazier to the LEFT. Southern lamp ahead on the LEFT.
  - Reverse (180°): the gate 11 m in the centre, the leaf on the RIGHT of the opening, the beggar's corner 12 m in the centre, the service door 14 m on the LEFT, the houses 17 m in the centre. Brazier behind the camera. Southern lamp behind on the LEFT.
  - Left (90°): the north colonnade, the columns 8 m on the RIGHT, the mat 4 m on the RIGHT, the street 15 m on the LEFT. Brazier to the RIGHT. Southern lamp behind on the RIGHT.
- **Court at dawn (25, 26-30):** redrawn from 19. Stands at (-3.95, 0.25), five centimetres east and twenty-five centimetres north of the night stand, still facing 0°. Grey dawn from 5°.
  - Plate: the same axis. Mat on the LEFT, table in the centre, brazier and Tyche in the centre. Dawn ahead, the view backlit. Ash travels west, toward the lens.
  - Right (270°): south walk, service door on the RIGHT. Dawn to the LEFT. Ash crosses toward the right.
  - Reverse (180°): the gate in the centre, lit from the front. Ash travels away west.
  - Left (90°): north colonnade, mat on the RIGHT. Dawn to the RIGHT. Ash travels toward the left.
- **Court gate, another night (31, 32-36):** redrawn from 19. Stands at (-19.5, 0), on the street 4.5 m west of the gate, facing 0°.
  - Plate (0°): the gate 4 m in the centre, the leaf on the LEFT inside the opening, the beggar's corner 4 m on the LEFT in deep shade, the brazier 30 m in the centre, Tyche 33 m in the centre, the lamps 22 m on the RIGHT. Backlit through the gate.
  - Right (270°): south along the street. Court wall on the LEFT, houses 2 m on the RIGHT. Flame light from the LEFT.
  - Reverse (180°): the opposite house front, about 1 m ahead, lit from the front by the gate behind the camera.
  - Left (90°): north along the street. Houses on the LEFT, court wall on the RIGHT. Flame light from the RIGHT.

## The locked design

- **The crest:** a three-metre earth road over a low limestone ridge, shallow wheel grooves, three scrub trees (one on the north shoulder west of the brow, two east of it), three low limestone boulders, the east slope falling to the misted Jordan valley. Sunrise at 5°, long shadows west.
- **The ford:** the Jordan flowing south, brown and quick, a shallow knee-deep crossing from the west bank to the east. Two tamarisks on each bank, the thickest just south of the west entry. High noon sun from the south, short shadows north.
- **The plain:** a bare ochre plain, a three-metre road running east, one thorn on the north rise and three on the plain, a wind-driven dust whirl, and a low walled city with flat roofs about three kilometres east, its first lamp points coming on. Evening sun from the west-south-west, shadows long toward the city.
- **The court:** a Greek peristyle, thirty metres east to west and twenty-one north to south, twenty-six limestone columns (nine on each long side, four between the corners on each short end), clay tile over the walks. The open shrine of Tyche at the east end, the crowned stone figure on its plinth, the round bronze brazier on the axis west of it. One gate in the west wall, two metres twenty wide, the iron-bound leaf hinged on the north jamb and opening inward. A service door in the south wall near its west end. Couches and low tables, the main couch and the olive-wood table on the axis, flutes and a drum on the reed mat north of the axis, cups, tablet, stylus, purse, silver and a wine spill on the table. Outside, a paved street and the houses across it. At the north side of the gate, a worn stone corner with one empty clay bowl.
- **Night:** the brazier is the great flame. The colonnade lamps and the two torches inside the gate jambs are smaller flames of the same amber, because the screenplay lights the court with torches and lamps as well as the brazier. Deep shade holds the walks between those pools.
- **Dawn:** grey light over the shrine wall, a hot wind out of the east. The brazier holds pale ash and the lamp bowls hold spent wicks. The ash trail runs west.
- **The gate night:** the same court, seen from the street. Flame light comes through the open gate. The bowl corner stays in deep shade.

The plates are empty. The road keeps its earth, water, trees and dust. The court keeps its furniture, fire and bowl.

## Redrawn plates

- 25, the court at dawn, is redrawn from 19, the court at night (`sc07_D_kalliass_court_at_night`). The hour changes from night to grey dawn, and the stand shifts five centimetres east and twenty-five centimetres north.
- 31, the gate on another night, is redrawn from 19. The hour stays night. The stand moves from the paving inside the court to the street, four and a half metres west of the gate.
