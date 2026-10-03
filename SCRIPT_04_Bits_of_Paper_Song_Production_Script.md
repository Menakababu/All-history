# SCRIPT 04 — Bits of Paper: a classroom clean-up song with Priya and Kavya
### [TEMPLATE v3 — Google Flow only · song slots of 4/6 s, Flow clips generated at 8 s · character and prop sheets → a different school spot per scene → per-scene reference image → per-scene video · global lock appended to every prompt · no on-screen text · consistent visible faces · quiet SFX only]

**Duration:** about 0:38 (song ≈ 37–38 s, not attached; estimated) | **Total Scenes:** 15 = 15 reference images = 15 videos (9 timed scenes + 6 bonus dance scenes)
**Image generation:** Google Flow only (Step 1 sheets, Step 2 location plan, Step 3 scene reference images)
**Video generation:** Google Flow — one video prompt per scene, each generated as an 8 s clip (a 4 s or 6 s song slot plus spare seconds to trim)
**Payoff:** The two girls turn a messy classroom into a sparkling tidy one, ending with a high-five and a thumbs up.
**Dialogue/Audio rule:** The generated clips contain NO voice, singing or music: only quiet sound effects. Your song is added in the edit.

**Assumptions made for the blank input fields (change if needed):**
- **Style:** 3D animated family-film look (bright, cheerful, child-friendly). Tell me if you want 2D cartoon instead.
- **Characters:** two invented girls, Priya and Kavya, plus bits of paper and a small cleanup kit (green bin, broom, dustpan).
- **Hard rules:** no on-screen text or lyrics, no teacher or other children.
- **Song length:** estimated; the audio was not attached.

**Segment map**

| # | Segment | Scenes | Time |
|---|---|---|---|
| 1 | Intro and verse 1: bits of paper lying on the floor | S001–S003 | 0:00–0:12 |
| 2 | Verse 2: it makes our class untidy, pick them up | S004–S005 | 0:12–0:20 |
| 3 | Verse 1 repeats: dancing with the paper | S006–S007 | 0:20–0:28 |
| 4 | Verse 2 repeats and the tidy finale | S008–S009 | 0:28–0:38 |
| 5 | Bonus vibe scenes (use anywhere in the edit) | S010–S015 | bonus (no timestamp) |

---

## ⚠️ GLOBAL LOCK BLOCK — append this in full to the END of every single prompt below (Step 1, every Step 3, every Step 4)

```
GLOBAL LOCK:
CONTINUITY — Keep Priya (red ribbons, navy pinafore, red bag), Kavya (yellow hairband, curly hair, maroon pinafore, blue bag), the bits of paper (red, yellow, blue, green and pink scraps) and the cleanup kit (green bin, red-handled broom, yellow dustpan) in exact face, colour, clothing and proportion continuity from their saved reference sheets — no redesign, recolor or scale drift. Every scene takes place in its own different spot of the same school: sunny yellow walls, wooden desks, a green blackboard with only simple doodles, tiled floor. Never copy the previous scene's spot, background or composition.
CAST RULE — Every scene shows exactly the two girls, Priya and Kavya, plus the bits of paper (and, where the prompt says so, the cleanup kit). No other children, no teacher, no animals.
STYLE — 3D animated family-film style, bright cheerful colours, soft global illumination, a warm 35mm-lens depth of field, one consistent colour grade (sunny gold, fresh greens, sky blue, bright paper colours), smooth appealing character animation with natural squash and stretch, expressive faces and exaggerated happy dance moves that land on the beat of a catchy song.
HARD RULES — No on-screen text, captions, lyrics, logos or watermarks; the blackboard and papers show only simple doodles and unreadable marks. Fully child-friendly: no scolding, no scary or dangerous content. The girls always have clear, fully visible, expressive faces matching their sheets in every shot; faces never morph between shots. Paper bits stay small and colourful and never turn into anything else.
ZERO AI ARTIFACTS — No morphing, warping, melting, flicker, extra or duplicated limbs, hands, fingers or characters, floating debris other than the intended paper bits, texture smearing, distorted hands or feet.
LIGHTING — Follow the time of day and light written in each scene's prompt; no sudden unintended light jumps inside a shot.
AUDIO — Generated audio is ONLY quiet diegetic sound effects (paper rustle, footsteps, sneaker squeaks, broom sweep, bin thud, clapping). No music, no singing, no speech, no lip-sync: the song is added in the edit. The girls keep expressive faces with closed mouths.
CAMERA — Smooth, physically plausible motion only; each shot's opening camera motion matches the previous shot's closing motion vector for a seamless cut.
```

