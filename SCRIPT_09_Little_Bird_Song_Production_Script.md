# SCRIPT 09 — Little Bird, Little Bird: a dancing song with bird-costume kids and forest friends
### [TEMPLATE v3 — Google Flow only · song slots of 4/6 s, Flow clips generated at 8 s · character, animal and prop sheets → a different spot per scene → per-scene reference image → per-scene video · global lock appended to every prompt · no on-screen text · eyes always open, always smiling · soundless dance clips]

**Duration:** 1:00 (song 60.05 s) | **Total Scenes:** 22 = 22 reference images = 22 videos (14 timed scenes + 8 bonus dance scenes)
**Image generation:** Google Flow only (Step 1 sheets, Step 2 location plan, Step 3 scene reference images)
**Video generation:** Google Flow — one video prompt per scene, each generated as an 8 s clip (a 4 s or 6 s song slot plus spare seconds to trim)
**Payoff:** The children and their forest friends dance through the whole song, the little bird flies up to touch the sky, and everyone reaches up together at sunrise.
**Dialogue/Audio rule:** The generated clips are SOUNDLESS action videos: no singing, no lip movement, no voices, no chirps, no music and no sound effects. Your recorded song is added in the edit; every scene is timed to the song.

**Assumptions made for the blank input fields (change if needed):**
- **Style:** 3D animated family-film look with vibrant colours, sparkle and glow. Tell me if you want 2D cartoon instead.
- **Characters:** the girl Mithra (blue bird costume), the boy Arav (yellow bird costume), the little bird Chiku, and forest friends (a squirrel, a rabbit, a frog, a hen with chicks, a fawn, butterflies and bees). The costume wings, beak headbands and tails keep the children's faces fully visible.
- **Hard rules:** no on-screen text or lyrics; nobody sings or chirps; eyes always wide open; everyone always smiling; soundless clips; children never leave the ground.

**Segment map**

| # | Segment | Scenes | Time |
|---|---|---|---|
| 1 | Intro, verse 1 and verse 2: the tree, the flap, the hop and the chirp | S001–S005 | 0:00–0:22 |
| 2 | Verse 3: peck some grain, drink some water | S006–S007 | 0:22–0:30 |
| 3 | Verse 4: fly, fly, fly; fly up high to touch the sky | S008–S009 | 0:30–0:38 |
| 4 | Verse 5: back to the nest to rest, and the dawn dance (instrumental) | S010–S012 | 0:38–0:52 |
| 5 | Verse 4 returns: fly, fly, fly; the finale | S013–S014 | 0:52–1:00 |
| 6 | Bonus dance scenes (use anywhere in the edit) | S015–S022 | bonus (no timestamp) |

---

## ⚠️ GLOBAL LOCK BLOCK — append this in full to the END of every single prompt below (Step 1, every Step 3, every Step 4)

```
GLOBAL LOCK:
CONTINUITY — Keep Mithra (blue bird costume: blue wings, yellow beak headband, blue tail feathers), Arav (yellow bird costume: yellow wings, orange beak headband, yellow tail feathers), the little bird Chiku (round, sky-blue back, golden-yellow belly, orange beak), the squirrel, the rabbit, the frog, the hen with three chicks, the fawn, the butterflies and bees, and the woven nest in exact face, colour, costume and proportion continuity from their saved reference sheets — no redesign, recolor or scale drift. Every scene takes place in its own different spot of the same magical storybook countryside: meadows, trees, ponds, hills and skies in golden light. Never copy the previous scene's spot, background or composition.
CAST RULE — Every scene shows Mithra, Arav and Chiku, plus the other living things the prompt names for that line of the song (squirrel for the tree, rabbit and frog for hopping, butterflies and bees for singing and flying, the hen with chicks for pecking grain, the fawn and frog for drinking water). Only the creatures named in a scene appear in it. No other people.
STYLE — 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination, a warm 35mm-lens depth of field, one consistent colour grade (sunny gold, fresh greens, sky blue, jewel colours), smooth appealing character animation with natural squash and stretch, and high-energy, bouncy dance moves that land exactly on the beat of a happy children's song. The children's bird costumes always keep their faces fully visible.
EYE RULE — Everyone's eyes (the children's, Chiku's and all the animals') are wide open and fully visible in every single frame of every scene, from the first frame to the last: no blinking, no closing, no squinting, no winking, no sleeping, no half-closed or sleepy eyes, and no eyelid motion at all, even when smiling widely, cheering, spinning, landing, snuggling in the nest or swaying at bedtime.
EYE DESIGN — To make blinking impossible, every character has big, glossy, perfectly round eyes with large highlights and eyelids that are permanently fixed open (like toy or doll eyes); a smile only lifts the cheeks and mouth corners while the eyes stay perfectly round.
AVOID — closed eyes, blinking, squinting, eyes shut, winking, half-closed eyelids, sleepy eyes, laughing squint, eyes closed in a smile, eyelids covering the pupils, eyes rolling back.
SMILE RULE — Everyone is smiling happily in every frame, with joyful faces and energetic body language.
MOUTH RULE — Nobody sings, speaks or chirps. Everyone keeps a happy closed-mouth smile (beaks closed), and the dance is carried by bodies, arms, legs, heads, wings and tails.
SAFETY RULE — The children never leave the ground and never go near edges: they run, hop, spin and reach up on tiptoe, with their costume wings flapping; only Chiku, the butterflies and the bees fly. Fully child-friendly: nothing scary, sad or dangerous.
HARD RULES — No on-screen text, captions, lyrics, logos or watermarks. Faces never morph between shots.
ZERO AI ARTIFACTS — No closed or blinking eyes, no morphing, warping, melting, flicker, extra or duplicated limbs, wings, legs or characters, floating debris other than the intended sparkles and petals, texture smearing, distorted hands or feet, costume wings that fuse with bodies.
LIGHTING — Follow the time of day and light written in each scene's prompt; no sudden unintended light jumps inside a shot.
AUDIO — The generated clip is SOUNDLESS: no sound effects, no music, no singing, no speech, no chirps. (If Flow still adds a little ambience, mute it in the edit.) The recorded song is added in the edit.
CAMERA — Smooth, physically plausible motion only; each shot's opening camera motion matches the previous shot's closing motion vector for a seamless cut.
```

---

# STEP 1 — CHARACTER, ANIMAL & PROP REFERENCE IMAGES (Google Flow — image generation ONLY)

