# SCRIPT 05 — Tick, Bang, Spin: a day-in-the-life song with Ravi, Anu and Divya
### [TEMPLATE v3 — Google Flow only · song slots of 4/6 s, Flow clips generated at 8 s · character and prop sheets → a different spot of the family home per scene → per-scene reference image → per-scene video · global lock appended to every prompt · no on-screen text · consistent visible faces · very quiet SFX only]

**Duration:** about 0:58 (song ≈ 57–58 s, not attached; estimated) | **Total Scenes:** 22 = 22 reference images = 22 videos (13 timed scenes + 9 bonus dance scenes)
**Image generation:** Google Flow only (Step 1 sheets, Step 2 location plan, Step 3 scene reference images)
**Video generation:** Google Flow — one video prompt per scene, each generated as an 8 s clip (a 4 s or 6 s song slot plus spare seconds to trim)
**Payoff:** The three children go through their day, from the clock's "time to start", through the plates' "time to eat", to the fan's "time to sleep", ending asleep and peaceful.
**Dialogue/Audio rule:** The generated clips contain NO voice, singing or music: only very quiet sound effects. Your song is added in the edit.

**Assumptions made for the blank input fields (change if needed):**
- **Style:** 3D animated family-film look (bright, cheerful, child-friendly). Tell me if you want 2D cartoon instead.
- **Characters:** three invented children (the boy Ravi, the girls Anu and Divya) plus three props (wall clock, steel plates, ceiling fan).
- **Hard rules:** no on-screen text or lyrics, no adults, no numerals on the clock, plates only tapped gently.
- **Song length:** estimated; the audio was not attached.

**Segment map**

| # | Segment | Scenes | Time |
|---|---|---|---|
| 1 | Clock verse: tick, tick, tick, it's time to start | S001–S005 | 0:00–0:20 |
| 2 | Plate verse: bang, bang, bang, it's time to eat | S006–S009 | 0:20–0:38 |
| 3 | Fan verse: spin, spin, spin, it's time to sleep | S010–S013 | 0:38–0:58 |
| 4 | Bonus dance scenes (use anywhere in the edit) | S014–S022 | bonus (no timestamp) |

---

## ⚠️ GLOBAL LOCK BLOCK — append this in full to the END of every single prompt below (Step 1, every Step 3, every Step 4)

```
GLOBAL LOCK:
CONTINUITY — Keep Ravi (orange T-shirt, green shorts), Anu (pink flower frock, two buns with pink ribbons), Divya (light-blue kurta, long braid with a yellow ribbon), the yellow wall clock, the steel plates and spoons and the white ceiling fan in exact face, colour, clothing and proportion continuity from their saved reference sheets — no redesign, recolor or scale drift. Every scene takes place in its own different spot of the same warm family home: pastel walls, tiled floors, wooden furniture. Never copy the previous scene's spot, background or composition.
CAST RULE — Every scene shows exactly the three children Ravi, Anu and Divya, plus the prop named in that scene (clock, plates or fan). No adults, no other children, no animals.
STYLE — 3D animated family-film style, bright cheerful colours, soft global illumination, a warm 35mm-lens depth of field, one consistent colour grade (sunny gold by day, cosy lamp amber and soft moonlight blue at night), smooth appealing character animation with natural squash and stretch, expressive faces and bouncy, in-rhythm dance moves that land on the beat of a catchy song.
HARD RULES — No on-screen text, captions, lyrics, logos or watermarks; the clock face has only dot marks and no numerals. Fully child-friendly and safe: plates are only gently tapped, never thrown or dropped hard; no scary or dangerous content. The children always have clear, fully visible, expressive faces matching their sheets in every shot; faces never morph between shots.
ZERO AI ARTIFACTS — No morphing, warping, melting, flicker, extra or duplicated limbs, hands, fingers, fan blades or characters, floating debris, texture smearing, distorted hands or feet.
LIGHTING — Follow the time of day and light written in each scene's prompt; no sudden unintended light jumps inside a shot.
AUDIO — Generated audio is ONLY very quiet diegetic sound effects (footsteps, fabric, soft taps, fan whirr, ambience), never louder than the room tone. No music, no singing, no speech, no lip-sync, and no loud ticks, bangs or whooshes: the song, with its tick, bang and spin sounds, is added in the edit. The children keep expressive faces with closed mouths.
CAMERA — Smooth, physically plausible motion only; each shot's opening camera motion matches the previous shot's closing motion vector for a seamless cut.
```

---

# STEP 1 — CHARACTER & PROP REFERENCE IMAGES (Google Flow — image generation ONLY)

### 1A. Boy ("Ravi")
**Portrait Image Prompt — Google Flow:**
Full-body portrait of a 7-year-old Tamil boy named Ravi standing in a happy relaxed pose, facing the camera, with a clearly visible, fully expressive animated face: warm brown skin, round cheeks, big dark sparkling eyes, short black hair that sticks up a little at the front, a cheeky wide grin. Orange T-shirt, green shorts, bare feet. 3D animated family-film style, bright cheerful colours, soft global illumination. Neutral light-grey background, soft key light, clean readable shapes. Locked reference design.
**Save as:** `Ravi_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Ravi_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) locking the face.
**Save as:** `Ravi_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S001–S022.

### 1B. Girl 1 (the youngest) ("Anu")
**Portrait Image Prompt — Google Flow:**
Full-body portrait of a 6-year-old Tamil girl named Anu standing in a happy relaxed pose, facing the camera, with a clearly visible, fully expressive animated face: medium-brown skin, rosy cheeks, big bright brown eyes, two small black hair buns tied with pink ribbons, a sweet gap-toothed smile. A pink frock with small white flowers, bare feet. 3D animated family-film style, bright cheerful colours, soft global illumination. Neutral light-grey background, soft key light. Locked reference design.
**Save as:** `Anu_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Anu_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) locking the face.
**Save as:** `Anu_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S001–S022.

