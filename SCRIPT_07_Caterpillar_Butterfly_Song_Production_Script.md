# SCRIPT 07 — Crawl, Eat, Sleep, Peep, Fly: an energetic caterpillar-to-butterfly dance song
### [TEMPLATE v3 — Google Flow only · song slots of 4 s, Flow clips generated at 8 s · character and prop sheets → a different garden spot per scene → per-scene reference image → per-scene video · global lock appended to every prompt · no on-screen text · eyes always open, always smiling · soundless dance clips]

**Duration:** about 0:32 (song ≈ 32 s, not attached; estimated) | **Total Scenes:** 16 = 16 reference images = 16 videos (8 timed scenes + 8 bonus dance scenes)
**Image generation:** Google Flow only (Step 1 sheets, Step 2 location plan, Step 3 scene reference images)
**Video generation:** Google Flow — one video prompt per scene, each generated as an 8 s clip (a 4 s song slot plus spare seconds to trim)
**Payoff:** The caterpillar becomes a gorgeous butterfly and soars into the sky while the children dance, ending with a joyful wave and "thank you".
**Dialogue/Audio rule:** The generated clips are SOUNDLESS action videos: no singing, no lip movement, no voices, no music and no sound effects. Your recorded song and music are added in the edit; every scene is timed to the song.

**Assumptions made for the blank input fields (change if needed):**
- **Style:** 3D animated family-film look with vibrant jewel colours, sparkle and glow. Tell me if you want 2D cartoon instead.
- **Characters:** the girl Oviya, the boy Vetri (two children who dance in every scene, added to carry the energy; tell me if you want insects only), the caterpillar Chinnu who becomes the butterfly Chitti, and an emerald chrysalis.
- **Hard rules:** no on-screen text or lyrics; nobody sings or speaks; eyes always wide open; everyone always smiling; soundless clips.
- **Song length:** estimated; the audio was not attached.

**Segment map**

| # | Segment | Scenes | Time |
|---|---|---|---|
| 1 | The caterpillar: crawl and eat | S001–S003 | 0:00–0:12 |
| 2 | Sleep in the chrysalis home and peep out | S004–S005 | 0:12–0:20 |
| 3 | The butterfly: spread the wings and fly | S006–S008 | 0:20–0:32 |
| 4 | Bonus energetic dance scenes (use anywhere in the edit) | S009–S016 | bonus (no timestamp) |

---

## ⚠️ GLOBAL LOCK BLOCK — append this in full to the END of every single prompt below (Step 1, every Step 3, every Step 4)

```
GLOBAL LOCK:
CONTINUITY — Keep Oviya (magenta frock, plait with a magenta ribbon and jasmine), Vetri (turquoise T-shirt, orange shorts), the caterpillar Chinnu (lime-green body with yellow stripes and orange spots, emerald eyes, golden antennae), the butterfly Chitti (the same emerald eyes, cheek blush and green-yellow striped body as Chinnu, with iridescent royal-blue and turquoise wings, gold veins and pink edges) and the emerald chrysalis in exact face, colour, clothing and proportion continuity from their saved reference sheets — no redesign, recolor or scale drift. Chinnu and Chitti are the same character before and after the change. Every scene takes place in its own different spot of the same magical garden world: lush gardens, flowers, ponds and meadows in warm light. Never copy the previous scene's spot, background or composition.
CAST RULE — Every scene shows exactly the girl Oviya, the boy Vetri and ONE hero insect: the caterpillar Chinnu in the caterpillar scenes, the butterfly Chitti in the butterfly scenes (the chrysalis appears only in the scenes that name it). No other people, animals or insects, apart from tiny ambient sparkles, pollen and fireflies.
STYLE — 3D animated family-film style, vibrant jewel colours, dreamy sparkle and soft glow, soft global illumination, a warm 35mm-lens depth of field, one consistent colour grade (fresh greens, sunny gold, jewel blues and pinks), smooth appealing character animation with natural squash and stretch, glittering gorgeous butterfly wings, and high-energy, bouncy dance moves that land exactly on the beat of an energetic, addictive children's song.
EYE RULE — The eyes of Oviya, Vetri, Chinnu and Chitti are wide open and fully visible in every single frame of every scene, from the first frame to the last: no blinking, no closing, no squinting, no winking, no sleeping, no half-closed or sleepy eyes, and no eyelid motion at all, even when smiling widely, laughing, cheering, spinning, landing, snuggling into the chrysalis or "sleeping". Faces stay bright, wide-eyed and expressive.
EYE DESIGN — To make blinking impossible, every character has big, glossy, perfectly round eyes with large highlights and eyelids that are permanently fixed open (like toy or doll eyes). The eyes have no visible eyelid movement, the pupils and highlights are always visible, and smiles never squeeze the eyes: a smile only lifts the cheeks and mouth corners while the eyes stay perfectly round.
AVOID — closed eyes, blinking, squinting, eyes shut, winking, half-closed eyelids, sleepy eyes, laughing squint, eyes closed in a smile, eyelids covering the pupils, eyes rolling back.
SMILE RULE — Everyone is smiling happily in every frame, with beaming, joyful faces and energetic body language.
MOUTH RULE — Nobody sings or speaks. Everyone keeps a happy closed-mouth smile, and the dance is carried by bodies, arms, legs, heads, antennae and wings.
HARD RULES — No on-screen text, captions, lyrics, logos or watermarks. Fully child-friendly: no scary, sad or dangerous content. Faces never morph between shots.
ZERO AI ARTIFACTS — No closed or blinking eyes, no morphing, warping, melting, flicker, extra or duplicated limbs, wings, antennae, legs or characters, floating debris other than the intended sparkles, texture smearing, distorted hands or feet, mismatched or misshapen wings.
LIGHTING — Follow the time of day and light written in each scene's prompt; no sudden unintended light jumps inside a shot.
AUDIO — The generated clip is SOUNDLESS: no sound effects, no music, no singing, no speech. (If Flow still adds a little ambience, mute it in the edit.) The recorded song and music are added in the edit.
CAMERA — Smooth, physically plausible motion only; each shot's opening camera motion matches the previous shot's closing motion vector for a seamless cut.
```