### 1A. Girl in the blue bird costume ("Mithra")
**Portrait Image Prompt — Google Flow:**
Full-body portrait of a 7-year-old Tamil girl named Mithra standing in an energetic happy pose with her costume wings spread, facing the camera, with a clearly visible, fully expressive animated face: warm brown skin, rosy cheeks, big sparkling dark eyes wide open, a huge bright smile with a closed mouth. She wears a blue bird costume: big blue feathered wings attached to her arms, a small yellow beak headband on her forehead (her face fully visible), a tail of blue feathers, a sky-blue top and white leggings, bare feet. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination. Neutral light-grey background, soft key light. Eyes wide open, never closed. Locked reference design.
**Save as:** `Mithra_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Mithra_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) with the eyes wide open in every panel, locking the face.
**Save as:** `Mithra_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S001–S022.

### 1B. Boy in the yellow bird costume ("Arav")
**Portrait Image Prompt — Google Flow:**
Full-body portrait of a 7-year-old Tamil boy named Arav standing in an energetic happy pose with his costume wings spread, facing the camera, with a clearly visible, fully expressive animated face: warm brown skin, round cheeks, big dark sparkling eyes wide open, short black hair, a huge cheeky smile with a closed mouth. He wears a yellow bird costume: big yellow feathered wings attached to his arms, a small orange beak headband on his forehead (his face fully visible), a tail of yellow feathers, a yellow top and orange shorts, bare feet. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination. Neutral light-grey background, soft key light. Eyes wide open, never closed. Locked reference design.
**Save as:** `Arav_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Arav_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) with the eyes wide open in every panel, locking the face.
**Save as:** `Arav_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S001–S022.

### 1C. The little bird ("Chiku")
**Portrait Image Prompt — Google Flow:**
A tiny round little bird named Chiku perched on a branch in a happy pose, with a clearly visible, fully expressive animated face: big shiny round black eyes with highlights, wide open, a small orange beak (closed), a sky-blue back and wings, a golden-yellow round belly, a tiny tuft on its head, soft feather detail. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination. Neutral light-grey background, soft key light. Eyes wide open, never closed. Locked reference design.
**Save as:** `Chiku_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Chiku_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) with the eyes wide open in every panel, locking the face.
**Save as:** `Chiku_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S001–S022.

### 1D. Squirrel ("Squirrel")
**Portrait Image Prompt — Google Flow:**
A cute red-brown squirrel standing upright on a branch in a happy pose, with a fully expressive animated face: big round shiny dark eyes wide open, a cream chest, a big fluffy tail, a small acorn in its paws. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination. Neutral light-grey background, soft key light. Eyes wide open, never closed. Locked reference design.
**Save as:** `Squirrel_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Squirrel_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) with the eyes wide open in every panel, locking the face.
**Save as:** `Squirrel_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S001–S003, S010, S012, S014, S021–S022.

### 1E. Rabbit ("Rabbit")
**Portrait Image Prompt — Google Flow:**
A cute fluffy white rabbit with pale-pink inner ears sitting in a happy pose, with a fully expressive animated face: big round shiny dark eyes wide open, a little pink nose, a cotton-ball tail. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination. Neutral light-grey background, soft key light. Eyes wide open, never closed. Locked reference design.
**Save as:** `Rabbit_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Rabbit_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) with the eyes wide open in every panel, locking the face.
**Save as:** `Rabbit_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S001–S002, S004, S012, S014, S016, S021.

### 1F. Frog ("Frog")
**Portrait Image Prompt — Google Flow:**
A cute bright green frog with a pale-green belly sitting on a lily pad in a happy pose, with a fully expressive animated face: big round gold-ringed eyes wide open, a wide gentle closed-mouth smile, small darker-green spots. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination. Neutral light-grey background, soft key light. Eyes wide open, never closed. Locked reference design.
**Save as:** `Frog_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Frog_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) with the eyes wide open in every panel, locking the face.
**Save as:** `Frog_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S001–S002, S004, S007, S012, S014, S016, S019, S021.

### 1G. Hen and three chicks ("HenChicks")
**Portrait Image Prompt — Google Flow:**
A friendly round brown hen with a red comb standing in a happy pose, with three fluffy yellow chicks beside her, all with fully expressive animated faces: big shiny round eyes wide open, small orange beaks (closed). 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination. Neutral light-grey background, soft key light. Eyes wide open, never closed. Locked reference design.
**Save as:** `HenChicks_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `HenChicks_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) with the eyes wide open in every panel, locking the face.
**Save as:** `HenChicks_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S006, S012, S014, S018, S021.

### 1H. Fawn ("Fawn")
**Portrait Image Prompt — Google Flow:**
A gentle young spotted fawn standing in a happy pose, with a fully expressive animated face: big round shiny dark eyes wide open, long lashes, white spots on a golden-brown coat, small ears. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination. Neutral light-grey background, soft key light. Eyes wide open, never closed. Locked reference design.
**Save as:** `Fawn_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Fawn_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) with the eyes wide open in every panel, locking the face.
**Save as:** `Fawn_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S007, S019.

### 1I. Butterflies and bees ("ButterfliesBees")
**Portrait Image Prompt — Google Flow:**
A sheet showing three jewel-coloured butterflies (orange, turquoise and pink wings with gold edges) and two round fuzzy bees with tiny wings, all with cute faces and big shiny eyes wide open, in flight poses with sparkle trails. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination. Neutral light-grey background, soft key light. Eyes wide open, never closed. Locked reference design.
**Save as:** `ButterfliesBees_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `ButterfliesBees_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) with the eyes wide open in every panel, locking the face.
**Save as:** `ButterfliesBees_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S001–S002, S005, S008–S009, S012–S014, S017, S020–S021.

### 1J. The big woven nest (prop) ("Nest")
**Portrait Image Prompt — Google Flow:**
A large cosy round woven nest made of twigs, soft feathers and green leaves, big enough for two children, set in the fork of a banyan tree branch, with a warm inner glow and a few fireflies. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination. Neutral light-grey background, soft key light. Locked reference design.
**Save as:** `Nest_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Nest_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up detail panels.
**Save as:** `Nest_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S011.

---

# STEP 2 — LOCATION PLAN (no reusable environment plates: every scene is a different spot of the same storybook countryside)

There are no shared environment-plate images. Each scene's Step 3 prompt describes its own spot, and `Environment Reference Image` is `none`. All spots belong to the same magical countryside, so the look stays consistent. The spots match the lyrics (a tree, a meadow, a farmyard, a pond, a hillside, a mountain peak, a nest). The table lists every spot so you can check none repeats.

