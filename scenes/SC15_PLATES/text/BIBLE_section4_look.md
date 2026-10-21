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

