# Brief: one scene's staging atlas with camera motion

The owner (21 Oct 2026): "PLS GENERATE THE VISUAL MPAS FOR THE REST OF THE SCENES WITH CAMERA MOTION FIRST DEPLOY 1 OPUS MAX PER SCENE".

Scene 1 is done. Its atlas is `staging/svg/SC01_STAGING_MAP_svg.png`, and its data in this format is `staging/atlas/example_sc01.json`. You make the same thing for your scene:

- every place of the scene, drawn top-down to scale;
- everyone in it, with their facings and their walking paths;
- the camera setups;
- every H3 window's camera path in time, plus the joins between windows (continue, hidden stitch, whip or cut).

Every line of the scene must be spoken verbatim inside the windows. This is a plan on paper: nothing is generated or rendered on H3.

Paths below are relative to `D:/Projects/Premiere316_v4.1/work/prodigal-v3-20261019/`. Python is `D:/Dev/Tools/Python312/python.exe -I`.

## The owner's map instruction (binding, verbatim, 21 Oct 2026)

These words come before everything else in this brief.

- "Physical walking paths must be drawn as solid technical lines. Distant viewpoint relocations across large spaces (such as whip-pans or mantle stitches) must be represented as elegant, dashed gold loops (#D4AF37)."
- "SCENE 02 MAP (Eliab's Farmhouse Main Room): Map a strict, rectangular farmhouse interior shell measuring exactly 7 paces long by 4 paces wide. Wall Orientations (Ref2VA 360° Plan):
  - FRONT Wall: Must contain the low fire-blackened hearth ring, clay cooking pot, and the arched lamp niche.
  - RIGHT Wall: Must contain the open timber doorway opening out onto the dark yard wall, with the clay water jar beside it.
  - BEHIND Wall: Must contain the low mud-brick sleeping bench stacked with rolled sheepskins and folded wool blankets.
  - LEFT Wall: Must contain the tall sealed clay storage jars, oil jars, and the stone hand mill resting on a reed mat with spilled flour.
  - Center Space: Place the low, heavy olive-wood table and wooden stools exactly in the middleground, perfectly anchoring the 360° camera orbit turns."

  This is the room of every scene in Eliab's house (2, 4, 14, 15). The coordinator's reading:
  - a pace is 0.75 m, so the interior is 5.25 m by 3.0 m;
  - the long axis runs from the hearth (front, the north end wall) to the bench (behind, the south end wall);
  - the doorway is in the right long wall, facing east onto the yard, so the gate lamp shows through it;
  - Asher's mat and the sling peg are at the bench wall.
- "ALL SUBSEQUENT SCENE MAPS (Harvest Fields, Kallias's Court, Pig Fields, etc.): Extrapolate the boundaries dynamically from the script text. The Pig Fields must feature a stark, bare field geometry with carob troughs and a distant thorn scrub boundary. Kallias's Court must feature a premium multi-column Greek layout with an open stone shrine of Tyche and a blazing central brazier."
- "Every map must feature a prominent, beautiful typographic header band" and "an embedded, scannable data panel or legend at the bottom grid line, cleanly indexing all nodes, camera markers, and metrics without overlapping the staging graphics." The renderer draws both; keep the spec clean so nothing overlaps.
- "Output a single, continuous SVG block containing all maps arranged neatly, or layered cleanly via interactive tabs." The coordinator assembles every scene's map into one tabbed SVG; you deliver your scene's spec and map.

Follow the cinema bible and the screenplay (owner, 21 Oct: "MAKE SURE FOLLOW THE CINEMA BIBLE AND SCREENPLAY").

## Read first, in this order