### 1C. Girl 2 (the eldest) ("Divya")
**Portrait Image Prompt — Google Flow:**
Full-body portrait of an 8-year-old Tamil girl named Divya standing in a happy relaxed pose, facing the camera, with a clearly visible, fully expressive animated face: warm brown skin, warm dark eyes, a gentle confident smile, a long black braid tied with a yellow ribbon. A light-blue kurta with white leggings, bare feet. 3D animated family-film style, bright cheerful colours, soft global illumination. Neutral light-grey background, soft key light. Locked reference design.
**Save as:** `Divya_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Divya_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) locking the face.
**Save as:** `Divya_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S001–S022.

### 1D. Wall Clock (prop) ("WallClock")
**Portrait Image Prompt — Google Flow:**
A big friendly round wall clock with a thick yellow frame, a plain white face with only small dot marks instead of numbers (no text or numerals), a short blue hour hand, a longer blue minute hand and a thin red second hand, shown hanging on a plain wall. 3D animated family-film style, bright cheerful colours, soft global illumination. Neutral light-grey background, soft key light. Locked reference design.
**Save as:** `WallClock_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `WallClock_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up detail panels.
**Save as:** `WallClock_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S002–S005, S014–S016.

### 1E. Steel Plates and Spoons (prop) ("SteelPlates")
**Portrait Image Prompt — Google Flow:**
Three shiny round stainless-steel dining plates with raised rims and three steel spoons, stacked and laid out neatly on a woven straw mat, soft reflections, a few small dents for character. 3D animated family-film style, bright cheerful colours, soft global illumination. Neutral light-grey background, soft key light. Locked reference design.
**Save as:** `SteelPlates_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `SteelPlates_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up detail panels.
**Save as:** `SteelPlates_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S006–S009, S017–S019.

### 1F. Ceiling Fan (prop) ("CeilingFan")
**Portrait Image Prompt — Google Flow:**
A white three-blade ceiling fan with a short rod and a round motor housing, hanging from a plain ceiling, shown from slightly below with the blades still and clean, no text or logos. 3D animated family-film style, bright cheerful colours, soft global illumination. Neutral light-grey background, soft key light. Locked reference design.
**Save as:** `CeilingFan_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `CeilingFan_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up detail panels.
**Save as:** `CeilingFan_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S010–S013, S020–S022.

---

# STEP 2 — LOCATION PLAN (no reusable environment plates: every scene is a different spot of the same family home)

There are no shared environment-plate images. Each scene's Step 3 prompt describes its own spot, and `Environment Reference Image` is `none`. All spots belong to the same warm family home, so the look stays consistent. The table lists every scene's spot so you can check none repeats.

| Scene | Time | Slot | Flow clip | Unique location |
|---|---|---|---|---|
| S001 | 0:00–0:04 | 4s | 8 s | A sunny bedroom at dawn with three sleeping mats on the floor |
| S002 | 0:04–0:08 | 4s | 8 s | A living-room wall with a big friendly wall clock in morning light |
| S003 | 0:08–0:12 | 4s | 8 s | A staircase landing with a window and a small wall clock |
| S004 | 0:12–0:16 | 4s | 8 s | A study corner with a small desk, school bags and a clock on the shelf |
| S005 | 0:16–0:20 | 4s | 8 s | The front veranda and door of the house in bright morning light |
| S006 | 0:20–0:26 | 6s | 8 s | A kitchen floor with straw mats and shiny steel plates |
| S007 | 0:26–0:30 | 4s | 8 s | A sunny courtyard with a tulsi plant and a small well |
| S008 | 0:30–0:34 | 4s | 8 s | A dining area with a low wooden table in warm light |
| S009 | 0:34–0:38 | 4s | 8 s | A veranda lunch mat with steaming rice and curry |
| S010 | 0:38–0:42 | 4s | 8 s | The hall at dusk, a ceiling fan seen from below |
| S011 | 0:42–0:48 | 6s | 8 s | A cosy bedroom with a ceiling fan and swaying curtains |
| S012 | 0:48–0:52 | 4s | 8 s | A living room at night with a lamp and a ceiling fan, children on a sofa |
| S013 | 0:52–0:58 | 6s | 8 s | The hall floor with three sleeping mats under a slowly spinning fan, moonlight |
| S014 | bonus (no timestamp) | none | 8 s | A cosy hallway with a tall grandfather clock |
| S015 | bonus (no timestamp) | none | 8 s | A rooftop terrace at sunrise with water tanks and kites |
| S016 | bonus (no timestamp) | none | 8 s | A playroom in the attic with a wooden cuckoo clock |
| S017 | bonus (no timestamp) | none | 8 s | A kitchen with a hanging rack of steel utensils |
| S018 | bonus (no timestamp) | none | 8 s | A backyard with a clothesline and bright sheets |
| S019 | bonus (no timestamp) | none | 8 s | A veranda with a wooden swing seat |
| S020 | bonus (no timestamp) | none | 8 s | A big hall with a ceiling fan and a rug |
| S021 | bonus (no timestamp) | none | 8 s | A balcony with a wind-chime and a stand fan |
| S022 | bonus (no timestamp) | none | 8 s | A bedroom with floating paper pinwheels on a string |

---

# STEP 3 & STEP 4 — SCENES (song slots of 4 and 6 seconds; every Flow video is generated at 8 seconds)

**How each scene is shaped:**
Header line (scene number, label, time range and slot) → **Song sync** (editor note only, never paste into Flow) → Step 3 Ingredients → Step 3 Reference Image Prompt → Step 4 Ingredients → Video Prompt (Google Flow, generated at 8 s; second marks relative to the clip start, the lyric beats first and spare seconds after) → Sound → Cut→.
Append the GLOBAL LOCK BLOCK to the end of every Step 3 and Step 4 prompt.

---

### Segment 1 — Clock verse: tick, tick, tick, it's time to start (Scenes 1–5) | 0:00–0:20

**S001 — Good morning: the children wake up | 0:00–0:04 (4s slot → generate 8s in Flow)**
Song sync: (0:00) "(அறிமுகம்; பாடல் 0:04-க்குத் தொடங்குகிறது)"
Step 3 Ingredients: Character & Prop Reference Images: `Ravi_Portrait.png`, `Ravi_6Angle.png`, `Anu_Portrait.png`, `Anu_6Angle.png`, `Divya_Portrait.png`, `Divya_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A sunny bedroom at dawn with three sleeping mats on the floor) · Scene Continuity Reference: none (first scene in the series)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot in a sunny bedroom at dawn in a warm, colourful Indian family home with pastel walls, tiled floors and wooden furniture: the children Ravi, Anu and Divya sitting up on three sleeping mats, stretching their arms with sleepy smiling faces, golden sunlight through a window, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S001_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S001_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the lyric beats, the last 4s are spare footage):
I2V from `S001_Ref.png`. 0–2s: the camera pushes in slowly as the three children stretch their arms up and yawn with big smiles; 2–4s: they spring up together and bounce on their toes. 4–8s (spare 4s): the same gentle motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No speech, singing or lip-sync: the children keep expressive happy faces with closed mouths. Audio is very quiet sound effects only; the song is added in the edit.
Sound (very quiet SFX only, no music, no voice): Soft fabric rustle, bare feet on the floor, quiet morning birdsong. From 4s to 8s the ambience sustains and eases down.
Cut→S002: Cut to the clock on the wall.

