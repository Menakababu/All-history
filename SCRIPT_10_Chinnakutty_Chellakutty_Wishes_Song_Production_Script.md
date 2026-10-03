# SCRIPT 10 — Chinnakutty Chellakutty: five wishes, a dancing song for children
### [TEMPLATE v3 — Google Flow only · song slots of 4/6 s, Flow clips generated at 8 s · character, animal and prop sheets → a different spot per scene → per-scene reference image → per-scene video · global lock appended to every prompt · no on-screen text · eyes always open, always smiling · soundless dance clips]

**Duration:** about 0:46 (the last line starts at 0:41; no audio file was attached, so the end is estimated; see notes) | **Total Scenes:** 18 = 18 reference images = 18 videos (10 timed scenes + 8 bonus dance scenes)
**Image generation:** Google Flow only (Step 1 sheets, Step 2 location plan, Step 3 scene reference images)
**Video generation:** Google Flow — one video prompt per scene, each generated as an 8 s clip (a 4 s or 6 s song slot plus spare seconds to trim)
**Payoff:** Paati asks little Kutty five times what she wants; Kutty wishes to visit an ant's house, sleep in a sparrow's nest, sail a paper boat, ride a butterfly, and finally to have a loving friend, and ends dancing with her friend Thenu and all her animal friends.
**Dialogue/Audio rule:** The generated clips are SOUNDLESS action videos: no singing, no lip movement, no voices, no music and no sound effects. Your recorded song is added in the edit; every scene is timed to the song.

**Assumptions made for the blank input fields (change if needed):**
- **Style:** 3D animated family-film look with vibrant colours, sparkle and glow. Tell me if you want 2D cartoon instead.
- **Characters:** Kutty (a little girl), her loving grandmother Paati, the friend Thenu (a boy), a family of ants, a mother sparrow with three chicks, a big paper boat and a giant butterfly. Kutty is shown tiny for the ant house and the nest. Tell me if Kutty should be a boy.
- **Hard rules:** no on-screen text or lyrics; nobody sings or speaks; eyes always wide open; everyone always smiling; soundless clips.

**Segment map**

| # | Segment | Scenes | Time |
|---|---|---|---|
| 1 | Intro: Kutty dances into the story | S001 | 0:00–0:06 |
| 2 | Wish 1: go into the ant's house | S002–S003 | 0:06–0:14 |
| 3 | Wish 2: sleep in the sparrow's nest | S004–S005 | 0:14–0:22 |
| 4 | Wish 3: sail a paper boat | S006–S007 | 0:22–0:30 |
| 5 | Wish 4: ride a butterfly | S008 | 0:30–0:36 |
| 6 | Wish 5: a loving friend | S009–S010 | 0:36–0:46 |
| 7 | Bonus dance scenes (use anywhere in the edit) | S011–S018 | bonus (no timestamp) |

---

## ⚠️ GLOBAL LOCK BLOCK — append this in full to the END of every single prompt below (Step 1, every Step 3, every Step 4)

```
GLOBAL LOCK:
CONTINUITY — Keep Kutty (a 5-year-old Tamil girl: warm brown skin, rosy cheeks, two high pigtails with red ribbons, a bright yellow frock with tiny white flowers, red bangles), Paati (her grandmother: silver hair in a bun with a jasmine garland, round gold-rimmed glasses, a maroon saree with a gold border), Thenu (a 5-year-old Tamil boy: short curly black hair, green shirt, white shorts), the ant family (a mother ant with a tiny golden crown), the mother sparrow with three golden chicks, the big white paper boat with a red flag and the giant orange-turquoise-pink butterfly in exact face, colour, clothing and proportion continuity from their saved reference sheets — no redesign, recolor or scale drift. Every scene takes place in its own different spot of the same warm storybook Tamil village and its gardens, ponds and skies. Never copy the previous scene's spot, background or composition.
CAST RULE — Every scene shows Kutty. Paati appears in the "asking" scenes; the ants, the sparrow family, the paper boat, the butterfly and Thenu appear in the scene that matches their line of the song. Only the characters named in a scene appear in it. No other people.
STYLE — 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination. A warm 35mm-lens depth of field, one consistent colour grade (golden light, fresh greens, jewel colours), smooth appealing character animation with natural squash and stretch, and energetic, bouncy dance moves that land on the beat of a happy children's song.
EYE RULE — Everyone's eyes (Kutty's, Paati's, Thenu's and all the animals') are wide open and fully visible in every single frame of every scene, from the first frame to the last: no blinking, no closing, no squinting, no winking, no sleeping, no half-closed or sleepy eyes, and no eyelid motion at all, even when smiling widely, spinning, or snuggling in the sparrow's nest.
EYE DESIGN — To make blinking impossible, every character has big, glossy, perfectly round eyes with large highlights and eyelids that are permanently fixed open (like toy or doll eyes); a smile only lifts the cheeks and mouth corners while the eyes stay perfectly round.
AVOID — closed eyes, blinking, squinting, eyes shut, winking, half-closed eyelids, sleepy eyes, laughing squint, eyes closed in a smile, eyelids covering the pupils, eyes rolling back.
SMILE RULE — Everyone is smiling happily in every frame, with joyful faces and energetic body language.
MOUTH RULE — Nobody sings or speaks. Everyone keeps a happy closed-mouth smile (beaks closed); Paati's asking is shown with her tilted head and open hands, and the dance is carried by bodies, arms, legs and heads.
SAFETY RULE — Kutty is shown tiny only in the ant, nest and leaf scenes and always safe and happy; she rides the butterfly only a little above the flowers, hugging it, with her smile on. Nothing scary, sad or dangerous.
HARD RULES — No on-screen text, captions, lyrics, logos or watermarks. Faces never morph between shots.
ZERO AI ARTIFACTS — No closed or blinking eyes, no morphing, warping, melting, flicker, extra or duplicated limbs, wings, legs or characters, floating debris other than the intended sparkles and petals, texture smearing, distorted hands or feet.
LIGHTING — Follow the time of day and light written in each scene's prompt; no sudden unintended light jumps inside a shot.
AUDIO — The generated clip is SOUNDLESS: no sound effects, no music, no singing, no speech. (If Flow still adds a little ambience, mute it in the edit.) The recorded song is added in the edit.
CAMERA — Smooth, physically plausible motion only; each shot's opening camera motion matches the previous shot's closing motion vector for a seamless cut.
```

