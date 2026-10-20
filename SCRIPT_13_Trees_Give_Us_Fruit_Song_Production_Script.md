# SCRIPT 13 — Trees Give Us Fruit: a dancing song for children about trees
### [TEMPLATE v3 — Google Flow only · song slots of 4/6 s, Flow clips generated at 8 s · character, animal and prop sheets → a different spot per scene → per-scene reference image → per-scene video · global lock appended to every prompt · no on-screen text · eyes always open, always smiling · soundless dance clips]

**Duration:** about 1:02 (the last line starts at 0:56; no audio file was attached, so the end is estimated; see notes) | **Total Scenes:** 20 = 20 reference images = 20 videos (12 timed scenes + 8 bonus dance scenes)
**Image generation:** Google Flow only (Step 1 sheets, Step 2 location plan, Step 3 scene reference images)
**Video generation:** Google Flow — one video prompt per scene, each generated as an 8 s clip (a 4 s or 6 s song slot plus spare seconds to trim)
**Payoff:** Two children in leaf crowns and their animal friends pick fruit, play in the shade, watch a bird build a nest, then plant and water a sapling, and end by hugging the big tree at sunset.
**Dialogue/Audio rule:** The generated clips are SOUNDLESS action videos: no singing, no lip movement, no voices, no music and no sound effects. Your recorded song is added in the edit; every scene is timed to the song.

**Assumptions made for the blank input fields (change if needed):**
- **Style:** 3D animated family-film look with vibrant colours, sparkle and glow. Tell me if you want 2D cartoon instead.
- **Characters:** the girl Meera and the boy Rohan in leaf-crown costumes with fruit-patch aprons (faces fully visible), Pachu the green parrot, a squirrel, a little monkey, a big mango tree and a sapling. Tell me if you want different names, costumes or animals.
- **Hard rules:** no on-screen text or lyrics; nobody sings or speaks; eyes always wide open; everyone always smiling; soundless clips.

**Segment map**

| # | Segment | Scenes | Time |
|---|---|---|---|
| 1 | Intro: the friends run to the big tree | S001–S002 | 0:00–0:12 |
| 2 | Verse 1: trees give us fruit to eat | S003–S004 | 0:12–0:22 |
| 3 | Verse 2: trees give us shade to play | S005–S006 | 0:22–0:30 |
| 4 | Verse 3: birds build their nest on trees | S007–S008 | 0:30–0:40 |
| 5 | Verse 4: let's all plant these lovely trees | S009–S010 | 0:40–0:50 |
| 6 | Instrumental dance and the final repeat | S011–S012 | 0:50–1:02 |
| 7 | Bonus dance scenes (use anywhere in the edit) | S013–S020 | bonus (no timestamp) |

---

## ⚠️ GLOBAL LOCK BLOCK — append this in full to the END of every single prompt below (Step 1, every Step 3, every Step 4)

```
GLOBAL LOCK:
CONTINUITY — Keep Meera (a 7-year-old Tamil girl: warm brown skin, a long black braid, a green leaf-crown headband, a green frock with fruit-patch pockets), Rohan (a 7-year-old Tamil boy: short black hair, a green leaf-crown headband, an orange shirt, a green apron with fruit-patch pockets), Pachu the green parrot, the red-brown squirrel, the little brown monkey, the big friendly mango tree and the little sapling in exact face, colour, costume and proportion continuity from their saved reference sheets — no redesign, recolor or scale drift. Every scene takes place in its own different spot of the same warm storybook countryside of orchards, groves, meadows and gardens. Never copy the previous scene's spot, background or composition.
CAST RULE — Every scene shows Meera and Rohan, plus the creatures and trees the prompt names for that line of the song (the monkey and squirrel for the fruit, the squirrel for the shade play, Pachu for the nest, the sapling for planting). Only the characters named in a scene appear in it. No other people.
STYLE — 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination. A warm 35mm-lens depth of field, one consistent colour grade (sunny gold, fresh greens, jewel colours), smooth appealing character animation with natural squash and stretch, and energetic, bouncy dance moves that land on the beat of a happy children's song. The children's leaf crowns keep their faces fully visible.
EYE RULE — Everyone's eyes (the children's and all the animals') are wide open and fully visible in every single frame of every scene, from the first frame to the last: no blinking, no closing, no squinting, no winking, no sleeping, no half-closed or sleepy eyes, and no eyelid motion at all, even when smiling widely, spinning, hugging the tree trunk or sitting in the nest.
EYE DESIGN — To make blinking impossible, every character has big, glossy, perfectly round eyes with large highlights and eyelids that are permanently fixed open (like toy or doll eyes); a smile only lifts the cheeks and mouth corners while the eyes stay perfectly round.
AVOID — closed eyes, blinking, squinting, eyes shut, winking, half-closed eyelids, sleepy eyes, laughing squint, eyes closed in a smile, eyelids covering the pupils, eyes rolling back.
SMILE RULE — Everyone is smiling happily in every frame, with joyful faces and energetic body language.
MOUTH RULE — Nobody sings, speaks or chirps. Everyone keeps a happy closed-mouth smile (beaks closed); the dance is carried by bodies, arms, legs and heads. Fruit is only held, shared or offered, never bitten.
SAFETY RULE — The children stay on the ground at all times: they pick, plant, water, hop, spin and hug trees from the ground; only Pachu flies and the animals climb. Fully child-friendly: nothing scary, sad or dangerous.
HARD RULES — No on-screen text, captions, lyrics, logos or watermarks. Faces never morph between shots.
ZERO AI ARTIFACTS — No closed or blinking eyes, no morphing, warping, melting, flicker, extra or duplicated limbs, wings, legs or characters, floating debris other than the intended sparkles, petals and water drops, texture smearing, distorted hands or feet.
LIGHTING — Follow the time of day and light written in each scene's prompt; no sudden unintended light jumps inside a shot.
AUDIO — The generated clip is SOUNDLESS: no sound effects, no music, no singing, no speech, no chirps. (If Flow still adds a little ambience, mute it in the edit.) The recorded song is added in the edit.
CAMERA — Smooth, physically plausible motion only; each shot's opening camera motion matches the previous shot's closing motion vector for a seamless cut.
```