**S002 — The clock goes tick, tick, tick | 0:04–0:08 (4s slot → generate 8s in Flow)**
Song sync: (0:04) "The clock on the wall goes tick, tick, tick, tick, tick, tick"
Step 3 Ingredients: Character & Prop Reference Images: `Ravi_Portrait.png`, `Ravi_6Angle.png`, `Anu_Portrait.png`, `Anu_6Angle.png`, `Divya_Portrait.png`, `Divya_6Angle.png`, `WallClock_Portrait.png`, `WallClock_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A living-room wall with a big friendly wall clock in morning light) · Scene Continuity Reference: `S001_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Medium shot in the living room of a warm, colourful Indian family home with pastel walls, tiled floors and wooden furniture: a big round yellow-framed wall clock with a plain white face and a red second hand, and the children Ravi, Anu and Divya standing below it pointing up with delighted faces, morning sunlight on the wall, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S002_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S002_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the lyric beats, the last 4s are spare footage):
I2V from `S002_Ref.png`. 0–2s: the camera pushes in on the clock as the red second hand jumps in steps and the children point at it one after another; 2–4s: the children bounce in time with the jumping hand, nodding their heads. 4–8s (spare 4s): the same gentle motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No speech, singing or lip-sync: the children keep expressive happy faces with closed mouths. Audio is very quiet sound effects only; the song is added in the edit.
Sound (very quiet SFX only, no music, no voice): Very soft clock-mechanism creaks, quiet footsteps, a gentle morning ambience. From 4s to 8s the ambience sustains and eases down.
Cut→S003: Cut to a staircase landing.

**S003 — Ticking like clock hands | 0:08–0:12 (4s slot → generate 8s in Flow)**
Song sync: (0:08) "tick, tick, tick, tick, tick, tick"
Step 3 Ingredients: Character & Prop Reference Images: `Ravi_Portrait.png`, `Ravi_6Angle.png`, `Anu_Portrait.png`, `Anu_6Angle.png`, `Divya_Portrait.png`, `Divya_6Angle.png`, `WallClock_Portrait.png`, `WallClock_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A staircase landing with a window and a small wall clock) · Scene Continuity Reference: `S002_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Medium shot on a bright staircase landing in a warm, colourful Indian family home with pastel walls, tiled floors and wooden furniture with a window and the yellow wall clock on the wall: the children Ravi, Anu and Divya in a line swinging their arms side to side like clock hands, big grins, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S003_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S003_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the lyric beats, the last 4s are spare footage):
I2V from `S003_Ref.png`. 0–2s: the children swing their arms from side to side like pendulums in rhythm; 2–4s: they march on the spot with sharp little steps in time with the beat as the clock's second hand ticks behind them. 4–8s (spare 4s): the same gentle motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No speech, singing or lip-sync: the children keep expressive happy faces with closed mouths. Audio is very quiet sound effects only; the song is added in the edit.
Sound (very quiet SFX only, no music, no voice): Soft quick footsteps on tiles, a cloth swish; a barely audible clock mechanism. From 4s to 8s the ambience sustains and eases down.
Cut→S004: Cut to a study corner.

**S004 — The clock goes tick, tick, tick: getting ready | 0:12–0:16 (4s slot → generate 8s in Flow)**
Song sync: (0:13) "The clock on the wall goes tick, tick, tick"
Step 3 Ingredients: Character & Prop Reference Images: `Ravi_Portrait.png`, `Ravi_6Angle.png`, `Anu_Portrait.png`, `Anu_6Angle.png`, `Divya_Portrait.png`, `Divya_6Angle.png`, `WallClock_Portrait.png`, `WallClock_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A study corner with a small desk, school bags and a clock on the shelf) · Scene Continuity Reference: `S003_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Medium shot of a study corner in a warm, colourful Indian family home with pastel walls, tiled floors and wooden furniture with a small desk, three school bags and a small yellow clock on a shelf: the children Ravi, Anu and Divya hurrying cheerfully to pack their bags, bouncing as they work, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S004_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S004_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the lyric beats, the last 4s are spare footage):
I2V from `S004_Ref.png`. 0–2s: the children zip up their bags in quick rhythm, bobbing their heads on the beat; 2–4s: they swing the bags onto their backs with a happy hop and turn toward the door. 4–8s (spare 4s): the same gentle motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No speech, singing or lip-sync: the children keep expressive happy faces with closed mouths. Audio is very quiet sound effects only; the song is added in the edit.
Sound (very quiet SFX only, no music, no voice): Zip sounds, bags thumping softly, light footsteps. From 4s to 8s the ambience sustains and eases down.
Cut→S005: Cut to the front door.

