# SCRIPT 11 — Bam Bam Bus Song: a children's tour of the village, the orchard, the birds, the waterfall and the mountain
### [TEMPLATE v3 — Google Flow only · song slots of 4/6/8/10 s, Flow clips generated at 8 s or 10 s · character, animal and prop sheets → a different spot per scene → per-scene reference image → per-scene video · global lock appended to every prompt · no on-screen text · eyes always open, always smiling · soundless dance clips]

**Duration:** 1:12 (estimated; the last line starts at 1:05 and the song is assumed to end at 1:12) | **Total Scenes:** 21 = 21 reference images = 21 videos (13 timed scenes + 8 bonus dance scenes)
**Image generation:** Google Flow only (Step 1 sheets, Step 2 location plan, Step 3 scene reference images)
**Video generation:** Google Flow — one video prompt per scene, each generated as an 8 s or 10 s clip (a song slot plus spare seconds to trim)
**Payoff:** Arun and Meena ride the village bus through the town and countryside, share guava and cucumber with the squirrel and the rabbit, dance with the koel and the peacock, admire the waterfall and the mountain, and finish with a big dance on the hilltop.
**Dialogue/Audio rule:** The generated clips are SOUNDLESS action videos: no singing, no lip movement, no voices, no music and no sound effects. Your recorded song is added in the edit; every scene is timed to the song.

**Assumptions made for the blank input fields (change if needed):**
- **Style:** 3D animated family-film look with vibrant colours, sparkle and glow. Tell me if you want 2D cartoon instead.
- **Characters:** the boy Arun and the girl Meena (the children in the song, "we"), and the village bus. The living things follow the lyrics: a squirrel (guava), a rabbit (cucumber), a koel (cuckoo) and a peacock. The waterfall and the mountain are shown as scenery.
- **Hard rules:** no on-screen text or lyrics; nobody sings, speaks or calls; eyes always wide open; everyone always smiling; soundless clips; the children stay safely inside the bus or far from edges and water.
- **Timing:** no audio file was attached; the song is assumed to end about 7 s after the last line begins (1:05), so the timed scenes run 0:00–1:12.

**Segment map**

| # | Segment | Scenes | Time |
|---|---|---|---|
| 1 | Intro: the bus arrives | S001 | 0:00–0:10 |
| 2 | Verse 1: bam bam, we ride and laugh; silu silu | S002–S004 | 0:10–0:26 |
| 3 | Verse 2: the squirrel and the rabbit | S005–S007 | 0:26–0:42 |
| 4 | Verse 3: the koel and the peacock | S008–S010 | 0:42–0:56 |
| 5 | Verse 4: the waterfall and the mountain; finale | S011–S013 | 0:56–1:12 |
| 6 | Bonus dance scenes (use anywhere in the edit) | S014–S021 | bonus (no timestamp) |

---

## ⚠️ GLOBAL LOCK BLOCK — append this in full to the END of every single prompt below (Step 1, every Step 3, every Step 4)

```
GLOBAL LOCK:
CONTINUITY — Keep Arun (7-year-old boy: warm brown skin, sky-blue shirt, khaki shorts, yellow cap, small cloth bag), Meena (7-year-old girl: two braids with yellow ribbons, red frock with white dots, straw hat), the orange-and-sky-blue village bus (no writing or numbers), the red-brown squirrel with a guava, the white rabbit with a cucumber, the glossy black koel with red eyes and the royal blue peacock in exact face, colour, clothing and proportion continuity from their saved reference sheets — no redesign, recolor or scale drift. Every scene takes place in its own different spot of the same sunny storybook Tamil countryside. Never copy the previous scene's spot, background or composition.
CAST RULE — Every scene shows Arun and Meena (the bonus scenes may show one of them with a friend). The bus appears in the bus scenes; the squirrel, rabbit, koel and peacock appear in their own verses. Only the characters named in a scene appear in it. No other people.
STYLE — 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination, a warm 35mm-lens depth of field, one consistent colour grade (sunny gold, fresh greens, sky blue, jewel colours), smooth appealing character animation with natural squash and stretch, and happy, bouncy dance moves that land on the beat of a sweet children's song.
EYE RULE — Everyone's eyes (the children's and all the animals') are wide open and fully visible in every single frame of every scene, from the first frame to the last: no blinking, no closing, no squinting, no winking, no sleeping, no half-closed or sleepy eyes, and no eyelid motion at all, even when smiling widely, cheering, spinning, hugging or waving.
EYE DESIGN — To make blinking impossible, every character has big, glossy, perfectly round eyes with large highlights and eyelids that are permanently fixed open (like toy or doll eyes); a smile only lifts the cheeks and mouth corners while the eyes stay perfectly round.
AVOID — closed eyes, blinking, squinting, eyes shut, winking, half-closed eyelids, sleepy eyes, laughing squint, eyes closed in a smile, eyelids covering the pupils, eyes rolling back.
SMILE RULE — Everyone is smiling happily in every frame, with joyful faces and energetic body language.
MOUTH RULE — Nobody sings, speaks or calls out. Everyone keeps a happy closed-mouth smile (beaks closed), and the dance is carried by bodies, arms, legs, heads, wings and tails.
SAFETY RULE — SAFETY RULE — The children only ride inside the bus (hands and scarves out of the windows, never heads or bodies), dance on the ground and stay behind sturdy railings or far from water and edges. Fully child-friendly: nothing scary, sad or dangerous.
HARD RULES — No on-screen text, captions, lyrics, logos or watermarks. Faces never morph between shots.
ZERO AI ARTIFACTS — No closed or blinking eyes, no morphing, warping, melting, flicker, extra or duplicated limbs, wings, legs or characters, floating debris other than the intended sparkles and petals, texture smearing, distorted hands or feet, characters that change face or clothes.
LIGHTING — Follow the time of day and light written in each scene's prompt; no sudden unintended light jumps inside a shot.
AUDIO — The generated clip is SOUNDLESS: no sound effects, no music, no singing, no speech, no sound of any kind. (If Flow still adds a little ambience, mute it in the edit.) The recorded song is added in the edit.
CAMERA — Smooth, physically plausible motion only; each shot's opening camera motion matches the previous shot's closing motion vector for a seamless cut.
```

