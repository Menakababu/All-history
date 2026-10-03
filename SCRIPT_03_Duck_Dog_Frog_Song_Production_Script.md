# SCRIPT 03 — வாத்து, நாய்க்குட்டி, தவளை: A dancing animal song with Arun and Meena
### [TEMPLATE v3 — Google Flow only · song slots of 4/6/8 s, Flow clips generated at 8 or 10 s · character sheets → unique location per scene → per-scene reference image → per-scene video · global lock appended to every prompt · no on-screen text · consistent visible faces · quiet SFX only]

**Duration:** 0:50 (song ≈ 50 s) | **Total Scenes:** 18 = 18 reference images = 18 videos (9 timed scenes + 9 bonus dance scenes)
**Image generation:** Google Flow only (Step 1 character sheets, Step 2 location plan, Step 3 scene reference images)
**Video generation:** Google Flow — one video prompt per scene, each generated as an 8 s or 10 s clip (a song slot plus spare seconds to trim)
**Payoff:** A joyful finale where the boy, the girl, the duck, the puppy and the frog dance together on the village green as the song ends.
**Dialogue/Audio rule:** The generated clips contain NO voice, singing, music or animal voices: only quiet sound effects. Your recorded Tamil song is added in the edit.

**Assumptions made for the blank input fields (change if needed):**
- **Style:** 3D animated family-film look (bright, cheerful, child-friendly). Tell me if you want 2D cartoon, clay or another look.
- **Characters:** the boy Arun, the girl Meena, the duckling Vaathu, the puppy Kutty and the frog Thavalai, all invented.
- **Hard rules:** no on-screen text or lyrics; each scene shows the boy, the girl and only the animal named in the lyrics (the chorus shows all three).
- **Chorus timing:** estimated, because the transcript ends at 0:32.

**Segment map (song ≈ 50 s, cut on the lyric phrases)**

| # | Segment | Scenes | Time |
|---|---|---|---|
| 1 | Duck verse (boy + girl + duck) | S001–S003 | 0:00–0:16 |
| 2 | Dog verse (boy + girl + dog) | S004–S005 | 0:16–0:24 |
| 3 | Frog verse (boy + girl + frog) | S006–S007 | 0:24–0:36 |
| 4 | Chorus: all friends sing together | S008–S009 | 0:36–0:50 |
| 5 | Bonus vibe scenes: dancing to the tune (use anywhere in the edit) | S010–S018 | bonus (no timestamp) |

---

## ⚠️ GLOBAL LOCK BLOCK — append this in full to the END of every single prompt below (Step 1, every Step 3, every Step 4)

```
GLOBAL LOCK:
CONTINUITY — Keep Arun (boy), Meena (girl), Vaathu (yellow duckling with blue scarf), Kutty (golden-brown puppy with red collar and bell) and Thavalai (green frog with lotus-petal hat) in exact face, colour, clothing, accessory and proportion continuity from their saved reference sheets — no redesign, recolor or scale drift. Every scene takes place in its own unique location exactly as written in its prompt; never copy or reuse the previous scene's location, background or composition.
CAST RULE — Every scene shows exactly the boy Arun, the girl Meena and ONLY the animal named in that scene's prompt: the duckling in the duck scenes, the puppy in the dog scenes, the frog in the frog scenes. The other two animals never appear, except in the chorus scenes whose prompt names all three. No other people or animals appear.
STYLE — 3D animated family-film style, bright cheerful colours, soft global illumination, a warm 35mm-lens depth of field, one consistent colour grade across all locations (sunny gold, fresh greens, sky blue), smooth appealing character animation with natural squash and stretch, expressive happy faces. Real material physics: water ripples and splashes, fur, feathers and cloth move naturally.
HARD RULES — No on-screen text, captions, lyrics, logos or watermarks. Fully child-friendly: no scary, violent or dangerous content. Characters always have clear, fully visible, expressive faces matching their sheets in every shot; faces never morph between shots. Dancing is bouncy, cheerful and in rhythm with a happy tune.
ZERO AI ARTIFACTS — No morphing, warping, melting, flicker, extra or duplicated limbs, tails, heads or characters, floating debris, texture smearing, distorted hands, paws or feet.
LIGHTING — Follow the time of day and light written in each scene's prompt; no sudden unintended light jumps inside a shot.
AUDIO — Generated audio is ONLY quiet diegetic sound effects (splashes, footsteps, paw patter, hops, rustle, jingles). No music, no singing, no speech, no lip-sync, and no animal voices (no quacking, barking or croaking): the Tamil song, with its animal sounds, is added in the edit. Characters keep happy smiles and closed mouths.
CAMERA — Smooth, physically plausible motion only; each shot's opening camera motion matches the previous shot's closing motion vector for a seamless cut.
```

---

# STEP 1 — CHARACTER REFERENCE IMAGES (Google Flow — image generation ONLY)

