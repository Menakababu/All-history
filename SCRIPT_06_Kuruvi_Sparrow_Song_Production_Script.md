# SCRIPT 06 — குருவி, குருவி (Sparrow, Sparrow): a singing and dancing song with Mani and Mullai
### [TEMPLATE v3 — Google Flow only · song slots of 4/6 s, Flow clips generated at 8 s · character and prop sheets → a different village spot per scene → per-scene reference image → per-scene video · global lock appended to every prompt · no on-screen text · consistent visible faces · children lip-sync the Tamil lyrics, dancing in every scene]

**Duration:** about 0:50 (song ≈ 47–50 s, not attached; estimated) | **Total Scenes:** 16 = 16 reference images = 16 videos (10 timed scenes + 6 bonus dance scenes)
**Image generation:** Google Flow only (Step 1 sheets, Step 2 location plan, Step 3 scene reference images)
**Video generation:** Google Flow — one video prompt per scene, each generated as an 8 s clip (a 4 s or 6 s song slot plus spare seconds to trim)
**Payoff:** The children and the little sparrow dance together across the village, and the sparrow flies off into the sunset with its grain as the children wave goodbye.
**Dialogue/Audio rule:** For this song the children DO sing on screen. Each video prompt contains the exact Tamil line for the singing child, so the lips move to the words, and Flow generates only that sung voice. Your recorded song replaces it in the edit.

**Assumptions made for the blank input fields (change if needed):**
- **Style:** 3D animated family-film look (bright, cheerful, child-friendly). Tell me if you want 2D cartoon instead.
- **Characters:** the boy Mani, the girl Mullai and the sparrow Kuruvi (a stylised sparrow with a paddy-grain beak, a gooseberry-round head and a guava-round body, as in the lyrics), plus a woven grain tray.
- **Hard rules:** no on-screen text or lyrics; one child sings at a time; the sparrow only dances.
- **Song length:** estimated; the audio was not attached.

**Segment map**

| # | Segment | Scenes | Time |
|---|---|---|---|
| 1 | Intro: the village and the grain tray | S001–S002 | 0:00–0:10 |
| 2 | Call the sparrow: come near, take the grain | S003–S004 | 0:10–0:20 |
| 3 | Describing the sparrow: paddy beak, gooseberry head, guava body | S005–S006 | 0:20–0:30 |
| 4 | Lively and flying; the refrain and the farewell | S007–S010 | 0:30–0:50 |
| 5 | Bonus dance and lip-sync scenes (the refrain; use anywhere in the edit) | S011–S016 | bonus (no timestamp) |

---

## ⚠️ GLOBAL LOCK BLOCK — append this in full to the END of every single prompt below (Step 1, every Step 3, every Step 4)

```
GLOBAL LOCK:
CONTINUITY — Keep Mani (boy: white shirt, red checked half-pant), Mullai (girl: yellow pattu pavadai, long plait with jasmine), Kuruvi (the plump sparrow with a golden paddy-grain beak, a round gooseberry-tinted head and a guava-tinted round body) and the woven grain tray in exact face, colour, clothing and proportion continuity from their saved reference sheets — no redesign, recolor or scale drift. Every scene takes place in its own different spot of the same sunny Tamil village: thatched and mud-wall houses, coconut palms, paddy fields, warm light. Never copy the previous scene's spot, background or composition.
CAST RULE — Every scene shows exactly Mani, Mullai and the sparrow Kuruvi, all dancing. No other people, no other birds or animals.
STYLE — 3D animated family-film style, bright cheerful colours, soft global illumination, a warm 35mm-lens depth of field, one consistent colour grade (sunny gold, fresh paddy green, sky blue), smooth appealing character animation with natural squash and stretch, big expressive faces and joyful dance moves that land exactly on the beat of a lively children's song.
LIP-SYNC RULE — In every scene with a lip-sync line, exactly ONE child sings (the other dances and claps with a closed smile). The singing child's lips, jaw and cheeks follow the syllables of the given Tamil line exactly, with clear open-and-close mouth shapes in time with the beat, the head bobbing slightly with the rhythm. The sparrow never sings: it dances (hops, flaps, tilts its head) with its beak closed.
HARD RULES — No on-screen text, captions, lyrics, logos or watermarks. Fully child-friendly: no scary or dangerous content. The children always have clear, fully visible, expressive faces matching their sheets in every shot; faces never morph between shots, and the mouth always stays clearly visible to the camera when singing.
ZERO AI ARTIFACTS — No morphing, warping, melting, flicker, extra or duplicated limbs, wings, beaks or characters, floating debris, texture smearing, distorted hands or feet, wrong or extra teeth.
LIGHTING — Follow the time of day and light written in each scene's prompt; no sudden unintended light jumps inside a shot.
AUDIO — In scenes with a lip-sync line, the generated audio is ONLY the singing child's voice singing that exact line (so the lips move to real syllables); no background music, no other voices, no sparrow chirps. In scenes without a lip-sync line, no sound except very quiet footsteps and ambience. The recorded Tamil song is added in the edit and replaces the generated voice.
CAMERA — Smooth, physically plausible motion only; each shot's opening camera motion matches the previous shot's closing motion vector for a seamless cut.
```

---

# STEP 1 — CHARACTER & PROP REFERENCE IMAGES (Google Flow — image generation ONLY)

### 1A. Boy ("Mani")
**Portrait Image Prompt — Google Flow:**
Full-body portrait of a 7-year-old Tamil boy named Mani standing in a happy relaxed pose, facing the camera, with a clearly visible, fully expressive animated face with a clear mouth ready to sing: warm brown skin, round cheeks, big dark sparkling eyes, short black hair with a small cowlick, a cheeky wide grin. A white short-sleeved shirt, a red checked half-pant, bare feet. 3D animated family-film style, bright cheerful colours, soft global illumination. Neutral light-grey background, soft key light, clean readable shapes. Locked reference design.
**Save as:** `Mani_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Mani_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile, and one with the mouth open mid-song) locking the face.
**Save as:** `Mani_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S001–S016.