---

# STEP 1 — CHARACTER, ANIMAL & PROP REFERENCE IMAGES (Google Flow — image generation ONLY)

### 1A. Arun (the boy)
**Portrait Image Prompt — Google Flow:**
Full-body portrait of a 7-year-old Tamil boy named Arun standing in a happy energetic pose, facing the camera, with a clearly visible, fully expressive animated face: warm brown skin, round cheeks, big sparkling dark eyes wide open, a huge bright smile with a closed mouth. He wears a sky-blue shirt, khaki shorts, a small yellow cap and sandals, with a little cloth bag across his chest. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination. Neutral light-grey background, soft key light. Eyes wide open, never closed. Locked reference design.
**Save as:** `Arun_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Arun_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) with the eyes wide open in every panel, locking the face.
**Save as:** `Arun_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S001, S002, S003, S004, S005, S006, S007, S008, S009, S010, S011, S012, S013, S014, S015, S017, S018, S019, S020, S021.

### 1B. Meena (the girl)
**Portrait Image Prompt — Google Flow:**
Full-body portrait of a 7-year-old Tamil girl named Meena standing in a happy energetic pose, facing the camera, with a clearly visible, fully expressive animated face: light-brown skin, rosy cheeks, big sparkling dark eyes wide open, two braids tied with yellow ribbons, a huge bright smile with a closed mouth. She wears a red frock with white dots, a small straw hat and sandals. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination. Neutral light-grey background, soft key light. Eyes wide open, never closed. Locked reference design.
**Save as:** `Meena_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Meena_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) with the eyes wide open in every panel, locking the face.
**Save as:** `Meena_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S001, S002, S003, S004, S005, S006, S007, S008, S009, S010, S011, S012, S013, S014, S016, S017, S018, S019, S020, S021.

### 1C. The village bus (prop)
**Portrait Image Prompt — Google Flow:**
A cheerful toy-like village bus painted orange and sky blue with a white roof, two big round headlights, wide open windows with little green curtains, a friendly rounded front and chunky wheels, with no writing, numbers or logos anywhere. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination. Neutral light-grey background, soft key light. Locked reference design.
**Save as:** `Bus_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Bus_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up detail panels.
**Save as:** `Bus_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S001, S002, S003, S004, S013, S014, S018, S021.

### 1D. The squirrel
**Portrait Image Prompt — Google Flow:**
A cute red-brown squirrel standing upright, with a cream chest, a big fluffy tail, big round shiny dark eyes wide open, a happy closed-mouth smile and a ripe pink guava held in its paws. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination. Neutral light-grey background, soft key light. Eyes wide open, never closed. Locked reference design.
**Save as:** `Squirrel_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Squirrel_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) with the eyes wide open in every panel, locking the face.
**Save as:** `Squirrel_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S005, S007, S013, S015, S021.

### 1E. The rabbit
**Portrait Image Prompt — Google Flow:**
A cute fluffy white rabbit with long pale-pink inner ears, a pink nose, big round shiny dark eyes wide open, a happy closed-mouth smile and a fresh green cucumber held in its paws. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination. Neutral light-grey background, soft key light. Eyes wide open, never closed. Locked reference design.
**Save as:** `Rabbit_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Rabbit_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) with the eyes wide open in every panel, locking the face.
**Save as:** `Rabbit_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S006, S007, S013, S016, S021.

### 1F. The koel (cuckoo)
**Portrait Image Prompt — Google Flow:**
A glossy black koel (cuckoo) perched on a branch with a long tail, a pale green-grey beak (closed), big round bright red eyes with dark pupils and highlights wide open, a happy friendly face. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination. Neutral light-grey background, soft key light. Eyes wide open, never closed. Locked reference design.
**Save as:** `Koel_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Koel_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) with the eyes wide open in every panel, locking the face.
**Save as:** `Koel_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S008, S010, S013, S017, S021.

### 1G. The peacock
**Portrait Image Prompt — Google Flow:**
A royal peacock with a shimmering blue neck, a green-gold tail fan spread wide with big eye-spot patterns, a tiny crown crest, big round shiny dark eyes wide open, a happy friendly face with a closed beak. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination. Neutral light-grey background, soft key light. Eyes wide open, never closed. Locked reference design.
**Save as:** `Peacock_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Peacock_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) with the eyes wide open in every panel, locking the face.
**Save as:** `Peacock_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S009, S010, S013, S017, S021.

