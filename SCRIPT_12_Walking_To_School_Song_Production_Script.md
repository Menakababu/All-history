# SCRIPT 12 — I Am Walking to School Today: a morning walk with buses, cycles and a happy puppy
### [TEMPLATE v3 — Google Flow only · song slots of 4/6/8/10 s, Flow clips generated at 8 s or 10 s · character, animal and prop sheets → a different spot per scene → per-scene reference image → per-scene video · global lock appended to every prompt · no on-screen text · eyes always open, always smiling · soundless dance clips]

**Duration:** 0:52 (estimated; the last line starts at 0:46 and the song is assumed to end at 0:52) | **Total Scenes:** 18 = 18 reference images = 18 videos (10 timed scenes + 8 bonus dance scenes)
**Image generation:** Google Flow only (Step 1 sheets, Step 2 location plan, Step 3 scene reference images)
**Video generation:** Google Flow — one video prompt per scene, each generated as an 8 s or 10 s clip (a song slot plus spare seconds to trim)
**Payoff:** Ravi and Priya walk to school with their puppy, wave at the buses and the cycles, spot the school ahead and run into a happy welcome from their teacher.
**Dialogue/Audio rule:** The generated clips are SOUNDLESS action videos: no singing, no lip movement, no voices, no music and no sound effects. Your recorded song is added in the edit; every scene is timed to the song.

**Assumptions made for the blank input fields (change if needed):**
- **Style:** 3D animated family-film look with vibrant colours, sparkle and glow. Tell me if you want 2D cartoon instead.
- **Characters:** the schoolboy Ravi and the schoolgirl Priya ("I" in the song, shown as two friends), their puppy Tommy, the teacher Madam, the yellow school buses, and two cycle friends. A bus driver appears only as a friendly extra.
- **Hard rules:** no on-screen text or lyrics; nobody sings or speaks; eyes always wide open; everyone always smiling; soundless clips; the children always stay on a safe footpath or pavement behind railings, far from moving vehicles.
- **Timing:** no audio file was attached; the song is assumed to end about 6 s after the last line begins (0:46), so the timed scenes run 0:00–0:52. Your transcript has a gap between 0:01 and 0:14 (the first line is only given at 0:01), so the first stanza is spread over 0:00–0:20 and marked "filled from the lyrics".

**Segment map**

| # | Segment | Scenes | Time |
|---|---|---|---|
| 1 | Verse 1: walking to school in the morning | S001–S003 | 0:00–0:20 |
| 2 | Verse 2: the buses | S004–S005 | 0:20–0:30 |
| 3 | Verse 3: the cycles | S006–S007 | 0:30–0:38 |
| 4 | Verse 4: the school is near; the welcome | S008–S010 | 0:38–0:52 |
| 5 | Bonus dance scenes (use anywhere in the edit) | S011–S018 | bonus (no timestamp) |

---

## ⚠️ GLOBAL LOCK BLOCK — append this in full to the END of every single prompt below (Step 1, every Step 3, every Step 4)