---

# STEP 1 — CHARACTER, ANIMAL & PROP REFERENCE IMAGES (Google Flow — image generation ONLY)

### 1A. Kutty, the little darling ("Kutty")
**Portrait Image Prompt — Google Flow:**
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Full-body portrait of a 5-year-old Tamil girl named Kutty standing in an energetic happy pose with her arms wide, facing the camera, with a clearly visible, fully expressive animated face: warm brown skin, rosy cheeks, two high pigtails tied with red ribbons, huge sparkling dark eyes wide open, a huge bright smile with a closed mouth. She wears a bright yellow frock with tiny white flowers, red bangles and bare feet. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination. Neutral light-grey background, soft key light. Locked reference design.
**Save as:** `Kutty_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Kutty_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) with big round glossy eyes wide open and fixed-open eyelids in every panel, locking the face.
**Save as:** `Kutty_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S001–S018.

### 1B. Paati, the loving grandmother ("Paati")
**Portrait Image Prompt — Google Flow:**
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Full-body portrait of Paati, a loving Tamil grandmother in her 60s standing in a warm happy pose with open arms, facing the camera, with a clearly visible, fully expressive animated face: warm brown skin, a kind round face with gentle smile lines, silver hair in a bun with a jasmine garland, round gold-rimmed glasses, big warm dark eyes wide open, a bright smile with a closed mouth. She wears a maroon cotton saree with a gold border and a small red bindi. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination. Neutral light-grey background, soft key light. Locked reference design.
**Save as:** `Paati_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Paati_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) with big round glossy eyes wide open and fixed-open eyelids in every panel, locking the face.
**Save as:** `Paati_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S001–S002, S004, S006, S008–S010, S014, S017.

### 1C. Thenu, the loving friend ("Thenu")
**Portrait Image Prompt — Google Flow:**
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Full-body portrait of a 5-year-old Tamil boy named Thenu standing in an energetic happy pose with his arms wide, facing the camera, with a clearly visible, fully expressive animated face: warm brown skin, round cheeks, short curly black hair, huge sparkling dark eyes wide open, a huge bright smile with a closed mouth. He wears a green shirt, white shorts, a tiny blue wristband and bare feet. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination. Neutral light-grey background, soft key light. Locked reference design.
**Save as:** `Thenu_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Thenu_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) with big round glossy eyes wide open and fixed-open eyelids in every panel, locking the face.
**Save as:** `Thenu_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S010–S011, S016–S018.

### 1D. The friendly ant family ("Ants")
**Portrait Image Prompt — Google Flow:**
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. A group portrait of a friendly ant family standing upright on two legs: a round-bodied red-brown mother ant with a tiny golden crown, a dad ant and three small ant children, all with big glossy round eyes wide open, bright closed-mouth smiles and cute faces, waving their little arms. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination. Neutral light-grey background, soft key light. Locked reference design.
**Save as:** `Ants_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Ants_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) with big round glossy eyes wide open and fixed-open eyelids in every panel, locking the face.
**Save as:** `Ants_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S003, S010, S012, S018.

### 1E. The mother sparrow and her chicks ("Sparrow")
**Portrait Image Prompt — Google Flow:**
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. A portrait of a round brown-and-cream mother sparrow with a black bib and an orange beak (closed) standing on a branch, with three fluffy golden chicks beside her, all with fully expressive animated faces, big shiny round black eyes wide open and happy expressions. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination. Neutral light-grey background, soft key light. Locked reference design.
**Save as:** `Sparrow_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Sparrow_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) with big round glossy eyes wide open and fixed-open eyelids in every panel, locking the face.
**Save as:** `Sparrow_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S005, S010, S013, S018.

### 1F. The big paper boat (prop) ("Boat")
**Portrait Image Prompt — Google Flow:**
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. A big white folded paper boat, large enough for a child to sit in, with crisp sharp folds and a small bright red paper flag on top, floating on calm blue water with a few lily pads and a warm glow. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination. Neutral light-grey background, soft key light. Locked reference design.
**Save as:** `Boat_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Boat_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up detail panels of the folds.
**Save as:** `Boat_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S007.