### 1B. Girl ("Mullai")
**Portrait Image Prompt — Google Flow:**
Full-body portrait of a 7-year-old Tamil girl named Mullai standing in a happy relaxed pose, facing the camera, with a clearly visible, fully expressive animated face with a clear mouth ready to sing: medium-brown skin, rosy cheeks, big bright brown eyes, a long black plait tied with a bunch of white jasmine flowers, a sweet wide smile. A bright yellow pattu pavadai (silk skirt and blouse) with a red border, small gold earrings, bare feet. 3D animated family-film style, bright cheerful colours, soft global illumination. Neutral light-grey background, soft key light. Locked reference design.
**Save as:** `Mullai_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Mullai_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up face panels (front, left profile, right profile, and one with the mouth open mid-song) locking the face.
**Save as:** `Mullai_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S001–S016.

### 1C. Sparrow ("Kuruvi")
**Portrait Image Prompt — Google Flow:**
A cute plump sparrow named Kuruvi perched on a branch in a lively pose, with a clearly visible, fully expressive animated face: big round black eyes with highlights, a small pointed golden-cream beak shaped like a grain of paddy, a perfectly round head with a soft pale yellow-green gooseberry tint, and a plump round body in warm brown with a soft light-green guava-tinted chest, a small tuft of tail feathers. Soft feather detail. 3D animated family-film style, bright cheerful colours, soft global illumination. Neutral light-grey background, soft key light. Locked reference design.
**Save as:** `Kuruvi_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Kuruvi_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up head panels (front, left profile, right profile) locking the face.
**Save as:** `Kuruvi_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S001–S016.

### 1D. Grain Tray (prop) ("GrainTray")
**Portrait Image Prompt — Google Flow:**
A round woven bamboo winnowing tray holding a small heap of pale broken rice grains (kurunoy) with a few whole golden paddy grains on top, shown on a plain surface. 3D animated family-film style, bright cheerful colours, soft global illumination. Neutral light-grey background, soft key light. Locked reference design.
**Save as:** `GrainTray_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `GrainTray_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral light-grey background, matched lighting/scale, neutral pose in every panel. Add a second row of close-up detail panels.
**Save as:** `GrainTray_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S001–S016.

---

# STEP 2 — LOCATION PLAN (no reusable environment plates: every scene is a different spot of the same village)

There are no shared environment-plate images. Each scene's Step 3 prompt describes its own spot, and `Environment Reference Image` is `none`. All spots belong to the same sunny Tamil village, so the look stays consistent. Several spots match the lyrics (the paddy field for the paddy-like beak, the gooseberry tree for the gooseberry head, the guava orchard for the guava body). The table lists every spot so you can check none repeats.

| Scene | Time | Slot | Flow clip | Unique location |
|---|---|---|---|---|
| S001 | 0:00–0:04 | 4s | 8 s | A village at sunrise with coconut palms, thatched roofs and paddy fields |
| S002 | 0:04–0:10 | 6s | 8 s | The front yard of a thatched house with a mango tree |
| S003 | 0:10–0:14 | 4s | 8 s | Stone veranda steps of a village house with a rangoli |
| S004 | 0:14–0:20 | 6s | 8 s | A banyan-shaded courtyard with a rope swing |
| S005 | 0:20–0:26 | 6s | 8 s | A golden paddy-field edge with a gooseberry tree |
| S006 | 0:26–0:30 | 4s | 8 s | A guava orchard in cool green shade |
| S007 | 0:30–0:34 | 4s | 8 s | A flowery village lane with marigolds and a bullock cart |
| S008 | 0:34–0:40 | 6s | 8 s | A sunny rooftop terrace with kites and coconut fronds |
| S009 | 0:40–0:46 | 6s | 8 s | A hill meadow with wildflowers and a wide blue sky |
| S010 | 0:46–0:50 | 4s | 8 s | A village garden gate at sunset with fireflies starting |
| S011 | bonus (no timestamp) | none | 8 s | A village temple courtyard with a flag pole |
| S012 | bonus (no timestamp) | none | 8 s | A bamboo grove clearing with sacks of grain |
| S013 | bonus (no timestamp) | none | 8 s | A riverside with a wooden boat and reeds |
| S014 | bonus (no timestamp) | none | 8 s | A flower garden with a butterfly arch |
| S015 | bonus (no timestamp) | none | 8 s | A mud-wall house backyard with a hanging cradle |
| S016 | bonus (no timestamp) | none | 8 s | A school playground at golden hour with a slide |

---

# STEP 3 & STEP 4 — SCENES (song slots of 4 and 6 seconds; every Flow video is generated at 8 seconds; children lip-sync the Tamil lyrics)

**How each scene is shaped:**
Header line (scene number, label, time range and slot) → **Song sync** (editor note only) → Step 3 Ingredients → Step 3 Reference Image Prompt → Step 4 Ingredients → Video Prompt (Google Flow, generated at 8 s; second marks relative to the clip start; the **Lip-sync line** gives the exact Tamil words and their sounds for the singing child) → Sound → Cut→.
Unlike the earlier songs, the lyrics ARE written inside the video prompts here, because this video needs the lips to move to the words. Append the GLOBAL LOCK BLOCK to the end of every Step 3 and Step 4 prompt.

---

### Segment 1 — Intro: the village and the grain tray (Scenes 1–2) | 0:00–0:10

**S001 — A village wakes up, a sparrow far away | 0:00–0:04 (4s slot → generate 8s in Flow)**
Song sync: (0:00) "(அறிமுகம் / இசை; பாடல் 0:10-க்குத் தொடங்குகிறது)"
Step 3 Ingredients: Character & Prop Reference Images: `Mani_Portrait.png`, `Mani_6Angle.png`, `Mullai_Portrait.png`, `Mullai_6Angle.png`, `Kuruvi_Portrait.png`, `Kuruvi_6Angle.png`, `GrainTray_Portrait.png`, `GrainTray_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A village at sunrise with coconut palms, thatched roofs and paddy fields) · Scene Continuity Reference: none (first scene in the series)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot at sunrise over a village with coconut palms, thatched roofs and golden paddy fields: the boy Mani and the girl Mullai standing together in a front-yard clearing bouncing on their toes with big smiles, holding a woven grain tray between them, and a tiny sparrow Kuruvi fluttering high in the sunny sky above, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S001_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S001_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the lyric beats, the last 4s are spare footage):
I2V from `S001_Ref.png`. 0–2s: the camera swoops down over the village toward the children as they bounce on the beat and lift the grain tray; 2–4s: the children sway side to side together and point up at the tiny sparrow circling in the sky. 4–8s (spare 4s): the same gentle dance motion continues and settles into a calm happy hold with no new action and no more singing, so the clip can be trimmed back to the 4s slot or stretched. Audio: very quiet footsteps and ambience only; the song is added in the edit.
Sound: very quiet footsteps and ambience; no music
Cut→S002: Cut to the front yard.