---

# STEP 2 — LOCATION PLAN (no reusable environment plates: every scene is a different spot)

There are no shared environment-plate images. Each scene's Step 3 prompt describes its own spot, and `Environment Reference Image` is `none`. The table lists every spot so you can check none repeats.

| Scene | Time | Slot | Flow clip | Unique location |
|---|---|---|---|---|
| S001 | 0:00–0:10 | 10s | 10 s | A village bus stop under a tamarind tree at sunrise |
| S002 | 0:10–0:16 | 6s | 8 s | Inside the bus on a country road with paddy fields in the windows |
| S003 | 0:16–0:20 | 4s | 8 s | A village main street with a temple tower and shops |
| S004 | 0:20–0:26 | 6s | 8 s | A straight road through green paddy fields with a windmill |
| S005 | 0:26–0:32 | 6s | 8 s | A guava orchard with baskets and fallen leaves |
| S006 | 0:32–0:36 | 4s | 8 s | A vegetable garden with cucumber vines on bamboo frames |
| S007 | 0:36–0:42 | 6s | 8 s | A grassy farm lane with a wooden bridge over a small canal |
| S008 | 0:42–0:46 | 4s | 8 s | A gulmohar tree covered in red blossoms |
| S009 | 0:46–0:50 | 4s | 8 s | A forest clearing with sunbeams at golden hour |
| S010 | 0:50–0:56 | 6s | 8 s | A banyan-shaded pond bank at golden hour |
| S011 | 0:56–1:00 | 4s | 8 s | A sparkling waterfall pool with rainbow mist |
| S012 | 1:00–1:04 | 4s | 8 s | A safe viewpoint with misty blue mountains at sunrise |
| S013 | 1:04–1:12 | 8s | 10 s | A hilltop picnic meadow with the bus parked and mountains behind |
| S014 | bonus (no timestamp) | none | 8 s | A roadside tea stall under banana trees |
| S015 | bonus (no timestamp) | none | 8 s | A cashew orchard on a gentle hill |
| S016 | bonus (no timestamp) | none | 8 s | A carrot patch at dawn |
| S017 | bonus (no timestamp) | none | 8 s | A lotus pond with stepping stones |
| S018 | bonus (no timestamp) | none | 8 s | A seaside road with coconut palms |
| S019 | bonus (no timestamp) | none | 8 s | A shallow clear stream with flat stepping stones |
| S020 | bonus (no timestamp) | none | 8 s | A rocky ridge with fluttering colourful pennants behind a stone wall |
| S021 | bonus (no timestamp) | none | 8 s | A golden village road at sunset lined with palm trees |

---

# STEP 3 & STEP 4 — SCENES (song slots of 4, 6, 8 and 10 seconds; every Flow video is generated at 8 or 10 seconds; soundless, eyes always open, always smiling)

**How each scene is shaped:**
Header line → **Song sync** (editor note only: the lyric words; they are not part of the Flow prompt) → Step 3 Ingredients → Step 3 Reference Image Prompt → Step 4 Ingredients → Video Prompt (Google Flow; second marks relative to the clip start; the dance beats first and spare seconds after) → Sound → Cut→.
The lyrics are NOT written inside the Flow prompts. Append the GLOBAL LOCK BLOCK to the end of every Step 3 and Step 4 prompt.

---

### Segment 1 — Intro: the bus arrives (Scenes 1–1) | 0:00–0:10

**S001 — The bus arrives at sunrise | 0:00–0:10 (10s slot → generate 10s in Flow)**
Song sync: (0:00) "(இசை அறிமுகம்)"
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Arun_Portrait.png`, `Arun_6Angle.png`, `Meena_Portrait.png`, `Meena_6Angle.png`, `Bus_Portrait.png`, `Bus_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A village bus stop under a tamarind tree at sunrise) · Scene Continuity Reference: none (first scene in the series)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot at a village bus stop under a big tamarind tree at sunrise: the orange-and-sky-blue village bus pulling in with its headlights glowing, and the boy Arun (a sky-blue shirt, khaki shorts, a yellow cap) and the girl Meena (a red frock with white dots, two braids with yellow ribbons, a straw hat) waving happily with their little bags, floating sparkles and golden rays. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S001_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S001_Ref.png`
Video Prompt (Google Flow, generate 10s = the full 10s slot):
I2V from `S001_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: the bus rolls in with a happy bounce as the children wave both arms; 2–5s: Arun and Meena hop up and down and dance a happy step; 5–8s: they run to the bus steps and climb aboard; 8–10s: they stand on the bus steps smiling and wave at the camera. Slow push-in on the bus, then a gentle tilt up. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, hugging or waving. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S002: Cut inside the bus.

### Segment 2 — Verse 1: bam bam, we ride and laugh; silu silu (Scenes 2–4) | 0:10–0:26