---

# STEP 1 — CHARACTER & PROP REFERENCE IMAGES (Google Flow — image generation ONLY)

### 1A. Girl 1 ("Priya")
**Portrait Image Prompt — Google Flow:**
Full-body portrait of an 8-year-old Tamil girl named Priya standing in a happy relaxed pose, facing the camera, with a clearly visible, fully expressive animated face: warm brown skin, big bright dark eyes, rosy cheeks, two high black pigtails tied with red ribbons, a cheerful gap-toothed smile. White school shirt, navy-blue pinafore, white socks and black school shoes, a small red school bag. 3D animated family-film style, bright cheerful colours, soft global illumination. Neutral light-grey background, soft key light, clean readable shapes. Locked reference design.
**Save as:** `Priya_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Priya_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) locking the face.
**Save as:** `Priya_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S001–S015.

### 1B. Girl 2 ("Kavya")
**Portrait Image Prompt — Google Flow:**
Full-body portrait of an 8-year-old Tamil girl named Kavya standing in a happy relaxed pose, facing the camera, with a clearly visible, fully expressive animated face: medium-brown skin, big warm brown eyes, dimples, short curly black hair held back by a yellow hairband, a bright mischievous smile. White school shirt, maroon pinafore, white socks and black school shoes, a small blue school bag. 3D animated family-film style, bright cheerful colours, soft global illumination. Neutral light-grey background, soft key light. Locked reference design.
**Save as:** `Kavya_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Kavya_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) locking the face.
**Save as:** `Kavya_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S001–S015.

### 1C. Bits of Paper (prop) ("PaperBits")
**Portrait Image Prompt — Google Flow:**
A cheerful prop sheet of torn bits of paper: about twenty small irregular scraps in bright red, yellow, blue, green and pink, some flat and some crumpled, in a loose pile on a neutral surface, soft paper fibre edges, a few scraps mid-flutter above the pile. 3D animated family-film style, bright cheerful colours, soft global illumination. Neutral light-grey background, soft key light. Locked reference design.
**Save as:** `PaperBits_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `PaperBits_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up detail panels.
**Save as:** `PaperBits_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S001–S015.

### 1D. Cleanup Kit (prop) ("CleanupKit")
**Portrait Image Prompt — Google Flow:**
A cleanup prop sheet: a small child-sized green plastic waste bin with a simple recycling-arrow symbol embossed (no text), a small soft broom with a red handle and a matching yellow dustpan, standing together on a neutral surface. 3D animated family-film style, bright cheerful colours, soft global illumination. Neutral light-grey background, soft key light. Locked reference design.
**Save as:** `CleanupKit_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `CleanupKit_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up detail panels.
**Save as:** `CleanupKit_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S005, S009.

---

# STEP 2 — LOCATION PLAN (no reusable environment plates: every scene is a different spot of the school)

There are no shared environment-plate images. Each scene's Step 3 prompt describes its own spot, and `Environment Reference Image` is `none`. Every spot is in the same sunny school, so the look stays consistent. The table lists the spot of every scene so you can check none repeats.

| Scene | Time | Slot | Flow clip | Unique location |
|---|---|---|---|---|
| S001 | 0:00–0:04 | 4s | 8 s | Doorway of a bright classroom in the morning, paper bits scattered inside |
| S002 | 0:04–0:08 | 4s | 8 s | The aisle between rows of wooden desks |
| S003 | 0:08–0:12 | 4s | 8 s | The tiled classroom floor between the desks, seen from a very low angle |
| S004 | 0:12–0:16 | 4s | 8 s | The back of the classroom with a bookshelf and a messy craft table |
| S005 | 0:16–0:20 | 4s | 8 s | Beside a green waste bin under a classroom window |
| S006 | 0:20–0:24 | 4s | 8 s | The art corner with colourful paper rolls and a craft table |
| S007 | 0:24–0:28 | 4s | 8 s | The front of the classroom by the blackboard and the teacher's desk |
| S008 | 0:28–0:32 | 4s | 8 s | A reading corner with beanbags and a rug, half messy and half tidy |
| S009 | 0:32–0:38 | 6s | 8 s | The centre of a sunny, now-tidy classroom floor |
| S010 | bonus (no timestamp) | none | 8 s | A school corridor with lockers and polished floor |
| S011 | bonus (no timestamp) | none | 8 s | A classroom with a ceiling fan swirling paper bits |
| S012 | bonus (no timestamp) | none | 8 s | A sunny veranda outside the classroom door |
| S013 | bonus (no timestamp) | none | 8 s | A classroom window seat beside a green bin |
| S014 | bonus (no timestamp) | none | 8 s | A tidy classroom in warm sunset light |
| S015 | bonus (no timestamp) | none | 8 s | Rows of desks in the classroom with pencils |

