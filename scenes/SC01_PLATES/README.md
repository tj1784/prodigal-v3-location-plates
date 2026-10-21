# Scene 1, the hillside above the lake: location plates for Grok

The Prodigal Son v3, 21 Oct 2026. Nothing in this package is approved.

## What to make (12 pictures, in this order)

| # | prompt | tool | attach | what |
|---|---|---|---|---|
| 01 | prompts/01_gate_plate.txt | image_gen 3:2 | nothing | THE FIRST PLATE: outside the gate, looking in |
| 02 | prompts/02_olive_plate.txt | image_edit | 01 | uphill inside the wall: the olive, the ledge, the gate |
| 03-07 | prompts/03-07 | image_edit | 01 | the gate spot turned right, reversed, turned left, low corner, macro |
| 08-12 | prompts/08-12 | image_edit | 02 | the olive spot turned right, reversed, turned left, low corner, macro |

- 01 is drawn from text, and every other picture is drawn from a plate, so the gate, walls, olive and light stay one design (your first option, 21 Oct).
- Use each prompt word for word.

## Where each picture stands (maps/SC01_ORBIT_SPOTS_MAP.png)

The local grid: +x toward the gate (screen right), +y downhill to the lake (top). The seat and ledge are at (0, 0), the gate at (27, 0). The sun comes from 135°: late afternoon, low, through haze.

- **Gate spot (01, 03-07):** stands at (33, 0), 6 m outside the gateway.
  - It faces 180°: the gate, the olive 35 m beyond, the lake on the RIGHT, the sun ahead-right.
  - Turned right (90°): the wall runs down to the lake on the left, the grove is on the right, the sun is ahead-left.
  - Reversed (0°): into the grove, lit from behind on the left.
  - Turned left (270°): the leaf close on the right, the wall climbing the hill, lit from behind on the right.
- **Olive spot (02, 08-12):** stands at (-2, -11), uphill inside the wall.
  - It faces 60°: the olive and ledge 12 m left, the gate 30 m right, the lake on the LEFT, the sun from the left.
  - Turned right (330°): toward the gate and the uphill wall, lit from behind.
  - Reversed (240°): uphill to the crest, lit from the right.
  - Turned left (150°): down to the lake, backlit.

## The locked design (staging map and screenplay)

- **The wall:** waist-high dry-stone, rough unmortared fieldstone, enclosing a terraced gathering ground.
- **The gate:** a 3 m opening between two square piers of roughly squared fieldstone, a little taller than the wall. One weathered wooden leaf with a diagonal brace and rope lashings hangs on the uphill pier (the LEFT one seen from outside) and swings OUTWARD, wide open. The threshold is bare trodden earth.
- **Outside the gate:** an old olive grove.
- **Inside:** 27 m from the gate stands one ancient olive. At its foot is the teacher's seat: a long, flat, knee-high shelf of NATURAL pale limestone bedrock, worn smooth. It is a natural outcrop, so it must not read as a built bench or a stone ring.
- **Beyond:** the slope falls to the pale lake and the grey far shore.
- **Empty:** no people, no animals.
- **Later scenes:** the same place returns at sunset (4A), at dusk with a small fire and hand lamps (11) and at night (16). Each is redrawn from these plates. Eleazar's loose stone sits on top of the wall 1 m from the north (lake-side) gate pier.

## The look (bible §4; full text in text/)

- One natural source with real deep shadow; muted sun-faded earth palette; pale warm-grey hazy sky; fine grain.
- Measured targets: luma 0.28-0.36; shadow at least 18 %; colourfulness 24 or less; warmth R-B +0.06 to +0.14; no clipped highlights; sharpness 750 or less; grain 1.0 or more.

## In the package

- **prompts/:** the 12 prompts, each headed by its tool and attachment.
- **maps/:**
  - SC01_STAGING_MAP_atlas.png and SC01_STAGING_MAP_reviewed.png: the staging map; the second is the version you reviewed;
  - SC01_ORBIT_SPOTS_MAP.png: where each picture stands.
- **text/:** Scene 1's screenplay; the bible's §4 look section; the design note's hillside lines.
- **data/:**
  - example_sc01.json: the staging map, as data;
  - SC01_ORBIT_SPOTS.json: the stand points;
  - hillside.json: the shared place.
