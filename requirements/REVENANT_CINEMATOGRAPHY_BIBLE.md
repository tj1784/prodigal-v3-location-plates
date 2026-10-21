# The Revenant cinematography bible

Reference for Prodigal Son v3 and the Scene 1 long-take study. Reviewed again on 18 October AD 2026 for attempt 4, including the young shepherd, 33-person gathering and lived-in photographic texture.

## Owner decisions — binding

1. Whip pan on the name. The Scene 1 name cue motivates the turn toward the named listener.
2. Ref2VA, with character references on, for the long takes. Cast photographs supply identity as the camera reaches people.
3. Spherical ultra-wide close-ups with deep focus. Very close faces and a legible world belong in the same composition.
4. The owner's corrected restrained warm look is binding. One available source, actual dark shadow sides, dusty faded earth colours, pale hazy sky and matte real skin. Use the two owner boards only to study light/palette, never as generation inputs.
5. H3 speaks every line itself. No ElevenLabs and no pinned dialogue recordings. A library voice is a timbre reference, not replacement speech.
6. The civitai reference supplies actor realism and prompt structure only. Camera, staging, light and editing follow this Revenant study.
7. Review the bible before image generation. These six design plates are writer/reviewer references, never first frames or a way around asset prerequisites, content locks or owner holds.
8. For this task the explicit brief specifies late afternoon and the gate at Jesus's three o'clock about 27 m away. This supersedes the older SC02 template's anamorphic/shallow-focus treatment and its later 5.1 m gate layout for these study deliverables. It does not modify any live scene or approved asset.

9. **Exactly 33 people in Scene 1**, named cast included. The eight named people are Jesus, Jotham, Eleazar, the shepherd boy, the mother, her baby, Hezron and the woman beside him; 25 unnamed listeners complete the count. There are 31 people inside the gathering and two watchers outside the gate. A cropped view shows a subset of these same people, never extra spectators.
10. **The current @ref5 is the approved 17-year-old Judean shepherd boy.** Warm olive skin, dark brown curls, clean-shaven face, russet headcloth, sand-brown wool tunic, rope belt, sling, small bag, sandals and wooden staff. His identity source is `D:/Projects/Premiere316_v4.1/work/shepherd-boy-20261017/plate/shepherd_boy_plate.png`. His unchanged answer is He doth. Every shepherd doth., spoken in a light, clear young voice. The earlier elderly shepherd is superseded in all deliverable pictures and prompts.
11. Use the current owner-approved sheets in `ComfyUI/input/Prodigal_v2/SC01_plates_approved_20261013/` for Jesus, Jotham, Hezron, mother, baby and woman beside the collector, and `eleazar_frame10.png` or `eleazar_frame13.png` for Eleazar. The older cast directory and prior plates are historical comparison, not current identity authority. Preserve the actual faces and costume pigments in these sheets while changing their light, wear and setting.
12. **Opening orientation** is teacher and old olive at screen left, wall and open gate at screen right, lake beyond both, as in `01_s01_jesus_question.png`. All map panels share that orientation. The 33 people sit in a few loose, interrupted terrace groups, with backs and shoulders cut by the image edges.
13. **Attempt 4 texture is binding.** The owner said pls generate new plate last one still looks to clean. Every photograph must carry lived-in people, used materials, an unarranged gathering and imperfect camera texture, as specified in section 4. Run `tools/clean_meter.py` on the photographs and assembled boards; sharpness must be at most 750 and grain at least 1.0.

Work is confined to this bible, `plates/`, `study/` and `windows_W1-W4_sol.json`. No application, node, film-library or server change is part of this study.

## 1. Evidence and how to read this bible

**Production facts** below have inline sources. **File observations** describe this particular film copy; they do not prove the physical rig, exact lens, VFX technique or number of camera setups used. **Pipeline facts** come from the supplied builder, compiled prompts and coordinator's 17 October test record. **Targets and proposals** are decisions for our work, not claims about every shot of the film.

All film timestamps are FILE TIME in `F:/MOZ DOWNLOAAD HELPER/The Revenant watch free online on Myflixer.mp4`, measured duration 9417.668 s, picture 1920 × 800. ffprobe reports a 120/1 nominal frame rate. The supplied measurement tools explicitly resample to 24 fps; cut times are therefore approximate to one 24 fps sample, not certified source-frame boundaries. Some independently sought strip frames reveal the transition one sample before the detector's reported time.

The new study comprises a 104-frame sparse whole-film index, detailed sequence sheets, 24 bounded `cuts.py` scans, 49 inspected twelve-frame boundary strips, and 13 `feel2.py` intervals. Files and exact interval commands are in `study/`. This is a whole-film survey with selected detailed takes, not an exhaustive catalogue of every shot or a claim that the entire movie is one take. Film frames, including the new study samples, are study-only material. They must never be supplied to an image generator. Every generated photographic plate uses only explicitly listed Prodigal cast/place references.

## 2. The cinematic idea

In the opening attack the camera behaves like someone within the event. A nearby face, the next person and the landscape share a wide field of view. The camera receives its next destination from a glance, a handoff, an impact or a voice. It can descend with a body, rise into the canopy, or leave people behind and attend to the place. Distance and speed change within the image.

The rest of the film adds an essential qualification. Landscapes, memories and exhausted faces can be almost stationary. The language alternates physical involvement with stillness and scale. The moving dialogue target in section 10 applies to the Scene 1 design; it is not a description of every Revenant frame.

## 3. Production fact audit