---

# STEP 3 & STEP 4 — SCENES (song slots of 4 and 6 seconds; every Flow video is generated at 8 or 10 seconds)

**How each scene is shaped:**
Header line (scene number, label, time range and slot) → **Song sync** (editor note only, never paste into Flow) → Step 3 Ingredients → Step 3 Reference Image Prompt → Step 4 Ingredients → Video Prompt (Google Flow, generated at 8 s; second marks relative to the clip start, the lyric beats first and spare seconds after) → Sound → Cut→.
Append the GLOBAL LOCK BLOCK to the end of every Step 3 and Step 4 prompt.

---

### Segment 1 — Intro and verse 1: bits of paper lying on the floor (Scenes 1–3) | 0:00–0:12

**S001 — A messy classroom, the girls arrive | 0:00–0:04 (4s slot → generate 8s in Flow)**
Song sync: (0:00) "(அறிமுகம்; பாடல் 0:04-க்குத் தொடங்குகிறது)"
Step 3 Ingredients: Character & Prop Reference Images: `Priya_Portrait.png`, `Priya_6Angle.png`, `Kavya_Portrait.png`, `Kavya_6Angle.png`, `PaperBits_Portrait.png`, `PaperBits_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: Doorway of a bright classroom in the morning, paper bits scattered inside) · Scene Continuity Reference: none (first scene in the series)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot from the doorway of a bright school classroom with sunny yellow walls, wooden desks, a green blackboard with only simple doodles (no writing) and a tiled floor in morning sunlight: the girls Priya and Kavya stopping at the door with their school bags and surprised, wide-eyed faces, and colourful bits of paper scattered across the floor beyond, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S001_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S001_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the lyric beats, the last 4s are spare footage):
I2V from `S001_Ref.png`. 0–2s: the camera pushes in slowly over the girls' shoulders as they gasp and look at the paper-strewn floor; 2–4s: the girls look at each other with wide eyes and bounce on their toes in rhythm. 4–8s (spare 4s): the same gentle motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No speech, singing or lip-sync: the girls keep expressive happy or playful faces with closed mouths. Audio is quiet sound effects only; the song is added in the edit.
Sound (SFX only, no music, no voice): Footsteps stopping, school bags thumping softly, a few paper bits rustling; morning birdsong through the window. From 4s to 8s the ambience sustains and eases down.
Cut→S002: Cut to a close shot of the aisle.

**S002 — Bits of paper, bits of paper | 0:04–0:08 (4s slot → generate 8s in Flow)**
Song sync: (0:04) "Bits of paper, bits of paper"
Step 3 Ingredients: Character & Prop Reference Images: `Priya_Portrait.png`, `Priya_6Angle.png`, `Kavya_Portrait.png`, `Kavya_6Angle.png`, `PaperBits_Portrait.png`, `PaperBits_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: The aisle between rows of wooden desks) · Scene Continuity Reference: `S001_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Medium shot down the aisle between rows of wooden desks in a bright school classroom with sunny yellow walls, wooden desks, a green blackboard with only simple doodles (no writing) and a tiled floor: the girls Priya and Kavya pointing at colourful bits of paper that flutter in the air around them, big delighted-surprised faces, red, yellow, blue, green and pink paper scraps in sunbeams, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S002_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S002_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the lyric beats, the last 4s are spare footage):
I2V from `S002_Ref.png`. 0–2s: the girls point at the fluttering paper bits in time with the beat, one finger after the other; 2–4s: they bounce side to side as the paper bits swirl and drift down, the camera pushing slowly in. 4–8s (spare 4s): the same gentle motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No speech, singing or lip-sync: the girls keep expressive happy or playful faces with closed mouths. Audio is quiet sound effects only; the song is added in the edit.
Sound (SFX only, no music, no voice): Light paper flutter and rustle, soft sneaker squeaks on the tiles; a soft tapping of fingers. From 4s to 8s the ambience sustains and eases down.
Cut→S003: Cut to a low shot of the floor.

**S003 — Lying on the floor | 0:08–0:12 (4s slot → generate 8s in Flow)**
Song sync: (0:08) "Lying on the floor, lying on the floor"
Step 3 Ingredients: Character & Prop Reference Images: `Priya_Portrait.png`, `Priya_6Angle.png`, `Kavya_Portrait.png`, `Kavya_6Angle.png`, `PaperBits_Portrait.png`, `PaperBits_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: The tiled classroom floor between the desks, seen from a very low angle) · Scene Continuity Reference: `S002_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Very low-angle shot at floor level between desk legs in a bright school classroom with sunny yellow walls, wooden desks, a green blackboard with only simple doodles (no writing) and a tiled floor: many colourful bits of paper lying scattered on the shiny tiles, and in the background the girls Priya and Kavya's shoes and their puzzled faces peering down, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S003_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S003_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the lyric beats, the last 4s are spare footage):
I2V from `S003_Ref.png`. 0–2s: the camera slides low along the tiles past the paper bits in rhythm as the girls' shoes tap on the beat; 2–4s: a few paper bits flutter down and land, and the girls crouch into frame with scolding-but-playful faces. 4–8s (spare 4s): the same gentle motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No speech, singing or lip-sync: the girls keep expressive happy or playful faces with closed mouths. Audio is quiet sound effects only; the song is added in the edit.
Sound (SFX only, no music, no voice): Paper scraps landing softly, shoe taps on tile in rhythm. From 4s to 8s the ambience sustains and eases down.
Cut→S004: Cut to the back of the classroom.

---

### Segment 2 — Verse 2: it makes our class untidy, pick them up (Scenes 4–5) | 0:12–0:20

**S004 — Make our class untidy | 0:12–0:16 (4s slot → generate 8s in Flow)**
Song sync: (0:13) "Make our class untidy, make our class untidy"
Step 3 Ingredients: Character & Prop Reference Images: `Priya_Portrait.png`, `Priya_6Angle.png`, `Kavya_Portrait.png`, `Kavya_6Angle.png`, `PaperBits_Portrait.png`, `PaperBits_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: The back of the classroom with a bookshelf and a messy craft table) · Scene Continuity Reference: `S003_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot at the back of a bright school classroom with sunny yellow walls, wooden desks, a green blackboard with only simple doodles (no writing) and a tiled floor with a bookshelf and a craft table: the room looks untidy with paper bits and a few tilted chairs, and the girls Priya and Kavya with their hands on their hips and playful sad faces shaking their heads, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S004_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S004_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the lyric beats, the last 4s are spare footage):
I2V from `S004_Ref.png`. 0–2s: the girls shake their heads in rhythm with hands on hips; 2–4s: they wag a finger at the mess together and then shrug with a smile as the camera pushes in. 4–8s (spare 4s): the same gentle motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No speech, singing or lip-sync: the girls keep expressive happy or playful faces with closed mouths. Audio is quiet sound effects only; the song is added in the edit.
Sound (SFX only, no music, no voice): Chair legs scraping softly, paper rustle, a gentle head-shake whoosh. From 4s to 8s the ambience sustains and eases down.
Cut→S005: Cut to the bin by the window.

**S005 — Pick them up! | 0:16–0:20 (4s slot → generate 8s in Flow)**
Song sync: (0:17) "Pick them up! Pick them up!"
Step 3 Ingredients: Character & Prop Reference Images: `Priya_Portrait.png`, `Priya_6Angle.png`, `Kavya_Portrait.png`, `Kavya_6Angle.png`, `PaperBits_Portrait.png`, `PaperBits_6Angle.png`, `CleanupKit_Portrait.png`, `CleanupKit_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: Beside a green waste bin under a classroom window) · Scene Continuity Reference: `S004_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Medium shot beside a green waste bin under a sunny window in a bright school classroom with sunny yellow walls, wooden desks, a green blackboard with only simple doodles (no writing) and a tiled floor: the girl Priya bending to pick up bits of paper and the girl Kavya holding the small broom and dustpan, both with determined happy faces, a few paper bits on the floor, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S005_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S005_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the lyric beats, the last 4s are spare footage):
I2V from `S005_Ref.png`. 0–2s: Priya picks up a handful of paper bits on the beat and drops them in the bin as Kavya sweeps in rhythm; 2–4s: they swap with a quick step, both picking up and sweeping to the beat with big smiles. 4–8s (spare 4s): the same gentle motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No speech, singing or lip-sync: the girls keep expressive happy or playful faces with closed mouths. Audio is quiet sound effects only; the song is added in the edit.
Sound (SFX only, no music, no voice): Paper scraps landing in the bin, broom sweeping on tile in rhythm, a soft pat of hands. From 4s to 8s the ambience sustains and eases down.
Cut→S006: Cut to the art corner.

---

### Segment 3 — Verse 1 repeats: dancing with the paper (Scenes 6–7) | 0:20–0:28

**S006 — Bits of paper, dancing in the art corner | 0:20–0:24 (4s slot → generate 8s in Flow)**
Song sync: (0:21) "Bits of paper, bits of paper"
Step 3 Ingredients: Character & Prop Reference Images: `Priya_Portrait.png`, `Priya_6Angle.png`, `Kavya_Portrait.png`, `Kavya_6Angle.png`, `PaperBits_Portrait.png`, `PaperBits_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: The art corner with colourful paper rolls and a craft table) · Scene Continuity Reference: `S005_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Medium shot in the art corner of a bright school classroom with sunny yellow walls, wooden desks, a green blackboard with only simple doodles (no writing) and a tiled floor: colourful paper rolls on shelves and a craft table, and the girls Priya and Kavya dancing with bits of paper swirling around them like confetti, joyful faces, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S006_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S006_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the lyric beats, the last 4s are spare footage):
I2V from `S006_Ref.png`. 0–2s: the girls twirl in opposite directions as the paper bits swirl up around them on the beat; 2–4s: they clap and bounce together, the paper bits settling in the light. 4–8s (spare 4s): the same gentle motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No speech, singing or lip-sync: the girls keep expressive happy or playful faces with closed mouths. Audio is quiet sound effects only; the song is added in the edit.
Sound (SFX only, no music, no voice): Paper confetti rustle, light clapping, soft footsteps. From 4s to 8s the ambience sustains and eases down.
Cut→S007: Cut to the front of the classroom.

**S007 — Lying on the floor, a peek | 0:24–0:28 (4s slot → generate 8s in Flow)**
Song sync: (0:25) "Lying on the floor, lying on the floor"
Step 3 Ingredients: Character & Prop Reference Images: `Priya_Portrait.png`, `Priya_6Angle.png`, `Kavya_Portrait.png`, `Kavya_6Angle.png`, `PaperBits_Portrait.png`, `PaperBits_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: The front of the classroom by the blackboard and the teacher's desk) · Scene Continuity Reference: `S006_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot at the front of a bright school classroom with sunny yellow walls, wooden desks, a green blackboard with only simple doodles (no writing) and a tiled floor by the blackboard and a teacher's desk: bits of paper lying on the floor in a trail, and the girls Priya and Kavya tiptoeing along the trail with exaggerated looking-down poses and curious faces, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S007_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S007_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the lyric beats, the last 4s are spare footage):
I2V from `S007_Ref.png`. 0–2s: the girls tiptoe along the paper trail in rhythm with big exaggerated steps; 2–4s: they stop and point down at the paper bits together, with surprised faces, as the camera pushes in. 4–8s (spare 4s): the same gentle motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No speech, singing or lip-sync: the girls keep expressive happy or playful faces with closed mouths. Audio is quiet sound effects only; the song is added in the edit.
Sound (SFX only, no music, no voice): Exaggerated tiptoe taps, a paper scrap rustle, a small comic squeak. From 4s to 8s the ambience sustains and eases down.
Cut→S008: Cut to the reading corner.