| Scene | Time | Slot | Flow clip | Unique location |
|---|---|---|---|---|
| S001 | 0:00–0:04 | 4s | 8 s | A forest clearing at sunrise with fairy sparkles |
| S002 | 0:04–0:08 | 4s | 8 s | A hilltop meadow with a giant old tree on the horizon |
| S003 | 0:08–0:14 | 6s | 8 s | A giant old oak tree with a rope swing in golden light |
| S004 | 0:14–0:18 | 4s | 8 s | A flower meadow with stepping logs |
| S005 | 0:18–0:22 | 4s | 8 s | A sunlit garden with a little stage of wooden stumps |
| S006 | 0:22–0:26 | 4s | 8 s | A farmyard with a haystack and baskets of grain |
| S007 | 0:26–0:30 | 4s | 8 s | A clear pond with lily pads at the forest edge |
| S008 | 0:30–0:34 | 4s | 8 s | A windy hillside with a sky full of kites |
| S009 | 0:34–0:38 | 4s | 8 s | A mountain peak above a sea of clouds at golden hour |
| S010 | 0:38–0:42 | 4s | 8 s | A mango grove at dusk with fireflies |
| S011 | 0:42–0:46 | 4s | 8 s | A cosy giant nest in a banyan tree under the night stars |
| S012 | 0:46–0:52 | 6s | 8 s | A dewy forest clearing at dawn |
| S013 | 0:52–0:56 | 4s | 8 s | A rainbow-lit waterfall valley |
| S014 | 0:56–1:00 | 4s | 8 s | A seaside cliff at sunrise with a wide sky |
| S015 | bonus (no timestamp) | none | 8 s | A sunny rooftop garden with potted flowers |
| S016 | bonus (no timestamp) | none | 8 s | A springy meadow with giant toadstools |
| S017 | bonus (no timestamp) | none | 8 s | A flowering cherry grove with falling petals |
| S018 | bonus (no timestamp) | none | 8 s | A farmyard with a windmill and hay bales |
| S019 | bonus (no timestamp) | none | 8 s | A shallow stream with stepping stones |
| S020 | bonus (no timestamp) | none | 8 s | A lavender hill at golden hour |
| S021 | bonus (no timestamp) | none | 8 s | A sunflower field at bright noon |
| S022 | bonus (no timestamp) | none | 8 s | A tree glade with hanging hammocks at moonrise |

---

# STEP 3 & STEP 4 — SCENES (song slots of 4 and 6 seconds; every Flow video is generated at 8 seconds; soundless, eyes always open, always smiling)

**How each scene is shaped:**
Header line (scene number, label, time range and slot) → **Song sync** (editor note only: the lyric words; they are not part of the Flow prompt) → Step 3 Ingredients → Step 3 Reference Image Prompt → Step 4 Ingredients → Video Prompt (Google Flow, generated at 8 s; second marks relative to the clip start; the dance beats first and spare seconds after) → Sound → Cut→.
The lyrics are NOT written inside the Flow prompts. Append the GLOBAL LOCK BLOCK to the end of every Step 3 and Step 4 prompt.

---

### Segment 1 — Intro, verse 1 and verse 2: the tree, the flap, the hop and the chirp (Scenes 1–5) | 0:00–0:22

**S001 — The friends gather at sunrise | 0:00–0:04 (4s slot → generate 8s in Flow)**
Song sync: (0:00) "(இசை அறிமுகம்)"
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Mithra_Portrait.png`, `Mithra_6Angle.png`, `Arav_Portrait.png`, `Arav_6Angle.png`, `Chiku_Portrait.png`, `Chiku_6Angle.png`, `Squirrel_Portrait.png`, `Squirrel_6Angle.png`, `Rabbit_Portrait.png`, `Rabbit_6Angle.png`, `Frog_Portrait.png`, `Frog_6Angle.png`, `ButterfliesBees_Portrait.png`, `ButterfliesBees_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A forest clearing at sunrise with fairy sparkles) · Scene Continuity Reference: none (first scene in the series)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot in a forest clearing at sunrise with floating sparkles: the girl Mithra in her blue bird costume (blue feathered wings on her arms, a little yellow beak headband, a tail of blue feathers) and the boy Arav in his yellow bird costume (yellow feathered wings, an orange beak headband, a tail of yellow feathers) standing in the middle with their wings spread and big smiles, the little bird Chiku (a tiny round bird with a sky-blue back, a golden-yellow belly and a small orange beak) perched on Mithra's hand, and gathered around them a squirrel, a rabbit, a frog and a few butterflies, all with bright wide-open eyes, golden rays through the trees, 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S001_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S001_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S001_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: the camera swoops in low as the animals arrive from the sides and bounce on the beat; 2–4s: the children flap their wings in a bouncy dance step as Chiku flutters up and the butterflies circle. 4–8s (spare 4s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth (beaks closed). Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, flapping or landing. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S002: Cut to a hilltop meadow.