```
GLOBAL LOCK:
CONTINUITY — Keep Ravi (7-year-old boy: warm brown skin, white shirt, navy-blue shorts, red tie, green backpack), Priya (7-year-old girl: two braids with red ribbons, white blouse, navy-blue pinafore, red tie, yellow backpack), Tommy the golden-brown puppy with a red collar, Madam the teacher (pale-blue saree, black bun, bindi), the big yellow school bus (no writing or numbers) and the two cycle friends (red and green bicycles with silver bells) in exact face, colour, clothing and proportion continuity from their saved reference sheets — no redesign, recolor or scale drift. Every scene takes place in its own different spot of the same sunny storybook village and its roads. Never copy the previous scene's spot, background or composition.
CAST RULE — Every scene shows Ravi and Priya (the bonus scenes may add Tommy, Madam or the cycle friends). The buses appear in the bus verse, the cycle friends in the cycle verse, and Madam at the school. Only the characters named in a scene appear in it; a friendly bus driver is the only extra. No other people.
STYLE — 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination, a warm 35mm-lens depth of field, one consistent colour grade (sunny gold, fresh greens, sky blue, jewel colours), smooth appealing character animation with natural squash and stretch, and happy, bouncy dance moves that land on the beat of a sweet children's song.
EYE RULE — Everyone's eyes (the children's and all the animals') are wide open and fully visible in every single frame of every scene, from the first frame to the last: no blinking, no closing, no squinting, no winking, no sleeping, no half-closed or sleepy eyes, and no eyelid motion at all, even when smiling widely, cheering, spinning, hugging or waving.
EYE DESIGN — To make blinking impossible, every character has big, glossy, perfectly round eyes with large highlights and eyelids that are permanently fixed open (like toy or doll eyes); a smile only lifts the cheeks and mouth corners while the eyes stay perfectly round.
AVOID — closed eyes, blinking, squinting, eyes shut, winking, half-closed eyelids, sleepy eyes, laughing squint, eyes closed in a smile, eyelids covering the pupils, eyes rolling back.
SMILE RULE — Everyone is smiling happily in every frame, with joyful faces and energetic body language.
MOUTH RULE — Nobody sings, speaks or calls out. Everyone keeps a happy closed-mouth smile (beaks closed), and the dance is carried by bodies, arms, legs, heads, wings and tails.
SAFETY RULE — SAFETY RULE — The children always walk on a wide footpath or pavement behind railings, never on the road, and vehicles stay at a distance moving slowly; cyclists use a separate cycle lane; water is never near their feet. Fully child-friendly: nothing scary, sad or dangerous.
HARD RULES — No on-screen text, captions, lyrics, logos or watermarks. Faces never morph between shots.
ZERO AI ARTIFACTS — No closed or blinking eyes, no morphing, warping, melting, flicker, extra or duplicated limbs, wings, legs or characters, floating debris other than the intended sparkles and petals, texture smearing, distorted hands or feet, characters that change face or clothes.
LIGHTING — Follow the time of day and light written in each scene's prompt; no sudden unintended light jumps inside a shot.
AUDIO — The generated clip is SOUNDLESS: no sound effects, no music, no singing, no speech, no sound of any kind. (If Flow still adds a little ambience, mute it in the edit.) The recorded song is added in the edit.
CAMERA — Smooth, physically plausible motion only; each shot's opening camera motion matches the previous shot's closing motion vector for a seamless cut.
```

---

# STEP 1 — CHARACTER, ANIMAL & PROP REFERENCE IMAGES (Google Flow — image generation ONLY)

### 1A. Ravi (the boy)
**Portrait Image Prompt — Google Flow:**
Full-body portrait of a 7-year-old Indian schoolboy named Ravi standing in a happy energetic pose, facing the camera, with a clearly visible, fully expressive animated face: warm brown skin, round cheeks, big sparkling dark eyes wide open, short black hair, a huge bright smile with a closed mouth. He wears a white shirt, navy-blue shorts, a red tie, black shoes and a green school backpack. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination. Neutral light-grey background, soft key light. Eyes wide open, never closed. Locked reference design.
**Save as:** `Ravi_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Ravi_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) with the eyes wide open in every panel, locking the face.
**Save as:** `Ravi_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S001, S002, S003, S004, S005, S006, S007, S008, S009, S010, S011, S012, S013, S014, S015, S016, S017, S018.

### 1B. Priya (the girl)
**Portrait Image Prompt — Google Flow:**
Full-body portrait of a 7-year-old Indian schoolgirl named Priya standing in a happy energetic pose, facing the camera, with a clearly visible, fully expressive animated face: light-brown skin, rosy cheeks, big sparkling dark eyes wide open, two braids tied with red ribbons, a huge bright smile with a closed mouth. She wears a white blouse, a navy-blue pinafore, a red tie, black shoes and a yellow school backpack. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination. Neutral light-grey background, soft key light. Eyes wide open, never closed. Locked reference design.
**Save as:** `Priya_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Priya_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) with the eyes wide open in every panel, locking the face.
**Save as:** `Priya_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S001, S002, S003, S004, S005, S006, S007, S008, S009, S010, S011, S012, S013, S014, S015, S016, S017, S018.

### 1C. Tommy (the puppy)
**Portrait Image Prompt — Google Flow:**
A cute round golden-brown puppy named Tommy with floppy ears, a white chest, a wagging tail, big round shiny dark eyes wide open, a happy closed-mouth smile and a little red collar. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination. Neutral light-grey background, soft key light. Eyes wide open, never closed. Locked reference design.
**Save as:** `Puppy_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Puppy_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) with the eyes wide open in every panel, locking the face.
**Save as:** `Puppy_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S001, S002, S003, S008, S009, S010, S012, S015, S018.

### 1D. Madam (the teacher)
**Portrait Image Prompt — Google Flow:**
Full-body portrait of a kind Indian school teacher named Madam standing in a welcoming pose with open arms, facing the camera, with a clearly visible, fully expressive animated face: warm smile with a closed mouth, big warm dark eyes wide open, black hair in a neat bun, a small bindi. She wears a pale-blue cotton saree and carries a small book. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination. Neutral light-grey background, soft key light. Eyes wide open, never closed. Locked reference design.
**Save as:** `Teacher_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Teacher_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) with the eyes wide open in every panel, locking the face.
**Save as:** `Teacher_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S010, S016, S018.

