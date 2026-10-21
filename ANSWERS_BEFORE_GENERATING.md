# Answers before generating

1. **Complete?** Yes. All 20 scenes and 384 prompts are in the repo. Generate Scenes 1A, 2, 4A, 6A, 6B and 7 to 16. Scenes 0, 1, 3, 4 and 5 are done.
2. **Where to start?** Start with 1A, then follow film order: 1A, 2, 4A, 6A, 6B, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16. Later scenes attach plates from earlier ones, so keep that order.
3. **Earlier scenes:** reuse the images already made for Scenes 0, 1, 3 and 5 as references; regenerate nothing. Where a tool line names one of those plates, attach this file:

   | tool line names | attach |
   |---|---|
   | sc00 01_A_plate | SC00 `01_A_plate.jpg` |
   | sc01 01_A_plate | SC01 `01_gate_plate.jpg` |
   | sc01 07_B_plate | SC01 `02_olive_plate.png` (Sol's redo) |
   | sc03 01_A_plate | SC03 `01_A_plate.jpg` |
   | sc05 01_A_plate | SC05 `01_A_plate_night.jpg` |
   | sc05 07_B_plate | SC05 `07_B_plate.png` (Sol's redo) |

4. **Order inside a scene:** every prompt in file-number order. Each spot's plate comes before its five views, because the views attach it.
5. **Settings:** follow each tool line exactly. `image_gen` draws from the text alone. `image_edit` attaches only the named plate. One image per prompt, 3:2, the largest size. No seeds, no variants, no extra settings.
6. **Maps:** correct. The staging maps and the atlas are for reading only. Never attach them.
7. **Naming:** yes. Name each image after its prompt file, for example `SC10_PLATES_GENERATED/01_A_plate.jpg`.
8. **Empty and period:**
   - No people.
   - Animals only where the prompt names them: the flock in its fold, the pigs in the pig fields, hens in a yard, a tethered donkey, the farm dog at rest.
   - Nothing modern. Lamps are open clay saucer lamps.
   - Light and shadow as each prompt says, with real deep shadow over a third of the frame or more.
   - There are no exceptions.
9. **Scene 15's oxen:** leave them out. They belong to the scene's action, so the prompts no longer name them (commit 2bb9d00). The yoke and the plough stay where the prompts put them. Scene 6B is the same: the loaded donkey is out, and the farm dog at the north post stays.
10. **Anything else:**
    - Scene 1A carries only the place.
    - The place rules in the README are binding: Eliab's 7-by-4-pace room, Kallias's peristyle court, and the bare pig fields as one place at every hour.
    - Reject any image with mirrored sides, the sun or a lamp in the wrong place, a reverse view that shows the subject behind the camera, an invented gate, arch or building, or a redrawn plate that changes the reference's design.