**S002 — Bam bam, we ride the bus and laugh | 0:10–0:16 (6s slot → generate 8s in Flow)**
Song sync: (0:11) "பாம் பாம் பேருந்தில் வருகிறோம், பாட்டுப் பாடிச் சிரிக்கிறோம்."
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Arun_Portrait.png`, `Arun_6Angle.png`, `Meena_Portrait.png`, `Meena_6Angle.png`, `Bus_Portrait.png`, `Bus_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: Inside the bus on a country road with paddy fields in the windows) · Scene Continuity Reference: `S001_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Medium shot inside the orange-and-sky-blue village bus with wide open windows showing green paddy fields rolling past: the boy Arun (a sky-blue shirt, khaki shorts, a yellow cap) and the girl Meena (a red frock with white dots, two braids with yellow ribbons, a straw hat) dancing in the aisle holding the seat rails, with huge smiles and wide sparkling eyes, warm morning light. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S002_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S002_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the dance beats, the last 2s are spare footage):
I2V from `S002_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: Arun and Meena bounce on the beat holding the seat rails; 2–4s: they clap a rhythm and sway side to side; 4–6s: they pump a fist twice on the beat like pressing a horn. 6–8s (spare 2s): the same joyful motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 6s slot or stretched. Handheld-style slider move along the aisle. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, hugging or waving. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S003: Cut outside to a street.

**S003 — Silu silu, the breeze and the town tour | 0:16–0:20 (4s slot → generate 8s in Flow)**
Song sync: (0:17) "சிலுசிலு காற்றில் வருகிறோம், ஊரைச் சுற்றிப் பார்க்கிறோம்." (starts 1 s into the clip)
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Arun_Portrait.png`, `Arun_6Angle.png`, `Meena_Portrait.png`, `Meena_6Angle.png`, `Bus_Portrait.png`, `Bus_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A village main street with a temple tower and shops) · Scene Continuity Reference: `S002_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Side-on wide shot of the orange-and-sky-blue village bus rolling past a village main street with a temple tower and colourful shops, the boy Arun (a sky-blue shirt, khaki shorts, a yellow cap) and the girl Meena (a red frock with white dots, two braids with yellow ribbons, a straw hat) seated at the open windows with their heads inside, waving their hands and scarves outside in the breeze and smiling, golden light. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S003_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S003_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S003_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: the bus rolls past shop fronts while the children wave their hands from the windows; 2–4s: their scarves flutter in the breeze as they wave to the town. 4–8s (spare 4s): the same joyful motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. Smooth tracking shot alongside the bus. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, hugging or waving. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S004: Cut to a country road.

**S004 — Bam bam silu silu: the happy bus dance | 0:20–0:26 (6s slot → generate 8s in Flow)**
Song sync: (0:21) "பாம் பாம் பாம் பாம் சிலு சிலு சிலு சிலு"
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Arun_Portrait.png`, `Arun_6Angle.png`, `Meena_Portrait.png`, `Meena_6Angle.png`, `Bus_Portrait.png`, `Bus_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A straight road through green paddy fields with a windmill) · Scene Continuity Reference: `S003_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Aerial wide shot of the orange-and-sky-blue village bus driving along a straight road through green paddy fields with a windmill, the boy Arun (a sky-blue shirt, khaki shorts, a yellow cap) and the girl Meena (a red frock with white dots, two braids with yellow ribbons, a straw hat) dancing at the open windows with scarves streaming in the wind, bright sunny light. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S004_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S004_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the dance beats, the last 2s are spare footage):
I2V from `S004_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: the bus bounces along on the beat as the children dance at the windows; 2–4s: they wave scarves in the wind in a swinging rhythm; 4–6s: they throw their hands up together in a happy pose. 6–8s (spare 2s): the same joyful motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 6s slot or stretched. Aerial tracking shot circling the bus. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, hugging or waving. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S005: Cut to an orchard.

### Segment 3 — Verse 2: the squirrel and the rabbit (Scenes 5–7) | 0:26–0:42

**S005 — Thuru thuru: guava for the squirrel | 0:26–0:32 (6s slot → generate 8s in Flow)**
Song sync: (0:27) "துறுதுறு அணிலே வருகிறோம், கொய்யாப் பழங்கள் தருகிறோம்."
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Arun_Portrait.png`, `Arun_6Angle.png`, `Meena_Portrait.png`, `Meena_6Angle.png`, `Squirrel_Portrait.png`, `Squirrel_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A guava orchard with baskets and fallen leaves) · Scene Continuity Reference: `S004_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Medium shot in a guava orchard with baskets of pink guavas: the boy Arun (a sky-blue shirt, khaki shorts, a yellow cap) and the girl Meena (a red frock with white dots, two braids with yellow ribbons, a straw hat) offering ripe guavas on their open palms to a red-brown squirrel on a low stump, all with huge smiles and wide-open eyes, dappled golden light. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S005_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S005_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the dance beats, the last 2s are spare footage):
I2V from `S005_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: the squirrel scampers up the stump and bobs on the beat; 2–4s: Arun and Meena hold out guavas on their palms and bounce; 4–6s: the squirrel takes a guava and everyone does a happy wiggle. 6–8s (spare 2s): the same joyful motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 6s slot or stretched. Low slider move. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, hugging or waving. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S006: Cut to a vegetable garden.

**S006 — Kudu kudu: cucumber for the rabbit | 0:32–0:36 (4s slot → generate 8s in Flow)**
Song sync: (0:32) "குடுகுடு முயலே வருகிறோம், வெள்ளரிப் பிஞ்சைத் தருகிறோம்."
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Arun_Portrait.png`, `Arun_6Angle.png`, `Meena_Portrait.png`, `Meena_6Angle.png`, `Rabbit_Portrait.png`, `Rabbit_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A vegetable garden with cucumber vines on bamboo frames) · Scene Continuity Reference: `S005_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Medium shot in a vegetable garden with cucumber vines on bamboo frames: the boy Arun (a sky-blue shirt, khaki shorts, a yellow cap) and the girl Meena (a red frock with white dots, two braids with yellow ribbons, a straw hat) holding out fresh green cucumbers to a fluffy white rabbit that hops toward them, all with huge smiles and wide-open eyes, soft morning light. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S006_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S006_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S006_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: the rabbit hops toward the children in quick bounces on the beat; 2–4s: Meena and Arun hold out cucumbers and hop with it. 4–8s (spare 4s): the same joyful motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. Low-angle tracking shot. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, hugging or waving. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S007: Cut to a farm lane.