**S002 — Dancing in the yard, waiting for the sparrow | 0:04–0:10 (6s slot → generate 8s in Flow)**
Song sync: (0:04) "(இசை / அறிமுகம்)"
Step 3 Ingredients: Character & Prop Reference Images: `Mani_Portrait.png`, `Mani_6Angle.png`, `Mullai_Portrait.png`, `Mullai_6Angle.png`, `Kuruvi_Portrait.png`, `Kuruvi_6Angle.png`, `GrainTray_Portrait.png`, `GrainTray_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: The front yard of a thatched house with a mango tree) · Scene Continuity Reference: `S001_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Medium shot in the front yard of a thatched village house with a mango tree and a swept-earth ground: the boy Mani and the girl Mullai dancing side by side with matching steps, holding the woven grain tray of broken rice grains between them, happy faces turned up to the sky where the sparrow Kuruvi is gliding down toward them, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S002_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S002_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the lyric beats, the last 2s are spare footage):
I2V from `S002_Ref.png`. 0–2s: the children start a matching two-step dance on the beat, swinging the tray gently side to side; 2–4s: they clap together, spin once and look up as the sparrow glides lower; 4–6s: the sparrow lands on a low mango branch and the children freeze in a delighted pose. 6–8s (spare 2s): the same gentle dance motion continues and settles into a calm happy hold with no new action and no more singing, so the clip can be trimmed back to the 6s slot or stretched. Audio: very quiet footsteps and ambience only; the song is added in the edit.
Sound: very quiet footsteps and ambience; no music
Cut→S003: Cut to the veranda steps.

---

### Segment 2 — Call the sparrow: come near, take the grain (Scenes 3–4) | 0:10–0:20

**S003 — Sparrow, sparrow, come near | 0:10–0:14 (4s slot → generate 8s in Flow)**
Song sync: (0:10) "குருவி, குருவி, அருகில் வா" · (0:13) "குறுநொய் தருவேன்…"
Step 3 Ingredients: Character & Prop Reference Images: `Mani_Portrait.png`, `Mani_6Angle.png`, `Mullai_Portrait.png`, `Mullai_6Angle.png`, `Kuruvi_Portrait.png`, `Kuruvi_6Angle.png`, `GrainTray_Portrait.png`, `GrainTray_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: Stone veranda steps of a village house with a rangoli) · Scene Continuity Reference: `S002_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Medium shot on the stone veranda steps of a village house with a colourful rangoli on the floor: the girl Mullai in the foreground with her mouth open mid-song and her hand beckoning toward the camera, the boy Mani beside her dancing with a grain tray, and the sparrow Kuruvi hopping on the step toward them, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S003_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S003_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the lyric beats, the last 4s are spare footage):
I2V from `S003_Ref.png`. 0–2s: Mullai sings and beckons with her hand on the beat while Mani bounces and sways with the tray; 2–4s: the sparrow hops closer on the step in rhythm and tilts its head as Mullai holds out her arms. Lip-sync line: Mullai sings exactly «குருவி, குருவி, அருகில் வா, குறுநொய்…» (sounds: kuruvi, kuruvi, arugil vaa, kurunoy), mouth shapes matching every syllable. 4–8s (spare 4s): the same gentle dance motion continues and settles into a calm happy hold with no new action and no more singing, so the clip can be trimmed back to the 4s slot or stretched. Audio: only the singing child's voice singing exactly the line above in a sweet, cheerful child's voice at a lively tempo, no background music, no other voices, no sparrow chirps; this sung audio is for lip timing and will be muted and replaced by the recorded song in the edit.
Sound: the singing child's voice singing the Lip-sync line, nothing else; the song replaces it in the edit
Cut→S004: Cut to the banyan courtyard.

**S004 — I will give you grain, take it and go | 0:14–0:20 (6s slot → generate 8s in Flow)**
Song sync: (0:14) "…தருவேன் வாங்கிப் போ" · (0:15) "குருவி, குருவி, அருகில் வா" · (0:18) "குறுநொய் தருவேன்"
Step 3 Ingredients: Character & Prop Reference Images: `Mani_Portrait.png`, `Mani_6Angle.png`, `Mullai_Portrait.png`, `Mullai_6Angle.png`, `Kuruvi_Portrait.png`, `Kuruvi_6Angle.png`, `GrainTray_Portrait.png`, `GrainTray_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A banyan-shaded courtyard with a rope swing) · Scene Continuity Reference: `S003_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Medium shot in a courtyard under a huge banyan tree with a rope swing: the boy Mani in the foreground with his mouth open mid-song holding out a handful of grain, the girl Mullai beside him swaying with the tray, and the sparrow Kuruvi landing on the swing rope, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S004_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S004_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the lyric beats, the last 2s are spare footage):
I2V from `S004_Ref.png`. 0–2s: Mani sings and offers the grain with an open palm while Mullai sways on the beat; 2–4s: the sparrow hops along the swing rope and Mani and Mullai step side to side together; 4–6s: Mani sings the repeat with a bigger arm sweep as the sparrow flaps its wings in rhythm. Lip-sync line: Mani sings exactly «(…தருவேன்) வாங்கிப் போ. குருவி, குருவி, அருகில் வா, குறுநொய் தருவேன்» (sounds: (…tharuven) vaangip po. kuruvi, kuruvi, arugil vaa, kurunoy tharuven), mouth shapes matching every syllable. 6–8s (spare 2s): the same gentle dance motion continues and settles into a calm happy hold with no new action and no more singing, so the clip can be trimmed back to the 6s slot or stretched. Audio: only the singing child's voice singing exactly the line above in a sweet, cheerful child's voice at a lively tempo, no background music, no other voices, no sparrow chirps; this sung audio is for lip timing and will be muted and replaced by the recorded song in the edit.
Sound: the singing child's voice singing the Lip-sync line, nothing else; the song replaces it in the edit
Cut→S005: Cut to the paddy field.