1. `staging/atlas/ATLAS_SPEC.md`: the format and the checks.
2. `staging/atlas/example_sc01.json` and its map `staging/atlas/example_sc01_STAGING_MAP.png`: a finished scene.
3. Your scene's section of the main screenplay, `The Prodigal Son v3 - screenplay (19 Oct 2026).fountain`: from its `#N#` heading to the next. The cold open is lines 8–14, before `#1#`.
4. `PRODIGAL_V3_DESIGN_NOTE.md`:
   - §2c, the world (the geography, the air and the sound of each place);
   - §2d, the look and the camera (and the "Signature moves" table);
   - §2e, the cold open and the road home;
   - §3, the people;
   - your scene's row in §5.
5. `D:/Projects/Premiere316_v4.1/work/revenant-cinematography-20261017/REVENANT_CINEMATOGRAPHY_BIBLE.md`:
   - §5, the movement grammar;
   - §11, H3 speech in a long take;
   - §13, the template (so you know what a window must be able to carry);
   - §14, Scene 1's paths and stitches, and the 27 m constraint.
6. The shared places your scene reads, in `staging/places/`.

## What you make

All of it goes in your own folder, `staging/scNN/`. The cold open is `sc00`; the lettered scenes are `sc01a`, `sc04a`, `sc06a` and `sc06b`.

- `SCNN_STAGING.json`: the spec. `check_atlas.py` must print `ok`. Read every warning, and fix it or say why it stands.
- `SCNN_STAGING_MAP.svg` and `.png`, from `render_atlas.py --png`.
- `REPORT.md`, at most 20 lines, as FILES / CHECKS / RESULT / OPEN. RESULT gives:
  - the scene's minutes against the design note's budget;
  - the windows;
  - the joins.

  OPEN lists any screenplay conflict you found, and anything the renderer could not draw.
- A shared place file in `staging/places/` only if this brief makes you its owner.

## How to stage it