---

# STEP 1 — CHARACTER & PROP REFERENCE IMAGES (Google Flow — image generation ONLY)

### 1A. Girl ("Oviya")
**Portrait Image Prompt — Google Flow:**
Full-body portrait of a 7-year-old Tamil girl named Oviya standing in an energetic happy pose, facing the camera, with a clearly visible, fully expressive animated face: warm brown skin, rosy cheeks, big glossy round brown eyes with fixed-open eyelids, wide open, a huge bright smile with a closed mouth, a long black plait tied with a magenta ribbon and a small jasmine flower. A bright magenta frock with a gold border and white leggings, bare feet. 3D animated family-film style, vibrant jewel colours, dreamy sparkle and soft glow, soft global illumination. Neutral light-grey background, soft key light. Eyes wide open, never closed, no blinking, no squinting; no closed-eye expression anywhere on the sheet. Locked reference design.
**Save as:** `Oviya_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Oviya_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) with the eyes wide open in every panel (never closed, blinking or squinting), locking the face.
**Save as:** `Oviya_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S001–S016.

### 1B. Boy ("Vetri")
**Portrait Image Prompt — Google Flow:**
Full-body portrait of a 7-year-old Tamil boy named Vetri standing in an energetic happy pose, facing the camera, with a clearly visible, fully expressive animated face: warm brown skin, round cheeks, big glossy round dark eyes with fixed-open eyelids, wide open, short black hair with a small cowlick, a huge cheeky smile with a closed mouth. A turquoise T-shirt, orange shorts, bare feet. 3D animated family-film style, vibrant jewel colours, dreamy sparkle and soft glow, soft global illumination. Neutral light-grey background, soft key light. Eyes wide open, never closed, no blinking, no squinting; no closed-eye expression anywhere on the sheet. Locked reference design.
**Save as:** `Vetri_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Vetri_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) with the eyes wide open in every panel (never closed, blinking or squinting), locking the face.
**Save as:** `Vetri_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S001–S016.

### 1C. Caterpillar ("Chinnu")
**Portrait Image Prompt — Google Flow:**
A cute chubby caterpillar named Chinnu in a happy wiggling pose on a green leaf, with a clearly visible, fully expressive animated face: two big round glossy emerald-green eyes with highlights and fixed-open eyelids, wide open, rosy cheek blush, a bright smile with a closed mouth, two curly golden antennae. A plump segmented body in bright lime green with yellow stripes and small orange spots, tiny stubby feet, a faint soft glow. 3D animated family-film style, vibrant jewel colours, dreamy sparkle and soft glow, soft global illumination. Neutral light-grey background, soft key light. Eyes wide open, never closed, no blinking, no squinting; no closed-eye expression anywhere on the sheet. Locked reference design.
**Save as:** `Chinnu_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Chinnu_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) with the eyes wide open in every panel (never closed, blinking or squinting), locking the face.
**Save as:** `Chinnu_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S001–S004, S009–S012.

### 1D. Butterfly ("Chitti")
**Portrait Image Prompt — Google Flow:**
A gorgeous butterfly named Chitti hovering gracefully with wings open, with a clearly visible, fully expressive animated face: the same two big round glossy emerald-green eyes with highlights and fixed-open eyelids as the caterpillar Chinnu, wide open, the same rosy cheek blush, a bright smile with a closed mouth, two curly golden antennae. A slender body with lime-green and yellow stripes, and huge shimmering iridescent wings in royal blue and turquoise with gold veins, pink edges and tiny sparkling dots, a trail of golden sparkles. 3D animated family-film style, vibrant jewel colours, dreamy sparkle and soft glow, soft global illumination. Neutral light-grey background, soft key light. Eyes wide open, never closed, no blinking, no squinting; no closed-eye expression anywhere on the sheet. Locked reference design.
**Save as:** `Chitti_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Chitti_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) with the eyes wide open in every panel (never closed, blinking or squinting), locking the face.
**Save as:** `Chitti_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S005–S008, S013–S016.