### 1G. The giant friendly butterfly ("Butterfly")
**Portrait Image Prompt — Google Flow:**
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. A giant friendly butterfly with big orange, turquoise and pink wings edged in gold, a soft fuzzy golden body, long curly antennae, big glossy round eyes wide open and a gentle smile, wings spread wide, with a sparkle trail. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination. Neutral light-grey background, soft key light. Locked reference design.
**Save as:** `Butterfly_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Butterfly_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) with big round glossy eyes wide open and fixed-open eyelids in every panel, locking the face.
**Save as:** `Butterfly_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S008, S010, S015, S018.

---

# STEP 2 — LOCATION PLAN (no reusable environment plates: every scene is a different spot of the same storybook village)

There are no shared environment-plate images. Each scene's Step 3 prompt describes its own spot, and `Environment Reference Image` is `none`. The table lists every spot so you can check none repeats.

| Scene | Time | Slot | Flow clip | Unique location |
|---|---|---|---|---|
| S001 | 0:00–0:06 | 6s | 8 s | A sunlit village courtyard with a colourful kolam and a clay-pot tulsi plant |
| S002 | 0:06–0:10 | 4s | 8 s | A wooden veranda swing with hanging brass lanterns |
| S003 | 0:10–0:14 | 4s | 8 s | A giant ant hill among towering grass blades and flowers in a garden |
| S004 | 0:14–0:18 | 4s | 8 s | A shady spot under a neem tree with a rope cot |
| S005 | 0:18–0:22 | 4s | 8 s | A cosy woven sparrow nest high in a banyan tree branch |
| S006 | 0:22–0:26 | 4s | 8 s | A rain-washed house window ledge with clay-tile eaves |
| S007 | 0:26–0:30 | 4s | 8 s | A clear lily pond with dragonflies at the edge of a village |
| S008 | 0:30–0:36 | 6s | 8 s | A meadow of tall sunflowers with a hill path |
| S009 | 0:36–0:40 | 4s | 8 s | A lamp-lit living room with a rocking chair and a window of fireflies |
| S010 | 0:40–0:46 | 6s | 8 s | A grassy hilltop at sunset with fireflies and a banyan tree |
| S011 | bonus (no timestamp) | none | 8 s | A sunny rooftop terrace with colourful kites on strings |
| S012 | bonus (no timestamp) | none | 8 s | A giant green leaf stage in a dewy garden |
| S013 | bonus (no timestamp) | none | 8 s | A flowering mango-tree branch in spring |
| S014 | bonus (no timestamp) | none | 8 s | A rainy village lane with puddles and colourful umbrellas |
| S015 | bonus (no timestamp) | none | 8 s | A rainbow flower garden with arched trellises |
| S016 | bonus (no timestamp) | none | 8 s | A colourful village schoolyard with a big tamarind tree |
| S017 | bonus (no timestamp) | none | 8 s | A village festival stage with strings of lights |
| S018 | bonus (no timestamp) | none | 8 s | A moonlit meadow full of fireflies |

---

# STEP 3 & STEP 4 — SCENES (song slots of 4 and 6 seconds; every Flow video is generated at 8 seconds; soundless, eyes always open, always smiling)

**How each scene is shaped:**
Header line (scene number, label, time range and slot) → **Song sync** (editor note only: the lyric words; they are not part of the Flow prompt) → Step 3 Ingredients → Step 3 Reference Image Prompt → Step 4 Ingredients → Video Prompt (Google Flow, generated at 8 s; second marks relative to the clip start; the dance beats first and spare seconds after) → Sound → Cut→.
The lyrics are NOT written inside the Flow prompts. Append the GLOBAL LOCK BLOCK to the end of every Step 3 and Step 4 prompt.

---

### Segment 1 — Intro: Kutty dances into the story (Scenes 1–1) | 0:00–0:06