**S005 — It's time to start! | 0:16–0:20 (4s slot → generate 8s in Flow)**
Song sync: (0:17) "It's time to start!"
Step 3 Ingredients: Character & Prop Reference Images: `Ravi_Portrait.png`, `Ravi_6Angle.png`, `Anu_Portrait.png`, `Anu_6Angle.png`, `Divya_Portrait.png`, `Divya_6Angle.png`, `WallClock_Portrait.png`, `WallClock_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: The front veranda and door of the house in bright morning light) · Scene Continuity Reference: `S004_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot from inside the doorway of the front veranda of a warm, colourful Indian family home with pastel walls, tiled floors and wooden furniture in bright morning light: the children Ravi, Anu and Divya running out of the door with their school bags and big excited smiles, thumbs up, with the wall clock visible on the wall behind, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S005_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S005_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the lyric beats, the last 4s are spare footage):
I2V from `S005_Ref.png`. 0–2s: the children burst out of the door into the sunshine with thumbs up; 2–4s: they spin and skip along the veranda in a line as the camera tracks backwards ahead of them. 4–8s (spare 4s): the same gentle motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No speech, singing or lip-sync: the children keep expressive happy faces with closed mouths. Audio is very quiet sound effects only; the song is added in the edit.
Sound (very quiet SFX only, no music, no voice): Quick footsteps, a door swinging open, birdsong. From 4s to 8s the ambience sustains and eases down.
Cut→S006: Cut to the kitchen mat.

---

### Segment 2 — Plate verse: bang, bang, bang, it's time to eat (Scenes 6–9) | 0:20–0:38

**S006 — The plate goes bang, bang, bang | 0:20–0:26 (6s slot → generate 8s in Flow)**
Song sync: (0:21) "The plate on the floor goes bang, bang, bang, bang, bang, bang, bang, bang"
Step 3 Ingredients: Character & Prop Reference Images: `Ravi_Portrait.png`, `Ravi_6Angle.png`, `Anu_Portrait.png`, `Anu_6Angle.png`, `Divya_Portrait.png`, `Divya_6Angle.png`, `SteelPlates_Portrait.png`, `SteelPlates_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A kitchen floor with straw mats and shiny steel plates) · Scene Continuity Reference: `S005_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Medium shot on the floor of a bright kitchen in a warm, colourful Indian family home with pastel walls, tiled floors and wooden furniture with straw mats and a row of shiny steel plates and spoons: the children Ravi, Anu and Divya sitting around the plates, each tapping a plate with a spoon and grinning, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S006_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S006_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the lyric beats, the last 2s are spare footage):
I2V from `S006_Ref.png`. 0–2s: the children start tapping their plates with the spoons in a steady beat, bobbing their heads; 2–4s: the beat gets faster and their shoulders bounce; 4–6s: they pause and raise their spoons in the air with big laughs, then tap again. 6–8s (spare 2s): the same gentle motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched. No speech, singing or lip-sync: the children keep expressive happy faces with closed mouths. Audio is very quiet sound effects only; the song is added in the edit.
Sound (very quiet SFX only, no music, no voice): Very soft spoon-on-steel taps, kitchen ambience, light breathing. From 6s to 8s the ambience sustains and eases down.
Cut→S007: Cut to the courtyard.

**S007 — Dancing with the plates | 0:26–0:30 (4s slot → generate 8s in Flow)**
Song sync: (0:26) "bang, bang, bang, bang"
Step 3 Ingredients: Character & Prop Reference Images: `Ravi_Portrait.png`, `Ravi_6Angle.png`, `Anu_Portrait.png`, `Anu_6Angle.png`, `Divya_Portrait.png`, `Divya_6Angle.png`, `SteelPlates_Portrait.png`, `SteelPlates_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A sunny courtyard with a tulsi plant and a small well) · Scene Continuity Reference: `S006_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Medium shot in a sunny courtyard of a warm, colourful Indian family home with pastel walls, tiled floors and wooden furniture with a tulsi plant and a small stone well: the children Ravi, Anu and Divya dancing and bouncing while holding their steel plates in front of them like drums, joyful faces, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S007_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S007_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the lyric beats, the last 4s are spare footage):
I2V from `S007_Ref.png`. 0–2s: the children bounce and tap the plates with their hands on the beat; 2–4s: they spin once and tap the plates together in the air, with big happy smiles. 4–8s (spare 4s): the same gentle motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No speech, singing or lip-sync: the children keep expressive happy faces with closed mouths. Audio is very quiet sound effects only; the song is added in the edit.
Sound (very quiet SFX only, no music, no voice): Soft plate taps, bare feet on stone, a breeze in the leaves. From 4s to 8s the ambience sustains and eases down.
Cut→S008: Cut to the dining area.

**S008 — The plate goes bang, bang, bang | 0:30–0:34 (4s slot → generate 8s in Flow)**
Song sync: (0:30) "The plate on the floor goes bang, bang, bang"
Step 3 Ingredients: Character & Prop Reference Images: `Ravi_Portrait.png`, `Ravi_6Angle.png`, `Anu_Portrait.png`, `Anu_6Angle.png`, `Divya_Portrait.png`, `Divya_6Angle.png`, `SteelPlates_Portrait.png`, `SteelPlates_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A dining area with a low wooden table in warm light) · Scene Continuity Reference: `S007_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Medium shot in a dining area of a warm, colourful Indian family home with pastel walls, tiled floors and wooden furniture with a low wooden table in warm light: the children Ravi, Anu and Divya sitting on the floor each patting their steel plate lying on the mat in front of them, bright expectant faces, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S008_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S008_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the lyric beats, the last 4s are spare footage):
I2V from `S008_Ref.png`. 0–2s: the children pat the plates in a three-beat pattern together; 2–4s: they repeat it with bigger arm swings and a happy shoulder bounce. 4–8s (spare 4s): the same gentle motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No speech, singing or lip-sync: the children keep expressive happy faces with closed mouths. Audio is very quiet sound effects only; the song is added in the edit.
Sound (very quiet SFX only, no music, no voice): Soft pats on steel, a gentle room tone. From 4s to 8s the ambience sustains and eases down.
Cut→S009: Cut to the veranda lunch mat.