### 1E. The big yellow school bus (prop)
**Portrait Image Prompt — Google Flow:**
A cheerful big yellow school bus with a rounded friendly front, two big round headlights, wide windows, a folding door and a black stripe along the side, with no writing, numbers or logos anywhere. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination. Neutral light-grey background, soft key light. Locked reference design.
**Save as:** `SchoolBus_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `SchoolBus_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up detail panels.
**Save as:** `SchoolBus_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S004, S005.

### 1F. The two cycle friends
**Portrait Image Prompt — Google Flow:**
Two friendly schoolchildren (a boy in a white shirt and navy shorts and a girl in a white blouse and navy pinafore) each riding a colourful bicycle (one red, one green) with a shiny silver bell on the handlebar, helmets on, with clearly visible, fully expressive animated faces, big sparkling dark eyes wide open and huge closed-mouth smiles. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination. Neutral light-grey background, soft key light. Eyes wide open, never closed. Locked reference design. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination. Neutral light-grey background, soft key light. Eyes wide open, never closed. Locked reference design.
**Save as:** `CycleKids_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `CycleKids_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) with the eyes wide open in every panel, locking the face.
**Save as:** `CycleKids_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S006, S007, S017.

---

# STEP 2 — LOCATION PLAN (no reusable environment plates: every scene is a different spot)

There are no shared environment-plate images. Each scene's Step 3 prompt describes its own spot, and `Environment Reference Image` is `none`. The table lists every spot so you can check none repeats.

| Scene | Time | Slot | Flow clip | Unique location |
|---|---|---|---|---|
| S001 | 0:00–0:08 | 8s | 10 s | A lane outside a blue house gate with a rangoli at early morning |
| S002 | 0:08–0:14 | 6s | 8 s | A leafy lane with coconut trees and morning mist |
| S003 | 0:14–0:20 | 6s | 8 s | A footpath beside a lotus pond at sunrise |
| S004 | 0:20–0:24 | 4s | 8 s | A wide pavement behind a low railing beside a main road |
| S005 | 0:24–0:30 | 6s | 8 s | A bus stop with a shelter and a friendly bus driver |
| S006 | 0:30–0:34 | 4s | 8 s | A tree-lined avenue with a wide footpath |
| S007 | 0:34–0:38 | 4s | 8 s | A little stone bridge with railings over a stream |
| S008 | 0:38–0:42 | 4s | 8 s | A bend in the road with the school roof visible on a green hill |
| S009 | 0:42–0:46 | 4s | 8 s | A flowering avenue of yellow trees leading to the school |
| S010 | 0:46–0:52 | 6s | 8 s | A colourful school gate with a welcoming teacher |
| S011 | bonus (no timestamp) | none | 8 s | A village street in light rain with shop awnings |
| S012 | bonus (no timestamp) | none | 8 s | A market lane with fruit stalls and hanging banana bunches |
| S013 | bonus (no timestamp) | none | 8 s | The wide stone steps of a village temple tank in morning sun |
| S014 | bonus (no timestamp) | none | 8 s | A playground with hopscotch squares and swings |
| S015 | bonus (no timestamp) | none | 8 s | A grassy village green with a big banyan tree |
| S016 | bonus (no timestamp) | none | 8 s | A school courtyard with lines of colourful flags |
| S017 | bonus (no timestamp) | none | 8 s | A shaded cycle track under flowering trees |
| S018 | bonus (no timestamp) | none | 8 s | A sunny classroom doorway with a shelf of books |

---

# STEP 3 & STEP 4 — SCENES (song slots of 4, 6, 8 and 10 seconds; every Flow video is generated at 8 or 10 seconds; soundless, eyes always open, always smiling)

**How each scene is shaped:**
Header line → **Song sync** (editor note only: the lyric words; they are not part of the Flow prompt) → Step 3 Ingredients → Step 3 Reference Image Prompt → Step 4 Ingredients → Video Prompt (Google Flow; second marks relative to the clip start; the dance beats first and spare seconds after) → Sound → Cut→.
The lyrics are NOT written inside the Flow prompts. Append the GLOBAL LOCK BLOCK to the end of every Step 3 and Step 4 prompt.

---

### Segment 1 — Verse 1: walking to school in the morning (Scenes 1–3) | 0:00–0:20