**S007 — Thuru thuru, kudu kudu: the animal dance | 0:36–0:42 (6s slot → generate 8s in Flow)**
Song sync: (0:37) "துறுதுறு துறுதுறு குடுகுடு குடுகுடு"
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Arun_Portrait.png`, `Arun_6Angle.png`, `Meena_Portrait.png`, `Meena_6Angle.png`, `Squirrel_Portrait.png`, `Squirrel_6Angle.png`, `Rabbit_Portrait.png`, `Rabbit_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A grassy farm lane with a wooden bridge over a small canal) · Scene Continuity Reference: `S006_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot on a grassy farm lane with a small wooden bridge over a canal: the boy Arun (a sky-blue shirt, khaki shorts, a yellow cap) and the girl Meena (a red frock with white dots, two braids with yellow ribbons, a straw hat) dancing with the squirrel and the rabbit in a happy line, everyone with wide-open eyes and big smiles, warm golden light. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S007_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S007_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the dance beats, the last 2s are spare footage):
I2V from `S007_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: the squirrel scampers in a circle while the rabbit hops in place on the beat; 2–4s: Arun and Meena hop in step with the animals; 4–6s: everyone jumps together and freezes in a happy pose. 6–8s (spare 2s): the same joyful motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 6s slot or stretched. Circling camera. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, hugging or waving. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S008: Cut to a blossoming tree.

### Segment 4 — Verse 3: the koel and the peacock (Scenes 8–10) | 0:42–0:56

**S008 — Kuku: singing with the koel | 0:42–0:46 (4s slot → generate 8s in Flow)**
Song sync: (0:42) "குக்கூ குயிலே வருகிறோம், உன்னுடன் சேர்ந்து பாடுகிறோம்."
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Arun_Portrait.png`, `Arun_6Angle.png`, `Meena_Portrait.png`, `Meena_6Angle.png`, `Koel_Portrait.png`, `Koel_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A gulmohar tree covered in red blossoms) · Scene Continuity Reference: `S007_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Medium shot under a gulmohar tree covered in red blossoms with petals drifting: the boy Arun (a sky-blue shirt, khaki shorts, a yellow cap) and the girl Meena (a red frock with white dots, two braids with yellow ribbons, a straw hat) swaying happily with their hands cupped behind their ears, looking up at a glossy black koel on a branch, everyone with wide-open eyes and big smiles, golden light. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S008_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S008_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S008_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: Arun and Meena sway side to side looking up at the koel as petals drift; 2–4s: the koel bobs on its branch and the children copy the bob. 4–8s (spare 4s): the same joyful motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. Slow crane up through the branches. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, hugging or waving. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S009: Cut to a forest clearing.

**S009 — Thak thak: dancing like the peacock | 0:46–0:50 (4s slot → generate 8s in Flow)**
Song sync: (0:46) "தக்தக் மயிலே வருகிறோம், உன்னைப் போல ஆடுகிறோம்."
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Arun_Portrait.png`, `Arun_6Angle.png`, `Meena_Portrait.png`, `Meena_6Angle.png`, `Peacock_Portrait.png`, `Peacock_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A forest clearing with sunbeams at golden hour) · Scene Continuity Reference: `S008_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot in a forest clearing with sunbeams at golden hour: a royal peacock with its green-gold tail fan spread wide and the boy Arun (a sky-blue shirt, khaki shorts, a yellow cap) and the girl Meena (a red frock with white dots, two braids with yellow ribbons, a straw hat) dancing beside it with their arms fanned out like feathers, everyone with wide-open eyes and big smiles. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S009_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S009_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S009_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: the peacock spreads its tail and the children fan their arms out beside it; 2–4s: they step and spin in a circle in rhythm with the peacock. 4–8s (spare 4s): the same joyful motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. Slow orbit. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, hugging or waving. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S010: Cut to a village pond.

**S010 — Kuku kuku thak thak: the bird dance | 0:50–0:56 (6s slot → generate 8s in Flow)**
Song sync: (0:51) "குக்கூ குக்கூ தக்தக் தக்தக்" (starts 1 s into the clip)
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Arun_Portrait.png`, `Arun_6Angle.png`, `Meena_Portrait.png`, `Meena_6Angle.png`, `Koel_Portrait.png`, `Koel_6Angle.png`, `Peacock_Portrait.png`, `Peacock_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A banyan-shaded pond bank at golden hour) · Scene Continuity Reference: `S009_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot on a pond bank shaded by a giant banyan tree at golden hour: the boy Arun (a sky-blue shirt, khaki shorts, a yellow cap) and the girl Meena (a red frock with white dots, two braids with yellow ribbons, a straw hat) dancing with the peacock (tail spread) while the koel bobs on a low branch above them, everyone with wide-open eyes and big smiles, sparkling water behind. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S010_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S010_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the dance beats, the last 2s are spare footage):
I2V from `S010_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: the koel bobs on the branch while the peacock shimmers its tail on the beat; 2–4s: Arun and Meena dance a side-step with their arms out like wings; 4–6s: everyone strikes a happy pose. 6–8s (spare 2s): the same joyful motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 6s slot or stretched. Smooth crane move. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, hugging or waving. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S011: Cut to a waterfall.