---

### Segment 3 — Describing the sparrow: paddy beak, gooseberry head, guava body (Scenes 5–6) | 0:20–0:30

**S005 — A beak like paddy, a head like a gooseberry | 0:20–0:26 (6s slot → generate 8s in Flow)**
Song sync: (0:20) "…வாங்கிப் போ" · (0:21) "நெல்லைப் போன்ற உன் மூக்கும்" · (0:23) "நெல்லிக் காய்போல் உன் தலையும்"
Step 3 Ingredients: Character & Prop Reference Images: `Mani_Portrait.png`, `Mani_6Angle.png`, `Mullai_Portrait.png`, `Mullai_6Angle.png`, `Kuruvi_Portrait.png`, `Kuruvi_6Angle.png`, `GrainTray_Portrait.png`, `GrainTray_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A golden paddy-field edge with a gooseberry tree) · Scene Continuity Reference: `S004_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Medium shot at the edge of a golden paddy field beside a gooseberry tree full of small pale-green fruits: the girl Mullai with her mouth open mid-song pointing gently at the sparrow's beak, the boy Mani dancing beside her, and the sparrow Kuruvi perched on a paddy stalk with its golden beak and round head turned toward them, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S005_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S005_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the lyric beats, the last 2s are spare footage):
I2V from `S005_Ref.png`. 0–2s: Mullai sings and points a finger toward the sparrow's beak on the beat while Mani bounces; 2–4s: the sparrow tilts its round head and Mani points at its head and then at a gooseberry on the tree; 4–6s: the children twirl together as the sparrow hops along the stalks. Lip-sync line: Mullai sings exactly «(வாங்கிப் போ.) நெல்லைப் போன்ற உன் மூக்கும், நெல்லிக் காய்போல் உன் தலையும்» (sounds: (vaangip po.) nellaip ponra un mookkum, nellik kaay pol un thalaiyum), mouth shapes matching every syllable. 6–8s (spare 2s): the same gentle dance motion continues and settles into a calm happy hold with no new action and no more singing, so the clip can be trimmed back to the 6s slot or stretched. Audio: only the singing child's voice singing exactly the line above in a sweet, cheerful child's voice at a lively tempo, no background music, no other voices, no sparrow chirps; this sung audio is for lip timing and will be muted and replaced by the recorded song in the edit.
Sound: the singing child's voice singing the Lip-sync line, nothing else; the song replaces it in the edit
Cut→S006: Cut to the guava orchard.

**S006 — A body like a tender guava | 0:26–0:30 (4s slot → generate 8s in Flow)**
Song sync: (0:26) "கொய்யாப் பிஞ்சைப் போல் உடலும்" · (0:28) "குழந்தை இடத்தில்…"
Step 3 Ingredients: Character & Prop Reference Images: `Mani_Portrait.png`, `Mani_6Angle.png`, `Mullai_Portrait.png`, `Mullai_6Angle.png`, `Kuruvi_Portrait.png`, `Kuruvi_6Angle.png`, `GrainTray_Portrait.png`, `GrainTray_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A guava orchard in cool green shade) · Scene Continuity Reference: `S005_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Medium shot in a guava orchard in cool green shade with small round green guavas on the branches: the boy Mani with his mouth open mid-song holding a tiny guava next to the sparrow for comparison, the girl Mullai dancing beside him, and the sparrow Kuruvi perched on a low branch with its plump round body, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S006_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S006_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the lyric beats, the last 4s are spare footage):
I2V from `S006_Ref.png`. 0–2s: Mani sings and holds the tiny guava up next to the sparrow's round body on the beat while Mullai sways; 2–4s: both children spin around and bounce as the sparrow fluffs its chest and hops on the branch. Lip-sync line: Mani sings exactly «கொய்யாப் பிஞ்சைப் போல் உடலும், குழந்தை இடத்தில்…» (sounds: koyyap pinjaip pol udalum, kuzhandhai idaththil), mouth shapes matching every syllable. 4–8s (spare 4s): the same gentle dance motion continues and settles into a calm happy hold with no new action and no more singing, so the clip can be trimmed back to the 4s slot or stretched. Audio: only the singing child's voice singing exactly the line above in a sweet, cheerful child's voice at a lively tempo, no background music, no other voices, no sparrow chirps; this sung audio is for lip timing and will be muted and replaced by the recorded song in the edit.
Sound: the singing child's voice singing the Lip-sync line, nothing else; the song replaces it in the edit
Cut→S007: Cut to a flowery lane.

---

### Segment 4 — Lively and flying; the refrain and the farewell (Scenes 7–10) | 0:30–0:50