**S001 — Ravi and Priya step out for school | 0:00–0:08 (8s slot → generate 10s in Flow)**
Song sync: (0:01) "I am walking to school today."
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Ravi_Portrait.png`, `Ravi_6Angle.png`, `Priya_Portrait.png`, `Priya_6Angle.png`, `Puppy_Portrait.png`, `Puppy_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A lane outside a blue house gate with a rangoli at early morning) · Scene Continuity Reference: none (first scene in the series)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot in a lane outside a blue house gate with a colourful rangoli on the ground at early morning: the schoolboy Ravi (a white shirt, navy-blue shorts, a red tie, a green backpack) and the schoolgirl Priya (a white blouse, a navy-blue pinafore, a red tie, a yellow backpack) stepping out swinging their backpacks with big smiles, and a golden-brown puppy bouncing beside them, soft pink sunrise light. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S001_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S001_Ref.png`
Video Prompt (Google Flow, generate 10s: the first 8s carry the dance beats, the last 2s are spare footage):
I2V from `S001_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: the gate swings open and Ravi and Priya step out swinging their arms; 2–4s: the puppy bounces beside them as they march on the beat; 4–6s: they skip together down the lane; 6–8s: they turn and wave at the camera. 8–10s (spare 2s): the same joyful motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 8s slot or stretched. Slow push-in then a gentle pan with them. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, hugging or waving. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S002: Cut to a leafy lane.

**S002 — School today, school today | 0:08–0:14 (6s slot → generate 8s in Flow)**
Song sync: (0:14) "School today, school today." (filled from the lyrics: no timestamp was given for 0:08–0:14)
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Ravi_Portrait.png`, `Ravi_6Angle.png`, `Priya_Portrait.png`, `Priya_6Angle.png`, `Puppy_Portrait.png`, `Puppy_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A leafy lane with coconut trees and morning mist) · Scene Continuity Reference: `S001_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Medium tracking shot on a leafy lane with coconut trees and morning mist: the schoolboy Ravi (a white shirt, navy-blue shorts, a red tie, a green backpack) and the schoolgirl Priya (a white blouse, a navy-blue pinafore, a red tie, a yellow backpack) marching happily side by side with the puppy trotting beside them, sunbeams through the mist. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S002_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S002_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the dance beats, the last 2s are spare footage):
I2V from `S002_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: Ravi and Priya march in rhythm swinging their arms; 2–4s: the puppy trots and wags its tail on the beat; 4–6s: they hop together twice. 6–8s (spare 2s): the same joyful motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 6s slot or stretched. Smooth side-tracking shot. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, hugging or waving. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S003: Cut to a lotus pond path.

**S003 — Walking early in the morning | 0:14–0:20 (6s slot → generate 8s in Flow)**
Song sync: (0:14) "School today." (0:16) "I am walking to school today." (0:19) "Early in the morning."
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Ravi_Portrait.png`, `Ravi_6Angle.png`, `Priya_Portrait.png`, `Priya_6Angle.png`, `Puppy_Portrait.png`, `Puppy_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A footpath beside a lotus pond at sunrise) · Scene Continuity Reference: `S002_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot on a footpath beside a lotus pond at sunrise with pink lotus flowers: the schoolboy Ravi (a white shirt, navy-blue shorts, a red tie, a green backpack) and the schoolgirl Priya (a white blouse, a navy-blue pinafore, a red tie, a yellow backpack) walking happily with the puppy, golden reflections on the water, a few dragonflies. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S003_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S003_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the dance beats, the last 2s are spare footage):
I2V from `S003_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: Ravi and Priya swing their arms and walk on the beat; 2–4s: dragonflies zip past and the puppy hops; 4–6s: they stop, spread their arms to the sunrise and smile. 6–8s (spare 2s): the same joyful motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 6s slot or stretched. Slow crane along the pond. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, hugging or waving. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S004: Cut to the roadside pavement.

### Segment 2 — Verse 2: the buses (Scenes 4–5) | 0:20–0:30