**S001 — Kutty twirls into the story | 0:00–0:06 (6s slot → generate 8s in Flow)**
Song sync: (0:00) "(இசை அறிமுகம்)"
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Kutty_Portrait.png`, `Kutty_6Angle.png`, `Paati_Portrait.png`, `Paati_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A sunlit village courtyard with a colourful kolam and a clay-pot tulsi plant) · Scene Continuity Reference: none (first scene in the series)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot in a sunlit village courtyard at morning with a bright rice-flour kolam and floating sparkles: Kutty (a 5-year-old Tamil girl with warm brown skin, rosy cheeks, two high pigtails with red ribbons, a bright yellow frock with tiny white flowers and red bangles) twirling with her arms wide and a huge smile, and Paati (her loving grandmother with silver hair in a bun with a jasmine garland, a kind round face, round gold-rimmed glasses and a maroon cotton saree with a gold border) sitting on a wooden stool beside her clapping with a warm smile, both with bright wide-open eyes. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S001_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S001_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the dance beats, the last 2s are spare footage):
I2V from `S001_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: the camera swoops in low as Kutty twirls and her ribbons fly while Paati claps on the beat; 2–4s: Kutty hops in a bouncy dance step and spreads her arms; 4–6s: Paati stands and they dance together a few steps, swaying side to side. 6–8s (spare 2s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 6s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, laughing, spinning or sleeping in the nest. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S002: Cut to a veranda swing.

### Segment 2 — Wish 1: go into the ant's house (Scenes 2–3) | 0:06–0:14

**S002 — Paati asks: what do you want? | 0:06–0:10 (4s slot → generate 8s in Flow)**
Song sync: (0:07) "சின்னக்குட்டி, செல்லக்குட்டி என்ன வேண்டும்?"
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Kutty_Portrait.png`, `Kutty_6Angle.png`, `Paati_Portrait.png`, `Paati_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A wooden veranda swing with hanging brass lanterns) · Scene Continuity Reference: `S001_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Medium shot on a village-house veranda with a wooden swing and hanging brass lanterns: Paati (her loving grandmother with silver hair in a bun with a jasmine garland, a kind round face, round gold-rimmed glasses and a maroon cotton saree with a gold border) sitting on the swing leaning toward the camera with her palms open in a loving asking gesture and a warm smile, and Kutty (a 5-year-old Tamil girl with warm brown skin, rosy cheeks, two high pigtails with red ribbons, a bright yellow frock with tiny white flowers and red bangles) beside her bouncing on her toes with a big grin, both with bright wide-open eyes. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S002_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S002_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S002_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: Paati tilts her head and opens her palms in a loving asking gesture as the swing sways; 2–4s: Kutty bounces on her toes, points a finger up to her chin as if thinking, then jumps with a wide smile. 4–8s (spare 4s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, laughing, spinning or sleeping in the nest. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S003: Cut to a garden below.

**S003 — Kutty tiny, walking into the ant house | 0:10–0:14 (4s slot → generate 8s in Flow)**
Song sync: (0:11) "குட்டி எறும்பின் வீட்டுக்குள்ளே செல்ல வேண்டும்."
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Kutty_Portrait.png`, `Kutty_6Angle.png`, `Ants_Portrait.png`, `Ants_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A giant ant hill among towering grass blades and flowers in a garden) · Scene Continuity Reference: `S002_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Macro low-angle shot in a garden where everything is giant: Kutty (a 5-year-old Tamil girl with warm brown skin, rosy cheeks, two high pigtails with red ribbons, a bright yellow frock with tiny white flowers and red bangles) shrunk to ant size, standing at the glowing arched door of a huge ant hill between towering grass blades and giant flowers, while the friendly ant family (a mother ant with a tiny golden crown, a dad ant and three ant children, all with big glossy eyes) welcome her at the door and dance in a line, all with bright wide-open eyes. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S003_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S003_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S003_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: the ants hop on the beat and wave Kutty in as she dances toward the glowing door; 2–4s: Kutty and the ant family do a bouncy conga line into the hill as sparkles trail behind them. 4–8s (spare 4s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, laughing, spinning or sleeping in the nest. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S004: Cut to a tree branch.

### Segment 3 — Wish 2: sleep in the sparrow's nest (Scenes 4–5) | 0:14–0:22

**S004 — Paati asks again | 0:14–0:18 (4s slot → generate 8s in Flow)**
Song sync: (0:15) "சின்னக்குட்டி, செல்லக்குட்டி என்ன வேண்டும்?"
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Kutty_Portrait.png`, `Kutty_6Angle.png`, `Paati_Portrait.png`, `Paati_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A shady spot under a neem tree with a rope cot) · Scene Continuity Reference: `S003_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Medium shot under a leafy neem tree in a village yard with a rope cot and falling leaves: Paati (her loving grandmother with silver hair in a bun with a jasmine garland, a kind round face, round gold-rimmed glasses and a maroon cotton saree with a gold border) sitting on the rope cot with her hands open in a loving asking gesture, and Kutty (a 5-year-old Tamil girl with warm brown skin, rosy cheeks, two high pigtails with red ribbons, a bright yellow frock with tiny white flowers and red bangles) in front of her swaying happily with a big smile, both with bright wide-open eyes. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S004_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S004_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S004_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: Paati opens her hands lovingly and tilts her head with a smile as neem leaves drift down; 2–4s: Kutty sways and claps twice, then turns in a happy twirl. 4–8s (spare 4s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, laughing, spinning or sleeping in the nest. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S005: Cut up into a banyan tree.

**S005 — Kutty snuggles into the sparrow's nest | 0:18–0:22 (4s slot → generate 8s in Flow)**
Song sync: (0:19) "குருவி கட்டும் கூட்டுக்குள்ளே தூங்க வேண்டும்."
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Kutty_Portrait.png`, `Kutty_6Angle.png`, `Sparrow_Portrait.png`, `Sparrow_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A cosy woven sparrow nest high in a banyan tree branch) · Scene Continuity Reference: `S004_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Medium shot high in a banyan tree at golden hour: Kutty (a 5-year-old Tamil girl with warm brown skin, rosy cheeks, two high pigtails with red ribbons, a bright yellow frock with tiny white flowers and red bangles) shrunk to bird size, snuggled in a cosy woven twig-and-feather nest with a big smile and bright wide-open eyes, the mother sparrow (round, brown and cream with a black bib and an orange beak) and her three fluffy golden chicks bobbing and swaying happily around her. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S005_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S005_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S005_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: Kutty settles into the nest and sways side to side as the sparrow chicks bob on the beat; 2–4s: the mother sparrow flaps her wings softly, and they all sway and rock together with wide happy smiles. 4–8s (spare 4s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, laughing, spinning or sleeping in the nest. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S006: Cut to a rainy windowsill.

### Segment 4 — Wish 3: sail a paper boat (Scenes 6–7) | 0:22–0:30

**S006 — Paati asks a third time | 0:22–0:26 (4s slot → generate 8s in Flow)**
Song sync: (0:22) "சின்னக்குட்டி, செல்லக்குட்டி என்ன வேண்டும்?"
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Kutty_Portrait.png`, `Kutty_6Angle.png`, `Paati_Portrait.png`, `Paati_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A rain-washed house window ledge with clay-tile eaves) · Scene Continuity Reference: `S005_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Medium shot at a rain-washed house window ledge under clay-tile eaves, with raindrops glittering: Paati (her loving grandmother with silver hair in a bun with a jasmine garland, a kind round face, round gold-rimmed glasses and a maroon cotton saree with a gold border) leaning from the window with a folded paper boat in her hand and a warm smile, and Kutty (a 5-year-old Tamil girl with warm brown skin, rosy cheeks, two high pigtails with red ribbons, a bright yellow frock with tiny white flowers and red bangles) outside under a little red umbrella bouncing on her toes with a big grin, both with bright wide-open eyes. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S006_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S006_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S006_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: Paati holds out the paper boat with a loving asking gesture as raindrops sparkle; 2–4s: Kutty spins her red umbrella and hops with a wide smile. 4–8s (spare 4s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, laughing, spinning or sleeping in the nest. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S007: Cut to a pond.

**S007 — Kutty sails the paper boat | 0:26–0:30 (4s slot → generate 8s in Flow)**
Song sync: (0:26) "தாளில் செய்த கப்பல் ஏறிச் சுற்ற வேண்டும்."
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Kutty_Portrait.png`, `Kutty_6Angle.png`, `Boat_Portrait.png`, `Boat_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A clear lily pond with dragonflies at the edge of a village) · Scene Continuity Reference: `S006_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot on a calm lily pond with dragonflies at golden hour: Kutty (a 5-year-old Tamil girl with warm brown skin, rosy cheeks, two high pigtails with red ribbons, a bright yellow frock with tiny white flowers and red bangles) sitting happily in the big white paper boat with a small red flag, floating among lily pads with her arms up in joy and a huge smile and bright wide-open eyes, the ripples glittering. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S007_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S007_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S007_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: the paper boat glides in a circle between the lily pads as Kutty waves her arms and sways on the beat; 2–4s: the boat spins gently on the water as dragonflies loop past and Kutty throws her arms up. 4–8s (spare 4s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, laughing, spinning or sleeping in the nest. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S008: Cut to a sunflower field.

### Segment 5 — Wish 4: ride a butterfly (Scenes 8–8) | 0:30–0:36

**S008 — Paati asks; Kutty rides the butterfly | 0:30–0:36 (6s slot → generate 8s in Flow)**
Song sync: (0:30) "சின்னக்குட்டி, செல்லக்குட்டி என்ன வேண்டும்? (0:33) பட்டாம்பூச்சி முதுகில் ஏறிப் பறக்க வேண்டும்."
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Kutty_Portrait.png`, `Kutty_6Angle.png`, `Paati_Portrait.png`, `Paati_6Angle.png`, `Butterfly_Portrait.png`, `Butterfly_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A meadow of tall sunflowers with a hill path) · Scene Continuity Reference: `S007_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot in a meadow of tall sunflowers at golden hour: Kutty (a 5-year-old Tamil girl with warm brown skin, rosy cheeks, two high pigtails with red ribbons, a bright yellow frock with tiny white flowers and red bangles) sitting safely on the back of the giant friendly butterfly with orange, turquoise and pink gold-edged wings just above the flower tops, hugging it with a huge smile and bright wide-open eyes, and Paati (her loving grandmother with silver hair in a bun with a jasmine garland, a kind round face, round gold-rimmed glasses and a maroon cotton saree with a gold border) on the path below waving up with a warm smile. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S008_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S008_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the dance beats, the last 2s are spare footage):
I2V from `S008_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: Paati opens her palms in a loving asking gesture, and Kutty bounces with a smile; 2–4s: Kutty climbs onto the butterfly's back and the wings begin to flap; 4–6s: the butterfly rises gently over the sunflowers as Kutty throws one arm up and Paati waves. 6–8s (spare 2s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 6s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, laughing, spinning or sleeping in the nest. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S009: Cut to a lamp-lit room.

### Segment 6 — Wish 5: a loving friend (Scenes 9–10) | 0:36–0:46

**S009 — Paati asks the last time | 0:36–0:40 (4s slot → generate 8s in Flow)**
Song sync: (0:37) "சின்னக்குட்டி, செல்லக்குட்டி என்ன வேண்டும்?"
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Kutty_Portrait.png`, `Kutty_6Angle.png`, `Paati_Portrait.png`, `Paati_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A lamp-lit living room with a rocking chair and a window of fireflies) · Scene Continuity Reference: `S008_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Medium shot in a cosy lamp-lit village living room with a wooden rocking chair and fireflies glowing at the window: Paati (her loving grandmother with silver hair in a bun with a jasmine garland, a kind round face, round gold-rimmed glasses and a maroon cotton saree with a gold border) in the rocking chair opening her arms in a loving asking gesture, and Kutty (a 5-year-old Tamil girl with warm brown skin, rosy cheeks, two high pigtails with red ribbons, a bright yellow frock with tiny white flowers and red bangles) hugging a small cushion and bouncing happily, both with bright wide-open eyes. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S009_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S009_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the dance beats, the last 4s are spare footage):
I2V from `S009_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: Paati opens her arms lovingly as the chair rocks; 2–4s: Kutty hugs the cushion, bounces, then throws it up in a happy toss and smiles wide. 4–8s (spare 4s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, laughing, spinning or sleeping in the nest. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→S010: Cut to a hilltop.

**S010 — Kutty and Thenu: a loving friend | 0:40–0:46 (6s slot → generate 8s in Flow)**
Song sync: (0:41) "எப்போதுமே அன்பு காட்டும் நண்பர் வேண்டும்."
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Kutty_Portrait.png`, `Kutty_6Angle.png`, `Thenu_Portrait.png`, `Thenu_6Angle.png`, `Paati_Portrait.png`, `Paati_6Angle.png`, `Ants_Portrait.png`, `Ants_6Angle.png`, `Sparrow_Portrait.png`, `Sparrow_6Angle.png`, `Butterfly_Portrait.png`, `Butterfly_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A grassy hilltop at sunset with fireflies and a banyan tree) · Scene Continuity Reference: `S009_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot on a grassy hilltop at sunset with fireflies and a big banyan tree: Kutty (a 5-year-old Tamil girl with warm brown skin, rosy cheeks, two high pigtails with red ribbons, a bright yellow frock with tiny white flowers and red bangles) and Thenu (a 5-year-old Tamil boy with short curly black hair, a green shirt and white shorts) holding hands and dancing joyfully with big smiles, while Paati (her loving grandmother with silver hair in a bun with a jasmine garland, a kind round face, round gold-rimmed glasses and a maroon cotton saree with a gold border) watches and claps behind them, and around them the ants, the mother sparrow (round, brown and cream with a black bib and an orange beak) and her three fluffy golden chicks and the giant butterfly dance happily, all with bright wide-open eyes. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S010_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S010_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the dance beats, the last 2s are spare footage):
I2V from `S010_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–2s: Thenu runs in and takes Kutty's hands as the two begin to spin in a circle, the animals bouncing around them; 2–4s: Kutty and Thenu hop and dance in step while Paati claps and the butterfly circles; 4–6s: everyone gathers in a happy group pose with arms up as sparkles and fireflies drift. 6–8s (spare 2s): the same joyful dance motion continues and settles into a bright happy hold with no new action, so the clip can be trimmed back to the 6s slot or stretched. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, laughing, spinning or sleeping in the nest. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→Fade out; use the bonus scenes as cutaways.

---

### Segment 7 — Bonus dance scenes (Scenes 11–18) | bonus (no timestamp)

**S011 — Rooftop kite dance | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any line of the song or between wishes.
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Kutty_Portrait.png`, `Kutty_6Angle.png`, `Thenu_Portrait.png`, `Thenu_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A sunny rooftop terrace with colourful kites on strings) · Scene Continuity Reference: `S010_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot on a sunny village rooftop terrace with colourful kites and a low safe parapet: Kutty (a 5-year-old Tamil girl with warm brown skin, rosy cheeks, two high pigtails with red ribbons, a bright yellow frock with tiny white flowers and red bangles) and Thenu (a 5-year-old Tamil boy with short curly black hair, a green shirt and white shorts) dancing with big smiles on the beat, kites fluttering in the sky behind them, both with bright wide-open eyes. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S011_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S011_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S011_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: Kutty and Thenu clap and step side to side on the beat; 3–6s: they spin once each and hop together with their arms up; 6–8s: they strike a happy pose as the kites sway. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, laughing, spinning or sleeping in the nest. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→Use as a cutaway or loop.