---

# STEP 1 — CHARACTER, ANIMAL & PROP REFERENCE IMAGES (Google Flow — image generation ONLY)

### 1A. Meera, the girl in the leaf crown ("Meera")
**Portrait Image Prompt — Google Flow:**
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Full-body portrait of a 7-year-old Tamil girl named Meera standing in an energetic happy pose with her arms wide, facing the camera, with a clearly visible, fully expressive animated face: warm brown skin, rosy cheeks, a long black braid, big sparkling dark eyes wide open, a huge bright smile with a closed mouth. She wears a green leaf-crown headband and a green cotton frock with fruit-patch pockets, bare feet. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination. Neutral light-grey background, soft key light. Locked reference design.
**Save as:** `Meera_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Meera_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) with big round glossy eyes wide open and fixed-open eyelids in every panel, locking the face.
**Save as:** `Meera_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S001–S020.

### 1B. Rohan, the boy in the leaf crown ("Rohan")
**Portrait Image Prompt — Google Flow:**
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Full-body portrait of a 7-year-old Tamil boy named Rohan standing in an energetic happy pose with his arms wide, facing the camera, with a clearly visible, fully expressive animated face: warm brown skin, round cheeks, short black hair, big sparkling dark eyes wide open, a huge bright smile with a closed mouth. He wears a green leaf-crown headband, an orange shirt and a green apron with fruit-patch pockets, white shorts, bare feet. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination. Neutral light-grey background, soft key light. Locked reference design.
**Save as:** `Rohan_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Rohan_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) with big round glossy eyes wide open and fixed-open eyelids in every panel, locking the face.
**Save as:** `Rohan_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S001–S020.

### 1C. Pachu, the green parrot ("Parrot")
**Portrait Image Prompt — Google Flow:**
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. A cute bright green parrot named Pachu with a red beak (closed), a yellow chest, blue wing tips and a long tail, standing on a branch in a happy pose, with a fully expressive animated face and big shiny round black eyes wide open. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination. Neutral light-grey background, soft key light. Locked reference design.
**Save as:** `Parrot_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Parrot_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) with big round glossy eyes wide open and fixed-open eyelids in every panel, locking the face.
**Save as:** `Parrot_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S002, S004, S006–S008, S010–S012, S014, S016, S019–S020.

### 1D. The squirrel ("Squirrel")
**Portrait Image Prompt — Google Flow:**
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. A cute red-brown squirrel standing upright on a branch in a happy pose with a cream chest, a big fluffy tail and a small fruit in its paws, with a fully expressive animated face and big round shiny dark eyes wide open. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination. Neutral light-grey background, soft key light. Locked reference design.
**Save as:** `Squirrel_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Squirrel_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) with big round glossy eyes wide open and fixed-open eyelids in every panel, locking the face.
**Save as:** `Squirrel_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S002, S004–S005, S010–S012, S015, S017–S020.

### 1E. The little monkey ("Monkey")
**Portrait Image Prompt — Google Flow:**
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. A cute little brown monkey with a cream face and big ears, sitting on a branch in a happy pose with a ripe mango in one hand and a closed-mouth smile, with a fully expressive animated face and big round shiny dark eyes wide open. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination. Neutral light-grey background, soft key light. Locked reference design.
**Save as:** `Monkey_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Monkey_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) with big round glossy eyes wide open and fixed-open eyelids in every panel, locking the face.
**Save as:** `Monkey_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S002–S003, S010–S013, S016, S018–S020.

### 1F. The big friendly fruit tree (prop) ("Tree")
**Portrait Image Prompt — Google Flow:**
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. A huge friendly old mango tree with a thick trunk, a wide green canopy, ripe golden mangoes, a safe branch fork with a woven bird nest holding two chicks, and dappled shade beneath it, set on a sunny hillside. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination. Neutral light-grey background, soft key light. Locked reference design.
**Save as:** `Tree_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Tree_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) with big round glossy eyes wide open and fixed-open eyelids in every panel, locking the face.
**Save as:** `Tree_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S001, S003, S007–S008, S012, S020.

### 1G. The little sapling (prop) ("Sapling")
**Portrait Image Prompt — Google Flow:**
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. A little green sapling with six fresh leaves planted in a mound of rich brown soil with a tiny wooden support stick, next to a small red watering can and a small spade, in morning light. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination. Neutral light-grey background, soft key light. Locked reference design.
**Save as:** `Sapling_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Sapling_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) with big round glossy eyes wide open and fixed-open eyelids in every panel, locking the face.
**Save as:** `Sapling_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S009–S010.

---

# STEP 2 — LOCATION PLAN (no reusable environment plates: every scene is a different spot of the same storybook countryside)

There are no shared environment-plate images. Each scene's Step 3 prompt describes its own spot, and `Environment Reference Image` is `none`. The table lists every spot so you can check none repeats.