**S004 — I see buses on the road | 0:20–0:24 (4s slot → generate 8s in Flow)**
Song sync: (0:21) "I see buses on the road." (0:23) "On the road, on the road."
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Ravi_Portrait.png`, `Ravi_6Angle.png`, `Priya_Portrait.png`, `Priya_6Angle.png`, `SchoolBus_Portrait.png`, `SchoolBus_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A wide pavement behind a low railing beside a main road) · Scene Continuity Reference: `S003_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot on a wide pavement behind a low sturdy railing beside a main road with a row of big yellow school buses driving slowly far away: the schoolboy Ravi (a white shirt, navy-blue shorts, a red tie, a green backpack) and the schoolgirl Priya (a white blouse, a navy-blue pinafore, a red tie, a yellow backpack) pointing at the buses with wide-eyed delighted smiles, morning light. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S004_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S004_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S004_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: Ravi and Priya point at the buses and bounce on their toes; 2–4s: the buses roll slowly past in the distance as the children wave. 4–8s (spare 4s): the same joyful motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. Over-the-shoulder slider move. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, hugging or waving. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S005: Cut to the bus stop.

**S005 — Beep, beep, they go | 0:24–0:30 (6s slot → generate 8s in Flow)**
Song sync: (0:25) "I see buses on the road." (0:28) "Beep, beep, they go."
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Ravi_Portrait.png`, `Ravi_6Angle.png`, `Priya_Portrait.png`, `Priya_6Angle.png`, `SchoolBus_Portrait.png`, `SchoolBus_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A bus stop with a shelter and a friendly bus driver) · Scene Continuity Reference: `S004_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Medium shot at a bus stop with a small shelter, far from the road edge: a big yellow school bus waiting with a friendly driver smiling and waving from the window, and the schoolboy Ravi (a white shirt, navy-blue shorts, a red tie, a green backpack) and the schoolgirl Priya (a white blouse, a navy-blue pinafore, a red tie, a yellow backpack) waving back and dancing happily, bright morning light. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S005_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S005_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the dance beats, the last 2s are spare footage):
I2V from `S005_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: the bus driver waves as Ravi and Priya wave back; 2–4s: the children pump a fist twice on the beat like pressing a horn; 4–6s: they dance a happy step together. 6–8s (spare 2s): the same joyful motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 6s slot or stretched. Slow push-in. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, hugging or waving. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S006: Cut to an avenue.

### Segment 3 — Verse 3: the cycles (Scenes 6–7) | 0:30–0:38

**S006 — I see cycles passing by | 0:30–0:34 (4s slot → generate 8s in Flow)**
Song sync: (0:30) "I see cycles passing by." (0:32) "Passing by, passing by."
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Ravi_Portrait.png`, `Ravi_6Angle.png`, `Priya_Portrait.png`, `Priya_6Angle.png`, `CycleKids_Portrait.png`, `CycleKids_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A tree-lined avenue with a wide footpath) · Scene Continuity Reference: `S005_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot on a tree-lined avenue with a wide footpath and a separate cycle lane: two children on bicycles (a red one and a green one) with helmets cycling past on the cycle lane, and the schoolboy Ravi (a white shirt, navy-blue shorts, a red tie, a green backpack) and the schoolgirl Priya (a white blouse, a navy-blue pinafore, a red tie, a yellow backpack) on the footpath waving at them with huge smiles, dappled light. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S006_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S006_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S006_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: the cyclists glide past in the cycle lane as Ravi and Priya wave; 2–4s: the children turn their heads with the cyclists and dance in place. 4–8s (spare 4s): the same joyful motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. Smooth tracking shot with the cyclists. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, hugging or waving. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S007: Cut to a bridge.

**S007 — Ching, ching, ching, they go | 0:34–0:38 (4s slot → generate 8s in Flow)**
Song sync: (0:34) "I see cycles passing by." (0:37) "Ching, ching, ching, they go."
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Ravi_Portrait.png`, `Ravi_6Angle.png`, `Priya_Portrait.png`, `Priya_6Angle.png`, `CycleKids_Portrait.png`, `CycleKids_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A little stone bridge with railings over a stream) · Scene Continuity Reference: `S006_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Medium shot on a little stone bridge with sturdy railings over a stream: the two cycle friends riding past ringing their silver bells, and the schoolboy Ravi (a white shirt, navy-blue shorts, a red tie, a green backpack) and the schoolgirl Priya (a white blouse, a navy-blue pinafore, a red tie, a yellow backpack) on the bridge walkway clapping to the rhythm with huge smiles, sparkling water below, bright light. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S007_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S007_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S007_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: the cyclists ring their bells three times as they pass; 2–4s: Ravi and Priya clap three times and bounce. 4–8s (spare 4s): the same joyful motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. Slow tracking shot. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, hugging or waving. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S008: Cut to a bend in the road.

### Segment 4 — Verse 4: the school is near; the welcome (Scenes 8–10) | 0:38–0:52

**S008 — Now my school is very near | 0:38–0:42 (4s slot → generate 8s in Flow)**
Song sync: (0:39) "Now my school is very near." (0:41) "Very near, very near."
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Ravi_Portrait.png`, `Ravi_6Angle.png`, `Priya_Portrait.png`, `Priya_6Angle.png`, `Puppy_Portrait.png`, `Puppy_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A bend in the road with the school roof visible on a green hill) · Scene Continuity Reference: `S007_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot at a bend in a quiet road with the school roof visible on a green hill ahead: the schoolboy Ravi (a white shirt, navy-blue shorts, a red tie, a green backpack) and the schoolgirl Priya (a white blouse, a navy-blue pinafore, a red tie, a yellow backpack) pointing at it with delighted wide eyes and big smiles, with the puppy jumping beside them, golden light. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S008_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S008_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S008_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: Ravi and Priya point at the school and jump with joy; 2–4s: the puppy bounces as they run a few happy steps. 4–8s (spare 4s): the same joyful motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. Smooth crane move following them. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, hugging or waving. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S009: Cut to a flowering avenue.

