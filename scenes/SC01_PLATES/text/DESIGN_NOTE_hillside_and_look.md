| **Hillside (frame)** | Exactly 33 people (your Scene 1 rule) in loose groups across a big hillside, with the lake and far shore beyond, so the scale comes from depth, not headcount; bread passing hand to hand, children, a donkey tethered at the wall. | A breeze off the lake moving veils and olive leaves; dust kicked up by latecomers; smoke from a cooking fire; at dusk, the fire's sparks rising. | Lake water, the murmur of the crowd, a child, birds in the olives. At dusk, the fire crackling and crickets. |
| 1 | **Hillside: the murmur** | Publicans and sinners draw near; bread passes; Hezron at Jesus's knee. At the gate: "His own father will not say his name." Jotham and Eleazar murmur: "This man receiveth sinners, and eateth with them." Jesus turns toward the gate: the parable is spoken *unto them* (Luke 15:3). The lost sheep, short: the shepherd boy answers "He doth. Every shepherd doth.", ending on Luke 15:7 ("ninety and nine just persons, which need no repentance"). "A certain man had two sons." We know who this story is aimed at. | 2.25 |

## 2d. Look, camera and assets

Grok's light, palette and texture, with your camera rules and the Revenant decisions in place of Grok's camera.

**Frame.** 2.39:1, 2048×864 video (locked 29 Sep). Delivered as Rec.709.

**Light (Grok's, corrected).**
- Available light only, from one source. Outdoors, the sun through dust and haze, at each scene's real hour (Scene 1: a low sun through haze). Indoors, a doorway, a window, a clay lamp or the hearth.
- No fill, reflector, beauty light or glamour rim. The shadow side of a face falls dark under the brow, beard and chin (Grok's Caravaggio reference is right).
- Warmth is restrained. The feast is warmer than the far country, but never golden. The famine is a hard, pale, dry light.

**Palette and texture.**
- One sun-faded earth family: dusty linen, ochre, wool brown, olive-grey, chalk, weathered skin. The one rich colour at home is the purple hem on Asher's tunic.
- A pale, hazy sky, never a saturated blue. The city of Fortune gets a little more colour from torches and dyed cloth, still inside the gate below.
- Lived-in: worn wool, dust, chaff, crumbs, motivated sweat, ungroomed hair and beards, cracked lips, dirt in the creases.
- An imperfect camera: fine grain, soft edges, slight motion blur, haze veiling the distance.

**Measured on every location asset and every render** (`look_natural.py`, `clean_meter.py`): brightness 0.28–0.36, real shadow ≥ 18%, colourfulness ≤ 24, no blue sky, sharpness ≤ 750, grain ≥ 1.0.

**Lens.** Spherical ultra-wide, about 14 mm, with deep focus: a very close face and a readable world in the same frame (your 17 Oct decision). Prompts describe it in words, not lens numbers, because image models ignore those: "the face very close and big in frame, the people and hillside behind it still sharp". An extreme close-up still means the face fills the frame, off-centre.

**Camera.**
- A handheld human operator: small irregular sways and framing corrections, with real travel (a stride, an arm's length, a quarter-circle arc, a long pull-back).
- Never a locked tripod, a gimbal float or a "hold".
- Measured with `feel2.py`: moving in ≥ 85% of frames, pan/tilt 0.2–0.35, jitter 0.05–0.15.
- Stillness only by choice: the exhausted face in the pig field, a huge landscape.
- Long takes are several H3 windows joined at hidden stitches (an occluder, a whip pan, a flare). The ewe handover is stitched on her fleece (Eliab holds her out; the next window opens in Asher's arms), the cold open's throws on whip pans, and the run on the sun's flare (the faceless runner with references off, the face reveal with Eliab's on); the tests are in `H3_TEST_RISK_AND_VOICE.md`. Ref2VA with the cast references on, so the camera can reach anyone: the reference supplies the face.
- Eyes look past the lens, never into it. No posed lineups.