**S012 — Ant dance party on a leaf stage | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any line of the song or between wishes.
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Kutty_Portrait.png`, `Kutty_6Angle.png`, `Ants_Portrait.png`, `Ants_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A giant green leaf stage in a dewy garden) · Scene Continuity Reference: `S011_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Macro shot of a giant green leaf like a stage in a dewy garden: Kutty (a 5-year-old Tamil girl with warm brown skin, rosy cheeks, two high pigtails with red ribbons, a bright yellow frock with tiny white flowers and red bangles) shrunk to ant size dancing in front of the friendly ant family (a mother ant with a tiny golden crown, a dad ant and three ant children, all with big glossy eyes), all dancing with big smiles and bright wide-open eyes, dew drops glittering. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S012_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S012_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S012_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: the ants and Kutty bounce on the beat in a line; 3–6s: they spin in a circle holding hands; 6–8s: they strike a joyful pose as dew sparkles. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, laughing, spinning or sleeping in the nest. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→Use as a cutaway or loop.

**S013 — Sparrow branch dance | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any line of the song or between wishes.
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Kutty_Portrait.png`, `Kutty_6Angle.png`, `Sparrow_Portrait.png`, `Sparrow_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A flowering mango-tree branch in spring) · Scene Continuity Reference: `S012_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Medium shot on a thick flowering mango-tree branch in spring: Kutty (a 5-year-old Tamil girl with warm brown skin, rosy cheeks, two high pigtails with red ribbons, a bright yellow frock with tiny white flowers and red bangles) shrunk to bird size dancing happily with the mother sparrow (round, brown and cream with a black bib and an orange beak) and her three fluffy golden chicks, all with big smiles and bright wide-open eyes, mango blossoms falling. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S013_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S013_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S013_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: Kutty and the chicks bob and hop on the beat; 3–6s: the mother sparrow flaps while Kutty spins; 6–8s: they pose together as blossoms drift. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, laughing, spinning or sleeping in the nest. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→Use as a cutaway or loop.