| Scene | Time | Slot | Flow clip | Unique location |
|---|---|---|---|---|
| S001 | 0:00–0:06 | 6s | 8 s | A sunrise hilltop with a giant mango tree on the horizon |
| S002 | 0:06–0:12 | 6s | 8 s | A dewy forest-edge path with ferns and wildflowers |
| S003 | 0:12–0:16 | 4s | 8 s | A sunny mango orchard with baskets |
| S004 | 0:16–0:22 | 6s | 8 s | A shady guava grove with a wooden fruit stall |
| S005 | 0:22–0:26 | 4s | 8 s | A giant banyan tree with a swing and a picnic mat |
| S006 | 0:26–0:30 | 4s | 8 s | A bright sunny meadow with one big neem tree and a hopscotch drawing |
| S007 | 0:30–0:36 | 6s | 8 s | A tall tamarind tree with a half-built twig nest |
| S008 | 0:36–0:40 | 4s | 8 s | A golden-hour mango tree fork with a finished nest and two chicks |
| S009 | 0:40–0:44 | 4s | 8 s | A community garden plot with raised soil beds at sunrise |
| S010 | 0:44–0:50 | 6s | 8 s | A sunny village green with a stone well |
| S011 | 0:50–0:56 | 6s | 8 s | A tree-lined avenue with hanging flower garlands |
| S012 | 0:56–1:02 | 6s | 8 s | A golden sunset grove of grown fruit trees |
| S013 | bonus (no timestamp) | none | 8 s | A sunbeam bamboo grove |
| S014 | bonus (no timestamp) | none | 8 s | A willow-lined riverbank at golden hour |
| S015 | bonus (no timestamp) | none | 8 s | A coconut-palm beach with soft waves |
| S016 | bonus (no timestamp) | none | 8 s | A red gulmohar flower avenue |
| S017 | bonus (no timestamp) | none | 8 s | A rainforest clearing with giant leaf umbrellas |
| S018 | bonus (no timestamp) | none | 8 s | A jackfruit orchard terrace with stone steps |
| S019 | bonus (no timestamp) | none | 8 s | An ancient oak glade with a fairy ring of mushrooms |
| S020 | bonus (no timestamp) | none | 8 s | A moonlit fruit grove full of fireflies |

---

# STEP 3 & STEP 4 — SCENES (song slots of 4 and 6 seconds; every Flow video is generated at 8 seconds; soundless, eyes always open, always smiling)

**How each scene is shaped:**
Header line (scene number, label, time range and slot) → **Song sync** (editor note only: the lyric words; they are not part of the Flow prompt) → Step 3 Ingredients → Step 3 Reference Image Prompt → Step 4 Ingredients → Video Prompt (Google Flow, generated at 8 s; second marks relative to the clip start; the dance beats first and spare seconds after) → Sound → Cut→.
The lyrics are NOT written inside the Flow prompts. Append the GLOBAL LOCK BLOCK to the end of every Step 3 and Step 4 prompt.

---

### Segment 1 — Intro: the friends run to the big tree (Scenes 1–2) | 0:00–0:12

