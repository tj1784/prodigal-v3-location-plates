# Scene 4, Eliab's house at supper: location plates

The Prodigal Son v3, 21 Oct 2026. Nothing in this set is approved.

One spot. Six pictures. The place is the owner's 7-by-4-pace room at dusk.

## What to make (6 pictures, in this order)

| # | file | tool | attach | what |
|---|---|---|---|---|
| 01 | prompts/01_A_plate.txt | image_edit 3:2 | the plate of sc02 01_A_plate | THE PLATE: middle of the room, facing the hearth, dusk |
| 02 | prompts/02_A_right.txt | image_edit 3:2 | 01 | quarter turn right, east, through the open door |
| 03 | prompts/03_A_reverse.txt | image_edit 3:2 | 01 | half turn, south, the sleeping bench |
| 04 | prompts/04_A_left.txt | image_edit 3:2 | 01 | quarter turn left, west, jars and the hand mill |
| 05 | prompts/05_A_low_corner.txt | image_edit 3:2 | 01 | lens a hand's breadth above the south-west floor |
| 06 | prompts/06_A_macro.txt | image_edit 3:2 | 01 | the rubbed olive wood of the table and the lamp's clay foot |

01 is redrawn from Scene 2's first plate of this room, so the shell, the walls and the objects stay one design. The hour changes.

## Where the picture stands

Grid: +x east, +y north, metres. Origin is the lamp niche in the north gatepost, (0, 0).

`orbits/sc04/FIELDS.json` is absent. The interior rule puts the camera in the middle of the room, facing the main wall. That is the spot's own stand: `orbit_centre` (-35.8, -1.8), facing 90° (north), the hearth wall. The table's middle is that point.

Digest, `orbit_spots.py --digest sc04_A_eliabs_house_at_supper -35.8 -1.8 90`:

- Front, 90°: water jar 2 m right; oil jars 2 m left; hearth 2 m centre; storage jars 3 m left; lamp niche 3 m left; eaves and yard on the right; yard wall 4 m right; the fold 14 m right. Light: the place light.
- Right, 0°: doorway 2 m centre; water jar 2 m left; yard 2 m centre; fold 12 m left; fold gate 19 m left; yard wall 20 m left; calf pen 28 m left; ox byre 29 m left; cistern 30 m right; threshing floor 33 m right. Light: the place light.
- Behind, 270°: stools 1 m centre; hand mill 2 m right; Asher's mat 2 m left; sleeping bench 2 m right; sling peg 3 m left. Light: the place light.
- Left, 180°: oil jars 2 m right; hand mill 2 m left. Light: the place light.

The digest prints "the place light" because the staging lamp, "The one lamp" at (-35.7, -1.7), sits 0.14 m from the stand point and the digest skips a flame closer than 0.3 m. Its bearing is 45°. From the middle:

- Facing north, the lamp is on the table, ahead on the right.
- Facing east, it is ahead on the left.
- Facing south, it is behind on the left.
- Facing west, it is behind on the right.

That lamp is the only light on the room. A bar of last grey dusk shows through the open east door, and the gate lamp burns 34 m east of the door, small in that opening. Screenplay and design note §2c.

- **Plate (01), 90° north.** Hearth and pot 2 m centre, niche 3 m on the LEFT, storage jars 3 m on the LEFT, oil jars 2 m on the LEFT, water jar 2 m on the RIGHT, the doorway at the RIGHT edge. Yard wall 4 m and fold 14 m lie on the RIGHT past that edge. The lamp lights the hearth from the near table. Beams, jar bases and the doorway hold more than a third of the frame in deep shadow.
- **Right (02), 0° east.** Door 2 m centre, leaf on the LEFT jamb, water jar 2 m on the LEFT. Gate lamp centred in the opening, 34 m east. Fold, fold gate, yard wall, calf pen and ox byre on the LEFT. Cistern and threshing floor on the RIGHT. The lamp is ahead on the left. The yard is the deep shadow.
- **Reverse (03), 270° south.** South wall 2.6 m ahead. Bench 2 m on the RIGHT, mat and sling peg on the LEFT, south stool 1 m centre, hand mill 2 m on the RIGHT. The lamp is behind on the left. Shadows fall forward onto the bench.
- **Left (04), 180° west.** West wall 1.5 m ahead. Oil jars 2 m on the RIGHT, hand mill 2 m on the LEFT, a storage jar at the RIGHT edge, the bench at the far LEFT. The lamp is behind on the right.
- **Low corner (05).** Stands at (-36.85, -3.95), facing 45° (north-east), the lens a hand's breadth above the floor beside the bench. Digest: mill 1 m left; stool 2 m centre; mat 2 m right; table 2 m left; the lamp 3 m left, the view toward the flame; oil jars 3 m left; doorway 3 m right; water jar 4 m left; hearth 4 m left. Near floor and the bench underside are the deep shadow.
- **Macro (06).** Stands at (-35.95, -2.05), facing 30°, a hand's breadth off the table's south-west quarter. Digest: the lamp 0 m on the left, the view toward the flame; the doorway 2 m on the right, outside this close frame.

The digest also lists a track named "Gate lamp, 34 m east" at about 1 m. That track is the sightline drawn on the staging map. Its nearest point lies beside the table. The lamp itself is the niche at (0, 0).

## The locked design

Eliab's house, the owner's map instruction, the same shell Scene 2 drew:

- Strict rectangle, 7 paces by 4, a pace 0.75 m: 5.25 m north to south, 3.0 m east to west. Mud brick, patchy lime plaster, sooted timber beams. Walls about 0.6 m thick.
- FRONT, north: the low fire-blackened hearth ring, the clay cooking pot, the arched lamp niche at shoulder height on the left of that wall.
- RIGHT, east: the metre-wide open timber doorway onto the yard, on the gate's axis. The olive-wood leaf hangs on the north jamb and folds back inside. The clay water jar stands beside the door, to its north.
- BEHIND, south: the low mud-brick sleeping bench, rolled sheepskins and folded wool blankets. The reed mat lies along the east wall. The sling hangs on a peg at the south wall.
- LEFT, west: tall sealed storage jars and the oil jars toward the north; the stone hand mill on its reed mat, with spilled flour, toward the south by the bench.
- Centre: the low heavy olive-wood table, 0.75 by 1.4 m, and four wooden stools. The table's middle is `orbit_centre`.
- At this hour the one clay lamp, bowls and flat bread are on the table. Lamp smoke, a thread of cooking smoke off the pot, and dust from the yard in the doorway's grey. Moths at the gate lamp. Each particle has that cause.
- The room in the plate is empty. The household and the dog under the table belong to the scene's action, and they stay off this location plate.

## Redrawn from

01 comes from `sc02_A_the_house_before_dawn`, the file `sc02/prompts/01_A_plate.txt`. Same stand point, the middle of the room facing the hearth. The hour changes from before dawn to dusk, and the light changes with it: the threshold lamp of that plate gives way to the one clay lamp on the table. Views 02–06 attach 01.

## Look

Bible §4 and the brief's look line. One source on the room, the clay lamp. Real deep shadow over more than a third of the frame. Muted sun-faded earth, pale warm-grey haze, fine grain, wide lens, deep focus. The macro ends on the short line.