**S009 — It's time to eat! | 0:34–0:38 (4s slot → generate 8s in Flow)**
Song sync: (0:34) "It's time to eat!"
Step 3 Ingredients: Character & Prop Reference Images: `Ravi_Portrait.png`, `Ravi_6Angle.png`, `Anu_Portrait.png`, `Anu_6Angle.png`, `Divya_Portrait.png`, `Divya_6Angle.png`, `SteelPlates_Portrait.png`, `SteelPlates_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A veranda lunch mat with steaming rice and curry) · Scene Continuity Reference: `S008_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Medium shot on a cosy veranda of a warm, colourful Indian family home with pastel walls, tiled floors and wooden furniture at lunchtime: the children Ravi, Anu and Divya sitting cross-legged on a mat, each with a steel plate of steaming rice and a bowl of curry, rubbing their tummies with huge delighted smiles, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S009_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S009_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the lyric beats, the last 4s are spare footage):
I2V from `S009_Ref.png`. 0–2s: the children rub their tummies and lean toward the plates sniffing the steam; 2–4s: they lift their spoons together and cheer with their arms up. 4–8s (spare 4s): the same gentle motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No speech, singing or lip-sync: the children keep expressive happy faces with closed mouths. Audio is very quiet sound effects only; the song is added in the edit.
Sound (very quiet SFX only, no music, no voice): Soft spoons on steel, a light sizzle of curry, a gentle veranda ambience. From 4s to 8s the ambience sustains and eases down.
Cut→S010: Cut to the hall at dusk.

---

### Segment 3 — Fan verse: spin, spin, spin, it's time to sleep (Scenes 10–13) | 0:38–0:58

**S010 — The fan goes spin, spin, spin | 0:38–0:42 (4s slot → generate 8s in Flow)**
Song sync: (0:38) "The fan in the hall goes spin, spin, spin"
Step 3 Ingredients: Character & Prop Reference Images: `Ravi_Portrait.png`, `Ravi_6Angle.png`, `Anu_Portrait.png`, `Anu_6Angle.png`, `Divya_Portrait.png`, `Divya_6Angle.png`, `CeilingFan_Portrait.png`, `CeilingFan_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: The hall at dusk, a ceiling fan seen from below) · Scene Continuity Reference: `S009_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Low-angle shot looking up from the floor of the hall of a warm, colourful Indian family home with pastel walls, tiled floors and wooden furniture at dusk to a white ceiling fan spinning, with the children Ravi, Anu and Divya lying on their backs in a circle around the centre with their heads toward the fan, delighted faces, warm lamp light, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S010_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S010_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the lyric beats, the last 4s are spare footage):
I2V from `S010_Ref.png`. 0–2s: the camera holds low as the fan blades spin and the children's hair and shirts flutter; 2–4s: the children raise their arms and spin their hands in circles in time with the fan. 4–8s (spare 4s): the same gentle motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No speech, singing or lip-sync: the children keep expressive happy faces with closed mouths. Audio is very quiet sound effects only; the song is added in the edit.
Sound (very quiet SFX only, no music, no voice): A soft fan whirr, fabric fluttering, light breathing. From 4s to 8s the ambience sustains and eases down.
Cut→S011: Cut to a bedroom with curtains.

**S011 — Spin, spin, spin: twirling | 0:42–0:48 (6s slot → generate 8s in Flow)**
Song sync: (0:42) "Spin, spin, spin, spin, spin, spin"
Step 3 Ingredients: Character & Prop Reference Images: `Ravi_Portrait.png`, `Ravi_6Angle.png`, `Anu_Portrait.png`, `Anu_6Angle.png`, `Divya_Portrait.png`, `Divya_6Angle.png`, `CeilingFan_Portrait.png`, `CeilingFan_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A cosy bedroom with a ceiling fan and swaying curtains) · Scene Continuity Reference: `S010_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Medium shot in a cosy bedroom of a warm, colourful Indian family home with pastel walls, tiled floors and wooden furniture with a spinning ceiling fan and swaying curtains: the children Ravi, Anu and Divya twirling slowly with their arms out like fan blades, dreamy smiling faces, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S011_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S011_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the lyric beats, the last 2s are spare footage):
I2V from `S011_Ref.png`. 0–2s: the children start to twirl slowly with arms out; 2–4s: they spin faster in circles as the curtains billow; 4–6s: they slow down and wobble with sleepy smiles, still turning gently. 6–8s (spare 2s): the same gentle motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched. No speech, singing or lip-sync: the children keep expressive happy faces with closed mouths. Audio is very quiet sound effects only; the song is added in the edit.
Sound (very quiet SFX only, no music, no voice): A gentle fan whirr, curtain flutter, soft footsteps. From 6s to 8s the ambience sustains and eases down.
Cut→S012: Cut to the living room at night.

**S012 — The fan goes spin, spin, spin: getting sleepy | 0:48–0:52 (4s slot → generate 8s in Flow)**
Song sync: (0:48) "The fan in the hall goes spin, spin, spin"
Step 3 Ingredients: Character & Prop Reference Images: `Ravi_Portrait.png`, `Ravi_6Angle.png`, `Anu_Portrait.png`, `Anu_6Angle.png`, `Divya_Portrait.png`, `Divya_6Angle.png`, `CeilingFan_Portrait.png`, `CeilingFan_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A living room at night with a lamp and a ceiling fan, children on a sofa) · Scene Continuity Reference: `S011_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Medium shot in a living room of a warm, colourful Indian family home with pastel walls, tiled floors and wooden furniture at night lit by a small lamp: the children Ravi, Anu and Divya snuggled on a sofa under a gently spinning ceiling fan, yawning with heavy-lidded sleepy eyes, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S012_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S012_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the lyric beats, the last 4s are spare footage):
I2V from `S012_Ref.png`. 0–2s: the children yawn in turn and rub their eyes as the fan spins above; 2–4s: they lean their heads on each other's shoulders and their eyelids droop. 4–8s (spare 4s): the same gentle motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No speech, singing or lip-sync: the children keep expressive happy faces with closed mouths. Audio is very quiet sound effects only; the song is added in the edit.
Sound (very quiet SFX only, no music, no voice): A soft fan whirr, a sofa cushion rustle, quiet crickets outside. From 4s to 8s the ambience sustains and eases down.
Cut→S013: Cut to the hall mats.