---

### Segment 4 — Verse 2 repeats and the tidy finale (Scenes 8–9) | 0:28–0:38

**S008 — Make our class untidy, half and half | 0:28–0:32 (4s slot → generate 8s in Flow)**
Song sync: (0:29) "Make our class untidy, make our class untidy"
Step 3 Ingredients: Character & Prop Reference Images: `Priya_Portrait.png`, `Priya_6Angle.png`, `Kavya_Portrait.png`, `Kavya_6Angle.png`, `PaperBits_Portrait.png`, `PaperBits_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A reading corner with beanbags and a rug, half messy and half tidy) · Scene Continuity Reference: `S007_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot of a reading corner in a bright school classroom with sunny yellow walls, wooden desks, a green blackboard with only simple doodles (no writing) and a tiled floor with beanbags and a round rug: the left half is messy with paper bits and scattered books, the right half is neat, and the girls Priya and Kavya standing on the middle line comparing the two sides with playful faces, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S008_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S008_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the lyric beats, the last 4s are spare footage):
I2V from `S008_Ref.png`. 0–2s: the girls look at the messy side and shake their heads on the beat; 2–4s: they look at the tidy side, smile and nod, and the camera pushes in on their faces. 4–8s (spare 4s): the same gentle motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No speech, singing or lip-sync: the girls keep expressive happy or playful faces with closed mouths. Audio is quiet sound effects only; the song is added in the edit.
Sound (SFX only, no music, no voice): Beanbags squishing, paper rustle, a soft comparison 'boing'. From 4s to 8s the ambience sustains and eases down.
Cut→S009: Cut to the centre of the room.