### 1A. Boy ("Arun")
**Portrait Image Prompt — Google Flow:**
Full-body portrait of a 7-year-old Tamil boy named Arun standing in a happy relaxed pose, facing the camera, with a clearly visible, fully expressive animated face: warm brown skin, round cheeks, big dark sparkling eyes, short black hair with a small cowlick, a cheeky grin with a missing front tooth. Bright yellow T-shirt, blue shorts, red sandals. 3D animated family-film style, bright cheerful colours, soft global illumination. Neutral light-grey background, soft key light, clean readable shapes. Locked reference design.
**Save as:** `Arun_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Arun_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT (face fully visible, identical to the portrait), REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE (feet and ground contact), neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) locking the face.
**Save as:** `Arun_6Angle.png`
**Usage note:** Attach both files to every scene where this character appears: S001–S018.

### 1B. Girl ("Meena")
**Portrait Image Prompt — Google Flow:**
Full-body portrait of a 6-year-old Tamil girl named Meena standing in a happy relaxed pose, facing the camera, with a clearly visible, fully expressive animated face: warm brown skin, dimples, big bright brown eyes, two high black pigtails tied with red ribbons, a sweet wide smile. A green frock with white polka dots, white socks and pink shoes. 3D animated family-film style, bright cheerful colours, soft global illumination. Neutral light-grey background, soft key light. Locked reference design.
**Save as:** `Meena_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Meena_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT (face fully visible, identical to the portrait), REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE (feet and ground contact), neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile) locking the face.
**Save as:** `Meena_6Angle.png`
**Usage note:** Attach both files to every scene where this character appears: S001–S018.

### 1C. Naughty Duckling ("Vaathu")
**Portrait Image Prompt — Google Flow:**
A fluffy yellow duckling named Vaathu standing upright on its orange feet in a cheeky pose, with a clearly visible, fully expressive animated face: big round black eyes with sparkling highlights, mischievous slightly raised eyebrows, a small orange bill, a tiny tuft of feathers on its head, and a tiny blue neck-scarf. Soft fluffy feather detail. 3D animated family-film style, bright cheerful colours, soft global illumination. Neutral light-grey background, soft key light. Locked reference design.
**Save as:** `Vaathu_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Vaathu_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT (face fully visible, identical to the portrait), REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE (feet and ground contact), neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up head panels (front, left profile, right profile) locking the face.
**Save as:** `Vaathu_6Angle.png`
**Usage note:** Attach both files to every scene where this character appears: S001–S003, S008–S012.

### 1D. Puppy ("Kutty")
**Portrait Image Prompt — Google Flow:**
A golden-brown puppy named Kutty sitting happily with its tongue out, with a clearly visible, fully expressive animated face: big brown eyes with highlights, floppy ears, a white patch on its chest, a pink tongue, a wagging tail, and a small red collar with a little gold bell. Soft fur detail. 3D animated family-film style, bright cheerful colours, soft global illumination. Neutral light-grey background, soft key light. Locked reference design.
**Save as:** `Kutty_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Kutty_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT (face fully visible, identical to the portrait), REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE (feet and ground contact), neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up head panels (front, left profile, right profile) locking the face.
**Save as:** `Kutty_6Angle.png`
**Usage note:** Attach both files to every scene where this character appears: S004–S005, S008–S009, S013–S015.