### 1E. Chrysalis / Cosy Home (prop) ("Chrysalis")
**Portrait Image Prompt — Google Flow:**
A glowing emerald-green chrysalis hanging from a thin branch, glossy and smooth with tiny golden dots and a soft inner glow, a small translucent round window near the top through which a pair of bright wide-open eyes and golden antennae can just be seen, a soft sparkle around it. 3D animated family-film style, vibrant jewel colours, dreamy sparkle and soft glow, soft global illumination. Neutral light-grey background, soft key light. Locked reference design.
**Save as:** `Chrysalis_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Chrysalis_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up detail panels.
**Save as:** `Chrysalis_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S004–S005.

---

# STEP 2 — LOCATION PLAN (no reusable environment plates: every scene is a different spot of the same magical garden world)

There are no shared environment-plate images. Each scene's Step 3 prompt describes its own spot, and `Environment Reference Image` is `none`. All spots belong to the same bright garden world, so the look stays consistent. The table lists every spot so you can check none repeats.

| Scene | Time | Slot | Flow clip | Unique location |
|---|---|---|---|---|
| S001 | 0:00–0:04 | 4s | 8 s | A wildflower meadow at sunrise with dew-covered grass |
| S002 | 0:04–0:08 | 4s | 8 s | A banana-leaf garden corner with huge glossy green leaves |
| S003 | 0:08–0:12 | 4s | 8 s | A vegetable garden with rows of lettuce and cabbage |
| S004 | 0:12–0:16 | 4s | 8 s | A mango orchard under a branch at golden dusk with fireflies starting |
| S005 | 0:16–0:20 | 4s | 8 s | A hibiscus bush full of red flowers at sunrise |
| S006 | 0:20–0:24 | 4s | 8 s | A pond edge with pink lotus flowers and floating leaves |
| S007 | 0:24–0:28 | 4s | 8 s | An open hilltop meadow with fluffy clouds and a wide blue sky |
| S008 | 0:28–0:32 | 4s | 8 s | A garden archway of flowers with a rainbow behind and fireflies |
| S009 | bonus (no timestamp) | none | 8 s | A mushroom-and-fern forest floor |
| S010 | bonus (no timestamp) | none | 8 s | A sunflower field in bright noon light |
| S011 | bonus (no timestamp) | none | 8 s | A strawberry patch with a friendly scarecrow |
| S012 | bonus (no timestamp) | none | 8 s | A garden pond with stepping stones |
| S013 | bonus (no timestamp) | none | 8 s | A lavender field at golden hour |
| S014 | bonus (no timestamp) | none | 8 s | A glass greenhouse full of tropical flowers |
| S015 | bonus (no timestamp) | none | 8 s | A waterfall pool garden with rainbow mist |
| S016 | bonus (no timestamp) | none | 8 s | A cherry-blossom lane with falling petals |

---

# STEP 3 & STEP 4 — SCENES (song slots of 4 seconds; every Flow video is generated at 8 seconds; soundless, eyes always open, always smiling)

**How each scene is shaped:**
Header line (scene number, label, time range and slot) → **Song sync** (editor note only: the lyric words at that moment; they are not part of the Flow prompt) → Step 3 Ingredients → Step 3 Reference Image Prompt → Step 4 Ingredients → Video Prompt (Google Flow, generated at 8 s; second marks relative to the clip start; the dance beats first and spare seconds after) → Sound → Cut→.
The lyrics are NOT written inside the Flow prompts. Append the GLOBAL LOCK BLOCK to the end of every Step 3 and Step 4 prompt.

---

### Segment 1 — The caterpillar: crawl and eat (Scenes 1–3) | 0:00–0:12

**S001 — Crawl, crawl, caterpillar! | 0:00–0:04 (4s slot → generate 8s in Flow)**
Song sync: (0:00) "(இசை அறிமுகம்)" · (0:02) "Crawl, crawl, caterpillar"
Step 3 Ingredients: Character & Prop Reference Images: `Oviya_Portrait.png`, `Oviya_6Angle.png`, `Vetri_Portrait.png`, `Vetri_6Angle.png`, `Chinnu_Portrait.png`, `Chinnu_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A wildflower meadow at sunrise with dew-covered grass) · Scene Continuity Reference: none (first scene in the series)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide low shot in a wildflower meadow at sunrise with sparkling dew: the girl Oviya and the boy Vetri dancing joyfully with their arms up, big smiles and wide-open eyes, and the bright green caterpillar Chinnu crawling in front of them along a dew-covered stem with a happy wiggle, golden backlight and drifting pollen sparkles, 3D animated family-film style, vibrant jewel colours, dreamy sparkle and soft glow, soft global illumination.
Save as: `S001_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S001_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S001_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: the camera glides low through the flowers toward the caterpillar as the children bounce with energy and clap on the beat; 2–4s: Chinnu wiggles along the stem in a bouncy rhythm as Oviya and Vetri copy the wiggle with their hips and arms. 4–8s (spare 4s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, laughing, cheering, spinning or landing. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song and music are added in the edit)
Cut→S002: Cut to a banana-leaf garden.