**S001 — The friends run to the big tree | 0:00–0:06 (6s slot → generate 8s in Flow)**
Song sync: (0:00) "(இசை அறிமுகம்)"
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Meera_Portrait.png`, `Meera_6Angle.png`, `Rohan_Portrait.png`, `Rohan_6Angle.png`, `Tree_Portrait.png`, `Tree_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A sunrise hilltop with a giant mango tree on the horizon) · Scene Continuity Reference: none (first scene in the series)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot on a sunrise hilltop with a giant mango tree on the horizon: Meera (a 7-year-old Tamil girl with warm brown skin, rosy cheeks, a long black braid, a green leaf-crown headband, a green cotton frock with fruit-patch pockets) and Rohan (a 7-year-old Tamil boy with warm brown skin, round cheeks, short black hair, a green leaf-crown headband, an orange shirt with a green apron with fruit-patch pockets) running up the path toward it with big smiles and arms wide, golden rays and floating sparkles, both with bright wide-open eyes. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S001_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S001_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the dance beats, the last 2s are spare footage):
I2V from `S001_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: the camera swoops in low as the children run up the path with their arms wide; 2–4s: they hop in a bouncy dance step and spin once; 4–6s: they strike a happy pose with the tree behind them. 6–8s (spare 2s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 6s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, spinning, hugging the tree or sitting in the nest. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S002: Cut to a dewy path.

**S002 — Animals join the dance | 0:06–0:12 (6s slot → generate 8s in Flow)**
Song sync: (0:06) "(இசை அறிமுகம்)"
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Meera_Portrait.png`, `Meera_6Angle.png`, `Rohan_Portrait.png`, `Rohan_6Angle.png`, `Parrot_Portrait.png`, `Parrot_6Angle.png`, `Squirrel_Portrait.png`, `Squirrel_6Angle.png`, `Monkey_Portrait.png`, `Monkey_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A dewy forest-edge path with ferns and wildflowers) · Scene Continuity Reference: `S001_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Medium shot on a dewy forest-edge path with ferns and wildflowers: Meera (a 7-year-old Tamil girl with warm brown skin, rosy cheeks, a long black braid, a green leaf-crown headband, a green cotton frock with fruit-patch pockets) and Rohan (a 7-year-old Tamil boy with warm brown skin, round cheeks, short black hair, a green leaf-crown headband, an orange shirt with a green apron with fruit-patch pockets) dancing happily with Pachu the green parrot (a red beak, a yellow chest, blue wing tips), the red-brown squirrel with a big fluffy tail and the little brown monkey with a cream face bouncing around them, all with big smiles and bright wide-open eyes. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S002_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S002_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the dance beats, the last 2s are spare footage):
I2V from `S002_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: the animals bounce in from the sides and the children clap on the beat; 2–4s: everyone does a bouncy hop together, Pachu fluttering above; 4–6s: they spin in a circle and pose. 6–8s (spare 2s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 6s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, spinning, hugging the tree or sitting in the nest. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S003: Cut to an orchard.

### Segment 2 — Verse 1: trees give us fruit to eat (Scenes 3–4) | 0:12–0:22

**S003 — Trees give us fruit to eat | 0:12–0:16 (4s slot → generate 8s in Flow)**
Song sync: (0:12) "Trees give us fruit to eat, fruit to eat, fruit to eat."
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Meera_Portrait.png`, `Meera_6Angle.png`, `Rohan_Portrait.png`, `Rohan_6Angle.png`, `Monkey_Portrait.png`, `Monkey_6Angle.png`, `Tree_Portrait.png`, `Tree_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A sunny mango orchard with baskets) · Scene Continuity Reference: `S002_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Medium shot in a sunny mango orchard with baskets on the ground: Meera (a 7-year-old Tamil girl with warm brown skin, rosy cheeks, a long black braid, a green leaf-crown headband, a green cotton frock with fruit-patch pockets) and Rohan (a 7-year-old Tamil boy with warm brown skin, round cheeks, short black hair, a green leaf-crown headband, an orange shirt with a green apron with fruit-patch pockets) holding up a wicker basket under a low branch while the little brown monkey with a cream face sits on the branch dropping golden mangoes gently into it, all with big smiles and bright wide-open eyes. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S003_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S003_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S003_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: the monkey drops a mango into the basket and the children catch it with a happy bounce; 2–4s: the children lift the basket and hop on the beat while more mangoes plop in. 4–8s (spare 4s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, spinning, hugging the tree or sitting in the nest. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S004: Cut to a guava grove.

**S004 — Sharing the fruit | 0:16–0:22 (6s slot → generate 8s in Flow)**
Song sync: (0:17) "Trees give us fruit to eat, every now and then."
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Meera_Portrait.png`, `Meera_6Angle.png`, `Rohan_Portrait.png`, `Rohan_6Angle.png`, `Squirrel_Portrait.png`, `Squirrel_6Angle.png`, `Parrot_Portrait.png`, `Parrot_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A shady guava grove with a wooden fruit stall) · Scene Continuity Reference: `S003_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Medium shot in a shady guava grove beside a wooden fruit stall: Meera (a 7-year-old Tamil girl with warm brown skin, rosy cheeks, a long black braid, a green leaf-crown headband, a green cotton frock with fruit-patch pockets) and Rohan (a 7-year-old Tamil boy with warm brown skin, round cheeks, short black hair, a green leaf-crown headband, an orange shirt with a green apron with fruit-patch pockets) offering guavas and mangoes to the red-brown squirrel with a big fluffy tail and Pachu the green parrot (a red beak, a yellow chest, blue wing tips) on the stall, everyone holding a piece of fruit and smiling with closed mouths, all with bright wide-open eyes. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S004_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S004_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the dance beats, the last 2s are spare footage):
I2V from `S004_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: the children hold fruit up high and sway side to side on the beat; 2–4s: the squirrel and parrot hop and accept the fruit as the children twirl; 4–6s: everyone lifts their fruit together in a happy toast. 6–8s (spare 2s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 6s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, spinning, hugging the tree or sitting in the nest. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S005: Cut to a big banyan.

### Segment 3 — Verse 2: trees give us shade to play (Scenes 5–6) | 0:22–0:30

**S005 — Trees give us shade to play | 0:22–0:26 (4s slot → generate 8s in Flow)**
Song sync: (0:22) "Trees give us shade to play, shade to play, shade to play."
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Meera_Portrait.png`, `Meera_6Angle.png`, `Rohan_Portrait.png`, `Rohan_6Angle.png`, `Squirrel_Portrait.png`, `Squirrel_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A giant banyan tree with a swing and a picnic mat) · Scene Continuity Reference: `S004_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot under a giant banyan tree with a rope swing and a picnic mat in cool dappled shade: Meera (a 7-year-old Tamil girl with warm brown skin, rosy cheeks, a long black braid, a green leaf-crown headband, a green cotton frock with fruit-patch pockets) and Rohan (a 7-year-old Tamil boy with warm brown skin, round cheeks, short black hair, a green leaf-crown headband, an orange shirt with a green apron with fruit-patch pockets) playing a clapping game while the red-brown squirrel with a big fluffy tail bounces on the mat beside them, all with big smiles and bright wide-open eyes. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S005_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S005_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S005_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: the children clap hands together on the beat as the squirrel bounces; 2–4s: they clap, spin and hop in a matching step. 4–8s (spare 4s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, spinning, hugging the tree or sitting in the nest. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S006: Cut to a sunny meadow.

**S006 — Playing in the sun and shade | 0:26–0:30 (4s slot → generate 8s in Flow)**
Song sync: (0:26) "Trees give us shade to play, on a sunny day."
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Meera_Portrait.png`, `Meera_6Angle.png`, `Rohan_Portrait.png`, `Rohan_6Angle.png`, `Parrot_Portrait.png`, `Parrot_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A bright sunny meadow with one big neem tree and a hopscotch drawing) · Scene Continuity Reference: `S005_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot in a bright sunny meadow with one big neem tree casting a pool of shade and a chalk hopscotch drawing: Meera (a 7-year-old Tamil girl with warm brown skin, rosy cheeks, a long black braid, a green leaf-crown headband, a green cotton frock with fruit-patch pockets) and Rohan (a 7-year-old Tamil boy with warm brown skin, round cheeks, short black hair, a green leaf-crown headband, an orange shirt with a green apron with fruit-patch pockets) playing hopscotch in the shade, with big smiles, Pachu the green parrot (a red beak, a yellow chest, blue wing tips) perched on a low branch bobbing, all with bright wide-open eyes. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S006_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S006_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S006_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: the children hop through the hopscotch squares on the beat; 2–4s: they jump out into the sun and back into the shade, arms up. 4–8s (spare 4s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, spinning, hugging the tree or sitting in the nest. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S007: Cut to a tamarind tree.

### Segment 4 — Verse 3: birds build their nest on trees (Scenes 7–8) | 0:30–0:40

**S007 — Birds build their nest on trees | 0:30–0:36 (6s slot → generate 8s in Flow)**
Song sync: (0:31) "Birds build their nest on trees, nest on trees, nest on trees."
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Meera_Portrait.png`, `Meera_6Angle.png`, `Rohan_Portrait.png`, `Rohan_6Angle.png`, `Parrot_Portrait.png`, `Parrot_6Angle.png`, `Tree_Portrait.png`, `Tree_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A tall tamarind tree with a half-built twig nest) · Scene Continuity Reference: `S006_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide low-angle shot beneath a tall tamarind tree with a half-built twig nest in a fork: Pachu the green parrot (a red beak, a yellow chest, blue wing tips) fluttering up with a twig in its beak (beak closed around the twig) while Meera (a 7-year-old Tamil girl with warm brown skin, rosy cheeks, a long black braid, a green leaf-crown headband, a green cotton frock with fruit-patch pockets) and Rohan (a 7-year-old Tamil boy with warm brown skin, round cheeks, short black hair, a green leaf-crown headband, an orange shirt with a green apron with fruit-patch pockets) stand below pointing up and dancing on tiptoe, all with big smiles and bright wide-open eyes. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S007_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S007_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the dance beats, the last 2s are spare footage):
I2V from `S007_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: the children point up and bounce on the beat as Pachu flies in with a twig; 2–4s: Pachu tucks the twig into the nest and the children cheer with raised arms; 4–6s: the children spin while the nest sways gently in the leaves. 6–8s (spare 2s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 6s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, spinning, hugging the tree or sitting in the nest. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S008: Cut to a cosy nest.

**S008 — A safe and happy home | 0:36–0:40 (4s slot → generate 8s in Flow)**
Song sync: (0:36) "Birds build their nest on trees, a safe and happy home."
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Meera_Portrait.png`, `Meera_6Angle.png`, `Rohan_Portrait.png`, `Rohan_6Angle.png`, `Parrot_Portrait.png`, `Parrot_6Angle.png`, `Tree_Portrait.png`, `Tree_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A golden-hour mango tree fork with a finished nest and two chicks) · Scene Continuity Reference: `S007_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Medium shot at golden hour at the fork of the huge friendly mango tree with golden mangoes and a nest in its branches: a finished cosy nest with Pachu the green parrot (a red beak, a yellow chest, blue wing tips) and two fluffy green chicks, and Meera (a 7-year-old Tamil girl with warm brown skin, rosy cheeks, a long black braid, a green leaf-crown headband, a green cotton frock with fruit-patch pockets) and Rohan (a 7-year-old Tamil boy with warm brown skin, round cheeks, short black hair, a green leaf-crown headband, an orange shirt with a green apron with fruit-patch pockets) standing close below with their hands clasped under their chins, smiling, all with bright wide-open eyes. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S008_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S008_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S008_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: the chicks bob on the beat as Pachu spreads her wings gently; 2–4s: the children sway side to side and wave up at the nest. 4–8s (spare 4s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, spinning, hugging the tree or sitting in the nest. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S009: Cut to a garden bed.

### Segment 5 — Verse 4: let's all plant these lovely trees (Scenes 9–10) | 0:40–0:50

**S009 — Let’s all plant these lovely trees | 0:40–0:44 (4s slot → generate 8s in Flow)**
Song sync: (0:40) "Let’s all plant these lovely trees, lovely trees, lovely trees."
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Meera_Portrait.png`, `Meera_6Angle.png`, `Rohan_Portrait.png`, `Rohan_6Angle.png`, `Sapling_Portrait.png`, `Sapling_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A community garden plot with raised soil beds at sunrise) · Scene Continuity Reference: `S008_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Medium shot in a community garden plot with raised soil beds at sunrise: Meera (a 7-year-old Tamil girl with warm brown skin, rosy cheeks, a long black braid, a green leaf-crown headband, a green cotton frock with fruit-patch pockets) and Rohan (a 7-year-old Tamil boy with warm brown skin, round cheeks, short black hair, a green leaf-crown headband, an orange shirt with a green apron with fruit-patch pockets) kneeling and planting the little sapling in a mound of soil with a small red watering can and a small spade together, patting the soil with happy smiles, both with bright wide-open eyes. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S009_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S009_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S009_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: the children lower the sapling into the soil and pat it down on the beat; 2–4s: they stand, throw their arms up and bounce with a big smile. 4–8s (spare 4s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, spinning, hugging the tree or sitting in the nest. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S010: Cut to the watering.

**S010 — Watering the sapling | 0:44–0:50 (6s slot → generate 8s in Flow)**
Song sync: (0:45) "Let’s all plant these lovely trees, every single day."
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Meera_Portrait.png`, `Meera_6Angle.png`, `Rohan_Portrait.png`, `Rohan_6Angle.png`, `Sapling_Portrait.png`, `Sapling_6Angle.png`, `Squirrel_Portrait.png`, `Squirrel_6Angle.png`, `Monkey_Portrait.png`, `Monkey_6Angle.png`, `Parrot_Portrait.png`, `Parrot_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A sunny village green with a stone well) · Scene Continuity Reference: `S009_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Medium shot on a sunny village green next to a stone well: Meera (a 7-year-old Tamil girl with warm brown skin, rosy cheeks, a long black braid, a green leaf-crown headband, a green cotton frock with fruit-patch pockets) and Rohan (a 7-year-old Tamil boy with warm brown skin, round cheeks, short black hair, a green leaf-crown headband, an orange shirt with a green apron with fruit-patch pockets) watering the little sapling in a mound of soil with a small red watering can and a small spade with small red watering cans while the red-brown squirrel with a big fluffy tail, the little brown monkey with a cream face and Pachu the green parrot (a red beak, a yellow chest, blue wing tips) dance beside them, water droplets sparkling, all with big smiles and bright wide-open eyes. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S010_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S010_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the dance beats, the last 2s are spare footage):
I2V from `S010_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: the children pour water in sparkling arcs on the beat; 2–4s: the animals bounce and dance around the sapling; 4–6s: the children hug the little sapling gently and pose. 6–8s (spare 2s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 6s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, spinning, hugging the tree or sitting in the nest. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S011: Cut to a tree-lined avenue.

### Segment 6 — Instrumental dance and the final repeat (Scenes 11–12) | 0:50–1:02

**S011 — The big tree dance party | 0:50–0:56 (6s slot → generate 8s in Flow)**
Song sync: (0:50) "(இசை இடைவேளை)"
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Meera_Portrait.png`, `Meera_6Angle.png`, `Rohan_Portrait.png`, `Rohan_6Angle.png`, `Parrot_Portrait.png`, `Parrot_6Angle.png`, `Squirrel_Portrait.png`, `Squirrel_6Angle.png`, `Monkey_Portrait.png`, `Monkey_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A tree-lined avenue with hanging flower garlands) · Scene Continuity Reference: `S010_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot down a tree-lined avenue with hanging flower garlands and falling petals: Meera (a 7-year-old Tamil girl with warm brown skin, rosy cheeks, a long black braid, a green leaf-crown headband, a green cotton frock with fruit-patch pockets) and Rohan (a 7-year-old Tamil boy with warm brown skin, round cheeks, short black hair, a green leaf-crown headband, an orange shirt with a green apron with fruit-patch pockets) leading a group dance with Pachu the green parrot (a red beak, a yellow chest, blue wing tips), the red-brown squirrel with a big fluffy tail and the little brown monkey with a cream face, everyone dancing in a line with big smiles and bright wide-open eyes. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S011_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S011_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the dance beats, the last 2s are spare footage):
I2V from `S011_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: everyone steps side to side on the beat in a line; 2–4s: they spin in turns with petals swirling; 4–6s: they jump together and pose. 6–8s (spare 2s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 6s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, spinning, hugging the tree or sitting in the nest. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S012: Cut to the sunset grove.

**S012 — Everyone loves the trees | 0:56–1:02 (6s slot → generate 8s in Flow)**
Song sync: (0:56) "Let’s all plant these lovely trees, every single day."
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Meera_Portrait.png`, `Meera_6Angle.png`, `Rohan_Portrait.png`, `Rohan_6Angle.png`, `Parrot_Portrait.png`, `Parrot_6Angle.png`, `Squirrel_Portrait.png`, `Squirrel_6Angle.png`, `Monkey_Portrait.png`, `Monkey_6Angle.png`, `Tree_Portrait.png`, `Tree_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A golden sunset grove of grown fruit trees) · Scene Continuity Reference: `S011_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot in a golden sunset grove of tall grown fruit trees: Meera (a 7-year-old Tamil girl with warm brown skin, rosy cheeks, a long black braid, a green leaf-crown headband, a green cotton frock with fruit-patch pockets) and Rohan (a 7-year-old Tamil boy with warm brown skin, round cheeks, short black hair, a green leaf-crown headband, an orange shirt with a green apron with fruit-patch pockets) hugging the trunk of the huge friendly mango tree with golden mangoes and a nest in its branches with their arms and cheeks resting on it, Pachu the green parrot (a red beak, a yellow chest, blue wing tips), the red-brown squirrel with a big fluffy tail and the little brown monkey with a cream face gathered at their feet, everyone smiling warmly with bright wide-open eyes, sparkles floating. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S012_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S012_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the dance beats, the last 2s are spare footage):
I2V from `S012_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: the children hug the trunk and sway side to side with the animals; 2–4s: they step back, spread their arms wide and look up at the leaves with a happy smile; 4–6s: everyone strikes a joyful group pose as petals and sparkles drift down. 6–8s (spare 2s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 6s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, spinning, hugging the tree or sitting in the nest. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→Fade to black.

---

### Segment 7 — Bonus dance scenes (Scenes 13–20) | bonus (no timestamp)

**S013 — Bamboo grove dance | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any line of the song or between wishes.
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Meera_Portrait.png`, `Meera_6Angle.png`, `Rohan_Portrait.png`, `Rohan_6Angle.png`, `Monkey_Portrait.png`, `Monkey_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A sunbeam bamboo grove) · Scene Continuity Reference: `S012_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot in a sunbeam bamboo grove: Meera (a 7-year-old Tamil girl with warm brown skin, rosy cheeks, a long black braid, a green leaf-crown headband, a green cotton frock with fruit-patch pockets) and Rohan (a 7-year-old Tamil boy with warm brown skin, round cheeks, short black hair, a green leaf-crown headband, an orange shirt with a green apron with fruit-patch pockets) dancing with the little brown monkey with a cream face in the golden light beams, everyone with big smiles and bright wide-open eyes. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S013_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S013_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S013_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: they bounce side to side on the beat; 3–6s: they spin and hop together; 6–8s: they pose with arms up. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, spinning, hugging the tree or sitting in the nest. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→Use as a cutaway or loop.

**S014 — Willow riverbank dance | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any line of the song or between wishes.
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Meera_Portrait.png`, `Meera_6Angle.png`, `Rohan_Portrait.png`, `Rohan_6Angle.png`, `Parrot_Portrait.png`, `Parrot_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A willow-lined riverbank at golden hour) · Scene Continuity Reference: `S013_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot on a willow-lined riverbank at golden hour: Meera (a 7-year-old Tamil girl with warm brown skin, rosy cheeks, a long black braid, a green leaf-crown headband, a green cotton frock with fruit-patch pockets) and Rohan (a 7-year-old Tamil boy with warm brown skin, round cheeks, short black hair, a green leaf-crown headband, an orange shirt with a green apron with fruit-patch pockets) dancing and clapping with Pachu the green parrot (a red beak, a yellow chest, blue wing tips) above them, everyone with big smiles and bright wide-open eyes. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S014_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S014_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S014_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: they clap and step side to side on the beat; 3–6s: they twirl as Pachu loops over their heads; 6–8s: they pose with arms up. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, spinning, hugging the tree or sitting in the nest. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→Use as a cutaway or loop.

