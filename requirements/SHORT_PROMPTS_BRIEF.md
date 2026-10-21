# Brief: short image prompts for one scene's location plates

The owner, 21 Oct 2026:
- "SEND ME ALL THE OTHER SCENES INCLUDING 1A 2 ETC IN ONE ZIP WITH ALL THE PROMPTS AND RESOURCES NO IMAGE REFERENCES"
- "MAKE SURE FOLLOW THE CINEMA BIBLE AND SCREENPLAY"
- "NOTHING IS CURRENTLY APPROVED"

Paths are under `D:/Projects/Premiere316_v4.1/work/prodigal-v3-20261019/`. Python is `D:/Dev/Tools/Python312/python.exe -I`.

**Your job is words only.** Write the image prompts for every location plate your scene needs, in the short style that worked for Scene 1. Write them into `location-plates/short_prompts/scNN/`. No image is made, and nothing is attached or quoted from any picture.

## The worked example: read it first

`location-plates/packages/SC01_PLATES/`: `README.md` and `prompts/01..12`. This is Scene 1 in exactly the shape you produce:
- one plate per spot, plus five views of it;
- each prompt headed by its tool line;
- about 120–230 words each;
- the subject first, then where the camera stands and what lies left, right and beyond, with distances, then the one light and its shadows, then the fixed look line.

Match that voice, length and precision.

## What you write, per spot

Your spots are the entries in `location-plates/ORBIT_SPOTS.json` whose `scene` is yours (`location-plates/orbits/scNN/SPOTS.md` lists them). Each spot is one place at one hour.

For each spot, in this order, write six prompts:
1. **plate:**
   - If the spot's `from` is empty, it is drawn from text: `[image_gen, aspect 3:2, drawn from text alone]`.
   - Otherwise it is redrawn from the plate of the `from` spot: `[image_edit, attach the plate of <from spot> as the only reference]`. Open the prompt with "The same <place> as the reference image, ..." and say what changes: the hour, the stand point, or both.
2. **right:** a quarter turn right from the plate's view.
3. **reverse:** a half turn.
4. **left:** a quarter turn left.
5. **low corner:** the lens a hand's breadth above the ground.
6. **macro:** one worn surface fills the frame.

Views 2–6 attach the spot's own plate: `[image_edit, attach NN (this spot's plate) as the only reference]`.

**File names.** `prompts/NN_<spot letter>_<view>.txt`, numbered through the scene: `01_A_plate.txt`, `02_A_right.txt`, ... `06_A_macro.txt`, `07_B_plate.txt`, and so on.
- The first line is the tool line in square brackets, then a blank line, then the prompt.
- For a cross-scene attachment, name the other scene's file, for example `attach the plate of sc02 01_A_plate`.

## How to get every view right

- **Choose the plate's stand point** by the template rule:
  - interior: the middle of the room, facing the main wall;
  - exterior: open ground at a distance, the whole place in frame.

  Start from the spot's `pos` and `facing`. If `location-plates/orbits/scNN/FIELDS.json` exists for your scene, Sol already chose a stand point there; use it.
- **For every view, run** `D:/Dev/Tools/Python312/python.exe -I location-plates/orbit_spots.py --digest <spot id> <x> <y> <facing>`. It prints what each quarter turn faces, with distances and sides, and where the light falls. Write those sides into the prompts.
  - Name the side of every landmark that matters (the lake, the gate, the doorway, the sun): "on the LEFT", "ahead on the right".
  - A view that loses its sides draws the place mirrored.
- **Use the facts of the place** from:
  - the scene's staging map (`staging/scNN/SCNN_STAGING.json` and its PNG);
  - the shared places it reads (`staging/places/*.json`, with their anchors);
  - Sol's `orbits/scNN/FIELDS.json` where it exists;
  - the screenplay section;
  - `PRODIGAL_V3_DESIGN_NOTE.md` §2c (each place's life and air; every particle has a cause) and §2d.
- **Keep the design fixed:** every prompt of one place describes the same design, the same materials and the same objects in the same positions.

## Binding rules

- **The bible** (`../revenant-cinematography-20261017/REVENANT_CINEMATOGRAPHY_BIBLE.md` §4):
  - one natural source at the scene's real hour;
  - real deep shadow over a third of the frame or more;
  - a muted sun-faded earth palette and a pale warm-grey hazy sky;
  - fine grain.
- **The look line:** end each prompt with "Muted sun-faded earth colours, a pale warm-grey haze, fine film grain, wide lens, deep focus. The place is empty and still."
  - At night or indoors, keep it but describe the one flame or the doorway as the only light.
  - For a macro, end with "Muted sun-faded earth colours, fine film grain."
- **The screenplay is locked.** Draw what the scene's place holds at that hour and nothing it lacks.
- **The owner's map instruction** (`staging/atlas/BRIEF_scene_maps.md`, first section):
  - **Eliab's room** is exactly 7 by 4 paces. Facing the hearth wall from the middle of the room:
    - FRONT: the hearth ring, the pot and the arched lamp niche;
    - RIGHT: the timber doorway onto the dark yard, with the water jar;
    - BEHIND: the mud-brick sleeping bench with sheepskins and blankets;
    - LEFT: the sealed storage jars, the oil jars and the hand mill on its reed mat with spilled flour;
    - middle: the low, heavy olive-wood table and stools.
  - **Kallias's court** is a multi-column Greek peristyle, with the open stone shrine of Tyche and the blazing central brazier.
  - **The pig fields** are stark and bare, with carob troughs and a distant thorn scrub boundary.
- **Positive words only.** Never write no, not, never, without, none, nobody or avoid.
- **The place is empty of people.** Never use person, man, men, woman, women or crowd, and never name the teacher.
  - Animals appear only where the place keeps them at that hour: the flock in a fold, the pigs in the pig fields, a tethered beast at a trough.
- **3:2** for every image.

## Finish

1. Write every prompt for every spot of your scene.
2. Run `D:/Dev/Tools/Python312/python.exe -I location-plates/short_prompts/check_short_prompts.py <scene>` until it prints ok. It checks the files, the tool lines, the lengths and the words.
3. Write `location-plates/short_prompts/scNN/SCENE_NOTES.md` in the Scene 1 README's shape:
   - the order table (file, tool, attach, what);
   - where each spot stands and faces, with each view's direction and light;
   - the locked design of each place;
   - for each redrawn plate, which earlier plate it comes from.
4. Write `location-plates/short_prompts/scNN/REPORT.md`, at most 15 lines.

Write only inside `location-plates/short_prompts/scNN/`. Make no image. No web search, no deletions, no subagents, and never stop to ask.