**S014 — Puddle splash dance | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any line of the song or between wishes.
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Kutty_Portrait.png`, `Kutty_6Angle.png`, `Paati_Portrait.png`, `Paati_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A rainy village lane with puddles and colourful umbrellas) · Scene Continuity Reference: `S013_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot on a rainy village lane with shiny puddles and colourful umbrellas: Kutty (a 5-year-old Tamil girl with warm brown skin, rosy cheeks, two high pigtails with red ribbons, a bright yellow frock with tiny white flowers and red bangles) and Paati (her loving grandmother with silver hair in a bun with a jasmine garland, a kind round face, round gold-rimmed glasses and a maroon cotton saree with a gold border) dancing with umbrellas and big smiles, raindrops glittering, both with bright wide-open eyes. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S014_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S014_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S014_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: Kutty and Paati spin their umbrellas on the beat; 3–6s: they splash through puddles in a matching step; 6–8s: they pose under their umbrellas. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, laughing, spinning or sleeping in the nest. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→Use as a cutaway or loop.

**S015 — Butterfly garden twirl | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any line of the song or between wishes.
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Kutty_Portrait.png`, `Kutty_6Angle.png`, `Butterfly_Portrait.png`, `Butterfly_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A rainbow flower garden with arched trellises) · Scene Continuity Reference: `S014_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot in a rainbow flower garden with arched trellises: Kutty (a 5-year-old Tamil girl with warm brown skin, rosy cheeks, two high pigtails with red ribbons, a bright yellow frock with tiny white flowers and red bangles) twirling with her arms wide in front of the giant friendly butterfly with orange, turquoise and pink gold-edged wings, which flaps over her head, both with big smiles and bright wide-open eyes, petals swirling. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S015_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S015_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S015_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: Kutty twirls and the butterfly circles around her; 3–6s: she hops in a bouncy step as petals swirl; 6–8s: she strikes a happy pose as the butterfly lands on her hand. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, laughing, spinning or sleeping in the nest. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→Use as a cutaway or loop.