**S002 — Wings out: the bird costumes pose | 0:04–0:08 (4s slot → generate 8s in Flow)**
Song sync: (0:04) "(இசை அறிமுகம்)"
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Mithra_Portrait.png`, `Mithra_6Angle.png`, `Arav_Portrait.png`, `Arav_6Angle.png`, `Chiku_Portrait.png`, `Chiku_6Angle.png`, `Squirrel_Portrait.png`, `Squirrel_6Angle.png`, `Rabbit_Portrait.png`, `Rabbit_6Angle.png`, `Frog_Portrait.png`, `Frog_6Angle.png`, `ButterfliesBees_Portrait.png`, `ButterfliesBees_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A hilltop meadow with a giant old tree on the horizon) · Scene Continuity Reference: `S001_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide low-angle shot on a hilltop meadow with a giant old tree on the horizon: the girl Mithra in her blue bird costume (blue feathered wings on her arms, a little yellow beak headband, a tail of blue feathers) and the boy Arav in his yellow bird costume (yellow feathered wings, an orange beak headband, a tail of yellow feathers) striking a joyful pose with their wings spread wide, the little bird Chiku (a tiny round bird with a sky-blue back, a golden-yellow belly and a small orange beak) hovering between them, and the squirrel, rabbit, frog and butterflies posing around them, huge smiles and wide-open eyes, 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S002_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S002_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S002_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: the children spread their wings and bounce into a pose as the animals copy them; 2–4s: they spin in a circle with Chiku flying a loop around them. 4–8s (spare 4s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth (beaks closed). Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, flapping or landing. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S003: Cut to the oak tree.

**S003 — Little bird on the tree: flap, one, two, three | 0:08–0:14 (6s slot → generate 8s in Flow)**
Song sync: (0:08) "Little bird, little bird, on the tree" · (0:11) "flap your wings, one, two, three"
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Mithra_Portrait.png`, `Mithra_6Angle.png`, `Arav_Portrait.png`, `Arav_6Angle.png`, `Chiku_Portrait.png`, `Chiku_6Angle.png`, `Squirrel_Portrait.png`, `Squirrel_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A giant old oak tree with a rope swing in golden light) · Scene Continuity Reference: `S002_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Medium shot under a giant old oak tree with a rope swing in golden light: the little bird Chiku (a tiny round bird with a sky-blue back, a golden-yellow belly and a small orange beak) perched on a branch flapping its wings, a squirrel on the trunk beside it, and below them the girl Mithra in her blue bird costume (blue feathered wings on her arms, a little yellow beak headband, a tail of blue feathers) and the boy Arav in his yellow bird costume (yellow feathered wings, an orange beak headband, a tail of yellow feathers) flapping their costume wings in time, huge smiles and wide-open eyes, 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S003_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S003_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the dance beats, the last 2s are spare footage):
I2V from `S003_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: Chiku flaps on the branch while the squirrel bounces beside it; 2–4s: the children flap their wings three big times in rhythm (one, two, three), raising their arms higher each time; 4–6s: they jump in a happy hold as Chiku flutters down onto Mithra's shoulder. 6–8s (spare 2s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 6s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth (beaks closed). Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, flapping or landing. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S004: Cut to a flower meadow.

**S004 — Hop, hop, hop | 0:14–0:18 (4s slot → generate 8s in Flow)**
Song sync: (0:15) "Little bird, little bird, hop, hop, hop"
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Mithra_Portrait.png`, `Mithra_6Angle.png`, `Arav_Portrait.png`, `Arav_6Angle.png`, `Chiku_Portrait.png`, `Chiku_6Angle.png`, `Rabbit_Portrait.png`, `Rabbit_6Angle.png`, `Frog_Portrait.png`, `Frog_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A flower meadow with stepping logs) · Scene Continuity Reference: `S003_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Medium shot in a flower meadow with stepping logs: the girl Mithra in her blue bird costume (blue feathered wings on her arms, a little yellow beak headband, a tail of blue feathers) and the boy Arav in his yellow bird costume (yellow feathered wings, an orange beak headband, a tail of yellow feathers) hopping with their wings out, the little bird Chiku (a tiny round bird with a sky-blue back, a golden-yellow belly and a small orange beak) hopping on a log between them, and a rabbit and a frog hopping along the logs beside them, bright smiles and wide-open eyes, 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S004_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S004_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S004_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: everyone hops once together on the beat, the rabbit and frog landing on the logs; 2–4s: they hop three times in a row (hop, hop, hop), Chiku hopping in the middle with its wings flapping. 4–8s (spare 4s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth (beaks closed). Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, flapping or landing. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S005: Cut to a garden bandstand.

**S005 — Sing a happy song: chirp, chirp, chirp | 0:18–0:22 (4s slot → generate 8s in Flow)**
Song sync: (0:18) "sing a happy song" · (0:20) "chirp, chirp, chirp"
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Mithra_Portrait.png`, `Mithra_6Angle.png`, `Arav_Portrait.png`, `Arav_6Angle.png`, `Chiku_Portrait.png`, `Chiku_6Angle.png`, `ButterfliesBees_Portrait.png`, `ButterfliesBees_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A sunlit garden with a little stage of wooden stumps) · Scene Continuity Reference: `S004_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Medium shot on a little stage of wooden stumps in a sunlit garden of hibiscus flowers: the girl Mithra in her blue bird costume (blue feathered wings on her arms, a little yellow beak headband, a tail of blue feathers) and the boy Arav in his yellow bird costume (yellow feathered wings, an orange beak headband, a tail of yellow feathers) dancing with their arms swaying, the little bird Chiku (a tiny round bird with a sky-blue back, a golden-yellow belly and a small orange beak) on the tallest stump with its wings spread, and butterflies and bees dancing in the air around them, everyone with huge smiles and wide-open eyes, 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S005_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S005_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S005_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: the children sway and clap on the beat as Chiku bobs on its stump; 2–4s: they pop three quick dance moves (chirp, chirp, chirp) as the butterflies and bees swirl in a happy loop. 4–8s (spare 4s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth (beaks closed). Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, flapping or landing. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S006: Cut to a farmyard.

---

### Segment 2 — Verse 3: peck some grain, drink some water (Scenes 6–7) | 0:22–0:30

**S006 — Peck some grain | 0:22–0:26 (4s slot → generate 8s in Flow)**
Song sync: (0:22) "Little bird, little bird, peck some grain"
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Mithra_Portrait.png`, `Mithra_6Angle.png`, `Arav_Portrait.png`, `Arav_6Angle.png`, `Chiku_Portrait.png`, `Chiku_6Angle.png`, `HenChicks_Portrait.png`, `HenChicks_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A farmyard with a haystack and baskets of grain) · Scene Continuity Reference: `S005_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Medium shot in a farmyard with a haystack and baskets of golden grain: the girl Mithra in her blue bird costume (blue feathered wings on her arms, a little yellow beak headband, a tail of blue feathers) and the boy Arav in his yellow bird costume (yellow feathered wings, an orange beak headband, a tail of yellow feathers) kneeling and sprinkling grain from small baskets, the little bird Chiku (a tiny round bird with a sky-blue back, a golden-yellow belly and a small orange beak) pecking grain beside them, and a hen with three fluffy yellow chicks pecking the grain too, big happy smiles and wide-open eyes, 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S006_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S006_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S006_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: the children sprinkle grain in a bouncy rhythm as Chiku and the chicks peck on the beat; 2–4s: they peck-bob their heads like birds with big grins, the hen bobbing too. 4–8s (spare 4s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth (beaks closed). Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, flapping or landing. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S007: Cut to a pond.

**S007 — Drink some water, and peck again | 0:26–0:30 (4s slot → generate 8s in Flow)**
Song sync: (0:26) "drink some water and peck again"
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Mithra_Portrait.png`, `Mithra_6Angle.png`, `Arav_Portrait.png`, `Arav_6Angle.png`, `Chiku_Portrait.png`, `Chiku_6Angle.png`, `Fawn_Portrait.png`, `Fawn_6Angle.png`, `Frog_Portrait.png`, `Frog_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A clear pond with lily pads at the forest edge) · Scene Continuity Reference: `S006_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Medium shot at a clear pond with lily pads at the forest edge: the girl Mithra in her blue bird costume (blue feathered wings on her arms, a little yellow beak headband, a tail of blue feathers) and the boy Arav in his yellow bird costume (yellow feathered wings, an orange beak headband, a tail of yellow feathers) sitting on a mossy log, the little bird Chiku (a tiny round bird with a sky-blue back, a golden-yellow belly and a small orange beak) dipping its beak in the water on a lily pad, a young fawn drinking from the pond beside them and a frog on a lily pad, big smiles and wide-open eyes, 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S007_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S007_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S007_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: Chiku dips its beak in the water and lifts its head on the beat as the fawn drinks; 2–4s: the children scoop their hands in a drinking motion and then pretend to peck, bobbing and smiling as the frog hops to a new lily pad. 4–8s (spare 4s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth (beaks closed). Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, flapping or landing. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S008: Cut to a windy hillside.

---

### Segment 3 — Verse 4: fly, fly, fly; fly up high to touch the sky (Scenes 8–9) | 0:30–0:38

**S008 — Fly, fly, fly | 0:30–0:34 (4s slot → generate 8s in Flow)**
Song sync: (0:30) "Little bird, little bird, fly, fly, fly"
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Mithra_Portrait.png`, `Mithra_6Angle.png`, `Arav_Portrait.png`, `Arav_6Angle.png`, `Chiku_Portrait.png`, `Chiku_6Angle.png`, `ButterfliesBees_Portrait.png`, `ButterfliesBees_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A windy hillside with a sky full of kites) · Scene Continuity Reference: `S007_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide low-angle shot on a windy hillside with a sky full of colourful kites: the girl Mithra in her blue bird costume (blue feathered wings on her arms, a little yellow beak headband, a tail of blue feathers) and the boy Arav in his yellow bird costume (yellow feathered wings, an orange beak headband, a tail of yellow feathers) running with their wings spread wide and bright wide-open eyes, the little bird Chiku (a tiny round bird with a sky-blue back, a golden-yellow belly and a small orange beak) flying just above them, and butterflies and bees flying beside them, grass bending in the wind, 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S008_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S008_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S008_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: the children run up the hill with their wings spread as Chiku swoops overhead; 2–4s: they spin and flap their wings in a happy dance while the butterflies and bees streak past. 4–8s (spare 4s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth (beaks closed). Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, flapping or landing. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S009: Cut to a mountain peak.

**S009 — Fly up high, to touch the sky | 0:34–0:38 (4s slot → generate 8s in Flow)**
Song sync: (0:34) "fly up high to touch the sky"
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Mithra_Portrait.png`, `Mithra_6Angle.png`, `Arav_Portrait.png`, `Arav_6Angle.png`, `Chiku_Portrait.png`, `Chiku_6Angle.png`, `ButterfliesBees_Portrait.png`, `ButterfliesBees_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A mountain peak above a sea of clouds at golden hour) · Scene Continuity Reference: `S008_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot on a mountain peak above a sea of clouds at golden hour: the girl Mithra in her blue bird costume (blue feathered wings on her arms, a little yellow beak headband, a tail of blue feathers) and the boy Arav in his yellow bird costume (yellow feathered wings, an orange beak headband, a tail of yellow feathers) standing on tiptoe on the rocky peak with their arms and wings reaching up to the sky, wide-open eyes and huge smiles, the little bird Chiku (a tiny round bird with a sky-blue back, a golden-yellow belly and a small orange beak) flying high above their hands and butterflies spiralling up around it, 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S009_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S009_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S009_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: the children stretch up on tiptoe with their wings spread as Chiku flies higher; 2–4s: Chiku and the butterflies spiral up through the golden clouds and the children cheer with their arms up. 4–8s (spare 4s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth (beaks closed). Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, flapping or landing. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S010: Cut to a mango grove at dusk.

---

### Segment 4 — Verse 5: back to the nest to rest, and the dawn dance (instrumental) (Scenes 10–12) | 0:38–0:52

**S010 — Back to the nest | 0:38–0:42 (4s slot → generate 8s in Flow)**
Song sync: (0:38) "Little bird, little bird, back to the nest"
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Mithra_Portrait.png`, `Mithra_6Angle.png`, `Arav_Portrait.png`, `Arav_6Angle.png`, `Chiku_Portrait.png`, `Chiku_6Angle.png`, `Squirrel_Portrait.png`, `Squirrel_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A mango grove at dusk with fireflies) · Scene Continuity Reference: `S009_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot in a mango grove at dusk with the first fireflies: the little bird Chiku (a tiny round bird with a sky-blue back, a golden-yellow belly and a small orange beak) flying toward a big woven nest in a mango tree, the girl Mithra in her blue bird costume (blue feathered wings on her arms, a little yellow beak headband, a tail of blue feathers) and the boy Arav in his yellow bird costume (yellow feathered wings, an orange beak headband, a tail of yellow feathers) skipping beneath the tree with their wings spread and wide-open eyes, a squirrel on a branch watching, warm orange sky, 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S010_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S010_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S010_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: Chiku flies in a graceful curve toward the nest as the children skip along beneath it; 2–4s: Chiku lands on the nest's edge and the children wave up at it with big smiles. 4–8s (spare 4s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth (beaks closed). Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, flapping or landing. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S011: Cut to the nest at night.

