# The Prodigal Son v3: location plates for every scene

21 Oct 2026. These are the prompts, maps and rules for every location plate (empty background image) of the film, one folder per scene. Nothing here is approved.

## Status

| scene | state |
|---|---|
| 0, 1, 3, 4, 5 | Already generated on Grok web from an earlier version of the prompts. Sol is redrawing the rejected images. The prompts here are the rewritten ones, kept for any regeneration. |
| 1A, 2, 4A, 6A, 6B, 7, 8, 9, 10, 11, 12, 13, 14, 16 | Ready to generate. |
| 15 | Map, screenplay and data are in; its 24 prompts are being written and will be added. |

`scenes/README.md` lists every scene's folder, spots and prompt count, and which earlier scene's plates it draws on.

## How to generate all the shots

1. **Order.** Go scene by scene in film order: 0, 1, 1A, 2, 3, 4, 4A, 5, 6A, 6B, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16. Inside a scene, go in file-number order (`01_A_plate`, `02_A_right`, ...). A later plate is often drawn from an earlier one, so the order matters.
2. **One prompt file = one image.** Every `.txt` file in `scenes/SCNN_PLATES/prompts/` is one image.
3. **Read the first line of the file**, the tool line in square brackets:
   - `[image_gen, aspect 3:2, drawn from text alone]`: a first plate. Make a new image from the text only.
   - `[image_edit, attach NN (this spot's plate) as the only reference]`: a view. Attach that plate from the same scene, as the only reference.
   - `[image_edit, attach the plate of scNN NN_X_plate as the only reference]`: a returning place. Attach that plate from the named earlier scene, as the only reference.
4. **Prompt.** The text after the blank line is the prompt. Use it word for word.
5. **Format.** Aspect 3:2, the largest size available, one image per prompt.
6. **Name.** Name each image after its prompt file (`01_A_plate.jpg`) and keep one folder per scene (`SC02_PLATES_GENERATED/`), so later scenes can attach it.

### Spots and the six images per spot

Each scene has one or more spots. A spot is one place at one hour, seen from one stand point. Each spot has six images, in this order:

1. **plate:** the establishing view;
2. **right:** a quarter turn right from the plate;
3. **reverse:** a half turn;
4. **left:** a quarter turn left;
5. **low corner:** the lens a hand's breadth above the ground;
6. **macro:** one worn surface fills the frame.

The five views keep the plate's place, design and light. Only the direction of the camera changes. Each scene's `README.md` gives the order table and where every spot stands and faces. Its `maps/` folder holds the staging map, and its `data/SPOTS.json` holds the exact stand points.

## Check every image before keeping it

These are the mistakes that sent images back in the first runs:

- **Sides.** Every landmark must be on the side the prompt names (LEFT or RIGHT). A mirrored view is a reject.
- **Light.** The sun, the lamp or the fire must be where the prompt puts it. "Behind the camera" means out of frame.
- **Reverse views** look away from the plate's subject. The gate, threshing floor or building behind the camera stays out of frame.
- **Nothing invented.** Add no extra gate, arch, ruin or house beyond what the prompt names.
- **Period.** Nothing modern: lamps are open clay saucer lamps, never lampshades.
- **Empty.** The place is empty and still: no people, and no animals beyond the ones the prompt names.
- **Design.** A redrawn plate keeps the reference image's design stone for stone. Only the hour or the stand point changes.

## The look (the cinema bible, section 4)

- One natural source at the scene's real hour, with real deep shadow over a third of the frame or more.
- A muted, sun-faded earth palette and a pale warm-grey hazy sky; fine film grain; a wide lens and deep focus.
- Measured targets: luma 0.28-0.36; shadow at least 18 %; colourfulness 24 or less; warmth R-B +0.06 to +0.14; no clipped highlights; sharpness 750 or less; grain 1.0 or more.

## The owner's place rules

- **Eliab's room** is exactly 7 by 4 paces. Facing the hearth wall from the middle of the room:
  - FRONT: the hearth ring, the pot and the arched lamp niche;
  - RIGHT: the timber doorway onto the dark yard, with the water jar;
  - BEHIND: the mud-brick sleeping bench with sheepskins and blankets;
  - LEFT: the sealed storage jars, the oil jars and the hand mill on its reed mat with spilled flour;
  - middle: the low, heavy olive-wood table and stools.
- **Kallias's court** is a multi-column Greek peristyle, with the open stone shrine of Tyche and the blazing central brazier.
- **The pig fields** are stark and bare, with carob troughs and a distant thorn-scrub boundary. They are one place at every hour.
- **A place keeps one design.** Each place is drawn from text once. Every later image of it is redrawn from the nearest earlier plate of that place.

## What is in this repo

- `scenes/SCNN_PLATES/`: one folder per scene.
  - `README.md`: the order, the tools, the spots;
  - `prompts/`: one file per image;
  - `maps/`: the scene's staging map;
  - `text/`: the scene's screenplay, the bible's look section and the design note's world and look;
  - `data/`: the staging spec, the spots and the shared places it uses.
- `requirements/`:
  - the locked screenplay;
  - the full cinema bible (`REVENANT_CINEMATOGRAPHY_BIBLE.md`);
  - the design note (`PRODIGAL_V3_DESIGN_NOTE.md`);
  - the owner's map brief (`BRIEF_scene_maps.md`);
  - the prompt-writing rules (`SHORT_PROMPTS_BRIEF.md`).
- `maps/PRODIGAL_V3_STAGING_ATLAS.svg`: every scene's staging map, a tab per scene. Open it in a browser.
- `data/ORBIT_SPOTS.json`: every spot of the film, with its stand point, facing, hour, light and the plate it is drawn from. `data/places/`: the shared places (the hillside, Eliab's farm, house and valley, the village gate, Kallias's court, the foreign farm).
