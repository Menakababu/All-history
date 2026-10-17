# SCRIPT 02 — The Cry in the Ruins: Sgt. Ryker's Dawn Rescue
### [TEMPLATE v3 (action-rescue edition) — Google Flow only · clips of 4/6/8/10 s · character sheets → fixed environment plates → per-scene reference image → per-scene video · 9:16 STRICTLY for every image and video · global lock appended to every prompt · negative prompt on every video · no on-screen text · BGM + SFX only]

**Duration:** 0:30 | **Total Scenes:** 4 = 4 reference images = 4 videos (1 × 6 s, 3 × 8 s = 30 s, no trimming needed)
**Image generation:** Google Flow only (Step 1 character sheets, Step 2 fixed-environment plates, Step 3 scene reference images) — **aspect ratio 9:16 on every generation**
**Video generation:** Google Flow — one video prompt per scene, each exactly as long as its clip (6 or 8 s), Scene 1 from its reference image and Scenes 2–4 from the last frame of the previous clip, each carrying its own sound design and its own negative prompt
**Payoff:** A sergeant follows a baby's cry into a ruin, carries her out through an aftershock, and hands her to safety as the sun rises.
**Dialogue/Audio rule:** The clips contain NO speech of any kind: only instrumental BGM and diegetic SFX (the baby's non-verbal cry and coo are SFX). A single continuous master music track is provided in the Sound Design section for the edit.

**Logic fixes made to your story (so nothing contradicts itself):**
1. Your Step-3 image said the headlamp was **on**, but the video says he **switches it on** → the reference image now shows the headlamp **mounted but OFF**; it lights at 5.5 s in Scene 1.
2. Your image already shows his hand raised and head tilted, but the video began with him *raising* it → the video now starts **holding** that pose.
3. The building was described differently in each scene → one **fixed layout** (Environment Lock) and six environment plates, so every scene happens in the same ruin.
4. Sun direction was not defined → the low sun is **always at screen-left**, so the final shot can show the rising sun and the lighting never flips.
5. A shoulder cannot lift a concrete beam → it is a **timber joist** that he pivots leftward off the cradle; the cradle is never touched.
6. Medic appeared from nowhere → distant sirens in S1, an **ambulance behind a cordon** at the street end in S4, so her arrival is set up.
7. Flow only makes 4/6/8/10 s clips → **8 + 6 + 8 + 8 = 30 s** exactly. Beats 2–4 start at 0:08 / 0:14 / 0:22 (instead of 0:08 / 0:15 / 0:23); the story is unchanged.
8. The baby's cry and coo are allowed as sound effects; the no-dialogue rule still applies to every person.

**Segment map**

| # | Segment | Scenes | Time | Clip |
|---|---|---|---|---|
| 1 | The Cry | S001 | 0:00–0:08 | 8 s |
| 2 | Found Her | S002 | 0:08–0:14 | 6 s |
| 3 | Aftershock | S003 | 0:14–0:22 | 8 s |
| 4 | Safe | S004 | 0:22–0:30 | 8 s |

---

## ⚠️ GLOBAL LOCK BLOCK — append this in full to the END of every single prompt below (Step 1, Step 2, every Step 3, every Step 4)

```
GLOBAL LOCK:
ASPECT RATIO — STRICTLY 9:16 vertical portrait (1080x1920) for every image and every video. Never 16:9, 1:1, 4:3 or 4:5; no letterbox, pillarbox or black bars. Compose natively for vertical and keep faces and key action inside the central safe area.
NO OTHER CHANGES — Generate exactly what this prompt describes and nothing more: one continuous shot with no cuts, no extra characters, no extra props, no extra events, no new locations, no text. Do not add, remove, rename or restyle anything that is not written here.
CONTINUITY — Sgt. Ryker, Baby Mia (cream blanket with small yellow stars) and Medic Hale keep their exact faces, hair, skin tone, costume, colours and proportions from their saved reference sheets in every shot: no redesign, recolour, age change or scale drift.
FIXED ENVIRONMENT — One single location only, "The Ruin": a four-storey concrete apartment block seen from its street side. The screen-left two-thirds has pancaked into a sloping rubble mound; the right third is a cracked, slightly leaning standing facade with a wide lobby doorway at its base; a one-metre-high dark entry gap lies at the foot of the mound about 5 m left of the lobby doorway. Interior route: entry gap -> 8 m debris hall -> 3x3 m nursery (honey-coloured wooden cradle under a leaning timber joist) -> door in the nursery's right wall -> 12 m corridor (one leaning timber beam at head height, one 1 m gap in the floor) -> lobby doorway -> street. Never rearrange, mirror, rebuild or replace any part of this layout.
LIGHT — Daybreak. A low golden sun sits at the far SCREEN-LEFT end of the street and rakes warm light from screen-left to screen-right in every exterior shot; it never changes side. Interiors are dim, lit by the helmet headlamp (only AFTER its switch-on moment in Scene 1), floating dust and thin warm shafts. One colour grade throughout: warm amber-gold highlights, cool slate-teal shadows, muted concrete greys, natural skin tones.
STYLE — Photorealistic cinematic live-action, 35mm anamorphic lens look, shallow depth of field on close shots, fine natural film grain, real material physics: dust drifts and settles, concrete cracks and crumbles, fabric moves naturally.
HARD RULES — No on-screen text, captions, subtitles, logos or watermarks; no lettering on clothing, vehicles or signs. Human faces are clear, natural and fully rendered, identical in every shot (invented fictional faces). No gore, no blood, no visible injury. The baby is never dropped, struck, thrown or touched by falling debris: danger is shown by dust, shaking, shadow and sound.
ZERO AI ARTIFACTS — No morphing, warping, melting, flicker, extra or duplicated limbs/people/objects, floating debris, texture smearing, plastic skin, distorted hands or anatomy.
AUDIO — Instrumental cinematic BGM plus diegetic SFX only. No dialogue, narration or speech in any language; characters never speak (breathing and exertion only). The baby's non-verbal cry and coo are allowed SFX.
CAMERA — Smooth, physically plausible motion only; each shot opens with the camera motion the previous shot closed on.
```

**If Flow warns that a prompt is too long**, append this SHORT LOCK instead (the full detail is already inside each scene prompt):

```
GLOBAL LOCK (short): STRICT 9:16 vertical, no black bars. One continuous shot; add nothing that is not written. Same faces, costumes and star blanket as the saved sheets. Same fixed ruin layout; low golden sun always at screen-left. Photorealistic cinematic 35mm look, warm amber highlights, cool slate shadows. No text/logos, no gore, baby never harmed. No speech: music + SFX only (baby cry/coo allowed). No morphing, flicker, extra limbs or objects.
```

### NEGATIVE PROMPTS
Paste into Flow's negative-prompt field if it shows one; otherwise append to the end of the prompt as `AVOID: …`.

**NEG-IMG (all Step 1, 2 and 3 images):**
```
text, captions, subtitles, logos, watermarks, letters on clothing, 16:9, 4:3, 1:1, horizontal frame, letterbox, black bars, cropped head, extra people, extra limbs, extra fingers, distorted hands, morphing, face change, identity drift, plastic skin, waxy skin, cartoon, anime, illustration, painting, CGI look, video-game look, low resolution, blur, noise, gore, blood, fire, flames, rain, night, harsh midday sun, overexposure, floating debris, duplicate objects
```
**NEG-VID (master — every Step 4 video also adds its own scene-specific extras, which are printed under each video prompt):**
```
text, captions, subtitles, logos, watermarks, letters on clothing or vehicles, speech, talking, dialogue, narration, voice-over, lip movement, singing, humming, whispering, lyrics, choir, 16:9, 4:3, 1:1, horizontal frame, letterbox, black bars, pillarbox, cropped head, subject cut off, scene cut, jump cut, hard cut, zoom glitch, sudden lighting change, changing location, changed building layout, mirrored layout, extra people, crowd, bystanders, animals, fire, flames, explosion fireball, gore, blood, injury, baby harmed, baby dropped, baby thrown, morphing, warping, melting, face change, identity drift, age change, extra limbs, extra fingers, fused fingers, distorted hands, duplicate baby, duplicate characters, floating objects, floating debris, flicker, jitter, frame stutter, texture smearing, plastic skin, waxy skin, cartoon, anime, illustration, painting, 3D render look, video-game look, uncanny face, changed costume, changed helmet colour, missing helmet, missing rescue rope, different blanket pattern, sun on the wrong side, night, rain, snow, harsh overexposure, big lens-flare blobs, time-lapse, unrequested slow motion
```

### Quick Flow settings
- Aspect ratio **9:16** on every image and every video. Audio **on** for videos. Generate 2–4 variations and keep the best one.
- Scene 1 = *Frames to video* from `S001_Ref.png`. Scenes 2–4 = *Frames to video* from the **exact last frame** of the previous accepted clip (pause on the final frame and save it as a still). The `S00X_Ref.png` image is the visual target and the fallback start frame if the saved last frame is blurry.
- Attach the listed subject sheets and environment plates as ingredients wherever Flow allows it.

---

# STEP 1 — CHARACTER REFERENCE IMAGES (Google Flow — image generation ONLY, 9:16)

### 1A. Rescue Sergeant ("Sgt. Ryker")
**Portrait Image Prompt — Google Flow:**
Vertical 9:16 full-body standing portrait of Sgt. Ryker, a rugged urban search-and-rescue sergeant in his early 40s, facing the camera in a neutral relaxed pose, with a clearly visible, fully detailed face: square jaw, olive-tan skin with fine sun lines, three-day dark stubble, warm hazel-brown eyes, strong straight brows, a thin pale scar through the outer end of the left eyebrow, short dark-brown hair visible at the temples, a calm, determined, quietly caring expression. Matte charcoal-grey rescue helmet with a small black headlamp mounted on the front (lamp switched OFF, lens dark) and a chin strap; a dust-grey neck gaiter pulled down around the neck; dark-olive rescue jacket under a sand-coloured strap harness vest; a coil of orange-and-black rescue rope fixed on the LEFT side of the vest; a small black radio clipped to the left shoulder strap; black leather-palmed gloves; olive cargo trousers with knee pads; worn tan-grey boots; three-chevron sergeant insignia on both sleeves (symbol only, no letters), no logos, no text. Dust-streaked, worn fabrics. Neutral grey seamless background, soft key light from upper left, macro detail on skin texture, stitching, rope weave and helmet scratches. An invented fictional face. Locked reference design.
**Save as:** `Ryker_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Ryker_Portrait.png` as exact reference, generate ONE vertical 9:16 character sheet in four rows: row 1 FRONT and REAR full-body; row 2 LEFT SIDE and RIGHT SIDE; row 3 TOP-DOWN and BOTTOM/UNDERCARRIAGE (boots and ground contact); row 4 three close-up face panels (front, left profile, right profile) locking the face. Neutral grey seamless background, matched lighting and scale, neutral standing pose in every panel, headlamp OFF, no labels or text.
**Save as:** `Ryker_6Angle.png`
**Usage note:** Attach both files to every scene where this character appears: S001–S004.

### 1B. Baby Mia ("Mia")
**Portrait Image Prompt — Google Flow:**
Vertical 9:16 portrait of Baby Mia, a healthy seven-month-old baby girl, swaddled in a soft cream cotton blanket printed with small, evenly spaced yellow five-pointed stars (about 3 cm each) and a thin pale-yellow hem, lying on her back on a neutral surface with her head turned slightly toward the camera so her face is clearly visible: round rosy cheeks, large dark-brown eyes, a few soft dark-brown curly wisps of hair, tiny nose, small relaxed mouth, calm and curious expression; one tiny hand free near her chin. Neutral grey seamless background, soft warm key light from upper left, macro detail on skin, eyelashes and cotton weave. An invented fictional baby. Locked reference design.
**Save as:** `Mia_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Mia_Portrait.png` as exact reference, generate ONE vertical 9:16 sheet in four rows: row 1 HEAD-END view and FOOT-END view; row 2 LEFT SIDE and RIGHT SIDE; row 3 TOP-DOWN and UNDERSIDE (back of the swaddle); row 4 three close-up face panels (front, left profile, right profile) locking the face. Same swaddle, same star pattern and spacing in every panel, neutral grey background, matched lighting and scale, no labels or text.
**Save as:** `Mia_6Angle.png`
**Usage note:** Attach both files to every scene where this character appears: S002–S004 (and the Nursery plate in Step 2).

### 1C. Field Medic ("Medic Hale")
**Portrait Image Prompt — Google Flow:**
Vertical 9:16 full-body standing portrait of Medic Hale, a calm, capable paramedic woman in her late 30s, facing the camera in a neutral relaxed pose, with a clearly visible, fully detailed face: light-brown skin, dark-brown almond eyes, strong dark brows, a small mole under the right eye, black hair pulled into a tight low bun, a focused, kind, reassuring expression. Bright orange-red high-visibility paramedic jacket with two silver reflective bands (no text or symbols), navy cargo trousers, black boots, blue nitrile gloves, a green medical backpack with a plain blank white square panel, and a folded dove-grey wool blanket with a soft blue edge stripe draped over her LEFT forearm. Neutral grey seamless background, soft key light from upper left, macro detail on skin, fabric weave and reflective tape. An invented fictional face. Locked reference design.
**Save as:** `Medic_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Medic_Portrait.png` as exact reference, generate ONE vertical 9:16 character sheet in four rows: row 1 FRONT and REAR full-body; row 2 LEFT SIDE and RIGHT SIDE; row 3 TOP-DOWN and BOTTOM/UNDERCARRIAGE (boots and ground contact); row 4 three close-up face panels (front, left profile, right profile) locking the face. Neutral grey seamless background, matched lighting and scale, neutral pose with the blanket on the left forearm in every panel, no labels or text.
**Save as:** `Medic_6Angle.png`
**Usage note:** Attach both files to every scene where this character appears: S004.

---

# STEP 2 — FIXED ENVIRONMENT PLATES (Google Flow — image generation ONLY, 9:16)

One building, one layout. These plates lock the geography so every scene happens in the same ruin. Generate them before any scene image.

**Layout map (top-down, for your reference — not an image prompt):**

```
STREET (cordon + ambulance at far RIGHT end; low sun at far LEFT end)
        ◀── sun                                          ambulance ──▶

[ RUBBLE CREST ]        (entry GAP)   5 m   [LOBBY DOORWAY]  ← exit to street
  collapsed 2/3  ─────────┐            ┌──────────────┘
                          │ DEBRIS     │  CORRIDOR 12 m
                          │ HALL 8 m   │  beam @4 m · floor gap @9 m
                          ▼            │
                    [ NURSERY 3×3 m ] ─┘  (door in RIGHT wall)
                    cradle on back wall, joist leaning from the left
```

| Plate | Name | Save as | Used in |
|---|---|---|---|
| 2A | The Ruin — exterior from the rubble crest | `Ruin_A_Exterior_Crest.png` | S001 |
| 2B | The Ruin — debris hall (interior, entry side) | `Ruin_B_DebrisHall.png` | S002 |
| 2C | The Ruin — nursery with cradle | `Ruin_C_Nursery.png` | S002–S003 |
| 2D | The Ruin — corridor, view back toward the nursery | `Ruin_D1_Corridor_ToNursery.png` | S003 |
| 2E | The Ruin — corridor, view toward the exit | `Ruin_D2_Corridor_ToExit.png` | S003 (reverse-angle reference) |
| 2F | The Ruin — street in front of the building | `Ruin_E_Street.png` | S004 |

### 2A. The Ruin — exterior from the rubble crest
**Environment Image Prompt — Google Flow:**
Vertical 9:16 photorealistic wide establishing shot of the Ruin at first light, seen from a low position on the crest of the rubble mound in the street-side foreground (empty crest at lower-left, no people): a four-storey 1970s beige-grey concrete apartment block: the screen-left two-thirds has pancaked into a sloping mound of broken floor slabs, rebar, bricks, a bent steel balcony railing and one torn pale-blue curtain; the right third is a still-standing, cracked, slightly leaning facade with empty window openings on four floors and a wide lobby doorway at its base (cracked concrete lintel, one slab leaning beside it); a one-metre-high dark triangular entry gap at the foot of the mound about 5 m to the left of the lobby doorway. A dust-hazed empty street behind the camera, no vehicles, a pale gold-pink sky, a low golden sun just out of frame at the far SCREEN-LEFT raking warm light across the rubble from left to right, fine dust floating in the light, long soft shadows falling to the right, quiet and tense mood. Locked environment layout.
**Save as:** `Ruin_A_Exterior_Crest.png`

### 2B. The Ruin — debris hall (interior, entry side)
**Environment Image Prompt — Google Flow:**
Vertical 9:16 photorealistic interior shot looking inward along an 8 m low, narrow debris hall, from just inside the one-metre entry gap (no people): sloping concrete slabs overhead, protruding rebar, a rubble-strewn floor, dust floating in thin beams, a soft warm golden glow spilling in from behind the camera, and at the far end a low doorway into a darker room. Dim, dusty, tense; cool slate-teal shadows and warm amber highlights. Locked environment layout.
**Save as:** `Ruin_B_DebrisHall.png`

### 2C. The Ruin — nursery with cradle
**Environment Image Prompt — Google Flow:**
Using the saved Mia sheets for the baby: vertical 9:16 photorealistic interior of a 3x3 m ground-floor nursery with a cracked ceiling and faded pale-yellow wallpaper (no people except the baby). A small honey-coloured wooden cradle with a scalloped headboard stands against the back wall; Baby Mia lies in it swaddled in the cream blanket with small yellow stars, calm. A 3 m timber ceiling joist, 15 cm thick, has fallen and leans from the broken ceiling at upper-left down over the cradle with a 20 cm clear gap above the baby, touching neither the cradle nor the baby. A doorway is in the RIGHT wall (leading to the corridor) and the low doorway to the debris hall is in the front wall (behind the camera). One thin warm sun shaft falls through a ceiling crack onto the floor to the left of the cradle; dust floats in the air. Locked environment layout.
**Save as:** `Ruin_C_Nursery.png`

### 2D. The Ruin — corridor, view back toward the nursery
**Environment Image Prompt — Google Flow:**
Vertical 9:16 photorealistic interior view from the lobby-doorway end looking back along a narrow 12 m corridor toward the nursery door (no people): 1.5 m wide, cracked walls, hanging ceiling panels, dust haze; a timber beam wedged at head height at 4 m from the nursery door; a clean 1 m-wide gap in the floor at 9 m with darkness below; the nursery doorway at the far end, dim. Strong warm golden sunlight comes from behind the camera (the lobby doorway), lighting the dust and the corridor walls. Locked environment layout.
**Save as:** `Ruin_D1_Corridor_ToNursery.png`

### 2E. The Ruin — corridor, view toward the exit
**Environment Image Prompt — Google Flow:**
Vertical 9:16 photorealistic interior view from the nursery-door end looking along the same narrow 12 m corridor toward the lobby doorway (no people): the same timber beam wedged at head height at 4 m, the same 1 m floor gap at 9 m, hanging ceiling panels, dust haze, and at the far end the lobby doorway blazing with warm golden daylight. Locked environment layout, identical to the saved `Ruin_D1_Corridor_ToNursery.png` seen from the opposite direction.
**Save as:** `Ruin_D2_Corridor_ToExit.png`

### 2F. The Ruin — street in front of the building
**Environment Image Prompt — Google Flow:**
Vertical 9:16 photorealistic wide low shot from the middle of the empty street, about 15 m from the lobby doorway, looking at the Ruin (no people): a four-storey 1970s beige-grey concrete apartment block: the screen-left two-thirds has pancaked into a sloping mound of broken floor slabs, rebar, bricks, a bent steel balcony railing and one torn pale-blue curtain; the right third is a still-standing, cracked, slightly leaning facade with empty window openings on four floors and a wide lobby doorway at its base (cracked concrete lintel, one slab leaning beside it); a one-metre-high dark triangular entry gap at the foot of the mound about 5 m to the left of the lobby doorway. Cracked asphalt with dust and scattered bricks, no other vehicles. At the far SCREEN-RIGHT end of the street a plain white ambulance with an orange stripe (no text, no markings) is parked behind a plain red-and-white cordon tape, its blue emergency lights flashing. The low golden sun sits just above the rooftops at the far SCREEN-LEFT end of the street, raking long warm light and shadows from left to right; haze, floating dust, calm and tense. Locked environment layout, identical in structure to the saved `Ruin_A_Exterior_Crest.png` seen from the street.
**Save as:** `Ruin_E_Street.png`

---

# STEP 3 & STEP 4 — SCENES (clips of 6 and 8 seconds)

**How each scene is shaped:** Header (scene number, label, time range, clip length) → **Story beat** → **Entry state** → Step 3 Ingredients → Step 3 Reference Image Prompt → Step 4 Ingredients → Video Prompt (exact clip length, in-clip second marks where `0s` = clip start) → **Negative prompt (video)** → Sound → **Exit state** → Cut→.
Append the GLOBAL LOCK BLOCK to every Step 3 and Step 4 prompt. In Step 4, paste the **Sound** text at the end of the video prompt under the line `AUDIO DIRECTION:` (the PASTE-READY file already does this).

### Segment 1 — The Cry | 0:00–0:08

**S001 — The Cry | 0:00–0:08 (8s)**
Story beat: Dawn. Ryker hears a faint cry and enters the ruins.
Entry state: Ryker stands on the rubble crest, back-left three-quarter to camera, RIGHT hand raised for silence, head tilted listening, headlamp OFF.
Step 3 Ingredients: Subject Reference Images: `Ryker_Portrait.png`, `Ryker_6Angle.png` · Environment Reference Images: `Ruin_A_Exterior_Crest.png` · Scene Continuity Reference: none (first scene)
Step 3 — Reference Image Prompt (Google Flow, 9:16):
Vertical 9:16 cinematic shot. Sgt. Ryker (use the character reference) stands on the crest of the rubble mound in front of the collapsed apartment block at dawn (layout exactly as the saved Ruin_A environment reference), his RIGHT hand raised for silence, head tilted as he listens toward the ruins. His helmet headlamp is mounted on the helmet but switched OFF (lens dark); the orange-and-black rescue rope is on the LEFT of his vest. Low angle from behind-left, his face visible in soft three-quarter rear profile, shallow depth of field. The dark entry gap is visible at the foot of the mound ahead-right of him and the lobby doorway at the far right edge of the frame. Golden raking light from screen-left, dust floating in the light, tense quiet mood, photorealistic.
Save as: `S001_Ref.png`
Step 4 Ingredients: Starting Frame: `S001_Ref.png` · Also attach: `Ryker_Portrait.png`, `Ryker_6Angle.png`, `Ruin_A_Exterior_Crest.png`
Video Prompt (Google Flow, 8s, 9:16):
Vertical 9:16, cinematic, no text, no subtitles. I2V from `S001_Ref.png`, one continuous shot, 8 seconds. 0–2s: the pose from the image is held (right hand raised, head tilted) while the camera makes a very slow push-in from low behind-left; dust drifts in the golden light; the headlamp stays OFF. At 2s a very faint baby's cry drifts out of the ruins (heard, never seen). 2–3s: Ryker's head snaps toward the entry gap, eyes locked on it, and the raised hand lowers. 3–5.5s: he climbs carefully down the rubble toward the gap, the camera following from behind-left at the same low height. At 5.5s he taps the headlamp switch on his helmet with his right hand and the beam lights. 5.5–7s: he crouches and ducks through the gap, the camera following him to the threshold. 7–8s: inside the 8 m debris hall he moves away from the camera, headlamp beam cutting through the floating dust, warm golden light spilling from the gap behind the camera onto his back. Last frame: Ryker seen from behind, about 3 m from the camera, beam aimed at the low doorway at the far end of the hall. Nothing else happens: no other people, no collapse, no fire. No speech, narration, whispering or lip movement: characters never speak. Audio is music and sound effects only.
Save as: `S001_Video.mp4` · also save the final frame as `S001_LastFrame.png` (start frame for the next scene)
Negative prompt (video): NEG-VID master + headlamp lit before 5.5s, Ryker already walking at 0s, loud or close baby cry, baby visible, other rescuers, vehicles, ambulance, collapse or aftershock, fire, Ryker facing the camera, camera cut.
Sound (BGM+SFX only, no voice or speech): BGM: sparse low cello drone on D, airy pad, a high violin harmonic at 2s on the cry, a distant sub-heartbeat pulse (60 BPM) from 4s. SFX: light dawn wind, trickling settling debris, very faint distant sirens, three faint baby cries at 2s / 3.5s / 5s, boots on gravel and concrete, concrete creaks, a soft click at 5.5s as the headlamp turns on, dull interior hush from 7s.
Exit state: Ryker from behind in the debris hall, ~3 m from camera, headlamp ON, beam aimed at the low nursery doorway; warm light from behind camera; camera moving forward.
Cut→S002: continuous — the last frame of this clip is the first frame of S002 (same viewpoint, same forward camera motion).

### Segment 2 — Found Her | 0:08–0:14

**S002 — Found Her | 0:08–0:14 (6s)**
Story beat: He finds Baby Mia in a cradle and lifts her out gently.
Entry state: Same as S001's exit: Ryker from behind in the debris hall, headlamp ON, beam toward the nursery doorway.
Step 3 Ingredients: Subject Reference Images: `Ryker_Portrait.png`, `Ryker_6Angle.png`, `Mia_Portrait.png`, `Mia_6Angle.png` · Environment Reference Images: `Ruin_B_DebrisHall.png`, `Ruin_C_Nursery.png` · Scene Continuity Reference: last frame of the S001 clip (fallback: `S001_Ref.png`) — identity, headlamp state and colour grade only
Step 3 — Reference Image Prompt (Google Flow, 9:16):
Vertical 9:16 cinematic shot inside the debris hall of the Ruin (layout exactly as the saved Ruin_B environment reference). Sgt. Ryker (use the character reference) is seen from behind, about 3 m from the camera, walking away down the hall, headlamp ON with a bright narrow beam aimed at the low doorway of the nursery at the far end, floating dust lit in the beam, warm golden light spilling from the entry gap behind the camera onto his back and shoulders, rescue rope on the left side of his vest. Tense, dusty, photorealistic.
Save as: `S002_Ref.png`
Step 4 Ingredients: Starting Frame: the exact last frame of the S001 clip (fallback: `S002_Ref.png`) · Also attach: `Ryker_Portrait.png`, `Ryker_6Angle.png`, `Mia_Portrait.png`, `Mia_6Angle.png`, `Ruin_B_DebrisHall.png`, `Ruin_C_Nursery.png`
Video Prompt (Google Flow, 6s, 9:16):
Vertical 9:16, cinematic, no text, no subtitles. Image-to-video from the start frame, one continuous shot, 6 seconds, same hall as the start frame. 0–1.5s: Ryker ducks through the low doorway at the end of the hall into the nursery (layout as the Nursery reference), the camera following from behind-right at shoulder height; the headlamp beam sweeps across the floating dust and the faded pale-yellow wallpaper. 1.5–2.5s: the beam lands on the honey-coloured wooden cradle against the back wall, under the leaning timber joist; Baby Mia lies in it wrapped in the cream blanket with small yellow stars; the cries fade to one soft whimper and stop as the light touches the blanket (the beam never shines into her eyes). 2.5–3.7s: he kneels on his right knee and, with his right shoulder under the joist, slowly pushes it leftward until it rests securely against the left wall; it never touches the cradle or the baby. 3.7–5s: both hands lift Baby Mia out gently, one under her head and back, one under her body; she coos softly. 5–6s: he draws her against the left side of his chest, her head in the crook of his left arm and his right hand cupping her head, and looks down at her with a relieved, tender expression while the camera arcs smoothly to a warm front three-quarter medium close-up. Last frame: Ryker kneeling on his right knee beside the empty cradle, Mia cradled as described, face visible, headlamp beam aimed down-left at the floor. No speech, narration, whispering or lip movement: characters never speak. Audio is music and sound effects only.
Save as: `S002_Video.mp4` · also save the final frame as `S002_LastFrame.png` (start frame for the next scene)
Negative prompt (video): NEG-VID master + joist touching or falling on the baby, debris falling on the baby, cradle moved or tipped, baby's face covered, loud baby crying, baby held upside down, two babies, lifting the joist with the hands instead of the shoulder, headlamp beam aimed into the baby's eyes, headlamp off, nursery different from reference, other people.
Sound (BGM+SFX only, no voice or speech): BGM: the cello drone warms; the sub-heartbeat pulse STOPS at 4.2s as he lifts her; solo piano enters at 4.2s with a slow four-note motif (D–F–A–G); gentle string swell from 5s. SFX: boots on gravel, dust hiss, one soft baby whimper at 2s, a low wood groan as the joist slides (2.8s) and a soft thud as it settles (3.6s), cloth rustle, soft baby coos at 4.3s and 5.3s, Ryker's relieved exhale at 5.5s.
Exit state: Ryker kneeling on right knee beside the empty cradle, Mia in his left arm against his chest, his right hand cupping her head, face visible, beam down-left; slow push-in.
Cut→S003: continuous — same pose, same room, same framing; the shake begins right after the cut.

### Segment 3 — Aftershock | 0:14–0:22

**S003 — Aftershock | 0:14–0:22 (8s)**
Story beat: An aftershock hits. He shields her and runs for the exit.
Entry state: Same as S002's exit: Ryker kneeling, Mia in his left arm, right hand cupping her head.
Step 3 Ingredients: Subject Reference Images: `Ryker_Portrait.png`, `Ryker_6Angle.png`, `Mia_Portrait.png`, `Mia_6Angle.png` · Environment Reference Images: `Ruin_C_Nursery.png`, `Ruin_D1_Corridor_ToNursery.png`, `Ruin_D2_Corridor_ToExit.png` · Scene Continuity Reference: last frame of the S002 clip (fallback: `S002_Ref.png`)
Step 3 — Reference Image Prompt (Google Flow, 9:16):
Vertical 9:16 cinematic medium close-up inside the nursery of the Ruin (layout exactly as the saved Ruin_C environment reference, but the cradle now EMPTY). Sgt. Ryker (use the character reference) kneels on his right knee beside the empty cradle, Baby Mia (use the character reference) cradled against the left side of his chest in the crook of his left arm, his right hand cupping her head, face visible and looking down at her tenderly. Headlamp ON with the beam aimed down-left at the floor; the fallen joist rests against the left wall; the doorway to the corridor is in the right wall behind him; one thin warm sun shaft from a ceiling crack; dust floating. Warm, intimate, photorealistic.
Save as: `S003_Ref.png`
Step 4 Ingredients: Starting Frame: the exact last frame of the S002 clip (fallback: `S003_Ref.png`) · Also attach: `Ryker_Portrait.png`, `Ryker_6Angle.png`, `Mia_Portrait.png`, `Mia_6Angle.png`, `Ruin_C_Nursery.png`, `Ruin_D1_Corridor_ToNursery.png`, `Ruin_D2_Corridor_ToExit.png`
Video Prompt (Google Flow, 8s, 9:16):
Vertical 9:16, cinematic, no text, no subtitles. Image-to-video from the start frame, one continuous shot, 8 seconds, handheld camera with controlled shake. 0–0.7s: hold on the kneeling pose. At 0.7s the room shakes: dust pours from the ceiling cracks, cracks race across the wall behind him, the empty cradle rattles. 0.7–2.2s: Ryker curls his body protectively around Baby Mia, shoulders turned to the ceiling and his right hand cupping her head, rises to his feet in one motion and turns to the doorway in the nursery's right wall. 2.2–4.5s: the camera is now AHEAD of him, tracking backwards along the 12 m corridor and facing him as he runs toward the camera, Mia held against the left side of his chest with his right hand cupping her head; strong warm golden sunlight from the lobby doorway behind the camera lights his face and the dust. 4.5–5.7s: he ducks under the timber beam wedged at head height; ceiling panels crash down behind him and kick up dust, never touching him or Mia. 5.7–7s: he leaps over the 1 m gap in the floor and lands steady, keeping Mia level and protected. 7–8s: the glare ahead grows; he keeps running toward the camera, face determined. Last frame: Ryker mid-stride toward the camera, about 3 m from the lobby doorway, Mia protected against his chest, dust-filled corridor behind him, bright golden glare behind the camera. No speech, narration, whispering or lip movement: characters never speak. Audio is music and sound effects only.
Save as: `S003_Video.mp4` · also save the final frame as `S003_LastFrame.png` (start frame for the next scene)
Negative prompt (video): NEG-VID master + baby dropped, baby thrown, baby raised above the head, baby exposed to falling debris, debris hitting Ryker or Mia, Ryker stumbling or falling, Ryker running away from the light, corridor different from reference, exit dark, extra rooms, extra people, fireball, static camera with no shake, slow motion, blanket pattern changing.
Sound (BGM+SFX only, no voice or speech): BGM: a sudden low brass-and-sub braam hit at 0.7s; war-drum / taiko ostinato at 150 BPM from 2.2s with low strings repeating a tight rhythmic figure; rising tension riser from 4.5s to 8s; no melody, pure urgency. SFX: deep rumbling that grows to cracking concrete (0.7s), cascading dust hiss, a short startled baby cry at 1s then settling whimpers, rattling cradle, pounding boots, ragged breathing, ceiling-panel crashes at 4.7s and 5.2s, a hard landing thud at 6.9s.
Exit state: Ryker mid-stride running toward camera in the corridor, ~3 m from the lobby doorway, Mia on his left chest, bright glare behind camera; camera tracking backwards.
Cut→S004: match cut on the same screen direction and subject scale — he continues running toward camera, now out in the street.

### Segment 4 — Safe | 0:22–0:30

**S004 — Safe | 0:22–0:30 (8s)**
Story beat: He bursts out as the building collapses behind him. A medic takes the baby. Sunrise.
Entry state: Ryker running toward camera at the lobby doorway threshold, Mia on his left chest.
Step 3 Ingredients: Subject Reference Images: `Ryker_Portrait.png`, `Ryker_6Angle.png`, `Mia_Portrait.png`, `Mia_6Angle.png`, `Medic_Portrait.png`, `Medic_6Angle.png` · Environment Reference Images: `Ruin_E_Street.png` · Scene Continuity Reference: last frame of the S003 clip (fallback: `S003_Ref.png`)
Step 3 — Reference Image Prompt (Google Flow, 9:16):
Vertical 9:16 cinematic low wide shot at sunrise in the street in front of the Ruin (layout exactly as the saved Ruin_E environment reference). Sgt. Ryker (use the character reference) bursts out of the lobby doorway at the base of the still-standing cracked facade, running toward the camera in mid-stride about 12 m from it, Baby Mia (use the character reference) held against the left side of his chest in the cream star blanket, his right hand cupping her head, dust puffing out of the doorway behind him, face determined and lit by golden light from screen-left. The ambulance with flashing blue lights waits far right behind the cordon tape; the low golden sun is at the far screen-left. Photorealistic.
Save as: `S004_Ref.png`
Step 4 Ingredients: Starting Frame: the exact last frame of the S003 clip (fallback: `S004_Ref.png`) · Also attach: `Ryker_Portrait.png`, `Ryker_6Angle.png`, `Mia_Portrait.png`, `Mia_6Angle.png`, `Medic_Portrait.png`, `Medic_6Angle.png`, `Ruin_E_Street.png`
Video Prompt (Google Flow, 8s, 9:16):
Vertical 9:16, cinematic, no text, no subtitles. Image-to-video from the start frame, one continuous shot, 8 seconds, camera low in the street, 12 m from the doorway, facing the building. 0–1.5s: Ryker sprints out of the lobby doorway toward the camera with dust puffing behind him, Mia against his chest. 1.5–3.5s: behind him the cracked standing facade and upper floors fold straight down into the rubble (collapsing inward and downward, never outward onto the street) in a huge rolling dust cloud that billows and thins before reaching him; he keeps sprinting toward the camera without looking back. 3.5–5s: Medic Hale runs in from screen-right with the folded dove-grey blanket and meets him mid-frame; Ryker carefully hands over Baby Mia; she wraps the grey blanket around Mia over the cream star blanket, whose stars stay visible at the edge; Mia coos. 5–6.3s: Ryker rests his hands on his thighs, exhales deeply, straightens and looks up toward the low rising sun at the upper screen-left, warm golden light across his face and helmet. 6.3–8s: slow pull-back to a wide shot: Ryker at centre-left, Medic Hale holding Mia at centre-right, the settling dust cloud over the ruin, the sun disc just above the rooftops at screen-left, the ambulance's lights flashing far right; the image fades smoothly to black over the last 0.7s. No speech, narration, whispering or lip movement: characters never speak. Audio is music and sound effects only.
Save as: `S004_Video.mp4`
Negative prompt (video): NEG-VID master + collapse falling toward or onto Ryker or Mia, debris hitting people, Ryker looking back or stumbling, additional medics, stretcher, firefighters, crowd, press, helicopter, vehicles other than the one ambulance, text or markings on the ambulance, medic grabbing the baby roughly, cream star blanket disappearing, different medic face, sun on the wrong side, sun not visible at the end, 'THE END' title card.
Sound (BGM+SFX only, no voice or speech): BGM: the percussion peaks with a huge impact at 1.5s as the facade falls, then the music DROPS OUT at 3.5s leaving only natural sound; at 4.5s the solo piano motif (D–F–A–G) returns resolved in D major with warm strings swelling to 6.5s; a long sustained final chord that decays to silence at 8s. SFX: pounding sprint footsteps and heavy breathing 0–3.5s, deep rolling collapse rumble with crumbling concrete and a ground-shaking sub-boom (1.5–3.5s), settling dust hiss, soft baby coo at 4.3s and 5s, the medic's quick boots, distant sirens, Ryker's long exhale at 5.5s, a final gentle breeze.
Exit state: Fade to black.
Cut→End of video (fade to black).

---

# SOUND DESIGN MASTER (BGM · SFX · mix)

**Why this exists:** each Flow clip generates its own audio, so the music can "restart" at every cut. For a seamless Short, generate the clips with audio, keep their **SFX**, and lay the one continuous **master track** below underneath. Mute the clips' music in the edit if it clashes.

**Master BGM prompt (any AI music generator — 30 s, instrumental):**
```
Cinematic instrumental underscore, exactly 30 seconds, no vocals, no choir, no lyrics. Four continuous movements. 0:00–0:08 'The Cry': sparse low cello drone on D, airy pad, a single high violin harmonic at 0:02, a distant sub-heartbeat pulse at 60 BPM entering at 0:04; hushed, tense. 0:08–0:14 'Found Her': the heartbeat stops at 0:12; a slow solo-piano motif (D–F–A–G) enters at 0:12 with a gentle cello and string swell; warm, tender, relieved. 0:14–0:22 'Aftershock': a violent low brass-and-sub braam hit at 0:14, then taiko and war-drum ostinato at 150 BPM with tight low-string rhythm figures and a rising tension riser to 0:22; urgent, no melody. 0:22–0:30 'Safe': a huge impact at 0:23.5, then the music drops to near-silence for one second, then the piano motif returns resolved in D major with warm strings swelling to 0:28 and a long sustained final chord that decays to silence at 0:30.
```

**Cue sheet (what must be heard, second by second):**

| Time | Music | SFX |
|---|---|---|
| 0:00–0:02 | Low cello drone fades in | Dawn wind, trickling debris, faint distant sirens |
| 0:02 | High violin harmonic | First very faint baby cry |
| 0:03–0:05 | Drone holds; heartbeat pulse starts at 0:04 | Cry again (0:03.5 and 0:05), boots on rubble |
| 0:05.5 | Pulse continues | Soft click — headlamp on |
| 0:06–0:08 | Pulse + drone, darker | Concrete creaks, interior hush |
| 0:10 | Drone warms | Single soft whimper, then silence |
| 0:11–0:12 | Heartbeat stops at 0:12 | Wood groan, soft thud as the joist settles |
| 0:12–0:14 | Solo piano motif enters; strings swell | Soft baby coos, Ryker's relieved exhale |
| 0:14.7 | BRAAM hit, sub drop | Deep rumble → cracking concrete, dust pours, cradle rattles, startled baby cry |
| 0:16–0:20 | Taiko ostinato 150 BPM, riser starts | Pounding boots, ragged breath, ceiling panels crash (0:18.7, 0:19.2) |
| 0:20–0:22 | Riser peaks | Hard landing thud (0:20.9), growing glare whoosh |
| 0:22–0:23.5 | Percussion at full intensity | Sprint, breath, dust puffs |
| 0:23.5–0:25.5 | Giant impact, then music ducks out at 0:25.5 | Facade collapse: deep rolling rumble, crumbling concrete, sub-boom |
| 0:25.5–0:26.5 | Near silence | Dust hiss, footsteps, breathing, distant sirens |
| 0:26.5–0:28.5 | Piano motif returns in D major; strings swell | Medic's boots, baby coo (0:26.3, 0:27), Ryker's long exhale (0:27.5) |
| 0:28.5–0:30 | Final chord sustains and decays to silence | Soft breeze; everything fades with the picture |

**Mix guide:** SFX stem –6 dB peak, master BGM –14 dB under SFX, collapse and braam hits allowed to peak at –3 dB; duck music 6 dB under every baby sound; 6-frame audio crossfades at each cut; target loudness –14 LUFS for YouTube Shorts / Reels.

# QC CHECKLIST (run on every generated clip before moving on)

- [ ] Frame is 9:16, no black bars, no text anywhere.
- [ ] Ryker's, Mia's and Hale's faces match the sheets; costume, rope on the LEFT of the vest, helmet colour unchanged.
- [ ] S001: headlamp is OFF until ~5.5 s; he enters through the gap, not through the lobby.
- [ ] S002: joist never touches the cradle or baby; he lifts it with the shoulder; the blanket shows yellow stars.
- [ ] S003: nothing falls on Mia; order is shake → run → duck under beam → panels fall → leap gap → bright exit.
- [ ] S004: collapse is behind him and never reaches him; medic takes Mia; cream star blanket still visible; sun disc at screen-left in the final wide; fade to black.
- [ ] Sun / key light is from screen-left in all exterior shots; same ruin layout in every shot.
- [ ] The last frame of each clip matches the entry state of the next scene (see Exit state / Entry state).

# SHORTS PUBLISHING (optional)

- **Title ideas:** "He Followed a Baby's Cry Into a Collapsing Building" · "30 Seconds Before the Aftershock"
- **Description:** A rescue sergeant hears a faint cry inside a collapsed building. Seconds before the aftershock, he finds her. AI-generated cinematic short.
- **Hashtags:** #shorts #rescue #hero #cinematic #aivideo #googleflow #veo
- Keep the AI-generated / altered-content disclosure switched on when you upload.