### Segment 5 — Verse 4: the waterfall and the mountain; finale (Scenes 11–13) | 0:56–1:12

**S011 — Sala sala: the waterfall | 0:56–1:00 (4s slot → generate 8s in Flow)**
Song sync: (0:56) "சலசல அருவியே வருகிறோம், உன் ஓசை கேட்டு மகிழ்கிறோம்."
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Arun_Portrait.png`, `Arun_6Angle.png`, `Meena_Portrait.png`, `Meena_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A sparkling waterfall pool with rainbow mist) · Scene Continuity Reference: `S010_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot of a sparkling waterfall pool with rainbow mist: the boy Arun (a sky-blue shirt, khaki shorts, a yellow cap) and the girl Meena (a red frock with white dots, two braids with yellow ribbons, a straw hat) standing safely on a flat dry rock far from the water's edge behind a low stone railing, arms spread wide with huge smiles and wide-open eyes, bright sunlight. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S011_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S011_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S011_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: the waterfall sparkles as Arun and Meena sway with their arms wide; 2–4s: they clap in rhythm and bounce on their toes. 4–8s (spare 4s): the same joyful motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. Slow tilt up the waterfall. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, hugging or waving. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S012: Cut to a mountain view.

**S012 — Kulu kulu: the misty mountain | 1:00–1:04 (4s slot → generate 8s in Flow)**
Song sync: (1:01) "குளுகுளு மலையே வருகிறோம், உன்னைப் பார்த்து வியக்கிறோம்."
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Arun_Portrait.png`, `Arun_6Angle.png`, `Meena_Portrait.png`, `Meena_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A safe viewpoint with misty blue mountains at sunrise) · Scene Continuity Reference: `S011_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot at a safe stone viewpoint with a sturdy railing and misty blue mountains at sunrise: the boy Arun (a sky-blue shirt, khaki shorts, a yellow cap) and the girl Meena (a red frock with white dots, two braids with yellow ribbons, a straw hat) with their hands up in wonder and huge smiles, wide-open sparkling eyes, golden mist. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S012_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S012_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S012_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: Arun and Meena raise their arms in wonder as the mist drifts; 2–4s: they jump up happily with a gentle bounce. 4–8s (spare 4s): the same joyful motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. Slow push-in from behind them. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, hugging or waving. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S013: Cut to the finale.

**S013 — Finale: everyone dances at the hilltop picnic | 1:04–1:12 (8s slot → generate 10s in Flow)**
Song sync: (1:05) "சலசல சலசல குளுகுளு குளுகுளு" (end of the song)
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Arun_Portrait.png`, `Arun_6Angle.png`, `Meena_Portrait.png`, `Meena_6Angle.png`, `Bus_Portrait.png`, `Bus_6Angle.png`, `Squirrel_Portrait.png`, `Squirrel_6Angle.png`, `Rabbit_Portrait.png`, `Rabbit_6Angle.png`, `Koel_Portrait.png`, `Koel_6Angle.png`, `Peacock_Portrait.png`, `Peacock_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A hilltop picnic meadow with the bus parked and mountains behind) · Scene Continuity Reference: `S012_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot on a hilltop picnic meadow with the orange-and-sky-blue village bus parked and misty mountains behind: the boy Arun (a sky-blue shirt, khaki shorts, a yellow cap) and the girl Meena (a red frock with white dots, two braids with yellow ribbons, a straw hat) dancing in a circle with the squirrel and the rabbit, the peacock with its tail spread behind them and the koel on the bus roof, everyone with wide-open eyes and big smiles, golden sunset light. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S013_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S013_Ref.png`
Video Prompt (Google Flow, generate 10s: the first 8s carry the dance beats, the last 2s are spare footage):
I2V from `S013_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: everyone dances in a circle on the beat; 2–4s: the animals take turns leaping and the children clap; 4–6s: Arun and Meena throw their hands up as the peacock fans its tail; 6–8s: the whole group holds a happy pose and waves at the camera. 8–10s (spare 2s): the same joyful motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 8s slot or stretched. Crane shot rising and pulling back. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, hugging or waving. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song is added in the edit)
Cut→END: Fade to black (trim in edit to land at the real end of the song).

---

### Segment 6 — Bonus dance scenes (Scenes 14–21) | bonus, no timestamp

**S014 — Bonus 1: dancing at the tea stall | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any line of the song.
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Arun_Portrait.png`, `Arun_6Angle.png`, `Meena_Portrait.png`, `Meena_6Angle.png`, `Bus_Portrait.png`, `Bus_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A roadside tea stall under banana trees) · Scene Continuity Reference: `S013_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot at a roadside tea stall under banana trees with the village bus parked beside it: the boy Arun (a sky-blue shirt, khaki shorts, a yellow cap) and the girl Meena (a red frock with white dots, two braids with yellow ribbons, a straw hat) dancing happily on the road verge, bright noon light. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S014_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S014_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S014_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: Arun and Meena bounce on the beat by the bus. 3–6s: they spin in a circle with their bags swinging. 6–8s: they strike a happy pose. Crane pull-back. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, hugging or waving. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S015: Use as a cutaway or loop anywhere in the edit.