**S007 — Come to where the children are; so lively! | 0:30–0:34 (4s slot → generate 8s in Flow)**
Song sync: (0:30) "…காட்ட வா" · (0:31) "சுறுசுறுப்புப் பிள்ளை நீ" · (0:33) "சோம்பல் என்றும் இல்லையே"
Step 3 Ingredients: Character & Prop Reference Images: `Mani_Portrait.png`, `Mani_6Angle.png`, `Mullai_Portrait.png`, `Mullai_6Angle.png`, `Kuruvi_Portrait.png`, `Kuruvi_6Angle.png`, `GrainTray_Portrait.png`, `GrainTray_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A flowery village lane with marigolds and a bullock cart) · Scene Continuity Reference: `S006_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Medium shot along a flowery village lane lined with marigolds and a parked wooden bullock cart: the girl Mullai with her mouth open mid-song waving the sparrow toward them, the boy Mani dancing with energetic steps, and the sparrow Kuruvi hopping along the lane toward them, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S007_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S007_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the lyric beats, the last 4s are spare footage):
I2V from `S007_Ref.png`. 0–2s: Mullai sings and waves the sparrow in with her arm sweeping on the beat while Mani dances with quick steps; 2–4s: they clap and spin as the sparrow hops quickly in a lively zigzag between them. Lip-sync line: Mullai sings exactly «(…காட்ட வா.) சுறுசுறுப்புப் பிள்ளை நீ, சோம்பல் என்றும்…» (sounds: (…kaatta vaa.) surusuruppup pillai nee, sombal endrum), mouth shapes matching every syllable. 4–8s (spare 4s): the same gentle dance motion continues and settles into a calm happy hold with no new action and no more singing, so the clip can be trimmed back to the 4s slot or stretched. Audio: only the singing child's voice singing exactly the line above in a sweet, cheerful child's voice at a lively tempo, no background music, no other voices, no sparrow chirps; this sung audio is for lip timing and will be muted and replaced by the recorded song in the edit.
Sound: the singing child's voice singing the Lip-sync line, nothing else; the song replaces it in the edit
Cut→S008: Cut to the terrace.

**S008 — Flying and flying, bring us a song | 0:34–0:40 (6s slot → generate 8s in Flow)**
Song sync: (0:34) "…இல்லையே" · (0:35) "பறந்து பறந்து செல்லுவாய்" · (0:38) "பாட்டு ஒன்று சொல்லுவாய்"
Step 3 Ingredients: Character & Prop Reference Images: `Mani_Portrait.png`, `Mani_6Angle.png`, `Mullai_Portrait.png`, `Mullai_6Angle.png`, `Kuruvi_Portrait.png`, `Kuruvi_6Angle.png`, `GrainTray_Portrait.png`, `GrainTray_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A sunny rooftop terrace with kites and coconut fronds) · Scene Continuity Reference: `S007_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Medium shot on a sunny rooftop terrace with colourful kites and coconut fronds overhead: the boy Mani with his mouth open mid-song and his arms spread like wings, the girl Mullai flapping her arms beside him, and the sparrow Kuruvi mid-flight just above them, wings spread, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S008_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S008_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the lyric beats, the last 2s are spare footage):
I2V from `S008_Ref.png`. 0–2s: Mani sings with arms spread and the sparrow swoops past; 2–4s: Mullai flaps her arms in rhythm and both children run a small circle as the sparrow flies loops above them; 4–6s: they stretch their arms to the sky as the sparrow lifts up toward the kites. Lip-sync line: Mani sings exactly «(…இல்லையே.) பறந்து பறந்து செல்லுவாய், பாட்டு ஒன்று சொல்லுவாய்» (sounds: (…illaiye.) parandhu parandhu selluvaai, paattu ondru solluvaai), mouth shapes matching every syllable. 6–8s (spare 2s): the same gentle dance motion continues and settles into a calm happy hold with no new action and no more singing, so the clip can be trimmed back to the 6s slot or stretched. Audio: only the singing child's voice singing exactly the line above in a sweet, cheerful child's voice at a lively tempo, no background music, no other voices, no sparrow chirps; this sung audio is for lip timing and will be muted and replaced by the recorded song in the edit.
Sound: the singing child's voice singing the Lip-sync line, nothing else; the song replaces it in the edit
Cut→S009: Cut to the hill meadow.

**S009 — Come near again, the refrain | 0:40–0:46 (6s slot → generate 8s in Flow)**
Song sync: (0:40) "…சொல்லுவாய்" · (0:41) "குருவி, குருவி, அருகில் வா" · (0:44) "குறுநொய் தருவேன்"
Step 3 Ingredients: Character & Prop Reference Images: `Mani_Portrait.png`, `Mani_6Angle.png`, `Mullai_Portrait.png`, `Mullai_6Angle.png`, `Kuruvi_Portrait.png`, `Kuruvi_6Angle.png`, `GrainTray_Portrait.png`, `GrainTray_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A hill meadow with wildflowers and a wide blue sky) · Scene Continuity Reference: `S008_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot on a hill meadow with wildflowers and a wide blue sky: the girl Mullai and the boy Mani holding hands and dancing in a circle with big smiles, Mullai's mouth open mid-song, and the sparrow Kuruvi flying a loop around them, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S009_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S009_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the lyric beats, the last 2s are spare footage):
I2V from `S009_Ref.png`. 0–2s: the children hold hands and skip in a circle on the beat as the sparrow circles them; 2–4s: Mullai sings and lifts the grain tray with one hand while Mani spins; 4–6s: the sparrow lands on the tray and they bounce together in a happy hold. Lip-sync line: Mullai sings exactly «(…சொல்லுவாய்.) குருவி, குருவி, அருகில் வா, குறுநொய் தருவேன்» (sounds: (…solluvaai.) kuruvi, kuruvi, arugil vaa, kurunoy tharuven), mouth shapes matching every syllable. 6–8s (spare 2s): the same gentle dance motion continues and settles into a calm happy hold with no new action and no more singing, so the clip can be trimmed back to the 6s slot or stretched. Audio: only the singing child's voice singing exactly the line above in a sweet, cheerful child's voice at a lively tempo, no background music, no other voices, no sparrow chirps; this sung audio is for lip timing and will be muted and replaced by the recorded song in the edit.
Sound: the singing child's voice singing the Lip-sync line, nothing else; the song replaces it in the edit
Cut→S010: Cut to the garden gate at sunset.