**S002 — Crawl on a leaf | 0:04–0:08 (4s slot → generate 8s in Flow)**
Song sync: (0:04) "crawl on a leaf" · (0:07) "Eat…"
Step 3 Ingredients: Character & Prop Reference Images: `Oviya_Portrait.png`, `Oviya_6Angle.png`, `Vetri_Portrait.png`, `Vetri_6Angle.png`, `Chinnu_Portrait.png`, `Chinnu_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A banana-leaf garden corner with huge glossy green leaves) · Scene Continuity Reference: `S001_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Medium shot in a garden corner with huge glossy banana leaves: the caterpillar Chinnu crawling along the wide green leaf in the foreground with a big happy smile and wide-open eyes, and behind it the girl Oviya and the boy Vetri dancing and swaying with delighted faces, sunbeams through the leaves, 3D animated family-film style, vibrant jewel colours, dreamy sparkle and soft glow, soft global illumination.
Save as: `S002_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S002_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S002_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: Chinnu crawls along the leaf in a bouncy wave as the camera tracks beside it and the children sway on the beat; 2–4s: the children spin and clap in time while Chinnu crawls over the leaf's edge and wiggles. 4–8s (spare 4s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, laughing, cheering, spinning or landing. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song and music are added in the edit)
Cut→S003: Cut to a vegetable garden.

**S003 — Eat, eat, caterpillar: a green leaf | 0:08–0:12 (4s slot → generate 8s in Flow)**
Song sync: (0:07) "Eat, eat, caterpillar" · (0:09) "eat a green leaf"
Step 3 Ingredients: Character & Prop Reference Images: `Oviya_Portrait.png`, `Oviya_6Angle.png`, `Vetri_Portrait.png`, `Vetri_6Angle.png`, `Chinnu_Portrait.png`, `Chinnu_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A vegetable garden with rows of lettuce and cabbage) · Scene Continuity Reference: `S002_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Medium shot in a vegetable garden with rows of lettuce and cabbage in morning light: the caterpillar Chinnu nibbling the edge of a bright green lettuce leaf with a joyful smile and wide-open sparkling eyes, and the girl Oviya and the boy Vetri dancing beside it, rubbing their tummies and grinning, 3D animated family-film style, vibrant jewel colours, dreamy sparkle and soft glow, soft global illumination.
Save as: `S003_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S003_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S003_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: Chinnu munches the leaf edge in a bouncy rhythm as the children rub their tummies and bop to the beat; 2–4s: they hop and clap together as a green leaf crumb flips in the air and Chinnu wiggles with delight. 4–8s (spare 4s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, laughing, cheering, spinning or landing. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song and music are added in the edit)
Cut→S004: Cut to a mango orchard.

---

### Segment 2 — Sleep in the chrysalis home and peep out (Scenes 4–5) | 0:12–0:20

**S004 — Sleep, sleep: a cosy home | 0:12–0:16 (4s slot → generate 8s in Flow)**
Song sync: (0:12) "Sleep, sleep, caterpillar" · (0:14) "sleep in your home"
Step 3 Ingredients: Character & Prop Reference Images: `Oviya_Portrait.png`, `Oviya_6Angle.png`, `Vetri_Portrait.png`, `Vetri_6Angle.png`, `Chinnu_Portrait.png`, `Chinnu_6Angle.png`, `Chrysalis_Portrait.png`, `Chrysalis_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A mango orchard under a branch at golden dusk with fireflies starting) · Scene Continuity Reference: `S003_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Medium shot in a mango orchard at golden dusk with the first fireflies: the caterpillar Chinnu on a low branch spinning a glowing emerald chrysalis around itself, smiling with wide-open sparkling eyes still visible, and the girl Oviya and the boy Vetri below swaying slowly side to side with their arms up and round-eyed smiles, warm glow on their faces, 3D animated family-film style, vibrant jewel colours, dreamy sparkle and soft glow, soft global illumination.
Save as: `S004_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S004_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S004_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: Chinnu curls up and the emerald chrysalis forms around it with a soft glow and sparkles, its smiling face and open eyes visible through the shiny shell; 2–4s: the children sway gently in a calm swaying dance, round-eyed and smiling, as the chrysalis glows brighter and settles. 4–8s (spare 4s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, laughing, cheering, spinning or landing. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song and music are added in the edit)
Cut→S005: Cut to a hibiscus bush at sunrise.

**S005 — Peep, peep: the chrysalis cracks | 0:16–0:20 (4s slot → generate 8s in Flow)**
Song sync: (0:16) "Peep, peep, butterfly" · (0:19) "peep out and smile"
Step 3 Ingredients: Character & Prop Reference Images: `Oviya_Portrait.png`, `Oviya_6Angle.png`, `Vetri_Portrait.png`, `Vetri_6Angle.png`, `Chitti_Portrait.png`, `Chitti_6Angle.png`, `Chrysalis_Portrait.png`, `Chrysalis_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A hibiscus bush full of red flowers at sunrise) · Scene Continuity Reference: `S004_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Medium shot at a hibiscus bush full of red flowers at sunrise: a glowing emerald chrysalis hanging from a branch with a small crack and the butterfly Chitti's bright eyes and antennae peeping out with a happy smile, and the girl Oviya and the boy Vetri crouching close with wide-open excited eyes and delighted smiles, rays of sunlight and sparkles, 3D animated family-film style, vibrant jewel colours, dreamy sparkle and soft glow, soft global illumination.
Save as: `S005_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S005_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S005_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: the crack widens as Chitti peeps out with bright wide eyes and wiggling antennae while the children bounce on their toes in excitement; 2–4s: Chitti peeks out further and the children react with joy and clap with round wide eyes on the beat as sparkles flutter. 4–8s (spare 4s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, laughing, cheering, spinning or landing. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song and music are added in the edit)
Cut→S006: Cut to a lotus pond.