**S015 — Bonus 2: guava toss | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any line of the song.
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Arun_Portrait.png`, `Arun_6Angle.png`, `Squirrel_Portrait.png`, `Squirrel_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A cashew orchard on a gentle hill) · Scene Continuity Reference: `S014_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Medium shot in a cashew orchard on a gentle hill: the boy Arun (a sky-blue shirt, khaki shorts, a yellow cap) tossing a guava gently to a red-brown squirrel on a branch low enough to reach, golden light. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S015_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S015_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S015_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: Arun tosses a guava in a gentle arc on the beat. 3–6s: the squirrel catches it and bobs happily. 6–8s: Arun cheers with both arms up. Slow slider move. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, hugging or waving. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S016: Use as a cutaway or loop anywhere in the edit.

**S016 — Bonus 3: rabbit hop | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any line of the song.
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Meena_Portrait.png`, `Meena_6Angle.png`, `Rabbit_Portrait.png`, `Rabbit_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A carrot patch at dawn) · Scene Continuity Reference: `S015_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Medium shot in a carrot patch at dawn with dew on the leaves: the girl Meena (a red frock with white dots, two braids with yellow ribbons, a straw hat) hopping side by side with a fluffy white rabbit, soft pink light. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S016_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S016_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S016_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: Meena and the rabbit hop together in rhythm. 3–6s: they hop in a circle around a carrot top. 6–8s: they strike a happy pose. Low tracking shot. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, hugging or waving. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S017: Use as a cutaway or loop anywhere in the edit.

**S017 — Bonus 4: the lotus pond bird party | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any line of the song.
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Arun_Portrait.png`, `Arun_6Angle.png`, `Meena_Portrait.png`, `Meena_6Angle.png`, `Koel_Portrait.png`, `Koel_6Angle.png`, `Peacock_Portrait.png`, `Peacock_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A lotus pond with stepping stones) · Scene Continuity Reference: `S016_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot at a lotus pond with large flat stepping stones: the boy Arun (a sky-blue shirt, khaki shorts, a yellow cap) and the girl Meena (a red frock with white dots, two braids with yellow ribbons, a straw hat) dancing on the bank with the peacock while the koel bobs on a reed, sparkling water, golden light. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S017_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S017_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S017_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: the peacock fans its tail as the children sway. 3–6s: the koel bobs and Arun and Meena copy it. 6–8s: everyone freezes in a happy pose. Slow orbit. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, hugging or waving. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S018: Use as a cutaway or loop anywhere in the edit.

**S018 — Bonus 5: coconut-palm seaside road | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any line of the song.
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Arun_Portrait.png`, `Arun_6Angle.png`, `Meena_Portrait.png`, `Meena_6Angle.png`, `Bus_Portrait.png`, `Bus_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A seaside road with coconut palms) · Scene Continuity Reference: `S017_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot on a quiet seaside road with coconut palms and the village bus parked at a lay-by: the boy Arun (a sky-blue shirt, khaki shorts, a yellow cap) and the girl Meena (a red frock with white dots, two braids with yellow ribbons, a straw hat) dancing beside the bus with the sea behind them, bright blue sky. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S018_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S018_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S018_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: Arun and Meena bounce on the beat with palm leaves waving. 3–6s: they spin and wave at the sea. 6–8s: they jump together. Crane shot rising. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, hugging or waving. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S019: Use as a cutaway or loop anywhere in the edit.

**S019 — Bonus 6: stream stepping stones | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any line of the song.
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Arun_Portrait.png`, `Arun_6Angle.png`, `Meena_Portrait.png`, `Meena_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A shallow clear stream with flat stepping stones) · Scene Continuity Reference: `S018_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Medium shot at a shallow clear stream with large flat stepping stones, sparkling water only ankle deep: the boy Arun (a sky-blue shirt, khaki shorts, a yellow cap) and the girl Meena (a red frock with white dots, two braids with yellow ribbons, a straw hat) hopping across the stones hand in hand, sunlit. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S019_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S019_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S019_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: Arun and Meena hop from stone to stone on the beat. 3–6s: they spin once on a big stone. 6–8s: they raise their arms together. Tracking shot. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, hugging or waving. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S020: Use as a cutaway or loop anywhere in the edit.

**S020 — Bonus 7: cheering on the pennant ridge | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any line of the song.
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Arun_Portrait.png`, `Arun_6Angle.png`, `Meena_Portrait.png`, `Meena_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A rocky ridge with fluttering colourful pennants behind a stone wall) · Scene Continuity Reference: `S019_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot on a rocky ridge with fluttering colourful pennants (no writing) and a sturdy stone wall in front: the boy Arun (a sky-blue shirt, khaki shorts, a yellow cap) and the girl Meena (a red frock with white dots, two braids with yellow ribbons, a straw hat) cheering with their arms up and dancing a happy step, bright sky. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S020_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S020_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S020_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: Arun and Meena bounce and cheer on the beat. 3–6s: the pennants flutter as they spin. 6–8s: they wave at the camera. Pull-back. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, hugging or waving. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S021: Use as a cutaway or loop anywhere in the edit.