**S011 — Back to the nest: time to rest | 0:42–0:46 (4s slot → generate 8s in Flow)**
Song sync: (0:42) "back to the nest, to get some rest"
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Mithra_Portrait.png`, `Mithra_6Angle.png`, `Arav_Portrait.png`, `Arav_6Angle.png`, `Chiku_Portrait.png`, `Chiku_6Angle.png`, `Nest_Portrait.png`, `Nest_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A cosy giant nest in a banyan tree under the night stars) · Scene Continuity Reference: `S010_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Medium shot in a giant woven nest in a banyan tree under a night sky full of stars and fireflies: the girl Mithra in her blue bird costume (blue feathered wings on her arms, a little yellow beak headband, a tail of blue feathers) and the boy Arav in his yellow bird costume (yellow feathered wings, an orange beak headband, a tail of yellow feathers) snuggled in the nest with the little bird Chiku (a tiny round bird with a sky-blue back, a golden-yellow belly and a small orange beak) between them, all smiling happily with bright wide-open eyes and swaying slowly, a warm glow around the nest, 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S011_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S011_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S011_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: the children and Chiku snuggle together in the nest and sway gently, eyes wide open; 2–4s: they wave their wings softly and the fireflies drift around them as the nest glows warmly. 4–8s (spare 4s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth (beaks closed). Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, flapping or landing. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S012: Cut to a dawn clearing.

**S012 — Dawn wake-up dance party | 0:46–0:52 (6s slot → generate 8s in Flow)**
Song sync: (0:46) "(இசை இடைவெளி)"
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Mithra_Portrait.png`, `Mithra_6Angle.png`, `Arav_Portrait.png`, `Arav_6Angle.png`, `Chiku_Portrait.png`, `Chiku_6Angle.png`, `Squirrel_Portrait.png`, `Squirrel_6Angle.png`, `Rabbit_Portrait.png`, `Rabbit_6Angle.png`, `Frog_Portrait.png`, `Frog_6Angle.png`, `HenChicks_Portrait.png`, `HenChicks_6Angle.png`, `ButterfliesBees_Portrait.png`, `ButterfliesBees_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A dewy forest clearing at dawn) · Scene Continuity Reference: `S011_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot in a dewy forest clearing at dawn: the girl Mithra in her blue bird costume (blue feathered wings on her arms, a little yellow beak headband, a tail of blue feathers) and the boy Arav in his yellow bird costume (yellow feathered wings, an orange beak headband, a tail of yellow feathers) dancing with their wings spread, the little bird Chiku (a tiny round bird with a sky-blue back, a golden-yellow belly and a small orange beak) flying a loop above them, and a squirrel, a rabbit, a frog, a hen with her chicks and butterflies all dancing around them in a happy circle, everyone with bright wide-open eyes, 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S012_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S012_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the dance beats, the last 2s are spare footage):
I2V from `S012_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: the children stretch their wings and the animals bounce in; 2–4s: everyone dances in a circle on the beat with Chiku looping overhead; 4–6s: they all strike a joyful pose together as the sun rises. 6–8s (spare 2s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 6s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth (beaks closed). Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, flapping or landing. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S013: Cut to a rainbow valley.

---

### Segment 5 — Verse 4 returns: fly, fly, fly; the finale (Scenes 13–14) | 0:52–1:00

**S013 — Fly, fly, fly again | 0:52–0:56 (4s slot → generate 8s in Flow)**
Song sync: (0:52) "Little bird, little bird, fly, fly, fly"
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Mithra_Portrait.png`, `Mithra_6Angle.png`, `Arav_Portrait.png`, `Arav_6Angle.png`, `Chiku_Portrait.png`, `Chiku_6Angle.png`, `ButterfliesBees_Portrait.png`, `ButterfliesBees_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A rainbow-lit waterfall valley) · Scene Continuity Reference: `S012_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot in a rainbow-lit waterfall valley with misty falls: the girl Mithra in her blue bird costume (blue feathered wings on her arms, a little yellow beak headband, a tail of blue feathers) and the boy Arav in his yellow bird costume (yellow feathered wings, an orange beak headband, a tail of yellow feathers) running along a grassy ridge with their wings spread, the little bird Chiku (a tiny round bird with a sky-blue back, a golden-yellow belly and a small orange beak) soaring beside them, and butterflies and bees streaming past through the rainbow mist, wide-open eyes and huge smiles, 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S013_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S013_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S013_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: the children run and flap their wings as Chiku swoops through the rainbow; 2–4s: they spin with their arms up as the butterflies and bees swirl in the mist. 4–8s (spare 4s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth (beaks closed). Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, flapping or landing. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S014: Cut to a sunrise cliff.

**S014 — Fly up high, to touch the sky: the finale | 0:56–1:00 (4s slot → generate 8s in Flow)**
Song sync: (0:56) "fly up high to touch the sky"
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Mithra_Portrait.png`, `Mithra_6Angle.png`, `Arav_Portrait.png`, `Arav_6Angle.png`, `Chiku_Portrait.png`, `Chiku_6Angle.png`, `Squirrel_Portrait.png`, `Squirrel_6Angle.png`, `Rabbit_Portrait.png`, `Rabbit_6Angle.png`, `Frog_Portrait.png`, `Frog_6Angle.png`, `HenChicks_Portrait.png`, `HenChicks_6Angle.png`, `ButterfliesBees_Portrait.png`, `ButterfliesBees_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A seaside cliff at sunrise with a wide sky) · Scene Continuity Reference: `S013_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot at a seaside cliff at sunrise with a wide golden sky: the girl Mithra in her blue bird costume (blue feathered wings on her arms, a little yellow beak headband, a tail of blue feathers) and the boy Arav in his yellow bird costume (yellow feathered wings, an orange beak headband, a tail of yellow feathers) on the cliff top with their wings spread and arms reaching up, the little bird Chiku (a tiny round bird with a sky-blue back, a golden-yellow belly and a small orange beak) flying high above, and the squirrel, rabbit, frog, hen with chicks, butterflies and bees all gathered and looking up with bright wide-open eyes and happy smiles, 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S014_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S014_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S014_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: everyone reaches up together as Chiku and the butterflies fly up into the sunrise; 2–4s: the children strike a final happy pose with the animals around them as the camera cranes up and the sun glows. 4–8s (spare 4s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth (beaks closed). Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, flapping or landing. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→END of the timed song: fade out over the last second (the bonus scenes S015–S022 are optional cutaways).

---

### Segment 6 — Bonus dance scenes (use anywhere in the edit) (Scenes 15–22)

**S015 — Bonus 1: the flap one-two-three dance | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free dance cutaway: cut it in over any part of the song.
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Mithra_Portrait.png`, `Mithra_6Angle.png`, `Arav_Portrait.png`, `Arav_6Angle.png`, `Chiku_Portrait.png`, `Chiku_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A sunny rooftop garden with potted flowers) · Scene Continuity Reference: `S014_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot at a sunny rooftop garden with potted flowers: the girl Mithra in her blue bird costume (blue feathered wings on her arms, a little yellow beak headband, a tail of blue feathers) and the boy Arav in his yellow bird costume (yellow feathered wings, an orange beak headband, a tail of yellow feathers) in a playful start pose with huge smiles and wide-open eyes, with the little bird Chiku (a tiny round bird with a sky-blue back, a golden-yellow belly and a small orange beak) beside them, 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S015_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S015_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S015_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: the children start an energetic dance to a bouncy beat, flapping their wings in three big flaps (one, two, three) with Chiku flapping beside them; 3–6s: they repeat the move with a bigger bounce and a spin, grinning at each other in time with the beat; 6–8s: the camera circles them as they strike a joyful pose and the movement settles. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth (beaks closed). Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, flapping or landing. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S016: Use as a cutaway or loop anywhere in the edit.