### 1E. Frog ("Thavalai")
**Portrait Image Prompt — Google Flow:**
A bright green frog named Thavalai sitting on a stone, with a clearly visible, fully expressive animated face: big round gold-ringed eyes with highlights, a wide gentle smile, a pale-green belly, small darker-green spots on its back, and a tiny pink lotus petal worn like a hat on its head. Smooth glossy skin. 3D animated family-film style, bright cheerful colours, soft global illumination. Neutral light-grey background, soft key light. Locked reference design.
**Save as:** `Thavalai_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Thavalai_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT (face fully visible, identical to the portrait), REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE (feet and ground contact), neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up head panels (front, left profile, right profile) locking the face.
**Save as:** `Thavalai_6Angle.png`
**Usage note:** Attach both files to every scene where this character appears: S006–S009, S016–S018.

---

# STEP 2 — LOCATION PLAN (no reusable environment plates: every scene has its own unique place)

There are no shared environment-plate images. Each scene's Step 3 prompt fully describes its own location, and `Environment Reference Image` is `none`. The table lists every scene's location so you can check that no place repeats.

| Scene | Time | Slot | Flow clip | Unique location |
|---|---|---|---|---|
| S001 | 0:00–0:06 | 6s | 8 s | Village pond edge at sunrise with reeds and a small wooden jetty |
| S002 | 0:06–0:10 | 4s | 8 s | Stone steps (ghat) of a village temple pond in the morning |
| S003 | 0:10–0:16 | 6s | 8 s | A wide lotus pond with floating leaves at bright midday |
| S004 | 0:16–0:20 | 4s | 8 s | Front yard of a village house with a kolam pattern and a tulsi plant |
| S005 | 0:20–0:24 | 4s | 8 s | Green meadow beside a paddy-field bund under coconut palms |
| S006 | 0:24–0:30 | 6s | 8 s | A pond edge with big mossy stones and ferns after morning rain |
| S007 | 0:30–0:36 | 6s | 8 s | A small round rainwater pond under a banyan tree at golden hour |
| S008 | 0:36–0:42 | 6s | 8 s | A sunny village lane lined with coconut palms and flowering hedges |
| S009 | 0:42–0:50 | 8s | 10 s | A festival-bright village green with a banyan tree, bunting and lanterns at golden hour |
| S010 | bonus (no timestamp) | none | 8 s | A stepping-stone path across a small pond in morning light |
| S011 | bonus (no timestamp) | none | 8 s | A calm backwater at sunrise with a small wooden boat |
| S012 | bonus (no timestamp) | none | 8 s | A puddle-filled farmyard after rain with a hay cart |
| S013 | bonus (no timestamp) | none | 8 s | A hay-stack field at sunset with golden light |
| S014 | bonus (no timestamp) | none | 8 s | A garden with a rope swing under a mango tree |
| S015 | bonus (no timestamp) | none | 8 s | A sandy beach at golden hour with a fishing boat |
| S016 | bonus (no timestamp) | none | 8 s | A rainy-day bamboo grove with big banana-leaf umbrellas |
| S017 | bonus (no timestamp) | none | 8 s | A moonlit lotus pond at dusk with fireflies |
| S018 | bonus (no timestamp) | none | 8 s | A bright garden stream with wooden stepping logs and ferns at noon |

---

# STEP 3 & STEP 4 — SCENES (song slots of 4, 6 and 8 seconds; every Flow video is generated at 8 or 10 seconds)

**How each scene is shaped:**
Header line (scene number, label, time range and slot) → **Song sync** (editor note only, never paste into Flow) → Step 3 Ingredients → Step 3 Reference Image Prompt → Step 4 Ingredients → Video Prompt (Google Flow, generated at 8 s or 10 s; second marks relative to the clip start, the lyric beats first and spare seconds after) → Sound → Cut→.
Append the GLOBAL LOCK BLOCK to the end of every Step 3 and Step 4 prompt.

---

### Segment 1 — Duck verse (boy + girl + duck) (Scenes 1–3) | 0:00–0:16

**S001 — Quack, quack: the duck arrives | 0:00–0:06 (6s slot → generate 8s in Flow)**
Song sync: (0:00) "குவாக்... குவாக்... (அறிமுகம்; நேரக்குறிப்பு இல்லை)"
Step 3 Ingredients: Character Reference Images: `Arun_Portrait.png`, `Arun_6Angle.png`, `Meena_Portrait.png`, `Meena_6Angle.png`, `Vaathu_Portrait.png`, `Vaathu_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: Village pond edge at sunrise with reeds and a small wooden jetty) · Scene Continuity Reference: none (first scene in the series)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot at sunrise at the edge of a village pond with tall reeds and a small wooden jetty: the boy Arun and the girl Meena standing on the jetty bouncing happily on their toes with big smiles, and the fluffy yellow duckling Vaathu paddling toward them across glittering golden water, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S001_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S001_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the lyric beats, the last 2s are spare footage):
I2V from `S001_Ref.png`. 0–2s: the camera floats low over the water as the duckling paddles in and the boy and girl bounce to the beat; 2–4s: the duckling flaps its tiny wings with a splash and the children throw their arms up in delight; 4–6s: the camera circles slightly as all three sway from side to side. 6–8s (spare 2s): the same gentle motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched. No speech, singing, quacking, barking, croaking or lip-sync: the characters keep happy smiles and closed mouths. Audio is quiet sound effects only; the song is added in the edit.
Sound (SFX only, no music, no voice): Soft water ripples and a tiny splash at 2s; the children's light footsteps on wooden planks, reeds rustling; quiet birdsong. From 6s to 8s the sound ambience sustains and eases down.
Cut→S002: Cut to a stone-step pond.

**S002 — Naughty duck | 0:06–0:10 (4s slot → generate 8s in Flow)**
Song sync: (0:06) "வாத்து, குறும்புக்கார வாத்து"
Step 3 Ingredients: Character Reference Images: `Arun_Portrait.png`, `Arun_6Angle.png`, `Meena_Portrait.png`, `Meena_6Angle.png`, `Vaathu_Portrait.png`, `Vaathu_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: Stone steps (ghat) of a village temple pond in the morning) · Scene Continuity Reference: `S001_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Medium shot on the wide stone steps of a village temple pond in morning light: the boy Arun and the girl Meena crouching on a step laughing, and the naughty yellow duckling Vaathu splashing water at them with a flap of its wings and a cheeky tilt of its head, droplets sparkling, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S002_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S002_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the lyric beats, the last 4s are spare footage):
I2V from `S002_Ref.png`. 0–2s: the duckling splashes a spray of water and the boy and girl lean back giggling with their arms up; 2–4s: the children dance a little bounce on the step as the duckling wiggles its tail feathers at them. 4–8s (spare 4s): the same gentle motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No speech, singing, quacking, barking, croaking or lip-sync: the characters keep happy smiles and closed mouths. Audio is quiet sound effects only; the song is added in the edit.
Sound (SFX only, no music, no voice): Water splash, droplets pattering on stone, soft child-sized footsteps; a distant temple bell. From 4s to 8s the sound ambience sustains and eases down.
Cut→S003: Cut to a lotus pond.

**S003 — Swimming criss-cross in the pond | 0:10–0:16 (6s slot → generate 8s in Flow)**
Song sync: (0:10) "குளத்துக்குள்ள நீந்திக்கிட்டு" · (0:12) "குறுக்க நெடுக்கப் போகுதாம்"
Step 3 Ingredients: Character Reference Images: `Arun_Portrait.png`, `Arun_6Angle.png`, `Meena_Portrait.png`, `Meena_6Angle.png`, `Vaathu_Portrait.png`, `Vaathu_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: A wide lotus pond with floating leaves at bright midday) · Scene Continuity Reference: `S002_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot at bright midday over a wide lotus pond with big green leaves and pink blossoms: the yellow duckling Vaathu swimming in a zigzag across the water, and on the bank the boy Arun and the girl Meena dancing and clapping along, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S003_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S003_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the lyric beats, the last 2s are spare footage):
I2V from `S003_Ref.png`. 0–2s: the duckling paddles in a wavy line between the lotus leaves, the boy and girl swaying on the bank; 2–4s: it zigzags back the other way crossing its own ripples as the children clap in rhythm; 4–6s: the camera tracks along the bank with the children's dance steps as the duckling makes a last curve and a ripple spreads. 6–8s (spare 2s): the same gentle motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched. No speech, singing, quacking, barking, croaking or lip-sync: the characters keep happy smiles and closed mouths. Audio is quiet sound effects only; the song is added in the edit.
Sound (SFX only, no music, no voice): Gentle water paddling, lotus leaves brushing, soft clapping; a dragonfly buzz. From 6s to 8s the sound ambience sustains and eases down.
Cut→S004: Cut to a village front yard.