**S010 — Take it and go: the happy ending | 0:46–0:50 (4s slot → generate 8s in Flow)**
Song sync: (0:46) "…வாங்கிப் போ" · (0:47) "(முடிவு; ஆடியோ நீளம் மதிப்பீடு)"
Step 3 Ingredients: Character & Prop Reference Images: `Mani_Portrait.png`, `Mani_6Angle.png`, `Mullai_Portrait.png`, `Mullai_6Angle.png`, `Kuruvi_Portrait.png`, `Kuruvi_6Angle.png`, `GrainTray_Portrait.png`, `GrainTray_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A village garden gate at sunset with fireflies starting) · Scene Continuity Reference: `S009_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot at a village garden gate at sunset with soft fireflies starting: the boy Mani and the girl Mullai standing together waving, Mullai's mouth open on the last word, the sparrow Kuruvi perched on top of the wooden gate with a grain in its beak, golden-orange sky, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S010_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S010_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the lyric beats, the last 4s are spare footage):
I2V from `S010_Ref.png`. 0–1s: the children sing the last word and wave on the beat; 1–3s: the sparrow flaps its wings, takes off from the gate with the grain and flies off toward the sunset as the children wave and cheer; 3–4s: the children give a final thumbs-up and the camera pulls back as the fireflies glow. Lip-sync line: Mullai sings exactly «(…தருவேன்) வாங்கிப் போ» (sounds: (…tharuven) vaangip po), mouth shapes matching every syllable. 4–8s (spare 4s): the same gentle dance motion continues and settles into a calm happy hold with no new action and no more singing, so the clip can be trimmed back to the 4s slot or stretched. Audio: only the singing child's voice singing exactly the line above in a sweet, cheerful child's voice at a lively tempo, no background music, no other voices, no sparrow chirps; this sung audio is for lip timing and will be muted and replaced by the recorded song in the edit.
Sound: the singing child's voice singing the Lip-sync line, nothing else; the song replaces it in the edit
Cut→S011: END: the song ends; fade out over the last second.

---

### Segment 5 — Bonus dance and lip-sync scenes (the refrain; use anywhere in the edit) (Scenes 11–16)

**S011 — Bonus 1: duet dance | bonus, no timestamp (generate 8s in Flow)**
Song sync: the refrain «குருவி, குருவி, அருகில் வா, குறுநொய் தருவேன் வாங்கிப் போ». Cut it in over any of the three refrains (0:10, 0:15, 0:41) or as a cutaway.
Step 3 Ingredients: Character & Prop Reference Images: `Mani_Portrait.png`, `Mani_6Angle.png`, `Mullai_Portrait.png`, `Mullai_6Angle.png`, `Kuruvi_Portrait.png`, `Kuruvi_6Angle.png`, `GrainTray_Portrait.png`, `GrainTray_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A village temple courtyard with a flag pole) · Scene Continuity Reference: `S010_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot in a village temple courtyard with a stone flag pole and a sunlit stone floor: the boy Mani and the girl Mullai in a playful start pose with big smiles, Mullai's mouth open ready to sing, the grain tray in their hands and the sparrow Kuruvi beside them, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S011_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S011_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S011_Ref.png`. 0–6s: Mullai sings the refrain while the children and the sparrow dance, mirrored steps: Mani and Mullai stepping and clapping in perfect mirror to the beat; the moves land on the beat and the camera circles them gently; 6–8s: they strike a cheerful pose and the movement settles. Lip-sync line: Mullai sings exactly «குருவி, குருவி, அருகில் வா, குறுநொய் தருவேன் வாங்கிப் போ» (sounds: kuruvi, kuruvi, arugil vaa, kurunoy tharuven vaangip po), mouth shapes matching every syllable. Audio: only the singing child's voice singing exactly the line above in a sweet, cheerful child's voice at a lively tempo, no background music, no other voices, no sparrow chirps; this sung audio is for lip timing and will be muted and replaced by the recorded song in the edit.
Sound: the singing child's voice singing the Lip-sync line, nothing else; the song replaces it in the edit
Cut→S012: Use as a cutaway or loop anywhere in the edit.

**S012 — Bonus 2: sparrow hop-dance | bonus, no timestamp (generate 8s in Flow)**
Song sync: the refrain «குருவி, குருவி, அருகில் வா, குறுநொய் தருவேன் வாங்கிப் போ». Cut it in over any of the three refrains (0:10, 0:15, 0:41) or as a cutaway.
Step 3 Ingredients: Character & Prop Reference Images: `Mani_Portrait.png`, `Mani_6Angle.png`, `Mullai_Portrait.png`, `Mullai_6Angle.png`, `Kuruvi_Portrait.png`, `Kuruvi_6Angle.png`, `GrainTray_Portrait.png`, `GrainTray_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A bamboo grove clearing with sacks of grain) · Scene Continuity Reference: `S011_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot in a bamboo grove clearing with a few grain sacks: the boy Mani and the girl Mullai in a playful start pose with big smiles, Mullai's mouth open ready to sing, the grain tray in their hands and the sparrow Kuruvi beside them, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S012_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S012_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S012_Ref.png`. 0–6s: Mullai sings the refrain while the children and the sparrow dance, the sparrow hopping from sack to sack in rhythm while the children bounce and clap; the moves land on the beat and the camera circles them gently; 6–8s: they strike a cheerful pose and the movement settles. Lip-sync line: Mullai sings exactly «குருவி, குருவி, அருகில் வா, குறுநொய் தருவேன் வாங்கிப் போ» (sounds: kuruvi, kuruvi, arugil vaa, kurunoy tharuven vaangip po), mouth shapes matching every syllable. Audio: only the singing child's voice singing exactly the line above in a sweet, cheerful child's voice at a lively tempo, no background music, no other voices, no sparrow chirps; this sung audio is for lip timing and will be muted and replaced by the recorded song in the edit.
Sound: the singing child's voice singing the Lip-sync line, nothing else; the song replaces it in the edit
Cut→S013: Use as a cutaway or loop anywhere in the edit.