| Subject | Reviewed fact and correction | Source |
|---|---|---|
| Cameras and capture | ALEXA XT and M, with ALEXA 65 for selected material. Tests led the filmmakers to abandon film acquisition. Digital sensitivity helped at very low light levels. | [ARRI production account](https://www.arri.com/news-en/alexa-xt-and-alexa-65-on-the-revenant-) |
| Exact lenses | The main Master Prime was **14 mm**, with **12 and 16 mm** used occasionally. The lightweight Leica in the cited account was **16 mm Summilux-C**, then that series' widest lens. The old 12/14/18 and Leica 14/16/18 lists are corrected. | [American Cinematographer, January AD 2016, Left for Dead, indexed lens passage](https://pages.nxtbook.com/nxtbooks/ac/ac0116/offline/ac_ac0116.pdf) |
| Wide field of view | Sakamoto describes a 12–21 mm range including equivalent fields of view on the larger format. Millimetres on different formats are not directly interchangeable. | [Sakamoto's SOC account](https://soc.org/project/the-revenant-shooting-in-the-elements/) |
| ALEXA 65 example | ARRI documents a 24 mm lens on a small crane arm for the avalanche close-up, at 1200 ASA to retain depth of field. This is an example, not proof of the lens on an arbitrary film frame. | [ARRI production account](https://www.arri.com/news-en/alexa-xt-and-alexa-65-on-the-revenant-) |
| Format | 2.39:1 digital capture with the spherical lens families above. This study adopts spherical 14 mm language for Scene 1. An earlier anamorphic acquisition proposal is not the finished lens recipe. | [AC technical specification](https://pages.nxtbook.com/nxtbooks/ac/ac0116/offline/ac_ac0116.pdf), [SOC equipment history](https://soc.org/project/the-revenant-shooting-in-the-elements/) |
| Camera support | Handheld, Steadicam and telescopic crane are documented. The previous absolute prohibition on dollies is removed. Accounts differ in their terminology; our criterion is motivated movement and parallax, not a global equipment ban. | [ASC Wrap Shot](https://theasc.com/article/wrap-shot-the-revenant/), [Lubezki interview](https://britishcinematographer.co.uk/emmanuel-lubezki-amc-asc-the-revenant/) |
| Light | Predominantly natural light and firelight. A windy campfire required a constant light cushion, and another setup blocked moonlight. Natural acquisition also received a substantial DI. The old claim that absolutely nothing else was lit is too broad. | [Lubezki on lighting and finishing](https://britishcinematographer.co.uk/emmanuel-lubezki-amc-asc-the-revenant/) |
| Opening VFX | MPC describes joining more than 100 shots into **39 extended shots**, matching light, retiming and rebuilding image regions, with CG horses, arrows, smoke, fire, mud and skies. Those are vendor shot counts, not our visible edit count. | [MPC's own account](https://www.mpcvfx.com/en/filmography/revenant/) |
| Rehearsal and order | Sakamoto confirms careful choreography and shooting in story order. Lubezki describes a proxy stage and stunt rehearsal for the bear scene. The former blanket claims of no storyboards/no previs, exactly three weeks/four shooting days, and one or two takes on every setup were not established by the accessible cited sources and are removed as production facts. | [SOC](https://soc.org/project/the-revenant-shooting-in-the-elements/), [Awards Daily interview](https://www.awardsdaily.com/2015/12/18/interview-cinematographer-emmanuel-lubezki-talks-shooting-the-revenant-and-bear-attacks/) |

**Usable-light correction.** The brief's working figure is about **8 hours of usable light, with about 5 hours actually spent shooting**, rather than five usable hours. The underlying Lubezki interview more precisely describes some eight-hour working days with five hours of shooting. Do not turn that into a fixed daylight measurement for every location/day. The original Deadline page could not be fetched in attempt 2; its 8/5 statement is reproduced by the accessible [Adorama account linking the original interview](https://www.adorama.com/alc/the-revenant-shooting-under-extreme-conditions/) and is traceable to the [Deadline interview](https://deadline.com/2015/12/emmanuel-chivo-lubezki-revenant-cinematographer-interview-oscars-1201671835/).

There are no verbatim production-source quotations in this bible. The Screen Daily and Variety links in the earlier version could not be fetched reliably and are no longer sole authorities for a production assertion. Attempt 2 rechecked ARRI, British Cinematographer, MPC and Awards Daily directly, and the SOC account and AC lens/aspect passages through their indexed primary-source text. The indexed AC passages were available through search; the full PDF did not open in the browsing tool. The Adorama reproduction remains an explicitly secondary trace of the unavailable Deadline 8/5 wording, not a new independent primary-source confirmation. No claim is made that it was downloaded or read cover to cover.

## 4. Light, skin and the measured look

**File observations.** Low sun enters between trunks, outlines bodies and sometimes veils the lens in flare. Faces often live in open shade while the background remains bright. Smoke, mist, water and breath give depth to the air. These observations describe the opening passage; later sequences include overcast snow, firelight, twilight and windows. Natural light does not mean an identical time of day or colour in every scene.

The earlier bible's 24-frame summary is retained below as a historical comparison, with a reproducible new sample beside it. The new sample takes 480-pixel-wide PNG frames at 7:20, then every 15 s through 13:05; `tools/lookagg.py` reports medians across those 24 samples. Sampling, resolution and masks matter. The old brightness/contrast pair cannot be asserted as newly reproduced.

| Metric | Previous Revenant table | New 24-frame sample | Ours 00276, inherited measurement | Approved images, inherited measurement |
|---|---:|---:|---:|---:|
| Saturation in lit pixels, luma > 0.08 | 0.22 | **0.22** | 0.36 | 0.29–0.35 |
| Highly saturated lit pixels, HSV S > 0.6 | 1.8% | **1.0%** | 10.6% | 4.5–6.5% |
| Mean R minus B | -0.05 | **-0.044** | +0.13 | +0.11–+0.13 |
| Mean G minus R | +0.03 | **+0.031** | -0.08 | — |
| Mean luma | 0.27 | **0.22** | 0.36 | — |
| Luma standard deviation | 0.19 | **0.16** | 0.22 | 0.19–0.24 |
| Luma > 0.95 | 0.00% | **0.00%** | 0.02% | — |
| Luma < 0.02 | not recorded | **2.0%** | not recorded | 0.1–0.3% |

This copy's opening is muted, cool/green and relatively dark. Those numbers are a study of the delivered file, not camera-original exposure or a recoverable shooting LUT. The 00276 and approved-image columns are coordinator measurements supplied with the brief; they were not remeasured in this task.

### Owner look correction — binding, 17 October AD 2026

The owner stopped attempt 1 with the words **NEED MORE NATURL; SHADOWS**, describing its professional-magazine studio lighting. His subsequent correction was **ITS TOO COLORFUL LIKE A HIGH END PIXAR MOVIE**. These are owner instructions, not production-source quotations. The stopped boards and prompts in `plates/rejected_studio_look_20261017/` are rejected history and are not reused.

The two boards are `look_refs/owner_look_ref_1_story_grid.webp` and `look_refs/owner_look_ref_2_father_son.webp`. They define **light and palette only**. Their actors, compositions and events do not become our cast or story. Never send either board, a Revenant frame, or anything in `reference_frames/` or the film-study sheets to an image generator. Generation receives only the needed Prodigal cast images plus at most one approved Scene 1 place frame, with at most five inputs per call.

**Light.** Outdoors, one low late-afternoon sun passes through dusty haze and olive branches; a later scene may use its own thin overcast. Indoors, only the actual doorway or window lights the room and the room falls into darkness. No fill, reflector, beauty light or glamour rim. A narrow source-side edge may occur where the real sun reaches it; an illuminated outline around every person is not the design. The shadow side falls visibly dark under brow, beard and chin. Real leaf, cast and contact shadows connect people, worn wool and earth. Backgrounds generally sit a little darker than faces; the sunlit crowd beyond the deeply shaded gate is the motivated divided-light exception.

**Palette and texture.** One sun-faded earth family — dusty linen, ochre, wool brown, olive-grey, chalk and weathered skin. The sky and distant lake read as pale warm-grey haze. Preserve muted costume pigments and actual olive skin while keeping vivid blue/green out of the look. Matte surfaces, irregular pores, sun damage, road dust, sweat and worn dirty cloth belong to a caught mid-moment photographic image. People attend to each other or the bread. @ref2's eyes look past the lens at listeners, never into or near it. At the bow @ref7 lowers his head and closes his eyes while seated; he is not face-down on the ground.

Run **`tools/look_natural.py` on every photographic panel**, then on each assembled plate. Evaluate the photographs separately from captions, margins and letterboxing. The cream-board mask in that tool is part of its measurement definition; do not create dark labels or black bars to manufacture a shadow pass. P2 is a diagram and is excluded.

| Metric | Owner's panel target | Acceptance checker tolerance |
|---|---:|---:|
| Mean luma | **0.28–0.36** | 0.26–0.38 for assembled plate |
| Real shadow, luma below 0.15 | **at least 18%** | at least 15% |
| Bright-blue sky saturation | **≤0.18, or no qualifying blue pixels** | same |
| Mean R minus B | **+0.06 to +0.14** | not checked by the supplied checker |
| Clipped highlights, luma above 0.97 | **0%** | below 0.5% |
| Hasler–Süsstrunk colourfulness | **≤24** | ≤26 |

The owner boards measured luma about 0.30–0.33, shadows 20–26% and colourfulness 21.6–23.0 in the supplied review. The supplied comparison gives Revenant colourfulness 12.7 and our 00276 30.6. Those inherited values are labelled as supplied evidence; attempt 2 also measures the actual owner boards read-only in `study/attempt2_look_refs.txt`.

These targets supersede the older attempt-1 saturation/warmth table. Whole-frame HSV saturation and `lookagg.py`'s lit-pixel saturation have different denominators; neither replaces the colourfulness gate. Short plain image prompts lead with the desired light and texture, and describe only what is wanted. A failed panel is redrawn with the built-in image tool, not repaired by quietly grading the raster. Save the exact prompt, references, source crop, raw and final panel statistics and inspection decision. Preserve every later scene's actual hour and geography.

### Lived-in, imperfect plates — binding, 18 October AD 2026

Faces retain their approved identity and age while showing uneven weathering, sunburn, chapped lips, squint lines, stray hair, sweat and road dust. Adult beards are irregular. The shepherd boy remains clean-shaven and visibly adolescent. Hands have flour, crumbs and dirt under the nails; dusty feet and practical sandals touch the earth. Unnamed faces range from plain to rough.

Cloth is sweat-marked, stained, patched, frayed and creased. Baskets and cloaks lie where people set them down among loose stones and trampled grass. A listener scratches, a child fidgets and another person shifts on the ground. These are incidental states within a shared event, not a synchronized acting list or neatly posed rows.

Moving fingers carry slight motion blur; lens edges are gently soft while depth of field keeps the hillside and gateway legible. Dust and low sun veil the image and lift the deepest blacks slightly. Fine irregular grain is visible throughout. Deep focus describes depth, not razor-sharp digital edges. The requested grain is an owner-directed treatment for Prodigal; it is not a claim that The Revenant was shot on film. [ARRI's production account](https://www.arri.com/news-en/alexa-xt-and-alexa-65-on-the-revenant-) explicitly describes its digital acquisition.

The supplied owner-board texture benchmark is sharpness 570–620 and grain 0.8–1.5. The acceptance target for every photographic plate is **sharpness ≤750 and grain ≥1.0** using `tools/clean_meter.py`; measure individual photographic panels too. Preserve every look target above. Neither grain nor blurred detail can substitute for worn faces, clothes and spontaneous blocking. Cropping, ordinary resizing and board layout are documented; failed photographic light or texture is regenerated with the built-in image tool, never silently graded, blurred or given synthetic noise by a script.

**Specific picture corrections.** The W1 close approach and W9 key use a clear off-axis listener eyeline. The boy replaces the former shepherd in W3, W10 and W16 and any wider view that reaches him. W11 starts on a close oblique view of the woman, travels around her into profile, then reveals the sharp distant gate behind her. W11-open, W11-key, W11-end and W12-open must be four visibly different camera positions; W12-open continues the approach from the gate-related end view. Board gutters stay outside each photograph; no seam or white line crosses a panel.

## 5. Movement grammar

1. **Motivated travel.** In the opening dialogue-like take, the camera walks through people rather than gently animating a posed portrait. Movement has a destination and changes foreground parallax.
2. **Baton pass.** Follow the loaf from one pair of hands to another, then receive the new person's attention. In the film an event or body performs this transfer.
3. **Elastic distance.** A close face can become a wide view inside one take; the next person's movement brings the camera close again.
4. **Human height and gravity.** Rise from knee height, descend with the bow, or look upward when the person/world gives a reason. Do not invent a flying operator inside a crowd.
5. **Speed change.** A quiet approach, a quick turn on a cue and a slower recovery differ from a constant motor glide.
6. **Physical presence.** Foreground cloth, hands, weather and flare belong to the place. A splash or flare is not automatically an edit.
7. **Sharp context.** The Scene 1 design keeps nearby faces and geography legible on a spherical ultra-wide lens. The actual film also contains focus changes and softer backgrounds; deep focus everywhere is our owner decision, not a universal production claim.
8. **Permission to be still.** An exhausted face or immense landscape may make the body's motion more visible by reducing camera motion. Use the opening's travel target for Scene 1; choose stillness deliberately elsewhere.

## 6. Opening cut map — 7:20 to 13:00

The former statement of six cuts mixed boundaries and categories. The inspected map has **seven image boundaries inside the passage**: six overt cuts plus the foreground-masked edit at 8:45.88. The entry at 7:20.17 is listed separately and is not an internal cut. The foreground boundary is visible in the strip; whether the production built it as a composited stitch or a straightforward edit cannot be established from this copy.

| File time | Observation | Counting category |
|---|---|---|
| 7:20.17 | Flooded hunters to the camp ground and game carcass | Entry boundary, excluded from the seven |
| **8:34.58** | Wounded men by a tree to riders in a misty creek | Internal place cut |
| 8:39.21 | Splash over the lens to the charging rider's new angle | Internal action cut, splash-masked |
| 8:43.96 | Falling rider/shield to sun and dark trunks | Internal action cut |
| 8:45.88 | Forest view to the rifle and new foreground tree angle | Internal foreground-masked edit; not proof of a particular VFX method |
| 9:50.83 | Fallen body to an axe swing in extreme close view | Internal action cut |
| **10:56.33** | Cabin interior to the burning camp | Internal place cut |
| 11:27.04 | Carrying the wounded man to the rifle aimed at the river | Internal action cut |

The next inspected boundary is 13:14.42, beyond the requested passage. The spike at 10:52.17 is **not a cut**: the cabin door's sun flare blooms and clears while the body/doorway continue. Whips and muzzle flashes elsewhere likewise require visual checking. See the original `reference_frames/cut_*.jpg`, plus new `study/boundary_review_09-10.jpg` and `study/extra_boundaries_02-03.jpg`.

### Take A — 7:20.17–8:34.58, about 74.4 s

Opens at ground level, rises along a rifle to a very close face, tilts toward the pine canopy, then passes from worker to worker. The first arrow changes its pace. It descends again with the wounded people and the flaring trees. **New measurement reproduces 91% moving frames, pan 0.29/0.07, tilt 0.28/0.10, push 0.21/0.05**. This is Scene 1's dialogue-travel reference.

### Short burst — 8:34.58–8:45.88, about 11.3 s

Riders, splash, fall and forest angles arrive in four boundary events. Distinguish this brief edited burst from the long passages around it.

### Take B — 8:45.88–9:50.83, about 65.0 s

Glass fires and the frame receives another fighter. The camera drops into a strangling struggle, rises with a body and returns to the fallen man. The inherited coordinator measurement is 97% moving; pan 0.50/0.38, tilt 0.55/0.73, push 0.31/0.28. It is action energy, not the target for a quiet question.

### Take C — 9:50.83–10:56.33, about 65.5 s

An axe swing hands the camera to a rider, the falling rider and a man with pelts, then to a body entering the cabin. Flares and changing light bind the passage. Inherited measurement is 95% moving; pan 0.49/0.32, tilt 0.42/0.68, push 0.44/0.24.

### Take D — 10:56.33–11:27.04, about 30.7 s

From the smoky camp the camera travels with the retreat toward the boat. A carried body supplies pace and height. Inherited measurement is 99% moving; pan 0.49/0.14, tilt 0.31/0.16, push 0.63/0.22.

### Take E — 11:27.04–13:14.42, about 107.4 s

The camera enters and leaves the water, reaches the boat, then lets the escaping people go. It attends to riders, smoke and sky before receiving the older woman's approaching face. The inherited measurement covers only 11:27–13:00, **93 s rather than the full take**: 89% moving; pan 0.20/0.08, tilt 0.42/0.17, push 0.29/0.10. Use that limited interval honestly. The camera can remain with a place after an event and change the scene's emotional tempo.

## 7. Whole-film study beyond the opening

The sparse index surveys the movie from 0:30 into the end credits. It locates the family memory and flooded hunt, ambush and retreat, riverbank arguments, bear, carrying and campfire, abandonment and crawling, river escape, travelling/camp companionship, healing and ruined-church dream, horse escape, exposure and rebirth, return to the fort, pursuit, final fight and closing vision. The detailed sheets around those sequences establish the selected intervals below. The section covering 97:30–100:30 corrects the initial search range: the ruined-church embrace is around 99 minutes, not 95 minutes.

### Measured takes and signature passages

Values are **median speed / robust jitter**, in percent of frame size per frame for pan/tilt/push. Moving percentage uses the supplied tool's smoothed pan/tilt threshold of 0.15. Exact stdout, including roll, is in `study/feel2_*.txt`; exact commands are in `study/measured_intervals.json`.

| Sequence and file interval | Apparent take length | Pan / jitter | Tilt / jitter | Push / jitter | Moving |
|---|---:|---:|---:|---:|---:|
| Opening memory tree, 1:55.125–2:05.458 | 10.333 s | 0.02 / 0.01 | 0.03 / 0.02 | 0.03 / 0.02 | 0% |
| Ambush A, 7:20.167–8:34.583 | 74.416 s | 0.29 / 0.07 | 0.28 / 0.10 | 0.21 / 0.05 | 91% |
| Bear attack, 24:00.250–28:57.958 | 297.708 s | 0.19 / 0.15 | 0.25 / 0.32 | 0.18 / 0.13 | 87% |
| Night campfire, 33:10.833–34:45.542 | 94.709 s | 0.08 / 0.09 | 0.12 / 0.13 | 0.13 / 0.10 | 65% |
| Riverbank into river escape, 70:07.167–71:59.875 | 112.708 s | 0.23 / 0.13 | 0.23 / 0.24 | 0.32 / 0.13 | 90% |
| Breath close-up, 97:15.542–97:27.375 | 11.833 s to the fog-masked angle boundary | 0.01 / 0.03 | 0.06 / 0.08 | 0.01 / 0.03 | 36% |
| Ruined-church dream embrace, 99:06.292–99:30.250 | 23.958 s | 0.12 / 0.04 | 0.12 / 0.05 | 0.12 / 0.04 | 61% |
| Horse mounting/chase/cliff, 109:59.125–111:11.917 | 72.792 s | 0.20 / 0.08 | 0.22 / 0.19 | 0.26 / 0.06 | 78% |
| Wife vision within the horse shelter, 114:03.250–114:30.583 | 27.333 s | 0.03 / 0.06 | 0.09 / 0.20 | 0.05 / 0.06 | 39% |
| Departure into forest scale, 115:05.333–115:50.292 | 44.959 s | 0.02 / 0.00 | 0.02 / 0.01 | 0.04 / 0.00 | 0% |
| Frozen-valley scale, 115:50.292–116:27.875 | 37.583 s | 0.01 / 0.00 | 0.02 / 0.00 | 0.03 / 0.00 | 3% |
| Final ground fight, 139:42.208–142:21.542 | 159.334 s | 0.34 / 0.50 | 0.68 / 0.99 | 0.37 / 0.56 | 96% |
| Late exhausted face, 146:06.042–146:16.042 | 10.000 s, not the film's final shot | 0.01 / 0.02 | 0.02 / 0.04 | 0.03 / 0.05 | 0% |

**Measurement limits.** Apparent take means the passage presented between inspected boundaries, potentially containing VFX stitches. It does not certify one physical camera exposure. `feel2.py` prints a field called cuts, but that is a brightness-change frame mask, not an edit count. The bear gives 14 masked frames and the wife vision 30 despite their apparent continuity; bodies, shadows and smoke trigger it. Its derived average-shot field must not be used as a take-length measurement. Take lengths above come from the boundary map. Global affine optical flow can also confuse actor motion, perspective and camera movement. Push is an image-scale proxy, not measured camera travel in metres.

### What the camera does and what Prodigal Son v3 can use

| Sequence | File observation and rhythm | Prodigal application |
|---|---|---|
| Family memory, 1:55–2:05 | A broad tree and tiny figures place intimacy inside a large world; wind/body movement supplies life in a nearly still frame. The subsequent face angles are real cuts, not part of the measured 10.3 s wide. | A memory of home during the **long walk home**. Preserve Prodigal geography; do not import this tree composition. |
| Bear, 24:00–28:58 | From an alert standing face the frame turns with danger, collapses to ground height, receives weight and occlusion, then recovers unevenly. Pauses between attacks make resumed violence unpredictable. The body/fur can obscure possible joins. | **Famine and pig field** exhaustion: descend with the weakened body and let breath set pace. Borrow physical vulnerability, not the bear choreography or wounds. |
| Campfire, 33:10–34:45 | A moving group view yields to close profiles, returns through flame/shoulders and settles into a dispute. The fire gives a coherent local source while forest depth remains cold. Flame spikes are not automatically cuts. | **Far country feast**: pass attention between diners, cups and a face; sustain physical ambience. For the **older brother outside**, let warm inside/cool outside separate emotional belonging while keeping the actual scene hour. |
| River escape, 70:07–71:59 | Starts at hands/body on the bank, rises to the strained face, travels beside the rock shelf, and drops with the body into water. The next river view at 71:59.875 is a genuine new angle. The later 72:04.583 splash boundary is visually masked/ambiguous, so no extra cut count is asserted from it. | **Pig field** into **long walk home**: let the decision become a real change in bodily level and travel. Carry wind/ground sound continuously. |
| Breath, 97:15–97:27 | The very low close face breathes into the foreground; a cloud grows before the angle changes near 97:27.375. The cloud is continuous physical action; the angle boundary can be masked by it. | **Famine/pig field** close presence. In warm Galilee use audible breathing and credible dust/cloth, not invented freezing condensation. |
| Ruined church, 99:06–99:30 | The camera receives the approaching son, moves into the embrace and makes their faces, hair and shoulders the world; a close reaction follows on a cut. This is dream space with some softer focus, not a mandate for shallow-focus Scene 1. | **Father running and embrace**: follow the meeting until the body contact completes the emotional action. Keep both identities and hand/shoulder geography readable. No ruined church or vision character is transferred to Prodigal. |
| Horse and cliff, 109:59–111:11 | Begins with the sleeper near the tree, reacts to pursuit, rises with mounting, travels at body/horse height, then breaks the horizon with the fall. The overhead forest angle after 111:11.917 is a separate shot. | **Father running**: accelerate because the father acts, retain actual ground parallax, then decelerate into contact. **Long walk home**: an obstacle changes level and effort. No cliff stunt is required. |
| Wife vision, 114:03–114:30 | A tight shelter/face view opens into an intimate apparition; breathing haze, light and overlapping bodies disturb image contrast. The cut back to the canopy is at 114:30.583. | Subjective memory during **famine** or the **long walk home** if the script permits it. The interior state can motivate light/scale changes without adding unapproved story events. |
| Departure and valley, 115:05–116:27 | One wide watches the body retreat among trees for about 45 s; the next makes a walker tiny against a frozen valley for about 37.6 s. These are two takes separated at 115:50.292. Motion is mainly in the person. | **Long walk home** and **famine**: scale and duration make effort legible. Preserve the dry Galilee terrain and its own sun/weather. |
| Final fight, 139:42–142:21 | Close physical contest drops, rolls and rises with the men, then receives the distant riders. Large tilt jitter belongs to impacts and struggle, not merely a handheld adjective. The arrival angle at 142:21.542 is a genuine cut. | **Older brother outside**: borrow unequal spacing, obstruction and the feeling of being unable to step into a shared space. Use dialogue-level movement unless the approved script calls for physical conflict. |
| Late face/vision, 146:06 onward | Nearly still facial presence alternates with the woman among trees. The inspected cuts are 146:06.042, 146:16.042 and 146:33.208. The selected ten-second face is not the final shot; the ending continues afterward. | After the **embrace**, or **older brother outside**, a completed movement can yield to listening. Our eyelines remain on people/place; the film's eventual near-lens address does not override the owner's lens-gaze rule. |

## 8. Sound and performance inside the image

Listening observations from the film: breathing, water, wind and close physical impacts anchor camera position. A change in visual scale need not interrupt the sound of the place. A sky or landscape passage can retain the consequences of what has just happened. These are observations, not newly measured film-audio dB values.

For Prodigal, the breeze, leaf movement, sandals, cloth, bread and quiet crowd make the scene a shared physical event. Sound perspective should change as the operator leaves a mouth and approaches hands or the gate. Room tone must continue under speech and across all visual stitches. A quiet beat still has a sound floor.

## 9. Actors and prompt writing (from the civitai reference)

This section uses the coordinator's supplied clip review; the civitai clip itself and its prompt text were not downloaded or copied. Its structure is the useful evidence, and it is not a cinematography reference.

- Its H3 wrapper uses `subject_definitions`, `summary`, `retention_analysis`, `detailed_description`, `overall_soundscape` and `non_diegetic_music`.
- Time-stamped shot entries use the form `[Shot N] At 00:05.000`. These are wrapper conventions, not permission to introduce several editorial shots within a Scene 1 window. Our owner-facing prompt body uses decimal-second stamps to avoid extra colons.
- Give each actor an intention and state of mind with a grounded physical state. Let the person pursue that intention through the speech. Select the few prop actions that actually transfer attention; avoid a sequence of isolated blinks, thumb motions and prescribed nods.
- Speech belongs in `<d>[English] ... </d>` with `<inhale>` and `<pause>` at natural phrase boundaries. Keep the line word-exact while using breathable phrasing.
- The manner phrase intentionally handheld, slightly imperfect describes human correction. It must be paired with a measurable path in our scene.
- The supplied model stack is 10Eros Max H3 TURBO-hybrid, DaSiWa Ref2VA turbo v4 at 1.0, h3-realism-people at 1.0, lms v1.0 at 0.5 and Cinematic v01 at 1.625. This records the reference experiment; it is not a new installation or model change.

| Supplied speech measurement | Rate | Pitch range | Digital silence |
|---|---:|---:|---:|
| Civitai reference | 165 wpm | 22 semitones | 0%, room-tone floor -64 dBFS |
| Our 00283 | 138 wpm | 16.5 semitones | 21% |
| Our 00276 | 67 wpm | not measured in this comparison | 56% |

These are inherited coordinator results, not fresh audio analysis in this task. They justify conversational phrasing, intentions and an audible continuous location rather than an attempt to copy the clip's dialogue, setting, camera or acting ticks.

## 10. Camera numbers and our dialogue target

The old comparison remains useful when labelled as inherited measurement: civitai pan 0.10/0.15 and tilt 0.13/0.18 with 64% moving; 00276 first 120 s pan 0.08/0.02 and tilt 0.07/0.04 with 47% moving; 120–240 s pan 0.04/0.02 and tilt 0.06/0.05 with 38% moving. The newly reproduced Take A is pan 0.29/0.07 and tilt 0.28/0.10 with 91% moving.

**Scene 1 dialogue QA target** is moving **≥85%** of valid frames, median pan and tilt speed **0.20–0.35% of frame size per frame**, jitter **0.05–0.15**. Inspect visible travelling parallax as well as the scores. A face moving inside an otherwise fixed frame must not pass as operator travel. Cinematic action may exceed this band; the final fight's tilt jitter 0.99 would be wrong for the question even though it is authentic to that fight.

## 11. H3 speech in a long take

- A line sits **whole inside one window**. Stitches fall between lines, never inside a word, sentence or complete scripted line.
- **One speaker per window.** The node sends one library voice reference per window, the first speaker's timbre as `<Audio 1>`. The camera may look at a listener while that same speaker continues off screen.
- H3 performs the words itself. Voice references identify timbre; they do not authorize ElevenLabs or imported dialogue recordings.
- Every speaking direction includes **articulate, clear diction**, plus emotion, delivery, pace and the person/group addressed.
- Put breaths and pauses between existing words. Use an exact normalized-text check on `<d>` content before generation and Whisper word comparison after rendering.
- Stamp silent beats every **1.5–2 s** with visible mouths closed. In an occluder, describe the visible cloth/hand instead of inventing a mouth behind it.
- Every window carries the full soundscape. Also supply it at `timeline.overall_soundscape` when the coordinator wires the scene. A body prompt alone does not repair the engine's read location.

### Timing and the revised W1–W4 file

The builder's `NEW` tuples request **168, 377, 344, 301** frames. The compiled text reports **175, 379, 345, 311** frames after the 17n+5 window snapping, at 24 fps. The JSON deliverable retains the builder's input convention. W1–W3 keep **168, 377, 344**. W4 requests **445**, expected to snap to **447** frames, about **18.625 s**; the coordinator must confirm the compiled result before sampling.

W4 is deliberately lengthened because its original approximately 13 s included the close eye/bread handoffs plus a 27 m gate journey. After the handoffs that demanded roughly 3–4 m/s through seated people. The revision allows a purposeful approximately 2 m/s jog along the crowd edge and a slower final gate approach. Its beats and terminal view behind the two watchers are preserved. W2's complete question has about fourteen seconds of speaking time, compatible with a conversational rate near the supplied 165 wpm example. The expected compiled test length becomes about **56.08 s** instead of **50.42 s**. This timing change is explicit, not hidden in a prompt.

### Correct the later-window plan before wiring all 21

The supplied plan's evening owner decisions supersede its older recommendations for split lines, recorded speech and pictures on W1/W13/W19. These plates keep its story order and three-take design, with these necessary speech allocations shown in their captions and manifest:

| Windows | Speech-safe allocation |
|---|---|
| W5–W7 | Keep the naming line whole in W5, including the name-cued whip. W6 receives Hezron silently with bread. W7 owns Eleazar's whole answer; his line begins after the stitch rather than leaking into W6. |
| W8–W9 | W8 is the silent hand-to-hand return. W9 owns the complete found-sheep line, then the mother handoff; retime up to the TURBODS limit as needed. Do not divide it at the stitch. |
| W10–W12 | The first hard cut opens W11 on the woman with the gate's whole off-screen intrusion there. W12 owns the next gate speaker's complete accusation. |
| W13–W18 | Put the complete ten-silver question in W13, the mother's answer in W14, the complete found-coin line in W15, joy/nonverbal laughter in W16, the angels line in W17 and the bow response in W18. Check actual source-script word counts and durations before generation. |
| W19–W21 | W19 owns the scoff. W20 rises with Jesus, then carries Jotham's whole off-screen whisper after the rise and before the return whip. W21 opens on the now silent watcher, returns to Jesus and gives only him the whole two-sons line, followed by the requested 1.5 s breeze beat with his mouth closed. |

These are reviewable allocations, not edits to the locked script or live timeline. W5–W21 source-script text and final frame budgets remain a coordinator preflight gate. Only W1–W4 have revised deliverable prompt bodies in this task.

## 12. Pipeline facts (17 Oct)

These are the supplied node/test findings for `ComfyUI/custom_nodes/blokey316_long_take`, cross-checked against the read-only builder and compiled prompt examples. The node code was not changed or contacted in this task.

| Item | Fact | Status |
|---|---|---|
| TURBODS steps | Six simple steps plus one interpolated sigma in every gap produce 12 sampler steps. First two run at scene size ÷1.25, aligned to the 32 grid; the H3 3D latent upscaler expands ×1.25, then ten steps run with noise off. | Documented graph behaviour; the workflow label 10 STEPS does not mean ten total steps |
| Opening image | A pinned opening frame remains at first-pass size after upscaling; sampling fails with shape mismatch [N,96]. Open each window from words and cast/place references. | **Unfixed node bug** in the supplied test record |
| Own Turbo body | Each window needs its own `promptVariants.turbo` text. Without it `lt/turbo_prompt.convert` substitutes generic ambience and labels a subject as Picture 1 even without a picture. | **Unfixed converter defect**; explicit per-window Turbo text is the workaround |
| Soundscape location | Engine reads only `timeline.overall_soundscape`; Scene 1 had stored it in `characters.soundscape`. | **Unfixed field-location/schema bug**; coordinator supplies the field where read |
| decodeFrom | `h3.decodeFrom` compares saved TURBODS latents with first-pass dimensions and resamples instead of decoding. | **Unfixed node bug**; never promise a cheap decode-only resume |
| Length | TURBODS supports up to **464 frames**, 19.333 s at 24 fps. The other workflow rule is **345 frames**, 14.375 s. Confirm each workflow's snapping. | Workflow distinction, not a universal 345-frame cap |
| Test resolution | Final test is **1440 × 608**; first pass is 1152 × 480, then the aspect/grid-aware upscaler reaches the final grid. The ratio is approximately 2.37, slightly different from the 2.39 plate panels. | Supplied test setting; do not silently alter the node's aspect/grid |
| _turbods_upscaler race | Loop over `sys.modules` was made stable by iterating a copy. | **Fixed by coordinator earlier on 17 October**, not by this task |

Compiled `<Picture N>` cast references are not opening-frame pins. The body prompts contain no opening picture and use `@refN`; the coordinator's wrapper maps them to H3 subjects and pictures. With Ref2VA, a window may reach an identity not seen at its opening because the cast reference supplies it. Generated design boards do not replace these identity photographs.

Continuation/pinned-frame strategies remain subject to the current TURBODS defects. Do not claim that a detailed final-frame image or the phrase continues previous shot repairs a shape bug. A fully occluded stitch still needs matching cloth/crust/hand, direction, colour and speed. W4 ends in an open view, so its handoff to W5 needs explicit geometry and identity continuity rather than a newly invented full gatepost wipe.

## 13. Writing a Revenant window prompt

The deliverable is a window body for the node's H3 wrapper. The wrapper supplies subject definitions, retention, detailed description and sound fields. Do not paste a second contradictory wrapper inside it. Use ordinary paragraph breaks or bare headings, with **no colon except the one introducing the speaker line**. Decimal-second stamps such as `At 1.500 s` satisfy the body rule without time-code colons.

### Template

```text
Describe the opening physical view and the incoming stitch material, scale, light and screen direction. Identify principal people only by their assigned @refN slots.

Give each reached @refN an intention, a state of mind and a physical condition. Say whom the eyes attend to so nobody looks into the lens. Keep collective background listeners subordinate to the reached people.

Describe the spherical ultra-wide lens and deep focus, the visible foreground and distant geography, the actual light source and shade, and the restrained warm materials.

At 0.000 s describe the opening and the visible mouths closed before speech.
At successive decimal-second stamps give the motivated path in paces, arcs and heights. Silent intervals get closed-mouth stamps every 1.5–2 s. During speech give only the prop/camera beats that transfer attention.
@refN speaks once to the reached people, with emotion, delivery, loudness and pace, articulate, clear diction: <d>[English] Complete exact scripted line with optional <inhale> and <pause> between words.</d>

Describe the full continuous location sound, its changing perspective and the breeze/cloth/breath that carry through the incoming and outgoing stitch.

The shot ends on the named outgoing physical view, one continuous shot.
```

Use positive descriptions of what is present. Do not name an unwanted object/style in a negation. Write travel in paces, quarter-arcs and changes from knee to standing height, never inches or tiny drift. Never use holds or stays on in a window body. Describe only the people/place this window actually reaches. Protect a complete scripted line, even when its grammar contains a negative word. The required final form is `The shot ends on ..., one continuous shot.`

### Worked example — revised W2, identical to the JSON body

```text
A shaded cream veil with dark folds fills the opening frame and slides toward screen-right, revealing @ref2 seated beneath the old olive from his front side. This is the same cream cloth, light and screen direction that close the preceding window.

@ref2 wants the listeners to recognise their own care for a lost creature. He asks to invite an answer, with calm warmth and a curious, alert mind. His body is grounded on the limestone seat and his attention moves naturally between the loaf and the nearby listeners. His eyes follow these people and the bread.

A spherical ultra-wide 14 mm lens gives close faces their surrounding world, with the faces, terraced rows, olive trunks and lake all sharp in deep focus. The operator moves with a human walking rhythm, intentionally handheld, slightly imperfect, making small corrections within real travel. One low late-afternoon sun filters through dusty haze behind the olives. Leaf shadows cross skin and linen, and the shadow sides fall dark under brows and beards. A passing trunk briefly reveals a muted flare. Faces emerge from darker olive shade. The pale hazy sky and lake, sun-faded linen, dusty ochre, wool brown and olive-grey share one muted earth palette. Matte weathered skin shows pores, road dust and sweat, and the cloth is worn and dirty. Eyes attend to the reached listeners past the lens. First-century Galilee AD, a terraced olive hillside above the lake. There are 33 people in the whole scene, the named people and baby included, in a few loose groups on the slope. Nearby heads and shoulders are cut by the frame edges. Cloth is stained, patched and sweat-marked; loose stones, trampled grass, a dropped cloak and baskets lie between the groups. Fine film grain, slightly soft lens edges, slight blur in moving hands and a low-sun dust veil give the image an imperfect physical texture.

At 0.000 s the veil clears, revealing @ref2's face and the whole round loaf together in a very close wide view, his mouth closed. The seated rows and lake remain sharp behind him.
At 0.800 s he takes a natural breath and begins the question. The operator starts a slow quarter-arc from his side toward his front-left, at knee height.
@ref2 speaks once to the nearby listeners, warm, inviting, conversational in a mid-low voice, articulate, clear diction, with gentle emphasis on one, lost and find, at an easy talking pace: <d>[English] What man of you, having an hundred sheep, if he lose one of them, <pause> doth not leave the ninety and nine in the wilderness, <inhale> and go after that which is lost, until he find it?</d>
At 3.000 s the crust opens with a dry crack during the question. The camera travels with the bread, retaining the face and both hands in the same sharp frame.
At 6.000 s the quarter-arc continues across his front side and the lake shifts behind him through parallax.
At 9.000 s the operator continues the arc at an uneven human pace as @ref2 includes the nearest rows in the question.
At 12.000 s the camera begins its descent with the torn loaf while @ref2 completes the thought to the people around him.
At 14.800 s the complete question has finished and @ref2's mouth closes into a quiet, expectant smile.
At 15.300 s the camera dips with the crumbs toward the two torn halves on his knee, until the open crumb and crust fill the entire image.

The dry crust crack and falling crumbs sit inside the location sound.
A continuous soft breeze from the lake rustles the olive leaves in irregular gusts. Close cloth movement, quiet breathing and weight shifts of the seated crowd, sandals on limestone grit, occasional distant birds and faint water far below form an outdoor room tone under every moment and between the words. Its quiet floor is around minus sixty dBFS. Sound perspective travels with the operator and the same breeze carries through the stitch.

The shot ends on the torn loaf filling the frame, one continuous shot.
```

## 14. Scene 1 staging, paths and stitches

P2 uses an **opening-oriented local coordinate system**, not compass north. Page/screen right is +x, downhill toward the lake is +y at the top, and uphill/rear rows are at the bottom. The teaching seat is (0,0), the open gate is (27,0), and the rear-row camera looks downhill with the teacher/olive at screen left and the gate at screen right. This corrects attempt 2's mirrored map. The brief's three-o'clock gate is a screen/map relationship here, not a claim about the teacher's anatomical right or a surveyed compass bearing. The specified 27 m distance remains unchanged for this study.

The old olive shades the seat. Exactly 33 numbered people are drawn once on each take map: six named people inside (teacher, boy, Hezron, mother, baby and woman), 25 unnamed listeners in irregular terrace groups, and the two named watchers outside the gate. The baby has a separate count marker beside the mother. The boy sits near the teacher with his staff, sling and small bag. The mother/baby, Hezron and the woman occupy nearby loose groups. Narrow walkable gaps weave between people; the staging does not create a ceremonial central aisle.

The wall connects to both gate piers. The threshold is earth and the exterior grove shades the watchers. The operator remains on the teaching figure's front side during Take I. A front view of the watchers from the teaching side has exterior grove behind their faces; a rear gate view has the gathering beyond their backs. Each map gives window labels their own numbered legend and marks stitch positions and the two hard cuts without overlapping text.

**The 27 m constraint matters.** A whip rotates a viewpoint; it cannot carry an operator instantly from a gate close-up to a close face at the seat. On P2 those distant whip/mantle joins are dashed **concealed viewpoint relocations**, while solid lines show plausible local travel. This preserves the proposed stitched long-take illusion without claiming a physically continuous 27 m move. A literal continuous-operator version would require additional travel time and revised blocking. That issue is a preflight gate for the full-scene render, not permission to alter the owner-specified gate distance.

| Window | Open → key → end reference | Stitch to the next window |
|---|---|---|
| W1 | Rear wide → walk between rows → cream veil | S1 cream veil |
| W2 | Same veil → complete question/break loaf → torn loaf | S2 torn loaf |
| W3 | Torn loaf → young shepherd answer/return smile → hand and bread | S3 hand and bread |
| W4 | Same hand → bread travels to gate → behind shaded watchers | S4 open-view continuation, exact geometry required |
| W5 | Rear gate view → naming/profile turn → name-cued whip | S5 whip; concealed relocation to seat |
| W6 | Whip clears on Hezron → receiving bread → return whip | S6 whip; concealed relocation to gate |
| W7 | Gate → complete accusation → dark mantle | S7 mantle; concealed relocation |
| W8 | Mantle clears → bread through the woman → approach Jesus silently | S8 matching moving view, complete line deferred to W9 |
| W9 | Same approach → complete found-sheep line → mother/child and shawl | S9 shawl |
| W10 | Same shawl → bread to shepherd → rising wide of sharing rows | **Hard cut 1**, on the gate's intrusion at W11 |
| W11 | Woman close → hope and gate in deep context → profile/gateway relation | S10 continued view; gate-transit budget needs preflight |
| W12 | Gate arrival → accusation/tightening hand → mantle | S11 mantle |
| W13 | Dark shoulder clears → complete ten-silver question → matching two-shoulder view | S12 continuation |
| W14 | Counting hands → mother's answer → swaddling cloth | S13 swaddling |
| W15 | Swaddling → child then complete found-coin line → joy close | S14 continuation |
| W16 | Joy → lift over laughing rows/return → listener head crosses | S15 listener head |
| W17 | Head clears → Jesus/Hezron angels line → same two-person relation | S16 continuation |
| W18 | Hezron close → seated head bow → low camera beside the seated figure, eyes closed | **Hard cut 2**, on the scoff at W19 |
| W19 | Shaded watchers → scoff/divided light → whip toward teaching figure | S17 whip; concealed relocation |
| W20 | Whip clears → stands/hears off-screen whisper → return whip | S18 whip |
| W21 | Silent watcher → return to standing teacher/two-sons line → 1.5 s breeze | End of scene |

Three designed long takes, **two hard cuts and eighteen window stitches** remain the structure. The old 247 s/21-window timing is a sketch, not a locked speech-safe schedule after these corrections. The plates are staging/design references, not evidence that every full-scene transit or speech duration has passed render QA.

## 15. Before generating anything

This checklist gates production sampling and later Phase-4 first frames. This task is authorized to make the six design-reference boards after this bible review; it does not authorize a scene render or a first-frame batch.

- [ ] Review this bible and owner decisions before generating a design board or window.
- [ ] Assemble all required cast, environment and prop assets before any Phase-4 first frame; respect current owner holds and content locks.
- [ ] Confirm source script, exact words, speaker and one complete line per window. Allocate voice timbre only to that speaker.
- [ ] Use Ref2VA and the actual current cast photos, with a reference for every principal face reached. Audit each image-generation call's inputs; ≤5 cast/place references, ≤1 Scene 1 place frame, zero Revenant images.
- [ ] Apply both owner corrections in section 4. Measure every photographic panel with `tools/look_natural.py` and `tools/clean_meter.py`; redraw misses and retain raw results. Check the young boy, exactly 33 people in total, worn material, off-axis eyelines and seam-free panels. Neither look board enters generation.
- [ ] Verify the map, 27 m distance, eyelines, front-side camera rule, shade, connected wall and open threshold. Budget physical travel and identify every concealed viewpoint relocation.
- [ ] Confirm TURBODS, final 1440 × 608 grid, per-window frame snapping and ≤464 generated frames. Other workflows retain their own ≤345 rule.
- [ ] Verify there is no pinned opening image. Put the body's own text into `promptVariants.turbo`, and the full location sound in `timeline.overall_soundscape`.
- [ ] Compile without sampling and inspect actual H3 text, cast-to-subject mapping, first speaker's `<Audio 1>`, complete `<d>` line and soundscape. Do not trust earlier compiled text after changing the body.
- [ ] Compare incoming/outgoing stitch scale, direction, occluder, light, parallax and sound. S4 is an open-view continuity risk, not a full-frame wipe.
- [ ] Run the W1–W4 pilot and its QA before wiring a full 21-window scene. Confirm W4's increased budget and retime W5–W21 complete lines from the locked script.

## 16. After a render — QA targets

- **Camera** — run `feel2.py`; dialogue target ≥85% moving, pan/tilt 0.20–0.35%/frame, jitter 0.05–0.15. Visually confirm real parallax, changing height and correct destinations. Report masked brightness spikes separately from actual cuts.
- **Words** — Whisper must find every scripted line word-exact after punctuation/case normalization; compare medium.en and small.en where available, then listen to resolve disagreement. Count omissions, additions and repetitions explicitly. Natural breath/nonverbal acting may remain, while invented words fail.
- **Sound** — 0% digital silence; outdoor room-tone floor around **-60 dBFS**, allowing natural variation such as the reference clip's -64 dBFS. Measure sustained exact/near-zero gaps separately from quiet ambience, and inspect every seam for clicks, chopped breaths and sudden floor changes. Do not obtain the floor by adding implausibly loud hiss.
- **Stitches** — inspect every join on a **12-frame strip**, six before/six after, plus playback with audio. Check cloth/crust/hand, face, direction, camera speed, light, scale and sound perspective. A deliberately masked viewpoint reset must remain hidden through the whole reset.
- **Faces and anatomy** — compare **every visible principal face** against its actual cast picture, including profiles and newly reached faces. Check eyes, hands, bread, swaddling, duplicate people, wardrobe and eyelines. Design plates are not identity truth.
- **Look** — run `tools/look_natural.py` on every photographic panel and each assembled board. Meet the owner's section 4 targets, including colourfulness ≤24, real shadow ≥18%, luma 0.28–0.36, R−B +0.06–+0.14 and zero clipped highlights. Review the single-source shadow logic, cast identity and muted sky by eye; numerical passes cannot prove those things.
- **Texture** — run `tools/clean_meter.py`; sharpness ≤750 and grain ≥1.0 on each photographic plate. Inspect every panel separately, including small inserts, for softness, physical wear and real shadow.
- **Count and continuity** — 33 people total, including the baby and both gate watchers; the 17-year-old shepherd boy remains young and clean-shaven. Check W11’s successive arc positions and the left-teacher/right-gate orientation.
- **Evidence** — retain small metrics/strips and a truthful pass/fail report. No H3 footage was generated or speech/room-tone QA passed by this documentation-and-plates task.

## 17. Design reference plates

Original images of our film, first-century Galilee AD, late afternoon, on the terraced olive hillside above the lake. Photographic panels use spherical ultra-wide deep focus with gentle edge softness, one hazy low sun, actual dark shadow sides, lived-in people, visible grain and dusty matte earth colours in the owner's corrected look. Nobody looks into the lens. Labels sit below the images and never on faces. P2 is a deterministic schematic for legibility, not a simulated photograph.

| Plate | Content and use |
|---|---|
| `P1_LOOK_AND_LENS.png` | Ten panels, approximately the requested nine: close face with sharp context, walk through rows, trunk flare, bread baton pass, canopy tilt, the three separate veil/loaf/hand occluders, divided-light gate and descent with the bow. Shared design vocabulary for writers, image workers and reviewers. |
| `P2_SC01_STAGING_MAP.png` | Top-down map with all 33 numbered people, loose terrace groups, old olive/seat, lake, connected wall/open gate at 27 m, sun direction, local paths for W1–W21, S1–S18 and two hard cuts. Solid local paths and dashed concealed relocations are distinct. |
| `P3_LONGTAKE_I_W1-4.png` | Twelve panels, open/key/end for each pilot window. W4's longer route ends behind the watchers, matching the builder's terminal view. |
| `P4_LONGTAKE_I_W5-10.png` | Eighteen panels showing the name-cued whip, Hezron's reception, gate answer, bread's return, whole-line W9 and the sharing wide before cut 1. |
| `P5_LONGTAKE_II.png` | Twenty-four panels showing hope/judgment, the coin parable, mother/child, shared joy, angels line and descent beside the seated head bow, eyes closed, before cut 2. |
| `P6_LONGTAKE_III.png` | Nine panels showing divided light, the scoff, rising teacher, off-screen whisper allocation, return whip and two-sons line. |

Use these boards as references for writing, image design and review, **never as a first frame**. Open/key/end images illustrate states within a moving window, not three cuts. `plates/MANIFEST.json` records final dimensions, prompts and exact authorized inputs per generation. Multi-part boards record each generation separately so every call remains within five inputs while all reached identities can be referenced. The 21-window panel descriptions and staging model are stored beside the boards for audit.

## 18. Review status and remaining production gates

The bible review, whole-film measurement, six design-board specification and W1–W4 body revision precede plate generation. P1–P6 are supplied for coordinator/owner design review, not newly declared approved. A still board cannot demonstrate invisible stitching, word-exact generated speech or stable moving identity.

Before a full-scene render, the coordinator must inspect the updated compiled W1–W4 bodies and W4 length, verify current node bug status, budget the 27 m gate transitions and source-script lines in W5–W21, and resolve the open-view S4 stitch. Existing asset prerequisites and content locks remain binding. No request to ComfyUI, no scene save, no paid API, no git and no node/app change is required to review these artifacts.