---

### Segment 2 — Dog verse (boy + girl + dog) (Scenes 4–5) | 0:16–0:24

**S004 — Woof, woof: the puppy | 0:16–0:20 (4s slot → generate 8s in Flow)**
Song sync: (0:15) "லொள்... லொள்... நாய்க்குட்டி" · (0:17) "குரைக்கும் நல்ல நாய்க்குட்டி"
Step 3 Ingredients: Character Reference Images: `Arun_Portrait.png`, `Arun_6Angle.png`, `Meena_Portrait.png`, `Meena_6Angle.png`, `Kutty_Portrait.png`, `Kutty_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: Front yard of a village house with a kolam pattern and a tulsi plant) · Scene Continuity Reference: `S003_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Medium shot in the front yard of a colourful village house with a white rice-flour kolam pattern on the ground and a tulsi plant: the boy Arun and the girl Meena kneeling and smiling, and the golden-brown puppy Kutty trotting up to them with floppy ears bouncing and a big pink tongue, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S004_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S004_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the lyric beats, the last 4s are spare footage):
I2V from `S004_Ref.png`. 0–2s: the puppy trots up with floppy ears bouncing and the children open their arms; 2–4s: it sits and its head tilts as the boy pats its head and the girl claps in rhythm. 4–8s (spare 4s): the same gentle motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No speech, singing, quacking, barking, croaking or lip-sync: the characters keep happy smiles and closed mouths. Audio is quiet sound effects only; the song is added in the edit.
Sound (SFX only, no music, no voice): Quick paw pitter-patter on the ground, the little bell on the puppy's collar jingling, soft clapping. From 4s to 8s the sound ambience sustains and eases down.
Cut→S005: Cut to a paddy-field meadow.

**S005 — Wagging tail, jumping dance | 0:20–0:24 (4s slot → generate 8s in Flow)**
Song sync: (0:20) "குழைந்து வாலை ஆட்டிக்கிட்டு" · (0:22) "குதித்து ஆட்டம் போடுதாம்"
Step 3 Ingredients: Character Reference Images: `Arun_Portrait.png`, `Arun_6Angle.png`, `Meena_Portrait.png`, `Meena_6Angle.png`, `Kutty_Portrait.png`, `Kutty_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: Green meadow beside a paddy-field bund under coconut palms) · Scene Continuity Reference: `S004_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot of a green meadow beside a paddy-field bund with coconut palms and a bright blue sky: the puppy Kutty wagging its tail and jumping high, and the boy Arun and the girl Meena jumping and dancing joyfully beside it, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S005_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S005_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the lyric beats, the last 4s are spare footage):
I2V from `S005_Ref.png`. 0–2s: the puppy's tail wags fast as it leaps on the beat, the children jumping with it; 2–4s: all three spin around in a little dance circle, ears, pigtails and the tail flying, and land with a bounce. 4–8s (spare 4s): the same gentle motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 4s slot or stretched. No speech, singing, quacking, barking, croaking or lip-sync: the characters keep happy smiles and closed mouths. Audio is quiet sound effects only; the song is added in the edit.
Sound (SFX only, no music, no voice): Grass rustle, thumping little jumps, the collar bell jingling; a breeze through the palms. From 4s to 8s the sound ambience sustains and eases down.
Cut→S006: Cut to a mossy pond edge.

---

### Segment 3 — Frog verse (boy + girl + frog) (Scenes 6–7) | 0:24–0:36

**S006 — Ribbit: the frog hops | 0:24–0:30 (6s slot → generate 8s in Flow)**
Song sync: (0:24) "க்ர்ரக்... க்ர்ரக்... தவளை" · (0:27) "தத்தித் தாவும் தவளை" · (0:29) "தண்ணிக்குள்ள"
Step 3 Ingredients: Character Reference Images: `Arun_Portrait.png`, `Arun_6Angle.png`, `Meena_Portrait.png`, `Meena_6Angle.png`, `Thavalai_Portrait.png`, `Thavalai_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: A pond edge with big mossy stones and ferns after morning rain) · Scene Continuity Reference: `S005_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Medium shot at a pond edge with big mossy stones and ferns after a morning rain, droplets on the leaves: the bright green frog Thavalai sitting on a stone, and the boy Arun and the girl Meena crouching beside it with delighted faces, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S006_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S006_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the lyric beats, the last 2s are spare footage):
I2V from `S006_Ref.png`. 0–2s: the frog sits still then springs onto the next stone with a big hop as the children gasp and smile; 2–4s: it hops again and the boy and girl hop along the bank in the same rhythm; 4–6s: the frog lands and its throat puffs softly as the children clap. 6–8s (spare 2s): the same gentle motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched. No speech, singing, quacking, barking, croaking or lip-sync: the characters keep happy smiles and closed mouths. Audio is quiet sound effects only; the song is added in the edit.
Sound (SFX only, no music, no voice): Soft hops landing on wet stone, water drips from leaves, light clapping; a gentle hum of insects. From 6s to 8s the sound ambience sustains and eases down.
Cut→S007: Cut to a banyan pond at golden hour.