**S016 — Bonus 2: the hop party | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free dance cutaway: cut it in over any part of the song.
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Mithra_Portrait.png`, `Mithra_6Angle.png`, `Arav_Portrait.png`, `Arav_6Angle.png`, `Chiku_Portrait.png`, `Chiku_6Angle.png`, `Rabbit_Portrait.png`, `Rabbit_6Angle.png`, `Frog_Portrait.png`, `Frog_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A springy meadow with giant toadstools) · Scene Continuity Reference: `S015_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot at a springy meadow with giant toadstools: the girl Mithra in her blue bird costume (blue feathered wings on her arms, a little yellow beak headband, a tail of blue feathers) and the boy Arav in his yellow bird costume (yellow feathered wings, an orange beak headband, a tail of yellow feathers) in a playful start pose with huge smiles and wide-open eyes, with the rabbit, the frog and Chiku beside them, 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S016_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S016_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S016_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: the children start an energetic dance to a bouncy beat, hopping on the toadstools in rhythm with the rabbit, frog and Chiku hopping along; 3–6s: they repeat the move with a bigger bounce and a spin, grinning at each other in time with the beat; 6–8s: the camera circles them as they strike a joyful pose and the movement settles. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth (beaks closed). Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, flapping or landing. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S017: Use as a cutaway or loop anywhere in the edit.

**S017 — Bonus 3: the feather shuffle | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free dance cutaway: cut it in over any part of the song.
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Mithra_Portrait.png`, `Mithra_6Angle.png`, `Arav_Portrait.png`, `Arav_6Angle.png`, `Chiku_Portrait.png`, `Chiku_6Angle.png`, `ButterfliesBees_Portrait.png`, `ButterfliesBees_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A flowering cherry grove with falling petals) · Scene Continuity Reference: `S016_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot at a flowering cherry grove with falling petals: the girl Mithra in her blue bird costume (blue feathered wings on her arms, a little yellow beak headband, a tail of blue feathers) and the boy Arav in his yellow bird costume (yellow feathered wings, an orange beak headband, a tail of yellow feathers) in a playful start pose with huge smiles and wide-open eyes, with Chiku and the butterflies beside them, 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S017_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S017_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S017_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: the children start an energetic dance to a bouncy beat, doing a feather shuffle, swishing their tail feathers and shimmying while Chiku and the butterflies dance around them; 3–6s: they repeat the move with a bigger bounce and a spin, grinning at each other in time with the beat; 6–8s: the camera circles them as they strike a joyful pose and the movement settles. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth (beaks closed). Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, flapping or landing. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S018: Use as a cutaway or loop anywhere in the edit.