---

### Segment 3 — The butterfly: spread the wings and fly (Scenes 6–8) | 0:20–0:32

**S006 — Peep out and smile: spreading the wings | 0:20–0:24 (4s slot → generate 8s in Flow)**
Song sync: (0:19) "peep out and smile" · (0:21) "Fly, fly, butterfly"
Step 3 Ingredients: Character & Prop Reference Images: `Oviya_Portrait.png`, `Oviya_6Angle.png`, `Vetri_Portrait.png`, `Vetri_6Angle.png`, `Chitti_Portrait.png`, `Chitti_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A pond edge with pink lotus flowers and floating leaves) · Scene Continuity Reference: `S005_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Medium shot at a pond edge with pink lotus flowers and floating leaves: the gorgeous butterfly Chitti with shimmering royal-blue and gold wings opening for the first time on a lotus bud, a huge sparkling smile and wide-open eyes, and the girl Oviya and the boy Vetri dancing joyfully on the bank with their arms up, golden reflections on the water, 3D animated family-film style, vibrant jewel colours, dreamy sparkle and soft glow, soft global illumination.
Save as: `S006_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S006_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S006_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: Chitti spreads its wings wide with a shower of golden sparkles as the children throw their arms up in celebration with round wide eyes; 2–4s: Chitti flutters up in a spin while the children spin on the bank on the beat. 4–8s (spare 4s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, laughing, cheering, spinning or landing. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song and music are added in the edit)
Cut→S007: Cut to a hilltop meadow.

**S007 — Fly, fly, butterfly: soaring | 0:24–0:28 (4s slot → generate 8s in Flow)**
Song sync: (0:24) "fly in the sky" · (0:27) "(இசை இடைவெளி)"
Step 3 Ingredients: Character & Prop Reference Images: `Oviya_Portrait.png`, `Oviya_6Angle.png`, `Vetri_Portrait.png`, `Vetri_6Angle.png`, `Chitti_Portrait.png`, `Chitti_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: An open hilltop meadow with fluffy clouds and a wide blue sky) · Scene Continuity Reference: `S006_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide low-angle shot on an open hilltop meadow with a wide blue sky and fluffy clouds: the butterfly Chitti soaring high with glittering blue-and-gold wings and a huge smile and wide-open eyes, and the girl Oviya and the boy Vetri running and dancing below with their arms spread like wings, big smiles, 3D animated family-film style, vibrant jewel colours, dreamy sparkle and soft glow, soft global illumination.
Save as: `S007_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S007_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S007_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: Chitti swoops across the sky in a graceful loop as the children run with their arms spread; 2–4s: they spin and jump as Chitti spirals up through the clouds with a trail of golden sparkles. 4–8s (spare 4s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, laughing, cheering, spinning or landing. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song and music are added in the edit)
Cut→S008: Cut to the flower archway.