**S016 — Clapping game in the schoolyard | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any line of the song or between wishes.
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Kutty_Portrait.png`, `Kutty_6Angle.png`, `Thenu_Portrait.png`, `Thenu_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A colourful village schoolyard with a big tamarind tree) · Scene Continuity Reference: `S015_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Medium shot in a colourful village schoolyard under a big tamarind tree: Kutty (a 5-year-old Tamil girl with warm brown skin, rosy cheeks, two high pigtails with red ribbons, a bright yellow frock with tiny white flowers and red bangles) and Thenu (a 5-year-old Tamil boy with short curly black hair, a green shirt and white shorts) playing a clapping game facing each other with big smiles and bright wide-open eyes. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S016_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S016_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S016_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: Kutty and Thenu clap hands together on the beat; 3–6s: they clap, spin and clap again; 6–8s: they jump together and pose. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, laughing, spinning or sleeping in the nest. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→Use as a cutaway or loop.

**S017 — Family dance on a festival stage | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any line of the song or between wishes.
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Kutty_Portrait.png`, `Kutty_6Angle.png`, `Paati_Portrait.png`, `Paati_6Angle.png`, `Thenu_Portrait.png`, `Thenu_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A village festival stage with strings of lights) · Scene Continuity Reference: `S016_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot on a village festival stage with strings of lights and flower garlands: Kutty (a 5-year-old Tamil girl with warm brown skin, rosy cheeks, two high pigtails with red ribbons, a bright yellow frock with tiny white flowers and red bangles), Thenu (a 5-year-old Tamil boy with short curly black hair, a green shirt and white shorts) and Paati (her loving grandmother with silver hair in a bun with a jasmine garland, a kind round face, round gold-rimmed glasses and a maroon cotton saree with a gold border) dancing together with big smiles and bright wide-open eyes, confetti petals falling. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S017_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S017_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S017_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: the three dance side to side on the beat; 3–6s: Kutty and Thenu twirl while Paati claps; 6–8s: all three raise their arms in a happy pose. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, laughing, spinning or sleeping in the nest. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→Use as a cutaway or loop.