**S007 — Tapping the rhythm on the water | 0:30–0:36 (6s slot → generate 8s in Flow)**
Song sync: (0:29) "தண்ணிக்குள்ள இருந்துகிட்டு" · (0:32) "தட்டித் தாளம் போடுதாம்"
Step 3 Ingredients: Character Reference Images: `Arun_Portrait.png`, `Arun_6Angle.png`, `Meena_Portrait.png`, `Meena_6Angle.png`, `Thavalai_Portrait.png`, `Thavalai_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: A small round rainwater pond under a banyan tree at golden hour) · Scene Continuity Reference: `S006_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Medium shot at golden hour of a small round pond under a huge banyan tree: the green frog Thavalai sitting on a floating lily pad patting the water with its front feet, ripples spreading, and the boy Arun and the girl Meena kneeling on the bank clapping along, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S007_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S007_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the lyric beats, the last 2s are spare footage):
I2V from `S007_Ref.png`. 0–2s: the frog pats the water with its front feet on the beat making rings of ripples; 2–4s: the children clap in time and sway their shoulders; 4–6s: the frog taps faster and the ripples overlap into a pattern as the children laugh and nod their heads. 6–8s (spare 2s): the same gentle motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched. No speech, singing, quacking, barking, croaking or lip-sync: the characters keep happy smiles and closed mouths. Audio is quiet sound effects only; the song is added in the edit.
Sound (SFX only, no music, no voice): Rhythmic soft patting on water, ripples, light clapping; evening crickets. From 6s to 8s the sound ambience sustains and eases down.
Cut→S008: Cut to a sunny village lane.

---

### Segment 4 — Chorus: all friends sing together (Scenes 8–9) | 0:36–0:50

**S008 — Competing and singing together | 0:36–0:42 (6s slot → generate 8s in Flow)**
Song sync: (0:36) "போட்டி போட்டு ஒன்றாகப் பாட்டுப் பாடிச் சென்றாங்க (இந்த வரி முதல் நேரக்குறிப்பு இல்லை; மதிப்பீடு)"
Step 3 Ingredients: Character Reference Images: `Arun_Portrait.png`, `Arun_6Angle.png`, `Meena_Portrait.png`, `Meena_6Angle.png`, `Vaathu_Portrait.png`, `Vaathu_6Angle.png`, `Kutty_Portrait.png`, `Kutty_6Angle.png`, `Thavalai_Portrait.png`, `Thavalai_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: A sunny village lane lined with coconut palms and flowering hedges) · Scene Continuity Reference: `S007_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot of a sunny village lane lined with coconut palms and flowering hedges: the boy Arun and the girl Meena skipping side by side holding hands, with the yellow duckling Vaathu waddling on the left, the puppy Kutty trotting on the right and the green frog Thavalai hopping between them, all in a happy parade, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S008_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S008_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the lyric beats, the last 2s are spare footage):
I2V from `S008_Ref.png`. 0–2s: the five friends start the parade down the lane, the children swinging their joined hands; 2–4s: they march in step, the duckling waddling, the puppy trotting and the frog hopping on the beat; 4–6s: the camera tracks backwards ahead of them as they sway and bounce together. 6–8s (spare 2s): the same gentle motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched. No speech, singing, quacking, barking, croaking or lip-sync: the characters keep happy smiles and closed mouths. Audio is quiet sound effects only; the song is added in the edit.
Sound (SFX only, no music, no voice): Footsteps, waddle and paw patter, small hops, the collar bell jingling; birds in the palms. From 6s to 8s the sound ambience sustains and eases down.
Cut→S009: Cut to a festival village green.

**S009 — All together: the dancing finale | 0:42–0:50 (8s slot → generate 10s in Flow)**
Song sync: (0:42) "குவாக்... குவாக்... லொள்... லொள்... க்ர்ரக்... க்ர்ரக்... குவாக்... குவாக்... (மதிப்பீடு; நேரக்குறிப்பு இல்லை)"
Step 3 Ingredients: Character Reference Images: `Arun_Portrait.png`, `Arun_6Angle.png`, `Meena_Portrait.png`, `Meena_6Angle.png`, `Vaathu_Portrait.png`, `Vaathu_6Angle.png`, `Kutty_Portrait.png`, `Kutty_6Angle.png`, `Thavalai_Portrait.png`, `Thavalai_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: A festival-bright village green with a banyan tree, bunting and lanterns at golden hour) · Scene Continuity Reference: `S008_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot at golden hour of a village green with a big banyan tree, colourful bunting (no text) and glowing lanterns: the boy Arun and the girl Meena in the centre dancing with their arms up, and around them the yellow duckling Vaathu, the puppy Kutty and the green frog Thavalai each dancing in their own style, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S009_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S009_Ref.png`
Video Prompt (Google Flow, generate 10s: the first 8s carry the lyric beats, the last 2s are spare footage):
I2V from `S009_Ref.png`. 0–2s: all five begin the dance, the children clapping and the animals bouncing; 2–5s: the duckling flaps and spins, the puppy jumps and wags, the frog hops in time as the children twirl in a circle; 5–8s: the camera cranes up and arcs around the group as they strike a happy final pose with the lanterns glowing. 8–10s (spare 2s): the same gentle motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 8s slot or stretched. No speech, singing, quacking, barking, croaking or lip-sync: the characters keep happy smiles and closed mouths. Audio is quiet sound effects only; the song is added in the edit.
Sound (SFX only, no music, no voice): Light foot taps, small hops and paw patter, bunting fluttering, a soft whoosh as the camera cranes up; evening crickets. From 8s to 10s the sound ambience sustains and eases down.
Cut→S010: END: the song ends; fade out over the last second.

---

### Segment 5 — Bonus vibe scenes: dancing to the tune (use anywhere in the edit) (Scenes 10–18)

**S010 — Duck vibe 1: hopping the stepping stones | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over the chorus, an instrumental gap or a repeat of the song.
Step 3 Ingredients: Character Reference Images: `Arun_Portrait.png`, `Arun_6Angle.png`, `Meena_Portrait.png`, `Meena_6Angle.png`, `Vaathu_Portrait.png`, `Vaathu_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: A stepping-stone path across a small pond in morning light) · Scene Continuity Reference: `S009_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot on a stepping-stone path across a small pond in morning light: the boy Arun and the girl Meena hopping from stone to stone with big smiles, and the yellow duckling Vaathu waddling on the stones beside them, ripples around the stones, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S010_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S010_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S010_Ref.png`. 0–3s: the children hop from stone to stone to a bouncy beat while the duckling waddles beside them and flutters its wings on each hop; 3–6s: they repeat the hops with a bigger bounce, the children clapping in time; 6–8s: the camera circles them as they strike a cheerful pose on the last stone. No speech, singing, quacking, barking, croaking or lip-sync: the characters keep happy smiles and closed mouths. Audio is quiet sound effects only; the song is added in the edit.
Sound (SFX only, no music, no voice): Light footsteps, splashes, hops or paw patter that suit the place, soft clapping and gentle ambience.
Cut→S011: Use as a cutaway or loop anywhere in the edit.