**S008 — Thank you: the happy finale | 0:28–0:32 (4s slot → generate 8s in Flow)**
Song sync: (0:30) "Thank you." · (0:31) "(இசை முடிவு; ஆடியோ நீளம் மதிப்பீடு)"
Step 3 Ingredients: Character & Prop Reference Images: `Oviya_Portrait.png`, `Oviya_6Angle.png`, `Vetri_Portrait.png`, `Vetri_6Angle.png`, `Chitti_Portrait.png`, `Chitti_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A garden archway of flowers with a rainbow behind and fireflies) · Scene Continuity Reference: `S007_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot at a garden archway of colourful flowers with a rainbow behind it and glowing fireflies: the girl Oviya and the boy Vetri waving with big smiles and wide-open eyes, and the butterfly Chitti hovering between them with its glittering wings spread, golden sunset glow, 3D animated family-film style, vibrant jewel colours, dreamy sparkle and soft glow, soft global illumination.
Save as: `S008_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S008_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S008_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: the children dance a bouncy final step and Chitti flutters in a loop above them; 2–4s: they wave and strike a happy final pose with Chitti landing gently on Oviya's raised hand as the sparkles fade. 4–8s (spare 4s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, laughing, cheering, spinning or landing. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song and music are added in the edit)
Cut→S009: END: fade out over the last second.

---

### Segment 4 — Bonus energetic dance scenes (use anywhere in the edit) (Scenes 9–16)

**S009 — Bonus 1: caterpillar conga | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free energetic cutaway scene: cut it in over any part of the song.
Step 3 Ingredients: Character & Prop Reference Images: `Oviya_Portrait.png`, `Oviya_6Angle.png`, `Vetri_Portrait.png`, `Vetri_6Angle.png`, `Chinnu_Portrait.png`, `Chinnu_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A mushroom-and-fern forest floor) · Scene Continuity Reference: `S008_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot at a mushroom-and-fern forest floor with glowing toadstools: the girl Oviya and the boy Vetri with huge smiles and wide-open eyes in a playful start pose, and the caterpillar Chinnu right beside them, 3D animated family-film style, vibrant jewel colours, dreamy sparkle and soft glow, soft global illumination.
Save as: `S009_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S009_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S009_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: the children start an energetic dance to a bouncy beat, dancing a bouncy conga line, the caterpillar wiggling at the front and the children copying with hip bumps and arm waves; 3–6s: they repeat the move with a bigger jump and spin, grinning at each other with round wide eyes in time with the beat; 6–8s: the camera circles them as they strike a joyful pose and the movement settles. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, laughing, cheering, spinning or landing. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song and music are added in the edit)
Cut→S010: Use as a cutaway or loop anywhere in the edit.

**S010 — Bonus 2: leaf-hop party | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free energetic cutaway scene: cut it in over any part of the song.
Step 3 Ingredients: Character & Prop Reference Images: `Oviya_Portrait.png`, `Oviya_6Angle.png`, `Vetri_Portrait.png`, `Vetri_6Angle.png`, `Chinnu_Portrait.png`, `Chinnu_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A sunflower field in bright noon light) · Scene Continuity Reference: `S009_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot at a sunflower field in bright noon light: the girl Oviya and the boy Vetri with huge smiles and wide-open eyes in a playful start pose, and the caterpillar Chinnu right beside them, 3D animated family-film style, vibrant jewel colours, dreamy sparkle and soft glow, soft global illumination.
Save as: `S010_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S010_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S010_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: the children start an energetic dance to a bouncy beat, hopping over big green leaves in rhythm while the caterpillar crawls in a bouncy wave beside them; 3–6s: they repeat the move with a bigger jump and spin, grinning at each other with round wide eyes in time with the beat; 6–8s: the camera circles them as they strike a joyful pose and the movement settles. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, laughing, cheering, spinning or landing. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song and music are added in the edit)
Cut→S011: Use as a cutaway or loop anywhere in the edit.

**S011 — Bonus 3: munch and groove | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free energetic cutaway scene: cut it in over any part of the song.
Step 3 Ingredients: Character & Prop Reference Images: `Oviya_Portrait.png`, `Oviya_6Angle.png`, `Vetri_Portrait.png`, `Vetri_6Angle.png`, `Chinnu_Portrait.png`, `Chinnu_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A strawberry patch with a friendly scarecrow) · Scene Continuity Reference: `S010_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot at a strawberry patch with a friendly scarecrow: the girl Oviya and the boy Vetri with huge smiles and wide-open eyes in a playful start pose, and the caterpillar Chinnu right beside them, 3D animated family-film style, vibrant jewel colours, dreamy sparkle and soft glow, soft global illumination.
Save as: `S011_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S011_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S011_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: the children start an energetic dance to a bouncy beat, grooving side to side while the caterpillar munches a leaf in rhythm, and clapping on every munch; 3–6s: they repeat the move with a bigger jump and spin, grinning at each other with round wide eyes in time with the beat; 6–8s: the camera circles them as they strike a joyful pose and the movement settles. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, laughing, cheering, spinning or landing. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song and music are added in the edit)
Cut→S012: Use as a cutaway or loop anywhere in the edit.