**S015 — Coconut-palm beach dance | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any line of the song or between wishes.
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Meera_Portrait.png`, `Meera_6Angle.png`, `Rohan_Portrait.png`, `Rohan_6Angle.png`, `Squirrel_Portrait.png`, `Squirrel_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A coconut-palm beach with soft waves) · Scene Continuity Reference: `S014_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot on a sandy beach lined with coconut palms: Meera (a 7-year-old Tamil girl with warm brown skin, rosy cheeks, a long black braid, a green leaf-crown headband, a green cotton frock with fruit-patch pockets) and Rohan (a 7-year-old Tamil boy with warm brown skin, round cheeks, short black hair, a green leaf-crown headband, an orange shirt with a green apron with fruit-patch pockets) dancing with the red-brown squirrel with a big fluffy tail on the sand, everyone with big smiles and bright wide-open eyes. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S015_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S015_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S015_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: they hop on the beat in the sand; 3–6s: they spin and clap with the squirrel; 6–8s: they pose with arms up. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, spinning, hugging the tree or sitting in the nest. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→Use as a cutaway or loop.

**S016 — Gulmohar avenue twirl | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any line of the song or between wishes.
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Meera_Portrait.png`, `Meera_6Angle.png`, `Rohan_Portrait.png`, `Rohan_6Angle.png`, `Parrot_Portrait.png`, `Parrot_6Angle.png`, `Monkey_Portrait.png`, `Monkey_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A red gulmohar flower avenue) · Scene Continuity Reference: `S015_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot on a flowering red gulmohar avenue with petals falling: Meera (a 7-year-old Tamil girl with warm brown skin, rosy cheeks, a long black braid, a green leaf-crown headband, a green cotton frock with fruit-patch pockets) and Rohan (a 7-year-old Tamil boy with warm brown skin, round cheeks, short black hair, a green leaf-crown headband, an orange shirt with a green apron with fruit-patch pockets) twirling with Pachu the green parrot (a red beak, a yellow chest, blue wing tips) and the little brown monkey with a cream face, everyone with big smiles and bright wide-open eyes. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S016_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S016_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S016_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: they twirl as petals fall; 3–6s: they hop together in a bouncy step; 6–8s: they pose under the petals. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, spinning, hugging the tree or sitting in the nest. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→Use as a cutaway or loop.