**S009 — Very near, very near | 0:42–0:46 (4s slot → generate 8s in Flow)**
Song sync: (0:43) "Now my school is very near."
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Ravi_Portrait.png`, `Ravi_6Angle.png`, `Priya_Portrait.png`, `Priya_6Angle.png`, `Puppy_Portrait.png`, `Puppy_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A flowering avenue of yellow trees leading to the school) · Scene Continuity Reference: `S008_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide symmetrical shot on an avenue of yellow flowering trees leading toward a colourful school: the schoolboy Ravi (a white shirt, navy-blue shorts, a red tie, a green backpack) and the schoolgirl Priya (a white blouse, a navy-blue pinafore, a red tie, a yellow backpack) skipping hand in hand with the puppy running ahead, petals drifting in the air, golden light. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S009_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S009_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S009_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: Ravi and Priya skip hand in hand as petals drift; 2–4s: the puppy races ahead and bounces back. 4–8s (spare 4s): the same joyful motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. Steady forward tracking shot. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, hugging or waving. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S010: Cut to the school gate.

**S010 — It's time to start the day | 0:46–0:52 (6s slot → generate 8s in Flow)**
Song sync: (0:46) "It's time to start the day." (outro)
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Ravi_Portrait.png`, `Ravi_6Angle.png`, `Priya_Portrait.png`, `Priya_6Angle.png`, `Puppy_Portrait.png`, `Puppy_6Angle.png`, `Teacher_Portrait.png`, `Teacher_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A colourful school gate with a welcoming teacher) · Scene Continuity Reference: `S009_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot at a colourful school gate with painted animals on the wall (no writing): the kind teacher Madam (a pale-blue saree, black bun) welcoming with open arms, the schoolboy Ravi (a white shirt, navy-blue shorts, a red tie, a green backpack) and the schoolgirl Priya (a white blouse, a navy-blue pinafore, a red tie, a yellow backpack) running up with huge smiles and wide-open eyes, and the puppy wagging its tail, bright morning light. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S010_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S010_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the dance beats, the last 2s are spare footage):
I2V from `S010_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: Ravi and Priya run up to the gate as Madam opens her arms; 2–4s: they jump together and give Madam a happy high-five; 4–6s: everyone waves at the camera in a happy pose. 6–8s (spare 2s): the same joyful motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 6s slot or stretched. Crane shot rising and pulling back. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, hugging or waving. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song is added in the edit)
Cut→END: Fade to black (trim in edit to land at the real end of the song).

---

### Segment 5 — Bonus dance scenes (Scenes 11–18) | bonus, no timestamp

**S011 — Bonus 1: umbrella dance in the rain | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any line of the song.
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Ravi_Portrait.png`, `Ravi_6Angle.png`, `Priya_Portrait.png`, `Priya_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A village street in light rain with shop awnings) · Scene Continuity Reference: `S010_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot on a village street in light rain with shop awnings and puddles: the schoolboy Ravi (a white shirt, navy-blue shorts, a red tie, a green backpack) and the schoolgirl Priya (a white blouse, a navy-blue pinafore, a red tie, a yellow backpack) dancing with colourful umbrellas and splashing happily, soft misty light. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S011_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S011_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S011_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: Ravi and Priya spin their umbrellas on the beat. 3–6s: they splash in a puddle together. 6–8s: they jump in a matching pose. Circling camera. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, hugging or waving. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S012: Use as a cutaway or loop anywhere in the edit.