**S009 — Pick them up! The tidy finish | 0:32–0:38 (6s slot → generate 8s in Flow)**
Song sync: (0:33) "Pick them up! Pick them up!" · (0:37) "(முடிவு; ஆடியோ நீளம் மதிப்பீடு)"
Step 3 Ingredients: Character & Prop Reference Images: `Priya_Portrait.png`, `Priya_6Angle.png`, `Kavya_Portrait.png`, `Kavya_6Angle.png`, `PaperBits_Portrait.png`, `PaperBits_6Angle.png`, `CleanupKit_Portrait.png`, `CleanupKit_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: The centre of a sunny, now-tidy classroom floor) · Scene Continuity Reference: `S008_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot at the centre of a bright school classroom with sunny yellow walls, wooden desks, a green blackboard with only simple doodles (no writing) and a tiled floor now tidy and sunlit, the girls Priya and Kavya high-fiving with big proud smiles, a green bin with the last paper bits beside them, sparkles on the clean floor, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S009_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S009_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the lyric beats, the last 2s are spare footage):
I2V from `S009_Ref.png`. 0–2s: the girls pick up the last bits of paper on the beat and drop them into the bin; 2–4s: they high-five and spin around together; 4–6s: they strike a proud pose with thumbs up as sparkles twinkle on the clean floor and the camera cranes up. 6–8s (spare 2s): the same gentle motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched. No speech, singing or lip-sync: the girls keep expressive happy or playful faces with closed mouths. Audio is quiet sound effects only; the song is added in the edit.
Sound (SFX only, no music, no voice): Paper dropping in the bin, a high-five clap, a soft sparkle chime; a gentle whoosh as the camera cranes up. From 6s to 8s the ambience sustains and eases down.
Cut→S010: END: the song ends; fade out over the last second.