**S017 — Rainforest leaf-umbrella dance | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any line of the song or between wishes.
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Meera_Portrait.png`, `Meera_6Angle.png`, `Rohan_Portrait.png`, `Rohan_6Angle.png`, `Squirrel_Portrait.png`, `Squirrel_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A rainforest clearing with giant leaf umbrellas) · Scene Continuity Reference: `S016_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot in a rainforest clearing: Meera (a 7-year-old Tamil girl with warm brown skin, rosy cheeks, a long black braid, a green leaf-crown headband, a green cotton frock with fruit-patch pockets) and Rohan (a 7-year-old Tamil boy with warm brown skin, round cheeks, short black hair, a green leaf-crown headband, an orange shirt with a green apron with fruit-patch pockets) dancing under giant leaf umbrellas with the red-brown squirrel with a big fluffy tail, raindrops sparkling, everyone with big smiles and bright wide-open eyes. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S017_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S017_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S017_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: they spin the leaf umbrellas on the beat; 3–6s: they splash through puddles in a matching step; 6–8s: they pose under the leaves. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, spinning, hugging the tree or sitting in the nest. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→Use as a cutaway or loop.

**S018 — Jackfruit orchard hop | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any line of the song or between wishes.
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Meera_Portrait.png`, `Meera_6Angle.png`, `Rohan_Portrait.png`, `Rohan_6Angle.png`, `Monkey_Portrait.png`, `Monkey_6Angle.png`, `Squirrel_Portrait.png`, `Squirrel_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A jackfruit orchard terrace with stone steps) · Scene Continuity Reference: `S017_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot in a jackfruit orchard terrace with low stone steps: Meera (a 7-year-old Tamil girl with warm brown skin, rosy cheeks, a long black braid, a green leaf-crown headband, a green cotton frock with fruit-patch pockets) and Rohan (a 7-year-old Tamil boy with warm brown skin, round cheeks, short black hair, a green leaf-crown headband, an orange shirt with a green apron with fruit-patch pockets) hopping on the steps with the little brown monkey with a cream face and the red-brown squirrel with a big fluffy tail, everyone with big smiles and bright wide-open eyes. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S018_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S018_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S018_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: they hop up the low steps on the beat; 3–6s: they turn and clap together; 6–8s: they pose together. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, spinning, hugging the tree or sitting in the nest. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→Use as a cutaway or loop.