**S012 — Bonus 4: stepping-stone shimmy | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free energetic cutaway scene: cut it in over any part of the song.
Step 3 Ingredients: Character & Prop Reference Images: `Oviya_Portrait.png`, `Oviya_6Angle.png`, `Vetri_Portrait.png`, `Vetri_6Angle.png`, `Chinnu_Portrait.png`, `Chinnu_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A garden pond with stepping stones) · Scene Continuity Reference: `S011_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot at a garden pond with stepping stones and water lilies: the girl Oviya and the boy Vetri with huge smiles and wide-open eyes in a playful start pose, and the caterpillar Chinnu right beside them, 3D animated family-film style, vibrant jewel colours, dreamy sparkle and soft glow, soft global illumination.
Save as: `S012_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S012_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S012_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: the children start an energetic dance to a bouncy beat, shimmying across the stepping stones as the caterpillar wiggles along a lily-pad path beside them; 3–6s: they repeat the move with a bigger jump and spin, grinning at each other with round wide eyes in time with the beat; 6–8s: the camera circles them as they strike a joyful pose and the movement settles. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, laughing, cheering, spinning or landing. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song and music are added in the edit)
Cut→S013: Use as a cutaway or loop anywhere in the edit.

**S013 — Bonus 5: lavender twirl | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free energetic cutaway scene: cut it in over any part of the song.
Step 3 Ingredients: Character & Prop Reference Images: `Oviya_Portrait.png`, `Oviya_6Angle.png`, `Vetri_Portrait.png`, `Vetri_6Angle.png`, `Chitti_Portrait.png`, `Chitti_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A lavender field at golden hour) · Scene Continuity Reference: `S012_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot at a lavender field at golden hour: the girl Oviya and the boy Vetri with huge smiles and wide-open eyes in a playful start pose, and the butterfly Chitti right beside them, 3D animated family-film style, vibrant jewel colours, dreamy sparkle and soft glow, soft global illumination.
Save as: `S013_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S013_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S013_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: the children start an energetic dance to a bouncy beat, twirling with their arms out among the flowers as the butterfly spirals around them; 3–6s: they repeat the move with a bigger jump and spin, grinning at each other with round wide eyes in time with the beat; 6–8s: the camera circles them as they strike a joyful pose and the movement settles. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, laughing, cheering, spinning or landing. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song and music are added in the edit)
Cut→S014: Use as a cutaway or loop anywhere in the edit.

**S014 — Bonus 6: greenhouse flutter dance | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free energetic cutaway scene: cut it in over any part of the song.
Step 3 Ingredients: Character & Prop Reference Images: `Oviya_Portrait.png`, `Oviya_6Angle.png`, `Vetri_Portrait.png`, `Vetri_6Angle.png`, `Chitti_Portrait.png`, `Chitti_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A glass greenhouse full of tropical flowers) · Scene Continuity Reference: `S013_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot at a glass greenhouse full of tropical flowers with sunbeams: the girl Oviya and the boy Vetri with huge smiles and wide-open eyes in a playful start pose, and the butterfly Chitti right beside them, 3D animated family-film style, vibrant jewel colours, dreamy sparkle and soft glow, soft global illumination.
Save as: `S014_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S014_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S014_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: the children start an energetic dance to a bouncy beat, flapping their arms like wings in a flutter dance while the butterfly flutters in time above them; 3–6s: they repeat the move with a bigger jump and spin, grinning at each other with round wide eyes in time with the beat; 6–8s: the camera circles them as they strike a joyful pose and the movement settles. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, laughing, cheering, spinning or landing. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song and music are added in the edit)
Cut→S015: Use as a cutaway or loop anywhere in the edit.

**S015 — Bonus 7: rainbow splash | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free energetic cutaway scene: cut it in over any part of the song.
Step 3 Ingredients: Character & Prop Reference Images: `Oviya_Portrait.png`, `Oviya_6Angle.png`, `Vetri_Portrait.png`, `Vetri_6Angle.png`, `Chitti_Portrait.png`, `Chitti_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A waterfall pool garden with rainbow mist) · Scene Continuity Reference: `S014_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot at a waterfall pool garden with rainbow mist: the girl Oviya and the boy Vetri with huge smiles and wide-open eyes in a playful start pose, and the butterfly Chitti right beside them, 3D animated family-film style, vibrant jewel colours, dreamy sparkle and soft glow, soft global illumination.
Save as: `S015_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S015_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S015_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: the children start an energetic dance to a bouncy beat, splashing and jumping in the shallow pool in rhythm as the butterfly dances through the rainbow mist; 3–6s: they repeat the move with a bigger jump and spin, grinning at each other with round wide eyes in time with the beat; 6–8s: the camera circles them as they strike a joyful pose and the movement settles. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, laughing, cheering, spinning or landing. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song and music are added in the edit)
Cut→S016: Use as a cutaway or loop anywhere in the edit.