**S013 — It's time to sleep | 0:52–0:58 (6s slot → generate 8s in Flow)**
Song sync: (0:52) "It's time to sleep"
Step 3 Ingredients: Character & Prop Reference Images: `Ravi_Portrait.png`, `Ravi_6Angle.png`, `Anu_Portrait.png`, `Anu_6Angle.png`, `Divya_Portrait.png`, `Divya_6Angle.png`, `CeilingFan_Portrait.png`, `CeilingFan_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: The hall floor with three sleeping mats under a slowly spinning fan, moonlight) · Scene Continuity Reference: `S012_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot of the hall of a warm, colourful Indian family home with pastel walls, tiled floors and wooden furniture at night in soft moonlight: the children Ravi, Anu and Divya fast asleep with peaceful smiles on three sleeping mats with light blankets, a ceiling fan turning slowly above, a night lamp glowing, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S013_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S013_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the lyric beats, the last 2s are spare footage):
I2V from `S013_Ref.png`. 0–2s: the camera slowly pushes in as the fan turns gently above the sleeping children; 2–4s: a blanket rises and falls with their slow breathing and a night-lamp glow softens; 4–6s: the camera tilts up to the slowly turning fan and the room dims toward a peaceful close. 6–8s (spare 2s): the same gentle motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched. No speech, singing or lip-sync: the children keep expressive happy faces with closed mouths. Audio is very quiet sound effects only; the song is added in the edit.
Sound (very quiet SFX only, no music, no voice): A very soft fan whirr, slow breathing, crickets outside, a gentle chime at the end. From 6s to 8s the ambience sustains and eases down.
Cut→S014: END: the song ends; fade out over the last second.

---

### Segment 4 — Bonus dance scenes (use anywhere in the edit) (Scenes 14–22)

**S014 — Bonus 1: the pendulum dance | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any part of the song.
Step 3 Ingredients: Character & Prop Reference Images: `Ravi_Portrait.png`, `Ravi_6Angle.png`, `Anu_Portrait.png`, `Anu_6Angle.png`, `Divya_Portrait.png`, `Divya_6Angle.png`, `WallClock_Portrait.png`, `WallClock_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A cosy hallway with a tall grandfather clock) · Scene Continuity Reference: `S013_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot in a cosy hallway with a tall wooden grandfather clock, in a warm, colourful Indian family home with pastel walls, tiled floors and wooden furniture: the children Ravi, Anu and Divya with joyful faces ready to dance, in a playful start pose, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S014_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S014_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S014_Ref.png`. 0–3s: the children start dancing to a bouncy beat, swaying from side to side like clock pendulums in a row, then marching tick-tock steps; 3–6s: they repeat the move with a bigger bounce, smiling at each other in time with the beat; 6–8s: the camera circles them as they strike a cheerful pose and the movement settles. No speech, singing or lip-sync: the children keep expressive happy faces with closed mouths. Audio is very quiet sound effects only; the song is added in the edit.
Sound (very quiet SFX only, no music, no voice): Light footsteps and fabric swish with the quiet sound that suits the action; gentle ambience; nothing louder than the room tone.
Cut→S015: Use as a cutaway or loop anywhere in the edit.

**S015 — Bonus 2: marching at sunrise | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any part of the song.
Step 3 Ingredients: Character & Prop Reference Images: `Ravi_Portrait.png`, `Ravi_6Angle.png`, `Anu_Portrait.png`, `Anu_6Angle.png`, `Divya_Portrait.png`, `Divya_6Angle.png`, `WallClock_Portrait.png`, `WallClock_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A rooftop terrace at sunrise with water tanks and kites) · Scene Continuity Reference: `S014_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot in a rooftop terrace at sunrise with water tanks and kites on a line, in a warm, colourful Indian family home with pastel walls, tiled floors and wooden furniture: the children Ravi, Anu and Divya with joyful faces ready to dance, in a playful start pose, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S015_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S015_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S015_Ref.png`. 0–3s: the children start dancing to a bouncy beat, marching in a line with high knees and swinging arms in sharp rhythm, then spinning around together; 3–6s: they repeat the move with a bigger bounce, smiling at each other in time with the beat; 6–8s: the camera circles them as they strike a cheerful pose and the movement settles. No speech, singing or lip-sync: the children keep expressive happy faces with closed mouths. Audio is very quiet sound effects only; the song is added in the edit.
Sound (very quiet SFX only, no music, no voice): Light footsteps and fabric swish with the quiet sound that suits the action; gentle ambience; nothing louder than the room tone.
Cut→S016: Use as a cutaway or loop anywhere in the edit.