**S011 — Duck vibe 2: the little boat | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over the chorus, an instrumental gap or a repeat of the song.
Step 3 Ingredients: Character Reference Images: `Arun_Portrait.png`, `Arun_6Angle.png`, `Meena_Portrait.png`, `Meena_6Angle.png`, `Vaathu_Portrait.png`, `Vaathu_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: A calm backwater at sunrise with a small wooden boat) · Scene Continuity Reference: `S010_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot on a calm backwater at sunrise: the boy Arun and the girl Meena sitting in a small wooden boat with joyful faces, and the yellow duckling Vaathu perched at the bow, soft golden mist on the water, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S011_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S011_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S011_Ref.png`. 0–3s: the boat rocks gently as the children sway and clap to a bouncy beat and the duckling flaps its wings at the bow; 3–6s: they dance in their seats with bigger arm swings, the boat creating ripples; 6–8s: the camera circles the boat as they strike a cheerful pose and the rocking settles. No speech, singing, quacking, barking, croaking or lip-sync: the characters keep happy smiles and closed mouths. Audio is quiet sound effects only; the song is added in the edit.
Sound (SFX only, no music, no voice): Light footsteps, splashes, hops or paw patter that suit the place, soft clapping and gentle ambience.
Cut→S012: Use as a cutaway or loop anywhere in the edit.

**S012 — Duck vibe 3: puddle splash dance | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over the chorus, an instrumental gap or a repeat of the song.
Step 3 Ingredients: Character Reference Images: `Arun_Portrait.png`, `Arun_6Angle.png`, `Meena_Portrait.png`, `Meena_6Angle.png`, `Vaathu_Portrait.png`, `Vaathu_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: A puddle-filled farmyard after rain with a hay cart) · Scene Continuity Reference: `S011_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot in a puddle-filled farmyard after rain with a hay cart: the boy Arun and the girl Meena in rain boots splashing in a puddle with big smiles, and the yellow duckling Vaathu splashing beside them, sunlight on the droplets, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S012_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S012_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S012_Ref.png`. 0–3s: the children stomp and splash in rhythm while the duckling splashes beside them, drops flying in the sunlight; 3–6s: they spin and splash with a bigger move, laughing; 6–8s: the camera circles them as they land in a cheerful pose and the water settles. No speech, singing, quacking, barking, croaking or lip-sync: the characters keep happy smiles and closed mouths. Audio is quiet sound effects only; the song is added in the edit.
Sound (SFX only, no music, no voice): Light footsteps, splashes, hops or paw patter that suit the place, soft clapping and gentle ambience.
Cut→S013: Use as a cutaway or loop anywhere in the edit.