**S019 — Oak glade circle dance | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any line of the song or between wishes.
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Meera_Portrait.png`, `Meera_6Angle.png`, `Rohan_Portrait.png`, `Rohan_6Angle.png`, `Parrot_Portrait.png`, `Parrot_6Angle.png`, `Squirrel_Portrait.png`, `Squirrel_6Angle.png`, `Monkey_Portrait.png`, `Monkey_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: An ancient oak glade with a fairy ring of mushrooms) · Scene Continuity Reference: `S018_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot in an ancient oak glade with a fairy ring of toadstools: Meera (a 7-year-old Tamil girl with warm brown skin, rosy cheeks, a long black braid, a green leaf-crown headband, a green cotton frock with fruit-patch pockets) and Rohan (a 7-year-old Tamil boy with warm brown skin, round cheeks, short black hair, a green leaf-crown headband, an orange shirt with a green apron with fruit-patch pockets) dancing in a circle with Pachu the green parrot (a red beak, a yellow chest, blue wing tips), the red-brown squirrel with a big fluffy tail and the little brown monkey with a cream face, everyone with big smiles and bright wide-open eyes. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S019_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S019_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S019_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: they walk in a circle on the beat; 3–6s: they spin and bounce; 6–8s: they raise their arms in a group pose. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, spinning, hugging the tree or sitting in the nest. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→Use as a cutaway or loop.

**S020 — Firefly grove finale | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any line of the song or between wishes.
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Meera_Portrait.png`, `Meera_6Angle.png`, `Rohan_Portrait.png`, `Rohan_6Angle.png`, `Parrot_Portrait.png`, `Parrot_6Angle.png`, `Squirrel_Portrait.png`, `Squirrel_6Angle.png`, `Monkey_Portrait.png`, `Monkey_6Angle.png`, `Tree_Portrait.png`, `Tree_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A moonlit fruit grove full of fireflies) · Scene Continuity Reference: `S019_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot in a moonlit fruit grove full of glowing fireflies: Meera (a 7-year-old Tamil girl with warm brown skin, rosy cheeks, a long black braid, a green leaf-crown headband, a green cotton frock with fruit-patch pockets) and Rohan (a 7-year-old Tamil boy with warm brown skin, round cheeks, short black hair, a green leaf-crown headband, an orange shirt with a green apron with fruit-patch pockets) dancing hand in hand around the huge friendly mango tree with golden mangoes and a nest in its branches with Pachu the green parrot (a red beak, a yellow chest, blue wing tips), the red-brown squirrel with a big fluffy tail and the little brown monkey with a cream face, everyone with big smiles and bright wide-open eyes. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S020_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S020_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S020_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: they spin hand in hand as fireflies glow; 3–6s: everyone dances in a happy circle; 6–8s: they strike a joyful group pose. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, spinning, hugging the tree or sitting in the nest. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→Use as a cutaway or loop.