---

### Segment 5 — Bonus vibe scenes (use anywhere in the edit) (Scenes 10–15)

**S010 — Bonus 1: hopping over the paper | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any part of the song.
Step 3 Ingredients: Character & Prop Reference Images: `Priya_Portrait.png`, `Priya_6Angle.png`, `Kavya_Portrait.png`, `Kavya_6Angle.png`, `PaperBits_Portrait.png`, `PaperBits_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A school corridor with lockers and polished floor) · Scene Continuity Reference: `S009_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot in a school corridor with colourful lockers and a polished floor: the girls Priya and Kavya with happy faces, hopping over bits of paper scattered along the corridor in rhythm, bits of paper in the scene, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S010_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S010_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S010_Ref.png`. 0–3s: the girls start hopping over bits of paper scattered along the corridor in rhythm, then pointing at them together; 3–6s: they repeat the move with a bigger bounce, smiling at each other in time with the beat; 6–8s: the camera circles them as they strike a cheerful pose and the movement settles. No speech, singing or lip-sync: the girls keep expressive happy or playful faces with closed mouths. Audio is quiet sound effects only; the song is added in the edit.
Sound (SFX only, no music, no voice): Light footsteps, paper rustle and the sound that suits the action (broom sweep, bin thud, pencil taps), soft clapping.
Cut→S011: Use as a cutaway or loop anywhere in the edit.

**S011 — Bonus 2: paper confetti in slow motion | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any part of the song.
Step 3 Ingredients: Character & Prop Reference Images: `Priya_Portrait.png`, `Priya_6Angle.png`, `Kavya_Portrait.png`, `Kavya_6Angle.png`, `PaperBits_Portrait.png`, `PaperBits_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A classroom with a ceiling fan swirling paper bits) · Scene Continuity Reference: `S010_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot in a classroom with a slowly turning ceiling fan: the girls Priya and Kavya with happy faces, laughing as a ceiling fan blows the bits of paper around them in a swirl, bits of paper in the scene, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S011_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S011_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S011_Ref.png`. 0–3s: the girls start laughing as a ceiling fan blows the bits of paper around them in a swirl, their arms reaching up to catch them; 3–6s: they repeat the move with a bigger bounce, smiling at each other in time with the beat; 6–8s: the camera circles them as they strike a cheerful pose and the movement settles. No speech, singing or lip-sync: the girls keep expressive happy or playful faces with closed mouths. Audio is quiet sound effects only; the song is added in the edit.
Sound (SFX only, no music, no voice): Light footsteps, paper rustle and the sound that suits the action (broom sweep, bin thud, pencil taps), soft clapping.
Cut→S012: Use as a cutaway or loop anywhere in the edit.