**S018 — Firefly meadow finale | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any line of the song or between wishes.
Step 3 Ingredients: Character, Animal & Prop Reference Images: `Kutty_Portrait.png`, `Kutty_6Angle.png`, `Thenu_Portrait.png`, `Thenu_6Angle.png`, `Ants_Portrait.png`, `Ants_6Angle.png`, `Sparrow_Portrait.png`, `Sparrow_6Angle.png`, `Butterfly_Portrait.png`, `Butterfly_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A moonlit meadow full of fireflies) · Scene Continuity Reference: `S017_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
All eyes wide open and fully visible, big round glossy eyes with fixed-open eyelids. Wide shot in a moonlit meadow full of glowing fireflies: Kutty (a 5-year-old Tamil girl with warm brown skin, rosy cheeks, two high pigtails with red ribbons, a bright yellow frock with tiny white flowers and red bangles) and Thenu (a 5-year-old Tamil boy with short curly black hair, a green shirt and white shorts) dancing hand in hand with the ants, the mother sparrow (round, brown and cream with a black bib and an orange beak) and her three fluffy golden chicks and the giant butterfly around them, all with big smiles and bright wide-open eyes, soft moonlight and sparkles. 3D animated family-film style, vibrant jewel colours, soft golden light, dreamy sparkle, soft global illumination.
Save as: `S018_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S018_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S018_Ref.png`. All eyes are wide open and fully visible from the first frame to the last. 0–3s: Kutty and Thenu spin hand in hand as the animals bounce around them; 3–6s: everyone dances in a happy circle; 6–8s: they all strike a joyful group pose as fireflies glow. No singing, speaking or lip movement: everyone keeps a bright happy smile with a closed mouth. Eyes: all eyes stay wide open for the entire clip, with big round glossy eyes and fixed-open eyelids, no eyelid movement; no blinking, no closing, no squinting, no winking, no half-closed or sleepy eyes, even when smiling, laughing, spinning or sleeping in the nest. AVOID: closed eyes, blinking, squinting, eyes shut. Soundless action clip: no sound, no music, no voices, no chirps.
Sound: none (a soundless clip; your song is added in the edit)
Cut→Use as a cutaway or loop.

---

# PRODUCTION NOTES

- **Total required:** 18 reference images (`S001_Ref.png` … `S018_Ref.png`) and 18 videos, one video per image: 10 timed scenes that follow the song plus 8 bonus dance scenes. Plus the Step 1 sheets: Kutty, Paati, Thenu, the ant family, the sparrow family, the paper boat and the butterfly, 7 portraits and 7 six-angle turnarounds (14 images). There are no environment-plate images. Overall: 18 scene images + 14 sheet images = 32 images, and 18 videos.
- **Song length:** no audio file came with this request, so the end is estimated at 0:46 (the last line starts at 0:41 and takes about 4 s). Send the audio and I will re-check the final cut. The timed scenes add up to 46 s.
- **Song structure (from your timestamps):** 0:00–0:07 intro; then five wishes, each a question ("சின்னக்குட்டி, செல்லக்குட்டி என்ன வேண்டும்?") and an answer: 0:07/0:11 the ant's house, 0:15/0:19 the sparrow's nest, 0:22/0:26 the paper boat, 0:30/0:33 the butterfly ride, 0:37/0:41 a loving friend. Clips use even seconds, so lines starting at odd seconds start 1 s into a clip; every clip has spare footage, so you can nudge a clip by a second to land a move on a beat. The transcript spellings (குட்டியரும்பு, தாலில், முதையில்) were corrected to match your lyrics.
- **Characters:** Paati asks every question with a tilted head and open hands (no speech). Kutty is shown tiny for the ant house, the sparrow nest and the ant leaf stage, then normal size again. Thenu appears for the final wish. Animals and creatures appear only in the line that names them.
- **Eyes open, always smiling:** the lock block has an EYE RULE, an EYE DESIGN line (big glossy round toy-like eyes with permanently fixed-open eyelids), an AVOID list and a SMILE RULE; every video prompt starts and ends with an eyes-open instruction and every reference-image prompt starts with one. The nest scene shows Kutty snuggled with eyes wide open. If a clip shows a blink, use another take, use only the first 4 s, regenerate from the same image, or trim before the blink and cross-dissolve; prompts cannot guarantee Flow's output, so check each clip.
- **Soundless clips:** no singing, voices, music or sound effects, and everyone keeps a closed-mouth smile. Your recorded song is added in the edit.
- **What to generate in Flow (8 s or 10 s only):** every video is generated at 8 s. All timed slots are 4 s or 6 s, so each clip has 2–4 s of spare footage after the dance beats. The bonus scenes are 8 s. No scene needs 10 s.

| Generate in Flow | Number of videos | Footage | Scenes |
|---|---|---|---|
| 8 s | 18 | 144 s | all scenes S001–S018 |

- **Slot plan (timed scenes):** the 4 s slots are S002–S007, S009 (7 clips, 28 s); the 6 s slots are S001, S008, S010 (3 clips, 18 s); total 46 s.
- **Timeline rule:** put the song on the timeline at 0:00, drop each timed clip at its scene start time and trim it to its slot. The extra seconds are spare footage. The bonus scenes have no timestamp: use them as cutaways, or loop the song to make a longer video.
- **Image generation is Google Flow only.** Generate the 7 sheets first, then each scene image in order. Video prompts use each scene's saved image as the starting frame.
- **Reminder:** the GLOBAL LOCK BLOCK must be appended in full to the end of every prompt (Step 1, every Step 3 and every Step 4) before submission.