---

# PRODUCTION NOTES

- **Total required:** 20 reference images (`S001_Ref.png` … `S020_Ref.png`) and 20 videos, one video per image: 12 timed scenes that follow the song plus 8 bonus dance scenes. Plus the Step 1 sheets: Meera, Rohan, Pachu the parrot, the squirrel, the monkey, the big tree and the sapling, 7 portraits and 7 six-angle turnarounds (14 images). There are no environment-plate images. Overall: 20 scene images + 14 sheet images = 34 images, and 20 videos.
- **Song length:** no audio file came with this request, so the end is estimated at about 1:02 (the last line starts at 0:56 and takes about 5 s). Send the audio and I will re-check the final cut. The timed scenes add up to 62 s.
- **Song structure (from your timestamps):** 0:00–0:12 instrumental intro; 0:12 and 0:17 "Trees give us fruit to eat"; 0:22 and 0:26 "Trees give us shade to play"; 0:31 and 0:36 "Birds build their nest on trees"; 0:40 and 0:45 the last verse; 0:50–0:56 instrumental; 0:56 the last line repeats. Clips use even seconds, so lines starting at odd seconds start 1 s into a clip; every clip has spare footage, so you can nudge a clip by a second to land a move on a beat.
- **Lyric difference to check:** your lyrics end the song with "Let's all thank these lovely trees", but your timestamped transcript says "Let’s all plant these lovely trees". I followed the transcript (planting and watering a sapling), and the last scene also shows the children hugging the tree to say thanks, so it works for both. Tell me if you want only "thank".
- **Costumes and living things:** the children wear green leaf-crown headbands with fruit-patch aprons (faces fully visible). The other living things follow the lyrics: a monkey and a squirrel for the fruit, the squirrel for the shade games, Pachu the parrot for the nest and chicks. Each verse has its own creature and its own dance move, so the scenes read clearly.
- **Eyes open, always smiling:** the lock block has an EYE RULE, an EYE DESIGN line (big glossy round toy-like eyes with permanently fixed-open eyelids), an AVOID list and a SMILE RULE; every video prompt starts and ends with an eyes-open instruction and every reference-image prompt starts with one. If a clip shows a blink, use another take, use only the first 4 s, regenerate from the same image, or trim before the blink and cross-dissolve; prompts cannot guarantee Flow's output, so check each clip.
- **Soundless clips:** no singing, voices, music or sound effects, and everyone keeps a closed-mouth smile. Your recorded song is added in the edit.
- **What to generate in Flow (8 s or 10 s only):** every video is generated at 8 s. All timed slots are 4 s or 6 s, so each clip has 2–4 s of spare footage after the dance beats. The bonus scenes are 8 s. No scene needs 10 s.

| Generate in Flow | Number of videos | Footage | Scenes |
|---|---|---|---|
| 8 s | 20 | 160 s | all scenes S001–S020 |

- **Slot plan (timed scenes):** the 4 s slots are S003, S005–S006, S008–S009 (5 clips, 20 s); the 6 s slots are S001–S002, S004, S007, S010–S012 (7 clips, 42 s); total 62 s.
- **Timeline rule:** put the song on the timeline at 0:00, drop each timed clip at its scene start time and trim it to its slot. The extra seconds are spare footage. The bonus scenes have no timestamp: use them as cutaways, or loop the song to make a longer video.
- **Image generation is Google Flow only.** Generate the 7 sheets first, then each scene image in order. Video prompts use each scene's saved image as the starting frame.
- **Reminder:** the GLOBAL LOCK BLOCK must be appended in full to the end of every prompt (Step 1, every Step 3 and every Step 4) before submission.