**S012 — Bonus 3: the sweeping dance | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any part of the song.
Step 3 Ingredients: Character & Prop Reference Images: `Priya_Portrait.png`, `Priya_6Angle.png`, `Kavya_Portrait.png`, `Kavya_6Angle.png`, `PaperBits_Portrait.png`, `PaperBits_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A sunny veranda outside the classroom door) · Scene Continuity Reference: `S011_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot in a sunny veranda outside a classroom door with potted plants: the girls Priya and Kavya with happy faces, dancing a sweeping dance with two small brooms in step, bits of paper in the scene, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S012_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S012_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S012_Ref.png`. 0–3s: the girls start dancing a sweeping dance with two small brooms in step, brushing paper bits into a pile; 3–6s: they repeat the move with a bigger bounce, smiling at each other in time with the beat; 6–8s: the camera circles them as they strike a cheerful pose and the movement settles. No speech, singing or lip-sync: the girls keep expressive happy or playful faces with closed mouths. Audio is quiet sound effects only; the song is added in the edit.
Sound (SFX only, no music, no voice): Light footsteps, paper rustle and the sound that suits the action (broom sweep, bin thud, pencil taps), soft clapping.
Cut→S013: Use as a cutaway or loop anywhere in the edit.

**S013 — Bonus 4: paper in the bin, basketball style | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any part of the song.
Step 3 Ingredients: Character & Prop Reference Images: `Priya_Portrait.png`, `Priya_6Angle.png`, `Kavya_Portrait.png`, `Kavya_6Angle.png`, `PaperBits_Portrait.png`, `PaperBits_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A classroom window seat beside a green bin) · Scene Continuity Reference: `S012_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot in a classroom window seat with a green bin in front of it: the girls Priya and Kavya with happy faces, tossing crumpled paper balls into the green bin one after the other and cheering with raised arms, bits of paper in the scene, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S013_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S013_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S013_Ref.png`. 0–3s: the girls start tossing crumpled paper balls into the green bin one after the other and cheering with raised arms; 3–6s: they repeat the move with a bigger bounce, smiling at each other in time with the beat; 6–8s: the camera circles them as they strike a cheerful pose and the movement settles. No speech, singing or lip-sync: the girls keep expressive happy or playful faces with closed mouths. Audio is quiet sound effects only; the song is added in the edit.
Sound (SFX only, no music, no voice): Light footsteps, paper rustle and the sound that suits the action (broom sweep, bin thud, pencil taps), soft clapping.
Cut→S014: Use as a cutaway or loop anywhere in the edit.