**S016 — Bonus 3: the cuckoo hop | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any part of the song.
Step 3 Ingredients: Character & Prop Reference Images: `Ravi_Portrait.png`, `Ravi_6Angle.png`, `Anu_Portrait.png`, `Anu_6Angle.png`, `Divya_Portrait.png`, `Divya_6Angle.png`, `WallClock_Portrait.png`, `WallClock_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A playroom in the attic with a wooden cuckoo clock) · Scene Continuity Reference: `S015_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot in an attic playroom with a wooden cuckoo clock on the wall, in a warm, colourful Indian family home with pastel walls, tiled floors and wooden furniture: the children Ravi, Anu and Divya with joyful faces ready to dance, in a playful start pose, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S016_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S016_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S016_Ref.png`. 0–3s: the children start dancing to a bouncy beat, hopping and clapping each time a little wooden bird pops out of the clock, then bowing together; 3–6s: they repeat the move with a bigger bounce, smiling at each other in time with the beat; 6–8s: the camera circles them as they strike a cheerful pose and the movement settles. No speech, singing or lip-sync: the children keep expressive happy faces with closed mouths. Audio is very quiet sound effects only; the song is added in the edit.
Sound (very quiet SFX only, no music, no voice): Light footsteps and fabric swish with the quiet sound that suits the action; gentle ambience; nothing louder than the room tone.
Cut→S017: Use as a cutaway or loop anywhere in the edit.

**S017 — Bonus 4: the kitchen drum band | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any part of the song.
Step 3 Ingredients: Character & Prop Reference Images: `Ravi_Portrait.png`, `Ravi_6Angle.png`, `Anu_Portrait.png`, `Anu_6Angle.png`, `Divya_Portrait.png`, `Divya_6Angle.png`, `SteelPlates_Portrait.png`, `SteelPlates_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A kitchen with a hanging rack of steel utensils) · Scene Continuity Reference: `S016_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot in a bright kitchen with a hanging rack of steel utensils and a mat on the floor, in a warm, colourful Indian family home with pastel walls, tiled floors and wooden furniture: the children Ravi, Anu and Divya with joyful faces ready to dance, in a playful start pose, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S017_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S017_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S017_Ref.png`. 0–3s: the children start dancing to a bouncy beat, drumming a beat on steel plates and pots with wooden spoons, bobbing and grinning; 3–6s: they repeat the move with a bigger bounce, smiling at each other in time with the beat; 6–8s: the camera circles them as they strike a cheerful pose and the movement settles. No speech, singing or lip-sync: the children keep expressive happy faces with closed mouths. Audio is very quiet sound effects only; the song is added in the edit.
Sound (very quiet SFX only, no music, no voice): Light footsteps and fabric swish with the quiet sound that suits the action; gentle ambience; nothing louder than the room tone.
Cut→S018: Use as a cutaway or loop anywhere in the edit.

**S018 — Bonus 5: plate cymbals in the yard | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any part of the song.
Step 3 Ingredients: Character & Prop Reference Images: `Ravi_Portrait.png`, `Ravi_6Angle.png`, `Anu_Portrait.png`, `Anu_6Angle.png`, `Divya_Portrait.png`, `Divya_6Angle.png`, `SteelPlates_Portrait.png`, `SteelPlates_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A backyard with a clothesline and bright sheets) · Scene Continuity Reference: `S017_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot in a sunny backyard with a clothesline and bright hanging sheets, in a warm, colourful Indian family home with pastel walls, tiled floors and wooden furniture: the children Ravi, Anu and Divya with joyful faces ready to dance, in a playful start pose, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S018_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S018_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S018_Ref.png`. 0–3s: the children start dancing to a bouncy beat, clapping two steel plates together like cymbals in a dance, then twirling with the plates held high; 3–6s: they repeat the move with a bigger bounce, smiling at each other in time with the beat; 6–8s: the camera circles them as they strike a cheerful pose and the movement settles. No speech, singing or lip-sync: the children keep expressive happy faces with closed mouths. Audio is very quiet sound effects only; the song is added in the edit.
Sound (very quiet SFX only, no music, no voice): Light footsteps and fabric swish with the quiet sound that suits the action; gentle ambience; nothing louder than the room tone.
Cut→S019: Use as a cutaway or loop anywhere in the edit.

**S019 — Bonus 6: the swing-seat beat | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any part of the song.
Step 3 Ingredients: Character & Prop Reference Images: `Ravi_Portrait.png`, `Ravi_6Angle.png`, `Anu_Portrait.png`, `Anu_6Angle.png`, `Divya_Portrait.png`, `Divya_6Angle.png`, `SteelPlates_Portrait.png`, `SteelPlates_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A veranda with a wooden swing seat) · Scene Continuity Reference: `S018_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot in a veranda with a wooden swing seat and hanging plants, in a warm, colourful Indian family home with pastel walls, tiled floors and wooden furniture: the children Ravi, Anu and Divya with joyful faces ready to dance, in a playful start pose, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S019_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S019_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S019_Ref.png`. 0–3s: the children start dancing to a bouncy beat, sitting on the swing seat tapping plates on their knees to the beat and swaying side to side; 3–6s: they repeat the move with a bigger bounce, smiling at each other in time with the beat; 6–8s: the camera circles them as they strike a cheerful pose and the movement settles. No speech, singing or lip-sync: the children keep expressive happy faces with closed mouths. Audio is very quiet sound effects only; the song is added in the edit.
Sound (very quiet SFX only, no music, no voice): Light footsteps and fabric swish with the quiet sound that suits the action; gentle ambience; nothing louder than the room tone.
Cut→S020: Use as a cutaway or loop anywhere in the edit.

**S020 — Bonus 7: ribbon twirl under the fan | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any part of the song.
Step 3 Ingredients: Character & Prop Reference Images: `Ravi_Portrait.png`, `Ravi_6Angle.png`, `Anu_Portrait.png`, `Anu_6Angle.png`, `Divya_Portrait.png`, `Divya_6Angle.png`, `CeilingFan_Portrait.png`, `CeilingFan_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A big hall with a ceiling fan and a rug) · Scene Continuity Reference: `S019_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot in a big hall with a large ceiling fan and a colourful rug, in a warm, colourful Indian family home with pastel walls, tiled floors and wooden furniture: the children Ravi, Anu and Divya with joyful faces ready to dance, in a playful start pose, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S020_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S020_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S020_Ref.png`. 0–3s: the children start dancing to a bouncy beat, twirling long coloured ribbons in circles under the spinning fan, then spinning with their arms out; 3–6s: they repeat the move with a bigger bounce, smiling at each other in time with the beat; 6–8s: the camera circles them as they strike a cheerful pose and the movement settles. No speech, singing or lip-sync: the children keep expressive happy faces with closed mouths. Audio is very quiet sound effects only; the song is added in the edit.
Sound (very quiet SFX only, no music, no voice): Light footsteps and fabric swish with the quiet sound that suits the action; gentle ambience; nothing louder than the room tone.
Cut→S021: Use as a cutaway or loop anywhere in the edit.

**S021 — Bonus 8: balcony spin | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any part of the song.
Step 3 Ingredients: Character & Prop Reference Images: `Ravi_Portrait.png`, `Ravi_6Angle.png`, `Anu_Portrait.png`, `Anu_6Angle.png`, `Divya_Portrait.png`, `Divya_6Angle.png`, `CeilingFan_Portrait.png`, `CeilingFan_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A balcony with a wind-chime and a stand fan) · Scene Continuity Reference: `S020_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot in a balcony with a wind-chime and a small stand fan, in a warm, colourful Indian family home with pastel walls, tiled floors and wooden furniture: the children Ravi, Anu and Divya with joyful faces ready to dance, in a playful start pose, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S021_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S021_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S021_Ref.png`. 0–3s: the children start dancing to a bouncy beat, spinning with arms out in front of the stand fan, their hair and clothes fluttering, then catching the breeze with their hands; 3–6s: they repeat the move with a bigger bounce, smiling at each other in time with the beat; 6–8s: the camera circles them as they strike a cheerful pose and the movement settles. No speech, singing or lip-sync: the children keep expressive happy faces with closed mouths. Audio is very quiet sound effects only; the song is added in the edit.
Sound (very quiet SFX only, no music, no voice): Light footsteps and fabric swish with the quiet sound that suits the action; gentle ambience; nothing louder than the room tone.
Cut→S022: Use as a cutaway or loop anywhere in the edit.