**S016 — Bonus 8: blossom shower | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free energetic cutaway scene: cut it in over any part of the song.
Step 3 Ingredients: Character & Prop Reference Images: `Oviya_Portrait.png`, `Oviya_6Angle.png`, `Vetri_Portrait.png`, `Vetri_6Angle.png`, `Chitti_Portrait.png`, `Chitti_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A cherry-blossom lane with falling petals) · Scene Continuity Reference: `S015_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot at a cherry-blossom lane with falling pink petals: the girl Oviya and the boy Vetri with huge smiles and wide-open eyes in a playful start pose, and the butterfly Chitti right beside them, 3D animated family-film style, vibrant jewel colours, dreamy sparkle and soft glow, soft global illumination.
Save as: `S016_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S016_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S016_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: the children start an energetic dance to a bouncy beat, dancing and spinning as pink petals fall around them while the butterfly glides in loops overhead; 3–6s: they repeat the move with a bigger jump and spin, grinning at each other with round wide eyes in time with the beat; 6–8s: the camera circles them as they strike a joyful pose and the movement settles. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, laughing, cheering, spinning or landing. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices.
Sound: none (a soundless clip; your song and music are added in the edit)
Cut→Use as a cutaway or loop anywhere in the edit.

---

# PRODUCTION NOTES

- **Total required:** 16 reference images (`S001_Ref.png` … `S016_Ref.png`) and 16 videos, one video per image: 8 timed scenes that follow the song plus 8 bonus dance scenes. Plus the Step 1 sheets: the girl, the boy, the caterpillar, the butterfly and the chrysalis, 5 portraits and 5 six-angle turnarounds (10 images). There are no environment-plate images. Overall: 16 scene images + 10 sheet images = 26 images, and 16 videos.
- **Song length:** your last timestamp is "Thank you" at 0:30, and no audio file was attached, so I assumed the song ends around 0:32 and made the timed scenes 32 s long (0:00–0:32). Send the audio length if it differs and I will adjust the last scene.
- **Song structure (from your timestamps):** 0:00–0:02 intro; 0:02 "Crawl, crawl, caterpillar, crawl on a leaf"; 0:07 "Eat, eat, caterpillar, eat a green leaf"; 0:12 "Sleep, sleep, caterpillar, sleep in your home"; 0:16 "Peep, peep, butterfly, peep out and smile"; 0:21 "Fly, fly, butterfly, fly in the sky"; 0:27–0:30 music; 0:30 "Thank you". Clips use even seconds, so a few lines start 1 s into a clip; every clip has spare footage, so you can nudge a clip by a second to land a move exactly on a beat.
- **Story:** the caterpillar Chinnu crawls and eats, curls up in a glowing emerald chrysalis ("your home") and comes out as the gorgeous butterfly Chitti, who spreads her wings and flies. Chinnu and Chitti share the same eyes, cheek blush and green-yellow stripes, so Flow keeps them recognisable as one character. The two children dance beside the hero in every scene to carry the energy.
- **Eyes open, always smiling (strengthened):** the lock block has an EYE RULE, an EYE DESIGN line (big glossy round eyes with eyelids fixed open, like toy eyes, so there is nothing to blink with) and an AVOID list (closed eyes, blinking, squinting, winking, sleepy eyes). Every video prompt now says the eyes are open from the first frame to the last right at the start of the prompt and again at the end with the same AVOID list; every reference-image prompt starts with "All eyes wide open and fully visible"; and every sheet asks for fixed-open eyelids. Words that make video models squeeze or close eyes were reworded ("gasp", "cheer", "lullaby", "grinning" now carry "round wide eyes"; smiles lift only the cheeks and mouth). The "sleep" line is shown with the caterpillar snuggling into the glowing chrysalis, its smiling face and open eyes visible through a small window. If Flow still blinks in a clip: (1) use another take, because blinks are random; (2) use only the first 4 s of the clip, since blinks mostly happen later in an 8 s clip; (3) regenerate from a scene image where the eyes are clearly open and round; (4) as a last resort, trim the clip just before the blink and cover the cut with a spare-footage cross-dissolve.
- **Cast rule:** every scene shows the two children plus one hero insect: the caterpillar in S001–S004 and bonus S009–S012, the butterfly in S005–S008 and bonus S013–S016, and the chrysalis only in S004–S005 and where the prompt names it.
- **What to generate in Flow (8 s or 10 s only):** every video is generated at 8 s. All timed slots are 4 s, so each clip has 4 s of spare footage after the dance beats. The bonus scenes are 8 s. No scene needs 10 s.

| Generate in Flow | Number of videos | Footage | Scenes |
|---|---|---|---|
| 8 s | 16 | 128 s | all scenes S001–S016 |

- **Slot plan (timed scenes):** 4 s slots: S001–S008 (8 clips, 32 s); total 32 s.
- **Timeline rule:** put the song on the timeline at 0:00, drop each timed clip at its scene start time and trim it to its slot. The extra seconds are spare footage. The bonus scenes have no timestamp: use them as cutaways, or loop the song to make a longer video.
- **Making it energetic and addictive:** fast bouncy dances on every beat (conga lines, leaf hops, stepping-stone shimmies, flutter dances), bright jewel colours, sparkles and glitter on the wings, a quick visual change every 4 s, and a clear transformation story that builds to the soaring butterfly and the final wave.
- **Audio:** generated clips are soundless: no singing, voices, music or sound effects. Your recorded song and music are added in the edit.
- **Image generation is Google Flow only.** Generate the 5 sheets first, then each scene image in order. Video prompts use each scene's saved image as the starting frame.
- **Reminder:** the GLOBAL LOCK BLOCK must be appended in full to the end of every prompt (Step 1, every Step 3 and every Step 4) before submission.