**S013 — Dog vibe 1: hay-stack dance | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over the chorus, an instrumental gap or a repeat of the song.
Step 3 Ingredients: Character Reference Images: `Arun_Portrait.png`, `Arun_6Angle.png`, `Meena_Portrait.png`, `Meena_6Angle.png`, `Kutty_Portrait.png`, `Kutty_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: A hay-stack field at sunset with golden light) · Scene Continuity Reference: `S012_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot in a hay-stack field at sunset with golden light: the boy Arun and the girl Meena twirling with their arms out and big smiles, and the golden-brown puppy Kutty jumping beside them, hay-stacks and long shadows behind, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S013_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S013_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S013_Ref.png`. 0–3s: the puppy jumps and spins with its tail wagging while the children twirl with their arms out to a bouncy beat; 3–6s: they repeat the dance with a bigger leap, hay seeds drifting in the golden light; 6–8s: the camera circles them as they strike a cheerful pose and the movement settles. No speech, singing, quacking, barking, croaking or lip-sync: the characters keep happy smiles and closed mouths. Audio is quiet sound effects only; the song is added in the edit.
Sound (SFX only, no music, no voice): Light footsteps, splashes, hops or paw patter that suit the place, soft clapping and gentle ambience.
Cut→S014: Use as a cutaway or loop anywhere in the edit.

**S014 — Dog vibe 2: the rope swing | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over the chorus, an instrumental gap or a repeat of the song.
Step 3 Ingredients: Character Reference Images: `Arun_Portrait.png`, `Arun_6Angle.png`, `Meena_Portrait.png`, `Meena_6Angle.png`, `Kutty_Portrait.png`, `Kutty_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: A garden with a rope swing under a mango tree) · Scene Continuity Reference: `S013_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot in a garden with a rope swing under a mango tree: the girl Meena swinging with a joyful face, the boy Arun pushing the swing with a big smile, and the golden-brown puppy Kutty running in a circle beneath it with its ears flying, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S014_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S014_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S014_Ref.png`. 0–3s: the boy pushes the swing to a bouncy beat as the girl swings and claps and the puppy runs circles beneath her; 3–6s: they swap places, the girl pushing and the boy swinging with his arms up; 6–8s: the camera circles the swing as the swing slows and all three finish in a cheerful pose. No speech, singing, quacking, barking, croaking or lip-sync: the characters keep happy smiles and closed mouths. Audio is quiet sound effects only; the song is added in the edit.
Sound (SFX only, no music, no voice): Light footsteps, splashes, hops or paw patter that suit the place, soft clapping and gentle ambience.
Cut→S015: Use as a cutaway or loop anywhere in the edit.

**S015 — Dog vibe 3: beach bounce | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over the chorus, an instrumental gap or a repeat of the song.
Step 3 Ingredients: Character Reference Images: `Arun_Portrait.png`, `Arun_6Angle.png`, `Meena_Portrait.png`, `Meena_6Angle.png`, `Kutty_Portrait.png`, `Kutty_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: A sandy beach at golden hour with a fishing boat) · Scene Continuity Reference: `S014_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot on a sandy beach at golden hour with a colourful fishing boat: the boy Arun and the girl Meena dancing barefoot on the sand with big smiles, and the golden-brown puppy Kutty chasing a small wave, sparkling shallow water, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S015_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S015_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S015_Ref.png`. 0–3s: the children dance and kick up sand to a bouncy beat while the puppy chases a small wave and leaps back; 3–6s: they repeat the dance with a bigger bounce and spin, the puppy jumping beside them; 6–8s: the camera circles them as they strike a cheerful pose and the wave settles. No speech, singing, quacking, barking, croaking or lip-sync: the characters keep happy smiles and closed mouths. Audio is quiet sound effects only; the song is added in the edit.
Sound (SFX only, no music, no voice): Light footsteps, splashes, hops or paw patter that suit the place, soft clapping and gentle ambience.
Cut→S016: Use as a cutaway or loop anywhere in the edit.

**S016 — Frog vibe 1: banana-leaf umbrellas | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over the chorus, an instrumental gap or a repeat of the song.
Step 3 Ingredients: Character Reference Images: `Arun_Portrait.png`, `Arun_6Angle.png`, `Meena_Portrait.png`, `Meena_6Angle.png`, `Thavalai_Portrait.png`, `Thavalai_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: A rainy-day bamboo grove with big banana-leaf umbrellas) · Scene Continuity Reference: `S015_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot in a rainy-day bamboo grove: the boy Arun and the girl Meena holding huge banana-leaf umbrellas in light rain with big smiles, and the green frog Thavalai hopping on a wet stone between puddles, droplets on leaves, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S016_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S016_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S016_Ref.png`. 0–3s: the children sway under their banana-leaf umbrellas to a bouncy beat while the frog hops between puddles; 3–6s: they twirl their umbrellas with a bigger move as the frog makes a bigger hop; 6–8s: the camera circles them as they strike a cheerful pose and the rain softens. No speech, singing, quacking, barking, croaking or lip-sync: the characters keep happy smiles and closed mouths. Audio is quiet sound effects only; the song is added in the edit.
Sound (SFX only, no music, no voice): Light footsteps, splashes, hops or paw patter that suit the place, soft clapping and gentle ambience.
Cut→S017: Use as a cutaway or loop anywhere in the edit.

**S017 — Frog vibe 2: moonlit lotus pond | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over the chorus, an instrumental gap or a repeat of the song.
Step 3 Ingredients: Character Reference Images: `Arun_Portrait.png`, `Arun_6Angle.png`, `Meena_Portrait.png`, `Meena_6Angle.png`, `Thavalai_Portrait.png`, `Thavalai_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: A moonlit lotus pond at dusk with fireflies) · Scene Continuity Reference: `S016_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot at a moonlit lotus pond at dusk with fireflies: the boy Arun and the girl Meena swaying at the water's edge with wondering smiles, and the green frog Thavalai on a lily pad making glowing ripples, soft blue light, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S017_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S017_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S017_Ref.png`. 0–3s: the children sway side to side to a bouncy beat while the frog hops from lily pad to lily pad and the fireflies float; 3–6s: they dance with a bigger sway and the ripples glow and spread; 6–8s: the camera circles them as the frog lands and they strike a cheerful pose. No speech, singing, quacking, barking, croaking or lip-sync: the characters keep happy smiles and closed mouths. Audio is quiet sound effects only; the song is added in the edit.
Sound (SFX only, no music, no voice): Light footsteps, splashes, hops or paw patter that suit the place, soft clapping and gentle ambience.
Cut→S018: Use as a cutaway or loop anywhere in the edit.