**S013 — Bonus 3: sprinkling grain | bonus, no timestamp (generate 8s in Flow)**
Song sync: the refrain «குருவி, குருவி, அருகில் வா, குறுநொய் தருவேன் வாங்கிப் போ». Cut it in over any of the three refrains (0:10, 0:15, 0:41) or as a cutaway.
Step 3 Ingredients: Character & Prop Reference Images: `Mani_Portrait.png`, `Mani_6Angle.png`, `Mullai_Portrait.png`, `Mullai_6Angle.png`, `Kuruvi_Portrait.png`, `Kuruvi_6Angle.png`, `GrainTray_Portrait.png`, `GrainTray_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A riverside with a wooden boat and reeds) · Scene Continuity Reference: `S012_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot in a riverside with a small wooden boat and reeds: the boy Mani and the girl Mullai in a playful start pose with big smiles, Mullai's mouth open ready to sing, the grain tray in their hands and the sparrow Kuruvi beside them, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S013_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S013_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S013_Ref.png`. 0–6s: Mullai sings the refrain while the children and the sparrow dance, sprinkling grain from the tray in time to the beat while the sparrow catches grains on the sand; the moves land on the beat and the camera circles them gently; 6–8s: they strike a cheerful pose and the movement settles. Lip-sync line: Mullai sings exactly «குருவி, குருவி, அருகில் வா, குறுநொய் தருவேன் வாங்கிப் போ» (sounds: kuruvi, kuruvi, arugil vaa, kurunoy tharuven vaangip po), mouth shapes matching every syllable. Audio: only the singing child's voice singing exactly the line above in a sweet, cheerful child's voice at a lively tempo, no background music, no other voices, no sparrow chirps; this sung audio is for lip timing and will be muted and replaced by the recorded song in the edit.
Sound: the singing child's voice singing the Lip-sync line, nothing else; the song replaces it in the edit
Cut→S014: Use as a cutaway or loop anywhere in the edit.

**S014 — Bonus 4: wings dance | bonus, no timestamp (generate 8s in Flow)**
Song sync: the refrain «குருவி, குருவி, அருகில் வா, குறுநொய் தருவேன் வாங்கிப் போ». Cut it in over any of the three refrains (0:10, 0:15, 0:41) or as a cutaway.
Step 3 Ingredients: Character & Prop Reference Images: `Mani_Portrait.png`, `Mani_6Angle.png`, `Mullai_Portrait.png`, `Mullai_6Angle.png`, `Kuruvi_Portrait.png`, `Kuruvi_6Angle.png`, `GrainTray_Portrait.png`, `GrainTray_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A flower garden with a butterfly arch) · Scene Continuity Reference: `S013_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot in a flower garden with a bright arch of climbing flowers and butterflies: the boy Mani and the girl Mullai in a playful start pose with big smiles, Mullai's mouth open ready to sing, the grain tray in their hands and the sparrow Kuruvi beside them, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S014_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S014_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S014_Ref.png`. 0–6s: Mullai sings the refrain while the children and the sparrow dance, flapping their arms like wings in a dance as the sparrow flaps beside them; the moves land on the beat and the camera circles them gently; 6–8s: they strike a cheerful pose and the movement settles. Lip-sync line: Mullai sings exactly «குருவி, குருவி, அருகில் வா, குறுநொய் தருவேன் வாங்கிப் போ» (sounds: kuruvi, kuruvi, arugil vaa, kurunoy tharuven vaangip po), mouth shapes matching every syllable. Audio: only the singing child's voice singing exactly the line above in a sweet, cheerful child's voice at a lively tempo, no background music, no other voices, no sparrow chirps; this sung audio is for lip timing and will be muted and replaced by the recorded song in the edit.
Sound: the singing child's voice singing the Lip-sync line, nothing else; the song replaces it in the edit
Cut→S015: Use as a cutaway or loop anywhere in the edit.

**S015 — Bonus 5: circle dance | bonus, no timestamp (generate 8s in Flow)**
Song sync: the refrain «குருவி, குருவி, அருகில் வா, குறுநொய் தருவேன் வாங்கிப் போ». Cut it in over any of the three refrains (0:10, 0:15, 0:41) or as a cutaway.
Step 3 Ingredients: Character & Prop Reference Images: `Mani_Portrait.png`, `Mani_6Angle.png`, `Mullai_Portrait.png`, `Mullai_6Angle.png`, `Kuruvi_Portrait.png`, `Kuruvi_6Angle.png`, `GrainTray_Portrait.png`, `GrainTray_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A mud-wall house backyard with a hanging cradle) · Scene Continuity Reference: `S014_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot in a mud-wall house backyard with a cloth cradle hanging from a tree: the boy Mani and the girl Mullai in a playful start pose with big smiles, Mullai's mouth open ready to sing, the grain tray in their hands and the sparrow Kuruvi beside them, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S015_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S015_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S015_Ref.png`. 0–6s: Mullai sings the refrain while the children and the sparrow dance, skipping hand in hand in a circle while the sparrow flies loops above them; the moves land on the beat and the camera circles them gently; 6–8s: they strike a cheerful pose and the movement settles. Lip-sync line: Mullai sings exactly «குருவி, குருவி, அருகில் வா, குறுநொய் தருவேன் வாங்கிப் போ» (sounds: kuruvi, kuruvi, arugil vaa, kurunoy tharuven vaangip po), mouth shapes matching every syllable. Audio: only the singing child's voice singing exactly the line above in a sweet, cheerful child's voice at a lively tempo, no background music, no other voices, no sparrow chirps; this sung audio is for lip timing and will be muted and replaced by the recorded song in the edit.
Sound: the singing child's voice singing the Lip-sync line, nothing else; the song replaces it in the edit
Cut→S016: Use as a cutaway or loop anywhere in the edit.