**S018 — Bonus 4: the grain-peck beat | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free dance cutaway: cut it in over any part of the song.
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Mithra_Portrait.png`, `Mithra_6Angle.png`, `Arav_Portrait.png`, `Arav_6Angle.png`, `Chiku_Portrait.png`, `Chiku_6Angle.png`, `HenChicks_Portrait.png`, `HenChicks_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A farmyard with a windmill and hay bales) · Scene Continuity Reference: `S017_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot at a farmyard with a windmill and hay bales: the girl Mithra in her blue bird costume (blue feathered wings on her arms, a little yellow beak headband, a tail of blue feathers) and the boy Arav in his yellow bird costume (yellow feathered wings, an orange beak headband, a tail of yellow feathers) in a playful start pose with huge smiles and wide-open eyes, with the hen with her chicks and Chiku beside them, 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S018_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S018_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S018_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: the children start an energetic dance to a bouncy beat, pecking and bobbing on the beat with the hen, her chicks and Chiku; 3–6s: they repeat the move with a bigger bounce and a spin, grinning at each other in time with the beat; 6–8s: the camera circles them as they strike a joyful pose and the movement settles. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth (beaks closed). Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, flapping or landing. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S019: Use as a cutaway or loop anywhere in the edit.

**S019 — Bonus 5: the splash dance | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free dance cutaway: cut it in over any part of the song.
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Mithra_Portrait.png`, `Mithra_6Angle.png`, `Arav_Portrait.png`, `Arav_6Angle.png`, `Chiku_Portrait.png`, `Chiku_6Angle.png`, `Fawn_Portrait.png`, `Fawn_6Angle.png`, `Frog_Portrait.png`, `Frog_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A shallow stream with stepping stones) · Scene Continuity Reference: `S018_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot at a shallow stream with stepping stones: the girl Mithra in her blue bird costume (blue feathered wings on her arms, a little yellow beak headband, a tail of blue feathers) and the boy Arav in his yellow bird costume (yellow feathered wings, an orange beak headband, a tail of yellow feathers) in a playful start pose with huge smiles and wide-open eyes, with the fawn, the frog and Chiku beside them, 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S019_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S019_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S019_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: the children start an energetic dance to a bouncy beat, splashing and hopping across the stepping stones with the fawn, frog and Chiku joining in; 3–6s: they repeat the move with a bigger bounce and a spin, grinning at each other in time with the beat; 6–8s: the camera circles them as they strike a joyful pose and the movement settles. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth (beaks closed). Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, flapping or landing. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S020: Use as a cutaway or loop anywhere in the edit.

**S020 — Bonus 6: the butterfly twirl | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free dance cutaway: cut it in over any part of the song.
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Mithra_Portrait.png`, `Mithra_6Angle.png`, `Arav_Portrait.png`, `Arav_6Angle.png`, `Chiku_Portrait.png`, `Chiku_6Angle.png`, `ButterfliesBees_Portrait.png`, `ButterfliesBees_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A lavender hill at golden hour) · Scene Continuity Reference: `S019_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot at a lavender hill at golden hour: the girl Mithra in her blue bird costume (blue feathered wings on her arms, a little yellow beak headband, a tail of blue feathers) and the boy Arav in his yellow bird costume (yellow feathered wings, an orange beak headband, a tail of yellow feathers) in a playful start pose with huge smiles and wide-open eyes, with Chiku, the butterflies and the bees beside them, 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S020_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S020_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S020_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: the children start an energetic dance to a bouncy beat, twirling with their wings out while Chiku, the butterflies and the bees spiral around them; 3–6s: they repeat the move with a bigger bounce and a spin, grinning at each other in time with the beat; 6–8s: the camera circles them as they strike a joyful pose and the movement settles. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth (beaks closed). Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, flapping or landing. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S021: Use as a cutaway or loop anywhere in the edit.

**S021 — Bonus 7: the animal conga line | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free dance cutaway: cut it in over any part of the song.
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Mithra_Portrait.png`, `Mithra_6Angle.png`, `Arav_Portrait.png`, `Arav_6Angle.png`, `Chiku_Portrait.png`, `Chiku_6Angle.png`, `Squirrel_Portrait.png`, `Squirrel_6Angle.png`, `Rabbit_Portrait.png`, `Rabbit_6Angle.png`, `Frog_Portrait.png`, `Frog_6Angle.png`, `HenChicks_Portrait.png`, `HenChicks_6Angle.png`, `ButterfliesBees_Portrait.png`, `ButterfliesBees_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A sunflower field at bright noon) · Scene Continuity Reference: `S020_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot at a sunflower field at bright noon: the girl Mithra in her blue bird costume (blue feathered wings on her arms, a little yellow beak headband, a tail of blue feathers) and the boy Arav in his yellow bird costume (yellow feathered wings, an orange beak headband, a tail of yellow feathers) in a playful start pose with huge smiles and wide-open eyes, with all the animals and Chiku beside them, 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S021_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S021_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S021_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: the children start an energetic dance to a bouncy beat, leading a bouncy conga line with the squirrel, rabbit, frog, hen with her chicks and Chiku following; 3–6s: they repeat the move with a bigger bounce and a spin, grinning at each other in time with the beat; 6–8s: the camera circles them as they strike a joyful pose and the movement settles. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth (beaks closed). Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, flapping or landing. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S022: Use as a cutaway or loop anywhere in the edit.