**S021 — Bonus 8: sunset road goodbye | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any line of the song.
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Arun_Portrait.png`, `Arun_6Angle.png`, `Meena_Portrait.png`, `Meena_6Angle.png`, `Bus_Portrait.png`, `Bus_6Angle.png`, `Squirrel_Portrait.png`, `Squirrel_6Angle.png`, `Rabbit_Portrait.png`, `Rabbit_6Angle.png`, `Koel_Portrait.png`, `Koel_6Angle.png`, `Peacock_Portrait.png`, `Peacock_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A golden village road at sunset lined with palm trees) · Scene Continuity Reference: `S020_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot on a golden village road at sunset lined with palm trees: the orange-and-sky-blue village bus waiting with its headlights on, and the boy Arun (a sky-blue shirt, khaki shorts, a yellow cap) and the girl Meena (a red frock with white dots, two braids with yellow ribbons, a straw hat) with the squirrel, rabbit, peacock and koel all waving goodbye, everyone with wide-open eyes and big smiles. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S021_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S021_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S021_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: everyone waves and bounces on the beat. 3–6s: the animals leap and the peacock fans its tail. 6–8s: the children climb the bus steps and wave from the door. Slow pull-back. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, hugging or waving. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song is added in the edit)
Cut→END: Use as a cutaway or loop anywhere in the edit.

---

# PRODUCTION NOTES

- **Total required:** 21 reference images (`S001_Ref.png` … `S021_Ref.png`) and 21 videos, one video per image: 13 timed scenes that follow the song plus 8 bonus dance scenes. Plus the Step 1 sheets (7 portraits and 7 six-angle turnarounds = 14 images). There are no environment-plate images. Overall: 21 scene images + 14 sheet images = 35 images, and 21 videos.
- **Song structure (from your timestamps):** 0:00–0:11 intro; 0:11 "bam bam, we come by bus, singing and laughing"; 0:17 "silu silu, we come in the breeze, touring the town"; 0:21 bam-bam / silu-silu refrain; 0:27 squirrel (guava); 0:32 rabbit (cucumber); 0:37 thuru-thuru / kudu-kudu refrain; 0:42 koel; 0:46 peacock; 0:51 koo-koo / thak-thak refrain; 0:56 waterfall; 1:01 mountain; 1:05 sala-sala / kulu-kulu refrain to the end. Clips use even seconds, so lines on odd seconds start about 1 s into a clip; every clip has spare footage.
- **Transcript clean-up:** the timestamped transcript has mis-hearings (for example "பேருண்டு", "சிலிக்கிறோம்", "அருகியே", "வெள்ளைத் திஞ்சை", "கோசை", "மகுகிறோம்"). The VO sync lines use the clean lyrics from your first version.
- **Safety:** the children never lean their heads out of the bus, stay behind railings at the waterfall and the viewpoint, and the stream is only ankle deep.
- **Eyes open, always smiling:** the lock block has a strengthened EYE RULE, an EYE DESIGN line (big glossy round toy-like eyes with permanently fixed-open eyelids) and an AVOID list; every image prompt starts with an eyes-open sentence; every video prompt starts and ends with eyes-open sentences. If a take still blinks: use another take, use only the first 4 s, regenerate from a clearly open-eyed scene image, or trim before the blink and cross-dissolve. Prompts cannot guarantee it, so check each clip.
- **Soundless clips:** no singing, voices, calls, music or sound effects, and everyone keeps a closed-mouth smile. Your recorded song is added in the edit.
- **What to generate in Flow (8 s or 10 s only):** 4 s and 6 s slots are generated at 8 s; 8 s and 10 s slots at 10 s. Each prompt puts the dance beats first and the spare seconds last, so you can trim a clip back to its slot or stretch it. The bonus scenes are 8 s.

| Generate in Flow | Number of videos | Footage | Scenes |
|---|---|---|---|
| 8 s | 19 | 152 s | S002, S003, S004, S005, S006, S007, S008, S009, S010, S011, S012, S014, S015, S016, S017, S018, S019, S020, S021 |
| 10 s | 2 | 20 s | S001, S013 |
| **Total** | **21** | **172 s** | timed song 72 s; timed footage 108 s |

- **Slot plan (timed scenes):** the 4 s slots are S003, S006, S008, S009, S011, S012 (6 clips, 24 s); the 6 s slots are S002, S004, S005, S007, S010 (5 clips, 30 s); the 8 s slots are S013 (1 clips, 8 s); the 10 s slots are S001 (1 clips, 10 s); total 72 s.
- **Timeline rule:** put the song on the timeline at 0:00, drop each timed clip at its scene start time and trim it to its slot. The extra seconds are spare footage. The bonus scenes have no timestamp: use them as cutaways, or loop the song to make a longer video.
- **Image generation is Google Flow only.** Generate the 7 sheets first, then each scene image in order. Video prompts use each scene's saved image as the starting frame.
- **Reminder:** the GLOBAL LOCK BLOCK must be appended in full to the end of every prompt (Step 1, every Step 3 and every Step 4) before submission.