**S014 — Bonus 5: the tidy class glows | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any part of the song.
Step 3 Ingredients: Character & Prop Reference Images: `Priya_Portrait.png`, `Priya_6Angle.png`, `Kavya_Portrait.png`, `Kavya_6Angle.png`, `PaperBits_Portrait.png`, `PaperBits_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A tidy classroom in warm sunset light) · Scene Continuity Reference: `S013_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot in a tidy classroom in warm golden sunset light: the girls Priya and Kavya with happy faces, standing proudly in the middle of the clean room, bits of paper in the scene, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S014_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S014_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S014_Ref.png`. 0–3s: the girls start standing proudly in the middle of the clean room, then spinning and giving a thumbs up together; 3–6s: they repeat the move with a bigger bounce, smiling at each other in time with the beat; 6–8s: the camera circles them as they strike a cheerful pose and the movement settles. No speech, singing or lip-sync: the girls keep expressive happy or playful faces with closed mouths. Audio is quiet sound effects only; the song is added in the edit.
Sound (SFX only, no music, no voice): Light footsteps, paper rustle and the sound that suits the action (broom sweep, bin thud, pencil taps), soft clapping.
Cut→S015: Use as a cutaway or loop anywhere in the edit.

**S015 — Bonus 6: tapping the beat | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any part of the song.
Step 3 Ingredients: Character & Prop Reference Images: `Priya_Portrait.png`, `Priya_6Angle.png`, `Kavya_Portrait.png`, `Kavya_6Angle.png`, `PaperBits_Portrait.png`, `PaperBits_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: Rows of desks in the classroom with pencils) · Scene Continuity Reference: `S014_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot in rows of wooden desks with pencils and notebooks: the girls Priya and Kavya with happy faces, tapping the beat on the desks with pencils and clapping together in rhythm, bits of paper in the scene, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S015_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S015_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S015_Ref.png`. 0–3s: the girls start tapping the beat on the desks with pencils and clapping together in rhythm; 3–6s: they repeat the move with a bigger bounce, smiling at each other in time with the beat; 6–8s: the camera circles them as they strike a cheerful pose and the movement settles. No speech, singing or lip-sync: the girls keep expressive happy or playful faces with closed mouths. Audio is quiet sound effects only; the song is added in the edit.
Sound (SFX only, no music, no voice): Light footsteps, paper rustle and the sound that suits the action (broom sweep, bin thud, pencil taps), soft clapping.
Cut→Use as a cutaway or loop anywhere in the edit.

---

# PRODUCTION NOTES

- **Total required:** 15 reference images (`S001_Ref.png` … `S015_Ref.png`) and 15 videos, one video per image: 9 timed scenes that follow the lyrics plus 6 bonus dance scenes. Plus the Step 1 sheets: 2 girls and 2 props (paper bits, cleanup kit), 4 portraits and 4 six-angle turnarounds (8 images). There are no environment-plate images. Overall: 15 scene images + 8 sheet images = 23 images, and 15 videos.
- **Song length:** you gave timestamps for the singing from 0:04 to 0:29 (four lines repeated twice), and the last "Pick them up, pick them up" begins at 0:29. The audio length was not attached, so I assumed the song ends around 0:37–0:38 and made the timed scenes 38 s long (0:00–0:38). Send me the audio length if it differs and I will adjust the last scene.
- **Song structure (from your timestamps):** 0:00–0:04 intro; 0:04 "Bits of paper… lying on the floor"; 0:13 "Make our class untidy… Pick them up"; 0:21 verse 1 again; 0:29 verse 2 again. Because the timestamps start on odd seconds (0:13, 0:21, 0:29) and clips use even seconds, each new part's visual starts about 1 s before the lyric. This lead-in feels natural; if you want it exact, nudge the clip by 1 s in the edit.
- **Cast rule:** every scene shows exactly the two girls Priya and Kavya plus the bits of paper; the cleanup kit appears in S005 and S009 only. No other people or animals appear.
- **What to generate in Flow (8 s or 10 s only):** every video is generated at 8 s. All timed slots are 4 s or 6 s, so each clip has 2–4 s of spare footage after the lyric beats. The bonus scenes are 8 s. No scene needs 10 s.

| Generate in Flow | Number of videos | Footage | Scenes |
|---|---|---|---|
| 8 s | 15 | 120 s | all scenes S001–S015 |

- **Slot plan (timed scenes):** 4 s slots: S001–S008 (8 clips, 32 s); 6 s slot: S009 (1 clip, 6 s); total 38 s.
- **Timeline rule:** put the song on the timeline at 0:00, drop each timed clip at its scene start time and trim it to its slot. The extra seconds are spare footage. The bonus scenes have no timestamp: use them as cutaways, or loop the song to make a longer video.
- **Making it addictive:** the prompts use bouncy on-the-beat moves (pointing, head shakes, sweeping, high-fives, clapping), colourful paper confetti and a clear mess-to-tidy story, with a quick visual change every 4 s. The song repeats twice, so the second pass (S006–S009) uses different spots and bigger moves so it feels fresh, not repeated.
- **Audio:** generated clips contain only quiet sound effects. They have no music, singing, speech or lip-sync, so your song is the only music and voice. If you want Flow to add its own music or have the girls sing on screen, tell me and I'll change the audio line in the global lock.
- **Image generation is Google Flow only.** Generate the 4 sheets first, then each scene image in order. Video prompts use each scene's saved image as the starting frame.
- **Reminder:** the GLOBAL LOCK BLOCK must be appended in full to the end of every prompt (Step 1, every Step 3 and every Step 4) before submission.