**S022 — Bonus 9: paper pinwheels | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over any part of the song.
Step 3 Ingredients: Character & Prop Reference Images: `Ravi_Portrait.png`, `Ravi_6Angle.png`, `Anu_Portrait.png`, `Anu_6Angle.png`, `Divya_Portrait.png`, `Divya_6Angle.png`, `CeilingFan_Portrait.png`, `CeilingFan_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A bedroom with floating paper pinwheels on a string) · Scene Continuity Reference: `S021_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot in a bedroom with paper pinwheels hanging on a string and a ceiling fan, in a warm, colourful Indian family home with pastel walls, tiled floors and wooden furniture: the children Ravi, Anu and Divya with joyful faces ready to dance, in a playful start pose, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S022_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S022_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S022_Ref.png`. 0–3s: the children start dancing to a bouncy beat, holding paper pinwheels that spin in the air and spinning along with them, then waving the pinwheels in rhythm; 3–6s: they repeat the move with a bigger bounce, smiling at each other in time with the beat; 6–8s: the camera circles them as they strike a cheerful pose and the movement settles. No speech, singing or lip-sync: the children keep expressive happy faces with closed mouths. Audio is very quiet sound effects only; the song is added in the edit.
Sound (very quiet SFX only, no music, no voice): Light footsteps and fabric swish with the quiet sound that suits the action; gentle ambience; nothing louder than the room tone.
Cut→Use as a cutaway or loop anywhere in the edit.

---

# PRODUCTION NOTES

- **Total required:** 22 reference images (`S001_Ref.png` … `S022_Ref.png`) and 22 videos, one video per image: 13 timed scenes that follow the song plus 9 bonus dance scenes. Plus the Step 1 sheets: 3 children and 3 props (wall clock, steel plates, ceiling fan), 6 portraits and 6 six-angle turnarounds (12 images). There are no environment-plate images. Overall: 22 scene images + 12 sheet images = 34 images, and 22 videos.
- **Song length:** your last timestamp is 0:52 ("It's time to sleep"). The audio length was not attached, so I assumed the song ends around 0:57–0:58 and made the timed scenes 58 s long (0:00–0:58). Send the audio length if it differs and I will adjust the last scene.
- **Song structure (from your timestamps):** 0:00–0:04 intro; 0:04 clock ticks; 0:13 "The clock on the wall goes tick, tick, tick, it's time to start"; 0:21 plate bangs; 0:30 "The plate on the floor goes bang, bang, bang, it's time to eat"; 0:39 fan spins; 0:43 "spin, spin, spin"; 0:48 "The fan in the hall goes spin, spin, spin"; 0:52 "It's time to sleep". Clips use even seconds, so each cut falls about 1 s before a section that starts on an odd second (0:13, 0:21, 0:39, 0:43). This lead-in feels natural; nudge a clip by 1 s in the edit if you want it exact.
- **Cast rule:** every scene shows exactly the three children Ravi, Anu and Divya, plus the one prop that fits the verse (clock in S002–S005, plates in S006–S009, fan in S010–S013). The bonus dance scenes follow the same pairing: S014–S016 clock, S017–S019 plates, S020–S022 fan.
- **What to generate in Flow (8 s or 10 s only):** every video is generated at 8 s. All timed slots are 4 s or 6 s, so each clip has 2–4 s of spare footage after the lyric beats. The bonus scenes are 8 s. No scene needs 10 s.

| Generate in Flow | Number of videos | Footage | Scenes |
|---|---|---|---|
| 8 s | 22 | 176 s | all scenes S001–S022 |

- **Slot plan (timed scenes):** 4 s slots: S001–S005, S007–S010, S012 (10 clips, 40 s); 6 s slots: S006, S011, S013 (3 clips, 18 s); total 58 s.
- **Timeline rule:** put the song on the timeline at 0:00, drop each timed clip at its scene start time and trim it to its slot. The extra seconds are spare footage. The bonus scenes have no timestamp: use them as cutaways, or loop a verse to make a longer video.
- **Making it addictive:** each verse has its own prop and its own dance (pointing and swinging arms like clock hands, tapping plates like drums, twirling like fan blades), a quick visual change every 4–6 s, and a clear day story from waking up, to eating, to sleeping. The repeated lines get new spots and bigger moves so they never look repeated.
- **Audio:** generated clips contain only very quiet sound effects. They have no music, singing, speech or lip-sync, and they avoid loud ticks, bangs or whooshes so your song's own tick, bang and spin sounds stay clean. If you want Flow to add music or have the children sing on screen, tell me and I'll change the audio line in the global lock.
- **Image generation is Google Flow only.** Generate the 6 sheets first, then each scene image in order. Video prompts use each scene's saved image as the starting frame.
- **Reminder:** the GLOBAL LOCK BLOCK must be appended in full to the end of every prompt (Step 1, every Step 3 and every Step 4) before submission.