1. **Place.** For each place of the scene:
   - draw what the screenplay and the design note put there, at real sizes (a doorway 0.9 m, a table 0.8 m wide, a person's seat 0.6 m, a sheep 1.2 m);
   - put the light where the scene's hour puts it;
   - use the grid conventions below.
2. **People.**
   - Put everyone where the action needs them at the plan's start, facing where they look. Named cast get `named: true`; animals get `animal: true`.
   - Draw a walking path for everyone who moves.
   - Crowds are loose groups with walkable gaps, never rows or lineups.
   - Eyes look past the lens.
3. **Windows.** Cut the scene into H3 windows in screenplay order.
   - One speaker per window. Every dialogue block goes whole inside one window, verbatim.
   - Silent action gets windows too: every beat of the screenplay's action happens inside some window.
   - Choose each length from the 17n+5 list. Leave time for the action around the line: a breath before it, a reaction after it.
4. **Camera.** Each window is one handheld operator on a spherical 14 mm lens, with real travel: a stride, an arm's length, a quarter-circle arc, a long pull-back. Heights change with a reason.
   - Follow the bible's movement grammar: motivated travel, the baton pass, elastic distance, human height and gravity, speed changes.
   - Use stillness only by choice.
   - The design note's signature move for your scene is binding where it applies.
   - Keys give the path: where the camera is, where it looks, at what height, at what second. Add a `note` where a reader needs it ("down into the bread in his hands").
5. **Joins.**
   - Stitch windows into long takes. Use `continue` (exact same pose) or an occluder (the real cloth, bread, shoulder, post or flare that fills the lens, in the same material, direction and speed on both sides).
   - A whip turns the view. It never carries the operator far: a relocation of more than a few metres is a cut or a hidden stitch.
   - Hard cuts are for a change of place or a deliberate break.
6. **Check, render, look.**
   - Run `check_atlas.py` until it prints `ok`, then `render_atlas.py --png`.
   - Look at the PNG. For details, view crops of it that you write with PIL to `staging/scNN/check/`; never edit the map itself.
   - Fix overlaps, crowded labels and unreadable areas through the spec: insets, `extent`, `join_bows`, `number_people`, `label_at`. Then render again.

## Owner rules (binding)

- **The screenplay is locked.** Stage it exactly as written: its words, its order, its people. Never edit it, and never re-word a line. If something cannot be staged as written, or contradicts the design note or another scene, say so under OPEN.
- **"The Nahum scene" (6A)** is locked text ("DONT TOUCH IT").
- **The teacher** is "the teacher" everywhere in the spec. Only the screenplay's `JESUS` cue appears, as the speaker id.
- **Prose fields** (`does`, `what`, `note`) use positive words only and no colons. The checker refuses the rest.
- **FLASH lines** are inserts cut in Resolve from the scene they belong to; they are not windows.
  - Name where each one cuts in, inside the `does` of the window it interrupts.
  - If your scene is the source of a flash used elsewhere, make sure that moment is inside one of your windows:
    - Sc 2, the old hand cupping the new flame at the gate at dusk;
    - Sc 6B, Amos holding out the cloak at the bend;
    - Sc 9, the purse tipped over the palm, one coin;
    - Sc 10, the pigs at the trough, the hand drifting to the husks;
    - Sc 12, the dog trotting off with the bread.
- **Write only inside your own folder** (and your shared place file, if you own one).
  - No other file changes: not the screenplay, not `staging/atlas/*`, not another scene's folder, nothing under `ComfyUI/`.
  - No image generation, no H3, nothing queued, no network, no deletions, no subagents.
  - Never stop to ask; decide, and record the decision in `notes` or the report.

## Grid conventions and shared places

All outdoor places except the hillside use **+x east, +y north**, with metres on the ground. The sun's `from_deg` then follows the hour:

| hour | sun `from_deg` |
|---|---|
| sunrise | about 0–10 |
| morning | about 330 |
| noon | 270, high |
| afternoon | about 210 |
| evening and dusk | about 190–200 |
| sunset | about 180 |

**Hillside above the lake** (`places/hillside.json`, done). Used by scenes 1, 4A, 11 and 16.
- Its own grid: +x toward the gate, +y downhill to the lake, the seat at (0, 0), the gate at (27, 0).
- The sun stays at about 130–145° from late afternoon through sunset, lower and redder.
- The same 33 people as Scene 1 (copy them from `example_sc01.json`): the same groups, moved only where the screenplay moves them.
- Anchors:
  - the fire of Scenes 11 and 16 burns at `fire_sc11_sc16` (3.2, −0.4);
  - Eleazar's loose stone on top of the wall, 4A and 16, is `loose_stone_sc4a_sc16` (27, 2.6), with Eleazar outside the wall.

**Eliab's valley, farm and house.** Owned by Scene 2: it writes `places/eliab_valley.json`, `places/eliab_farm.json` and `places/eliab_house.json`. Scenes 3, 4, 5, 6B, 8, 10, 13, 14 and 15 read them.
- **One frame for all three:** +x east, +y north, origin (0, 0) at the lamp niche in the gatepost.
- **The farm** sits on a terrace on the valley's north side. From west to east: the house at the west end of the yard, the yard with the fold inside it, then the one gate in the yard wall, facing east down the road. Around it:
  - the stone bench by the gatepost (Sc 5);
  - the trough by the gate (Sc 8, the traveller's camel);
  - the calf pen (Sc 8);
  - the ovens and the millstones;
  - the threshing floor on the terrace's south edge, open to the evening wind and the valley (Sc 2, 3, 8);
  - the eaves where Asher lies on his mat outside the house wall (Sc 2);
  - the doorway, which matters in Sc 2, 4, 14 and 15: half in the light, the gate lamp visible from inside.
- **The house** (`eliab_house`) is the owner's main room at the top of this brief: exactly 7 by 4 paces, the four walls as he gives them, and the low olive-wood table and stools in the middle, at the `orbit_centre` anchor. The supper (Sc 4) and the feast (Sc 14) fit inside it; a full room is crowded.
- **The valley** (`eliab_valley`, about 2 km across, not to scale beyond that):
  - The village lies below to the south-east, about 400–700 m from the gate, with its well inside and its gate (where the elders sit) facing up the hill path to the farm.
  - The road east leaves the farm gate, passes the village gate and winds east down the valley toward Jericho. About a mile of it is visible from the farm gate (Luke 15:20).
  - The bend where Amos catches Asher (Sc 6B) is on that road past the village; beyond it the road runs straight and open into the east.
  - The far field (Sc 15) lies on the lower terraces south-west of the house, in earshot of the music.
  - Other farms sit on the next terraces.
  - Give anchors for at least: `gate_lamp`, `bench`, `fold`, `threshing_floor`, `house_door`, `village_gate`, `well`, `bend`, `far_field`, `meeting_point` (Sc 13, where father and son meet on the road, below the village).
- **The evening wind** blows from the west, down the valley: chaff goes east and downhill (Sc 3).

**The foreign farm on the road west.** Owned by Scene 1A: it writes `places/foreign_farm.json`. Scenes 0, 1A and 12 read it.
- The road west runs along a field wall of piled field stones, with a single tamarisk over the ditch by the wall.
- Inside the wall:
  - stubble and the last strip of standing barley;
  - the farm in a green fold watered by its own spring (the only green in the dead brown land): the house with the pantry door and its bar, the clay god's niche by the house door, the yard with hens, the bread oven, the well, and the long table under a vine.
- Across the road, the burnt brown land falls away in a long, steep scree-and-thorn slope to the thorn scrub at its foot and a dry wadi far below.
- Sc 12 needs Asher at the wall under the tamarisk with a view of the table and the open pantry door. It also needs his run out of the pantry, across the yard and over the stubble into the standing barley by the wall.
- Sc 1A needs the beating under the wall at the road's edge, his run down the road, the throw, the fall off the road's edge, the roll, and the place in the scrub where he lies (where Sc 12 has him wake). Give anchors for these.

**Kallias's court.** Owned by Scene 7: it writes `places/kallias_court.json`. Scene 9 reads it.
- A colonnaded court in the city, with couches and many lamps along the colonnade.
- At the far end, the open shrine of Tyche (the crowned goddess above a roaring brazier).
- The court gate to the street, with the beggar's corner outside it (the blind beggar in Sc 7, Asher in Sc 9).
- Use +x east, +y north. The dawn wind of Sc 7 is out of the east.

**The village gate.** Owned by Scene 6A: it writes `places/village_gate.json`. Scene 13 may read it.
- The gate's stone arch throwing shade, the elders' bench inside it, and the wall children sit on.
- The hill path climbs from the gate toward Eliab's farm to the north-west.
- The morning sun is low in the east.

Every other place belongs to its own scene; draw it inside your plan's `place`.

## Your scene

| scene | owner of | reads | design note budget |
|---|---|---|---|
| 0 + 1A | foreign_farm | | teaser about 10 s; 1A 1.25 min |
| 2 | eliab_valley, eliab_farm, eliab_house | | 4.5 min |
| 3 | | eliab_farm | 3 |
| 4 | | eliab_house, eliab_farm | 3 |
| 4A | | hillside | 0.5 |
| 5 | | eliab_farm | 1 |
| 6A | village_gate | | 2 |
| 6B | | eliab_farm, eliab_valley | 2.5 |
| 7 | kallias_court | | 4.75 |
| 8 | | eliab_farm, eliab_valley | 3.5 |
| 9 | | kallias_court | 3.5 |
| 10 | | eliab_farm (the gate insert) | 3.5 |
| 11 | | hillside | 1 |
| 12 | | foreign_farm | 1.5 (written before Opening C added the farm; time it truthfully) |
| 13 | | eliab_farm, eliab_valley, village_gate | 3.5 |
| 14 | | eliab_house | 1.25 |
| 15 | | eliab_farm, eliab_house, eliab_valley | 3 |
| 16 | | hillside | 1.5 |

The budgets are soft. Time the scene truthfully, and report the minutes.