**S012 — Bonus 2: fruit-stall market parade | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any line of the song.
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Ravi_Portrait.png`, `Ravi_6Angle.png`, `Priya_Portrait.png`, `Priya_6Angle.png`, `Puppy_Portrait.png`, `Puppy_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A market lane with fruit stalls and hanging banana bunches) · Scene Continuity Reference: `S011_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Medium shot in a market lane with fruit stalls and hanging banana bunches: the schoolboy Ravi (a white shirt, navy-blue shorts, a red tie, a green backpack) and the schoolgirl Priya (a white blouse, a navy-blue pinafore, a red tie, a yellow backpack) marching happily with the puppy trotting beside them, warm morning light. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S012_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S012_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S012_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: Ravi and Priya march and swing their arms on the beat. 3–6s: the puppy hops and wags its tail. 6–8s: they strike a happy pose. Tracking shot. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, hugging or waving. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S013: Use as a cutaway or loop anywhere in the edit.

**S013 — Bonus 3: temple-tank steps dance | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any line of the song.
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Ravi_Portrait.png`, `Ravi_6Angle.png`, `Priya_Portrait.png`, `Priya_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: The wide stone steps of a village temple tank in morning sun) · Scene Continuity Reference: `S012_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot on the wide dry stone steps of a village temple tank in morning sun (far from the water): the schoolboy Ravi (a white shirt, navy-blue shorts, a red tie, a green backpack) and the schoolgirl Priya (a white blouse, a navy-blue pinafore, a red tie, a yellow backpack) dancing together on a flat landing with their bags, a few pigeons fluttering. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S013_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S013_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S013_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: Ravi and Priya step side to side on the beat. 3–6s: they spin and clap. 6–8s: they raise their arms together. Crane pull-back. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, hugging or waving. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S014: Use as a cutaway or loop anywhere in the edit.

**S014 — Bonus 4: hopscotch before school | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any line of the song.
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Ravi_Portrait.png`, `Ravi_6Angle.png`, `Priya_Portrait.png`, `Priya_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A playground with hopscotch squares and swings) · Scene Continuity Reference: `S013_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Medium shot in a school playground with painted hopscotch squares and swings: the schoolboy Ravi (a white shirt, navy-blue shorts, a red tie, a green backpack) and the schoolgirl Priya (a white blouse, a navy-blue pinafore, a red tie, a yellow backpack) hopping through the squares with huge smiles, bright morning light. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S014_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S014_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S014_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: Ravi and Priya hop through the squares on the beat. 3–6s: they clap hands in a quick rhythm. 6–8s: they jump together. Low tracking shot. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, hugging or waving. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S015: Use as a cutaway or loop anywhere in the edit.

**S015 — Bonus 5: the puppy dance | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any line of the song.
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Ravi_Portrait.png`, `Ravi_6Angle.png`, `Priya_Portrait.png`, `Priya_6Angle.png`, `Puppy_Portrait.png`, `Puppy_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A grassy village green with a big banyan tree) · Scene Continuity Reference: `S014_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot on a grassy village green with a big banyan tree: the schoolboy Ravi (a white shirt, navy-blue shorts, a red tie, a green backpack) and the schoolgirl Priya (a white blouse, a navy-blue pinafore, a red tie, a yellow backpack) dancing with the puppy hopping and spinning around them, golden light. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S015_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S015_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S015_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: the puppy spins on the beat as Ravi and Priya clap. 3–6s: they dance in a circle around the puppy. 6–8s: they freeze in a happy pose. Slow orbit. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, hugging or waving. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S016: Use as a cutaway or loop anywhere in the edit.

**S016 — Bonus 6: school assembly dance | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any line of the song.
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Ravi_Portrait.png`, `Ravi_6Angle.png`, `Priya_Portrait.png`, `Priya_6Angle.png`, `Teacher_Portrait.png`, `Teacher_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A school courtyard with lines of colourful flags) · Scene Continuity Reference: `S015_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot in a school courtyard with lines of colourful flags (no writing): the schoolboy Ravi (a white shirt, navy-blue shorts, a red tie, a green backpack) and the schoolgirl Priya (a white blouse, a navy-blue pinafore, a red tie, a yellow backpack) dancing happily with the kind teacher Madam clapping beside them, bright morning light. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S016_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S016_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S016_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: Madam claps the rhythm as Ravi and Priya dance. 3–6s: Ravi and Priya spin in a circle. 6–8s: everyone waves. Crane shot rising. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, hugging or waving. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S017: Use as a cutaway or loop anywhere in the edit.

**S017 — Bonus 7: cycle-bell chorus | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any line of the song.
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Ravi_Portrait.png`, `Ravi_6Angle.png`, `Priya_Portrait.png`, `Priya_6Angle.png`, `CycleKids_Portrait.png`, `CycleKids_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A shaded cycle track under flowering trees) · Scene Continuity Reference: `S016_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot on a shaded cycle track under flowering trees with a wide footpath: the two cycle friends riding slowly and ringing their bells while the schoolboy Ravi (a white shirt, navy-blue shorts, a red tie, a green backpack) and the schoolgirl Priya (a white blouse, a navy-blue pinafore, a red tie, a yellow backpack) dance along the footpath, petals drifting. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S017_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S017_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S017_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: the cyclists ring their bells in a rhythm as Ravi and Priya dance. 3–6s: they wave and spin as petals fall. 6–8s: everyone smiles and waves. Smooth tracking shot. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, hugging or waving. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S018: Use as a cutaway or loop anywhere in the edit.