**S016 — Bonus 6: the playground finish | bonus, no timestamp (generate 8s in Flow)**
Song sync: the refrain «குருவி, குருவி, அருகில் வா, குறுநொய் தருவேன் வாங்கிப் போ». Cut it in over any of the three refrains (0:10, 0:15, 0:41) or as a cutaway.
Step 3 Ingredients: Character & Prop Reference Images: `Mani_Portrait.png`, `Mani_6Angle.png`, `Mullai_Portrait.png`, `Mullai_6Angle.png`, `Kuruvi_Portrait.png`, `Kuruvi_6Angle.png`, `GrainTray_Portrait.png`, `GrainTray_6Angle.png` · Environment Reference Image: none (unique spot, described in the prompt: A school playground at golden hour with a slide) · Scene Continuity Reference: `S015_Ref.png` (character and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot in a school playground at golden hour with a slide and a swing: the boy Mani and the girl Mullai in a playful start pose with big smiles, Mullai's mouth open ready to sing, the grain tray in their hands and the sparrow Kuruvi beside them, 3D animated family-film style, bright cheerful colours, soft global illumination.
Save as: `S016_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S016_Ref.png`
Video Prompt (Google Flow, generate 8s; use anywhere, trim or loop freely):
I2V from `S016_Ref.png`. 0–6s: Mullai sings the refrain while the children and the sparrow dance, striking a joyful final pose together with thumbs up as the sparrow lands on the grain tray; the moves land on the beat and the camera circles them gently; 6–8s: they strike a cheerful pose and the movement settles. Lip-sync line: Mullai sings exactly «குருவி, குருவி, அருகில் வா, குறுநொய் தருவேன் வாங்கிப் போ» (sounds: kuruvi, kuruvi, arugil vaa, kurunoy tharuven vaangip po), mouth shapes matching every syllable. Audio: only the singing child's voice singing exactly the line above in a sweet, cheerful child's voice at a lively tempo, no background music, no other voices, no sparrow chirps; this sung audio is for lip timing and will be muted and replaced by the recorded song in the edit.
Sound: the singing child's voice singing the Lip-sync line, nothing else; the song replaces it in the edit
Cut→Use as a cutaway or loop anywhere in the edit.

---

# PRODUCTION NOTES

- **Total required:** 16 reference images (`S001_Ref.png` … `S016_Ref.png`) and 16 videos, one video per image: 10 timed scenes that follow the song plus 6 bonus dance scenes. Plus the Step 1 sheets: 2 children, the sparrow and the grain tray, 4 portraits and 4 six-angle turnarounds (8 images). There are no environment-plate images. Overall: 16 scene images + 8 sheet images = 24 images, and 16 videos.
- **Song length:** your last timestamp is the refrain at 0:41. The audio length was not attached, so I assumed the song ends around 0:47–0:50 and made the timed scenes 50 s long (0:00–0:50). Send the audio length if it differs and I will adjust the last scene.
- **Song structure (from your timestamps):** 0:00–0:10 intro; 0:10 and 0:15 the refrain twice ("Kuruvi, kuruvi, arugil vaa, kurunoy tharuven vaangip po"); 0:21 "paddy beak, gooseberry head"; 0:26 "guava body, show up where the children are"; 0:31 "lively child, no laziness"; 0:35 "fly and fly, tell us a song"; 0:41 the refrain again. Clips use even seconds, so each cut falls up to 1 s before a line that starts on an odd second, and the first word of a line may sit at the end of the previous clip. Because every clip has spare footage, you can also place a clip at the exact odd second and trim the previous one.
- **Lyrics: script versus audio:** the lip-sync lines use your written script. Your auto-transcript heard two words differently: "குருணை" instead of "குறுநொய்" (both mean broken rice grains) and "பார்த்து வந்து" instead of "பாட்டு ஒன்று" at 0:35–0:41. If the singer actually sings the transcript's words, tell me and I'll change the lip-sync lines, because the mouth shapes must match the sung syllables.
- **Cast rule:** every scene shows exactly Mani, Mullai and the sparrow Kuruvi, all dancing. In every scene with a lip-sync line only ONE child sings (they alternate: Mullai in S003, S005, S007, S009, S010, Mani in S004, S006, S008) and the other dances with a closed smile; the sparrow never sings.
- **How lip-sync is handled (important):** Google Flow cannot take your recorded song as an input, so it cannot copy its exact sound onto the lips. These prompts do the next best thing. Each video prompt gives the child the exact Tamil words (with their sounds), so Flow animates a mouth that sings those syllables on the beat and generates a sung voice. Then in the edit you **mute Flow's voice and lay your recorded song over it**, nudging each clip by up to a second to line the syllables up with your audio. This usually looks close, but Tamil singing may drift or garble in a few clips. For a perfect match: (1) regenerate any weak clip a couple of times, using the spare seconds to find the best take, and (2) if you need frame-exact lips, run the final clips through an audio-driven lip-sync tool with your recorded song as the input (this is outside Flow). I cannot test Flow's current features from here, so please try one scene first (for example S003) before generating them all.
- **What to generate in Flow (8 s or 10 s only):** every video is generated at 8 s. All timed slots are 4 s or 6 s, so each clip has 2–4 s of spare footage after the lyric. The bonus scenes are 8 s and sing the full refrain. No scene needs 10 s.

| Generate in Flow | Number of videos | Footage | Scenes |
|---|---|---|---|
| 8 s | 16 | 128 s | all scenes S001–S016 |

- **Slot plan (timed scenes):** 4 s slots: S001, S003, S006, S007, S010 (5 clips, 20 s); 6 s slots: S002, S004, S005, S008, S009 (5 clips, 30 s); total 50 s.
- **Timeline rule:** put the song on the timeline at 0:00, drop each timed clip at its scene start time and trim it to its slot. The extra seconds are spare footage. The bonus scenes have no timestamp: use them as cutaways over any of the three refrains, or loop a verse to make a longer video.
- **Making it addictive:** the song's picture-words are acted out literally (a paddy-field for the paddy beak, a gooseberry tree for the gooseberry head, a guava orchard for the guava body), the sparrow dances in every scene, the children alternate as lead singer, and the dance gets bigger as the song builds, from yard steps to wing flaps, to a circle dance and a final wave.
- **Audio:** in scenes with a lip-sync line, Flow generates only the child's sung voice (no music, no sparrow chirps). In scenes without a lip-sync line (the intro), only very quiet ambience. Your recorded song replaces all generated sound in the edit.
- **Image generation is Google Flow only.** Generate the 4 sheets first (make sure the face rows show clear open and closed mouths), then each scene image in order. Video prompts use each scene's saved image as the starting frame. In each lip-sync scene's image, the singing child's mouth is open and clearly visible, which helps Flow animate the lips.
- **Reminder:** the GLOBAL LOCK BLOCK must be appended in full to the end of every prompt (Step 1, every Step 3 and every Step 4) before submission.