**S022 — Bonus 8: the moonrise sway | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free dance cutaway: cut it in over any part of the song.
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Mithra_Portrait.png`, `Mithra_6Angle.png`, `Arav_Portrait.png`, `Arav_6Angle.png`, `Chiku_Portrait.png`, `Chiku_6Angle.png`, `Squirrel_Portrait.png`, `Squirrel_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A tree glade with hanging hammocks at moonrise) · Scene Continuity Reference: `S021_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot at a tree glade with hanging hammocks at moonrise: the girl Mithra in her blue bird costume (blue feathered wings on her arms, a little yellow beak headband, a tail of blue feathers) and the boy Arav in his yellow bird costume (yellow feathered wings, an orange beak headband, a tail of yellow feathers) in a playful start pose with huge smiles and wide-open eyes, with Chiku and the squirrel beside them, 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S022_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S022_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S022_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: the children start an energetic dance to a bouncy beat, swaying side to side with their wings out in a calm happy dance (eyes wide open) while Chiku, the squirrel and the fireflies sway too; 3–6s: they repeat the move with a bigger bounce and a spin, grinning at each other in time with the beat; 6–8s: the camera circles them as they strike a joyful pose and the movement settles. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth (beaks closed). Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, cheering, spinning, flapping or landing. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→Use as a cutaway or loop anywhere in the edit.

---

# PRODUCTION NOTES

- **Total required:** 22 reference images (`S001_Ref.png` … `S022_Ref.png`) and 22 videos, one video per image: 14 timed scenes that follow the song plus 8 bonus dance scenes. Plus the Step 1 sheets: the two children in bird costumes, the little bird, the squirrel, the rabbit, the frog, the hen with chicks, the fawn, the butterflies and bees, and the nest, 10 portraits and 10 six-angle turnarounds (20 images). There are no environment-plate images. Overall: 22 scene images + 20 sheet images = 42 images, and 22 videos.
- **Song length:** the attached audio is 60.05 s (measured from the file header; I cannot hear it), so the timed scenes run 0:00–1:00 and add up to 60 s. Your timestamps cover the five verses and the repeat of verse 4.
- **Song structure (from your timestamps):** 0:00–0:08 intro; 0:08 "on the tree, flap your wings, one, two, three"; 0:15 "hop, hop, hop, sing a happy song, chirp, chirp, chirp"; 0:22 "peck some grain, drink some water and peck again"; 0:30 "fly, fly, fly, fly up high to touch the sky"; 0:38 "back to the nest, to get some rest"; 0:46–0:52 instrumental (a dawn dance party); 0:52 "fly, fly, fly, fly up high to touch the sky" again. Clips use even seconds, so a few lines start 1 s into a clip; every clip has spare footage, so you can nudge a clip by a second to land a move on a beat.
- **Costumes and the other living things:** the children wear bird costumes (a blue bird and a yellow bird, with wings, beak headbands and tail feathers, faces fully visible), and the little bird Chiku wears the same two colours so they match. The other living things follow the lyrics: a squirrel on the tree, a rabbit and a frog for the hops, butterflies and bees for the chirping and flying, a hen with chicks pecking grain, a fawn drinking water. Each line of the song brings a different creature, so each scene reads clearly.
- **Eyes open, always smiling:** the lock block has an EYE RULE and a SMILE RULE, every video prompt ends with an eyes-open sentence, every reference-image prompt says the eyes are wide open, and the sheets show eyes wide open. The "rest" line is shown with everyone snuggled in the nest swaying happily with eyes wide open. If a clip shows a closed or blinking eye, regenerate it or use another take from the spare seconds. Strengthened: eyes are described as big glossy round toy-like eyes with fixed-open eyelids, the eye instruction comes first in every prompt, and there is an AVOID list. If a take still blinks, use another take, use only the first 4 s, regenerate from a clearly open-eyed scene image, or trim before the blink and cross-dissolve.
- **Soundless clips:** no singing, voices, chirps, music or sound effects, and everyone keeps a closed-mouth smile (beaks closed). Your recorded song is added in the edit. If you want the little bird or the children to move their mouths as if singing, tell me and I'll change the mouth rule.
- **Safety:** the children run, hop, spin and reach up on tiptoe with their costume wings flapping; only Chiku, the butterflies and the bees actually fly, so no child is shown flying or near an edge.
- **What to generate in Flow (8 s or 10 s only):** every video is generated at 8 s. All timed slots are 4 s or 6 s, so each clip has 2–4 s of spare footage after the dance beats. The bonus scenes are 8 s. No scene needs 10 s.

| Generate in Flow | Number of videos | Footage | Scenes |
|---|---|---|---|
| 8 s | 22 | 176 s | all scenes S001–S022 |

- **Slot plan (timed scenes):** the 4 s slots are S001, S002, S004–S011, S013 and S014 (12 clips, 48 s); the 6 s slots are S003 and S012 (2 clips, 12 s); total 60 s.
- **Timeline rule:** put the song on the timeline at 0:00, drop each timed clip at its scene start time and trim it to its slot. The extra seconds are spare footage. The bonus scenes have no timestamp: use them as cutaways over any verse, or loop the song to make a longer video.
- **Making it addictive:** each line of the song has its own move (flap one-two-three, hop-hop-hop, chirp-chirp-chirp sways, peck-bobbing, drinking scoops, running and reaching up), a quick visual change every 4 s, a new creature joining almost every line, and a big group dance in the instrumental break before the finale.
- **Image generation is Google Flow only.** Generate the 10 sheets first, then each scene image in order. Video prompts use each scene's saved image as the starting frame.
- **Reminder:** the GLOBAL LOCK BLOCK must be appended in full to the end of every prompt (Step 1, every Step 3 and every Step 4) before submission.