**S018 — Bonus 8: classroom door finale | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any line of the song.
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Ravi_Portrait.png`, `Ravi_6Angle.png`, `Priya_Portrait.png`, `Priya_6Angle.png`, `Teacher_Portrait.png`, `Teacher_6Angle.png`, `Puppy_Portrait.png`, `Puppy_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A sunny classroom doorway with a shelf of books) · Scene Continuity Reference: `S017_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Medium shot at a sunny classroom doorway with a shelf of colourful books: the schoolboy Ravi (a white shirt, navy-blue shorts, a red tie, a green backpack) and the schoolgirl Priya (a white blouse, a navy-blue pinafore, a red tie, a yellow backpack) waving from the doorway with the kind teacher Madam beside them and the puppy peeking in, bright light. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S018_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S018_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S018_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: Ravi and Priya wave and bounce at the doorway. 3–6s: Madam waves and the puppy wags its tail. 6–8s: everyone holds a happy pose. Slow pull-back. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, hugging or waving. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song is added in the edit)
Cut→END: Use as a cutaway or loop anywhere in the edit.

---

# PRODUCTION NOTES

- **Total required:** 18 reference images (`S001_Ref.png` … `S018_Ref.png`) and 18 videos, one video per image: 10 timed scenes that follow the song plus 8 bonus dance scenes. Plus the Step 1 sheets (6 portraits and 6 six-angle turnarounds = 12 images). There are no environment-plate images. Overall: 18 scene images + 12 sheet images = 30 images, and 18 videos.
- **Song structure (from your timestamps):** 0:01 "I am walking to school today"; 0:14 "school today, school today"; 0:16 "I am walking to school today"; 0:19 "early in the morning"; 0:21 "I see buses on the road"; 0:28 "beep, beep, they go"; 0:30 "I see cycles passing by"; 0:37 "ching, ching, ching, they go" (your lyrics say "tring, tring, tring"); 0:39 "now my school is very near"; 0:46 "it's time to start the day". Clips use even seconds, so lines on odd seconds start about 1 s into a clip; every clip has spare footage.
- **Transcript gap:** the timestamps jump from 0:01 to 0:14, so the first stanza is spread by the lyrics (S002 is marked "filled from the lyrics"). Send the audio or corrected timestamps and I will re-cut S001–S003.
- **Safety:** this is a road scene, so the children are shown only on footpaths and pavements behind railings, buses and cyclists stay in their own lanes at a distance, and the bridge has sturdy railings.
- **Eyes open, always smiling:** the lock block has a strengthened EYE RULE, an EYE DESIGN line (big glossy round toy-like eyes with permanently fixed-open eyelids) and an AVOID list; every image prompt starts with an eyes-open sentence; every video prompt starts and ends with eyes-open sentences. If a take still blinks: use another take, use only the first 4 s, regenerate from a clearly open-eyed scene image, or trim before the blink and cross-dissolve. Prompts cannot guarantee it, so check each clip.
- **Soundless clips:** no singing, voices, calls, music or sound effects, and everyone keeps a closed-mouth smile. Your recorded song is added in the edit.
- **What to generate in Flow (8 s or 10 s only):** 4 s and 6 s slots are generated at 8 s; 8 s and 10 s slots at 10 s. Each prompt puts the dance beats first and the spare seconds last, so you can trim a clip back to its slot or stretch it. The bonus scenes are 8 s.

| Generate in Flow | Number of videos | Footage | Scenes |
|---|---|---|---|
| 8 s | 17 | 136 s | S002, S003, S004, S005, S006, S007, S008, S009, S010, S011, S012, S013, S014, S015, S016, S017, S018 |
| 10 s | 1 | 10 s | S001 |
| **Total** | **18** | **146 s** | timed song 52 s; timed footage 82 s |

- **Slot plan (timed scenes):** the 4 s slots are S004, S006, S007, S008, S009 (5 clips, 20 s); the 6 s slots are S002, S003, S005, S010 (4 clips, 24 s); the 8 s slots are S001 (1 clips, 8 s); total 52 s.
- **Timeline rule:** put the song on the timeline at 0:00, drop each timed clip at its scene start time and trim it to its slot. The extra seconds are spare footage. The bonus scenes have no timestamp: use them as cutaways, or loop the song to make a longer video.
- **Image generation is Google Flow only.** Generate the 6 sheets first, then each scene image in order. Video prompts use each scene's saved image as the starting frame.
- **Reminder:** the GLOBAL LOCK BLOCK must be appended in full to the end of every prompt (Step 1, every Step 3 and every Step 4) before submission.