**S018 — Frog vibe 3: the garden stream | bonus, no timestamp (generate 8s in Flow)**
Song sync: none. Free cutaway scene: cut it in over the chorus, an instrumental gap or a repeat of the song.
Step 3 Ingredients: Character Reference Images: `Arun_Portrait.png`, `Arun_6Angle.png`, `Meena_Portrait.png`, `Meena_6Angle.png`, `Thavalai_Portrait.png`, `Thavalai_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: A bright garden stream with wooden stepping logs and ferns at noon) · Scene Continuity Reference: `S017_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot at bright noon in a garden stream with wooden stepping logs and ferns: the green frog Thavalai on a log, and the boy Arun and the girl Meena ready to hop with big smiles, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S018_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S018_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S018_Ref.png`. 0–3s: the frog leads with big hops across the wooden logs and the children follow with a bounce to a bouncy beat; 3–6s: they hop back in a line, clapping on each landing; 6–8s: the camera circles them as they strike a cheerful pose on the last log. No speech, singing, quacking, barking, croaking or lip-sync: the characters keep happy smiles and closed mouths. Audio is quiet sound effects only; the song is added in the edit.
Sound (SFX only, no music, no voice): Light footsteps, splashes, hops or paw patter that suit the place, soft clapping and gentle ambience.
Cut→Use as a cutaway or loop anywhere in the edit.

---

# PRODUCTION NOTES

- **Total required:** 18 reference images (`S001_Ref.png` … `S018_Ref.png`) and 18 videos, one video per image: 9 timed scenes that follow the lyrics plus 9 bonus dance scenes. Plus the Step 1 character sheets: 5 portraits and 5 six-angle turnarounds (10 images). There are no environment-plate images. Overall: 18 scene images + 10 character-sheet images = 28 images, and 18 videos.
- **Song length:** the audio file is about 50 s (50.04 s, read from the file header; I cannot hear the song). The timed scenes run 0:00–0:50 and add up to 50 s, which matches the song.
- **Timed scenes (the lyrics):** your timestamps cover the three verses (duck 0:06–0:15, dog 0:15–0:24, frog 0:24–0:35). The closing chorus ("போட்டி போட்டு ஒன்றாகப் பாடிச் சென்றாங்க… குவாக்… லொள்… க்ர்ரக்…") had no timestamps, so its two scenes (S008 0:36–0:42 and S009 0:42–0:50) are estimated. Send me the chorus timestamps if you want them exact. The intro quacks (0:00–0:06) are also untimed.
- **Cast rule:** every scene shows exactly the boy Arun, the girl Meena and only the animal of that verse (duck in S001–S003, dog in S004–S005, frog in S006–S007). The chorus scenes (S008–S009) show all three animals because the lyrics name them all. The bonus scenes follow the same one-animal rule: S010–S012 duck, S013–S015 dog, S016–S018 frog.
- **What to generate in Flow (8 s or 10 s only):** every video is generated at 8 s or 10 s. The timed scenes' 4 s and 6 s slots are generated at 8 s, and the 8 s slot (S009) at 10 s. Each prompt puts the lyric beats first, and the spare seconds only continue the same gentle motion.

| Generate in Flow | Number of videos | Footage | Scenes |
|---|---|---|---|
| 8 s | 17 | 136 s | S001, S002, S003, S004, S005, S006, S007, S008, S010, S011, S012, S013, S014, S015, S016, S017, S018 |
| 10 s | 1 | 10 s | S009 |
| **Total** | **18** | **146 s** | song length ≈ 50 s |

- **Slot plan (timed scenes):** 4 s slots: S002, S004, S005 (3 clips, 12 s); 6 s slots: S001, S003, S006, S007, S008 (5 clips, 30 s); 8 s slots: S009 (1 clip, 8 s); total 50 s.
- **Timeline rule:** put the song on the timeline at 0:00, drop each timed clip at its scene start time and trim it to its slot (the header of each scene shows the slot). The extra seconds are spare footage for stretching or overlapping. The bonus scenes have no timestamp: use them as cutaways over the chorus, or to make a longer video by repeating the song.
- **Making the video longer than the song:** loop the song or add a second pass; fill it with the bonus scenes (three per animal) in any order. Keep the animal pairing (duck bonus scenes together, and so on) if you want the cast rule to hold.
- **Audio:** generated clips contain only quiet sound effects. They have no music, singing, speech, lip-sync or animal voices, so the Tamil song (with its quack, woof and ribbit) is the only music and voice in the final video. If you would like Flow to add music for vibes anyway, delete the "no music" part of the audio line in the global lock.
- **Characters:** five invented characters: Arun (boy), Meena (girl), Vaathu (yellow duckling with a blue scarf), Kutty (golden-brown puppy with red collar and bell), Thavalai (green frog with a lotus-petal hat). The scarf, collar and petal hat are small accessories that help Flow keep each character consistent.
- **Image generation is Google Flow only.** Generate the 5 character sheets first, then each scene image in order. Video prompts use each scene's saved image as the starting frame.
- **Continuity chain:** every Step 3 prompt lists the previous scene's saved image as its continuity reference, for character look and colour grade only; the location must be new every time.
- **Lyrics:** the "Song sync" lines use the lyrics you pasted (corrected Tamil), with the timestamps taken from your transcript. The auto-transcript's mis-hearings are ignored.
- **Reminder:** the GLOBAL LOCK BLOCK must be appended in full to the end of every prompt (Step 1, every Step 3 and every Step 4) before submission.
